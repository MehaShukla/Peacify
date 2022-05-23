# Peacify

## Inspiration
1. In this world so full of stress and chaos, everyone aims of getting peace.
2. **Peacify** gives you the same, by detecting your emotions and gives recommendations to entertain you, and in turn peacify you.

## Features- With DEMO
**Peacify** is a facial expression recognition-based Movie , Books and Music Suggestion website that cheer up users and saves time while searching for a movie or song that matches their emotions.
1. It recognizes **facial expression** based on the **7 categories** i.e., angry, sad, fear, happy, disgust, surprise and neutral.
2. Based on the emotion it gives user **five choices**  either suggesting movies, books, songs or chat with friends or convert pics from jpg to gif.
3. **Live Camera Feed** to detect emotions.
4. If user wishes to watch movies/songs then a list of movies/songs/books matching their mood are suggested with movie/songs/books poster.
5. When user clicks on movie which he wishes to watch, they will be redirected to **IMDB website**.
6. For songs it redirects them to **Spotify website**.
7. For books it redirects them to **ZLibrary website**.
8. **Live Chat feature** with upto 20 users/friens in different chatrooms.
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
## Screenshots

 ### Light/ Dark UI-

![](Read%20Me%5C1.png)

![](Read%20Me%5C2.png)

![](Read%20Me%5C3.png)
 ### Live Camera emotion Detection- Happy, Sad, Angry, Disgust, Surprise,Fear, Neutral-

![](Read%20Me%5CEmotions%20Detected.png)

 ### Recommend IMDB Movies, Spotify Songs, ZLibrary Books based on Emotions-

![](Read%20Me%5COptions.png)

![](Read%20Me%5COptions2.png)

 ### Chat with upto 20 users, Notifaction sound, Login/Sign Up, Send attachment, emoji, react, Claim Profile, See no of users online, have seperate chat rooms-

![](Read%20Me%5CChat%20Features.png)

 ### Give your face movement- Convert jpg images to moving gif-

![](Read%20Me%5CRelive%20your%20face.png)

 ### Get Genre Based recommendation of Songs, Movies, Books- Comedy, Action, Romantic-

![](Read%20Me%5CGenre%20based.png)

 ### AI Powered ChatBot to assist you how to access website features-

![](Read%20Me%5CChatbot.png)

 ### Know More About Me- Directs to my Linkedin and Github-

 ![](Read%20Me%5CConnect%20With%20Me.png)


## Tech Stack
1. Python is the programming language used to create the emotion recognition model and deploy it on the web application using flask.
2. CV2, TensorFlow, NumPy, matplotlib,keras and other libraries are also utilized.
3. The model is build using the transfer learning approach for which MobileNet model is used.
4. The FER-2013 dataset, which comprises around 35000 photos, was utilized for model training and validation.
5. This model is deployed on a website created with HTML, CSS and Java Script using the flask framework.
6. Based on the seven emotions, a new dataset of movies, books and music was constructed. The data from movies, books and songs was utilized to create the various templates that correlate to various emotions.
## Challenges
It was hard to find Movies and Songs datasets that reflected different emotions on the web. Finding templates of emotion-based movies and songs proved to be a major challenge. It was a challenging task to get the website to access 7 movie templates from the movies button and 7 song templates from the songs button based on the emotion recognized. Dynamic links were used as a means to access the templates for movies/songs corresponding to the output of the model.
## Video
## Live Demo
## Meha Shukla
## Mail - meha12shukla@gmail.com
## Linkedin- https://www.linkedin.com/in/mehashukla/
## Github - https://github.com/MehaShukla