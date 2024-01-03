# BCRYPT.JS

```
  const hash = bcrypt.hashSync("surya@123", 10);
  const check = bcrypt.compareSync("myPlaintextPassword","$2b$10$BIFYfa5caeNfXB6.OpJc6O1At.F2i.TJiWJtJ/ytrNSjAQdGFZ5Te");
  console.log(hash);
  console.log(check);
```
