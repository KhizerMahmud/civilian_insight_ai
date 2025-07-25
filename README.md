**Multimodal AI platform for civic issue reporting and prioritization using Hugging Face models.**

## 🚀 Features
- 📸 Image classification for issue detection (e.g., potholes, trash)
- 🎤 Speech-to-text conversion of voice complaints
- 🧠 Text summarization for efficient processing
- 📍 Location tagging of reports
- 🗂️ Frontend dashboard with map + list view

## 🛠 Tech Stack
- **Backend**: FastAPI, Python, Hugging Face Transformers
- **Frontend**: React (Vite), TailwindCSS
- **Docker**: Dockerized backend & frontend

## 📦 Installation
```bash
git clone https://github.com/yourusername/civinsight-ai.git
cd civinsight-ai
docker-compose up --build
```

Then access frontend at `http://localhost:3000` and backend at `http://localhost:8000`.

## 🧪 Sample Workflow
1. Upload image + audio of civic issue
2. Describe the issue and location
3. Submit the form
4. View AI-processed summary and classification

## 🌍 Future Plans
- Add real-time map clustering
- Integrate city 311 APIs
- User authentication and roles