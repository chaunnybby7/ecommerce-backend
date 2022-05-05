## Object-Relational Mapping (ORM): E-Commerce Backend 
  
<p>
    <img src="https://img.shields.io/github/repo-size/chaunnybby7/ecommerce-backend" />



  
<p>
    <img src="https://img.shields.io/badge/express-orange" />
    <img src="https://img.shields.io/badge/Sequelize-blue"  />
    <img src="https://img.shields.io/badge/mySQL-blue"  />
    <img src="https://img.shields.io/badge/dotenv-green" />
</p>

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
![Top Language](https://img.shields.io/github/languages/top/chaunnybby7/ultimatenotetaker)


   
## Description

MySQL database and application backend for an e-commerce site. Built using MySQL, Express, Sequelize and dotenv.
  
  

## Demo



https://user-images.githubusercontent.com/97390473/166848730-a4ffafa5-4a66-4aed-8af1-0b819ca3e1a7.mp4




Or go to:

* <a href="https://drive.google.com/file/d/1zY3DTSq1I1kMHItbPoyyJPZsj2qZLA5s/view"> MySQL/Server Walkthrough Video </a>

Insomnia Walkthrough Video: 

https://user-images.githubusercontent.com/97390473/166848452-4dac11df-8628-4af2-ac4b-885c9faffe7c.mp4


* <a href="https://drive.google.com/file/d/18y1IPBeQfsB1tZH01f5GyQN5HVV4S3OY/view"> API GET routes in Insomnia Core for Categories, Products, or Tags</a>




https://user-images.githubusercontent.com/97390473/166848644-799bbb08-dff4-4c2b-be86-4117787f1d52.mp4




* <a href="https://drive.google.com/file/d/1O4ZsMsthrDBSi-dSlbbYCSdR4uQZ7CtG/view"> API POST, PUT, and DELETE routes in Insomnia Core </a>
  

## Table of Contents
- [Description](#description)
- [Demo](#demo)
- [Table of Contents](#table-of-contents)
- [Installation](#installation)
- [Contributing](#contributing)
- [Questions](#questions)

## Installation

Step 1: Please clone the repository:
```
git clone git@github.com:chaunnybby7/ecommerce-backend.git
```

Step 2: Run the following command at the root of your project
``` 
1. Run `npm init`

2. Run `npm install mysql2`

3. Run `npm install sequelize`

4. Run `npm install dotenv`
```

or Run `npm install`.
  


## Usage

1. Run the following command at the root of your project: 
```
mysql -u root -p
```
Enter your password when prompted.


2. Enter Schema and Seeds commands:

```
`source db/schema.sql`

`USE ecommerce_db;`

`quit` or `exit`

`npm run seed`
  
`npm start`
```
## Testing

No testing is currently set up.

## Authors
YiLin Ong
* [Github] (https://github.com/chaunnybby7)
* [LinkedIn] (https://www.linkedin.com/in/chauntelleong/)

## License 

MIT License

Copyright (c) [2022] [YiLin Ong]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
