# 📝 Django Blog Project

This is a simple **Django-based blog** where users can create, edit, and manage blog posts. Follow the steps below to set up the project locally.

## 📥 Clone the Repository
Create a folder and in that folder git bash/vscode terminal 
First, download the project by running:
```sh
git clone https://github.com/josephjames123/Blog.git
```

⚙️ **Installation Guide**
1️⃣ Set Up a Virtual Environment in the main folder
It is best to use a virtual environment to manage dependencies:
```sh
python -m venv venv
source venv/bin/activate  # On macOS/Linux
venv\Scripts\activate     # On Windows
```

2️⃣ **Install Required Packages**
Run the following command to install all dependencies:
```sh
pip install -r requirements.txt
```
3️⃣ **Apply Migrations**
Run database migrations to set up the necessary tables:
```sh
python manage.py makemigrations
python manage.py migrate
```

4️⃣ **Create a Superuser** (Optional)
If your project has a Django Admin panel, create a superuser:
```sh
python manage.py createsuperuser
```
Follow the prompts to set up a superuser account.

🚀 **Run the Project**
Start the Django development server:
```sh
python manage.py runserver
```
The project will be available at:
👉 http://127.0.0.1:8000/

📜 **License**
This project is licensed under the MIT License.
Feel free to modify and use it as needed.

👨‍💻 **Maintained by Joseph James**
📧 Contact: josephjames8387@gmail.com
🌍 GitHub: @josephjames123

