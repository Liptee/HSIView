# What is HSIView
HSIView is a native macOS desktop application for hyperspectral imaging workflows: it lets user open, visualize, analyze, process, and export hyperspectral images in common formats. It is for hyperspectral imaging practitioners who need practical day-to-day data work in one tool, such as remote sensing specialists, research engineers, data analysts, and applied scientists working with spectral data.

It started as a lightweight app for fast hypespectral file preview. Over time, it evolved as more and more tasks that were previously handled with Python scripts were brought directly into the product. This led to its core philosophy: *any routine hyperspectral task should be possible inside one application*. Today, HSIView is built to reduce code-heavy workflows and let users process, analyze, and export hyperspectral data with minimal scripting.

# System Requirements
- HSIView requires **macOS 15.0 or later** and runs on **Apple Silicon Macs only**.
- For optional custom `Python` pipeline operations, install Python3 with `NumPy`

# Installation from GitHub
1. Open the project repository on GitHub.
2. Go to the Releases section.
3. Select the latest stable release.
4. Download the attached archive.
5. Unzip the archieve
6. Drag `HSIView.app` to the **Applications** folder.
7. Launch the app.

If macOS blocks the first launch, right-click **HSIView.app** and choose **Open**, then confirm.
You can also allow it in `System Settings -> Privacy & Security`.

# What can you do?
## Open HSI with common extensions
![Opening HSI files from Finder](Media/gifs/FileOpen.gif)

You can open HSI file directrly from **Finder**, which makes everyday work much faster. Supported formats include: `npy`, `mat`, `tiff`, `dat/img/bsq/bil/raw + hdr`, `hsiv`.
