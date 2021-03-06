# DL_attachable_enhance_methods
Deep Learning attachable method to enhance model in my subjective. (Growing!😇)


## Training - model centric
- basic methods(drop out, weight decay, batch normalization) 
- An inverse relationship between batch size & learning late (relative link)
- 
- Linear Warmup & Cosine Annealing 
- Label Smoothing
- optuna, hyperparameter optimization (https://www.kaggle.com/code/tyrionlannisterlzy/jpx-lgbm-model-auto-search-para)

## Training - data centric
- Fixing the train-test resolution discrepancy(FixRes) (paper link) (repository link) (subjective readme link)
- Augmentations (subjective readme link: opencv, etc-> aug없이 먼저 학습 후 aug포함해서 fine-tuning. 상황에 따른 Weight decay 선적용/후적용?)
- - 높은 Weight Decay 학습 시 : 더 빠르게 수렴하나, 최종적으로 더 낮은 성능으로 수렴 

      낮은 Weight Decay 학습 시 : 수렴은 느리나, 최종적으로 더 좋은 성능으로 수렴

## Inference(Test)

## optimization & lightening
- Quantization with tflite (tflite doc link)
- TensorRT(TensorRT link) -> for GPU
- Convert to Onnx(Onnx link) and dynamic&static quantization
- Web-Client side edge computing with tfjs, OpenGL
- pruning

## Useful Toolkit(site)
- My quickstarters
- Timm: Pytorch pretrained model library
- Huggingface: NLP pretrained model library
- Firebase: mobile models platform
- pytorch lightening
- pytorch geometric
- mediapipe: lite models for mobile devices & small cpu runtime

## Visualization
- gradcam(heatmap)

## Deploying
- Torchserve
- Kserve
