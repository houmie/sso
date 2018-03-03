# sso
An Example with flask and keycloak

####Flask Client
1) `pip install -U -r requirements.txt`
2) `python src/app.py`
3) Login with `foo@bar.com` and `secret`

####KeyCloak Server
1) Download keycloak
2) Download latest JRE 1.8
3) `vim ~/.bash_profile`
4) `export PATH=/Library/Internet\ Plug-Ins/JavaAppletPlugin.plugin/Contents/Home/bin:$PATH`
5) Restart your Computer
6) cd keycloak_server/bin/
7) ./standalone.sh

1) Create the admin under http://localhost:8080/auth
2) Login http://localhost:8080/auth/admin/
3) Creating a Realm and User
https://keycloak.gitbooks.io/documentation/getting_started/topics/first-realm/realm.html