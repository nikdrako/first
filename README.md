from flask import Flask
import gunicorn

для запуску
-w 4 -b 127.0.0.1:5000 main:app
