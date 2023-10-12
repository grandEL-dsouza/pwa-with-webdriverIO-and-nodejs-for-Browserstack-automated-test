# pwa-with-webdriverIO-and-nodejs-for-Browserstack-automated-test

Download the file  

Unzip the file and follow the steps mentioned in the README.md file  

Please note the following:
1. You will run the tests on our App-Automate platform and uploading a sample app is mandatory to run tests on our App-Automate platform. You can upload any dummy app for this use case.

2. You can follow the Getting Started pages in our documentation to learn more about how to get onboarded to App Automate.

3. The attached project contains the first_test.js file which Closes the dummy app and Opens Chrome

4. The test then proceeds to go to a sample e-commerce site myntra.com and installs the PWA and
Launches the PWA from the home screen as per your requirement. 

5. You can refer to it to create your own script to test your PWA. You would need to add their user key and access key in the first_conf.js file. And also add the app ID in place of bs://<hashed app-id>. For more details about uploading the App on BrowserStack and getting the App-URL please refer to this documentation:
https://www.browserstack.com/docs/app-automate/api-reference/appium/apps#upload-an-app
