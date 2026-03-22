# Gemini Embedding 2 — Complete Guide

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1XDnY2InFiE_UNNyHOoN7NtbZKIKsYVqY?usp=sharing)

What if an image could find a sound? Or a voice clip could find a PDF? That's the kind of cross-modal magic that **Gemini Embedding 2** makes possible — and in this notebook, we build it all from scratch.

**Gemini Embedding 2** is Google's first natively multimodal embedding model. It maps text, images, audio, video, and PDFs into the same vector space, enabling cross-modal search through simple cosine similarity.

## What's Inside

**📝 Text Embeddings** — What embeddings are, cosine similarity, and the classic "king − man + woman = queen" experiment. Plus text clustering with TensorBoard.

**🖼️ Images** — Image-to-text matching, image-to-image comparison, and embedding arithmetic (king − crown = man).

**🔍 Image Search** — A full similarity search engine built with FAISS and Tiny ImageNet. Upload your own image and find the closest matches.

**🧩 Combined Embeddings** — Aggregating text + images into single embeddings for social media posts, then searching across 5 posts that all mention "Gemini" in different contexts (AI model, zodiac sign, NASA mission).

**🔊 Audio** — Text-to-audio search, audio-to-audio matching (a voice clip about a scary forest finding a wolf howl), and image-to-audio cross-modal search.

**🎬 Video** — Text-to-video, audio-to-video, and video-to-video similarity search.

**📄 PDFs** — Native PDF embedding (no text extraction needed), text-to-PDF search, audio-to-PDF cross-modal search, and PDF-to-PDF comparison.

**📐 Dimensionality** — Testing how Matryoshka Representation Learning (MRL) lets you reduce embedding dimensions from 3,072 down to 128 with minimal quality loss.

## Getting Started

1. Open the notebook in Google Colab using the badge above
2. Get a free API key from [Google AI Studio](https://aistudio.google.com/)
3. Save it in Colab's Secrets sidebar with the name `GEMINI_API_KEY`
4. Run the cells and explore

## Authors

- **Pedro Gengo** — [LinkedIn](https://www.linkedin.com/in/pedrogengo) — Email: pedro.gengo.lourenco@gmail.com
- **Fabrício Carraro** — [LinkedIn](https://www.linkedin.com/in/fabriciocarraro) — Email: fabriciocarraro@gmail.com
