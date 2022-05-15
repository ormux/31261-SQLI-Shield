<h1 align="center">31261 - SQLIA Proxy-based Detection</h1>
<h5 align="center">15/05/2022</h5>

![sqlia-guardian-logo](https://user-images.githubusercontent.com/19354579/168476793-ad4668d9-a050-45e9-bfbd-ea553c7fc13b.PNG)

<h3 align="center">Description</h3>

A simple proxy designed as a proof of concept for the detection and prevention of SQLIA against a vulnerable web application hosted within the same network.

<h3 align="center">Instructions</h3>

1. create python virtual environment
- `python -m venv venv`
- `. venv/bin/activate`

2. install requirements
- `pip install -r requirements.txt`

4. run the proxy
- `python app.py [host] [port]`
- `python app.py localhost 8000`

<h4 align="center">technologies used</h4>
<div align="center">
   <img alt="flask" src="https://img.shields.io/badge/-Flask-black?logo=flask">
   <img alt="python" src="https://img.shields.io/badge/-Python-black?logo=python&logoColor=yellow">
</div>