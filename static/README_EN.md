# Hello World Flask - Python Project

In this project, we will create a simple "Hello World" project in Python and upload it to GitHub.

---

## STEP 1

Open Visual Studio Code and make sure Python is installed:

```bash
python --version
```

---

## STEP 2

### Create a virtual environment:

```bash
python -m venv venv
```

### Activate the environment:

```bash
venv\Scripts\activate
```

### Install Flask:

```bash
pip install flask
```

### Develop or modify the project as needed

---

### Run the project:

```bash
python app.py
```

---

## STEP 3: Upload to GitHub

Open GitHub, log in, and create an empty repository.

Then, navigate to your project folder and run in the terminal:

```bash
git init
git remote add origin https://github.com/Bryan03A/HelloWorldPY.git
```

### Rename the `main` branch to `test`:

```bash
git checkout -b test
```

> Note: This creates and switches to the `test` branch (if you're on `main`, you can delete it later).

---

## STEP 4: Remove previous content from the remote repo and upload

```bash
git add .
git commit -m "Uploading Flask Hello World project"
git push -u origin test --force
```

---

## STEP 5 (optional): Delete the `main` branch on remote

```bash
git push origin --delete main
```

---

## ✅ Done!

Check that the changes have been applied in your GitHub repository:  
[https://github.com/Bryan03A/HelloWorldPY](https://github.com/Bryan03A/HelloWorldPY)