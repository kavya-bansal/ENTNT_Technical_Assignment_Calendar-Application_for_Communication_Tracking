#  ENTNT Technical Assignment : Calendar Application for Communication Tracking
## 2ND UI DESIGN
<img width="1467" alt="image" src="https://github.com/user-attachments/assets/0597a6e1-3cdc-493f-a568-bc478e714dde" />
<img width="1470" alt="image" src="https://github.com/user-attachments/assets/659b3b75-56c1-47f5-9616-d9882fd10de4" />
<img width="1470" alt="image" src="https://github.com/user-attachments/assets/979e334b-fcd4-411c-9002-341e63585616" />
<img width="1468" alt="image" src="https://github.com/user-attachments/assets/35cdfa15-cddd-4a35-8589-58ed7d57a581" />
<img width="1470" alt="image" src="https://github.com/user-attachments/assets/699ddeef-646b-434a-96a3-e9b9547e3988" />
<img width="1468" alt="image" src="https://github.com/user-attachments/assets/cda198d8-ad60-4b86-a8b7-2f47bcfef6a2" />
<img width="1466" alt="image" src="https://github.com/user-attachments/assets/eaed211d-26a6-4919-82b0-5a5134b3da42" />
## FIRST UI DESIGN
 <img width="1468" alt="image" src="https://github.com/user-attachments/assets/029119a8-76b6-4c09-a66f-3213702a6161" />
 <img width="1469" alt="image" src="https://github.com/user-attachments/assets/5f7471a9-3811-4212-b9a0-587649f4eaac" />
<img width="1470" alt="image" src="https://github.com/user-attachments/assets/dc2b0845-02ef-4d26-8772-149562da69d7" />
 <img width="1464" alt="image" src="https://github.com/user-attachments/assets/bcc20f5f-b213-4abf-a0fe-747cb527b058" />
<img width="1464" alt="image" src="https://github.com/user-attachments/assets/4f67297e-9687-4760-9139-712617bb736a" />
<img width="1462" alt="image" src="https://github.com/user-attachments/assets/45ccff9d-23d9-4026-923a-11389b95eb92" />
<img width="1465" alt="image" src="https://github.com/user-attachments/assets/664be421-274e-4cba-8072-eba48206a4c2" />
## contact : telegram -> https://t.me/Coding_Gurl    or  grp : https://t.me/Coders_Community_By_Kb
Objective
## As a company, we aim to maintain strong professional relationships by keeping accurate records of our interactions with other organizations. The objective of this assignment is to develop a React-based Calendar Application that enables us to efficiently track communication with companies, ensuring follow-ups are timely and consistent. This tool will provide a centralized platform to log past interactions, plan future communications, and manage the frequency of engagement based on predefined schedules.
The application will include:
An Admin Module for setting up companies and communication parameters.
A User Module for visualizing, managing, and performing communication tasks.
A Reporting and Analytics Module for actionable insights (optional).
It is critical to emphasize usability, clarity, and efficient data handling.

## Detailed Requirements
Admin Module
This module allows administrators to configure the application and manage its foundational data.
Company Management
Admins should be able to add, edit, and delete companies. Each company entry should include:
Name: Name of the company.
Location: Physical or operational location.
LinkedIn Profile: A link to the company’s LinkedIn page.
Emails: One or more email addresses for communication.
Phone Numbers: Contact numbers for representatives.
Comments: Notes or additional information about the company.
Communication Periodicity: The default time interval for scheduled communications (e.g., every 2 weeks).
Communication Method Management
Admins should define the available communication methods in the system. Each method should include:
Name: E.g., "Visit" or "LinkedIn Post."
Description: E.g., "Visit to company premises."
Sequence: Determines the order of communication (e.g., LinkedIn Post → LinkedIn Message → Email → Phone Call → Other).
Mandatory Flag: Indicates whether a communication method is mandatory in the sequence.
By default, the system should include these methods in the following order:
LinkedIn Post
LinkedIn Message
Email
Phone Call
Other

##User Module
This module is the primary interface for end-users, enabling them to view, manage, and perform communication tasks.
Dashboard
The dashboard provides a grid-like view where each row represents a company. Columns include:
Company Name: The name of the company.
Last Five Communications: A summary of the five most recent communications, including the type (e.g., "LinkedIn Post") and date (e.g., "5th September").
Next Scheduled Communication: The type and date of the next planned communication.
Color-Coded Highlights:
Red Highlight: Indicates overdue communication.
Yellow Highlight: Indicates communication due today.
Users can disable or override highlights for specific companies or communications as needed.
Interactive Features
Hover Effect: When hovering over a completed communication, a tooltip should display the notes or comments recorded for that communication.
Communication Action
Users can select a specific company or multi-select multiple companies.
Click on a "Communication Performed" button to log a new communication. 
In the action modal: 
Select Type of Communication: E.g., LinkedIn Post, Email.
Input Date of Communication: Date when the communication occurred.
Add Notes: Additional comments about the communication.
Upon submission, this action will reset any existing highlights (red or yellow) for the selected company/companies.
Notifications
A dedicated section displays overdue and due communications:
Overdue Communications Grid: Lists companies with overdue actions.
Today’s Communications Grid: Lists companies with tasks due today.
The notification icon should display a badge with the count of overdue and due communications.
Calendar View
A calendar interface that allows users to:
View Past Communications: Dates and methods of previous interactions.
View and Manage Upcoming Communications: Scheduled dates and methods for future interactions.

Reporting and Analytics Module (Optional)
This module provides actionable insights and performance metrics related to company communications.
Features:
Communication Frequency Report:
A visual representation (e.g., bar chart or pie chart) showing the frequency of each communication method (e.g., LinkedIn Post, Email) used over a selected time frame.
Users can filter by company, date range, or communication method.
Engagement Effectiveness Dashboard:
Track and display which communication methods are most effective in terms of response or follow-up actions.
Include metrics like the percentage of successful responses to emails, phone calls, or LinkedIn messages.
Overdue Communication Trends:
A trendline or heatmap showing the number of overdue communications over time, categorized by company.
Downloadable Reports:
Allow users to export reports in PDF or CSV format for sharing or offline analysis.
Real-Time Activity Log:
A live feed displaying all communication activities performed, sortable by date, user, or company.
