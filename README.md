docker network create nginx_proxy  # (sadece bir kez gerekir)
docker compose up -d

firewall üzerinden 1935 oluşturulan container ip ile 1935'e nat yapılır.
subdomain yönlendirilmesi dış ipye yapılır.
nginix proxy manager üzerinden oluşuturulacak subdomain 8080'e bağlanır.
localden ip:8080 portu ile izlenebilir.
live.test.com üzerinden izlenebilir.

yayın : rtmp://live.test.com/live üzerinden yapılır