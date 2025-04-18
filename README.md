# 🧩 Task Manager API

A simple REST API built using **Python** and **Flask** to manage tasks — ideal for learning API development and showcasing backend skills.

---

## 🔧 Features

- ✅ Get all tasks
- 🆕 Add a new task
- ✅ Mark task as completed
- ❌ Delete a task

---

## 📦 Tech Stack

- Python 3
- Flask

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/dev-it-shahid/task-manager-api.git

cd task-manager-api
```
### Create and activate a virtual environment (optional but recommended)
```

python -m venv venv
venv\Scripts\activate  # On Windows
```
### 3. Install dependencies
```
pip install flask
```

### 4. Run the Flask app
```
python app.py
```
Visit http://localhost:5000/tasks in your browser or use Postman.

### 🧪 API Endpoints

Method|	Endpoint|	Description
|----|--|--
GET|	/tasks|	Get all tasks       
POST	|/tasks|	Add a new task
PUT	|/tasks/<id>|	Mark task as completed
DELETE|	/tasks<id>|	Delete a task

### 📬 Example JSON
➕ Add Task (POST)
```json
{
  "title": "Write documentation"
}
```
### 🙌 Credits
Built with ❤️ by Shahid Laskar

- `https://github.com/dev-it-shahid/task-manager-api.git` 
- `Shahid Laskar`


