# Android-Studio-Project-3-Widget-Configure

![image](https://github.com/user-attachments/assets/f84737df-8642-4d00-9ae9-a9c3079a5419)


![image](https://github.com/user-attachments/assets/cd83816a-d930-4dcb-8185-c4d24aa563d0)


# A3DWidget - Android App Widget Configuration Example

## 📱 Project Overview

**A3DWidget** is a simple Android application that demonstrates how to create and configure an **App Widget** using a configuration activity. The app allows users to enter custom text through an `EditText` and then add the widget to the home screen using a button. The widget will then display the entered text.

---

## ✨ Features

- Android App Widget with a configuration screen
- `EditText` input and `Button` to submit data
- Saves custom widget text using `SharedPreferences`
- Demonstrates XML layout creation for widgets and configuration activities

---

## 🧱 Project Structure

```plaintext
app/
├── java/
│   └── com.example.a3rdwidget/
│       ├── MainActivity.java
│       ├── A3DWidget.java (AppWidgetProvider)
│       └── A3DWidgetConfigureActivity.java (Configuration screen logic)
├── res/
│   ├── layout/
│   │   ├── activity_main.xml
│   │   ├── amarjeet_widget.xml (Widget layout)
│   │   └── amarjeet_widget_configure.xml (Configure screen layout)
│   ├── values/
│   │   └── strings.xml
│   └── xml/
│       └── widget_info.xml (Widget metadata)
🛠️ Technologies Used
Java

Android SDK

AppWidgetProvider

SharedPreferences

XML-based UI Layouts

🚀 How to Run
Clone or download the project.

Open the project in Android Studio.

Build and run the project on an emulator or physical device.

Add the widget from the widget selector screen.

Enter your custom text in the configuration screen and press "Add widget".

The widget will be added to your home screen showing the text.

📂 Key Files Explained
amarjeet_widget_configure.xml: UI layout for configuring the widget (includes TextView, EditText, and Button)

A3DWidgetConfigureActivity.java: Stores input from user and applies it to the widget using AppWidgetManager

A3DWidget.java: Handles the widget display logic

widget_info.xml: Declares widget dimensions, preview layout, and configuration activity

🧑‍💻 Developer
  Amarjeet Kumar
  Email: ak7462514@gmail.com
  GitHub: https://github.com/AmarjeetJyotis

📄 License
This project is licensed under the MIT License. See the LICENSE file for details.

yaml
Copy
Edit

---

Let me know if you want me to include screenshots, instructions for publishing the widget, or anything specific from your source code.
