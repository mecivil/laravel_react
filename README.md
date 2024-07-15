**Project Manager App**

This is a Laravel 11 React Inertia app using Laravel Breeze as the starter  kit.
At the backend php and MySQL databases are used. The frontend is handled by react. The inertia acts as a glue between the frontend and the backend.

Steps to be followed to run the app locally for Windows environment

1 Install xampp from https://www.apachefriends.org/ <br />
2 Install composer from https://getcomposer.org/download/ <br />
3 Install node.js from https://nodejs.org/en <br />
  Install everything above to their default directory as directed without changing anything. Changing may cause problems later. <br />
4 Download the zip file from <>Code button and click download zip <br />
5 Extract the zip folder to the Downloads directory by clicking Extract All. You can choose any other path but in that case choose the path in the next steps accordingly. <br />
6 Write Environment Variables in Windows search box and open Edit the system environment variables <br />
7 Click on Environment Variables <br />
8 Under the System variables section double click on variable path <br />
9 Edit environment variable window will open <br />
10 Check if the following paths are added. If not then add these paths click on ok and again ok <br />
   C:\xampp\php <br />
   C:\ProgramData\ComposerSetup\bin <br />
   C:\Program Files\nodejs\ <br />

  If you have installed xampp and composer to different location then put their respective paths. <br />
  
  ![environsetup](https://github.com/user-attachments/assets/144857be-87b1-4178-87eb-270b0da5a63b)
 <br />

11 Open two powershell terminals. Type cd C:\Users\username\Downloads\laravel_react-master\laravel_react-master in both of them. <br />
   In place of username type your own computer's username. <br />
12 Type the following commands one after another in any one of the powershell terminals. Wait for each operation to complete. <br />
   composer diagnose </br>
   Scroll down to the bottom. If it says "zip: extension not loaded"  open xampp control panel.Click on config button beside Apache  and then click on PHP(php.ini)<br />
   Then Ctrl+F and search for zip . Click on the down arrow . Remove the semicolon in front of extension=zip .Click on File and Save. Now proceed with below commands. <br />
   composer install <br />
   npm install <br />
13 After the execution of above commands type in one of the terminals:<br />

   php artisan serve <br />

   <br />

   In the other terminal write :<br />

   npm run dev <br />
14 Provide your email (only gmail) addresses at the specified locations in the .env file
15 Now go to localhost:8000 <br />
**Voila! The app is running.** <br />

![login](https://github.com/user-attachments/assets/89d41804-6845-4325-b57b-c6f374fe49a2)
 <br />

 ![dashboard](https://github.com/user-attachments/assets/1f55bdfc-f212-43e5-b279-8dc50f0267c0)
<br />

![projects](https://github.com/user-attachments/assets/569a4c26-78d1-4d27-8ecd-afe58a81304e)
 <br />

 ![Tasks](https://github.com/user-attachments/assets/c943ac64-3128-4a67-90b8-9aa535a76f95)
<br />

 ![Users](https://github.com/user-attachments/assets/b46c945c-55eb-454e-b693-aa6ae3b138b9)
<br />





   

