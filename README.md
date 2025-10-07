# 🎓 Make Educational YouTube Videos **Halal** (Remove Music)

Process YouTube videos in **Google Colab** to remove background music and keep only vocals for personal, halal, educational use.  
Ideal for learners who prefer to avoid music in knowledge content, following Islamic ethics.

***

## 🚀 **Quick Start**

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1FVzFppcTwwIfaPxMehNdiQvhrJ02oWrk#scrollTo=8hi6wehDQmLV)

📋 **How to Use**

**1. Run the Notebook (in Colab)**  
Click the badge above to open the script on Google Colab.

***

**2. Set Your YouTube Video URL In The Script**

```python
VIDEO_URL = "https://www.youtube.com/watch?v=YOUR_VIDEO_ID"
```

***

**3. Export Your Cookies from YouTube**
- Use: [Get cookies.txt LOCALLY by kairi003](https://chromewebstore.google.com/detail/get-cookiestxt-locally/cclelndahbckbenkjhflpdbgdldlbecc) *(safe, open-source, privacy-respecting)*
- Visit [YouTube](https://www.youtube.com) while logged in, click the extension icon, and export cookies as a `.txt` file (e.g. `www.youtube.com_cookies.txt`) [just click the export button]
- This enables yt-dlp in Colab to authenticate with your account.

***

**4. Upload Your cookies.txt File in Colab**

- Click the “Choose Files” button in the Colab dialog.

- In the pop-up file explorer, navigate to the location on your computer where you saved your exported cookies file (usually called www.youtube.com_cookies.txt).

- Select the file and click “Open”.

- Wait for the file to finish uploading before proceeding to the next step.

***

**5. Wait for the Process**  
The notebook will use your cookies, take the video/audio, extract vocals only, merge them, and provide a small screen link for viewing.

***

## 🕌 **HALAL / ETHICAL DISCLAIMER**

### **Halal Usage Guidance**
- **Strictly for personal, private, educational use only.**
- **Do NOT share, publish, distribute, or monetize** any processed video or extracted audio.
- Only use for non-commercial or public purposes **if you have explicit, written consent from the creator.**
- Use with halal content (**avoid prohibited themes**).

### **Respect Copyright and Creators’ Rights**
- This notebook **does not condone piracy or unauthorized distribution**.

### **For Halal Compliance**
- Most Islamic scholars agree: **removing music for personal educational study is halal**, provided you do not violate another’s rights.

### **NOT Halal If:**
- Used for haram purposes, profit, or to harm someone.
- Public redistribution of videos, or processing content against explicit owner/platform terms.

***

## 🔒 **Privacy & Cookies**

- Recommended extension ([Get cookies.txt LOCALLY](https://chromewebstore.google.com/detail/get-cookiestxt-locally/cclelndahbckbenkjhflpdbgdldlbecc)) is **open-source, privacy-safe,** and does **NOT transmit your data externally.**
- Always use secure methods for exporting cookies. **Do not use suspicious plugins.**

***

## ⚖️ **Legal Notes**
- Downloading YouTube videos for personal, educational use is generally tolerated, but **may violate YouTube’s Terms if redistributed**.
- Always respect platform rules and local laws.

***

> **This notebook is a halal-friendly, ethical tool for private educational learning/study. Your use is your responsibility. Consult scholars or copyright owners if in doubt, and act with Islamic ethical intentions.**

***

*Reviewed: October 2025 – based on "Get cookies.txt LOCALLY" and latest halal guidance.*
