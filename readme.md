##                     Homework 7   - Docker and Python
This repository contains the dependencies and code for Homework 7 combining Docker with Python program that generates a QR code PNG file that points to my GitHub repository.

###Project Setup

  On cloning the repository, please run
  
  docker build -t qrcode .
  
  docker run --name my_qrcode -e QR_CODE_DIR=test -v .:/app  qrcode --url "https://github.com/Fernandezl7"
  

### Generated a QR code that points to my GitHub repository , Given below MY QRCODE IMAGE 

<img width="350" alt="Image" src="https://github.com/user-attachments/assets/2cf17c50-0f42-4fe8-9bc3-ca90105edd2e" />

### Logs to show Successfully generated QRCODE and saved in test directory 

<img width="1214" alt="Image" src="https://github.com/user-attachments/assets/caef1c04-01c8-4abf-a143-bf0e37802639" />
