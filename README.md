# KineX

![image](https://github.com/user-attachments/assets/7643de3e-bf1e-4c6c-9fcc-b88ddc99f5ff)

This is the repository for the backend of KineX AI. 

Recommendation LLM:
- The file titled "Recommendation_LLM" contains the code that is used for the "Ask for Exercises"
- This requires the import of the training_data and test_data JSON files into the runtime to train the LLM
- Includes exercise recommendation and explanation, along with video from physical therapist

Pose Estimation:
- This code shows how we are able to take real time video, gifs, and recording to analyze angles and movement of patients
- Using our pose estimation model, we are able to correct patients and summarize their PT sessions
- The red/green lines track the body and indicate correct vs incorrect movement. 

Demo Video:
- The full video of the app demo with functionalities and features is included in the demo_video file
- A short gif version of the demo is below.


![short_demo](https://github.com/user-attachments/assets/6ccc5ca0-d87e-465d-849f-8686e0b6c175)

Wearable Tech:
- The app uses wearable tech data (such as smartwatches, trackers) to account for movement and further fine tune the AI based analysis
- This is an optional feature, but will only improve a patients user experience and provide another dimension of data

Movement:
- Outputs movement data for good versus bad movements, based on time stamp and video performance
- Tracks the user's movement so they can look back at it and correct based on angle, extension, etc. 



