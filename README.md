# stopwatch-using-python
This project is a graphical digital clock application developed using Python and the PyQt5 framework. It provides a real-time display of the current system time within a simple and visually appealing user interface. The primary objective of this project is to demonstrate the use of GUI components, event-driven programming, and time-based updates in Python.

The application is built using a QWidget as the main window, which contains a QLabel to display the time. A QVBoxLayout is used to organize and center the label within the window, ensuring a clean and structured layout. The clock updates dynamically with the help of a QTimer, which triggers the time update function at regular intervals (every second).

The current time is retrieved using QTime.currentTime() and formatted into a readable string that includes hours, minutes, seconds, and an AM/PM indicator. This formatted time is then displayed on the label, giving the user an accurate and continuously updating digital clock.

To enhance the visual appearance, custom styling is applied using Qt Style Sheets. The background of the application is set to black, while the text is displayed in a bright green color, resembling a classic LED digital clock. Additionally, a custom font (DS-DIGIT) is loaded using QFontDatabase, which further improves the aesthetic by providing a realistic digital display effect.

The project highlights key concepts such as GUI design, widget management, layout handling, and real-time updates using timers. It also introduces the integration of external resources like custom fonts into a PyQt application.

Overall, this digital clock application is a beginner-friendly project that effectively demonstrates how to build interactive and visually appealing desktop applications using PyQt5, while also reinforcing fundamental programming and design principles.
