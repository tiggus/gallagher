Security is provied with WAF, application gateway, peering and DDOS protection - we could add intrusion detection etc

The app service can read write to blob (managed identity auth)

Data transforms via data factory

SQL connected do data factory and can be used by other services (app service etc)

Hosted on Azure, IAC pipelines, App service UI, Blob, KV and SQL all used

Scalable via app service scaling - sql can be scaled as needed / different dbs

Performance is covered by scaling app service

Managed identity used for app service

no public access

Dev and prod app service envs configured and can promote etc, dev and prod branches in IAC

All roles / permissions least privs

Everything monitored with Azure monitor, App insights and Log Analytics

Pipes use Keyvault 
