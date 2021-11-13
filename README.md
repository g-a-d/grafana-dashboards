# Grafana Dashboards for CloudQuery

[CloudQuery](https://github.com/cloudquery/cloudquery) is an open-source cloud asset management powered by SQL. Backed by PostgreSQL.

You can connect your PostgreSQL database with all your assets and use the following dashboards for visualization, monitoring and alerting (no more going through aws console region list to find where is your ec2 located).

## What's inside?

Currently we have dashboards for aws(more is coming...).

**Naming Convention** - Dashboards file name correlate to CloudQuery resources.

### AWS

All AWS dashboards are coming with account_ids and regions filter.

Located in [./dashboards/aws](./dashboards/aws)

### Example

Here is an example of AWS RDS Grafana Dashboard

![AWS RDS CloudQUery Grafana Dashboard](images/aws_rds_grafana_dashboard.png)

