# Image Sorter

A simple Windows app for quickly sorting images and videos into two folders.

## 📥 Installation

You **do not need Python** or any other software.

### 1. Download the EXE

Go to the **Releases** section of this GitHub repository and download:

**`image_sorter.zip`**

**`extract the zip file and you will see the exe and readme`**

### 2. Run the exe

Double-click the downloaded `.exe`.

Windows may show a security warning because the application is not digitally signed.

If Windows shows:

> Windows protected your PC

Click:

**More info → Run anyway**

### 3. Choose your folder

When the Image Sorter opens, select the folder containing the images/videos you want to sort.

The app will automatically create:

* `Bin 1`
* `Bin 2`

in the same folder as the `.exe`.

## 🎮 Controls

| Key               | Action                         |
| ----------------- | ------------------------------ |
| **Right Arrow →** | Move current file to **Bin 1** |
| **Left Arrow ←**  | Move current file to **Bin 2** |
| **Up Arrow ↑**    | Skip current file              |
| **Down Arrow ↓**  | Undo the previous action       |
| **ESC**           | Exit                           |

## 🖼️ Supported Files

### Images

* JPG / JPEG
* PNG
* GIF
* BMP
* WEBP
* TIFF

### Videos

* MP4
* MKV
* AVI
* MOV
* WMV
* FLV
* WebM
* MPEG / MPG
* 3GP
* TS
* MTS / M2TS
* VOB
* OGV

## 📁 Example

Before:

```text
My Photos/
├── photo1.jpg
├── photo2.jpg
├── video1.mp4
└── video2.mkv
```

After sorting:

```text
My Photos/
├── photo1.jpg
├── photo2.jpg
├── video1.mp4
├── video2.mkv
├── Bin 1/
│   ├── photo1.jpg
│   └── video1.mp4
└── Bin 2/
    ├── photo2.jpg
    └── video2.mkv
```

## ⚠️ Important

The application **copies** files into Bin 1/Bin 2 rather than deleting the originals.

If you accidentally sort something, press **↓ Down Arrow** to undo the last action.

## 💻 Requirements

* Windows 10 or Windows 11
* No Python installation required
* No additional dependencies required

## 📦 Download

Download the latest `.exe` from the **Releases** section.

That's it
