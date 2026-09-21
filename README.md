# Zero-Token AI

A lightweight, zero-token rule-based AI chatbot web application built with Flask and Gunicorn, designed for instant deployment on Render.

## Features
- **Zero API Costs**: Runs 100% locally with zero external API calls or tokens.
- **Fast & Responsive**: Clean UI with instant answers.
- **Production Ready**: Configured with Gunicorn and `render.yaml` Blueprint for 1-click deployment.

## Running Locally
1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Run the application:
   ```bash
   python app.py
   ```
3. Open your browser and navigate to `http://127.0.0.1:5000`.

## Deployment
This project includes a `render.yaml` Blueprint file, which automatically configures the Python runtime, build command (`pip install -r requirements.txt`), and start command (`gunicorn app:app`) on Render.
