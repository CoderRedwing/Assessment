# Assessment Task

## Overview

This repository is a simple Android application that helps you learn and implement various Android development concepts. Below is a guide on how to create and manage the necessary files to complete each task.

## Folder Structure and File Details

## Task List

### Task 1: Setting Up Android Studio

1. **Files to Create**:
   - **`AndroidManifest.xml`**: Automatically created when you start a new project.
   - **`MainActivity.java`**: Main activity file where you will define your main screen.

2. **Steps**:
   - Download and install Android Studio.
   - Create a new Android project. Android Studio will generate the `AndroidManifest.xml` and `MainActivity.java` files automatically.
   - Run the project on an emulator or physical device to ensure setup is correct.

### Task 2: Creating a Simple User Interface (UI)

1. **Files to Modify/Create**:
   - **`activity_main.xml`**: Define the layout for the main screen.
   - **`activity_second.xml`**: Define the layout for a second screen if needed.

2. **Steps**:
   - Edit `activity_main.xml` to add TextViews, EditTexts, and Buttons using XML.
   - Customize UI elements in `activity_main.xml` (e.g., color, size).
   - Use Android Studio’s Design Editor to preview and adjust the layout.

### Task 3: Handling Button Clicks (Event Handling)

1. **Files to Modify/Create**:
   - **`activity_main.xml`**: Add a Button element.
   - **`MainActivity.java`**: Implement the `onClickListener` for the Button.

2. **Steps**:
   - Add a Button to `activity_main.xml`.
   - Implement the `onClickListener` in `MainActivity.java` to handle button clicks and display a Toast message.

### Task 4: Displaying Toast Messages

1. **Files to Modify/Create**:
   - **`MainActivity.java`**: Use this file to create and display Toast messages.

2. **Steps**:
   - In `MainActivity.java`, create and display a Toast message with short text.
   - Customize the duration (short/long) and position of the Toast if needed.

### Task 5: Working with Activities

1. **Files to Modify/Create**:
   - **`AndroidManifest.xml`**: Declare additional activities.
   - **`SecondActivity.java`**: Create a new activity class.
   - **`activity_second.xml`**: Define layout for the second activity.

2. **Steps**:
   - Add a new activity in `AndroidManifest.xml`.
   - Create `SecondActivity.java` and define its behavior.
   - Design `activity_second.xml` for the new activity’s layout.
   - Implement navigation between `MainActivity` and `SecondActivity`.

### Task 6: Using RecyclerView to Display a List

1. **Files to Modify/Create**:
   - **`activity_recycler_view.xml`**: Define layout for RecyclerView.
   - **`item_view.xml`**: Define layout for individual items in the RecyclerView.
   - **`RecyclerViewActivity.java`**: Implement RecyclerView logic.
   - **`MyAdapter.java`**: Create an adapter for RecyclerView.

2. **Steps**:
   - Set up RecyclerView in `activity_recycler_view.xml`.
   - Create `item_view.xml` for item layout.
   - Implement `RecyclerViewActivity.java` and `MyAdapter.java` to bind data to RecyclerView.

### Task 7: Handling Permissions

1. **Files to Modify/Create**:
   - **`AndroidManifest.xml`**: Declare required permissions.
   - **`MainActivity.java`**: Handle runtime permission requests.

2. **Steps**:
   - Declare permissions in `AndroidManifest.xml`.
   - Implement runtime permission requests and handle results in `MainActivity.java`.



