# HandwrittenTextRecognition

The Handwritten Text Recognition system is implemented as follows:
  Dataset Collection and Preprocessing: Download and preprocess the IAM dataset (resize, normalize, and label the data).
  Data modelling: Building the HTR model using CNNs and BiLSTMs with CTC loss.
  Model Training: Training the prepared model. 
  Backend: Set up a Flask server that accepts image uploads, processes them with the trained model, and returns recognized text
  Frontend: Create an HTML interface where users can upload images and view the predicted text.
  Deployment: Host the backend and frontend on a cloud platform for production use.

