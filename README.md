# 🌍 Disaster Response and Management System (DRAMS)

🚨 **The speed of response during natural disasters saves lives.** DRAMS is here to empower communities, aid organizations, and authorities by providing real-time insights, early warnings, and efficient resource management for disaster situations.

---

## 🌟 Features

### 🛠️ Core Functionality:
- **Real-time Monitoring**: Combines data from the Mozilla Location Service API and RSS feeds with geographical information.
- **Layered View Mapping**: Displays affected zones with vegetation details on a dynamic map.
- **Early Warning System**: Provides predictive alerts for potential hazards like landslides or flash floods.
- **Social Crisis Search Engine**: Tracks crisis regions via mobile networks and GPS.

### 🚀 Advanced Functionalities:
- **Pattern Analysis**: Evaluates socioeconomic, anthropogenic, and political factors to identify risk patterns.
- **Color-Coded Visuals**: User-friendly dashboards for different disaster types.
- **Proactive Alerts**: Real-time notifications via social media, news outlets, and public platforms.
- **Predictive Analysis**: Assesses population density, infrastructure vulnerability, and resource availability.

---

## 🔧 Tech Stack

| **Technology** | **Purpose**             |
|-----------------|-------------------------|
| FastAPI         | Backend Development    |
| Mozilla API     | Location Data Retrieval|
| RSS Feeds       | Real-Time Geodata      |
| Google Maps API | Layered Map Views      |
| Python          | Core Programming       |
| HTML/CSS/JS     | Frontend Development   |

---

## 🎯 How It Works

1. **Data Collection** 📡: Gathers live data from APIs, RSS feeds, and mobile networks.
2. **Mapping & Visualization** 🗺️: Creates layered maps with real-time data overlays.
3. **Alert System** 📢: Dispatches early warnings and disaster updates via multiple platforms.
4. **Post-Disaster Analysis** 📊: Assists recovery efforts with actionable insights.

---

## 🚀 Getting Started

### Prerequisites
- Python 3.9+
- Virtual Environment Tool (optional but recommended)
- API Keys for Mozilla Location Service and Google Maps

### Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/DRAMS.git
   cd DRAMS
   ```

2. **Set Up Virtual Environment** (optional):
   ```bash
   python3 -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```

3. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Add API Keys**:
   Create a `.env` file and add:
   ```env
   MOZILLA_API_KEY=your_key_here
   GOOGLE_MAPS_API_KEY=your_key_here
   ```

5. **Run the Application**:
   ```bash
   uvicorn main:app --reload
   ```

6. **Access the App**:
   Open [http://127.0.0.1:8000](http://127.0.0.1:8000) in your browser.

---

## 🤝 Contributing

We welcome contributions! 🛠️ Follow these steps to contribute:

1. Fork the repository.
2. Create a new branch for your feature:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add a new feature"
   ```
4. Push to your branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request on GitHub.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 📢 Acknowledgements

- 🌐 [Mozilla Location Service API](https://location.services.mozilla.com/)
- 🗺️ [Google Maps API](https://developers.google.com/maps)
- 💻 Open-source contributors and developers

---

## 🙌 Join Us

For questions, suggestions, or support, please open an issue or connect with us via [email](mailto:support@drams.com).

---

### 📷 Screenshots

Add some screenshots of your application in action to enhance the README!

---

### 🛠️ Development Status

This project is actively maintained. Stay tuned for updates and enhancements! 🚀
