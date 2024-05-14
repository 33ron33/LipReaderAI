# LipReaderAI


![LipNet Demo](lips.png)

## Abstract-  LipReaderAI

LipReaderAI presents a novel approach in assistive technologies, designed to overcome communication barriers for individuals with hearing impairments. Our model leverages the synergy between spatiotemporal convolutions and recurrent neural network architectures to accurately transcribe spoken language from visual input across multiple speakers. To eliminate the need for manual segmentation, we employ Connectionist Temporal Classification (CTC) loss, which facilitates direct, end-to-end training from unprocessed video input to textual transcription. This project tests the robustness of the model by evaluating its accuracy on a custom dataset featuring recordings of the author, ensuring it can reliably translate visual speech. LipReaderAI not only aims to improve accessibility for those with hearing impairments but also extends the use of lipreading into loud environments where traditional speech recognition systems that rely solely on audio are ineffective.

![LipNet Demo](demo.gif)



# Setting Up the LiveLipNet-Duo Environment

This guide will walk you through setting up the Python environment required to run the projects in the [Lip_reading repository](https://github.com/33ron33/LiveLipNet-Duo).

## Prerequisites

Ensure you have Python installed on your system. You can download Python from [python.org](https://www.python.org/downloads/).

## Clone the Repository

First, clone the LiveLipNet-Duo repository to your local machine:

```bash
git clone https://github.com/33ron33/Lip_reading.git
```

## Create and Activate a Virtual Environment

Create a virtual environment nmaes 'LiveLipNet-env' within the repository directory:

```bash
python -m venv LiveLipNet-env
```

Activate the Virtual Environment 
- On macOS/Linux:
```bash
source LiveLipNet-env/bin/activate
```
- On Windows:
```bash
LiveLipNet-env\Scripts\activate
```
## Insatll and Verify Dependencies 
Install the project dependencies from the 'requirements.txt' file:
```bash
pip install -r requirements.txt
```

Verify Dependencies:
```bash
pip list
```
## Setting Up IPython Kernel

To set up the IPython kernel for the virtual environment, run the following command:

```bash
python -m ipykernel install --name=LiveLipNet-env
```

# Deactivate the Virtual Environment-

```bash
deactivate
```

  



