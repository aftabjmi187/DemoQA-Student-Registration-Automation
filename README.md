# Selenium DemoQA Automation

This project automates the **DemoQA Student Registration Form** using **Java and Selenium WebDriver**.

## Application Under Test

DemoQA Automation Practice Form

https://demoqa.com/automation-practice-form

## Features Automated

The following functionalities are automated:

* Enter First Name
* Enter Last Name
* Enter Email
* Select Gender
* Enter Mobile Number
* Select Date of Birth
* Select Subject from the auto-suggestion dropdown
* Select Hobbies
* Upload a Picture
* Enter Current Address
* Select State
* Select City
* Submit the Student Registration Form

## Technologies Used

* Java
* Selenium WebDriver
* ChromeDriver
* Eclipse IDE

## Selenium Concepts Used

* WebDriver
* Locators
* ID Locator
* CSS Selector
* XPath
* Explicit Wait
* WebDriverWait
* ExpectedConditions
* Select Class
* Date Picker Handling
* Auto-Suggestion Dropdown
* Radio Buttons
* Checkboxes
* File Upload
* Keyboard Actions using Keys

## How to Run the Project

1. Clone this repository.

2. Open the project in Eclipse.

3. Make sure Java and Selenium dependencies are configured.

4. Make sure Google Chrome is installed.

5. Update the picture file path in the code:

```java
driver.findElement(By.id("uploadPicture"))
        .sendKeys("C:\\Users\\alama\\OneDrive\\Pictures\\Nature\\naturePic.png");
```

6. Run the `TC_WaitStmt.java` file.

7. The automation script will open Chrome, fill out the Student Registration Form, and submit it.

## Author

**Aftab Alam**

This project is part of my Selenium automation learning journey and was created to practice automating different types of web elements and user interactions.
