# COMPS381F-Assignment
> OUHK 2019/20 Server-side Technologies and Cloud Computing (COMPS3812F) Group Project

> Web application: Restaurant website

[![Build Status](https://travis-ci.com/alvinau0427/COMPS381F-Assignment.svg?branch=master)](https://travis-ci.org/alvinau0427/COMPS381F-Assignment)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

## Getting Started
- An Express server that provides the basic CRUD serverices for the restaurants collection. The server running on Heroku with MongoDB.

## Features
- Create user accounts
- Create new restaurant documents
- Update restaurant documents
- Rate restaurant and a restaurant can only be rated once by the same user
- Display restaurant documents
- Delete restaurant documents
- Search

## Installation

### Setup
```
$ npm install
$ npm start
```

### Run the program
- If running in local host please change for your own MongoDB connection, then visit `localhost:8099` on browser.

- Deployed at https://alvinau0427-comps381f.herokuapp.com/
- P.S. The demonstration account: ID 'demo01', 'demo02' with no password

## Screenshots
![Image](https://github.com/alvinau0427/COMPS381F-Assignment/blob/master/doc/demo.png)

## License
- COMPS381F-Assignment is released under the [MIT License](https://opensource.org/licenses/MIT).
```
Copyright (c) 2020 alvinau0427

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
```
