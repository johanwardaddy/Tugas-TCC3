<h1>Teknologi Cloud Computing</h1>
Tugas Deploy Static Html
<hr>
<p>Johan Putra Rahmadan <br>
155410165</p>


touch Dockerfile

nano Dockerfile
// isi dari Docker file <br>
FROM nginx:alpine <br>
COPY Tugas-TCC2-master/ /usr/share/nginx/html

docker build -t johan:v1 .

docker images

docker run -d -p 80:80 johan:v1

cek ip docker dengan perintah <i>ifconfig</i><br>
172.17.0.1

buka di broswer

