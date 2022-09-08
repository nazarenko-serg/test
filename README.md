How to add new topics:
* Open https://github.com/dapperlabs/dapper-infrastructure/tree/main/terraform/<Select_env>/confluent.tf
* Find section #Dapper topics list
* Add > "topicname" = local.dapper_topic_config
* * Where **dapper_topic_config** - config with default values
