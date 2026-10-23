# Predicting gender using linguistic features and keystroke dynamics

## 📖 About

This repository contains the data and code needed to run the analysis in the following paper [insert super cool paper]. 

The data was obtained from the KLiCKe corpus, which contains ~5,000 argumentative essays written in English by adult writers from the US. For more information, see the following GitHub repository: https://github.com/terryyutian/KLiCKe-Corpus

## Project overview

The following repository is structured as such:

| Folder/File   | Description   |
| ------------- | ------------- |
| ```data/```   | contains essays and detailed keystroke logs  |
| ```plots/```  | contains figures from paper  |
| ```results/```  | contains results from analysis (F1, precision, recall, etc.)  |
| ```src/```  | python scripts related to the project  |


## 💻 Technical Requirements

The analysis was run on UCloud... (add more stuff here)

## 🛠️ Setup
Prior to running the code, run the following code below to (1) create a virtual environment (venv) and (2) download the required packages.

```bash setup.sh```

## 🚀 Usage

To run any script in the src folder, you can type specify the script's path in the terminal (with the .venv active):

```{python}
# activate env
source .venv/bin/activate

# run script
python src/main.py

# quit env 
deactivate
```

## 🌟 Acknowledgements

Thanks to Mina for making a very nice template for this! :D
