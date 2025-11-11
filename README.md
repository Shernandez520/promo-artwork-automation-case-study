# 🧩 Case Study: Automating Image Sorting for Webstore Production

### 🎯 The Problem
Our hybrid web development and design team regularly receives large batches of product images — typically **150–200 at a time** — from the Sales department. These images are used for bulk product uploads to customer webstores.  

Before automation, each batch had to be **manually reviewed and sorted by orientation** (portrait, landscape, or square). This process was tedious, time-consuming, and repetitive, consuming **several cumulative hours per week** that could have been spent on higher-value creative work.

---

### 💡 The Insight
After sorting through multiple batches by hand, I realized that image orientation data was already embedded in the file metadata. That meant the process could be automated.  

I decided to explore whether **PowerShell** could read these dimensions and sort files accordingly — saving our team time and frustration.

---

### ⚙️ The Solution
I partnered with **GitHub Copilot** to develop a custom PowerShell script that:

- Reads each image’s dimensions  
- Determines its orientation (portrait, landscape, or square)  
- Moves the file into the correct subfolder  
- Generates a detailed **log file** summarizing all sort actions  

The result was a reliable, lightweight tool that worked perfectly for our local Windows environment. I then documented the process and distributed the script and instructions across the team so everyone could use it independently.

---

### 🚀 The Impact
This simple automation reduced a **multi-hour weekly task to minutes**.  

Beyond time savings, it also:
- Increased accuracy and consistency in our uploads  
- Standardized the organization of our product image libraries  
- Empowered the team to use automation tools confidently  

This project proved how small, well-targeted scripts can have an outsized impact on creative workflow efficiency.

---

### 🧠 What I Learned
- Even simple automations can drastically improve productivity and morale  
- AI-assisted coding (Copilot) can accelerate script development for non-developers  
- Teaching others to use automation tools multiplies the value of a single project  

---

### 🧩 Tools & Tech
- **PowerShell**  
- **GitHub Copilot**  
- **Windows File System**  
- **Batch image workflows for webstore product listings**

---

### 🔗 View the Code
👉 [View the script on GitHub](https://github.com/Shernandez520/image-sorting-tool)
