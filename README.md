# Homework 1 - Open Source Data Engineering Tools

## Overview

This report is a comprehensive exploration of the **Open Source Data Engineering Landscape 2024**. It provides an overview of the major categories of open-source data engineering tools, such as **Storage Systems**, **Data Integration**, **Analytics and Visualization**, and more. Additionally, the report includes detailed descriptions of three specific categories of tools that are particularly interesting: **Data Processing and Computation**, **ML/AI Platforms**, and **Analytics and Visualization**.

The goal of the report is to familiarize you with the vast ecosystem of data engineering tools while providing insights into their unique characteristics, usage, and examples of open-source projects. The report also reflects on the importance of these tools in modern businesses and how they differ from traditional relational OLTP databases. You’ll see why each tool category plays a crucial role in data-driven decision-making and operational efficiency.

## Rendering Quarto Files

Quarto is a powerful tool that allows you to render `.qmd` files (Quarto Markdown) into various formats like HTML, PDF, or even Word documents. This report is built using Quarto, and to complete your assignment, you'll need to render the final output to HTML.

### Steps to Render the Quarto File:

1. Open the command line or terminal.
2. Navigate to the `SRC` folder where your `report.qmd` file is located.
3. Run the following command to render the `.qmd` file into an HTML document:

   ```bash
   quarto render report.qmd --to html


* GITHUB provides [good explanations of README.md'(https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-readmes) files,

* Here is a list of example *awesome* README files: <https://github.com/matiassingers/awesome-readme>

Part of your score for this assignment is how well you update/modify this README.

## Files and Folders

*./src* - contains the scaffold QMD file homework 1. Your job is to modify this document and render it to *html*.  The *html* file will
be created in the same *./src* folder.

*./samples* - contains several QMD files. Your job is to render these files and exam the output.  Output for these files will be in the *./docs* folder.

*./docs* - contains resulting files from quarto render operations.  *You should NEVER directly store files in ./docs.* Rather, you should let Quarto maintain the contents of the *./docs* folder using settings in the quarto project file, *_quarto.yml*.

## Confusion
The instructions said two different things. One to place the report in report and assets in the assets. The other said to keep it in src. I will be doing both.