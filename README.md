# generic-cam-trap-id

This repository contains the development files for a generic camera trap animal identification game application. **This application is not responsive to screen size and will only display properly on a 1920x1080 pixel sized screen.**

## About these files

### Generic camera trap animal identification game template

This is a collection of files that provide a template for building a game exploring camera trap photographs of animals. Users are tested on their ability to correctly identify animals pictured in five camera trap photos. Three animal names are provided and the user must select the one corresponding to the animal in the photo.

This application is built with Vue 2.6.11 using @vue/cli 4.4.1

### Data and data sources

The demo media and data for this application consists of images obtained from the [eMammal photo archive](https://emammal.si.edu/favorite-photos), open source reference images (sources provided in `referenceImageData.csv`), and a .csv file containing corresponding metadata for each image. This data is located within the assets folder: `src > assets` – images are .jpg files located in the folder `images` and `images/reference` and metadata is in the file `eMammalImageData.csv` and `referenceImageData.csv`.

### Creating a custom version

The text and design elements (e.g., HTML, CSS, and 'genericLogo.png) can be directly edited to change the look of the application. Game images can be updated by adding new image files to the `images` folder, with a corresponding data entry in `eMammalImageData.csv`, and the `images/reference` folder, with a corresponding data entry in `referenceImageData.csv`. Each image should have a corresponding entry (row), with all attributes (columns) included, in which the first field 'imagName' must be identical to the image file name it is referencing.

## Project setup

```bash
npm install
```

### Compiles and hot-reloads for development

```bash
npm run serve
```

### Compiles and minifies for production

```bash
npm run build
```

### Lints and fixes files

```bash
npm run lint
```
