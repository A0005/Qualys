Vulnerability Management Dectection and Response Life Cycle:

1 - Asset Management
    
    Here you will learn to identify and manage all assets throughout your
    business or enterprise architecture to protect your assets. This step is 
    also a part of the CIS Critical Contorls and NIST Cybersecurity Framework.
    
2 - Vulnerability Management:

    Here, you will be able to analyze the vulnerabilities findings for your
    enterprise assets.
    
3 - Threat Detection and Prioritization:

    Here yoou prioritize the vulnerability findings by the risk associated 
    with their known threats and other criteria.
    
4 - Response (Patch deployment):

    Here you can respond to the detected vulnerabilities and threats
    within days or even hours, rather than weeks or months.
    
CIS Critical Security Control 1: Inventory and Control of Enterprise Assets

Overview:

    Actively manage (inventory, track and correct) all enterprise assets 
    (end-user devices, including portable and mobile; network devices;
    non computing/Internet of Things (IoT) devices; and servers)
    connected to the infrastructure physically, virtually, remotely, 
    and those within cloud environments, to accurately know the totality
    of assets that need to be monotored and protected within the enterprise.
    This will also support identifying unauthorized and unmanaged assets to remove
    or remediate.
    
Qualys Sensor Platform:

1 - Remote Scanners:

    The Remote Scanners are internet-facing and ideal for scanning
    internet-facing assets around the globe.
    
2 - Local Scanners:

    Local Scanners are deployed on local area networks and commonly scan assets
    within reserved or private IP address ranges. These local scanners can be 
    deployed as physical or virtual appliances.
    
3 - Qualys Cloud Agents:

    Qualys Cloud Agents run as a local process on the host they
    protect. Qualys agents support a wide variety of OS platforms.
    
4 - Qualys Passive Sensors:

    Qualys Passive Sensors can be deployed as physical or virtual appliances.
    Working with TAPs and Switches throughout your network, passive sensors
    operate by sniffing network traffic sent to the Qualys platform for
    processing. Another essential benefit of Passive Sensor is helping
    you to identify the unmanaged assets throughout your network architecture.
    
5 - Cloud and SaaS Connectors:

    Cloud and SaaS Connectors work with the native services of your cloud and SaaS
    providers to identify misconfigurations and security blind spots. Cloud Connectors
    can be created for your AWS, Google Cloud, and Microsoft Azure accounts. SaaS Connectors
    are available for Microsoft Office 365, Google Workspace, Zoom, and SalesForce.
    
6 - Qualys Container Sensor:

    Qualys Container Sensor downloads as a docker image and is installed on a docker
    host as a container application, right alongside other container applications.
    Once installed, Container Sensor will assess all new and existing Docker images and 
    containers for vulnerabilities and misconfigurations.
    
7 - Out-of-band-Sensors:

    Out-of-band-Sensors help to secure devices on air-gapped netwroks.
    
8 - APIs:

    APIs collect data from third parties.
    
    
Qualys Scanner Appliance

1 - Qualys Cloud Platform Internet Scanner Pool:

    Internet-based applications located within the Qualys Cloud Platform.
    These scanners are available to Qualys user accounts that have scanning 
    privileges. These appliances are ideal for targeting and scanning
    Internet-facing assets.
    
2 - Hardware-based appliances:

    Hardware-based scanner appliances are deplyoed throughout your
    network and enterprise architecture. These are physical appliances.
    
3 - Virtual Scanner Appliances:

    Qualys Virtual scanner appliances are deployed throughout your network
    and enterpriser architecture. These appliances area available for multiple
    hypervisors and cloud platforms.
    
Qualys Cloud Agent:

    Qualys agents presently supports various Windows, Mac, Linux
    and Unix-based operating systems.
    
    The cloud agent is installed as a local system service on the host
    that it protects. Thus, the Qualys Cloud Agent provides a local perspective 
    of its host. These hosts can reside on the corporate network as well
    as cloud platforms. Agents are ideal for host assets that operate remotely.
    
    A successful installed agent will build a snapshot of the data rewuired by
    it's activated applications.
    
    Agents are downloaded from the Qualys Clous Agent application, as well as the 
    VMDR Welcome page.
    
    
VDMR Activation Key 1:
Default Activation Key:

    The VMDR Welcome Page uses the Default VMDR Activation Key to download agents.
    It comes with Asset Inevntory (AI), Vulnerability Management (VM), Secure
    Configuration Assessment (SCA), and Patch Management (PM) modules activated.
    
VMDR Activation Key 2:
Configure Agents for VMDR:

    For accounts with multiple activation keys, the VMDR Welcome Page comes with
    a button 'COnfigure Agents for VDMR' where you can configure agent activation 
    keys for VMDR. This typically replaces the button 'Download Cloud Agent'.
     
VMDR Activation Key 4:
Upgrade Agent Activation Keys:
   
   Use the "Upgrade" option on a selected Activation Key to ensure that the
   Patch Management (PM), Vulnerability Manager (VM), and Security Configuration
   Assessment (SCA) modules are added. All Activation Keys include the Cybersecurity 
   Asset Management (CSAM) application, by default.
   
VDMR Activation Key 4:
Add Application Modules:

   It is advised that you avoid including both the Secure Configuration Assessment
   (SCA) module and the Policy Compliance (PC) module in the same actication key.
   You can replace the SCA module with the PC module within one key. However, it is
   highly recommended that you create two separate keys for each of these modules.
   
VDMR Activation Key 5:
Activation Key Tagging:

   When agents are deployed with the Remote Host Activation Key, they automatically 
   consume a patching liscense because of the "Remote" tag.
   
   You can design and build Activation Keys around related groups
   of assets or subnets within your network or enterprise architecture.
   Assign a "static" tag to an agent Activation Key to quickly locate the
   agent hosts that it deploys.
   
   You can then use this staic tag (assigned to agent Activation Keys)
   to assign patching licenses to hosts and ensure these hosts are correctly
   assigned to their Configuration Profile, Patch Assessment Profile, and Patch Jobs.
   
   Best Practice: Use this strategy to assign agent host assets to their appropriate 
   profiles, licenses and jobs, at the time of agent deployment.
   
   
   
    

 
    
    
    
    
    
    
    
    
    
    
