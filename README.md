---
title: Image Matching App
emoji: 🦀
colorFrom: gray
colorTo: indigo
sdk: streamlit
sdk_version: 1.36.0
app_file: app.py
pinned: false
---

# Image Matching

An experimental **Hugging Face Space** demo for image matching, built with Streamlit. Users upload an image through a simple web interface, and the app runs an image-matching model on it.

> ⚠️ **Status: Experimental.** This is an early demo / learning Space and is still rough around the edges.

## Tech Stack

- Python
- Streamlit (web UI)
- PyTorch

## Run Locally

```bash
pip install -r requirements.txt
streamlit run app.py
```

## Notes

Built to experiment with deploying a vision model behind a minimal, shareable web interface on Hugging Face Spaces.
