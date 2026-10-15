# Student Fee Reminder Automation

## Overview

Student Fee Reminder is a Robotic Process Automation (RPA) project developed using **UiPath Studio** to automate the process of identifying students with pending fee payments and preparing reminders.

The project aims to reduce manual effort, improve accuracy, and simplify student fee management.

## Features

- Processes student fee records.
- Identifies students with pending payments.
- Supports automated reminder workflows.
- Displays or records results based on the configured workflow.

## Tech Stack

- **Automation:** UiPath Studio
- **Language:** Visual Basic .NET (UiPath expressions)
- **Input Data:** Depends on the configured workflow, such as Excel files.

## Prerequisites

Before running the project, ensure you have:

- [UiPath Studio](https://www.uipath.com/product/studio) installed.
- The required project dependencies.
- Any input files required by the workflow.

## Getting Started

### 1. Clone the Repository

Open PowerShell or a terminal and run:

```bash
git clone https://github.com/farhanKhan4/Student_Fee_Reminder.git
```

### 2. Open the Project

1. Launch UiPath Studio.
2. Select **Open a Local Project**.
3. Navigate to the cloned repository.
4. Open the `project.json` file.

### 3. Configure the Project

- Provide the required input files.
- Update file paths if they differ from the original system.
- Configure any required integrations or credentials securely.
- Restore project dependencies if prompted.

### 4. Run the Automation

1. Open the main workflow, usually `Main.xaml`.
2. Verify the input data and configuration.
3. Click **Run** in UiPath Studio.
4. Review the execution output and generated reminders.

## Project Structure

```text
Student_Fee_Reminder/
├── Main.xaml
├── project.json
├── Data/                 # If required
└── README.md
```

*The actual folder structure may vary depending on your implementation.*

## Privacy and Security

Use synthetic student records for testing and demonstrations. Never upload confidential student information, passwords, API keys, or other sensitive data to a public repository.

## Author

**Farhan Khan**

GitHub: [farhanKhan4](https://github.com/farhanKhan4)
