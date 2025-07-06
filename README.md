# instagram2digitalcommons
Vibe coded a tool for taking an instagram archive zip and transforming it into bepress ingestible files with metadata in colab. The avante guard technique of [vibe coding](https://en.wikipedia.org/wiki/Vibe_coding) is being put to use because I know enough python to be dangerous. 

# 📸 instagram2digitalcommons

**instagram2digitalcommons** is a librarian-friendly tool for transforming Instagram archive `.zip` files into structured media files + metadata packages for upload to your institutional repository (with the digital commons batch upload). It runs in Google Colab — no local installation required.

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
The instagram admin should be able to request their archive by visiting https://www.instagram.com/download/request.

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
[![First Pass - Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/e3la/i2dc/blob/main/i2dc.ipynb)
2. Upload your Instagram archive `.zip` when prompted (either directly or using google drive saved to a folder /i2dc)
3. Configure your preferences and metadata
4. Download your structured repository-ready packages!
   
## Advanced Review
[![Reels Metadata review - Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/e3la/i2dc/blob/main/Reels_Metadata_Review_and_Triage.ipynb)
Upload the reels zips you made in the First Pass and review them.

---

## 📚 Dependencies

All libraries are pre-installed in Colab.

---

## ✨ Future Ideas

- Custom field mapping for specific IR schemas
- Alt text generation using AI
- OCR of embedded text in images

---

## 👩‍🏫 Author

Created by [Helena Marvin](https://github.com/e3la)  
AI-assisted by ChatGPT  
Prompt and conversation for this readme at [https://chatgpt.com/share/6830b6b7-a65c-800f-9391-53d0c394587e]
University of Missouri–St. Louis | UMSL Libraries

---

## 📄 License

CC0 because I believe ai generated code should be public domain
