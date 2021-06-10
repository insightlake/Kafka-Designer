# Kafka.Cluster

## 1)Create RBAC and KERBEROS Configuration for Ansible Cluster
   i)Add host Of Component <br />
   ii)Select Confluent Clod Cluster Type<br />
  iii)We can select version from kafka version dropdown<br />

   <img src="cluster1.png" width="1000" height="600">
   
   2)Specify cluster Security<br />
    i)We can configure rest end point security by enabling flag true<br />
   ii)We can configure Zookeeper security<br />
  iii)We Can configure RBAC by enable true flag <br />
      if RBAC enable rbac listener required<br />
   iv)Select SASL type GSSAPI it will enable kerberos
  
    
   
   <img src="cluster2.png" width="1000" height="600">
   
   
   3)Specify cluster Monitoring<br />	
     Here we can configure Monitoring options by enable flag iterceptore and jmx
   
   <img src="cluster3.png" width="1000" height="600">
   
   4)Adding components using Designer<br />	
      i) Click on Designer button<br />
     ii) Drag and Drop cluster component from Left menu
    
   <img src="cluster4.png" width="1000" height="600">
   
 
   
   5)Download Cluster<br />
     ii)Select Cluster and click on Download Zip arrow and select Ansible Type<br />
     
   <img src="download.png" width="1000" height="600">

