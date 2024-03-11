# Handwritten Digit recognition with Cosine Similarity

[![Ruff](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/astral-sh/ruff/main/assets/badge/v2.json)](https://github.com/astral-sh/ruff)

![Alt text](./images/cover.jpg)
<p align="center">
  <i>Image credits: <a href='https://aigeekprogrammer.com/keras-python-mnist-handwritten-digit-recognition/'>AI Geek Programmer article</a></i>
</p>

## Table of Contents

* [Problem statement](#problem-statement)
* [Directory layout](#directory-layout)
* [Running the app with Docker (Recommended)](#running-the-app-with-docker-recommended)
* [Running the app manually](#running-the-app-manually)
* [Checkpoints](#checkpoints)
* [References](#references)

## Problem statement

Brief problem statement

## Directory layout

```
.
├── images
│   └── digits
├── src
│   └── array_digits
└── tests

5 directories
```

## Running the app with Docker (Recommended)

1. `git clone https://github.com/edcalderin/Handwritten-digit-recognition.git` 
2. `docker build -t digit-recognition .` 
3. `docker run -it --rm -p 8501:8501 digit-recognition`

Go to `http://localhost:8501`

The output should look like this:

![Alt text](./images/app.png)

## Running the app manually

> :memo: You will need **Python 3.12** installed on your system in order to reproduce this app manually.
Run the following commands from root project directory:

1. `git clone https://github.com/edcalderin/Handwritten-digit-recognition.git`
2. `pip install poetry`
3. `poetry shell`
4. `poetry install`
5. `streamlit run src/app.py`
6. Go to `http://localhost:8501`

## Checkpoints

- [x] Problem description
- [x] Reproducibility
- [x] Dependency and enviroment management
- [x] Containerization (Docker with multi-stage)
- [x] Linter
- [x] Unit tests
- [x] CI/CD workflow (Linter and Unit tests)
- [ ] Cloud deployment

## References

* https://en.wikipedia.org/wiki/Cosine_similarity