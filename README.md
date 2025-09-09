# AR Virtual Try-On using Gemini 2.5

This project overlays products (clothes) onto a person using Gemini 2.5 Flash Image API.
#try-on images

![alt text](https://github.com/divya0709/ar-virtual-tryon-gemini/blob/main/images/lipstick%20try-on.png)
![alt text](https://github.com/divya0709/ar-virtual-tryon-gemini/blob/main/images/jacket%20try-on.jpeg)
![alt text](https://github.com/divya0709/ar-virtual-tryon-gemini/blob/main/images/dress%20try-on.jpeg)

## Features
- Upload a person image and a product image (dataset-driven)
- Realistic overlay with correct body alignment, folds, and shading
- Multiple products on the same person for comparison
- Reduces delivery cost, over-purchasing, and environmental impact
- Fully implemented in Python (PIL + Gemini API) on Kaggle Notebook

## How to Run
1. Place dataset folder as `input/data_for_banana_hackathon/`
2. Open `new-banana-hackathon.ipynb` in Jupyter or Colab
3. Run all cells
4. Generated images appear in the notebook; optional save to `output/`

## Future Work
- Add interactive upload feature for live user try-on
- Develop a web or mobile app interface
