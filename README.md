# Emotion-Based Music Recommender using Streamlit and WebRTC

The "Emotion Based Music Recommender" is a web application built using Streamlit, WebRTC, and various AI libraries. The application is designed to capture a user's facial expressions, analyze their emotions, and recommend songs based on their emotional state. The recommender system is integrated with YouTube for music recommendations, and the user can specify the language and singer preferences to narrow down the song suggestions.

## How It Works

1. **Emotion Detection**: The application utilizes the MediaPipe Holistic model for facial landmark detection to capture the user's facial expressions. It identifies emotions from the detected facial landmarks using a pre-trained deep learning model.

2. **WebRTC Integration**: WebRTC (Web Real-Time Communication) is employed to enable real-time video streaming from the user's device camera. This allows the application to capture the user's facial expressions continuously.

3. **AI-Based Emotion Analysis**: The captured video frames are processed using the Holistic model to extract facial landmarks and hand landmarks. The coordinates of these landmarks are used to create a feature vector, which is fed into a pre-trained emotion recognition model.

4. **Music Recommendation**: Once the user's emotion is determined, the application recommends songs based on the detected emotion, specified language, and preferred singer. The user can trigger the recommendation process by clicking the "Recommend me songs" button.

5. **YouTube Integration**: The application generates a YouTube search query based on the detected emotion, specified language, and preferred singer. The user is redirected to YouTube's search results page, where they can explore the recommended songs.

## Usage

1. Access the "Emotion Based Music Recommender" web application.

2. Allow the application to access your device's camera to capture your facial expressions.

3. Specify your preferred language and singer for the music recommendations.

4. The application will continuously detect and analyze your emotions based on your facial expressions.

5. Click the "Recommend me songs" button to view music recommendations that match your emotional state, language, and singer preferences.

6. The application will open the YouTube search results page with the recommended songs.

7. Note: The application may ask for permission to access your camera for facial expression analysis.

## Dependencies

The "Emotion Based Music Recommender" utilizes the following Python libraries and models:

- Streamlit: For building the web application interface.
- WebRTC: For real-time video streaming and capturing from the user's camera.
- OpenCV: For video frame processing and image manipulation.
- NumPy: For numerical computations and array operations.
- Mediapipe: For the Holistic and Hand tracking models used in facial and hand landmark detection.
- Keras: For loading the pre-trained deep learning model for emotion recognition.
- YouTube (webbrowser): For redirecting the user to YouTube search results with music recommendations.

## Credits

This web application was designed and developed by Vansh Malhotra as a demonstration of integrating real-time emotion analysis and AI-based music recommendations. The AI model used for emotion recognition is trained using a dataset of facial landmarks and emotions.

For any questions or feedback, please feel free to contact vanshmalhotra353@gmail.com.
