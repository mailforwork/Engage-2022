# Crime Detection Model
#### Submission for Microsoft Engage 2022
![Heading](https://github.com/mailforwork/Engage-2022/blob/main/images/header.png)

This project is built as a part of [Engage Mentorship Program 2022](https://acehacker.com/microsoft/engage2022) by Microsoft.

### Table of Contents
1. [About the Project](#about)
2. [Demo Video](#demo-video)
3. [Features](#features)
5. [Instructions To Setup](#instructions)
6. [System Architecture](#system-architechture)
7. [Future Scope](#future-scope)
8. [References](#references)
9. [Thanking Note](#thanking-note)


### About

This is a basic website where victim can upload images of culprit or person they are suspicious about. The TensorFlow models present in the code integrated with face-api.js will help in identifying if this person is suspicious or not. The database of criminals can be provided by government or private investigators. 

**Ideation**
![Basic Idea](https://github.com/mailforwork/Engage-2022/blob/main/images/Ideation.png)
**Thought Process**
![enter image description here](https://github.com/mailforwork/Engage-2022/blob/main/images/ideation_1.png)
### Idea

The idea behind the website is very simple.
User is directed to a homepage with clear UI. User is expected to click on Upload as per the instructions mentioned on the website. Then user should upload the image and press submit. Within few seconds, the model will detect face of the person.
As the model is kept simple, for now I have added only a limited dataset. However, the database can be extended using NoSQL databases etc.

### Demo Video
- [Demo Video](#)

### Features
 - Landing Page
![enter image description here](https://github.com/mailforwork/Engage-2022/blob/main/images/coded_file.png)

 - Choosing Image
![enter image description here](https://github.com/mailforwork/Engage-2022/blob/main/images/choose_image.png)

 - Face Detection by Model : Using Test Image ![enter image description
   here](https://github.com/mailforwork/Engage-2022/blob/main/images/test_image.png)

### Instructions
#### Testing Locally
Follow the below instructions to setup the repository for working further on it.

 - Clone the repo `git clone https://github.com/mailforwork/Engage-2022.git`

 - Install live server in VS Code and run file : [Homepage HTML File](https://github.com/mailforwork/Engage-2022/blob/main/homepage/index.html)

 - In case the models do not load while face recognition, run file
   [Crime Detection Model Homepage](https://github.com/mailforwork/Engage-2022/blob/main/Criminal-Detector-Model/index.html)
   from live server in VS Code.

#### Note
 - Sometimes Tensorflow models do not load properly due to less RAM. Make sure to close other tabs in browser.
 - This website is currently designed to run on local server and has only test images.
 - Due to safety purpose, it does not include any images of criminal
   etc.

### System Architechture
 - File Structure
![enter image description here](https://github.com/mailforwork/Engage-2022/blob/main/images/System%20Architecture.png)
 - Images Structure
![enter image description here](https://github.com/mailforwork/Engage-2022/blob/main/images/Images.png)

### Future Scope

 - This website will have collective database where public and some private authorities can post pictures of criminals or culprits.
 - **This website can also be used to find missing people by creating separate database for them**
 - The website can be converted into a progressive web application which can be downloaded by public for better availability

### References
- Face-API.js projects online
- Youtube Tutorials on face-api.js & Tensorflow Models

### Thanking Note

This is thanking note to my mentor Tanishk Gupta Sir for helping me with my doubts. Due to my internship and exams, I could not figure out things neatly but he helped me to stay motivated and work on something even though it's small. He guided us to put our best. Thank you for being there!


