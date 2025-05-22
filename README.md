# fastapi-htmx-test-insights

A lightweight web application that combines **FastAPI** with **HTMX** for modern, server-driven interactivity and testing insights. This project uses **Invoke** for Python-based task automation.

---

## 🚀 Features

- ⚡️ **FastAPI** for fast, async Python web APIs
- 🧠 **HTMX** for dynamic frontend interactivity without writing JavaScript
- 🧪 Modular test insights service layer
- 🎨 Jinja2 templates for full and partial rendering
- 🛠️ **Invoke**-based task automation
- 🧪 **Pytest** for unit/integration testing
- 📦 Optional Docker support

---

## 📁 Project Structure

```
fastapi-htmx-test-insights/
├── app/
│   ├── api/              # Routes and endpoints
│   ├── services/         # Business logic layer
│   ├── templates/        # Jinja2 full/partial HTML templates
│   ├── static/           # Static assets (CSS, JS, images)
│   ├── config.py         # App settings
│   └── main.py           # FastAPI entrypoint
├── tests/                # Pytest-based test suite
├── tasks.py              # Invoke task definitions
├── .env                  # Environment variables
├── requirements.txt      # Python dependencies
├── Dockerfile            # Optional container build file
└── README.md             # You're here!
```

---

## 🛠️ Setup

### 1. Clone the repo

```bash
git clone https://github.com/ocrosby/fastapi-htmx-test-insights.git
cd fastapi-htmx-test-insights
```

### 2. Create virtual environment

```bash
python -m venv .venv
source .venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

---

## 🧪 Run the Application

```bash
invoke run
```

Then navigate to: [http://127.0.0.1:8000](http://127.0.0.1:8000)

---

## 🧰 Common Tasks (via Invoke)

| Command         | Description                     |
|----------------|---------------------------------|
| `invoke run`   | Start the FastAPI dev server    |
| `invoke lint`  | Run `flake8` linter             |
| `invoke format`| Auto-format with `black`        |
| `invoke test`  | Run tests using `pytest`        |

---

## 🧱 Tech Stack

- [FastAPI](https://fastapi.tiangolo.com/)
- [HTMX](https://htmx.org/)
- [Invoke](https://www.pyinvoke.org/)
- [Jinja2](https://jinja.palletsprojects.com/)
- [Pytest](https://docs.pytest.org/)

---

## 🤝 Contributing

Contributions are welcome! Please open an issue or PR with improvements, fixes, or ideas.

1. Fork this repo
2. Create a feature branch
3. Commit and push your changes
4. Open a pull request

---

## 📄 License

This project is licensed under the MIT License. See `LICENSE` for more information.

## References

- [FastAPI and HTMX](https://testdriven.io/blog/fastapi-htmx/)
