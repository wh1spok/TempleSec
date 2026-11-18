# 🏛️ TempleSec

<p align="center">
  <img src="https://img.shields.io/badge/Language-Python-blue.svg" alt="Python">
  <img src="https://img.shields.io/badge/Category-Red%20Teaming%20%2F%20OSINT-red.svg" alt="Cybersecurity">
  <img src="https://img.shields.io/badge/Inspired%20by-TempleOS-green.svg" alt="TempleOS">
</p>

Inspired by the unique aesthetic and philosophy of **TempleOS**, **TempleSec** is a multi-purpose reconnaissance and offensive cybersecurity toolkit built for red teaming, OSINT, and security auditing. 

I Believe that a Tool shouldn't have 300 files in one Repo just to use or install, The Repo Comes with Just **TempleSec** and a Optional Installation File. Run the file - and it will install all the 3rd Party Dependencies for you. Otherwise, you can install the imports by yourself.

---

## 🛠️ Features & Tools
`More Tools Will Come Soon!`

* **Network Reconnaissance**
  * **Port Scanner:** Scan target hosts for open ports.
  * **DNS Lookup:** Query DNS records and infrastructure.
  * **WHOIS Lookup:** Retrieve domain registration details.
* **Information Gathering**
  * **IP Geolocation / Info:** Gather location and ISP data for target IPs.
  * **Public IP Retrieval:** Quickly check your current external IP address.
* **Offensive Utilities**
  * **Brute Forcer:** Test login endpoints and authentication mechanisms.
  * **Code Obfuscator:** Obfuscate Python scripts or payloads.

---

## 📦 Dependencies

TempleSec relies on the following 3rd-party Python packages:
* `colorama`
* `requests`
* `dnspython` (imported as `dns`)
* `python-whois` (imported as `whois`)
* `urllib3`

---

##  Installation

Clone the repository and install the required dependencies using `pip`:

```bash
# Clone the repository
git clone [https://github.com/wh1spok/TempleSec.git](https://github.com/wh1spok/TempleSec.git)
cd TempleSec

# Install required packages
pip install colorama requests dnspython python-whois urllib3

      
