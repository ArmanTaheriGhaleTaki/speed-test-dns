<!-- ABOUT THE PROJECT -->
## About speed-test-dns

I had so many challenge in choosing the best DNS sni proxy server thats fits my internet service provider so I develope an script that tests the speed of the DNSs so I won't waste my time on finding the best DNS server  

      
![output](https://github.com/ArmanTaheriGhaleTaki/speed-test-dns/assets/88885103/d83c954e-5f3c-434e-ae4b-f119d69a4220)    



<!-- GETTING STARTED -->
## Getting Started
you can use this script with **docker** or on **bare metal** 
## bare metal
you need **root** accsses and **wget** package    
you can edit variables and customize the scripts for your needs [bash.sh](https://github.com/ArmanTaheriGhaleTaki/speed-test-dns/blob/main/bash.sh).

```sh
git clone https://github.com/ArmanTaheriGhaleTaki/speed-test-dns/ && cd speed-test-dns&& sed -i '2,4 s/^#//' bash.sh && sudo apt update && sudo apt install -y wget && sudo bash bash.sh
```
## docker
you only need **docker** installed and you can edit variables in  [Dockerfile](https://github.com/ArmanTaheriGhaleTaki/speed-test-dns/blob/main/Dockerfile) for your needs.

[**suggested**] using docker 

  ```sh
  git clone https://github.com/ArmanTaheriGhaleTaki/speed-test-dns/ && cd speed-test-dns && docker build -t speedtestdns . && docker run speedtestdns
  ```

## Contributing

you can add new DNS servers in [Dockerfile](https://github.com/ArmanTaheriGhaleTaki/speed-test-dns/blob/main/Dockerfile) with the following format
```
#########################
#https://example.com/
#xxx.xxx.xxx.xxx yyy.yyy.yyy.yyy
```
If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- CONTACT -->
## Contact

my social media - [@armondy🙄](https://twitter.com/taherighaletaki) - armantahery1381@gmail.com

Project Link:  [speed-test-dns](https://github.com/ArmanTaheriGhaleTaki/speed-test-dns) 




