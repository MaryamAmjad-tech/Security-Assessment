# Complete Guide to Node Authentication with MySQL

❤️ Visit [FullStack Framework 2023](https://github.com/manjeshpv/awesome-sandbox)

Code for the entire scotch.io tutorial series: Complete Guide to Node Authentication with MongoDB

Current version database is ported to MySQL

We will be using Passport to authenticate users locally, 

## Instructions

If you would like to download the code and try it for yourself:

1. Clone the repo: `git clone git@github.com:manjeshpv/node-express-passport-mysql.git`
1. Install packages: `npm install`
1. Edit the database configuration: `config/database.js`
1. Create the database schema: `node scripts/create_database.js`
1. Launch: `node server.js`
1. Visit in your browser at: `http://localhost:8080`


Licence: 1



# Security Assessment - Week 1

## Description
This repository contains a Node.js mock application used for basic vulnerability assessment during Week 1 of the Cybersecurity lab.

## Tasks Completed
✅ Cloned and ran the application locally (`npm install`, `npm start`)  
✅ Tested on `http://localhost:3000`  
✅ Performed vulnerability assessment:
- OWASP ZAP scan
- XSS test (`<script>alert('XSS')</script>`)
- SQL Injection test (`admin' OR '1'='1`)
- Checked for weak password storage
- Checked for misconfigurations

## Findings
- To be added here after your vulnerability testing results.

## Areas of Improvement
- Sanitize user inputs to prevent XSS
- Use parameterized queries to prevent SQL Injection
- Implement proper password hashing
- Apply authentication middleware on protected routes
