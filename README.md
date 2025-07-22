# Movie-Recommendation-and-Review-Prediction📽️
This project is a Multinomial Naive Bayes application that lets you classify your own movie reviews and receive movie recommendations. The program is built using Python (3.10.9). To generate a new trained model (.pickle file), delete the existing pickle file and run the program to create a new one.

## 📜Features 
The program's menu includes 4 main features:
1. **Write Review** - Write your own movie review and the model will predict wether it's positive or negative
2. **View Movie Recommendation** - The model will give you 2 movie recommendations based on the review you write
3. **View Named Entity Recognition** - Display entity tags such as language and location, along with the corresponding entity items present in the review.
4. **Exit** - Close the program

## Python Setup
1. Install [Python 3.10.9](https://www.python.org/downloads/release/python-3109/)
2. Choose a folder to create a *Python environment*
3. Move/Copy [requirements.txt](https://github.com/user-attachments/files/21361586/requirements.txt) to the folder
> Some of the libraries may not be used for this project
4. Click on the folder path and type "cmd" to open a command prompt
5. Create a virtual environment using this command
```bash
python -m venv environments/nlp
```
6. Run the virtual environment
```bash
environments\nlp\Scripts\activate.bat
```
7. Download a library in the command prompt
```bash
pip install -r requirements.txt
```

## How to install "en_core_web_sm" in Visual Studio Code
1. Go to Visual Studio Code terminal
2. Run this code to make sure spacy is installed
```bash
pip install spacy
```
3. Download the en_core_web_sm with this code
```bash
python -m spacy download en_core_web_sm
```

## Shortcut to open project folder in Visual Studio Code:
1. Click on the project folder path and type this code:
```bash
cmd
```
2. Press ENTER
> This will open a command prompt

3. Type in this code on the command prompt:
```bash
code .
```
4. Press ENTER
> This will open Visual Studio Code
