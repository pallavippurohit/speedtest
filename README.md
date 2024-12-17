# speedtest
Deploy speedtest application as docker compose

Create 2 folders **certs** & **conf** 

Create SSL certificate for the domain you want and put it's .crt & .key file in certs folder

Put nginx.conf in the conf folder

In nginx.conf replace **domain_name** with domain name you want

Then run `docker-compose up -d` 
