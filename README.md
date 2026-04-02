# Memento Design Pattern — Interactive Simulation

An interactive, visually rich HTML simulation that demonstrates the **Memento Design Pattern** in a clear, step-by-step way.

This project is designed for **university presentations** (Advanced Software Engineering) and helps explain how **state saving and restoration** works using the Memento pattern.

---

## 🎯 Objective

This simulation visually explains:

- **Originator** → The object whose state changes (Editor)
- **Memento** → A snapshot of the state
- **Caretaker** → Manages saved states (History stack)

It allows users to **interact with a simulated editor** and observe how states are saved and restored using the Memento pattern.

---

## 🧠 Concept Overview

The **Memento Design Pattern** is a behavioral design pattern that:

- Captures an object’s internal state
- Stores it externally without exposing its internal structure
- Restores the object to a previous state when needed

This simulation demonstrates:

> How undo functionality works internally using Mementos.

---

## ⚙️ Features

### 🔵 Interactive Editor (Originator)
- Simulates a text editor
- Supports:
  - `Type Hello`
  - `Type World`
- Displays real-time content updates

---

### 🟢 Memento System
- Creates snapshots of the editor state
- Each snapshot contains:
  - Content at that moment
  - Timestamp
  - Unique ID

---

### 🟠 History Stack (Caretaker)
- Stores Mementos in a **stack (LIFO)**
- Displays:
  - All saved states
  - Latest snapshot on top
- Handles:
  - Push (Save)
  - Pop (Undo)

---

### 🔁 Undo Functionality
- Restores the editor to the previous saved state
- Demonstrates:
  - Stack pop
  - State restoration

---

### 📊 Step-by-Step Log Panel
- Explains each action in real time
- Examples:
  - `"Typing 'Hello' → content updated"`
  - `"Saving state → Memento created"`
  - `"Undo → restoring previous state"`

---

### 🎬 Presentation Mode
- One-click automated demo
- Sequence: Hello → Save → World → Undo
- Hides controls
- Ideal for live presentations

---

### 🎨 UI/UX Design
- Modern **dark theme**
- Smooth animations (fade, slide, highlight)
- Color coding:
- 🔵 Editor (Originator)
- 🟢 Memento
- 🟠 History (Caretaker)

---

## 🧪 How to Use

### 1. Run the Simulation

Simply open the HTML file:

```bash
double-click index.html
