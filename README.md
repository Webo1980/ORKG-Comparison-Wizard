# ORKG-Comparison-Wizard
This code implementation allows the users to create an ORG comparison automatically using the ChatGPT by simply uploading the papers that the user wants to compare.<br>
The code is based on the ORKG source code from <a href="https://gitlab.com/TIBHannover/orkg/orkg-frontend/">here</a>. You will need to follow the instructions in the page to run the ORKG instatnce. <br>
The repo is divided into parts <a href="https://github.com/Webo1980/ORKG-Comparison-Wizard/tree/main/frontend/">frontend</a>, and <a href="https://github.com/Webo1980/ORKG-Comparison-Wizard/tree/main/backend/">backend</a><br>
After you install the ORKG instance, you will need to add the following line of code in your frontend instance in the following path ```/src/routes.config.js```: <br>
```import ComparisonWizard from 'pages/Comparisons/ComparisonWizard/ComparisonWizard';```<br>
Do not forget to add some link in your front end that refers to the wizard<br>
You should install at least Python 3.12.2 to run the backend<br>
Configure your backend code, and run the backend by simply typing in your command line the following code:<br>
```py ChatGPT.py```
