# Gemini-Powered-Image-Chatbot
-----------------------------
### App Link - https://gemini-vision-chatbot.streamlit.app/
--------
#### NOTE: At the first time, it will display "This app has gone to sleep due to inactivity. Would you like to wake it back up? Yes, get this app back up!" Then click on the "Yes, get this app back up!" button.

![gemini-vision](https://github.com/user-attachments/assets/181eb149-403a-4c47-98bf-e8d065d3a2bf)

This project demonstrates a chatbot application using Google's Generative AI (Gemini Flash). It allows users to upload an image and ask questions related to the image, receiving AI-generated responses.

#### Features
+ Interactive Interface: Utilizes Streamlit for a user-friendly web interface.
+ Image Upload: Supports uploading of images in JPG, PNG, and JPEG formats.
+ Real-time Responses: Generates responses to user queries about the uploaded image using the Google Gemini Flash model.
+ Center-aligned Title: A visually appealing title showcasing Google's branding colors.

#### Usage
+ Upload Image: Upload an image using the file uploader.
+ Input Query: Type your question in the text input box related to the uploaded image.
+ Submit: Click the **Get Response** button to see the AI's response.
+ Results: The app will display the uploaded image and the AI's response to your query.

#### Example
+ Input: Upload an image of a sunset and ask, What can you tell me about this image?
+ Output:
Image: Displayed in the app.
Gemini Flash: This is a beautiful sunset with vibrant colors and clear skies.

#### Dependencies
+ google-generativeai
+ streamlit
+ Pillow
+ Configuration
Ensure you have a valid API key for Google Generative AI. Replace the placeholder YOUR_GOOGLE_API_KEY in the code with your actual API key.

#### Acknowledgments
+ Google Generative AI: For providing the Gemini Flash model.
+ Streamlit: For the easy-to-use web application framework.
+ Pillow: For image processing capabilities.

