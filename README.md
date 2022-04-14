# Pen Testing Report On Wordpress
Testing certain penetration methods on WordPress

## H2 Intial Scan
1.  The first step in my initial scan was to have the docker images of both wordpress and kali running. With kali invoked we will first update the WordPress scans database using 
wpscan --update

2.	Now, I ran wpscan against the running WordPress instance on my local host. Using the following command 
wpscan --url http://127.0.0.1:8080 --api-token YOUR_API_TOKEN
Once scan was run 92 vulnerabilities were found 
 ![](CodePath_WPintialScan.gif)

## H2 Vulenabilities 
