# 📁 data

Place your medical image dataset here.

Recommended format:
- `data/class1/image1.jpg`
- `data/class1/image2.jpg`
- ...

## Recommended Datasets

For training this VAE, you can use:

1. NIH Chest X-Ray Dataset (most popular)
   -  Link: [NIH Data](https://nihcc.app.box.com/v/ChestXray-NIHCC)
   -  12,000+ frontal-view X-ray images (14 diseases)
   -  Use the “No Finding” images for training your VAE

2. RSNA Pneumonia Detection Challenge (Kaggle)
   -  Link: [RSNA Pneumonia Dataset](https://www.kaggle.com/c/rsna-pneumonia-detection-challenge/data)
   -  Chest X-rays labeled for pneumonia or not
   -  Needs Kaggle login + API key

3. Tuberculosis Chest X-ray Dataset
   -  Link: [Tuberculosis Data](https://www.kaggle.com/datasets/raddar/tuberculosis-chest-xray-dataset)
   -  Small dataset (~800 images), good for testing
   -  Make sure images are cleaned and resized to 64x64 if needed.

## ⚠️ Preprocessing:
- Resize images to 64x64
- Convert to RGB (if needed)
- Normalize using torchvision transforms (already in script)
