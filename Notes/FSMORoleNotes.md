# FSMO Role Notes
Task Description: What's FSMO?
What are the different roles? Which are particularly important to keep track of?
Write up a little explanation that would be easy for someone new to the concepts could follow.

- FSMO stands for Flexible Single Master Operation
- Active Directory has five FSMO roles
- Two FSMO roles are enterprise-level (one per forest) and three are domain-level (one per domain)
- The enterprise-level roles are called the Schema Master and the Domain Naming Master
- The domain-level FSMO roles are called the Primary Domain Controller Emulator, the Relative Identifier Master, and the Infrastructure Master
- RID Master is responsible for allocating active and standby RID pools to domain controllers
- RID pools are used to generate a new objects SID
- Infrastructure Master is responsible for managing phantom objects
- PDCE is responsible for backward compatibility, time synchronization, password update processing, group policy updates, and distributed file system
- Domain Naming Master is responsible for adding new domains and application partitions to the forest
- The Schema Master role owner is the only DC in a forest that contains a writable schema partition