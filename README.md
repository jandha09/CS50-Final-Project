# CS50 Final Project: Word Document Generator

## Overview
The CS50 Final Project is a Python application designed to streamline the process of generating Word documents from text pasted from a work webpage. The program simplifies the task by providing an easy-to-use graphical user interface (GUI) and four straightforward steps:

1. **Copy and Paste Text:** The user copies the necessary text from the Interaction Details on the work webpage.
2. **Enter Split Number:** The user enters the assigned split number.
3. **Select a Template:** The program offers three predefined templates.
4. **Generate and Open:** With a click of a button, the Word document is generated and opened.

## Libraries and Tools
To create this application, various libraries were employed. The primary library used was tkinter, which facilitated the creation of the GUI. Additionally, the program utilizes the docx library for editing Word documents and os for file operations. 

## Challenges and Solutions
The most challenging part of this project was editing the header values in the Word document template to match the information from the pasted text. The header values included Project Topic, Expert Name, Interaction ID, and XXXXXXX, each with different formatting requirements. Project Topic and Interaction ID needed to be in bold, while Expert Name and XXXXXXX were not. To overcome these challenges, extensive debugging and assistance from CS50's Duck Debugger, affectionately known as "Quacky," were invaluable.

## Development Environment
The development environment posed certain limitations. CS50.dev, where the project was initially hosted, doesn't support the graphical interface. As a result, Visual Studio was employed to build and test the application, ensuring it worked seamlessly.

The CS50 Final Project not only simplifies the process of generating Word documents but also serves as a testament to the problem-solving skills, resourcefulness, and dedication of the developer. With a user-friendly interface and a streamlined workflow, this application is a valuable tool for professionals looking to efficiently create Word documents based on web-based information.
