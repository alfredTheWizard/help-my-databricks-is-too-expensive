# Help my Azure Databricks is too expensive! Some Tips and Tricks
Some documentation and links to aid you in decreasing your Azure Databricks cost

## 1.	Monitoring, Budgets & Alerts

### Implement (Workspace) Budgets in Databricks Account Console
https://learn.microsoft.com/en-us/azure/databricks/admin/account-settings/budgets

### Implement Budgets & Quotas for Serverless compute in Databricks Workspaces
-	https://www.databricks.com/blog/attribute-serverless-costs-departments-and-users-budget-policies
-	https://learn.microsoft.com/en-us/azure/databricks/admin/usage/budget-policies
-	https://learn.microsoft.com/en-us/azure/databricks/admin/account-settings/serverless-quotas

### Stop (creation) of resources after budget alert in Azure Portal
https://learn.microsoft.com/en-us/answers/questions/1669420/enforcing-cost-limit-per-subscription-or-tenant-to

### Monitor Databricks DBU usage with Usage Dashboard
https://docs.databricks.com/en/admin/account-settings/usage.htmlx

## 2.	Azure Databricks Pricing
-	https://www.databricks.com/product/pricing
-	https://azure.microsoft.com/en-us/pricing/details/databricks/

## 3.	Cluster Optimization
### Cluster Configuration Considerations
-	https://docs.databricks.com/en/compute/photon.html
-	https://azure.microsoft.com/en-us/products/virtual-machines/spot#spot-virtual-machines
-	https://www.databricks.com/blog/2021/05/25/leverage-unused-compute-capacity-for-data-ai-with-azure-spot-instances-and-azure-databricks.html

###Configure compute for jobs
-	https://docs.databricks.com/en/jobs/compute.html

# 4.	Prepay for Resources
### Databricks Reserved Capacity
https://learn.microsoft.com/en-us/azure/cost-management-billing/reservations/prepay-databricks-reserved-capacity

### Prepay VM’s
-	https://learn.microsoft.com/en-us/azure/virtual-machines/prepay-reserved-vm-instances
-	https://learn.microsoft.com/en-us/azure/cost-management-billing/savings-plan/savings-plan-compute-overview
-	https://learn.microsoft.com/en-us/azure/cost-management-billing/savings-plan/decide-between-savings-plan-reservation

## 5.	Streaming on Databricks
### Cost savings for Streaming
https://www.databricks.com/blog/2017/05/22/running-streaming-jobs-day-10x-cost-savings.html

### Trigger Options for Jobs
-	https://docs.databricks.com/en/jobs/triggers.html
-	https://docs.databricks.com/en/jobs/file-arrival-triggers.html

### Auto Loader Considerations
-	https://docs.databricks.com/en/ingestion/cloud-object-storage/auto-loader/file-detection-modes.html
-	https://docs.databricks.com/en/ingestion/cloud-object-storage/auto-loader/production.html
-	https://learn.microsoft.com/en-us/azure/databricks/ingestion/cloud-object-storage/auto-loader/options
-	https://learn.microsoft.com/en-us/azure/databricks/ingestion/cloud-object-storage/auto-loader/file-notification-mode
-	https://docs.databricks.com/en/ingestion/cloud-object-storage/auto-loader/unity-catalog.html

## 6.	Limit users (to save costs)
-	https://www.databricks.com/blog/best-practices-cost-management-databricks
-	https://learn.microsoft.com/en-gb/azure/databricks/admin/clusters/policies
-	https://learn.microsoft.com/en-us/azure/databricks/admin/clusters/policy-families

## 7.	Workspace Tiers
https://www.databricks.com/product/pricing/platform-addons

