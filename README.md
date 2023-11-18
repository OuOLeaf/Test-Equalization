<h1 align="center">📊 Item Response Theory (IRT) Analytics in UI 🔍</h1>

# 💡 Introduction

This is an software application that performs **test equalization**.

The application can quantify the respondents' ability by showing their predictive count of correctly answered questions.

# 🌟 Features

> **Note**: The following are the demo version and have altered layouts and data for demonstration.

## 📁 1. File Explorer

Prepare the training data for the model with an intuitive File Explorer interface.

<div align="center">
    <img src="https://github.com/OuOLeaf/Testing_Equalization/blob/main/readme-gif/File_Explorer.gif" alt="File Explorer Demo"/>
</div>

## 📈 2. IRT Model Analyze & Visualize

Upon clicking the execution button, it proceeds with two primary functions:
1. **Training**: The IRT (Item Response Theory) model undergoes training
2. **Redirection**: Users are automatically redirected to the report page designed for visualization and search table.


<div align="center">
    <img src="https://github.com/OuOLeaf/Testing_Equalization/blob/main/readme-gif/IRT_Analyze_Visualize.gif" alt="IRT Model Analysis and Visualization"/>
</div>

## 📊 3. Interactive Graph

Offer an interactive graph that dynamically illustrates the relationship between the number of correctly answered questions and the abilities of respondents.

- **Sliders**: Users can manipulate sliders to observe variations in these metrics.
- **Visualization**: The graph responds instantly to slider adjustments, providing real-time insights into the data.

<div align="center">
    <img src="https://github.com/OuOLeaf/Testing_Equalization/blob/main/readme-gif/Interactive_Graph.gif" alt="Interactive Graph"/>
</div>

## 🔍 4. Search Table

Designed for conducting real-time searches with a specific focus:

- **Ability Level Specification**: Users can specify an ability level as a search parameter.
- **Targeted Results**: The search predicted the count of correctly answered questions associated with the specified ability level.


<div align="center">
    <img src="https://github.com/OuOLeaf/Testing_Equalization/blob/main/readme-gif/Real_time_Search_Table.gif" alt="Real-time Search Table"/>
</div>


### 🏆 Achievements

- **📈 IRT Model Training**: 
  - Developed and integrated a real-time Item Response Theory (IRT) model in the UI.
  - Utilized Bayesian estimation techniques for dynamic model adaptation.
  - Predicted the count of correctly answered questions given a student's ability.
  
- **🌐 UI Design**:
  - Created a user-friendly interface that significantly streamlined statistical analysis.
  - Facilitated immediate feedback and specific search.

### 📚 Python Libraries Utilized

- **📘 Girth**: Item Response Theory (IRT) model analysis. [Girth on PyPI](https://pypi.org/project/girth/)
- **🖥️ PyQt5**: Creation of the user interface. [PyQt5 Information](https://pypi.org/project/PyQt5/)





