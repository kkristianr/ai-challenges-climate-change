## Project 1
* Project 1 aims to tackle energy efficiency of AI models using quantization
* 2 versions of the project: Object-detection and LLMs

### Project 1.1: Energy Efficiency through Quantization- Object Detection Models

* Model: Object detection (suggested: ssd_mobilenet_v2) • Model-> TFLite -> Quantize
* Dataset: COCO data set 2017
* Tasks: Choose the following three configurations (weights only) 1.float32 2.float 16 3.int8. You should perform the inference from at least thousand images (randomly selection) from the COCO test dataset. Average results can be reported for all the input dataset.
______________________________
### Project 1.2: Energy Efficiency through Quantization- Large Language Models (LLMs)
* Model: Large language model (GPT, LLAMA, OPT...)
* Data: LAMBADA dataset
* Tasks: Choose the following three configurations (weights only) 1. int8 2. int4 3. int2
* Evaluation:
  * Accuracy: Top-k Accuracy
  * Speed: Tokens/s
  * Memory: Model size (mb)
    
### TODO:
* quantizing the pre-trained models
* measuring the accuracy and computational cost
_____________________________
* writing the report
* presentation
