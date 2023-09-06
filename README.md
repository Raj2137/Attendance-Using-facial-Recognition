<br>
<div align="center">
    <a href="https://github.com/itsmeSamrat" target="_blank">
        <img src="https://github.com/itsmeSamrat/Face-Recognition-System-for-Student-Attendance/blob/main/misc/app.png?raw=true" 
        alt="Logo" width="500" height="350">
    </a>
</div>

<div align="center">
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&duration=1500&pause=200&center=true&vCenter=true&multiline=true&width=435&height=100&lines=Face+Recognition+System+;for+Student+Attendance">
</div>

<h2 align="center"> Effortlessly track student attendance with reliable Face Recognition System. </h2>

## Description

Hello, everyone. This is my first attempt at creating a Flask web application with Firebase as Database and OpenCV and Face Recognition modules for developing a face recognition model. I have tried to keep all the resources in place and organized correctly, as per my knowledge. It was challenging to figure out every component and make them work together but looking into Stackoverflow, googling, and YouTubing, ChatGPT was able to piece them all together. I have provided links to some articles and videos, which helped me get this project done in the acknowledgement section.

Also, one limitation of this application is the routes in flask application are not secured meaning we can access the restricted data by simply pasting the routes(links). I tried different approaches like using decorators like @login_required and creating own middleware for checking the tokens which are send by the firebase authentication app also using JWT tokens. So, simply saying, being my first flask project, there was not good planning for the project. In the upcoming, project will keep that in mind. And if anybody can help me out with this problem, please feel free to contact me in the email address below, would really appreciate it. Thank you.


## Getting Started

- Start by cloning the repository into your local machine. Use the following command in your terminal:

```bash
    git clone https://github.com/itsmeSamrat/Face-Recognition-System-for-Student-Attendance.git
```

- Next, install all the necessary modules and dependencies listed in the requirement.txt file. Keep in mind that some modules might be missing, which could result in an error.
- Proceed to set up your Firebase database. Download the required credentials from Firebase and save them as **serviceAccountKey.json** .
- Locate the **initial_database.py** file in the misc directory. Open it and find the designated section to paste your database URL. If your setup and credentials are correct, the script will add the data to the database.
- Once you've created the database, run the **initial_encoding.py** Python file. Ensure that you've placed the image file in the **static/Files/Image** directory and named it with the corresponding user ID from the database. This allows us to associate user images with their unique identification numbers. Additionally, this encoding step will generate a pickle file used for the face recognition model.
- With the previous steps completed, execute the **webapp.py** script. If all the credentials and dependencies are correctly set up, the web application should start running. You can refer to the **[demo video](https://youtu.be/Zc-t0mjkiWk)** for a visual representation.
- Lastly, show your support by giving the repository a star! 🙂😁

Thank you. ✌✌


