# how to set Views and get the files  . . .hbs .ejb .pub etc
Installation 
```
npm install express
npm install hbs 
```
PreRequirements
```
const path = require('path');
const express = require('express');
const hbs = require('handlebars');
```

```
app.set('views', path.join(__dirname, 'views'));
app.set('view engine', 'hbs');
```
