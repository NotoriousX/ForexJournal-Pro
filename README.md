# 📘 Edge Journal — Your Ultimate Forex Trade Tracker

![Banner](assets/banner_placeholder.png) <!-- Replace with your banner or dashboard screenshot -->

**Edge Journal** is a professional-grade, data-driven journaling app for forex traders who want to track their performance, refine their strategy, and maintain discipline in the markets.

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

> Replace these placeholders with your actual screenshots.

### 📂 Dashboard Overview  
![Dashboard](assets/screenshot_dashboard.png)

### 📉 Trade Analysis  
![Analytics](assets/screenshot_analytics.png)

### ⚙️ Sidebar Controls  
![Sidebar](assets/screenshot_sidebar.png)

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

Made with ❤️ by [Abdullah Al-Sammarraie](https://github.com/NotoriousX)  
For feedback or collaboration: abdullah_alsammarraie@outlook.com

---

## 📜 License

MIT License — use it, modify it, share it.
