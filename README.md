# Blazingly Fast URL Shortener

A high-performance URL shortener service built with Rust, featuring encryption, MongoDB storage, and a clean REST API.

## Features

- ⚡ High-performance Rust implementation
- 🔒 URL encryption using AES-256-GCM
- 📦 MongoDB storage with indexed lookups
- 🔄 Automatic URL deduplication
- ⏰ Optional URL expiration
- 📊 Click tracking
- 🌐 RESTful API

## Prerequisites

- Rust (latest stable)
- MongoDB (4.x or later)
- OpenSSL development libraries

## Quick Start

### Clone the repository

```bash
git clone [YOUR_REPOSITORY_URL]
cd url-shortener
```

### Create a `.env` file

```env
MONGODB_URI=mongodb://localhost:27017/
ENCRYPTION_KEY=your_base64_encoded_32_byte_key
```

Note: To generate a 32-byte key, you can use the following command:

```bash
openssl rand -base64 32
```
