# 📦 SMS Spam Classifier (PyTorch)

A simple SMS spam detection model built using PyTorch and an LSTM neural network. The model classifies text messages as either **ham** (not spam) or **spam** based on their content.

---

## 🧠 Features

- LSTM-based text classifier
- Custom PyTorch `Dataset` and `DataLoader`
- Handles imbalanced datasets (class weights or sampling)
- Supports checkpoint saving and resuming
- Predicts new user input messages

---

## 📁 Dataset

The dataset used is [SMS Spam Collection](https://raw.githubusercontent.com/justmarkham/pycon-2016-tutorial/master/data/sms.tsv), with two columns:

- `label`: `ham` or `spam`
- `message`: the actual SMS text

---


