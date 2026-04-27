# Cascaded YOLO Pipeline for Document and Category Detection

This repository provides the **notebooks** used for the stage 3, optical character recognition (OCR), of our paper’s pipeline for document analysis in natural images.

In this stage, we evaluate three OCR engines, **EasyOCR**, **Kraken**, and **Tesseract**, using batch-processing notebooks that read a list of input images, apply OCR, and save the extracted text as output.


## Repository structure

```text
Vision-Project-Document-Detection/
├── README.md
└── Text Recognition/
    ├── easyocr_batch.ipynb
    ├── kraken_batch.ipynb
    └── tesseract_batch.ipynb
```


## Reference

**Paper:** *A Hierarchical YOLO-Based Pipeline for Document Analysis in Natural Images*  
