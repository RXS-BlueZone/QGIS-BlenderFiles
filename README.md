# 🔧 Git LFS Setup Instructions

This project uses **Git LFS (Large File Storage)** to handle large files such as:

- `.shp` – shapefiles  
- `.tif` – raster images  
- `.blend` – Blender project files

> ⚠️ **Important:** If Git LFS is not installed before cloning or pulling, these large files **won't download properly**.

---

## ✅ Step-by-Step Setup Guide

### 1. **Download Git LFS**

Go to:  
👉 [https://git-lfs.github.com/](https://git-lfs.github.com/)

Click "Download" and install it like a normal Windows program.

---

### 2. **Initialize Git LFS**

After installing, open **Command Prompt** and run:

```bash
git lfs install
```

This sets up Git LFS for your system.

---

### 3. **Clone the Repository**

If you haven’t cloned the project yet:

```bash
git clone https://github.com/RXS-BlueZone/QGIS-BlenderFiles.git
cd QGIS-BlenderFiles
```

Git LFS will automatically fetch and handle all large files correctly.

---

## 🛠 Already Cloned Without Git LFS?

No worries! Just follow these steps to fix it:

### 1. Install Git LFS (as shown above)  
### 2. Open Command Prompt and run:

```bash
git lfs install
```

### 3. Go to your project folder:

```bash
cd path\to\QGIS-BlenderFiles
```

### 4. Fetch the large files manually:

```bash
git lfs pull
```

Now all the missing or broken large files will be downloaded properly.

---

## ℹ️ Need Help?

- Ask in the group chat if anything breaks
- Or check: [https://git-lfs.github.com/](https://git-lfs.github.com/)
