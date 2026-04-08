# ✅ 1. REPOSITORY NAME (choose one)

### 🥇 Recommended:

👉 **kivy-calculator-app**

### Other options:

* `python-kivy-calculator`
* `av-calculator-kivy`
* `gui-calculator-python`

---

# ✅ 2. GITHUB DESCRIPTION

```text
A simple GUI calculator built using Python and Kivy with basic arithmetic operations and interactive UI.
```

---


---

# ✅ 3. README.md

````markdown
# 🧮 Kivy Calculator App

A simple and modern calculator built using **Python** and **Kivy** with a clean graphical user interface.

---

## 🚀 Features

- ➕ Basic arithmetic operations (+, -, *, /)
- 🔢 Support for decimal and double zero (00)
- 🔄 Sign toggle (+/-)
- 📊 Percentage calculation (%)
- 🧹 Clear screen (C)
- 🎨 Clean and responsive UI

---

## 🏗️ Tech Stack

- Python
- Kivy (GUI Framework) and best for beginner level mobile app.

---

## 📦 Installation

### 1. Clone the repository
```bash
git clone https://github.com/your-username/kivy-calculator-app.git
cd kivy-calculator-app
````

### 2. Install dependencies

```bash
pip install kivy
```

---

## ▶️ Run the App

```bash
python main.py
```

---


## 📁 Project Structure

```
kivy-calculator-app/
│
├── main.py
├── README.md
```

---

## 🔮 Future Improvements

* Scientific calculator features
* Keyboard input support
* Dark/Light theme toggle
* History of calculations

---

## 👨‍💻 Author

**Chanchal Choudhary**

---

## ⭐ Support

If you like this project, please ⭐ star the repository!

```

---

# ✅ 4. FILE STRUCTURE (IMPORTANT)

Create your repo like this:

```

kivy-calculator-app/
│
├── main.py   ← your code
├── README.md

````

---

# ✅ 5. IMPORTANT FIX (HIGHLY RECOMMENDED)

⚠️ our current code uses:
```python
eval(self.result.text)
````

👉 This is unsafe (bad practice)

### 🔥 Better (safe version):

Replace:

```python
self.result.text = str(eval(self.result.text))
```

With:

```python
import math
self.result.text = str(eval(self.result.text, {"__builtins__": None}, {}))
```

---


