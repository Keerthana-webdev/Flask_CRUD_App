## ✨Task Master (Flask Todo App)
A simple and modern Todo Web Application built using **Flask** and **SQLite** with a clean UI.

---

### Features
- ➕ Add new tasks
- 📝 Update existing tasks
- 🗑️ Delete tasks
- 📅 Timestamp for each task
- 🎨 Modern UI with CSS
- 💾 Data stored using SQLite database

---

### Tech Stack
- Python 
- Flask 
- SQLAlchemy 
- HTML + CSS 

---

### Project Structure
```
Todo_Flask/ 
│── app.py 
│── instance/
│   └── test.db 
│── static/ 
│   └── main.css 
│── templates/ 
│   ├── base.html 
│   ├── index.html 
│   └── update.html 
│── requirements.txt
```
---

### How To Run
1. Install `virtualenv`:
```
$ pip install virtualenv
```

2. Open a terminal in the project root directory and run:
```
$ virtualenv env
```

3. Then run the command:
```
$ .\env\Scripts\activate
```

4. Then install the dependencies:
```
$ (env) pip install -r requirements.txt
```

5. Finally start the web server:
```
$ (env) python app.py
```

This server will start on port 5000 by default. You can change this in `app.py` by changing the following line to this:

```python
if __name__ == "__main__":
    app.run(debug=True, port=<desired port>)
```
---

### Author

#### Keerthana S
