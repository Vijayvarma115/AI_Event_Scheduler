# AI Event Scheduler

This project leverages an **n8n automation workflow** to streamline the process of event scheduling and task management using AI. The workflow integrates with various tools such as Google Calendar, Google Sheets, and an AI agent powered by Google Gemini Chat Model. By combining these integrations, the workflow converts natural language input into actionable event and task data, making it easier to manage your schedule seamlessly.

## Overview

- **n8n Automation:** The entire process is automated through n8n, which orchestrates different services and nodes to receive chat messages, extract event details, and perform corresponding actions.
- **AI-Powered Interaction:** An AI agent processes natural language inputs to understand event details like start time, end time, and summary, ensuring that the scheduling is intuitive and user-friendly.
- **Google Services Integration:**
  - **Google Calendar:** Automatically creates and retrieves events.
  - **Google Sheets:** Retrieves and appends task/event details for additional record-keeping.
- **Memory Buffer:** Maintains conversation context using a window buffer memory to support natural interaction.

## Features

- **Chat Trigger:** The workflow is initiated via a chat message.
- **AI Agent Integration:** Uses the Google Gemini Chat Model to process user inputs.
- **Google Calendar:** 
  - Creates events with specified start time, end time, and summary.
  - Retrieves events within user-defined time intervals.
- **Google Sheets:**
  - Retrieves event/task details.
  - Appends new tasks with details like Task Name, Description, Due Date, and Priority.
- **Consistent Date Format:** All dates follow the MM/DD/YYYY structure for clarity and consistency.

## Prerequisites

- **n8n Workflow Automation:** Ensure you have an active n8n instance.
- **Google API Credentials:** Required for both Google Calendar and Google Sheets.
- **AI Agent Credentials:** Set up for the Google Gemini Chat Model integration.

## Setup Instructions

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/Vijayvarma/AI-Event-Scheduler.git
   cd AI-Event-Scheduler
## Here are the Snap-Shots

![image](https://github.com/user-attachments/assets/7c689e56-910d-4995-ab21-5c6bb6d208f5)

## Here is the WorkFlow




https://github.com/user-attachments/assets/b47ff1b9-98a0-487d-a7ad-32de8e60b7ec

