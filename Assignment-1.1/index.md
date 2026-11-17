# Assignment 1.1 — How a Website Works

## Explanatory Paragraph

When you type a URL into a web **browser** (which acts as the **client** on your device), it starts a **request-response cycle** to load the webpage on your screen. First, the browser sends an HTTP or HTTPS request across the internet to the web **server** hosting the website, where **HTTP** (*HyperText Transfer Protocol*) transfers data in plain text and **HTTPS** (*HyperText Transfer Protocol Secure*) encrypts the connection using SSL/TLS to keep data safe. Once the server receives the request, it determines what files to send back: if the site is a **static website**, the server immediately returns fixed, pre-built HTML, CSS, and JavaScript files that look identical for every user; if it is a **dynamic website**, the server connects to a **database** to fetch live or personalized data (such as user accounts, posts, or product listings) and builds a customized page in real time. Finally, the server sends these files back to the client in an HTTP/HTTPS response, and the browser translates the code to display the complete website on your screen.

---

## Key Concepts Breakdown

### 1. Roles of Browser, Client, Server, and Database
* **Client:** The user's device (computer, smartphone) or software application that initiates requests for web resources.
* **Browser:** The specific client application (such as Google Chrome, Safari, or Firefox) that sends requests to servers and renders HTML, CSS, and JavaScript into a visual webpage.
* **Server:** A remote, always-on computer that stores website files, processes incoming client requests, and sends back the requested resources.
* **Database:** An organized storage system that holds structured data (like user profiles, comments, or inventory) that the server queries when building dynamic content.

### 2. Meanings of HTTP and HTTPS
* **HTTP (HyperText Transfer Protocol):** The standard communication protocol used to transfer web pages and media between a browser and a server without encryption.
* **HTTPS (HyperText Transfer Protocol Secure):** The secure version of HTTP that uses TLS/SSL encryption to protect data from interception or tampering during transfer.

### 3. The Request-Response Cycle
1. **Request:** You enter a URL, and the browser sends an HTTP/HTTPS request (e.g., `GET /index.html`) to the server.
2. **Processing:** The server receives the request, runs any necessary backend logic, and queries the database if required.
3. **Response:** The server sends back an HTTP/HTTPS status code (such as `200 OK`) along with the website's files (HTML, CSS, JS, images).
4. **Rendering:** The browser reads the response files and paints the webpage on your screen.

### 4. Static vs. Dynamic Websites

| Feature | Static Website | Dynamic Website |
| :--- | :--- | :--- |
| **Content** | Fixed; every visitor sees the exact same content. | Changes based on the user, time, or database updates. |
| **Database Usage** | Does not require a database. | Relies heavily on a database to fetch and store data. |
| **How It Works** | Server sends pre-written HTML/CSS/JS files directly. | Server generates pages on the fly using backend code. |
| **Examples** | Portfolios, documentation pages, landing pages. | Social media (Instagram), e-commerce (Amazon), YouTube. |

---

## Chrome DevTools Network Tab Screenshot

*(Insert your screenshot of the Chrome DevTools Network tab here)*