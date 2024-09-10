# Domain Persistence and Dominance

- Abuse Kerberos functionality to persist with DA privileges. Forge tickets to execute attacks like Golden ticket and Silver ticket to persist.
- Subvert the authentication on the domain level with Skeleton key and custom SSP.
- Abuse the DC safe mode Administrator for persistence.
- Abuse the protection mechanism like AdminSDHolder for persistence.
- Abuse minimal rights required for attacks like DCSync by modifying ACLs of domain objects.
- Learn to modify the host security descriptors of the domain controller to persist and execute commands without needing DA privileges.
