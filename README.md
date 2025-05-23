# instagram2bepress
Vibe coded a tool for taking an instagram archive zip and transforming it into bepress ingestible files with metadata in colab

# 📸 instagram2bepress

**instagram2bepress** is a librarian-friendly tool for transforming Instagram archive `.zip` files into structured media + metadata packages ready for batch upload to an institutional repository (such as a bepress IR). It runs in Google Colab — no local installation required.

> Designed for cultural heritage preservation, digital collections, and digital humanities workflows.

---

## 🚀 Features

- ✅ Upload and parse Instagram `.zip` archives
- ✅ Extract images, videos, captions, dates, and metadata
- ✅ Categorize content into **Reels**, **Posts**, and **Stories**
- ✅ Preview extracted metadata in structured tables
- ✅ Download a set of archive-ready folders with:
  - Clean media files
  - Metadata spreadsheets (.xlsx) with emoji support
  - README files for each set

---

## 🔍 Use Case

Libraries and archives increasingly collect social media content for preservation and research. Instagram archives include valuable born-digital materials (e.g. event photos, exhibition documentation, institutional campaigns). This tool supports:

- Special Collections digitization projects
- Campus or departmental documentation
- Faculty digital scholarship
- Community history initiatives

---

## 📁 Input Format

Upload the official Instagram archive `.zip` file you receive when you request your data from Instagram.

Contents should include directories like:
/content/posts/media/
/content/stories/media/
/content/reels/media/
/content/posts_1.json


---

## 📦 Output

Each category (**Reels**, **Posts**, **Stories**) will be exported as:
/reels_export/
metadata_reels.xlsx
README.txt
/media/...

/posts_export/
metadata_posts.xlsx
README.txt
/media/...

/stories_export/
metadata_stories.xlsx
README.txt
/media/...


---

## 🧑‍💻 How to Run (in Google Colab)

1. Click the button below to launch the notebook:

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/e3la/instagram2bepress/blob/main/instagram2bepress.ipynb)

2. Upload your Instagram archive `.zip` when prompted  
3. Review the parsed metadata
4. Download your structured repository-ready packages!

---

## 📚 Dependencies

This notebook uses:

- Python 3
- `pandas`
- `zipfile`, `os`, `json`, `datetime`
- `openpyxl`
- `IPython.display`
- `google.colab.files`

All libraries are pre-installed in Colab.

---

## ✨ Future Ideas

- Custom field mapping for specific IR schemas
- Alt text generation using AI
- OCR for embedded text in images
- Direct integration with repository platforms

---

## 👩‍🏫 Author

Created by [Helena Marvin](https://github.com/e3la)  
AI-assisted by ChatGPT  
Prompt and conversation for this readme at [https://chatgpt.com/share/6830b6b7-a65c-800f-9391-53d0c394587e]
University of Missouri–St. Louis | UMSL Libraries

---

## 📄 License

CC0 because I believe ai generated code should be public domain
