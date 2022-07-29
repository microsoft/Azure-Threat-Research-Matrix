# Exfiltration

The adversary is trying to steal data. Exfiltration in Azure consists of using techniques to lift resource data from specific resources. This can be done by generating SAS URIs for unauthenticated & persistent downloads, or can be done by directly exfiltrating the data from the resource itself.

|ID                        |                         |Name                                                                          |Description                                       |
|--------------------------|-------------------------------|------------------------------------------------------------------------------|--------------------------------------------------|
|[AZT701](AZT701/AZT701.md)   |                               |SAS URI Generation                                                            |By generating an SAS URI for a resource, an adversary may extract the contents of that resource without authentication at any time.|
|                          |[.001](AZT701/AZT701-1.md)     |VM Disk SAS URI                                                               |An adversary may create an SAS URI to download the disk attached to a virtual machine.|
|                          |[.002](AZT701/AZT701-2.md)     |Storage Account File Share SAS                                                |By generating a Shared Access Signature (SAS) URI, an adversary can access a container in a Storage Account at any time.|
|[AZT702](AZT702/AZT702-1.md)|                               |File Share Mounting                                                           |An adversary may attach an Azure resource as a file share|
|                          |[.001](AZT702/AZT702-1.md)     |Storage Account File Share NFS/SMB Mount                                      |An adversary can generate a connection string to mount an Azure Storage Account File Share as an NFS or SMB share to their local machine.|
|[AZT703](AZT703/AZT703-1.md)|                               |Replication                                                           |An adversary may exfiltrate data by replicating it.|
|                          |[.001](AZT703/AZT703-1.md)     |Storage Account Replication                                     |By setting up cross-tenant replication, an adversary may set up replication from one tenant's storage account to an extrenal tenant's storage account.|
