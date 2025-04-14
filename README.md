# Fitness-Tracker
This is a simple Java Swing-based GUI app designed to track fitness activities by calculating the estimated calories burned. It allows users to input the number of steps taken and the distance traveled (in kilometers), and then estimates the calories burned based on these values.

Features:
- **User-friendly interface**: Simple and intuitive graphical user interface (GUI) created with Java Swing.
- **Steps and Distance input**: Users can input the number of steps taken and the distance covered.
- **Calories Burned Calculation**: Estimates the calories burned based on the entered values.
- **Instant Feedback**: Displays the calculated calories burned in the result section.
![fitness](https://github.com/user-attachments/assets/fe9af001-b091-4787-af59-b686727e957a)
How the Calculation Works:
- The app uses a simplified formula to estimate the calories burned based on:
  - **Calories per Step**: 0.04 calories per step.
  - **Calories per Kilometer**: 0.1 calories per kilometer.
  - **Calories Burned** = (Steps * Calories per Step) + (Distance * Calories per Kilometer)
