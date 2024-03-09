# python-api

This repository contains code of python flask API. It is a part of DevOps projects with two additional repositories: [Terraform-app](https://github.com/TusharThapliyal/Terraform-app.git) and [Terraform-jenkins](https://github.com/TusharThapliyal/Terraform-jenkins.git)

## Installation

Ensure you have all the requirements installed. pip, Flask, pymysql
```bash
yes | sudo apt update
yes | sudo apt install python3 python3-pip
pip3 install Flask
pip3 install pymysql
setsid python3 -u app.py
```

## Usage 
This API takes a string as input and saves it in mySQL database running on Aws RDS. For terraform code to provision the required AWS architecture, use repo: [TusharThapliyal/Terraform-jenkins](https://github.com/TusharThapliyal/Terraform-jenkins.git) for Jenkins server and [TusharThapliyal/Terraform-app](https://github.com/TusharThapliyal/Terraform-app.git) for application server

<img width="1440" alt="Screenshot 2024-03-07 at 4 30 22 AM" src="https://github.com/TusharThapliyal/python-api/assets/75366942/9cd61494-0f74-4a8c-ae12-5f0fd754f9a7">
