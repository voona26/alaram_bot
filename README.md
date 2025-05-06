# ⏰ Alarm Clock GUI using Python

This is a simple desktop-based Alarm Clock built with Python's `Tkinter` module. The application allows users to set a time, and it will play a sound when the system time matches the set alarm time.

## 🚀 Features

- Graphical User Interface using Tkinter.
- Hour, minute, and second dropdowns for setting alarm time.
- Real-time clock monitoring.
- Plays a sound (`sound.wav`) when the alarm triggers.
- Threading used to prevent UI blocking.

## 🛠️ Requirements

- Python 3.x
- `winsound` (built-in for Windows)
- `Tkinter` (comes with standard Python)
- `sound.wav` audio file (should be in the same directory)

## 📦 How to Run

1. Clone the repository or download the script.
2. Make sure you have a `sound.wav` file in the same folder.
3. Run the script:

```bash
python main.py
```

4. Use the dropdowns to set the desired alarm time.
5. Click on **Set Alarm**.

## 🔧 File Structure

```
.
├── main.py         # The main alarm clock script
└── sound.wav       # Audio file that plays when alarm triggers
```

## ⚠️ Note

- This code uses the `winsound` module, which only works on Windows. If you're using Linux or macOS, replace `winsound.PlaySound` with a cross-platform alternative like `playsound`.

## 📸 Screenshot

> _(Insert screenshot here if available)_

## 📜 License

This project is open-source and free to use under the MIT License.
