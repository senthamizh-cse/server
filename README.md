## server.js

```
const http = require('http');
const server = http.createServer((req, res) => {
  res.writeHead(200, { 'Content-Type': 'text/plain' });
  res.end('Hello, World!\n');
});
const port = 3000;
server.listen(port, () => {
  console.log(`Server running at http://localhost:${port}/`);
});

```
## output
![Screenshot 2024-07-18 142331](https://github.com/user-attachments/assets/ea8349b0-6cf7-4f69-80d9-091d32d2eef6)
