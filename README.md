# PEACIFY

![ezgif com-gif-maker (1)](https://user-images.githubusercontent.com/75724727/170585388-2d15ab99-4636-43d4-af39-1d5c523a2e11.gif)


## INSPIRATION
1. In this world so full of stress and chaos, everyone aims at getting peace.
2. **Peacify** gives you the same, by detecting your emotions and gives recommendations to entertain you, and in turn peacify you by its various features.
3. Genre Based Movies,Books,Songs , Emotion based Movies , Books,Songs, Chatting feature with friends, Give your static images some movement through GIFs,Chatbot Assistance,Light and Dark UI and many more.

# FEATURES WITH SCREENSHOTS-

 # Light/ Dark UI-

![1](https://user-images.githubusercontent.com/75724727/169809474-0f0d39e8-007c-4d31-a15c-b4dd0a0de356.png)

![2](https://user-images.githubusercontent.com/75724727/169809578-b99ff59e-3bde-4eb5-b6d9-888ff07b6ac4.png)

![3](https://user-images.githubusercontent.com/75724727/169809630-c28335b6-1190-4496-bdd5-861e1e301992.png)

 # Live Camera emotion Detection- Happy, Sad, Angry, Disgust, Surprise,Fear, Neutral-

![ Emotions Detected](https://user-images.githubusercontent.com/75724727/169809743-12d471e4-6cc0-4fa7-9c62-e4e075f84165.png)


 # Recommend IMDB Movies, Spotify Songs, ZLibrary Books based on Emotions-

![Options](https://user-images.githubusercontent.com/75724727/169809837-2c8bba45-4de7-414a-8109-4bbf25e3d03e.png)

![Options2](https://user-images.githubusercontent.com/75724727/169809902-0176c35e-6d86-4c85-bab6-560d2a3ea5a8.png)

 # Chat with upto 20 users, Notifaction sound, Login/Sign Up, Send attachment, emoji, react, Claim Profile, See no of users online, have seperate chat rooms-

![Chat Features](https://user-images.githubusercontent.com/75724727/169809937-fc4e0eb0-f5bb-4db6-b589-5a09f4be6e4f.png)

 # Give your face movement- Convert jpg images to moving gif-

![Relive your face](https://user-images.githubusercontent.com/75724727/169809981-520aaec8-c83e-4d2e-8dc9-559dbe7cdb81.png)

 # Get Genre Based recommendation of Songs, Movies, Books- Comedy, Action, Romantic-

![Genre based](https://user-images.githubusercontent.com/75724727/169810050-03dfc9f6-70fa-4fa6-8960-9f8e5c103128.png)

 # AI Powered ChatBot to assist you how to access website features-

![Chatbot](https://user-images.githubusercontent.com/75724727/169810076-52774a17-5c95-471d-bf0c-f3e3fc22b32a.png)

 # Know More About Me- Directs to my Linkedin and Github-

![Connect With Me](https://user-images.githubusercontent.com/75724727/169810158-5cabf831-f425-43c3-8a03-b08ad531a5b2.png)

## FEATURES WITH DEMO-
**Peacify** is a facial expression recognition-based Movie , Books and Music Suggestion website that cheer up users and saves time while searching for a movie or song that matches their emotions.
1. It recognizes **facial expression** based on the **7 categories** i.e., angry, sad, fear, happy, disgust, surprise and neutral.
2. Based on the emotion it gives user **five choices**  either suggesting movies, books, songs or chat with friends or convert pics from jpg to gif.
3. **Live Camera Feed** to detect emotions.
4. If user wishes to watch movies/songs then a list of movies/songs/books matching their mood are suggested with movie/songs/books poster.
5. When user clicks on movie which he wishes to watch, they will be redirected to **IMDB website**.
6. For songs it redirects them to **Spotify website**.
7. For books it redirects them to **ZLibrary website**.
8. **Live Chat feature** with upto 20 users/friends in different chatrooms.
    1. Tells Live users with their names.
    2. Login/Logout/ change Password,Dp of your personal chat.
    3. Reply by tagging messages in chat room.
    4. Send Emoji to upto 20 users.
    5. Send Attachments- files, songs, text, docs etc.
    6. Receive Notification on receiving message.
    7. See previous days messages even after days.
    8. Auto Scroll Feature.
9. **Relive your images**- Upload your images in jpg and convert them to gif and download.
10. **Light and Dark Mode UI** available for ease in readability and functionality.
11. **AI based Chatbot** feature to chat and seek assistance from regarding features of website and usability.
12. **Genre Based Recommendation**- watch movies, listen songs and read books without any particular emotion detection.
13. Get directed to My **Linkedin and GitHub** to know more about me and my experiences.
14. **Scroll Up feature** for ease in moving up while you navigate through the website.
15. No signup required for quick access to website.

## Video- https://youtu.be/8-TAWg-tnkc
## Live Demo-https://meha-shukla-peacify-production.up.railway.app/

## Tech Stack
1. Python is the programming language used to create the emotion recognition model and deploy it on the web application using flask.
2. CV2, TensorFlow, NumPy, matplotlib,keras and other libraries are also utilized.
3. The model is build using the transfer learning approach for which MobileNet model is used.
4. The FER-2013 dataset, which comprises around 35000 photos, was utilized for model training and validation.
5. This model is deployed on a website created with HTML, CSS and Java Script using the flask framework.
6. Based on the seven emotions, a new dataset of movies, books and music was constructed. The data from movies, books and songs was utilized to create the various templates that correlate to various emotions.

## My Documentation- https://drive.google.com/file/d/1cq3u6vCCyw2s6HK59svDwnLjJ3joE2S-/view?usp=sharing

## Challenges
It was hard to find Movies and Songs datasets that reflected different emotions on the web. Finding templates of emotion-based movies and songs proved to be a major challenge. It was a challenging task to get the website to access 7 movie templates from the movies button and 7 song templates from the songs button based on the emotion recognized. Dynamic links were used as a means to access the templates for movies/songs corresponding to the output of the model.

# Submission By - Meha Shukla                      Microsoft Engage Mentee'22


## Mail - meha12shukla@gmail.com
## Linkedin- https://www.linkedin.com/in/mehashukla/
## Github - https://github.com/MehaShukla

## INSTALLATION-
1. Clone App - git clone https://github.com/MehaShukla/Peacify .
2. Open the Folder in a terminal - Visual Studio preferred , if nothing installed yet.
3. Install the dependencies -Run pip install -r requirements. txt (Python 2), or pip3 install -r requirements. txt (Python 3).
4. Open app.py and Execute the program.
5. You will get a URL somewhat of this type- http://127.0.0.1:5000/
6. Copy and Paste in a browser.
Voila!! Your Application Starts Running.
