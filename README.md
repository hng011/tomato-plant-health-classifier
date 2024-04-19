# Tomato Plant Health Classifier 🍅
A deep learning model using CNN to predict the health of tomato plants based on a leaf image. Divided into 3 classes:
1. tomato_early_blight: Indicates the presence of disease symptoms in the tomato plant
2. tomato_healthy: Indicates a healthy tomato plant
3. tomato_late_blight: Indicates that the tomato plant is diseased
<br/><br/>

# Results
### Model 1
![alt text](history_1-plot.png)<br>
Accuracy: 94.84%<br>
Validation Accuracy: 96.58%<br>
Loss: 19.30%<br>
Validation Loss: 13.21%<br>
<br><br>

### Model 2
![alt text](history_2-plot.png)<br>
Accuracy: 94.65%<br>
Validation Accuracy: 93.45%<br>
Loss: 19.31%<br>
Validation Loss: 19.26%<br>
<br><br>

> Dataset<br>
https://www.kaggle.com/datasets/arjuntejaswi/plant-village<br>

> Docker Image: <br>
https://hub.docker.com/repository/docker/hng011/ai/general

### Notes: 
I utilize only three datasets, which consist of:<br>

1. Tomato_Early_blight
2. Tomato_Late_blight
3. Tomato_healthy