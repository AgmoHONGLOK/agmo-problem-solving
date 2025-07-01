# 🧪 Auto-Logout for Inactivity (eBanking)

## 📖 Scenario

You’ve received a feature request to build a **secure login system** for a mobile eBanking app. Due to strict security requirements, the app must **automatically end the session if the user is inactive for more than 30 seconds**.

## 🔧 Task

Build a basic mobile application using **Flutter (or a familiar platform)** that includes the following:

### 1. Login Screen
- Fields: **Username** and **Password**
- **Password validation**: 
  - Minimum 6 characters
  - Must include both **letters and numbers**
- A **Login** button that navigates to the Home screen after successful validation  
  *(No backend login is needed; mock logic is acceptable)*

### 2. Home Screen
- Display dummy account information:
  - Account number
  - Account balance
- Display a **list of recent transactions**
  - Each transaction should include a title (e.g. "Payment to ABC"), amount, and date
  - **Simulate API response** by mocking the data

### 3. Session Timeout Logic
- The session remains active as long as the user interacts with the app (e.g. taps, typing, scrolling)
- If the user is **completely inactive for 30 seconds**, show a **warning dialog**
- If the dialog is dismissed or no response within 5 seconds, **automatically log out** the user and redirect them to the Login screen

### 4. Architecture & State Management
- Choose a suitable **mobile architecture** (e.g. MVVM, Clean Architecture)
- Implement a **state management approach** (e.g. Provider, Riverpod, Bloc)
- Briefly explain:
  - Why you chose the architecture and state management method
  - How it helps you manage the user session and application state effectively

---

## 🚀 How to Submit

1. Fork this repository
2. Implement your solution
3. Submit a pull request or share your repository link

---
