moge-2-vits-int8.onnx
  MoGe-2 ViT-S "normal" (Microsoft), the ONNX export published by its authors at
  https://huggingface.co/Ruicheng/moge-2-vits-normal-onnx (model.onnx, 140,852,051 bytes),
  with its MatMul weights quantised to 8 bits by ONNX Runtime's quantize_dynamic
  (weight_type=QUInt8, op_types_to_quantize=["MatMul"]). No other change.
  Licence: see LICENSE-MoGe.txt (MIT, with Apache-2.0 text for parts derived from DINOv2).
  Source code: https://github.com/microsoft/MoGe
  SHA-256: d9a25592430075578d41db192b3ab43c69a7c353e4a5069957849e44c625827c
Used by the studio's "Start from a photo" to estimate depth on the visitor's own device.
