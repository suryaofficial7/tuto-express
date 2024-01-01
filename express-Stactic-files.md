# Serve HTML CSS & JS Files in Express JS
preRequirement Packages

```
const path = require("path");
or
import path from path;
```
```
const staticPath = path.join(__dirname,"../public");
app.use(express.static(staticPath));

```
