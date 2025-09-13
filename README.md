# Indian Constitution Search App

A simple **single-page web application** to search and explore articles of the **Indian Constitution**.  

Built with **HTML, TailwindCSS, and Vanilla JavaScript**, this app allows users to search by **article number, title, or keywords**.  

---

## 🚀 Features

- **Search Functionality**  
  Search articles by:
  - Article number (e.g., `325`)
  - Title (e.g., `Name and territory of the Union`)
  - Keywords within the description (e.g., `sovereign`, `justice`).

- **Dynamic Results**  
  - Search results are displayed instantly.  
  - Results update on pressing **Enter** or clicking **Search**.  

- **Dark / Light Theme Toggle** 🌙☀️  

- **Share Button**  
  - Copies the page link to your clipboard.  
  - Temporary notification confirms the copy action.  

- **Responsive Design**  
  - Optimized for desktop and mobile.  
  - Built with **TailwindCSS**.  

---

## 📂 Project Structure

project/
│── index.html # Main app (HTML + CSS + JS in one file)
│── README.md # Documentation

yaml
Copy code

---

## 🔧 Requirements

No backend or dependencies are needed.  
The app runs **entirely in the browser**.

---

## ▶️ Running the App

### Option 1: Open Directly
1. Download or clone the repository.  
2. Open `index.html` in any modern web browser (Chrome, Firefox, Edge).  

### Option 2: Run with a Local Server (Recommended for Development)
You can use **Python’s built-in server** or any static server:

```bash
# Python 3
python -m http.server 8080
Then open:
👉 http://127.0.0.1:8080/index.html

💻 Usage
Type a search term in the input box.

Example: 1 → shows Article 1.

Example: preamble → shows the Preamble.

Press Enter or click Search.

Results appear dynamically as cards.

Toggle dark/light theme using the button in the header.

Click Share → the link is copied to clipboard.

📑 Example Constitution Data
The data is embedded directly in the app. Example:

json
Copy code
[
  {
    "article": 0,
    "title": "Preamble",
    "description": "WE, THE PEOPLE OF INDIA, having solemnly resolved..."
  },
  {
    "article": 1,
    "title": "Name and territory of the Union",
    "description": "(1) India, that is Bharat, shall be a Union of States..."
  }
]
⚠️ Notes
This is a static demo project and does not fetch data from a server.

To expand, you can add more articles to the embedded constitutionData array in the <script> section.

📜 License
This project is for educational purposes.
Not affiliated with the Government of India.

