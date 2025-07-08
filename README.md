# instagram2digitalcommons
Are a collection of vibe coded tools for taking an instagram archive zip and transforming it into something closer to bepress ingestible files with metadata. The avante guard technique of [vibe coding](https://en.wikipedia.org/wiki/Vibe_coding) is being put to use in part because I know enough python to be dangerous and I'm curious if I can make useful things from ai prompts and plenty of testing. 

# 📸 instagram2digitalcommons

**instagram2digitalcommons** is a collection of hopefully librarian-friendly tools for transforming an Instagram archive `.zip` into structured media files + metadata packages for upload to your institutional repository (with the digital commons batch upload). It all runs online with no local installation required.

---

## 🚀 Features

- ✅ Upload and parse Instagram `.zip` archives
- ✅ Extract images, videos, captions, dates, and metadata
- ✅ Categorize content into **Reels**, **Posts**, and **Stories**
- ✅ Download a set zip files with:
  - Clean well labeled media files
  - Metadata spreadsheets (.xlsx)
  - README files for each set

---

## 🔍 Use Case

Collect and archive social media content for preservation and research. Instagram archives include valuable materials (e.g. event photos, exhibition documentation, institutional campaigns). This tool supports:

- Special Collections digitization projects
- Campus or departmental documentation
- Faculty digital scholarship
- Community history initiatives

---

## 📁 Input Format

Upload an official Instagram archive `.zip` file that you receive when you request your data from Instagram.
The instagram account admin can request their archive by visiting https://www.instagram.com/download/request.

---

## 📦 Output

Each category (**Reels**, **Posts**, **Stories**) will be exported as zip files

---

## 🧑‍💻 How to Run i2dc (in Google Colab)

You will need a google account to run this, but if you have another way to run a jupyter notebook, feel free to do that.

1. Click the button below to launch the notebook:
<a href="https://colab.research.google.com/github/e3la/i2dc/blob/main/i2dc.ipynb" target="_blank" rel="noopener noreferrer">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="First Pass - Open in Colab"/>
</a>
2. Upload your Instagram archive `.zip` when prompted (either directly or using google drive saved to a folder named /i2dc)
3. Configure your preferences and metadata
4. Download your zips directly or into your google drive /i2dc folder
5. Extract your zips and explore your media and metadata in a new more familiar format!
   
## Advanced Review Tools
[![Reels Metadata review - Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/e3la/i2dc/blob/main/Reels_Metadata_Review_and_Triage.ipynb)
Upload the reels zips you made in the First Pass and review them.

[![Posts - In Google AI Studio]([https://www.google.com/url?q=https%3A%2F%2Faistudio.google.com%2Fapp%2Fprompts%3Fstate%3D%257B%2522ids%2522%3A%255B%25221zgUh4dqoGWewtqPE40gBb96Vt2TMujgA%2522%255D%2C%2522action%2522%3A%2522open%2522%2C%2522userId%2522%3A%2522106905111806513074045%2522%2C%2522resourceKeys%2522%3A%257B%257D%257D%26usp%3Dsharin))
Upload the posts zips you made in the First Pass (why I recommend 20 at a time) and review them and add AI descriptions.

[![Posts Metadata review - Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/e3la/i2dc/blob/main/PostsReview.ipynb)
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
