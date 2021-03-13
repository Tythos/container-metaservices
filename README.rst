Container Metaservices
======================

Basic batch of metaservices (that is, services that help you monitor and manage
other services). Startup is relatively simple:

1. Spin up the compose suite: `> docker-compose up -d`

2. Browse to "localhost:3000" and log in to the dashboard (by default,
   "admin/admin")

3. Add the "Prometheus" data source, using the URL "http://prometheus:9090"

4. Import dashboard #179 and point it to your Prometheus data source
