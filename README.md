# Hybrid-Deep-Face-Music-Recommendation-Using-Emotions

This project is used to detect user's emotion and suggest a music playlist based on the emotion detected. It also provides YouTube link to the songs as well. 

## Flow Chart for Emotion Recognition

<img width="226" alt="Screenshot 2022-10-08 155307" src="https://user-images.githubusercontent.com/79396759/194706231-fa9c5c4a-759f-43fb-a9b4-728734ac105c.png">

The detection and facial emotion recognition of user's emotion is identified using a pre-trained model called Deep Face and OpenCV. Deep Face recognizes seven emotions - happy, neutral, angry, disgust, fear, sad, and surprise. Cascade classifier is used to train the images and Haar cascade is to identify the face and eyes which is a pre-trained model which is used to draw a box on the face identified in the image. The dominant emotion is displayed and that is the emotion detected. The accuracy of this is 97%.

## Architectural Diagram for Music Recommendation

<img width="293" alt="Screenshot 2022-10-08 155406" src="https://user-images.githubusercontent.com/79396759/194706271-8e4c297b-26e9-405e-ae4d-18e382d38e94.png">

The seven emotions - happy, neutral, angry, disgust, fear, sad, and surprise are broadly divided into two main emotions that are happy and sad for convenience. K-means clustering is used to cluster the songs into two clusters – happy and sad. The dataset used here is Kaggle Spotify Dataset. Then the YouTube link is displayed along with the music playlist based on the emotion detected. The accuracy for this model is 99.9% for testing and 99.5% for training.
