# WebCam-Face-Emotion-Detection-Streamlit
Real time face detection streamlit based bew application for server deployment.

##How to Run : 

Step 1: Clone the repository <br>
Step 2: Install requirement.txt <br>
Step 3: run app.py with the command : streamlit run app.py

##Problems With The Deployment : 


The Bundle Size is too big for compression despite replacing of the tensorflow module to tensorflow-cpu. <br>
Therefore the model can only be hosted in the premium tire of Heroku or AWS ES2 module. <br>
I tried using docker and that failed. Looks like docker can't really hold moules of this category. <br>
Streamli sharing won't work either as it is only ideal for single page streamlit applications.

#Anyways if anyone manages to make the hosting please commit to this readme file with the link. The ML model is basic and uses pre-defined libraries of trained and tested models and works in the API -> Server -> Client using the  automated libraries of streamlit. You can add custom markdown on streamlit apps and can even ecentrisize react front-end.

####hank You#####
