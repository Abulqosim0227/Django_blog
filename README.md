
```markdown
# Project Setup Instructions

Follow these steps to set up the project environment and run the application.

### Step 1: Install `virtualenv`
First, install `virtualenv` using pip:
```bash
pip install virtualenv
```

### Step 2: Create a Virtual Environment
Create a virtual environment named `venv`:
```bash
virtualenv venv
```

### Step 3: Activate the Virtual Environment
Activate the virtual environment:
- On **Windows**:
  ```bash
  venv\Scripts\Activate
  ```
- On **macOS/Linux**:
  ```bash
  source venv/bin/activate
  ```

### Step 4: Install Dependencies
Install the required dependencies from the `requirements.txt` file:
```bash
pip install -r requirements.txt
```

### Step 5: Apply Migrations
Run the following commands to apply database migrations:
```bash
python manage.py makemigrations
python manage.py migrate
```

### Step 6: Start the Development Server
Finally, start the Django development server:
```bash
python manage.py runserver
```

The server will run at `http://127.0.0.1:8000/`.
```

