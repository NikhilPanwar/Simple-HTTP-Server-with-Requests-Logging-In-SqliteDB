# Simple-HTTP-Server-with-Requests-Logging-In-SqliteDB

This code was generated using OpenAI ChatGPT.

A simple http server written in python that logs requests to a sqlite DB on local disk.
It can log following data
- request method
- requested path 
- headers
- request body
- timestamp
- IP address of request source

Supports the following methods
- GET
- POST
- HEAD
- OPTIONS
- DELETE

Stores the logs into a sqlite db file on local disk.

Useful for running honeypot and logging incoming malcious requests
