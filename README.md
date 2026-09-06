# Practical-4

## Aim

To develop an Android Alarm application using `Service` and `BroadcastReceiver`.

## Project Overview

This project demonstrates the implementation of an alarm system in Android using `AlarmManager`. The application allows the user to select a specific time for the alarm. When the selected time is reached, a `BroadcastReceiver` receives the alarm event and starts a background `Service` to play the alarm sound.

The application also provides a simple and modern Material Design interface for setting and cancelling alarms.

## Main Components

- **MainActivity:**  
  Provides the main user interface. It allows the user to select an alarm time using `TimePickerDialog` and schedules the alarm.

- **AlarmManager:**  
  Used to schedule the alarm at the selected time. It can trigger the alarm even when the application is not currently open.

- **AlarmBroadcastReceiver:**  
  Receives the broadcast when the scheduled alarm time is reached and starts the `AlarmService`.

- **AlarmService:**  
  Runs in the background and controls the alarm ringtone using `MediaPlayer`. The ringtone continues until the alarm is stopped or cancelled.

- **Material Design UI:**  
  The application uses Material Design components such as `MaterialCardView`, `MaterialButton`, and `TextClock` to provide a clean and responsive interface.

## Key Features

- Displays the current date and time.
- Allows the user to select an alarm time.
- Provides a time picker using `TimePickerDialog`.
- Schedules alarms using `AlarmManager`.
- Handles alarm events using `BroadcastReceiver`.
- Plays an alarm ringtone using `Service` and `MediaPlayer`.
- Provides a button to cancel the alarm.
- Uses a modern Material Design user interface.

## Screenshots

<table>
<tr>
<td align="center">
<img src="./screenshots/ss1.png" width="250" alt="Main Alarm Screen">
<br><br>
<b>1. Main Alarm Screen</b>
</td>

<td align="center">
<img src="./screenshots/ss2.png" width="250" alt="Time Picker">
<br><br>
<b>2. Time Picker</b>
</td>

<td align="center">
<img src="./screenshots/ss3.png" width="250" alt="Alarm Created">
<br><br>
<b>3. Alarm Created</b>
</td>
</tr>
</table>

## Application Working

1. The application displays the current date and time on the main screen.
2. The user clicks on the **Create Alarm** button.
3. A **Time Picker** is displayed.
4. The user selects the desired alarm time.
5. The selected time is calculated and scheduled using `AlarmManager`.
6. When the scheduled time is reached, `AlarmBroadcastReceiver` receives the alarm event.
7. The receiver starts the `AlarmService`.
8. The `AlarmService` starts playing the alarm ringtone using `MediaPlayer`.
9. The alarm can be cancelled using the **Cancel Alarm** button.

## Technologies Used

- **Kotlin**
- **Android Studio**
- **Android SDK**
- **AlarmManager**
- **BroadcastReceiver**
- **Service**
- **MediaPlayer**
- **TimePickerDialog**
- **Material Design Components**

## Project Structure

```text
Practical-4/
│
├── app/
│
├── screenshots/
│   ├── ss1.png
│   ├── ss2.png
│   └── ss3.png
│
├── README.md
│
└── ...# Practical-4

## Aim

To develop an Android Alarm application using `Service` and `BroadcastReceiver`.

## Project Overview

This project demonstrates the implementation of an alarm system in Android using `AlarmManager`. The application allows the user to select a specific time for the alarm. When the selected time is reached, a `BroadcastReceiver` receives the alarm event and starts a background `Service` to play the alarm sound.

The application also provides a simple and modern Material Design interface for setting and cancelling alarms.

## Main Components

- **MainActivity:**  
  Provides the main user interface. It allows the user to select an alarm time using `TimePickerDialog` and schedules the alarm.

- **AlarmManager:**  
  Used to schedule the alarm at the selected time. It can trigger the alarm even when the application is not currently open.

- **AlarmBroadcastReceiver:**  
  Receives the broadcast when the scheduled alarm time is reached and starts the `AlarmService`.

- **AlarmService:**  
  Runs in the background and controls the alarm ringtone using `MediaPlayer`. The ringtone continues until the alarm is stopped or cancelled.

- **Material Design UI:**  
  The application uses Material Design components such as `MaterialCardView`, `MaterialButton`, and `TextClock` to provide a clean and responsive interface.

## Key Features

- Displays the current date and time.
- Allows the user to select an alarm time.
- Provides a time picker using `TimePickerDialog`.
- Schedules alarms using `AlarmManager`.
- Handles alarm events using `BroadcastReceiver`.
- Plays an alarm ringtone using `Service` and `MediaPlayer`.
- Provides a button to cancel the alarm.
- Uses a modern Material Design user interface.

## Screenshots

<table>
<tr>
<td align="center">
<img src="./screenshots/ss1.png" width="250" alt="Main Alarm Screen">
<br><br>
<b>1. Main Alarm Screen</b>
</td>

<td align="center">
<img src="./screenshots/ss2.png" width="250" alt="Time Picker">
<br><br>
<b>2. Time Picker</b>
</td>

<td align="center">
<img src="./screenshots/ss3.png" width="250" alt="Alarm Created">
<br><br>
<b>3. Alarm Created</b>
</td>
</tr>
</table>

## Application Working

1. The application displays the current date and time on the main screen.
2. The user clicks on the **Create Alarm** button.
3. A **Time Picker** is displayed.
4. The user selects the desired alarm time.
5. The selected time is calculated and scheduled using `AlarmManager`.
6. When the scheduled time is reached, `AlarmBroadcastReceiver` receives the alarm event.
7. The receiver starts the `AlarmService`.
8. The `AlarmService` starts playing the alarm ringtone using `MediaPlayer`.
9. The alarm can be cancelled using the **Cancel Alarm** button.

## Technologies Used

- **Kotlin**
- **Android Studio**
- **Android SDK**
- **AlarmManager**
- **BroadcastReceiver**
- **Service**
- **MediaPlayer**
- **TimePickerDialog**
- **Material Design Components**

## Project Structure

```text
Practical-4/
│
├── app/
│
├── screenshots/
│   ├── ss1.png
│   ├── ss2.png
│   └── ss3.png
│
├── README.md
│
└── ...
