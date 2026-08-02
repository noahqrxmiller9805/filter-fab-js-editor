# Filter Fab JS - Image Filter Editor 2026

> **Filter Fab JS is a web-based image editing tool for creating RGBA channel formulas, viewing changes as they render, and saving processed images as PNG files.**

[![Platform](https://img.shields.io/badge/Platform-Web%20browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-Not%20specified-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/noahqrxmiller9805/filter-fab-js-editor?style=flat-square)](https://github.com/noahqrxmiller9805/filter-fab-js-editor)

---

<p align="center">
  <a href="https://noahqrxmiller9805.github.io/filter-fab-js-editor/">
    <img src="https://img.shields.io/badge/Download-Filter%20Fab%20JS%20Latest-brightgreen?style=for-the-badge" alt="Download Filter Fab JS">
  </a>
</p>

> **[Download Filter Fab JS](https://noahqrxmiller9805.github.io/filter-fab-js-editor/)**

---

[Download Latest Build](https://noahqrxmiller9805.github.io/filter-fab-js-editor/)

---

## What Is Filter Fab JS?

Filter Fab JS is a standalone image filter editor that operates inside a web browser. Its interface lets you write formulas for each RGBA channel and experiment with eight formula-controlled settings while seeing the image update during processing.

The tool is intended for designers, developers, and anyone exploring image processing through formulas. Load an image, inspect it through several preview layouts, export the processed result as PNG, or share filter configurations through JSON and AFS files.

---

## Capabilities

- Create independent formulas for red, green, blue, and alpha channels.
- Work with eight controls powered by filter formulas.
- Process loaded images within the browser.
- Save processed images as PNG files.
- Read and write filter definitions as JSON.
- Read and write AFS filter files.
- Monitor rendering progress while an image is processed.
- View original, filtered, or split comparisons.
- Use the full editor from one HTML file.

---

## Getting Started

### Download the application

Get the current build here:

[Download Filter Fab JS](https://noahqrxmiller9805.github.io/filter-fab-js-editor/)

After downloading it, open the HTML application with a modern web browser.

### Use the repository version

```bash
git clone https://github.com/noahqrxmiller9805/filter-fab-js-editor.git
cd REPO
```

Open the project HTML file in your browser. Filter Fab JS is provided as a single-file HTML application, so the standard workflow does not need package installation or a local server.

---

## Using the Editor

1. Launch Filter Fab JS in a web browser.
2. Import an image.
3. Write or modify formulas for the red, green, blue, and alpha channels.
4. Set the formula-based controls to the desired values.
5. Follow the rendering indicator while the preview is generated.
6. Select the original, filtered, or split preview.
7. Export the processed image as PNG.
8. Import or export the filter setup through JSON or AFS.

### Typical filter process

```text
Load image
   |
Define RGBA formulas
   |
Adjust formula controls
   |
Review live preview
   |
Export PNG or save the filter definition
```

---

## Filter Setup and Configuration

Configuration takes place in the built-in formula editor rather than in an external configuration file. Use it to create the four channel formulas and modify the eight formula-driven parameters.

To preserve a filter for later use or share it with others, export its definition as JSON or AFS. Either format can be imported again to restore the saved setup.

---

## Requirements

- A modern browser that supports HTML and JavaScript.
- Either the single-file HTML application stored locally or the hosted build.
- Image files that can be loaded by the browser.
- Enough browser memory for the images being processed.
- No separate runtime, package manager, or server is needed for basic use.

---

## Frequently Asked Questions

### Do I need to install Filter Fab JS?

No. Filter Fab JS is packaged as a self-contained HTML file and can be opened directly in a web browser.

### Where is the newest build available?

Open the [Download Latest Build](https://noahqrxmiller9805.github.io/filter-fab-js-editor/) link near the beginning of this README.

### What is the process for making a filter?

Start by loading an image. Then define the RGBA formulas, adjust the formula-controlled settings, and use the preview modes to evaluate the result.

### Can filter setups be saved or shared?

Yes. The editor supports importing and exporting filter definitions in both JSON and AFS formats.

### Which format is used for image exports?

Filtered images can be exported as PNG files.

### Why does rendering take a while?

The application displays rendering progress while the filter runs. The time required depends on the image and the complexity of its formulas.

### Is there a way to view the source beside the result?

Yes. The original, filtered, and split preview modes let you compare the input image with the processed output.

---

## Roadmap

- Further polish formula-driven image editing workflows.
- Make live rendering status easier to understand.
- Add more documentation around JSON and AFS filter sharing.
- Evaluate further browser-based editing enhancements as development continues.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
