# Kafka.Cluster

## 1)Create SASL_PLAINTEXT Cluster
   i)Add host Of Component <br />
   ii)Select Confluent Clod Cluster Type<br />
  iii)We can select version from kafka version dropdown<br />

   <img src="cluster1.png" width="1000" height="600">
   
   2)Specify cluster Security<br />
    i)We can configure rest end point security by enabling flag true<br />
   ii)We can configure Zookeeper security<br />
  iii)We Can configure RBAC by enable true flag <br />
      if RBAC enable rbac listener required<br />
   iv)We can provide different type of security mechanism using listener <br />
      i.e want to create SASL_PLAINTEXT configuration<br />
      select SSL PLAINTEXT from dropdown and SASL PLAIN <br/>
    v)We can configure multiple type of configuration like SASL_PLAINTEXT,SASL_GGSAPI,SASL_SCRAM,SASL_OUTHBEARER<br/>
      Ans SSL configuration SSL_PLAINTEXT,SSL_GGSAPI,SSL_SCRAM,SSL_OUTHBEARER<br/>
    vi)We Can configure Multiple listener to cluster <br/>
    vii)For creating SASL_PLAINTEXT cluster select SSL PLAINTEXT from dropdown and PLAIN from SASL dropdown
    
   
   <img src="cluster2.png" width="1000" height="600">
   
   
   3)Specify cluster Monitoring<br />	
     Here we can configure Monitoring options by enable flag iterceptore and jmx
   
   <img src="cluster3.png" width="1000" height="600">
   
   4)Adding components using Designer<br />	
      i) Click on Designer button<br />
     ii) Drag and Drop cluster component from Left menu
    
   <img src="cluster4.png" width="1000" height="600">
   
   4)View Cluster Detail<br />
    i) Select Cluster Below Tab you can find components <br />
   ii) Click On components to view property configuration, right side you can check properties <br />
    ii) To view Docker compose configuration. Click on Docker Compose Tab
    
   <img src="props.png" width="1000" height="600">
   
   <img src="docker.png" width="1000" height="600">
   
   5)Download Cluster<br />
     i)We can download five type of configuration<br />
      Properties Configuration,Operatore Configuration,Docker ,Properties,Configuration,Manifest Configuration<br />
     ii)Select Cluster and click on Download Zip arrow and select Type<br />
     
   <img src="download.png" width="1000" height="600">
   
 5)Download Sample Code<br />
     i)We can download three  of sample code it contain kafka consumer producer <br />
      We provide example in three languages Java,C#,Python<br />
    ii)Select Cluster and click on Download Code arrow and select Type<br />

     
   <img src="code.png" width="1000" height="600">
