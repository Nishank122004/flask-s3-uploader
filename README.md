# Flask S3 File Uploader

This is a simple Flask application that allows users to upload files to an **Amazon S3 bucket**. It also stores upload metadata (filename and timestamp) in a **SQLite database** and generates a **temporary URL** to access the uploaded file.

---

## 🌐 Features

- Upload files from the browser
- Store files in your AWS S3 bucket
- Save upload metadata to a local SQLite database
- Generate a temporary download link (valid for 1 hour)
- Keeps AWS credentials secure using `.env` file


