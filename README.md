<div align="center">
<h1 align="center">
<img src="https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/ec559a9f6bfd399b82bb44393651661b08aaf7ba/icons/folder-markdown-open.svg" width="100" />
<br>Project_6
<br>Automatically classify consumer goods based on textual and visual data (NLP & CV)
</h1>
<h3>◦ Developed with the software and tools listed below.</h3>

<p align="center">
<img src="https://img.shields.io/badge/Jupyter-F37626.svg?style&logo=Jupyter&logoColor=white" alt="Jupyter" />
</p>
<img src="https://img.shields.io/github/languages/top/chanthbouala/Project_6?style&color=5D6D7E" alt="GitHub top language" />
<img src="https://img.shields.io/github/languages/code-size/chanthbouala/Project_6?style&color=5D6D7E" alt="GitHub code size in bytes" />
<img src="https://img.shields.io/github/commit-activity/m/chanthbouala/Project_6?style&color=5D6D7E" alt="GitHub commit activity" />
<img src="https://img.shields.io/github/license/chanthbouala/Project_6?style&color=5D6D7E" alt="GitHub license" />
</div>

---

## 📒 Table of Contents
- [📒 Table of Contents](#-table-of-contents)
- [📍 Overview](#-overview)
- [⚙️ Features](#-features)
- [📂 Project Structure](#project-structure)
- [🧩 Modules](#modules)
- [🚀 Getting Started](#-getting-started)
- [🗺 Roadmap](#-roadmap)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)
- [👏 Acknowledgments](#-acknowledgments)

---


## 📍 Overview

### Mission: Automatically classify consumer goods based on textual and visual data (NLP & CV)
**Context**  
You are a Data Scientist with the company "Place de marché", which wants to launch an e-commerce marketplace. On the marketplace, sellers offer items to buyers by posting a photo and a description. For the time being, the category of an item is assigned manually by the sellers, and is therefore unreliable. On top of that, the volume of items is very small at the moment. To make the user experience for sellers (making it easier to put new items online) and buyers (making it easier to find products) as smooth as possible, and with a view to scaling up, **we need to automate this task**.  
Linda, Lead Data Scientist, has asked you to study the **feasibility of an engine for classifying items** into different categories, with a sufficient level of precision. Here's the email she sent you:  

"_Hello_,  
_Thank you for your help with this project! Your task is to carry out an **initial feasibility study of an article classification engine**, based on an image and a description, to automate the assignment of the article category.  
You will have to **analyse the dataset** by **pre-processing the product descriptions and images**, **performing dimension reduction** and then **clustering**. The results of the dimension reduction and clustering will be presented in the form of two-dimensional graphs, and confirmed by a similarity calculation between the actual categories and the clusters. These results will illustrate that the extracted characteristics can be used to group products in the same category.  
Could you use this modelling approach to demonstrate the feasibility of automatically grouping products in the same category?_  
_Here are the constraints:_  
  _In order to extract the text features, it will be necessary to implement:_  
  - _two **bag-of-words** approaches, **simple word count and Tf-idf**;_
  - _a classic **word/sentence embedding** approach with **Word2Vec** (or Glove or FastText);_
  - _a word/sentence embedding approach with **BERT**;_
  - _a word/sentence embedding approach with **USE** (Universal Sentence Encoder)._  

_In the attachment, you will find an example of the implementation of these approaches on another dataset. I encourage you to use it as a starting point, it will save you a lot of time!  
  To extract the image features, you will need to use:_ 
  - _a **SIFT / ORB / SURF algorithm**;_
  - _a **CNN Transfer Learning algorithm**._  

_Thanks again,  
Linda  
P.S.: I'd like to stress that we don't need a supervised classification engine at this stage, but a feasibility study!  
Attachments:_  
 - _[First dataset of articles with the link to download the photo and an associated description](https://s3-eu-west-1.amazonaws.com/static.oc-static.com/prod/courses/files/Parcours_data_scientist/Projet+-+Textimage+DAS+V2/Dataset+projet+pre%CC%81traitement+textes+images.zip)_  
 - _[A notebook of examples of implementation of these approaches](https://s3.eu-west-1.amazonaws.com/course.oc-static.com/projects/Data_Scientist_P6/Exemple_Tweets_Feature-extraction_Sentence+Embedding_V1.1.ipynb)  
Good luck!"_  

Deliverables:  
  - A **notebook** (or .py files) containing the functions used to pre-process the text and image data and the clustering results (including graphical representations). 
  - A **presentation** presenting the clustering approach and results.

---

## ⚙️ Features


---


## 📂 Project Structure




---

## 🧩 Modules

<details closed><summary>Root</summary>

| File                                                                       | Summary                                 |
| ---                                                                        | ---                                     |
| [P7.ipynb](https://github.com/chanthbouala/P7_notebook/blob/main/P7.ipynb) | Prompt exceeds max token limit: 872857. |

</details>

---

## 🚀 Getting Started

### ✔️ Prerequisites


### 📦 Installation

1. Clone the P7_notebook repository:
```sh
git clone https://github.com/chanthbouala/Project_6
```

2. Change to the project directory:
```sh
cd Project_6
```

3. Install the dependencies:
```sh
pip install -r requirements.txt
```

### 🎮 Using P7_notebook

```sh
jupyter nbconvert --execute P7.ipynb
```

---


## 🗺 Roadmap

---

## 🤝 Contributing

Contributions are always welcome! Please follow these steps:
1. Fork the project repository. This creates a copy of the project on your account that you can modify without affecting the original project.
2. Clone the forked repository to your local machine using a Git client like Git or GitHub Desktop.
3. Create a new branch with a descriptive name (e.g., `new-feature-branch` or `bugfix-issue-123`).
```sh
git checkout -b new-feature-branch
```
4. Make changes to the project's codebase.
5. Commit your changes to your local branch with a clear commit message that explains the changes you've made.
```sh
git commit -m 'Implemented new feature.'
```
6. Push your changes to your forked repository on GitHub using the following command
```sh
git push origin new-feature-branch
```
7. Create a new pull request to the original project repository. In the pull request, describe the changes you've made and why they're necessary.
The project maintainers will review your changes and provide feedback or merge them into the main branch.

---

## 📄 License

This project is licensed under the `GNU GPL` License. 

---

## 👏 Acknowledgments


---
