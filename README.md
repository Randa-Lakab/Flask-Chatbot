# 💬 Flask Chatbot using DialoGPT

This is a simple AI-powered chatbot built with Python, Flask, and Hugging Face's DialoGPT model. Users can interact with the chatbot through a clean web interface running on their local machine.



## ✅ How to Run This Project (Step-by-Step)

Follow these steps to run the chatbot on your computer:

## 1. Make sure Python is installed

Check if Python is installed by running:

```bash
python --version
If not, download and install it from: https://www.python.org

## 2. Install required libraries
Open a terminal or command prompt and run:

bash
Copier
Modifier
pip install flask torch transformers

## 3. Start the chatbot server
In the same terminal, run the following command from the folder where app.py is located:

bash
Copier
Modifier
python app.py
You should see something like this:

csharp
Copier
Modifier
 * Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)

## 4. Open the chatbot in your browser
Open your web browser and go to:

cpp
Copier
Modifier
http://127.0.0.1:5000/
You’ll see a simple chat interface where you can start talking to the AI.

## 5. Chat with the AI
Type a message in the text box.

Click the "Send" button.

The chatbot will respond instantly on the same page.

## 🧠 Notes
The first time you run the app, it may take a little longer because the model is being downloaded.

You must stay connected to the internet during the first launch.

The app runs locally — no data is sent to any server.

##❓ Need Help?
If you face any issues running the chatbot:

Make sure you're using the latest version of Python.

Check that all libraries are installed correctly.

Ensure the browser is pointing to http://127.0.0.1:5000/.