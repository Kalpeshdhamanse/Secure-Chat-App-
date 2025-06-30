# 🔐 Secure Chat App (End-to-End Encrypted)

## 📌 Project Title
Secure Encrypted Chat Application using Python (Socket + RSA + CLI)

## 📌 Short Description
A command-line-based secure messaging tool developed in Python using socket programming and RSA public-key encryption. It enables two-way communication between a client and server with end-to-end encryption. Ideal for learning cryptography and network security concepts.

---

## 🚀 Features

- 🔐 RSA encryption for secure message transfer
- 🖥️ Command-line interface (CLI)
- 💬 Real-time two-way communication (Client ↔ Server)
- 🛡️ Ensures confidentiality via public/private key encryption
- 🧪 Lightweight, no external server needed

---

## 🛠️ Technologies Used

- Python 3
- PyCryptodome (RSA)
- Socket Programming
- Base64 (for secure data transfer)
- Kali Linux (tested)

---

## 📁 Project Structure

secure-chat-app/
├── client.py
├── server.py
├── encryption_utils.py
├── generate_keys.py
├── keys/
│ ├── client_private.pem
│ ├── client_public.pem
│ ├── server_private.pem
│ └── server_public.pem
├── securechat-venv/ (virtual environment)


---

## ▶️ How to Run

### Step 1: Clone the Repository & Enter Directory
```bash
git clone https://github.com/yourusername/secure-chat-app.git
cd secure-chat-app
```
Step 2: Create and Activate Virtual Environment
```
python3 -m venv securechat-venv
source securechat-venv/bin/activate
```
Step 3: Install Required Packages
```
pip install pycryptodome
```
Step 4: Generate RSA Key Pairs
```
python generate_keys.py
```
Step 5: Start Server (Terminal 1)
```
python server.py
```
Step 6: Start Client (Terminal 2)
```
python client.py
```
