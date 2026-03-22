![Header](https://raw.githubusercontent.com/fabriciocarraro/Gemini-Embedding-2-Complete-Guide/refs/heads/main/images/header.jpg)

# Gemini Embedding 2 — Complete Guide

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1XDnY2InFiE_UNNyHOoN7NtbZKIKsYVqY?usp=sharing)

**Gemini Embedding 2** is Google's first natively multimodal embedding model. It maps text, images, audio, video, and PDFs into the same vector space, enabling cross-modal search through simple cosine similarity.

---
 
## What is this?
 
A hands-on notebook that walks you through **everything** Gemini Embedding 2 can do — from classic word-vector arithmetic ("king − man + woman = queen") to fully cross-modal searches where an image finds a sound, or a voice clip finds a PDF.
 
Everything runs in a single Google Colab. You just need a free API key from [Google AI Studio](https://aistudio.google.com/).

---

## Authors
 
- **Pedro Gengo** - [LinkedIn](https://www.linkedin.com/in/pedrogengo/) - pedro.gengo.lourenco@gmail.com
- **Fabrício Carraro** - [LinkedIn](https://www.linkedin.com/in/fabriciocarraro/) - fabriciocarraro@gmail.com
 
---

## What's Inside

**📝 Text Embeddings** — What embeddings are, cosine similarity, and the classic "king − man + woman = queen" experiment. Plus text clustering with TensorBoard.

**🖼️ Image Embeddings** — Image-to-text matching, image-to-image comparison, image embedding arithmetic (king − crown = man).

**🔍 Image Search** — A full similarity search engine built with FAISS and Tiny ImageNet. Upload your own image and find the closest matches.

**🧩 Combined Multimodal Embeddings** — Aggregating text + images into single embeddings for social media posts, then searching across 5 posts that all mention "Gemini" in different contexts (AI model, zodiac sign, NASA mission).

**🔊 Audio Embeddings** — Text-to-audio search, audio-to-audio matching, and image-to-audio cross-modal search.

**🎬 Video Embeddings** — Text-to-video, audio-to-video, and video-to-video similarity search.

**📄 PDF file Embeddings** — Native PDF embedding (no text extraction needed), text-to-PDF search, audio-to-PDF cross-modal search, and PDF-to-PDF comparison.

**📐 Dimensionality** — Testing how Matryoshka Representation Learning (MRL) lets you reduce embedding dimensions from 3,072 down to 128 with minimal quality loss.

---

## Getting Started

1. Open the notebook in Google Colab using the badge [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1XDnY2InFiE_UNNyHOoN7NtbZKIKsYVqY?usp=sharing)
2. Get a free API key from [Google AI Studio](https://aistudio.google.com/)
3. Save it in Colab's Secrets sidebar with the name `GEMINI_API_KEY`
4. Run the cells and explore

---

## Dependencies
 
The notebook installs everything it needs automatically. Key libraries:
 
| Library | Purpose |
|---|---|
| `google-genai` | Gemini API client |
| `faiss-cpu` | Fast similarity search (FAISS) |
| `scikit-learn` | Cosine similarity |
| `tensorflow` / `tensorboard` | Embedding visualization (Projector) |
| `datasets` | Hugging Face dataset loading |
| `matplotlib` / `Pillow` | Image display and plotting |
| `pandas` / `numpy` | Data manipulation |
