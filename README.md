# DL_attachable_enhance_methods
Deep Learning attachable method to enhance model in my subjective. (Growing!ð)


## Training - model centric
- basic methods(drop out, weight decay, batch normalization) 
- An inverse relationship between batch size & learning late (relative link)
- 
- Linear Warmup & Cosine Annealing 
- Label Smoothing
- optuna, hyperparameter optimization (https://www.kaggle.com/code/tyrionlannisterlzy/jpx-lgbm-model-auto-search-para)

## Training - data centric
- Fixing the train-test resolution discrepancy(FixRes) (paper link) (repository link) (subjective readme link)
- Augmentations (subjective readme link: opencv, etc-> augìì´ ë¨¼ì  íìµ í augí¬í¨í´ì fine-tuning. ìí©ì ë°ë¥¸ Weight decay ì ì ì©/íì ì©?)
- - ëì Weight Decay íìµ ì : ë ë¹ ë¥´ê² ìë ´íë, ìµì¢ì ì¼ë¡ ë ë®ì ì±ë¥ì¼ë¡ ìë ´ 

      ë®ì Weight Decay íìµ ì : ìë ´ì ëë¦¬ë, ìµì¢ì ì¼ë¡ ë ì¢ì ì±ë¥ì¼ë¡ ìë ´

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
