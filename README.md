# Net.Core.Elastic.Logstash.Kibana

It's a simple .net core 5 ASP.Net Web Application that log into ElasticSearch. It's really base on this [post](https://www.humankode.com/asp-net-core/logging-with-elasticsearch-kibana-asp-net-core-and-docker)


You should start ElasticSearch on port 9200 (dockerized\local instal) and then run this application to log into ElasticSearch.

## DO NOT Forget
- Config ElasticSearch username and password.
- Config ModifyConnectionSettings property of ElasticsearchSinkOptions on Program.cs file of .net project.
- Create Index pattern in Kibana to view web application log

You can use [this repo](https://github.com/tarafdarmansour/docker-elk) to start ELK(Elasticsearch-Logstash-Kibana) stack.
