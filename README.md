# What is this?

This is a project that automatically collects and creates artifacts to ease in air-gapped transfer of the catest conainer images from the internet.

It runs actions as needed/manually, on GIT Commit Push, or automatically on Mondays at 00:00 

In this case, it:

- collects container images
- creates a set of ISO Files for release on Sharepoint

## Images include:

### Disk 1 - _Base-Images-\<DATE>.iso_

- UBI 8 & 9 latest images from DSO.mil IronBank
- JDK 8, 11, & 17 latest images from DSO.mil IronBank
- nginx latest images from DSO.mil IronBank

### Disk 2 - _Pipeline-Images-\<DATE>.iso_

- Maven latest images from DSO.mil IronBank
- Skopeo latest images from DSO.mil IronBank
- Kaniko latest images from DSO.mil IronBank
- Redis latest images from DSO.mil IronBank
- RabbitMQ latest images from DSO.mil IronBank
- Sonatype Nexus latest images from DSO.mil IronBank
- Checkmarx CXCLI latest images from DSO.mil IronBank
- Keysight Eggplant Fusion Engine latest images from DSO.mil IronBank

### Disk 3 - _Service-Images-\<DATE>.iso_

- Redis Latest images from DSO.mil Ironbank
- RabbitMQ Latest images from DSO.mil Ironbank
- Nexus Latest images from DSO.mil Ironbank

### Disk 4 - _Support-Images-\<DATE>.iso_

- PlantUML Software for UML Diagramming

### Disk 5 - _Atlassian-Images-\<DATE>.iso_

- Atlassian Jira latest images from DSO.mil IronBank
- Atlassian Confluence latest images from DSO.mil IronBank
- Atlassian Bitbucket latest images from DSO.mil IronBank
- Atlassian Support latest images from DSO.mil IronBank