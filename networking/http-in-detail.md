# HTTP in Detail

## Platform

TryHackMe

## Room

HTTP in Detail

## Objective

Understand how HTTP works, how web browsers communicate with web servers, and why HTTP knowledge is essential for web application security testing.

## Topics Covered

- HTTP Basics
- HTTP Requests
- HTTP Responses
- HTTP Methods
- Status Codes
- Headers
- Cookies
- HTTPS

## What is HTTP?

HTTP (HyperText Transfer Protocol) is the protocol used for communication between a web browser and a web server.

Example:

Browser → HTTP Request → Server

Server → HTTP Response → Browser

## HTTP Request Structure

A typical HTTP request contains:

- Request Method
- URL
- Headers
- Body (optional)

Example:

GET /index.html HTTP/1.1

Host: example.com

User-Agent: Mozilla/5.0

## Common HTTP Methods

| Method | Purpose |
|----------|----------|
| GET | Retrieve data |
| POST | Submit data |
| PUT | Update data |
| DELETE | Remove data |
| PATCH | Partially update data |

## HTTP Response Structure

A typical response contains:

- Status Code
- Headers
- Response Body

Example:

HTTP/1.1 200 OK

Content-Type: text/html

## Common Status Codes

| Code | Meaning |
|--------|---------|
| 200 | OK |
| 301 | Moved Permanently |
| 302 | Redirect |
| 400 | Bad Request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |
| 500 | Internal Server Error |

## HTTP Headers

Headers provide additional information about requests and responses.

Examples:

- Host
- User-Agent
- Cookie
- Authorization
- Content-Type

## Cookies

Cookies are small pieces of data stored by the browser.

Common Uses:

- Authentication
- Session Management
- User Preferences

Example:

Set-Cookie: sessionid=abc123

## HTTPS

HTTPS is the secure version of HTTP.

Benefits:

- Encryption
- Data Integrity
- Authentication

HTTPS uses TLS/SSL certificates to secure communication.

## Why HTTP Matters in Pentesting

Understanding HTTP helps penetration testers:

- Analyze requests and responses
- Test authentication systems
- Discover vulnerabilities
- Use Burp Suite effectively
- Identify insecure configurations

## Tools Used for HTTP Analysis

- Burp Suite
- Browser Developer Tools
- cURL
- Wireshark

## Lessons Learned

This room helped me understand how web browsers communicate with servers using HTTP and why HTTP knowledge is essential for web application penetration testing.
