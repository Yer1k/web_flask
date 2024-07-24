# Translator App Flask via Azure AI
This is a simple translator app using Flask and Azure AI. The app is able to translate text from the language you have inputted to another.

<p align="center">
  <img src="/screenshots/demo.gif" alt="demo" width="800">
</p>

## Prerequisites
- Python 3.6 or higher
- Azure subscription
- Azure Translator Text API key

## Installation
1. Clone the repository
2. Install the required packages
```bash
pip install -r requirements.txt
```
3. Set the environment variables
```bash
export KEY=<your-azure-text-translator-api-key>
export ENDPOINT=<your-azure-text-translator-endpoint>
export LOCATION=<your-azure-text-translator-location>
```
For example:
[!keys](/screenshots/key.png)

4. Run the app
```bash
flask run
```
5. Open your browser and go to `http://127.0.0.1:5000`

6. Enter the text you want to translate and select the target languages. The language of the text you have entered should be auto-detected. Click the `Translate` button to see the translated text.