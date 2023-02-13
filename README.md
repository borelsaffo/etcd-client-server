# etcd-client-server
Install etcd-cleint and etcd-server

RUN : 
mkdir etcd
wget https://github.com/etcd-io/etcd/releases/tag/v3.5.7 /etcd
cd etcd
tar xzvfetc.......
![image](https://user-images.githubusercontent.com/27947973/218487632-7f63f02b-7a40-4cb7-b199-459759f7accf.png)

Run :
./etcd
![image](https://user-images.githubusercontent.com/27947973/218487798-48a6814e-fee9-41b2-9127-03a4fab88b88.png)


![image](https://user-images.githubusercontent.com/27947973/218487081-d8d00cc6-e4b4-4b5f-8d46-eb041c62ae76.png)
etcd --listen-client-urls=http://127.0.0.1:2379 \
   --advertise-client-urls=http://127.0.0.1:2379
![image](https://user-images.githubusercontent.com/27947973/218486911-31dafbe0-9457-4276-91cf-d81405b5e549.png)

