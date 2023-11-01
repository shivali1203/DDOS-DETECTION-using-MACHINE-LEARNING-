# DDOS-DETECTION-using-MACHINE-LEARNING
This project uses a simple feedforward network to determine if incoming network packets are from one of four types of ddos attacks or are a normal request.

# Dataset Download:
You can download the dataset used in this project here:
[Dataset link](https://drive.google.com/drive/folders/1BqMKyKUgc1U6hpfzsAAKODyG_6bAChU_?usp=sharing)

# Example lines of data:
36.850655,36.85372,36.863775,0.003065,1016.449678,703384,692,0.060108,0.037172,36.84,36.877172,1,9.960601,UDP-Flood
24.11,11,573923,24,23,ack,55,-------,12,15981,16103,885665,server1,Router,49.649341,49.649341,49.659344,0,328.522947,18068.8,55,0.008446,0,49.649341,49.67935,1.030019,50.046382,Normal

# Model accuracy:
Training loss & accuracy: [1.6756146636651195, 0.8960413987239542]
![model_accuracy](https://raw.githubusercontent.com/jacobvs/DDOS-ML-Detection/master/model_accuracy.jpg)
