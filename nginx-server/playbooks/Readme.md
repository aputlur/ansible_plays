Creating TLS Certificate

openssl req -x509 -nodes -days 3000 -newkey rsa:2048 \
    -subj /CN=localhost \
    -keyout files/nginx.key -out files/nginx.crt
