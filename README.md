# ASCVIT V1 APP
## Automatic Statistical Calculation, Visualization, and Interpretation Tool
#Ref= https://towardsdatascience.com/ascvit-v1-automatic-statistical-calculation-visualization-and-interpretation-tool-aa910001a3a7

The repository is based on the article published at [Towards Data Science](https://medium.com/towards-data-science/ascvit-v1-automatic-statistical-calculation-visualization-and-interpretation-tool-aa910001a3a7). In this article, I discuss the development of a first version (V1) of a local app that can be used to automatically apply various statistical methods to any datasets. This is an open source project for educational and research purposes.

### The following statistical procedures are supported by the first Version:
![ASCVIT V1 Overview of analysis methods (Image by author)](images/ASCVITV1_Overview.png)

The code to run the app is already in the repository as well as a script to remove missing values from data records. Below is a short GIF showing the structure and function of the app.

![ASCVIT V! (Gif by author](images/ASCVITV1.gif)

## Installing and running the application 
1. clone this repository on your local computer: 
```bash 
git clone https://github.com/stefanpietrusky/ascvitv1.git
```
2. install the required dependencies:
```bash 
pip install -r requirements.txt
```
3. install Ollama and load the model [Llama3.1](https://ollama.com/library/llama3.1) (8B)
4. start the Streamlit app:
```bash 
streamlit run app.py
```
