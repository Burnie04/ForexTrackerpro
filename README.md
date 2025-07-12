# ForexTrackerPro 💱

**ForexTradingPro** is a web-based developer tool that manually compiles live Forex data from multiple financial websites using **web scraping** and **Selenium** automation. Designed with developers and Forex enthusiasts in mind, this tool helps you easily view and analyze exchange rate data in a centralized, customizable interface.

---

## 🚀 Features

- 🔄 **Live Forex Data**: Scrapes real-time exchange rate data from various trusted sources.
- 🕸️ **Web Scraping Engine**: Built using **Selenium** for dynamic content handling and JS-rendered pages.
- 📊 **Interactive UI**: View and compare Forex rates in a clean and modern web interface.
- 🧩 **Modular Components**: Built with **React + TypeScript** and **TailwindCSS** for scalability.
- 📁 **Manual Data Refresh**: Trigger data updates manually when needed, without auto-polling overload.
- ⚙️ **Customizable Source List**: Easily add or remove target websites for scraping.

---

## 🛠️ Tech Stack

- **Frontend**: React + TypeScript + TailwindCSS
- **Backend / Scraper**: Node.js + Selenium + Puppeteer (optional headless browser support)
- **Bundler**: vite
- **Linter**: ESLint
- **Styling**: PostCSS + Tailwind
- **State Management**: React Hooks



🧪 Running the App
Start the frontend:
bash
Copy
Edit
npm run dev



Run the scraper (manual trigger):
bash
Copy
Edit
node scripts/scrape.js
⚠️ You must have Chrome/Chromium installed for Selenium to work properly.



🌐 Live Preview : -
https://686e27f160c0919c08d1fa06--forextrackerpro.netlify.app/



📁 Folder Structure
bash
Copy
Edit
/src
  /components     → UI components (data tables, headers, cards)
  /hooks          → Custom React hooks for Forex data fetching
  /scripts        → Selenium-based scraping scripts
  /assets         → Static files and icons
index.html        → App root
vite.config.ts    → Vite configuration
tailwind.config.js → Tailwind setup



📌 Future Enhancements
✅ Auto-scheduling of scraping jobs

✅ Multi-currency filtering

✅ Export to CSV/Excel

✅ Login for data history tracking



🧑‍💻 Contributing
We welcome contributions! If you'd like to add a new data source, fix a bug, or enhance the UI, feel free to:

Fork the repo

Create your feature branch: git checkout -b feature/YourFeature

Commit your changes: git commit -m 'Add YourFeature'

Push to the branch: git push origin feature/YourFeature

Open a Pull Request



📄 License
This project is licensed under the MIT License.




