
**Develop a Simple Web Application with the following features:**

Create a simple dashboard(web page) with following content:



# Solution/Steps
For running this application User need to following steps.

**Step1:** Download the latest version of python, for this i am using python 3.8.

**Step2:** Open Command Prompt or Favourite IDE.

**Step3:** Create Virtual Environment for the python project.

"sudo pip3 install virtualevn"

**Step4:** Create new directory and open this directory.

"mkdir task"

"cd newtask"

**Step5:**  Now, Create a virtual environment in the project directory 

"virtualevn newenv"

**Step6:** To install all packages or dependency into this environment, virtual environment 
must be activated. 

"source newenv/bin/activate"

**Step7:** Now install all dependency for the application

* **For django** "pip3 install django"
* **For pandas** "pip3 install pandas"
* **For numpy**  "pip3 install numpy"
* **For PDF Generator** "pip3 install xhtml2pdf"

**Step8:** Now all set to add code in the Directory. So, clone the code from Github.

"git clone https://github.com/jain221/domin_task.git"

django-admin startproject password_generator

**Step9:** Then using cd in the project folder go to web_develop directory 

"cd /password_generator"

**Step10:** Then copy all contents of password_generator in main directory as it is.

**Step11:** Final step to execute application using following command

"python3 manage.py runserver 8000"

Then Server will start and provide url.

**eg.** "http://127.0.0.1:8000"
Copy this URL and past in this browser.
Then Task dashboard will be display with above task.







