# Google-Drive-File-Upload



# File Upload to Google Drive Project

This project is a simple backend server built with **Node.js**, **Express**, and **Google Drive API** that allows you to upload files to Google Drive. The uploaded files are made publicly accessible with a shareable link.

## Features

- Upload files to Google Drive.
- Store files in a specific folder in Google Drive (configured by folder ID).
- Make uploaded files publicly accessible by generating a shareable link.
- Handles file uploads through **Multer** middleware.
- Server is built with **Express** and uses **Google Drive API** for file upload functionality.

## Prerequisites

To run this project locally, you need the following:

- **Node.js** installed on your system.
- A **Google Cloud project** with the **Google Drive API** enabled.
- A **service account key** (JSON format) from Google Cloud to authenticate with the Google Drive API.
- **Multer** package for handling file uploads.
- A **Google Drive folder** where files will be stored. (The folder ID should be set in the code.)

## Getting Started

### 1. Clone the Repository

Clone this repository to your local machine.

```bash
git clone https://github.com/your-username/file-upload-project.git
cd file-upload-project
