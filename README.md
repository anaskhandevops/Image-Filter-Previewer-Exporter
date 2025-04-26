# 🖼️ Image Filter Previewer & Exporter

A web-based tool to apply CSS filters to uploaded images in real-time, preview the results, copy the generated CSS code, and download the filtered image. ✨

---

## ✨ Features

* ⬆️ **Image Upload:** Select JPG, PNG, GIF, etc., from your device.
* 👁️ **Live Preview:** See filter effects applied instantly to your image.
* 🎛️ **Filter Controls:** Adjust sliders for:
    * Brightness
    * Contrast
    * Saturate
    * Hue Rotate
    * Blur
* ✅ **Toggle Filters:** Checkboxes for:
    * Grayscale
    * Sepia
    * Invert
* 📋 **CSS Code Generation:** Displays the corresponding CSS `filter` code.
* 🖱️ **Click-to-Copy:** Easily copy the generated CSS code.
* 🔄 **Reset Option:** Button to reset all filters to their default values.
* 💾 **Download Filtered Image:** Download the previewed image with the applied filters as a PNG file.
* 📱 **Responsive Design:** Adapts to different screen sizes.
* 💬 **User Feedback:** Displays messages for success or errors.

---

## 🚀 How to Use

1.  Clone this repository or download the `index.html` file.
2.  Open `index.html` in your web browser.
3.  Click "Choose Image File" and select your image.
4.  The image preview and filter controls will appear.
5.  Adjust the sliders and checkboxes to apply filters. See the changes live! 🔥
6.  The generated CSS code updates automatically in the "Generated CSS" box.
7.  Click the CSS code block to copy it to your clipboard.
8.  Click the "Reset Filters" button to revert all filters.
9.  Click the "Download Filtered Image" button to save the image with the current filters applied. 💾

---

## 💻 Technology Stack

* **HTML:** Page structure.
* **CSS (Tailwind CSS):** Styling & layout (via CDN).
* **JavaScript:** File handling, image preview, real-time filter application, CSS code generation, canvas manipulation for download, DOM updates, user interactions.
* **HTML Canvas API:** Used specifically for generating the downloadable image with filters applied.

---

## 🤝 Contributing

Contributions are welcome! 🎉 Whether it's bug fixes, feature additions, or documentation improvements, please feel free to contribute.

**How to Contribute:**

1.  **Fork the Repository:** Click the 'Fork' button at the top right.
2.  **Clone Your Fork:**
3.  **Create a New Branch:**
    ```bash
    git checkout -b feature/your-cool-filter
    # or
    git checkout -b fix/download-bug
    ```
4.  **Make Your Changes:** Add your code or fix the issue.
5.  **Test Your Changes:** Ensure everything works as expected.
6.  **Commit Your Changes:** Write clear commit messages (consider [Conventional Commits](https://www.conventionalcommits.org/)).
    ```bash
    git add .
    git commit -m "feat: Add drop-shadow filter control"
    # or
    git commit -m "fix: Improve download quality for large images"
    ```
7.  **Push to Your Fork:**
    ```bash
    git push origin feature/your-cool-filter
    ```
8.  **Open a Pull Request (PR):** Go to the original repository and open a PR from your branch.
    * Provide a clear title and description.
    * Link any relevant issues.

**Reporting Bugs:**

* Use the GitHub Issues tab.
* Provide a clear title, description, and steps to reproduce.
* Mention your browser and OS if relevant.

**Suggesting Enhancements:**

* Use the GitHub Issues tab.
* Provide a clear title and detailed description of the idea.

---

## 💡 Potential Enhancements

* **More Filters:** Add `opacity()`, `drop-shadow()`, or even SVG filters.
* **Filter Presets:** Add buttons for predefined filter combinations (e.g., "Vintage", "Black & White High Contrast").
* **Customizable Download Format:** Allow downloading as JPG with quality settings.
* **Undo/Redo:** Implement undo/redo functionality for filter changes.
* **Performance Optimization:** Improve handling of very large images for download.
* **UI/UX Improvements:** Enhance slider interactions or visual design.

---

Happy Filtering! 🎨
