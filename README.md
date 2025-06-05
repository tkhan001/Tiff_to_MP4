# TIFF to MP4 Chunking Pipeline
This repository contains a Python-based pipeline that processes large multi-frame `.tif` image stacks (e.g., microscope recordings) and converts them into smaller `.mp4` video chunks for easier visualization and downstream analysis.

---

## 📌 Overview

This pipeline:
- Reads TIFF files from a directory
- Splits each TIFF stack into fixed-duration chunks
- Converts each chunk into an `.mp4` grayscale video
- Saves output videos into a specified directory

---

## 🧰 Requirements

Install the required libraries using pip:

```bash
pip install tifffile opencv-python pillow matplotlib
