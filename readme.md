# Clickbait Spoiler Generation

Clickbait spoiling aims at generating short texts that satisfy the curiosity induced by a clickbait post. This project is a derivative of  [Clickbait Challenge 2023 at SemEval 2023](https://pan.webis.de/semeval23/pan23-web/clickbait-challenge.html). This work aims to solve 2 subtasks from challenge i.e. spoiler classification (phrase, passage,multi-line) and generation. This is my final project for the course LIGN-167 (Deep Learning for Natural Language Understanding).<br>

Check out [notebook](https://github.com/Rajasvi/clickbait-spoiler-generation/blob/main/final_notebook.ipynb) for model training/evaluation.Please check final [report](https://github.com/Rajasvi/clickbait-spoiler-generation/blob/main/LIGN_167__Final_Report.pdf).

## Environment Settings
Please install required dependencies in order to run model.pkl using:
```
pip install -r requirements.txt
```

Otherwise bare minimum add these packages required for runnning code notebook:

- torch
- wandb
- transformers
- accelerate
- gradio