
Customer Support Ticket Automation

Project Overview

This project automates the processing of customer support tickets using Python.
It reads ticket data from a CSV file, cleans the text, classifies issues, assigns priorities, calculates SLA deadlines, and exports a final processed report.


---

Features

Loads customer support ticket data from a CSV file

Automatically detects ticket text and created date columns

Cleans and normalizes ticket messages

Classifies tickets into issue types

Assigns priority levels (P0–P3)

Calculates SLA hours and due time

Generates a summary report

Exports the final processed data to a CSV file



---

Tools & Technologies Used

Python

Pandas

Google Colab / Jupyter Notebook

CSV Dataset



---

Input

File name: customer_support_tickets.csv

The dataset should contain:

Ticket description/message column

Ticket created date/time column




---

Output

File name: final_customer_support_output.csv

The output file includes:

Cleaned ticket message

Issue type

Priority level

SLA hours

Due time
