# elastic-messages-filebeat
A demonstration on how messages logs can be shipped to Elastic through filebeat

Filebeat can be started (assuming it is installed) using this command:
filebeat -e -v -c $PWD/filebeat.yml

messages.json serves as an example json file which is expected to be written by the application.
