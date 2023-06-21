# Setup_Linux_DNIe_Izenpe

1. Install  pre-requisites:
```
sudo apt-get install opensc pcscd libnss3-tools pcsc-tools pcscd firefox openjdk-18-jre
```

2. Download DNIe or izenpe software for linux and certificates

Izenpe. e.g. https://www.izenpe.eus/software/

- Software Izenpe para Linux
- Certificado Izenpe para Ubuntu Debian
- Linux 64bits

e.g. DNIe https://firmaelectronica.gob.es/Home/Descargas.html

- AutoFirma 1.8.2 para Debian Linux

3. Install DNIe / izenpe software

Izenpe 
```
unzip Software_Izenpe_Linux.zip
sudo dpkg -i  Middleware_izenpe_XXXX
sudo dpkg -i  izenpe-certificatesXXXX
chmod +x idazki-desktop-linux64.run
sudo ./idazki-desktop-linux64.run
```
DNIe
```
sudo dpkg -i AutoFirma_1_8_2.deb
```

3. Check certificates are installed
- Firefox
   - Settings --> Privacy and Security --> Security Devices
   - "Izenpe"  -> /usr/lib/bit4id/libbit4ipki.so


4. Just enjoy the wonders of digital certificates
