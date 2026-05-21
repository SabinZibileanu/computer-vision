# computer-vision
A repo containing everything about computer vision 

## 1. Basic Image Concepts

Before using AI models, it helps to understand how images work.

Important concepts:

- **Pixels** — small color values that make up an image.
- **RGB** — red, green, and blue color channels.
- **Grayscale** — image represented only by brightness.
- **Resolution** — image width and height.
- **Noise** — unwanted visual variation.
- **Blur** — loss of sharpness.
- **Contrast** — difference between light and dark areas.


## 2. Image Manipulation

Image manipulation means changing or processing an image before analysis.

Common operations:

- resizing an image;
- cropping an image;
- rotating or flipping an image;
- converting to grayscale;
- increasing brightness or contrast;
- blurring or sharpening;
- detecting edges;
- thresholding.

Popular tools:

- **OpenCV**
- **Pillow**
- **scikit-image**


## 3. Image Classification

Assigning a label to an image

Common models:

- Convolutional Neural Networks (CNNs);
- ResNet;
- Vision Transformer (ViT).

Useful links:

- [CNNs paper](https://arxiv.org/pdf/1511.08458)
- [Vision Transformer paper](https://arxiv.org/pdf/2010.11929)
- [Vision Transformer HuggingFace model info](https://huggingface.co/docs/transformers/model_doc/vit)
- [ResNet paper](https://arxiv.org/pdf/1512.03385)

---

## 4. Object Detection

Finding objects inside an image and drawing boxes around them.


Each detected object usually has:

- a label;
- a confidence score;
- a bounding box.

Common models:

- YOLO;
- Faster R-CNN;
- Detection Transformer (DETR).

Useful links:

- [Fast R-CNN paper](https://arxiv.org/abs/1504.08083)
- [YOLO documentation](https://docs.ultralytics.com/)
- [Detection Transformer paper](https://arxiv.org/pdf/2005.12872)
- [Detection Transformer HuggingFace model card](https://huggingface.co/docs/transformers/model_doc/detr)
---

## 5. Image Segmentation

Separating an image into meaningful regions.

There are different types:

- **Semantic segmentation** — labels each pixel by class.
- **Instance segmentation** — separates individual objects.
- **Prompt-based segmentation** — segmenting objects using clicks, boxes, or text prompts.


Common models:
- Mask R-CNN;
- Segment Anything Model, also called SAM.

Useful links:

- [Segment Anything Model (SAM 2) paper](https://arxiv.org/pdf/2408.00714)
- [Segment Anything Model (SAM 2) model card](https://huggingface.co/docs/transformers/model_doc/sam2)
- [Segment Anything Model (SAM 3) paper](https://arxiv.org/pdf/2511.16719)
- [Segment Anything Model (SAM 3) model card](https://huggingface.co/docs/transformers/model_doc/sam3)
- [Mask R-CNN paper](https://arxiv.org/pdf/1703.06870)
---

## 6. Feature Extraction

Finding useful visual information from an image.

Examples of features:

- color;
- shape;
- edges;
- corners;
- texture;
- object size;
- object position;
- brightness;
- symmetry.

This can be done with classical computer vision or AI models.

Useful links:

- [Feature extraction using Vision Transformers paper](https://arxiv.org/pdf/2302.00875)
- [OpenCV feature extraction](https://docs.opencv.org/4.x/dc/d7d/tutorial_py_brief.html)
- [Bag of viusal words paper](https://arxiv.org/pdf/2002.12247)

---

## 7. Change Detection

Comparing two images or video frames and reporting what changed.


Simple approaches:

- frame difference;
- background subtraction;
- object detection in both frames;
- comparing object positions;
- comparing image embeddings.

A more complex approach:
- changing the orientation of the camera and reporting the visible changes 

Useful links:
- [Background subtraction paper](https://arxiv.org/pdf/1901.03577)
- [Estimating the camera orientation using geometry](https://arxiv.org/pdf/1908.07070)
- [Ultralytics camera calibration guide](https://www.ultralytics.com/blog/a-guide-to-camera-calibration-for-computer-vision-in-2025)
---

## 8. Object Tracking

Object tracking follows an object across multiple video frames.


Tracking is useful for:

- movement analysis;
- counting people or objects;
- detecting if an object disappeared;
- understanding video events.

Useful links:

- [Multi - Object Tracking with YOLO](https://docs.ultralytics.com/modes/track)

---


## 9. OCR (Optical Character Recognition): Reading Text from Images

Used for reading text from images.

Examples:

- reading signs;
- reading labels;
- scanning documents;
- extracting text from screenshots;
- reading numbers from images.

Popular tools:

- Tesseract OCR;
- EasyOCR;
- PaddleOCR.

Useful links:

- [Tesseract OCR repo](https://github.com/tesseract-ocr/tesseract)
- [EasyOCR repo](https://github.com/jaidedai/easyocr)
- [PaddleOCR repo](https://github.com/PADDLEPADDLE/PADDLEOCR)
---

## 10. Vision-Language Models

Vision-language models understand both images and text.

They can answer questions like:

```text
What is in this image?
What changed between these two images?
Where is the red object?
Describe this scene.
Is this image blurry?
```

These models are useful for quick prototypes because they can reason about images without training a new model from scratch.

Useful links:

- [Vision-language models overview](https://huggingface.co/blog/vlms-2025)
- [CLIP paper](https://arxiv.org/pdf/2103.00020)
- [CLIP HuggingFace model card](https://huggingface.co/docs/transformers/model_doc/clip)
- [Qwen HuggingFace model card](https://huggingface.co/Qwen)
- [Gemma Huggingface Model Card](https://huggingface.co/blog/gemma4)
---


