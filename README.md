🧠 Project Title

JavaFX Task Scheduler & System Monitor

📖 Project Description

This project is a Task Scheduler and System Monitoring Application built using Java and JavaFX. It provides real-time insights into the system’s performance, including CPU usage, memory consumption, disk space, network activity, and running processes.

The application not only visualizes system resource usage through dynamic charts and graphs but also allows users to view, monitor, and manage running processes. With a simple and interactive interface, it combines the functionality of a task manager and a lightweight scheduler for managing background processes.

🎯 Key Features
🖥️ System Monitoring Dashboard

Displays real-time CPU usage, memory utilization, disk capacity, network speed, and process count.

Smooth line graph tracking CPU usage over time.

Pie chart visualization for memory usage (used vs. free).

⚙️ Process Management

Lists all currently running processes with their PID, command, CPU, and memory usage.

Allows users to terminate specific processes directly from the interface.

Provides options to refresh the process list and export data as CSV.

📊 Detailed Process Insights

For any selected process, users can view:

PID, command, uptime, and user.

Thread count and process state (Running, Sleeping, Waiting, etc.).

Real-time graphs for CPU%, memory usage (MB), and thread count over time.

🌗 Interface Features

Light and Dark modes for better usability.

Smooth Graph toggle for refined visualization.

Automatic updating at user-defined intervals.

Clear History option for resetting charts.

🧩 Tech Stack

Language: Java

GUI Framework: JavaFX

Build Tool: Maven

Platform Compatibility: Windows, macOS, Linux

Core Libraries:

javafx-controls, javafx-charts – for UI and visualization

java.lang.management – for process and system metrics

ProcessHandle API – for accessing and controlling processes

🧠 How It Works

The app continuously fetches system statistics using Java’s built-in Management APIs.

Data is rendered in real time using JavaFX charts and animations.

The Processes tab lists running programs, tracking their resource usage.

A selected process opens a detailed view with metrics over time (CPU, memory, thread count).

Users can terminate processes or export logs for analysis.

📸 Visual Overview (from screenshots)
<img width="1440" height="900" alt="Screenshot 2025-10-15 at 12 05 02 PM" src="https://github.com/user-attachments/assets/74d5303a-8c66-47b9-877c-abc61e4cc8ec" />
Overview Tab: Displays system-wide CPU and memory charts.
<img width="1440" height="900" alt="Screenshot 2025-10-15 at 12 05 11 PM" src="https://github.com/user-attachments/assets/5c2ec54c-1f86-4068-abcd-fe39698181e0" />

Processes Tab: Lists running processes with control options.
<img width="1440" height="900" alt="Screenshot 2025-10-15 at 12 05 22 PM" src="https://github.com/user-attachments/assets/2ce4032b-7c7e-415e-9d28-1adcef55f663" />


Process Info Tab: Shows details and runtime statistics of an individual process.
<img width="1440" height="900" alt="Screenshot 2025-10-15 at 12 06 56 PM" src="https://github.com/user-attachments/assets/97efb4fb-2dba-4843-b9b1-6aba66a30439" />
Stats Tab: Real-time CPU & memory graphs for that process.
<img width="1440" height="900" alt="Screenshot 2025-10-15 at 12 06 56 PM" src="https://github.com/user-attachments/assets/af9f87b0-9ea6-464c-b56f-00d5d277023d" />
Logs Tab: Displays live process state transitions (Running, Sleeping, etc.).
<img width="1440" height="900" alt="Screenshot 2025-10-15 at 12 07 54 PM" src="https://github.com/user-attachments/assets/d0d0b6da-946e-47e8-b03c-989b25e21228" />


🚀 Future Enhancements

Add custom task scheduling (run scripts or jobs at specific intervals).

Implement email or desktop notifications for resource thresholds.

Add process priority control and detailed I/O metrics.

Integrate database or CSV-based history storage for performance analysis.

Package as an executable .jar or .exe for easier deployment.

📦 Deployment Notes

The project is Maven-based and can be built with:

mvn clean package
java -jar target/task-scheduler.jar



