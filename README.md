
## 🚀 How It Works

- The app creates a `JFrame` window.
- A `JLabel` is used to display the formatted time (`HH:mm:ss`).
- A Swing `Timer` runs every 1000 milliseconds (1 second) to update the time display.

## 🧾 Code Summary

```java
SimpleDateFormat dateFormat = new SimpleDateFormat("HH:mm:ss");
String formattedTime = dateFormat.format(new Date());
timeLabel.setText(formattedTime);
