STP ถ้าเครื่องยังไม่มี Python3 ติดตั้งก่อน:Ubuntu / Debian คำสั่ง : 
```html

apt update && apt install python3 -y
```
รันแบบไม่ต้องโหลดไฟล์ (รันตรงจาก URL) คำสั่ง :
```html

curl -s https://raw.githubusercontent.com/benzvpn/stpvpn/refs/heads/main/chaiya-license-server.py | python3
```
แบบที่1
```
wget https://raw.githubusercontent.com/benzvpn/stpvpn/refs/heads/main/ChaiyaProject-3X-UI-SSHVIP.sh && chmod +x ChaiyaProject-3X-UI-SSHVIP.sh && ./ChaiyaProject-3X-UI-SSHVIP.sh
```
แบบที่2
```
wget https://raw.githubusercontent.com/benzvpn/stpvpn/refs/heads/main/ChaiyaProject.sh && chmod +x ChaiyaProject.sh && ./ChaiyaProject.sh
