# 🕰️ Analog Clock using HTML, CSS & JavaScript

This project is a simple and visually appealing **Analog Clock** built using **HTML**, **CSS**, and **JavaScript**. It dynamically shows the current time with moving hour, minute, and second hands—just like a real wall clock!

---

## 🚀 Features

- Real-time clock updates every second  
- Smooth rotation of clock hands  
- Pure HTML/CSS/JavaScript (no external libraries)  
- Fully responsive and customizable  

---

## 🛠️ Technologies Used

- **HTML** for the clock structure  
- **CSS** for styling and positioning the hands  
- **JavaScript** for time calculation and hand rotation  

---

## 📸 Preview

<!-- Add your screenshot here -->
![Analog Clock Screenshot](screenshot.png)

---

## 🧩 How It Works

JavaScript fetches the current system time using `Date()` and calculates the correct angles for:

- ⏰ **Hour hand** – rotates 30° per hour plus 0.5° per minute  
- 🕑 **Minute hand** – rotates 6° per minute  
- ⏱️ **Second hand** – rotates 6° per second  

These values are applied to each hand using CSS `transform: rotate(...)` every second.

---

## 📂 Installation & Usage

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/analog-clock.git
   ```

2. **Open `index.html` in your browser**.

That’s it! No build tools or setup needed.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
