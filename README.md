# 🖐️ Gesture-Control-PC

A computer vision-powered Python application that lets you control your computer using just your hand gestures — no mouse, no touchpad. Move your cursor, click, scroll, minimize, and close windows using natural hand signs captured via your webcam.

---

## 📽️ Demo

![Demo GIF](assets/Pardhu_OpenCV_mediaPipe_Cursor (1) (1).mp4)

---

## 📌 Features

- 🖱️ **Move Cursor** - Move your open hand in front of the webcam  
- 👊 **Click** - Make a fist gesture  
- ⬆️⬇️ **Scroll** - Hold your index and middle fingers together  
- 📉 **Minimize Window** - Raise your pinky finger  
- 👍 **Close Application** - Show a thumbs-up  
- 👌 **Double Click** - Make an OK sign  

🎮 Includes a **Pygame overlay** that visually displays real-time hand tracking and gesture detection feedback.

---

## 🛠️ Tech Stack

- **Python**  
- **OpenCV**  
- **MediaPipe**  
- **PyAutoGUI**  
- **Pygame**

---

## 📦 Installation

1️⃣ Clone the repository:
```bash
git clone https://github.com/your-username/Gesture-Control-PC.git
cd Gesture-Control-PC
```

2️⃣ Install dependencies:
```bash
pip install -r requirements.txt
```

3️⃣ Run the application:
```bash
python main.py
```

---

## ⚙️ How It Works

- Uses **MediaPipe** to detect hand landmarks in real-time via webcam.
- Maps specific gestures (fist, open hand, thumb up, etc.) to system actions using **PyAutoGUI**.
- Displays real-time gesture feedback and hand detection using **Pygame** overlay.

---

## 💡 Motivation

I’ve always been fascinated by the possibilities at the intersection of computer vision and human-computer interaction. While interning at **Turtil** and diving into machine learning, I challenged myself to create something functional and futuristic — and this is the result!

This project is a small step toward touchless interfaces redefining our digital experience.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙌 Let’s Connect!

Love tech, computer vision, or side projects?  
Feel free to connect and collaborate!

- [LinkedIn](https://www.linkedin.com/in/your-profile)
- [Twitter](https://twitter.com/your-profile)
- [Portfolio/Website](https://your-portfolio.com)

---

## ⭐️ Star this repo if you liked it!

---

## 🔖 TODO

- [ ] Add multi-hand support  
- [ ] Enable custom gesture mapping  
- [ ] Improve gesture detection robustness in low light  
