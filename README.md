# faceswap_insightface_inswapper
Introduction to deepfake face swap in pictures using only python and open source libraries.

Steps:

1. Install Insightface, ONNX Runtime, opencv
2. Use Insightface faceanalysing model to detect faces in both source and target frame
3. Use Inswapper from Huggingface to swap faces

Explainer video on youtube:
[https://youtu.be/Ju_reA3zQso](https://www.youtube.com/watch?v=Ju_reA3zQso)

Insightface: 
https://insightface.ai/

CMake (Windows): 
https://cmake.org/download/

C++ build tools (Windows): 
https://visualstudio.microsoft.com/visual-cpp-build-tools/

ONNX Runtime: 
https://onnxruntime.ai/

Insightface model for faceanalysis: 
https://github.com/deepinsight/insightface/tree/master/model_zoo

HuggingFace inswapper model:
https://huggingface.co/countfloyd/deepfake/resolve/main/inswapper_128.onnx
