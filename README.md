---

**Project Name: Growtopia HTTPS**

---

### Description:
Growtopia HTTPS provides a secure server for the popular game Growtopia, ensuring encrypted communication with the use of HTTPS protocol. This project enhances server security and performance through advanced features such as rate limiting, IP blacklisting, request filtering, and efficient caching.

---

### Usage:

1. **Download Executable:**
   - Obtain the pre-built executable file `HTTPServer.exe` from the provided link.

2. **Configuration:**
   - Place your SSL certificate (`cert.pem`) and private key (`key.pem`) in the same directory as the executable.
   - Edit the `config.json` file located in the `db` directory to configure server details (e.g., server name, port, and meta).
   - Update the `blacklist.txt` file in the `db` directory with IP addresses to be blocked by the server.

3. **Running the Server:**
   - Execute the `HTTPServer.exe` file by double-clicking it.
   - The server will start and listen for incoming connections on `0.0.0.0:443`.

---

### Features:

- **HTTPS Support:**
  - Leverages OpenSSL to provide secure HTTPS communication.

- **Rate Limiting:**
  - Implements safeguards against excessive requests from individual IP addresses.

- **IP Blacklisting:**
  - Blocks malicious IP addresses dynamically. Update `blacklist.txt` with IPs to block them.

- **Request Filtering:**
  - Filters harmful HTTP methods and rejects oversized requests to protect server integrity.

- **Caching:**
  - Improves performance by caching frequently requested content.

- **Request Logging:**
  - Logs incoming requests with timestamps for effective monitoring and debugging.

- **Proxy Attack Detection:**
  - Detects and mitigates potential proxy-based DDoS attacks.

- **Dynamic Configuration Loading:**
  - Supports dynamic loading of server configurations from a JSON file for flexibility.

- **Content Delivery:**
  - Efficiently serves content with caching support and proper handling of missing files.

- **Custom Dialog Notifications:**
  - Displays customizable popup dialogs for server status updates or alerts.

---

### Endpoints:

- **Server Data Endpoint:**
  - **URL:** `/growtopia/server_data.php`
  - **Description:** Handles requests related to retrieving server data.

- **Cache Endpoint:**
  - **URL:** `/cache/<file_path>`
  - **Description:** Retrieves cached content based on the specified file path.

- **Blacklist Management:**
  - **Description:** Manage IP blacklisting through the `blacklist.txt` file. The server will reload the blacklist dynamically upon updates.

---

### Dependencies:
- **OpenSSL:** Provides SSL/TLS support for secure communication.
- **nlohmann/json:** Facilitates JSON handling and parsing.
- **cpp-httplib:** C++ HTTP library for handling HTTP requests and responses.

---

### License:
This project is licensed under the [MIT License](LICENSE).

---

### Contact:
For support or inquiries, please reach out to us via our [Telegram Channel](https://t.me/htfgtps).

---

### Acknowledgements:
We extend our gratitude to the creators of the libraries utilized in this project and the Growtopia community for their ongoing inspiration and support.

---

**© 2024 How To Fix (GTPS). All rights reserved.**

---
