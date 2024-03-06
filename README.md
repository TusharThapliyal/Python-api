# python-api

this repository contains code of python flask api. It is a part of a bigger project with 3 repositories: Terraform-jenkins and Terraform-app.

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
this API just takes a string. and saves it in mySQL engine on Aws RDS. This repo does not contain terraform code for the AWS provisioning. use repo: [TusharThapliyal/Terraform-api](https://github.com/TusharThapliyal/Terraform-app.git)

<img width="1440" alt="Screenshot 2024-03-07 at 4 30 22 AM" src="https://github.com/TusharThapliyal/python-api/assets/75366942/9cd61494-0f74-4a8c-ae12-5f0fd754f9a7">
