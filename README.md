# Project Documentation

This document provides an overview of the organization and structure of the project files. The repository contains two main folders and one PDF document, each serving a specific purpose in the documentation and generation of the final article.

## Folder Structure

### 1. `source_of_figures_and_tables`
This folder contains the original source files for all figures and tables used in the article. It is divided into two subfolders:

- **Figures**: 
  - This subfolder stores the original image files (e.g., `.png`, `.jpg`, `.pdf`.) used in the article.
  - Files are named descriptively to indicate their content or purpose in the article.

- **Tables**:
  - This subfolder contains the raw data files used to generate the tables in the article.
  - Files are organized and named to reflect the table they represent.

### 2. `tex_files`
This folder contains all the LaTeX files required to generate the final article. It includes:

- **Main LaTeX File**:
  - The primary `.tex` file that compiles the article. This file references all figures, tables, and other resources.
  
- **Figures**:
  - A subfolder containing the figures used in the LaTeX document. These are typically high-resolution versions of the images stored in `source_of_figures_and_tables/Figures`.

### 3. `An Energy-Efficient Digital Computing-In-Memory STT-MRAM Macro for AdderNets with Optimized Addition Operations.pdf`
This is the final compiled PDF document of the article. It is generated from the LaTeX files in the `tex_files` folder and includes all figures, tables, and formatted text.
