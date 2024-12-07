# Procrasti-mate: Task Reminder Application

Procrasti-mate is a task reminder application built using Python's `tkinter` for the GUI, `mysql.connector` for database interaction, and `tkcalendar` for date selection. The app allows users to create, view, and manage their task reminders. It integrates voice notifications and desktop alerts when the reminders are due.

## Features

- **Create New Reminders**: Users can create reminders with a date, time, and description. The reminders are stored in a MySQL database.
- **View Today's Reminders**: Display reminders for the current day.
- **View Scheduled Reminders**: View reminders that are scheduled for a future date.
- **View All Reminders**: View all reminders sorted by date and time.
- **Voice Notifications**: When a reminder is due, the system gives a voice notification (works for macOS).
- **Desktop Notifications**: Alerts with notifications are displayed when reminders are due (supports macOS).

## Requirements

- Python 3.x
- `tkinter` - GUI framework
- `mysql-connector-python` - MySQL database connector
- `tkcalendar` - Calendar widget for date selection
- `Pillow` - For handling images in the GUI
- `platform` - For OS-specific operations (e.g., macOS notifications)
- `os` - For executing shell commands (e.g., voice notifications)

### Installing Dependencies

To install the required dependencies, run the following command:

```bash
pip install mysql-connector-python tkcalendar Pillow
