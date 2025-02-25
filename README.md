# Access to Health Facilities from IDP Sites

This paper explores the use of computational approaches to estimate travel times from Internally Displaced Persons (IDP) sites to health facilities, using Mozambique as a case study. By comparing these computational estimates with key-informant data, we aim to validate and improve data collection processes. The study identifies priority locations for further investigation of barriers to access and proposes a tool to enhance data quality and provide analytical insights for humanitarian actors. The findings highlight the potential of computational methods to complement traditional survey approaches and inform humanitarian decision-making and planning.

Follow the instructions below to run the (messy)code from the paper.

## Getting started

1. Install [Quarto](https://quarto.org/docs/get-started/), the tool/format for publishing to different formats
2. Install [Pixi](https://pixi.sh/latest/) to manage packages. On MacOS `curl -fsSL https://pixi.sh/install.sh | bash` and on Windows Powershell: `iwr -useb https://pixi.sh/install.ps1 | iex`
3. Run `pixi init .` to create a new Pixi project. It creates a pixi.toml and pixi.lock file.
3. Run `pixi add <packagename>` to add pacakges. Example: `pixi add python ruff polars matploltib requests` 
4. Do exploration in notebooks - ipynb's will keep cell output, which is good for exploratory analysis but is messy for version control.
5. When code is maturing, move it to files in src. The examples can be changed as needed.
6. Create quarto files for the analysis and formats you want, calling the code from src - dashboards, websites, pptx pdf.
7. Run `quarto render` in the quarto directory to render the quarto files and check that the outputs appear in the Reports directory.
8. If you wish to publish a directory as a static site, you can use this [Github Action](https://github.com/peaceiris/actions-gh-pages) to copy a directory to a gh-pages branch, which you can then configure using Github Pages.

## Structure
![image](https://github.com/user-attachments/assets/e7b8b320-1f49-49f5-b495-0b0fe38b0b90)
