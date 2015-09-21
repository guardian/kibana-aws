# kibana-aws

A simple Cloudformation template to create a standalone Kibana service
in AWS.

Google auth is used to secure the service. As such, you'll need to
create a Google Cloud project with access to the Google+ API, and to
generate access credentials from this.

Note, it is assumed you are running an existing Elasticsearch cluster
with data on it to point Kibana at.

If you want a template to create a fully-fledged 'ELK' stack
(Elasticsearch with Logstash and Kibana), use https://github.com/guardian/elk-stack.
