
<p align="center">
  <img width=30% src="static/AutoDL-Logo.jpg">
</p>

[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)
![Contributions welcome](https://img.shields.io/badge/contributions-welcome-orange.svg)
[![Slack](https://img.shields.io/badge/Join%20Our%20Community-Slack-blue)](https://join.slack.com/t/autodl/shared_invite/zt-qagxiwub-ywRM_oBvvF~F7YNtlBqy_Q)

# Auto-DL 

### Introduction
Auto-DL helps you make Deep Learning models without writing a single line of code and giving as little input as possible.

- Using the GUI, you can specify the model components and [DLMML](https://github.com/Auto-DL/DLMML) will convert it to code, in the language and framework of your choice.

- You can input the task and other abstract inputs like “data directory”, and the model architecture will also be generated by Auto-DL. It will truly be a one-click DL model development.

### To run Auto DL

1. Clone the repo

```
git clone https://github.com/Auto-DL/Generator.git
git submodule init
git submodule update
```

2. Install the requirements

```bash
pip install requirements.txt
cd FrontEndApp/v1-react
npm install
```

3. Run the application

```
python BackEndApp/manage.py runserver
cd FrontEndApp/v1-react
npm start
```
