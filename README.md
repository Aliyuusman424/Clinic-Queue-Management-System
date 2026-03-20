The Clinic Queue Management System is a web-based application developed using Python and Flask. It is designed to help manage patient flow in a clinic by organizing patients in a First-In, First-Out (FIFO) queue system.

This application allows users to register patients, view the current waiting list, and serve patients in the order they arrive. Each patient is automatically assigned a timestamp when they are added to the system, making it easy to track patient arrival times.
The system is built using Object-Oriented Programming (OOP) principles. A Patient class is used to represent individual patients, while a ClinicQueue class is used to manage queue operations such as adding and serving patients.

A list data structure is used to simulate a queue, ensuring that the first patient added is the first to be served. Additionally, Python’s built-in datetime module is used to record timestamps.

The user interface is developed using Flask and HTML, allowing users to interact with the system through a web browser.

HOW TO RUN THE PROJECT

Install Flask: pip install flask

Run the application: python app.py

Open your browser and go to: http://127.0.0.1:5000/