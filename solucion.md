1. mkdir repoisitorios
2. git clone
3. sudo apt update
4. sudo apt install apache
5. cd var/www
6. sudo mkdir jriveraindarte
7. sudo chown ubuntu jriveraindarte
8. cd etc/apache2/sites-avilables
9. sudo cp 000-default.conf jriveraindarte.conf
10. sudo nano jriveraindart.conf
11. sudo nano hosts
12. systemctl reload apache 2
13. cp -r ~/repoisitorios/AdmInf-web/* /var/www/jriveraindarte/
14. sudo a2ensite jriveraindarte.conf
15. 
{
    "serverName": "jriveraindarte.tecnologoinformatico.com",
    "ip": "144.22.177.72"
}
