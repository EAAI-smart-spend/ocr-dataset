# Smart Spend OCR Chinese Dataset

This project consists of three main steps to build a Chinese OCR dataset:

## Dataset Size
- Training set: 10,000 images
- Test set: 1,000 images
- Validation set: 1,000 images

## Step 1: Generate Chinese OCR dataset with TRDG
- Tool: [TextRecognitionDataGenerator (TRDG)](https://github.com/Belval/TextRecognitionDataGenerator)

## Step 2: Dataset transformation
- Tool: [TRDG2DTRB](https://github.com/DaveLogs/TRDG2DTRB)

## Step 3: Convert dataset to IMDB format
- Tool: [deep-text-recognition-benchmark](https://github.com/clovaai/deep-text-recognition-benchmark)