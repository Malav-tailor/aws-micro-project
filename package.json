const express = require('express');
const app = express();
const port = process.env.PORT || 8080;

app.get('/', (req, res) => {
  res.send('<h1>CI/CD Pipeline Micro Project</h1><p>Status: Successfully Deployed via Google Cloud Build!</p>');
});

app.get('/health', (req, res) => {
  res.status(200).send('OK');
});

app.listen(port, () => {
  console.log(`App listening on port ${port}`);
});
