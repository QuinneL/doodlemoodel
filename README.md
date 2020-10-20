# doodlemoodel
Description
Our goal is to make a classifier that can identify the contents of a doodle. We will start with the Google QuickDraw open source data, which gives us information about crowd-sourced drawings. For each drawing, we know each stroke of the sketch in (x,y) coordinate pairs along with the time of each pixel is drawn. 

Given this raw data, we will create feature vectors for each sketch to pass into our neural network using PyTorch. We plan on creating and training a neural network that will classify our chosen feature vectors. Our overall goal is to create an API that will take in drawn sketches and use the stroke information of the sketches to classify the drawing and output a label. 

If the API works successfully, we can extend it to take in a stream and output a constantly updating prediction of the contents of the drawing. This can be applied to interactive drawing programs like skribbl.io to identify drawings in real time.
