---
sidebar_position: 6
title: Performance Data
---
## Performance Data
 
 Beyond providing monitoring of the status and the availabilty/reliability of services, the ARGO Monitoring Service is able to enrich the monitoring experience by providing insights on the performance of the services  on network connection time response.  This insight can be extended also on the performance of the service on CPU load, memory, processes and disk usage, as well as any other category signifying service performance. 

This can be achieved by the ARGO Monitoring service by using its analytics engine to analyze the actual data that accompany the stream of the collected Metric Data, The actual data include additional information about the service behaviour and by their analyzation, the service can collect the time series values of the performance category. For example , ARGO Monitoring services collect the value of the connection time response, for every timestamp it is reported. 

The ARGO Monitoring Service, exploits the advantages of Influx Database, as a time series database, by storing the performance data on it.  Grafana is used to provide observability and data visualization, on the stored information, in order for the Argo Monitoring Service UI to be able to present the performance data. A mechanism is implemented in Grafana, to sort the performance data results by group, service in the Grafana Dashboard, as presented: 


<iframe width="85%" height="500px" src="https://timeseriesdb.devel.argo.grnet.gr:3000/d/ef673db3-c773-4211-8ff1-ffe1dbd4e9b8/performance?orgId=1&theme=light&kiosk=&from=1701912314651&to=1701955514651&viewPanel=1">

</iframe>

#### Example

Performance Data for EOSC-Helpdesk service

![](/img/reports/eosc-helpdesk.png) 






