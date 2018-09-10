% ELK(shell) Um Pages | Um Pages
% 
% August 26, 2018
# NAME
elk --

# SYNOPSIS


# DESCRIPTION
docker run -p 5601:5601 -p 9200:9200  -p 5044:5044 \
    -v elk-data:/var/lib/elasticsearch --name elk sebp/elk
: Start a set of Elasticsearch / LogStash / Kibana instances 

# OPTIONS

