Maritime Navigator 🚢

Maritime Navigator is an application designed to predict maritime traffic conditions on specific routes, given weather conditions and the desired date. It utilizes TabNet, a deep learning architecture, to analyze data and generate predictions. The application bridges its backend and frontend seamlessly using Gradio, enabling easy interaction and visualization.

Features ✨

	•	Predicts maritime traffic for specific routes on a given day.
	•	Incorporates weather conditions into predictions.
	•	Uses the TabNet architecture for accurate and efficient deep learning.
	•	Interactive Gradio interface for user-friendly predictions.
	•	Fully hosted and runnable on Google Colab.

How It Works 🔍

The workflow involves two stages:

	1.	Training the Model:
		•	A TabNet deep learning model is trained on maritime data to learn traffic patterns under various weather conditions.
	2.	Making Predictions:
		•	The trained model predicts maritime traffic for a given route and date using user-provided data.

Prerequisites 🛠️

	•	A Google account to access Google Colab.
	•	Basic familiarity with running code in Google Colab.

How to Run the Application 🚀

Step 1: Train the Model

	1.	Open the following Colab notebook:

			https://colab.research.google.com/drive/1taEETPduFLiJBN4OU0uRzq3mPtxl6J7D?usp=sharing

	2.	Run each block of code sequentially:
		•	Follow the prompts and ensure that all dependencies are installed.
		•	At the end of execution, a trained model file (model.pt) will be downloaded to your computer.

Step 2: Use the Trained Model

	1.	Open the second Colab notebook:
 
			https://colab.research.google.com/drive/1taEETPduFLiJBN4OU0uRzq3mPtxl6J7D?usp=sharing

	2.	Run each block of code sequentially:
   		•	When prompted, upload the trained model file downloaded earlier (model.pt).
  		•	Provide the required data inputs (route, date, and weather conditions).
		•	The code will process the inputs and display the maritime traffic predictions.

Experimentation ⚡

Feel free to experiment with different values in the dataset provided in the Prediction Notebook to observe how traffic predictions vary with input parameters.

Technologies Used 🖥️

	•	TabNet: Deep learning architecture for tabular data.
	•	Gradio: Frontend framework for linking machine learning models to user interfaces.
	•	Google Colab: Cloud-based environment for running Python code.

Future Improvements 🚀

	•	Expand prediction capabilities to include multiple routes simultaneously.
	•	Integrate live weather data from external APIs for real-time predictions.
	•	Deploy the application as a standalone web or mobile app.
