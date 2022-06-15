# Monitoring_and_alerts

![aws_disgram.png](/aws_diargam.png)
<br></br>
We can monitor all sorts of metrics:
- error logs
- budgeting
- uptime - access time - response time
- security breaches
- system test/health
- instance's health
- CPU utilisation %
- Memory utilisation %

## 4 Golden Signals

Latency (Rquest Service Time)

Traffic (User demand)

Errors (Rate of failed requests)

Saturation (Overall capacity of the system)

## AWS Monitoring

Three monitoring services in AWS
- Cloudwatch - Monitor AWS service
- SNS - Simple notification
- SQS - Simple queue service

CloudWatch enables you to monitor your complete stack (applications, infrastructure, and services) and use alarms, logs, and events data to take automated actions and reduce mean time to resolution (MTTR). This frees up important resources and allows you to focus on building applications and business value.

## Create SNS notifications on AWS
To receive email notifications, you will need to create an alarm in Cloudwatch and subscribe to it using your email.

# Autoscaling and load balancing 
![lb.png](/lb.png)
