- 👋 Hi, I’m @diep2412
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...import socket

HOST = '127.0.0.1'  # Địa chỉ IP của máy chủ
PORT = 65432        # Cổng mặc định

with socket.socket(socket.AF_INET, socket.SOCK_STREAM) as s:
    s.connect((HOST, PORT))
    while True:
        cmd = input("Nhập lệnh: ")
        s.sendall(cmd.encode('utf-8'))
        data = s.recv(1024)
        print(data.decode('utf-8'))

- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
diep2412/diep2412 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
