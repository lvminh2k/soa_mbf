# soa_mbf
ssh soa@192.168.1.132
ssh soa@192.168.1.131
password soa

#run Customer_Data_Access
sudo docker build -t customer_data_access:1.0 .
sudo docker run --name customer_data_access customer_data_access:1.0
sudo docker rm customer_data_access
sudo docker exec -it customer_data_access bash

