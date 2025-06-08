# 📘 RELEASE DATE 10/08/2025⭐️ — Your Ultimate Forex Trade Tracker FREE AND OFFLINE

🚧 **Important: This project is still in active development. Features may change, and feedback is welcome!**

<img width="1710" alt="Screenshot 2025-06-08 at 05 44 52" src="https://github.com/user-attachments/assets/250637de-eef8-4f6e-84d7-3e2b02040197" />

**Edge Journal** is a professional-grade, data-driven journaling app for forex traders who want to track their performance, refine their strategy, and maintain discipline in the markets.

🚧 **Important: This project is still in active development. Features may change, and feedback is welcome!**

Built with **Streamlit**, it empowers traders to upload trade data, visualize performance, calculate risk, and spot patterns — all in a beautiful and interactive dashboard.

Whether you're trading order blocks, price action, or algo strategies, **Edge Journal** helps you sharpen your edge.

---

## 🚀 Features

✨ **Drag-and-Drop Trade Upload**  
Upload your `.csv` files and instantly visualize your trade history.

📈 **Performance Analytics**  
Win rate, profit breakdown, trade count, and more — all at a glance.

⚖️ **Risk Management Tools**  
Built-in risk calculator to determine position sizes based on your preferred risk percentage.

📊 **Interactive Dashboards**  
Powered by Plotly and Streamlit for dynamic charts and clean data visualizations.

🧠 **Modular Codebase**  
Easily customizable and extensible — perfect for developers and advanced users.

---

## 🖼️ Screenshots
<img width="1218" alt="Screenshot 2025-06-08 at 05 48 38" src="https://github.com/user-attachments/assets/f879abaf-85dd-4554-803d-e7db05a0bcd7" />

<img width="1213" alt="Screenshot 2025-06-08 at 05 49 26" src="https://github.com/user-attachments/assets/6ba2f908-43f1-4c71-822d-13133e3ab5ee" />


### 📂 Dashboard Overview  
...

### 📉 Trade Analysis  
...

### ⚙️ Sidebar Controls  
<img width="444" alt="Screenshot 2025-06-08 at 05 46 42" src="https://github.com/user-attachments/assets/d586f929-3ec9-4e7a-9ae7-2d178dcb1d50" /><img width="441" alt="Screenshot 2025-06-08 at 05 47 06" src="https://github.com/user-attachments/assets/8e315398-1040-43a0-bcc1-f231fea720de" />
<img width="414" alt="Screenshot 2025-06-08 at 05 47 42" src="https://github.com/user-attachments/assets/804af832-2f99-4420-9d59-d6018f2d6b04" /><img width="441" alt="Screenshot 2025-06-08 at 05 48 07" src="https://github.com/user-attachments/assets/51253904-042b-48c8-be0b-276f845ee4df" />




---

## 🛠️ Installation

```bash
git clone https://github.com/yourusername/edge-journal.git
cd edge-journal
pip install -r requirements.txt
streamlit run app/main.py
```

---

## 📁 Folder Structure

```
forex_journal/
├── app/
│   ├── main.py                  # Main Streamlit app
│   ├── components/              # Dashboard, sidebar, etc.
│   ├── utils/                   # Risk calc, analytics, CSV loader
│   └── config.py                # Global constants/settings
├── data/                        # Uploaded CSVs
├── assets/                      # Screenshots, banner images
├── requirements.txt             # Python dependencies
├── .gitignore
└── README.md
```

---

## 📊 Sample CSV Format

Your CSV should include at least these columns:

| date       | pair   | entry | stop_loss | take_profit | result | profit |
|------------|--------|-------|-----------|--------------|--------|--------|
| 2024-06-01 | EURUSD | 1.105 | 1.102     | 1.115        | win    | 100    |

---

## 💡 Roadmap

- [ ] Add tagging for trade setups (e.g., order block, news, breakout)
- [ ] Include multi-timeframe analysis
- [ ] Export analysis to PDF
- [ ] Add dark mode theme

---

## 👨‍💻 Contributing

Pull requests are welcome! Feel free to fork the repo, improve the logic, add features, or enhance the UI.

---

## 📬 Contact

Made with ❤️ by [Abdullah](https://github.com/NotoriousX)  
For feedback or collaboration: abdullah_alsammarraie@outlook.com

---

## 📜 License

MIT License — use it, modify it, share it.
