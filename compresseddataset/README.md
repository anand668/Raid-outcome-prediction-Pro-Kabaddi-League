# Dataset

This folder contains information about the dataset used in this project.

## Details
- **Size:** ~554.3 MB
- **Format:** JSON
- **Storage:** Google Drive

## Access the Dataset
Click the link below to access the full dataset:

[📂 Download Dataset from Google Drive](https://drive.google.com/file/d/1eA2rVzfMwICErfzVIpZRJ9fhqsFvxUH-/view?usp=drive_link)

## How to Load in Colab
```python
from google.colab import drive
drive.mount('/content/drive')

df = pd.read_csv('/content/drive/MyDrive/your_dataset.csv')
```
