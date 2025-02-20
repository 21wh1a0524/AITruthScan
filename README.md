# AI Truth Scan

## Introduction
In this comprehensive approach, I utilize advanced AI techniques to tackle the growing challenge of deepfake images. By leveraging machine learning algorithms and neural networks, this project aims to identify and mitigate the impact of manipulated images. You'll find detailed documentation, code implementations, and datasets used to train and test our models. Whether you're a researcher, developer, or just curious about AI's role in combating digital misinformation, this repository offers valuable insights and tools to understand and counter deepfakes effectively.

## Usage
**1. Clone the repository:** Clone the repository to your local machine.<br>
**2. Install Dependancies:** Install required dependancies.<br>
**3. Run the Application:** Start the application using Streamlit by running the following command in your terminal:
`
  streamlit run app.py
`
<br>
**4. Open the Application:** After running the command a new tab will automatically open in your default web browser.<br>
**5. Upload an Image:** In the web application you'll find an interface to upload an image. Browse and select the image you want to analyze for deepfake detection.<br>
**6. Analyze the Image:** Once the image is uploaded, the tool will process it and provide you with a result indicating whether the image is a deepfake or real.<br>

## Result Snapshots
The project's introduction and goal are displayed in the front-end user interface (UI) of the model, which is displayed when we run the command streamlit run app.py.<br>
![Screenshot 2024-07-23 210810](https://github.com/user-attachments/assets/a6accefd-e20d-45db-b639-2c6e755ebc23)<br>
Then, in order for the user to determine if an image is real or fake, they must select one from the testing images that have been trained into the model.<br>
![Screenshot 2024-07-23 210853](https://github.com/user-attachments/assets/80529dfd-b428-434e-bd71-246aac435a7f)<br>
The model will identify the selected image for detection as real if it is, and it will provide the outcome as real along with an explanation of why it is real.<br>
![Screenshot 2024-06-09 173651](https://github.com/user-attachments/assets/c5e084a8-c33f-4d6d-84ee-27016760d58e)<br>
The model will identify the selected image for detection as fake and present the output as fake along with an explanation of why it is fake.<br>
![Screenshot 2024-06-09 173818](https://github.com/user-attachments/assets/2336d6df-7ebc-4cda-939b-f9da21e5a22b)

