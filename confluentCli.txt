curl -sL --http1.1 https://cnfl.io/cli | sh -s -- latest
echo $PATH
export PATH=/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/usr/games:/usr/local/games:/snap/bin:./bin:/home/confluent/bin
confluent version
confluent login --save
confluent environment list
confluent environment use env-18m53
ping pkac-k6ky6.us-east4.gcp.confluent.cloud
netstat pkac-k6ky6.us-east4.gcp.confluent.cloud
apt install net-tools
sudo apt install net-tools
netstat pkac-k6ky6.us-east4.gcp.confluent.cloud
nslookup pkac-k6ky6.us-east4.gcp.confluent.cloud
nslookup ppkc-m52y2.us-east4.gcp.confluent.cloud:9092
nslookup pkc-m52y2.us-east4.gcp.confluent.cloud:9092
nslookup pkc-m52y2.us-east4.gcp.confluent.cloud:9092:
ns lookup pkc-m52y2.us-east4.gcp.confluent.cloud:9092
nslookup pkc-m52y2.us-east4.gcp.confluent.cloud:9092
confluent environment use env-18m53
confluent kafka cluster list
confluent kafka cluster use lkc-k8yvrg
ping pkc-m52y2.us-east4.gcp.confluent.cloud:9092
ping pkc-m52y2.us-east4.gcp.confluent.cloud
confluent api-key use NWTXG4VK6WYQZICI --resource lkc-k8yvrg
confluent api-key store NWTXG4VK6WYQZICI vfbp6eSCXo8QSP8I7yKq2Khkdkox77ri8qchQnjSOPBseO2xTbQyzEeJEYdqMuSv --resource lkc-k8yvrg
confluent api-key use NWTXG4VK6WYQZICI --resource lkc-k8yvrg
confluent api-key use HV3JIOBZYOG6XNBK --resource lkc-12g09v
 confluent api-key store HV3JIOBZYOG6XNBK  Q1OUWi1H1Cgup2+dayA9oqFiq9DynNpJdILnODlGU650SzGWJlla1w2ypt4Typ0f --resource lkc-12g09v
confluent api-key use GFERPIML7H6JOW67 --resource lkc-12g09v
  confluent api-key store GFERPIML7H6JOW67  ZcOfAInvYiWOgy4orVrknerYl6jOQbeSynr46/pNNtYe10OGUAR3b1RKfZeOrEMb --resource lkc-12g09v

 confluent api-key store L2HAPU4ITXEVXC6V tyHAB4xCUOQOra8hYsBt8cbGUk6f8XYDVZNkV4IyxZOSuF8aE1cgPLYcOwMqfSO2 --resource lkc-k8yvrg 
confluent api-key create --resource lkc-k8yvrg
confluent api-key create --resource lkc-k8yvrg --service-account sa

confluent api-key create --resource lkc-k8yvrg --service-account  sa-5myqxn
confluent api-key create --resource lkc-k8yvrg --service-account  sa-230knm
confluent api-key create --resource lkc-k8yvrg --service-account  sa-230knm

confluent iam service-account create brspd-boss-sa-confluent-uat --description "Service Account to use by brspd BOSS in uat"
confluent iam service-account create brspd-boss-sa-restproxy-uat --description "Service Account to use by brspd BOSS on rest proxy in uat"
confluent iam service-account create brspd-boss-sa-confluent-admin-uat --description "Service Account to use by brspd BOSS admin in uat "

confluent kafka client-config create java --environment env-18m53 --cluster lkc-k8yvrg --api-key NWTXG4VK6WYQZICI --api-secret vfbp6eSCXo8QSP8I7yKq2Khkdkox77ri8qchQnjSOPBseO2xTbQyzEeJEYdqMuSv

 confluent  kafka topic  consume UAT_BOSS_NPS_ASSIGNODN_RESPONSE --group UAT_BOSS_TEST_CG --from-beginning

confluent api-key create --resource lkc-k8yvrg --service-account sa-9wwy55
confluent api-key create --resource lkc-k8yvrg  --service-account sa-j887zw
confluent api-key create --resource lkc-k8yvrg  --service-account sa-23365y

confluent api-key create --resource lkc-12g09v --service-account sa-kgwkm2

confluent kafka acl create --allow --service-account sa-23365y --operation read --operation write --topic 'UAT_BOSS' --prefix
confluent kafka acl create --allow --service-account sa-23365y --operation read --operation write --consumer-group 'UAT_BOSS' --prefix
confluent kafka acl create --allow --service-account sa-23365y --operation create --consumer-group 'UAT_BOSS' --prefix
confluent kafka acl create --allow --service-account sa-23365y --operation read --operation write --topic 'UAT' --prefix
confluent kafka acl create --allow --service-account sa-23365y --operation read --operation write --topic 'UAT' --prefix


confluent kafka acl create --allow --service-account sa-9wwy55  --operation read --operation write --topic 'UAT_BOSS' --prefix
confluent kafka acl create --allow --service-account sa-9wwy55  --operation read --operation write --consumer-group 'UAT_BOSS' --prefix
confluent kafka acl create --allow --service-account sa-9wwy55  --operation create --consumer-group 'UAT_BOSS' --prefix

confluent kafka acl create --allow --service-account sa-5myqxn  --operation read --operation write --topic 'UAT' --prefix
confluent kafka acl create --allow --service-account sa-5myqxn  --operation read --operation write --consumer-group 'UAT' --prefix
confluent kafka acl create --allow --service-account sa-5myqxn  --operation create --consumer-group 'UAT' --prefix

confluent kafka acl create --allow --service-account sa-kgwkm2  --operation read --operation write --topic 'DEV' --prefix
confluent kafka acl create --allow --service-account sa-kgwkm2  --operation read --operation write --consumer-group 'DEV' --prefix
confluent kafka acl create --allow --service-account sa-kgwkm2  --operation create --consumer-group 'DEV' --prefix
confluent kafka acl create --allow --service-account sa-kgwkm2  --operation read --operation write --topic 'error.' --prefix
confluent kafka acl create --allow --service-account sa-kgwkm2  --operation read --operation write --topic 'Dev' --prefix
confluent kafka acl create --allow --service-account sa-kgwkm2  --operation read --operation write --consumer-group 'Dev' --prefix
confluent kafka acl create --allow --service-account sa-kgwkm2  --operation create --consumer-group 'Dev' --prefix




confluent kafka topic list 
confluent kafka topic create test_topic
confluent kafka topic list 
confluent kafka topic produce test_topic
confluent kafka topic consume test_topic
confluent kafka topic consume test_topic --from-beginning
confluent kafka topic list



 confluent environment list
    7  confluent environment use env-0xkrrq
    8  confluent kafka cluster list
    9  confluent kafka cluster use lkc-o3gdvy

confluent iam service-account create brspd-boss-sa-confluent-prod --description "Service Account to use by brspd BOSS in prod"
confluent iam service-account create brspd-boss-sa-restproxy-prod --description "Service Account to use by brspd BOSS on rest proxy in prod"
confluent iam service-account create brspd-boss-sa-confluent-admin-prod --description "Service Account to use by brspd BOSS admin in prod "
confluent iam service-account create brspd-sa-confluent-prod --description "Service Account to use by brspd in prod"
confluent iam service-account create brspd-digital-boss-confluent-devqa --description "Service Account to use by brspd digital boss in devqa"
confluent iam service-account create brspd-dwh-boss-sa-devqa --description "Service Account to use by brspd dw boss in devqa"
confluent iam service-account create brspd-dwh-cxpxdx-sa-devqa --description "Service Account to use by brspd cxpxdx boss in devqa"

confluent api-key create --resource lkc-o3gdvy --service-account sa-19m376
confluent api-key create --resource lkc-o3gdvy  --service-account sa-7p7gx1
confluent api-key create --resource lkc-o3gdvy  --service-account  sa-3nm1qm
confluent api-key create --resource lkc-o3gdvy  --service-account  sa-ny9qd3
confluent api-key create --resource lkc-o3gdvy --service-account sa-nyjrjv
confluent api-key create --resource lkc-12g09v --service-account sa-x7mzdz
confluent api-key create --resource lkc-12g09v --service-account  sa-vn6od5
confluent api-key create --resource lkc-12g09v --service-account  sa-jv9dp2

lkc-12g09v

confluent kafka acl create --allow --service-account sa-x7mzdz  --operation read --operation write --topic 'DEV_BOSS_DIGITAL' --prefix
confluent kafka acl create --allow --service-account sa-x7mzdz  --operation read --operation write --consumer-group 'DEV_BOSS_DIGITAL' --prefix
confluent kafka acl create --allow --service-account sa-x7mzdz  --operation create --consumer-group 'DEV_BOSS_DIGITAL' --prefix

confluent kafka acl create --allow --service-account sa-vn6od5  --operation read --operation write --topic 'DEV' --prefix
confluent kafka acl create --allow --service-account sa-vn6od5  --operation read --operation write --consumer-group 'DEV_DW' --prefix
confluent kafka acl create --allow --service-account sa-vn6od5  --operation create --consumer-group 'DEV_DW' --prefix
confluent kafka acl create --allow --service-account sa-vn6od5  --operation read --operation write --topic 'Dev' --prefix

confluent kafka acl create --allow --service-account sa-jv9dp2  --operation read --operation write --topic 'DEV' --prefix
confluent kafka acl create --allow --service-account sa-jv9dp2  --operation read --operation write --consumer-group 'DEV_CXPXDX' --prefix
confluent kafka acl create --allow --service-account sa-jv9dp2  --operation create --consumer-group 'DEV_CXPXDX' --prefix
confluent kafka acl create --allow --service-account sa-jv9dp2  --operation read --operation write --topic 'Dev' --prefix



confluent kafka acl create --allow --service-account sa-ny9qd3  --operation read --operation write --topic 'PROD' --prefix
confluent kafka acl create --allow --service-account sa-ny9qd3  --operation read --operation write --consumer-group 'PROD' --prefix
confluent kafka acl create --allow --service-account sa-ny9qd3  --operation create --consumer-group 'PROD' --prefix



confluent kafka acl create --allow --service-account sa-19m376  --operation read --operation write --topic 'PROD' --prefix
confluent kafka acl create --allow --service-account sa-19m376  --operation read --operation write --topic 'PROD_BOSS' --prefix
confluent kafka acl create --allow --service-account sa-19m376  --operation read --operation write --consumer-group 'PROD_BOSS' --prefix
confluent kafka acl create --allow --service-account sa-19m376  --operation create --consumer-group 'PROD_BOSS' --prefix


confluent iam service-account create brspd-dispatch-sa-confluent-prod --description "Service Account to use by brspd dispatch in prod"
confluent kafka acl create --allow --service-account sa-nyjrjv --operation read --operation write --topic 'PROD_DISPATCH' --prefix

confluent kafka acl create --allow --service-account sa-19m376  --operation read --operation write --consumer-group 'PROD_DISPATCH' --prefix
confluent kafka acl create --allow --service-account sa-19m376  --operation read --operation read --consumer-group 'PROD_DISPATCH' --prefix
confluent kafka acl create --allow --service-account sa-nyjrjv  --operation read --operation write --consumer-group 'PROD_DISPATCH' --prefix
confluent kafka acl create --allow --service-account sa-nyjrjv  --operation read --operation read --consumer-group 'PROD_DISPATCH' --prefix

confluent kafka acl create --allow --service-account sa-19m376  --operation read --operation write --topic 'error.' --prefix
confluent kafka acl create --allow --service-account sa-23365y  --operation read --operation write --topic 'error.' --prefix
confluent kafka acl create --allow --service-account sa-j887zw  --operation read --operation write --topic 'error.' --prefix

confluent kafka acl delete --allow --service-account sa-19m376  --operation read --operation write --topic 'error.PROD_BOSS' --prefix
confluent kafka acl create --allow --service-account sa-19m376  --operation read --operation write --topic 'PROD' --prefix
confluent kafka acl delete --allow --service-account sa-19m376  --operation read --operation write --topic 'PROD_BOSS' --prefix


confluent kafka acl create --allow --service-account sa-z3nz53  --operation read --operation write --topic 'QA_DISPATCH' --prefix
confluent kafka acl create --allow --service-account sa-z3nz53  --operation read --operation read --topic 'QA_DISPATCH' --prefix
confluent kafka acl create --allow --service-account sa-z3nz53  --operation read --operation write --consumer-group 'QA_DISPATCH' --prefix
confluent kafka acl create --allow --service-account sa-z3nz53  --operation read --operation read --consumer-group 'QA_DISPATCH' --prefix

confluent kafka acl create --allow --service-account sa-j887zw  --operation read --operation write --operation create --topic 'UAT' --prefix 
confluent kafka acl create --allow --service-account sa-j887zw  --operation read --operation write --operation create --topic 'error.' --prefix 
confluent kafka acl create --allow --service-account sa-j887zw  --operation read --operation write --operation create --consumer-group 'UAT' --prefix 



confluent kafka acl create --allow --service-account sa-z3nz53  --operation create --operation describe --cluster-scope lkc-12g09v
confluent kafka acl create --allow --service-account sa-z3nz53  --operation read --operation describe --operation write --topic '_confluent' --prefix 




------------UAT----------------
confluent login --save
confluent environment use env-18m53
confluent kafka cluster list
confluent kafka cluster use lkc-k8yvrg
confluent api-key store NWTXG4VK6WYQZICI vfbp6eSCXo8QSP8I7yKq2Khkdkox77ri8qchQnjSOPBseO2xTbQyzEeJEYdqMuSv --resource lkc-k8yvrg
confluent api-key use NWTXG4VK6WYQZICI --resource lkc-k8yvrg

confluent kafka topic create topic_name


curl --request GET --url 'https://pkc-m52y2.us-east4.gcp.confluent.cloud:443/kafka/v3/clusters/lkc-k8yvrg/topics' --header 'Authorization: Basic TldUWEc0Vks2V1lRWklDSTp2ZmJwNmVTQ1hvOFFTUDhJN3lLcTJLaGtka294NzdyaThxY2hRbmpTT1BCc2VPMnhUYlF5ekVlSkVZZHFNdVN2'
----------PROD--------------

confluent login --save
confluent environment use env-0xkrrq
confluent kafka cluster list
confluent kafka cluster use  lkc-o3gdvy
confluent api-key store D66PUV54WHQK236J /YSOtCG0cSj6iyOoR0lQdY+ncsl2+2P7OI17Uj30HOakREM6L8JyXqPulcYsIkTX --resource lkc-o3gdvy
confluent api-key use D66PUV54WHQK236J --resource lkc-o3gdvy


----------DEVQA--------------
export PATH=$PATH:/home/confluent/bin
confluent login --save
confluent environment use env-gq8vnn
confluent kafka cluster list
confluent kafka cluster use  lkc-12g09v
confluent api-key store 5LGMGEROVGIWM2GQ pfajAaWb39aeExz6P6onBiZZCD2cA2ZsTpwHetBBMbA4swM2tkO/rHInLyePOAuW --resource lkc-12g09v
confluent api-key use 5LGMGEROVGIWM2GQ --resource lkc-12g09v


 confluent kafka topic consume DEV_AMS_BOSS_CM_REPLY -b

confluent ksql cluster create GE4-KSQL-DEVQA-01 --api-key 5LGMGEROVGIWM2GQ --secret pfajAaWb39aeExz6P6onBiZZCD2cA2ZsTpwHetBBMbA4swM2tkO/rHInLyePOAuW

-----------audit logs-----------
confluent login --save
confluent audit-log describe
confluent environment use env-mv66x7
confluent kafka cluster use lkc-k8zj66
confluent api-key list --resource lkc-k8zj66
confluent api-key create --service-account sa-096r89 --resource lkc-k8zj66
confluent api-key use IZEXQ45HGBR2LXQA> --resource lkc-k8zj66
confluent api-key use IZEXQ45HGBR2LXQA --resource lkc-k8zj66
confluent kafka topic consume -b confluent-audit-log-events

----add service account---

confluent iam service-account create brspd-boss-sa-confluent-uat --description "Service Account to use by brspd BOSS in uat"


--api create ---
confluent api-key create --resource lkc-k8yvrg --service-account  sa-5myqxn


--acls create ----
confluent kafka acl create --allow --service-account sa-23365y --operation read --operation write --topic 'UAT_BOSS' --prefix
confluent kafka acl create --allow --service-account sa-23365y --operation read --operation write --consumer-group 'UAT_BOSS' --prefix
confluent kafka acl create --allow --service-account sa-23365y --operation create --consumer-group 'UAT_BOSS' --prefix

confluent kafka acl delete  --allow --service-account sa-23365y --operation read --operation write --topic 'UAT_BOSS' --prefix

confluent kafka acl delete  --allow --service-account sa-23365y --operation read --operation write --topic 'UAT_DISPATCH' --prefix

confluent kafka acl delete  --allow --service-account sa-23365y --operation read --operation write --topic 'error. error.UAT_BOSS' --prefix

confluent kafka acl delete  --allow --service-account sa-23365y --operation read --operation write --topic 'UAT_DISPATCH' --prefix

confluent kafka acl create --allow --service-account sa-z3nz53 --operation read --operation write --operation create --topic 'DEV' --prefix
confluent kafka acl create --allow --service-account sa-z3nz53 --operation read --operation write --operation create --topic 'QA' --prefix
confluent kafka acl create --allow --service-account sa-23365y --operation read --operation write --operation create --consumer-group 'DEV' --prefix
confluent kafka acl create --allow --service-account sa-23365y --operation read --operation write --operation create --consumer-group 'QA' --prefix
confluent kafka acl create --allow --service-account sa-kgwkm2 --operation read --operation write --operation create --consumer-group 'DEV' --prefix
confluent kafka acl create --allow --service-account sa-kgwkm2 --operation read --operation write --operation create --consumer-group 'QA' --prefix
confluent kafka acl create --allow --service-account sa-kgwkm2 --operation read --operation write --operation create --consumer-group 'error.' --prefix
confluent kafka acl create --allow --service-account sa-kgwkm2 --operation read --operation write --operation create --topic 'DEV' --prefix
confluent kafka acl create --allow --service-account sa-kgwkm2 --operation read --operation write --operation create --topic 'QA' --prefix
confluent kafka acl create --allow --service-account sa-kgwkm2 --operation read --operation write --operation create --topic 'error.' --prefix

confluent kafka acl delete  --allow --service-account sa-z3nz53 --operation read --operation write --operation create --topic 'QA_DISPATCH' --prefix
confluent kafka acl delete  --allow --service-account sa-z3nz53 --operation read --operation write --operation create --topic 'QA' --prefix
confluent kafka acl delete --allow --service-account sa-23365y --operation read --operation write --operation create --consumer-group 'QA_DISPATCH' --prefix
confluent kafka acl delete  --allow --service-account sa-23365y --operation read --operation write --operation create --consumer-group 'QA' --prefix


---topics create ---

confluent kafka topic create topic_name


----look the data in the topic---

confluent kafka topic consume topic_name -b --print-key true --property print.timestamp true


confluent api-key list


./kafka-consumer-groups.sh --bootstrap-server pkc-m52y2.us-east4.gcp.confluent.cloud:9092 --group UAT_BOSS_NPS --command-config conf
ig.properties --describe |grep UAT_BOSS_OF_ASSIGNODN_REQUEST


 ./kafka-consumer-groups.sh --bootstrap-server pkc-m52y2.us-east4.gcp.confluent.cloud:9092 --group UAT_BOSS_NPS --command-config config.properties --describe |grep  UAT_BOSS_SN_SUSPEND_RESTORE_REQ

 ./kafka-consumer-groups.sh --bootstrap-server pkc-m52y2.us-east4.gcp.confluent.cloud:9092 --group UAT_BOSS_NPS --command-config config.properties --reset-offsets --shift-by 1 --topic UAT_BOSS_SN_SUSPEND_RESTORE_REQ:1 --execute

./kafka-console-consumer.sh --bootstrap-server pkc-m52y2.us-east4.gcp.confluent.cloud:9092  --consumer.config config.properties --to
pic UAT_BOSS_OF_ASSIGNODN_REQUEST --from-beginning --property print.offset=true --property print.partition=true | grep NJ2100001149

./kafka-console-consumer.sh --bootstrap-server pkc-m52y2.us-east4.gcp.confluent.cloud:9092  --consumer.config config.properties --topic UAT_BOSS_CUSTOMER360 --from-beginning --property print.offset=true --property print.partition=true | grep etekeswick@getnada.com


/kafka-consumer-groups.sh --bootstrap-server pkc-m52y2.us-east4.gcp.confluent.cloud:9092 --group UAT_BOSS_NPS --command-config config.properties --reset-offsets --shift-by 883 --topic UAT_BOSS_OF_ASSIGNODN_REQUEST --execute

./kafka-console-consumer.sh --bootstrap-server pkc-m52y2.us-east4.gcp.confluent.cloud:9092  --consumer.config config.properties --topic UAT_BOSS_CUSTOMER360 --from-beginning --property print.offset=true --property print.partition=true | grep etekeswick@getnada.com

/home/ashok_pyaram/bin/kafka/bin

pkc-epwny.eastus.azure.confluent.cloud:9092
./kafka-console-consumer.sh --bootstrap-server pkc-epwny.eastus.azure.confluent.cloud:9092  --consumer.config config.properties --topic UAT_BOSS_CUSTOMER360 --from-beginning --property print.offset=true --property print.partition=true | grep etekeswick@getnada.com



confluent kafka topic create DEV_BOSS_OF_ADDRESS_INFO_REQ
confluent kafka topic create Dev_OF_AssignODN_Request
confluent kafka topic create DEV_OF_COMPLETE_REQ
confluent kafka topic create DEV_OF_SERVICE_INFO_REQ
confluent kafka topic create DEV_OF_ORDER_COMPLETION_REQ
confluent kafka topic create DEV_SN_SUSPEND_RESTORE_REQ
confluent kafka topic create DEV_OF_UNASSIGNODN_REQ
confluent kafka topic create DEV_OF_UPDATE_SN_REQ
confluent kafka topic create DEV_BOSS_OF_DROP_STATUS_UPD_REQ
confluent kafka topic create Dev_PreProvisionComplete
confluent kafka topic create Dev_NPS_AssignODN_Response
confluent kafka topic create DEV_NPS_SUSPEND_RESTORE_RES
confluent kafka topic create DEV_NPS_UNASSIGNODN_RES




bootstrap.servers=pkc-m52y2.us-east4.gcp.confluent.cloud:9092=
ssl.endpoint.identification.algorithm=https
security.protocol=SASL_SSL
sasl.mechanism=PLAIN
sasl.jaas.config=org.apache.kafka.common.security.plain.PlainLoginModule required username="L2HAPU4ITXEVXC6V" password="tyHAB4xCUOQOra8hYsBt8cbGUk6f8XYDVZNkV4IyxZOSuF8aE1
cgPLYcOwMqfSO2";


bootstrap.servers=pkc-08yv9.us-east4.gcp.confluent.cloud:9092
ssl.endpoint.identification.algorithm=https
security.protocol=SASL_SSL
sasl.mechanism=PLAIN
sasl.jaas.config=org.apache.kafka.common.security.plain.PlainLoginModule required username="D66PUV54WHQK236J" password="/YSOtCG0cSj6iyOoR0lQdY+ncsl2+2P7OI17Uj30HOakREM6L8JyXqPulcYsIkTX";


bootstrap.servers=pkc-9dd5v.us-east4.gcp.confluent.cloud:9092
ssl.endpoint.identification.algorithm=https
security.protocol=SASL_SSL
sasl.mechanism=PLAIN
sasl.jaas.config=org.apache.kafka.common.security.plain.PlainLoginModule required username="5LGMGEROVGIWM2GQ" password="pfajAaWb39aeExz6P6onBiZZCD2cA2ZsTpwHetBBMbA4swM2tkO/rHInLyePOAuW";


wget https://downloads.apache.org/kafka/3.5.1/kafka_2.13-3.5.1.tgz


./kafka-consumer-groups.sh --bootstrap-server pkc-9dd5v.us-east4.gcp.confluent.cloud:9092  --command-config config.properties


./kafka-consumer-groups.sh --bootstrap-server pkc-08yv9.us-east4.gcp.confluent.cloud:9092 --command-config config.properties --list
