# SoundSortGenius (Because Classifying Audio is Rocket Science)

Welcome to SoundSortGenius, where sorting sounds is practically rocket science. This project turns the mundane task of audio file identification into an adventure with advanced machine learning and data analysis. Perfect for those who enjoy distinguishing a cat's meow from a dog's bark. Dive in and join us in revolutionizing the world, one sound wave at a time.

## Features
- Advanced machine learning algorithms for audio classification
- Support for various audio datasets
- Easy-to-use interface for training and testing models

## Datasets
SoundSortGenius utilizes several well-known audio datasets:
- **RAVDESS**: The Ryerson Audio-Visual Database of Emotional Speech and Song.
- **CREMA-D**: Crowd-sourced Emotional Multimodal Actors Dataset.
- **SAVEE**: Surrey Audio-Visual Expressed Emotion Database.
- **TESS**: Toronto Emotional Speech Set.

## Installation

To get started with SoundSortGenius, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/SoundSortGenius.git
    cd SoundSortGenius
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Download and prepare the datasets:
    - [RAVDESS](https://zenodo.org/record/1188976)
    - [CREMA-D](https://github.com/CheyneyComputerScience/CREMA-D)
    - [SAVEE](http://kahlan.eps.surrey.ac.uk/savee/Download.html)
    - [TESS](https://tspace.library.utoronto.ca/handle/1807/24487)

## Usage

Train your model using the provided datasets:

```bash
python train.py --dataset RAVDESS
```

## Evaluate your model:
```bash
python evaluate.py --model model_path
```
