# Music Transformer Project

Welcome to the Music Transformer project! This project explores the world of music generation using state-of-the-art language models like GPT-2 and BERT. Whether you're a music enthusiast or a machine learning wizard, this project will intrigue you.
![Music Generation GIF](https://media.giphy.com/media/KbTUp85em6hdmmgTfK/giphy.gif)

## Project Overview

The Music Transformer project is aimed at generating musical compositions in ABC notation. We employ powerful language models like GPT-2 and BERT to create harmonious melodies and structures. But that's not all! We also fine-tune these models to make them groove to the rhythm of the Maestro piano dataset and pop piano song dataset.

## Installation

To get started, make sure you have the following libraries and packages installed:

- [PyTorch](https://pytorch.org/) - A deep learning framework.
- [tqdm](https://github.com/tqdm/tqdm) - A handy progress bar for tracking tasks.
- [Wandb](https://wandb.ai/site) - Weights and Biases for tracking experiments.
- [youtokentome](https://github.com/VKCOM/YouTokenToMe) - Subword text tokenization.
- [transformers](https://huggingface.co/transformers/) - State-of-the-art Natural Language Processing models.
- [accelerate](https://github.com/huggingface/accelerate) - Speed up training of your deep learning models.


You can install the required packages using `pip`:

## Models
Both GPT2 and BERT are trained on google collab. Each model has its own notebook but you need to load your own dataset. This can be done eaisly if you place your dataset in goole drive  


## Usage

### Data Preparation

Before diving into the world of music generation, you need to prepare your data. We recommend using the Maestro piano dataset and the pop piano song dataset. These datasets will be the fuel for your musical AI.

### Fine-Tuning GPT-2 and BERT

To make your models resonate with the musical spirit, you can fine-tune GPT-2 and BERT on your dataset. This step will help them understand the intricacies of musical data.

### Training

Once your models are tuned up, you can start the training process. We recommend using the `Trainer` from the Transformers library and specifying your training arguments in a `TrainingArguments` object. Don't forget to define a suitable data collator, perhaps using `default_data_collator`.

### Listening to the Magic

Generate some mesmerizing ABC notations and listen to your AI's musical creations.

### Sample Music

Curious to hear what your models can do? Check out these sample MP3 samples:

- [Sample 1](Music_generated_samples/gpt2_1.mp3)
- [Sample 2](Music_generated_samples/gpt2_1.mp3)

## Contributions

Contributions to this project are more than welcome! Whether you're an AI composer or a data wizard, I would love to see your pull requests.


