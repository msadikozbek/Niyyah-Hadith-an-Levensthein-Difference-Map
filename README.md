# Algorithmic Approach to Hadith Textual Criticism

This repository contains the Python script and dataset used for the computational textual criticism of the "Niyyah (Intention) Hadith" across seven different transmissions in al-Bukhari's *al-Jami' al-Sahih*.

## Methodology
The script applies a **Word-Level Levenshtein Edit Distance** algorithm to calculate the structural differences between a reference text and other transmissions. It systematically identifies:
* **Insertions (Ziyada):** Highlighted in Green
* **Deletions (Nuqsan/Ihtisar):** Strikethrough and highlighted in Red
* **Substitutions (Ibdal):** Highlighted in Yellow

## Reproducibility
To ensure full reproducibility, the script requires no local installation. It is designed to run completely in the browser via Google Colab. 

You can run the analysis and reproduce the visual Difference Maps by clicking the badge below:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1OxduTUX7X6RW0017c0iVvTXS7Cvc3lJ8#scrollTo=gdwDH_BrdF83)

## Dependencies
* Python 3.x
* `re` (Built-in regex module)
* `IPython.display` (For rendering HTML in Jupyter environments)
