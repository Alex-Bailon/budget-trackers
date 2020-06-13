# budget-trackers
 
## Description

Budget-tracker allows the user to be able to keep track of expenses both on- and offline. Using a mongobd expenses are stored in database and chart is updated when the user is online. If the user is offline and has no network the expenses are stored in a indexedDB. When the user gains an network connection the mongobd is updated based off the informtion that was stored in the indexedDB. To have the app be operational the following tools were used: 
* Express
* Mongoose
* Morgan
* Compression

## Installation/Usage

Please ensure to do the following in terminal: 

* Run `npm install`
* To run code type `npm start`

A deployed version of the app can be found [here](https://vast-chamber-38546.herokuapp.com/)  
Below is a screenshot of the working app  
![budget-tracker homepage](./budget-tracker.png)  


## License
MIT License

Copyright (c) 2020 Alex Bailon

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

