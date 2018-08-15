# hakoniwa-nginx-docker
箱庭諸島2をnginxで動かす

docker build -t hakoniwa .

docker run -p 5000:80 hakoniwa

Access localhost:5000/hako-xxxx.cgi
