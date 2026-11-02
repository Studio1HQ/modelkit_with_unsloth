# Blog Companion Repository

This repository accompanies the blog post **“How to Use ModelKits with Unsloth Studio”** and contains a Jupyter notebook (`main.ipynb`) with comands and examples demonstrated in the article.

The goal of this repo is **reproducibility**: if you follow both the blog and notebook, you will be able to install the required tooling, pull the quantized model from huggingface, package it as a ModelKit using KitOps, upload to Jozu Hub and sign it with Cosign, then pull the ModelKit and run it locally with Unsloth Studio.

---

## 📁 Repository Structure

```text
.
├── .gitignore
├── README.md
├── main.ipynb              # Commands & Examples shown on the blog