# 🎯 Guess the Number Game

A simple and interactive number guessing game built using **HTML, CSS, and JavaScript**.  
Try to guess the randomly generated number between **1 and 10** and track your score!

---

## 🚀 Features

- 🎲 Random number generation (1–10)
- 🔢 User input for guesses
- ✅ Instant feedback (Right/Wrong)
- 📉 Score tracking system
- 🎨 Modern UI with animations and gradients
- 📱 Responsive design (works on mobile too)

---

## 🖥️ Demo

> Enter a number between **1 and 10** and click **Check** to see if you guessed correctly.

---

## 📂 Project Structure

```
📁 Guess-the-Number
 ┣ 📄 index.html
 ┗ 📄 README.md
```

---

## 🛠️ Technologies Used

- **HTML5** – Structure  
- **CSS3** – Styling & animations  
- **JavaScript** – Game logic  

---

## ⚙️ How It Works

1. A random number between **1 and 10** is generated:
   ```js
   var randomnumber = Math.floor(Math.random() * 10) + 1
   ```

2. User enters a number and clicks **Check**

3. If correct:
   - Displays ✅ *You are Right*
   - Shows success animation

4. If wrong:
   - Displays ❌ *You are Wrong*
   - Score decreases by 1

---

## ▶️ How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/guess-the-number.git
   ```

2. Open the project folder

3. Open `index.html` in your browser

---

## 📈 Future Improvements

- 🔁 Reset button
- 🔊 Sound effects
- 🏆 High score tracking
- 🎯 Difficulty levels (1–50, 1–100)

---

## 🤝 Contributing

Feel free to fork this repo and improve the game!  
Pull requests are welcome.

---

## 📄 License

This project is open-source and free to use.
