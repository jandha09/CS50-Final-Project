# CS50 Final Project: Word Document Generator

## Overview
The CS50 Final Project is a Python application designed to streamline the process of generating Word documents from text pasted from a work webpage. The program simplifies the task by providing an easy-to-use graphical user interface (GUI) and four straightforward steps:

1. **Copy and Paste Text:** The user copies and pastes the necessary text from the Interaction Details on the work webpage.
2. **Enter Split Number:** The user then enters the assigned split number.
3. **Select a Template:** The user chooses one from three provided templates. I made it so that even if the company decides to change the formatting of the templates, the program woudl still be useful.
4. **Generate and Open:** Generates and Opens the Word document with the CORRECT header values.

## Libraries and Tools
To create this application, I had to install different libraries. The primary library I used was tkinter for the GUI. Additionally, the program utilizes the docx library for editing Word documents and os for file operations (mainly opening the file after generation). 

## Challenges and Solutions
The most challenging part of this project was editing the header values in the Word document template to match the information from the pasted text. The header values included Project Topic, Expert Name, Interaction ID, and XXXXXXX, each with different formatting requirements. Project Topic and Interaction ID needed to be in bold, while Expert Name and XXXXXXX were not. It took me a while to find a solution to this since cs50.dev did not support GUIs, but I had had a lot of help with "Quacky", the trusted Duck Debugger!

## Development Environment
As I stated earlier, the development environment posed certain limitations. cs50.dev, where the project was initially hosted, doesn't support graphical interface outputs. As a result, I had to use Visual Studio to build and test the application, ensuring it worked seamlessly.

I had also installed it using pyinstaller so I could share it with my colleagues. I hope that it would be useful to them to streamline their transcription process but also to share to them the wonders I learned in learning how to code with Python! PS. I did this project for FREE for me. I shared with with my colleagues but I have no intention of getting any monetary value from this. I MAY or MAY NOT be updating or improving this in the future. 
