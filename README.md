# Emotion Detection with AlexNet

This project uses an AlexNet-based deep learning model for facial emotion detection. The main code is available in the Jupyter Notebook, and the repository also includes sample images and a demo video for testing the model.

The goal of this project is to detect emotions from face images or video input and show how a CNN model can be used for basic facial expression recognition.

## Repository Files

```text
Emotion-Detection-with-Alexnet-Model/
│
├── AlexNet_Emotion_Detection.ipynb   # Main notebook containing the model code
├── demo-video.mp4                    # Sample video for running the project
├── pic3.jpeg                         # Sample image for testing
├── pic4.jpeg                         # Sample image for testing
├── requirements.txt                  # Required Python packages
└── README.md                         # Project documentation
```

## Features

- Emotion detection using an AlexNet-based CNN model
- Image-based testing with sample pictures
- Video-based testing using a demo video
- Notebook-based workflow for training, testing, and visualization
- Simple project structure that is easy to run and understand

## Requirements

Make sure you have the following installed:

- Python 3.8 or later
- Jupyter Notebook or Google Colab
- pip

All required Python packages are listed in `requirements.txt`.

## Setup

Clone the repository:

```bash
git clone https://github.com/your-username/Emotion-Detection-with-Alexnet-Model.git
cd Emotion-Detection-with-Alexnet-Model
```

Create a virtual environment:

```bash
python -m venv venv
```

Activate the virtual environment.

For Windows:

```bash
venv\Scripts\activate
```

For macOS or Linux:

```bash
source venv/bin/activate
```

Install the dependencies:

```bash
pip install -r requirements.txt
```

## How to Run

Start Jupyter Notebook:

```bash
jupyter notebook
```

Open this file:

```text
AlexNet_Emotion_Detection.ipynb
```

Then run the notebook cells step by step.

The notebook contains the main workflow for loading the model/code, processing input images or video, and showing the emotion detection output.

## Testing with Sample Images

The repository includes two sample images:

```text
pic3.jpeg
pic4.jpeg
```

Use these files inside the notebook when you want to test emotion detection on still images.

If you want to test your own image, place it in the project folder and update the image path inside the notebook.

Example:

```python
image_path = "pic3.jpeg"
```

## Demo Video

The repository also includes one sample video for running project using picture uploading:


## Project Workflow

The general workflow is:

1. Install the required packages.
2. Open `AlexNet_Emotion_Detection.ipynb`.
3. Run the notebook cells in order.
4. Test the model using `pic3.jpeg`, `pic4.jpeg`.
5. View the predicted emotion output.

## Common Issues

### Notebook is not opening

Make sure Jupyter Notebook is installed:

```bash
pip install notebook
```

Then run:

```bash
jupyter notebook
```

### File not found error

Check that the file name in the notebook matches the actual file name in the repository.

For example:

```text
pic3.jpeg
pic4.jpeg
```

The file name and extension must be exactly the same.

### Packages are missing

Install the dependencies again:

```bash
pip install -r requirements.txt
```


## Notes

- The main project code is inside the Jupyter Notebook.
- `pic3.jpeg` and `pic4.jpeg` are included as dummy images for testing.
- `demo-video.mp4` is included as a sample video for running the project.
- You can replace the sample files with your own images or videos.
- Keep the file paths updated inside the notebook when using custom files.
