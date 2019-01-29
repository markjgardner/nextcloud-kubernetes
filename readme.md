# Nextcloud Kubernetes with Nginx

This configuration show how to setup nextcloud-fpm with nginx.

## Infrastructure overview

Container orchestration will be handled by Azure Kubernetes service.
The database is provided by an Azure Database for MariaDB Server.
Persistent Storage is provided by an Azure Files share within an Azure Storage Account.  

# Database
