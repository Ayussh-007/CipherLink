# CipherLink

CipherLink is a command-line based chat application built entirely in Python, designed for secure, encrypted communication between users over a local or simulated network. It uses end-to-end encryption (E2EE) with public-private key cryptography, ensuring that only the intended recipient can read the message — not even the server can see the contents.

✨ Features:
🔐 End-to-End Encryption using RSA keys (via pycryptodome)
🔄 Client-Server Architecture using Python’s socket module
💬 Real-Time Messaging with support for multiple clients
🧵 Multithreaded Server to handle simultaneous conversations
📁 Modular Codebase (client.py, server.py, encryption.py, utils.py, etc.)
🕓 Timestamped Messages and optional encrypted chat logging
🧠 Extensible Design — ready for features like file transfer or GUI

🛠 Technologies Used:
Python 3.x
socket — networking
threading — concurrency
pycryptodome — RSA encryption
argparse, logging, time — utility modules
