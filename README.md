# FaceSimilarityFinder

Utility to find and extract images with faces similar to a target face from a given dataset. Utilizes FaceNet for embedding extraction.

## Usage

1. Clone this repository:
```
git clone https://github.com/[your_username]/FaceSimilarityFinder.git
```

2. Open the Jupyter Notebook (`FaceSimilarityFinder.ipynb`) in Google Colab or a local Jupyter environment.

3. Run the notebook cells sequentially. The tool will prompt you to upload a zipped dataset of images and a target image.

4. After processing, a zipped folder of images similar to the target will be downloaded.

## Dependencies

- facenet-pytorch
- torchvision
- PIL (Pillow)
- Google Colab (for the current setup)

## Notes

- Ensure that the zipped dataset consists of `.jpg` or `.png` images.
- The similarity threshold is set at `0.7`. Adjust as needed.
