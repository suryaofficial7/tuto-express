# What is partials
***why do we use partials ?***
-> if you want same set of code for different pages we use Partials Eg: footer , header etc.

prerequirements:-
```
npm install hbs
```
imports
```
const hbs = require('hbs');
```
create a new folder "template" in your Root Folder ...
```
mkdir template 
```
In template add views folder and partials folder 
```
cd template
mkdir views , partials
```

In Express Code i.e index.js
```
hbs.registerPartials(path.join(__dirname, "/template/partials"));
```


