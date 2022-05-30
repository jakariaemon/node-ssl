# node-ssl
1.	We need a package manager to install mkcert:
•	MacOS: Use Homebrew or Macports.
•	Linux: Use certutil. Arch Linux only, mkcert is available on the Arch Linux repository.
•	Windows: Use chocolatey.
2.	Install mkcert.
3.	 Create a locally trusted CA with mkcert -install.
4.	 Generate an SSL certificate with mkcert localhost. 

It will create the SSL certificate. We need to add it in the code: 
![image](https://user-images.githubusercontent.com/43466665/170935141-c030e06e-09c8-4ee9-ab94-eb4584c0687f.png)

Use npm start, then go to localhost:3000 
