# 🏗️ How to Update the Text in `index.html`

Welcome to the **KAUST_susnews_test** repository!  
This guide explains how to update the text content inside the website’s **index.html** file — no need to keep outputs or create new files. We reuse and overwrite the same file each time.

---

## 🔹 Step-by-Step Instructions

### **1️⃣ Open the file on GitHub**
1. Go to the repo: **KAUST_susnews_test**  
2. Click on the file: **`index.html`**  
3. In the top-right corner, click the ✏️ **Edit this file** button.

---

### **2️⃣ Convert your new text to HTML**

Before editing the file, use **ChatGPT** to convert your regular text into clean HTML.  
Copy and paste this exact prompt into ChatGPT, replacing the placeholder text:

Prompt:

  Convert the following text into clean, production-ready HTML:
  Requirements:
  Preserve paragraph structure as <p>…</p>.
  Convert link text to <a href="…" target="_blank" rel="noopener">link text</a>.
  Do not add inline CSS or extra wrappers.
  Keep only semantic HTML (p, strong, a).
  Return ONLY the HTML snippet — no extra commentary.
  TEXT TO CONVERT:
  [Paste your new text here]

  
ChatGPT will return an HTML snippet you can copy directly into `index.html`.

---

### **3️⃣ Replace the old text**
1. In the `index.html` editor, locate the section containing the previous text. It should start with <p>.  
2. Select it and **replace** it with the new HTML snippet from ChatGPT.  
3. Make sure you do **not** delete the file’s main structure (`<html>`, `<body>`, `<header>`, etc.).

---

### **4️⃣ Preview and save** 
1. Scroll down to the **Commit changes** section:  
   - Select **Commit directly to the main branch**.  
2. Click **Commit changes** ✅

---

### **5️⃣ Done!**
The page https://rmcosta90.github.io/KAUST_susnews_test/ will automatically update.

---

## 💡 Quick Tips
- Always edit **`index.html`**, not a copy.  
- Each update replaces the previous text entirely.  
- Use proper HTML tag pairs (`<p>` and `</p>`, `<strong>` and `</strong>`).  
- Keep all external links safe with `target="_blank"` and `rel="noopener"`.  
