# Go URL Shortener

A simple **URL shortener service** built with **Golang**.  
It generates short hashes for long URLs and lets you redirect back to the original link.

---

## Features
- Shorten any long URL into a unique short hash  
- Redirect short URL → original URL  
- JSON-based in-memory storage (can be extended to DB)  
- REST API built using Go’s `net/http`  

---

## Tech Stack
- **Language**: Go (Golang)  
- **Libraries**: `crypto/md5`, `encoding/json`, `net/http`  
- **Database**: In-memory (map)
