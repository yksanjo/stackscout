# StackScout - Tech Stack Intelligence

<p align="center">
  <img src="https://img.shields.io/badge/Python-FastAPI-00d4aa?style=for-the-badge&logo=python" alt="Python">
  <img src="https://img.shields.io/badge/Tech-Stack-7c3aed?style=for-the-badge&logo=layers" alt="Tech Stack">
</p>

Analyze and compare technology stacks across trending repositories. Make data-driven decisions about your tech stack.

## 🌟 Features

- **Stack Comparison** - Compare tech stacks across repos
- **Trend Analysis** - See which technologies are rising/falling
- **Compatibility Checker** - Check if technologies work well together
- **Recommendations** - Get suggestions based on project type
- **Historical Data** - View tech stack evolution over time
- **Export Reports** - Share findings with your team

## 🚀 Quick Start

```bash
cd backend
pip install -r requirements.txt
python -m uvicorn app.main:app --reload

cd ../frontend
python -m http.server 8080
```

## 🔌 API Endpoints

- `GET /api/stacks` - Get tech stack data
- `POST /api/compare` - Compare stacks
- `GET /api/trends` - Tech trend analysis

---

Built with ⚡ for informed tech decisions
