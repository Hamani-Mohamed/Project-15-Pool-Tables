# 🎱 Pool Table Management Control (C# WinForms Custom UserControl)

## 📖 About the Project
A reusable **Windows Forms Pool Table UserControl** designed to track table usage, session duration, and billing in pool halls, gaming centers, and recreational clubs.

The control allows operators to start, pause, and end table sessions while automatically calculating the total play time and session cost based on a configurable hourly rate.

When a session ends, the control raises an event containing all session details, making it easy to integrate with billing systems, reports, or management applications.

This project was built as part of my journey through the **Abu-Hadhoud Platform**, focusing on custom controls, event-driven programming, timers, and component-based WinForms development.

## 📌 Features

### 1. 🎱 Pool Table Session Tracking
* Start and stop table sessions.
* Real-time session timer.
* Accurate tracking of total play duration.
* Automatic session reset after completion.

### 2. 💰 Cost Calculation
* Configurable hourly rate.
* Automatic billing based on session duration.
* Real-time calculation using total elapsed seconds.
* Suitable for pool halls and gaming centers.

### 3. 👤 Player & Table Management
* Assign a player name to each table.
* Custom table titles.
* Independent table configurations.
* Easy management of multiple tables.

### 4. 📢 Event-Driven Design
* Raises an event when a session is completed.
* Provides access to:
  * Player Name
  * Table Name
  * Time Consumed
  * Total Seconds
  * Hourly Rate
  * Total Cost

### 5. 🧩 Reusable WinForms Component
* Drag-and-drop support from the Toolbox.
* Easily embedded in any WinForms application.
* Encapsulates all timing and billing logic.

## 🏗️ Architecture & Technical Highlights
* **Custom UserControl Development** using WinForms.
* **Event-Based Communication** through delegates and events.
* **Timer-Driven Session Tracking** using `System.Windows.Forms.Timer`.
* **Property-Based Configuration** with designer support.
* **Automatic Cost Calculation** using elapsed play time.
* **Component Reusability** for managing multiple pool tables.

## 🛠️ Technologies Used
* **C#**
* **.NET Framework**
* **Windows Forms (WinForms)**
* **Custom User Controls**
* **Delegates & Events**
* **Timers**
* **Component Design**
