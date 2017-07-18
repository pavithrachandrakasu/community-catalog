# Logstash
## Install
    docker pull docker.elastic.co/logstash/logstash:5.5.0
## Configure files
Logstash has two config files:
1. *pepline config files* which define the Logtash processing pipes
2. *settnigs files* control Logstash itself
## Pipeline config
Structure of the Config looks like:
```
# This is a comment. You should use comments to describe
# parts of your configuration.
input {
  ...
}

filter {
  ...
}

output {
  ...
}
```

