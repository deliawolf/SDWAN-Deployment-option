# Flexible Controller Deployment Options

The Cisco SD-WAN architecture provides maximum flexibility regarding the deployment of the controllers.

You can deploy the three controller types (vManage, vSmart, and vBond) according to the following models:

1. In a cloud managed by the Cisco CloudOps team: This is the recommended model, and controllers can be deployed in Amazon Web Services (AWS) or Microsoft Azure by the Cisco CloudOps team. Single or multiple zones are available for deployment. Most customers opt for Cisco cloud-hosted controllers due to the ease of deployment and flexibility in scaling. Cisco provisions the controllers with certificates and meeting requirements for scale and redundancy. Cisco is responsible for backups, snapshots, and disaster recovery. The customer is given access to Cisco vManage to create configuration templates and control and data policies for their devices. When you choose a cloud-based subscription for your Cisco SD-WAN controllers, Cisco deploys the Cisco SD-WAN controllers—specifically, Cisco vManage, Cisco vBond Orchestrator, and Cisco vSmart Controller—on the public cloud. Cisco then provides you with administrator access. By default, a single Cisco vManage, Cisco vBond Orchestrator, and Cisco vSmart Controller are deployed in the primary cloud region, and an extra Cisco vBond Orchestrator and Cisco vSmart Controller are deployed in the secondary or backup region.

2. In a managed service provider (MSP) or partner-hosted cloud: This is privately cloud-hosted or can be publicly cloud-hosted and deployed in AWS or Azure. The MSP or partner is typically responsible for provisioning the controllers and responsible for backups and disaster recovery.

3. On-premises in a private cloud or data center that is owned by an organization: The customer is typically responsible for provisioning the controllers and for backups and disaster recovery. Some customers, such as financial institutions or government-based entities, may choose to run on-premises deployments mainly for security and compliance reasons.

