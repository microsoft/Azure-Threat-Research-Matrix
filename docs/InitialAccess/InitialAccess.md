# Initial Access

The adversary is attempting to gain access to an Azure Resource or Azure AD.

|ID                        |                         |Name                                                                          |Description                                       |
|--------------------------|-------------------------------|------------------------------------------------------------------------------|--------------------------------------------------|
|[AZT201](AZT201/AZT201.md)   |                               | Valid Credentials                                                       |Adversaries may login to AzureAD using valid credentials.|
|                          |[.001](AZT201/AZT201-1.md)     |User Account                                                                |By obtaining valid user credentials, an adversary may login to AzureAD via command line or through the Azure Portal. |
|                          |[.002](AZT201/AZT201-2.md)     |Service Principal                                              				|By obtaining a valid secret or certificate, an adversary may login to AzureAD via command line.|
|[AZT202](AZT202/AZT202.md)   |                               | Password Spraying                                                       |An adversary may potentially gain access to AzureAD by guessing a common password for multiple users.|
|[AZT203](AZT203/AZT203.md)   |                               | Malicious Application Consent                                           |An adversary may lure a victim into giving their access to a malicious application registered in AzureAD.|
