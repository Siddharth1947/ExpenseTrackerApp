# Expense Tracker App

A simple and beginner-friendly Android application for tracking daily expenses. This app allows users to record, manage, and view their expenses in a clean and organized way. It uses a local SQLite database for storing data and displays the total expenses on the main screen.

## Features

- Add daily expenses with amount, category, and date  
- View expenses in a scrollable list using RecyclerView  
- Display total expense amount at the top of the screen  
- Delete expenses easily  
- Store all data locally using SQLite database  
- Clean and intuitive user interface

## Built With

- Java (can also be adapted for Kotlin)
- Android Studio
- RecyclerView
- SQLite Database (or Room)
- Material Design Components

## Project Structure

app/
├── java/
│ └── com.example.expensetracker/
│ ├── MainActivity.java
│ ├── AddExpenseActivity.java
│ ├── ExpenseAdapter.java
│ ├── DatabaseHelper.java
│ └── Expense.java
├── res/
│ ├── layout/
│ ├── values/
├── AndroidManifest.xml
└── build.gradle
