# DOM-XSS
Small web app vulnerable to DOM-based Cross Site Scripting

Used to demo DOM Invader Burp extension


This website can be run locally using a Python web server on port 8000

```python -m http.server 8000 --bind localhost```

If you need to access this page from the internet, then use ngrok

```ngrok http localhost:8000```

Which will generate a temporary URL for you.

---
Navigating to the index.html page will prompt you to enter a name, after clicking the Submit button you will be taken to the xss.html page.

This page contains a vulnerable JavaScript sink which can be used to demo Dom-based XSS.
