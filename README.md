# 🛒 Django Ecommerce Bookstore Project

A clean, beginner-friendly ecommerce platform built using Django — with login/signup, PayPal/card support, and a modern UI. This is a great starter project for learning how to build scalable web apps with Django.

> 💡 Built with ❤️ by **Suraj M** x **Qbit Crew**

---

## 🔗 Project Link

**GitHub Repo:**  
[https://github.com/BytesofSurajm/django-ecommerce-bookstore](https://github.com/BytesofSurajm/django-ecommerce-bookstore)

---

## 🧠 Who is this for?

If you're a complete **noob** but eager to try out Django and clone a live project on your system, this is for you. Follow the steps below, and you’ll be up and running in no time 🔥

---

## 🛠️ Tools You Need

| Tool      | Download Link                         | Purpose                          |
|-----------|----------------------------------------|----------------------------------|
| Python    | https://www.python.org/downloads/      | Runs Django                      |
| Git       | https://git-scm.com/downloads          | Clones project                   |
| VS Code   | https://code.visualstudio.com/         | Code editor                      |
| Chrome    | https://www.google.com/chrome/         | Browser to test project          |

---

## 🚀 Step-by-Step Setup (DIY Friendly)

### 1️⃣ Clone the Project

```bash
git clone https://github.com/BytesofSurajm/django-ecommerce-bookstore.git
cd django-ecommerce-bookstore
```

---

### 2️⃣ Create a Virtual Environment

```bash
python -m venv env
```

Activate it:

- On **Windows**:
  ```bash
  env\Scripts\activate
  ```
- On **Mac/Linux**:
  ```bash
  source env/bin/activate
  ```

---

### 3️⃣ Install Requirements

```bash
pip install -r requirements.txt
```

---

### 4️⃣ Set Up the Database

```bash
python manage.py makemigrations
python manage.py migrate
```

---

### 5️⃣ Create a Superuser (for admin panel)

```bash
python manage.py createsuperuser
```

Follow prompts for username, email, and password.

---

### 6️⃣ Run the Server

```bash
python manage.py runserver
```

Visit your site: [http://127.0.0.1:8000](http://127.0.0.1:8000)  
Admin panel: [http://127.0.0.1:8000/admin/](http://127.0.0.1:8000/admin/)

---

## 💳 PayPal Sandbox Integration

1. Go to: [https://developer.paypal.com/](https://developer.paypal.com/)
2. Create a sandbox account + app
3. Add your credentials (`client_id`, `secret`) into your Django settings or `.env` file.

---

## 🐞 Common Issues & Fixes

| Problem                             | Solution                                |
|------------------------------------|-----------------------------------------|
| `ModuleNotFoundError`              | Run `pip install <missing-package>`     |
| Virtualenv not activating          | Use admin/PowerShell or check your path |
| Port already in use                | Use `python manage.py runserver 8080`   |

---

## 🙋 Need Help?

Raise a GitHub issue here:  
👉 [https://github.com/BytesofSurajm/django-ecommerce-bookstore/issues](https://github.com/BytesofSurajm/django-ecommerce-bookstore/issues)

---

## ✨ Built With

- Django
- HTML / CSS / JS
- Bootstrap
- PayPal SDK

---

## 🧠 About the Creator

**👨‍💻 Suraj M**  
Founder @ **Qbit Crew** – an AI-powered gang building fun & educational tech stuff for students in India 🇮🇳

Connect with us → [https://www.joinqbitcrew.com](https://www.joinqbitcrew.com)

---

## 📜 License

This project is licensed under the MIT License — use it, remix it, launch your own!

---

## 🌈 Final Words

If you're just getting started with Django, this project is a great launchpad. Clone it, tweak it, build your own features — and show the world what you got 🔥

Made with ❤️ by **Suraj M** & **Qbit Crew**
