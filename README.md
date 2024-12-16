Deploy antmedia community streaming service on a server.
-------------------------------------------
Edit hosts to configure inventory of streaming servers then to run:

        ansible-playbook -i hosts site.yml

Once done, you can visit the install by browsing to http://SERVERIP:5080. Default credentials are defined as admin/password
