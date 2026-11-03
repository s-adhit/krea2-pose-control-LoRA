# Krea-2 Pose Control for ComfyUI

Custom ComfyUI nodes for the Krea-2 Pose Control LoRA.

## Nodes

- `Krea2PoseExtractor` — reference image to PoseBridge pose condition
- `Krea2PoseCondition` — validates an existing PoseBridge condition
- `Krea2PoseGenerate` — pose-conditioned Krea-2 Turbo generation

## Example workflow

The recommended workflow is included at:

`example_workflows/krea2_pose_from_reference.json`

It follows:

`Reference Image -> DWPose -> PoseBridge -> Krea-2 Pose Control -> Generated Image`

## Requirements

Install the dependencies from `requirements.txt`.

The default pose extractor also requires
[ComfyUI-ControlNet-Aux](https://github.com/Fannovel16/comfyui_controlnet_aux)
for DWPose.

## Models

- Krea-2 Turbo
- Krea-2 Pose Control LoRA:
  https://huggingface.co/adhit-420/Krea-2-PoseControl-LoRA-checkpoints

For complete installation instructions, model paths, and workflow details see:

https://github.com/s-adhit/krea2-pose-controlnet/tree/main/comfyui
