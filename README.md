**Project Name: Growtopia HTTPS**

---

### Description:
This project provides a secure server for the popular game Growtopia. It utilizes HTTPS protocol for secure communication and incorporates features such as rate limiting, IP blacklisting, request filtering, and caching to enhance security and performance.

---

### Usage:

1. **Download Executable:**
   - Download the pre-built executable file `HTTPServer.exe` from the provided link.

2. **Configuration:**
   - Ensure your SSL certificate (`cert.pem`) and private key (`key.pem`) are placed in the same directory as the executable.
   - Update the `config.json` file located in the `db` directory with your server details (server name, port, meta).

3. **Running the Server:**
   - Double-click the `HTTPServer.exe` file to run the server.
   - The server will start listening on `0.0.0.0:443`.

---

### Features:

- **HTTPS Support:**
  - Utilizes OpenSSL for secure communication over HTTPS protocol.

- **Rate Limiting:**
  - Protects against excessive requests from individual IP addresses.

- **IP Blacklisting:**
  - Blocks malicious IP addresses based on predefined threshold.

- **Request Filtering:**
  - Filters out potentially harmful HTTP methods and oversized requests.

- **Caching:**
  - Caches frequently requested content for improved performance.

---

### Endpoint:

- **Server Data Endpoint:**
  - `/growtopia/server_data.php`
  - Handles requests related to server data retrieval.

- **Cache Endpoint:**
  - `/cache/<file_path>`
  - Retrieves cached content for specified file path.

---

### Dependencies:
- OpenSSL: Library for SSL/TLS support.

---

### License:
This project is licensed under the [MIT License](LICENSE).

---
### Contact:
For any inquiries or support, please contact our [Telegram Channel](https://t.me/htfgtps).
---

### Acknowledgements:
Special thanks to the creators of the libraries used in this project and the Growtopia community for inspiration.

---

**© 2024 Your Company Name. All rights reserved.**
