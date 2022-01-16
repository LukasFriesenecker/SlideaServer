# Python installieren
https://phoenixnap.com/kb/how-to-install-python-3-ubuntu  
Version: 3.8.2

# Serve Flask Applications
https://www.digitalocean.com/community/tutorials/how-to-serve-flask-applications-with-uswgi-and-nginx-on-ubuntu-18-04

# Flask Oracle
https://docs.oracle.com/en-us/iaas/developer-tutorials/tutorials/flask-on-ubuntu/01oci-ubuntu-flask-summary.htm  
sudo iptables -I INPUT -m state --state NEW -p tcp --dport 5000 -j ACCEPT  
sudo netfilter-persistent save
