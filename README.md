# Static Management for Lost Ark - Google Sheets Project

---

This sheet is a comprehensive yet user-friendly tool designed to streamline raid planning and character progress tracking for Lost Ark players.
    
A Google Sheets-based static management tool designed for **Lost Ark** players. This sheet helps track individual progress and plans for raids, supporting **8 core members** and **3 extra members** in a static team.

[Click here to access the Google Sheets template.](https://docs.google.com/spreadsheets/d/1BKOExbG7ytlijMTRmJ-zoOMUEIkjTxZYoYP4zV_et3c/copy)

---

The sheet may appear complex at first glance, but it’s designed for simplicity and ease of use. All tracking tools are consolidated into one page.
<details> 
   <summary><h1>  Characters Sheet </h1></summary> 

## Overview
The sheet is divided into **two main sections**:
1. **Simple Tracker (Quick Analysis)**
2. **Detailed Tracker (Individual Progress)**

![Screenshot 2024-09-29 115554](https://github.com/user-attachments/assets/fb92c41a-35e1-46f6-ba35-2c2497f02d09)

---

## How to Use the Sheet

1. **Input Your Information**: Add your character’s details (name, username, gear score, class).
2. **Raid Tracking**: Input your raid data either manually or automatically.

### Sample Input Screenshot
![Sample Input](https://github.com/user-attachments/assets/ea9b1393-3ff5-4504-8f30-0253cb8f0387)

---

## 1. Simple Tracker (Quick Analysis)
This section provides a **quick overview** of each member's progress through a clean, easy-to-read interface.

- **Member Information**: Displays basic member data with a summary graph.
- **Raid Tracking**: Monitors how many raids each member has completed, what remains, rewards earned, and progress on gold sales.
    - If you sell gold, you can input how much 100k gold is worth in EGP and quickly calculate the total value.
- **Top 10 Raids**: A list of the 10 most rewarding raids for fast reference.

### Sample Screenshot
![Quick Analysis](https://github.com/user-attachments/assets/9bf59c85-194a-4b27-b0f0-db4d6564daf3)

---

## 2. Detailed Tracker (Individual Progress)
A more granular tracker for daily, weekly, and raid-specific tasks. This section supports detailed tracking across various gameplay aspects.

- **Daily Tracker**: Tracks daily tasks like Una Tasks, Chaos Dungeons, Chaos Gates, and farming activities.  
    - **Automatic Reset**: The tracker resets daily at 1 PM (Egypt Timezone). You can adjust the timezone by referring to the included PDF instructions.
  
- **Weekly Mission Tracker**: Monitors weekly tasks such as Abyssal Dungeons and Guardian Raids.
    - **Automatic Weekly Reset**: Resets every Wednesday at 1 PM (Egypt Timezone). Instructions to change the timezone are included in the PDF.

- **Raid Tracker**: Allows manual input for completed raids. You can set custom gates for each raid using checkboxes.

- **Roster Analysis**: Provides insights into your character roster:
    - Tracks the number of raids completed.
    - Calculates gold collected and savings based on roster data.
    - Supports up to 4 rosters (24 characters, equivalent to 72 raids).
  
    > **Note**: If you are completing all 72 raids, you may want to reflect on your gaming habits and consider work-life balance!

### Sample Screenshot
![Roster Analysis](https://github.com/user-attachments/assets/46e164a1-08b8-4721-b798-8245096789d0)
---
</details>

<details> 
   <summary><h1>  Planner Sheet </h1></summary>

The **Planner Sheet** is a dynamic scheduling tool designed to optimize raid planning and team performance by providing a streamlined, automated process. It dynamically adjusts based on character eligibility for specific raids, ensuring efficient and accurate raid assignments.

### Key Features:
- **Dynamic Raid Selection**: 
    - The sheet automatically updates available raid options based on the selected day and time.
    - The list of eligible characters is dynamically adjusted according to the gear score requirements for each raid.
  
- **Time Management**:
    - **Average Completion Time**: Each raid comes with a preset average time to complete (modifiable in the "Raid Data" sheet). For example, challenging raids like Echidna NM may have a default time of 2 hours.
    - **Real-Time Performance Tracking**: By using a checkbox feature, the system logs the current time, allowing you to compare the actual raid duration to the average and assess the team’s performance.

- **Performance Metrics**: 
    - The system records start and end times for each raid, providing insights into how efficiently the static group is progressing over time.

![Screenshot 2024-09-17 111440](https://github.com/user-attachments/assets/3709bf8c-a243-4d07-beda-9c33eb1b037b)

### Additional Features:
- **Character Filtering**: Knowing that not all characters meet the gear score requirements for certain raids, the planner automatically filters out ineligible characters, saving time by only displaying valid options.
  
- **Manual Input**: While dynamic, the system also allows users to manually adjust certain elements, such as raid times or roster information.

- **Time Comparison**: After checking the checkbox, it automatically records your current time, allowing you to measure actual raid duration against the estimated time, giving valuable insights into your static group's performance.

![Screenshot 2024-09-17 111245](https://github.com/user-attachments/assets/5c55cb0b-f0c0-411a-84ea-b391688db71f)

</details>

<details> 
   <summary><h1>  Schedule Sheet </h1></summary>

This is where you inform the team about your availability to play. Lost Ark usually undergoes maintenance every Wednesday for 2-6 hours. You are free to adjust the cells by inserting "x" for not available, "y" for available, and "M" for maintenance during those times.

![Screenshot 2024-09-17 112010](https://github.com/user-attachments/assets/f1733094-10e4-4553-bcf4-d1a6357755e7)

</details>

<details> 
   <summary><h1>  Other </h1></summary>

## Raw Data
This table contains all info collected on each member, showing clear information on:
- Roster number
- Number of characters
- Raid names and values
- Income per character
- Income per roster

![image](https://github.com/user-attachments/assets/a9861f70-bac5-4255-a4df-10aee7b9858a)

## Raid Data
This sheet contains information on:
- Raid names
- Requirements to enter
- Type
- Average time to finish

![image](https://github.com/user-attachments/assets/0b74eb8d-b270-4965-82e3-b3441ec187a7)

## Raid Gold
This sheet details each raid by type, with further information on income per gate.

![image](https://github.com/user-attachments/assets/a0e3b433-3b61-4a34-b2be-bc6cb6d106d2)

</details>

<details> 
   <summary><h1>  How the Team Improved </h1></summary>

### Performance Improvements Achieved:
The implementation of this dynamic management system in Google Sheets led to significant improvements in team efficiency and performance:

- **40% Increase in Efficiency**: 
    - Within three months of utilizing the sheet, the team's overall raid completion efficiency improved by 40%. This improvement was achieved through better raid scheduling, real-time data tracking, and an optimized system that reduced bottlenecks.
  
- **50% Reduction in Manual Data Entry**: 
    - The automation of performance metrics using Google Sheets formulas reduced the need for manual updates by 50%, allowing team members to focus more on gameplay rather than administrative tasks.

- **Real-Time Dashboards**: 
    - The addition of real-time visual dashboards helped monitor team progress, enhance accountability, and motivate team members to maintain consistent productivity.

### Outcome Calculation:
The performance improvements were calculated based on several key metrics:
1. **Raid Completion Time**: 
    - Comparison of the average raid completion times before and after implementing the system. Teams were able to finish raids more quickly and efficiently, optimizing their playtime.
  
2. **Number of Successful Raids**: 
    - The number of successful raids within the expected timeframe increased, thanks to more efficient planning and execution.
  
3. **Manual Input Reduction**: 
    - By tracking the time saved from automating raid data input and reducing errors, the overall process became more efficient.

These results demonstrate how an effective management tool can significantly enhance both individual and team performance in a highly coordinated environment like Lost Ark.

</details>
