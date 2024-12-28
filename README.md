Steps to Access the Admin Account on OWASP Juice Shop Using Burp Suite:
Open OWASP Juice Shop:

1__Right-click anywhere on the webpage and select Inspect (or press F12) to open the Developer Tools.
Navigate to the Network tab.
Locate the Main JavaScript File:

2__Reload the page if necessary to populate the Network tab.
Filter by type "JS" to easily find the main JavaScript file (e.g., main.js).
View the JavaScript File:

3__Click on the main JavaScript file to open its content.
Switch to the Response or Source tab to view the file's code.
Search for the Admin Path:

4__Use Ctrl+F to search the file for keywords like admin or path.
Locate the specific admin path (e.g., /administration).
![WhatsApp Image 2024-12-28 at 6 15 22 PM (1)](https://github.com/user-attachments/assets/701d63ff-6d20-44e9-89ee-804cb5362902)
![WhatsApp Image 2024-12-28 at 6 15 22 PM](https://github.com/user-attachments/assets/dad09abc-504d-4f7f-8738-9e4ced6f862f)


this sql injection skip us from enter password and make us login to bender account successful
![WhatsApp Image 2024-12-28 at 5 57 35 PM](https://github.com/user-attachments/assets/365365b8-3f16-4f7a-a40b-68536abb2bdb)

the we pop up an alert to user using java script injection "<iframe src ="javascript:alert('xss')">"
![WhatsApp Image 2024-12-28 at 5 57 33 PM](https://github.com/user-attachments/assets/5ee96776-e08b-489c-9331-16bf3bef5af3)

final this is a vidio link explain all steps: https://drive.google.com/file/d/14f-_OVt_Cre0KycgOPAi9dqHdoS30YxT/view?usp=sharing

