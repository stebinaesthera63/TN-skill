# Installation

## Requirements

Python 3.x

## Setup

Create virtual environment:

python -m venv venv

Activate:

.\venv\Scripts\Activate.ps1

Install packages:

pip install -r requirements.txt

Run:

python -m uvicorn app.main:app --reload

Open:

http://127.0.0.1:8000/