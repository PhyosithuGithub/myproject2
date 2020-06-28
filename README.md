# myproject2
-This is a Ecommer Website.
-I run this project with my local custom Domain(shop.ps). If you got any error about URL ROOT. 
-you have to fix somthing changes.
-firstly, you have to create your custom domain. With Xampp server, you have to follow this step
    - go to xampp>apache>conf>extra> httpd-vhosts.conf
    <virtualHOST *:80>
      DocumentRoot (put your root folder )
      ServerName shop.ps
      <Directory "Your root folder">
        Require all granted
        order allow,deny
        Allow from all
      </Directory>
    </VirtualHost>
    - C:/windows>Systems32>drivers>etc>hosts (do something changes)
      shop.ps
      

-secondly, go back to your project foler
  -bootstrap>init.php>line 6. please check URL_ROOT if you have some error
  
