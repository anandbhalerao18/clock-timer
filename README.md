# ⏰ Clock Timer - Digital Clock in C

Welcome to the **Clock Timer** repository! This project showcases a simple digital clock implemented in the C programming language. The clock displays the current time in `HH : MM : SS` format and updates every second.

---

## 📁 Repository Structure

- `main.c`: The core C file containing the source code for the digital clock.

---

## 🔧 How It Works

The program simulates a digital clock by:
- Initializing hours, minutes, and seconds.
- Incrementing the seconds every second using `sleep(1)`.
- Clearing the screen on each update using `system("clear")`.
- Displaying the time in a consistent format using `printf("%02d : %02d : %02d", ...)`.

---

## 🚀 How to Run

1. **Clone the Repository**
   ```bash
   
   git clone https://github.com/anandbhalerao18/clock-timer.git
   cd clock-timer
   
   ```
2. **Compile the code**
   ```bash
   
   gcc main.c -o clock
   
   ```
3. **run the code**
   ```bash
   
   ./clock
   
   ```
  
