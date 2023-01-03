# Introduction to MS Azure fundamentals
### Azure:
      A cloud computing platform with services to help build solutions to meet business goals.
      It :
      - has Simple web services for hosting business presence in the cloud
      - Supports running fully virtualized computers managing custom solutions.
      - Provides cloud-based services like remote storage, database hosting, and centralized account management.
      - offers capabilites like artificial intelligence (AI) and internet of things (IoT) focused services.
### What is cloud computing?
      The delivery of computing services over the internet. 
      Computing services include common IT infrastructure such as virtual machine, storage, databases, and networking. It also expand tradition IT offerings to include IoT, machine learning (ML), and aritifical intelligence (AI).
      Because cloud computing is delivered over the internet it doen't have to be constrained by physical infrastructure the same way that a traditional datacenter is. 
### Describe the shared responsibility model:
      Shared responsiblity describes what and which computing resources that either the cloud provider or the consumer is responsible for managing. 
      It determines who manages the resource. 
      With on-premise resources, the consumer is fully resonsible for maintaining the datacenter, physical devices, software and applicaitons; however, with cloud computing, depending on the cloud service type (Iaas, PaaS, SaaS) the cloud provider or consumer may be solely responsible or may share the responsibility of resources. 
      Most of the time the consumer is repsonsible for the data.
      The repsoniblity may also depend on the situation. If you're using a cloud database, the db provider is responsible for maintaining the actual database but you're responsibile for the data ingested. However, if you install the db in a virtual machine in the cloud, you're responsible for database
         You'll be responsible for
             - The information and data stored in the cloud
             - Devices that are alllowed to connect to your cloud (cell phone,s computers and so on)
             -  The accounts and identites of the people, services and devices within your organization
         The cloud provider is always responsible for
             - The physical datacenter
             - The physical network
             - The physical hosts
         Your service model will determine responsiblity for things like:
             - Operating systems
             - network controls
             - applications
             - identity and infrastructre
### Define cloud models
      Cloud models define deployment type of cloud resources.
        - Private cloud:
           it is a cloud (delivering IT Services over the internet) used by a single entity. 
           pros:
             Greater control for the company and IT department
           cons:
             Greater cost and fewer of the benefits of a public cloud deployment.
           It may be hosted by from your on site datacenter. It may also be hosted in a dedicated datacenter offsite, potentially even by a a third party that has dedicated that datacenter to your company.
         - Public cloud
             The cloud provider builds, controls and maintains the cloud.
             Anyone can purchase the cloud services and access and use resources.
             NB: The public availability is a key difference between public and private clouds
         - Hybrid cloud
             Computing environment that  uses both private and public clouds in an inter-connected environment. 
             Hybrid cloud can be used by an entity when it needs to serve the need of an increased, temporary demand by deploying public cloud resources. 
             It can provide extra layer of security. eg. users can determine which service to keep in public and which to deploy in their private cloud infrastructure. 
         -  Multi-cloud: 
              Here, more that one cloud provider is used. this enables one to choose and use features from different cloud providers. 
              It is also used when one is in the process of migrating to a different provider from a previous one.
              In a multi-cloud environment you use two or more cloud providers and manage resources and security in both environments.
### Azure Arc:
      A set of technologies that enables one to manage your cloud environment. 
      It can be used manage a public cloud whether a solely Azure, private in your datacenter, a hybrid configuration, or even a multi-cloud environment running on multiple cloud providers at once.
### Azure VMware solution: 
      If an entity already uses VMware in a private cloud environment but wants to migrate to a public or hybrid cloud, Azure VMware solution let that entity run it's VMware workload in Azure with seamless integration and scalability.
### Describe the consumption-based model:
      In cloud computing there're 2 types of expenses to consider. Capital expenditure (CapEx) and Operational expenditure (OpEx).
        - Capital expenditure (CapEx) are the initial expenses needed to purchase or secure tangible resources. eg. building, vehicles, datacenter.
        - Operational expenditure are that expenses incurred on using services or products over time. Renting a convention center, leasing a company vehicle, or signing for cloud services. 
      Cloud computing falls under OpEx because it is based on consumption-based model. You only pay for what you use. You don't pay for the physical infrastracture, electricity, or anything associated with maintaining the datacenter. You don't pay for what you don't use.
      This consumption model has manay benefits, including
        - No upfront costs
        - No need to purchase and manage costly infrastructure that users might not use to its fullest potential.
        - The ability to pay for more resources when they're needed.
        - The ability to stop paying for resources that are no longer needed.
    When you try to estimate future resource demands in a traditional datacenter, you may eighter underestimate or overestimate. 
      Overestimating will cost an entity to spend more than necessary on unused or under-used resources. 
      Understimating may cause deprivation of resources when needed and can take longer time to upgrade due to delay often arose from procurement procedures.
      In a cloud environment you do not have to worry about estimation. You add resources when needed and remove when not. You don't not pay for the extra capacity that the cloud provider and provide.
### Compare cloud pricing models
      Cloud computing uses pay-as-you-go pricing model. You typically pay for the cloud services you use which helps you:
        - Plan and manage you operating costs
        - Run your infrasture more efficiently.
        - Scale as your business needs change.
      In order words, cloud computing is a way to rent compute power and storage from someone else's datacenter.  You can treat cloud resources as you would in your own datacenter. In cloud computing, when you're done with the resources you used, you give them back. You're billed only for what you used, which may not happen in the datacenter you own.
      You rent and use CPUs and storage for the time you need them instead of maintaining them in your datacenter. The cloud provider takes care of maintaining the underlying infrastracture for you.
      
# Describe the benefits of using cloud services
     The 2 most biggest considerations when building or deploying cloud applications are uptime(availability) and the ability to handle demand (Scale)
  ### High availability
       High availability focuses on ensuring maximum availability, regardless of disruptions or events that may occur.
       When architecting for cloud solutions, it is important to account for service availability quarantees.
       Azure is a highly available cloud environment with uptime guarantess depending on the service which are part of the service level aggreements (SLAs)
       - A service with 99% availability means that service can be unavailable only for 1.68 hours a week or 7.2 hours per month
       - A service with 99.9% availability means that service can be unavailable only for 10 minutes a week or 43.2 minutes per month
       100% availability is extremely difficult and expensive to achieve because it does not permit a service to be taken down for required maintenance and 
       upgrages. It requires the service to be redaundant and also requires the backup components to immediately kick-in with zero interference to the customer.
  ### Scalability
        Scalability is one of the major benefits of cloud computing. 
        It refers to the ability to adjust resources to meet demand. If a service experiences sudden peak traffic and the system is overwhelmed, the ability to scale means you can add more resources to better handle the increased demand.
        Scalability also helps to avoid overpaying resources because you can remove resources that are no longer needed. 
        There're 2 varieties of scaling: Vertical and horizontal scaling
  #### Vertical scaling
         With vertical scaling you increase or decrease resources capabilities as and when they're needed.
         If an app needed more power or memory, you can scale up by increasing CPUs capabilities or RAM size to the virtual machine. You can also scale down by reducing the   CPUs or RAM size that are too much for the app.
  #### Horizontal scaling
         With horizontal scaling you add more resources (scale out) when needed and remove resources that are not needed (scale in). 
         You scale out by adding resource eg. adding another virtual machine or running multiple instances of the services.
### Describe the benefits of reliability and predictability in the cloud
      Reliability and predictability are 2 crucial cloud benefits that help you develop solutions with confidence.
   #### Reliability:
          Reliability, which is one of the pillars of MZ Azure is the ability for a system to recover from failures and continue function.
          The decentralized design of the cloud makes it naturally support a reliable and resilient infrastructure. 
          With the decentralised design, the cloud makes it possible to deploy resources in different regions around the world. This design makes it possible for services to continue running even when there's catasrophic event as other regions are still up and running. 
          We can desing applications to take advantage of this increased reliability. 
          In some cases the cloud environment itself will automatically shift to a different reion, with no action needed on your part.
   #### Predictability: 
          Predictability lets you move forward with confidence because you can predict what the future will be in terms of cost and performance.
          Performance predictability: 
            This focuses on predicting the resources that are needed to deliver positive experience for your customers.
            - Autoscaling, load balancing and high availability are some of the cloud concepts that support performance predictability.
            - If you sudden need more resources, autoscaling can deploy additional resources to meet the demand, and then scale back when the demands drops.
            - Load balancing can help redirect some of the load to other less stressed areas when traffic demand is heavy in one area.
          Cost predictability:
            Cost predictability focuses to predicting or forecasting cloud spend.
            With the cloud we can monitory resources usage in real-time and ensure that we're using them in the most efficient way, and apply data
            analytics to find patterns and trends tha help better plan resource deployments.
            YOu can predict future costs and adjust your resources as needed by using cloud analytics and information.
            Total cost of Ownership (TCO0 or pricing calculator get help get an estimate of potential cloud spend.
### Describe the benefits of security and governance in the cloud
      Whether you're deploy and IaaS or SaaS, cloud features support governance and compliance.
      Set templates helps to ensure that all deployed resources meet corporate standards or government regulatory requirements.
      You can also update all deployed resources to new standards as standards change.
      Cloud-based auditing helps flag resources that do not meet standards or are out of compliance and provides migration strategies.
      Depending on the operating model, software udpates and patches can be applied automatically, which helps with both governance and security.
      - If you want maximum control IaaS provides you with physical resources but lets you manage operating system and installed software, including patches and updates
      - If you want patches and maintenance taken care of automatically then you should opt for SaaS.
      - Cloud provider are best suited to handle things like DDoS attacks, making your network more robust and secure because cloud is the delivery of IT resources over the internet.
      
### Describe the benefits of manageability in the cloud
      A major benefit of cloud computing is the manageability options. There're 2 types of cloud manageability - Management of the cloud and management in  the cloud.
#### Management of the cloud
       Management of the cloud is about managing your cloud resources. In the cloud, you can:
       - Automatically scale resources based on need.
       - Deploy resources based on preconfigured template, removing the need for manual configuraiton.
       - Monitor health of resources and automatically replace failing resources.
       - Receive auatomatic alerts based on configured metrics, so you're aware of performance in real time.
#### Management in the cloud.
        Management in the cloud is about how you're able to manage your cloud environment and resources. 
        It's about the channels that you can use to manage the cloud and the resources
          YOu can manage the cloud:
            - Through a web portal
            - Using command line interface (CLI)
            - using APIs
            - using PowerShell.
##  Describe cloud service types 
### Infrastructure as a Service (IaaS)
      Infrastructure as a service is the cloud type that provides maximum control. It is like you're renting the physical resources and whatever you do with those resources is up to you. 
      It is your responsibility to install operating sytems, databases, configuration etc., updates and software patches. 
      The cloud provider's responsibility is to maintain the physical hardware and internet connectivity.
 #### Scenarios suited for IaaS
        Lift-and-ship: When migrating from on-prem datacenter to cloud and simply want to move what are running on-prem to running on cloud infrastructure.
        Test and Development environment : You have established configuration for test and development environments and you rapidly want to replicate. 
 ### Platform as a service (IasS)
     PaaS is between IaaS and SaaS. It is mostly suited for development without the headache of maintaining infrastructure. The cloud provider maintains the physical infrastructure and connections, operating system, database, updates and patches and development tools.
     In PaaS you don't have to worry about software licence and operating system patches.
 #### Shared responsibility model
        PaaS splits the responsibility between you and the cloud provider. The provider maintains the physical resources like hardware and connections. Depending 
        on your configuration, the cloud provider may be responsible for network setting and connectivity within your cloud environment.
   ##### Scenarios.
           Common scenarios where PaaS is suited.
             - Development Framework: PaaS providers development framework that developers can build upon or customize cloud based-applications.
                                      PaaS lets developer4s create applications using built-in software components. 
                                      Cloud features such as scalability, high availability, multitenancy are included, reducing the amount of coding developers
                                      have to do.
             - Analytics or business intelligence: Tools included in PaaS enables organisations to analyze and  mine their data, finding insight and patterns and 
                                                   predicting outcomes to improve forecasting, product design, decision making, investment returns.
### Sofware as a Service  (SaaS).
      In a product perspective SaaS is the complete cloud service. With SaaS you're renting a fully developed application and you do not worry about infrastural and 
      platform concerns. Eg of SaaS. email, finance applications etc.
      SaaS is the cloud service with the lowest level of flexibility but also the easiest to get up and running. It require least techinical knowledge to employ. 
  #### shared responsibilites:
       Cloud provider: Manages physical infrastrue, operating system, power, security, updates, patches and etc.
       User: manages user accounts, database, devices that can connect and mainly data.
  #### Scenarios:
         - Email messaging,
         - Business productivity applications,
         - Finance and expense tracking.
      
      
 # Azure Fundamentals: Describe Azure architecture and 
 ## Describe Azure physical infrastructure
      The core architectural components of Azure may be broken down into 2 main groupings: the physical infrasctructure, and the management infrastrcuture.
 ### Physical infrasctructure
       The physical infrastructure starts with datacenters. They/'re facilities with resources arranged in racks, with decicated power, cooling, and networking infrastructure.
       Azure has datacenters around the world which are not directly accessible. Datacenters are grouped into Azure regions or Azure availability zones that are designed to achieve resiliency and reliability for business-critical workloads.
 #### Regions.
        A region is a geographical location the planet with one or more datacenters that are nearby and networked with low-latency network.
        Azure intelligent assigns and controls the resources within each region to ensure that workloads are appropriately balanced.
            NB: Some services or virtual machine (VM) features are only available in certain regions, such as VM sizes or storage types. 
                There're also some global Azure services that don't requre you to select a particular region, such as Azure active directory, Azure traffic manager, Azure DNS
#### Availability zones
       Availability zones are physically separate datacenters within an Azure region with each having its own dedicated power, cooling, and networking. 
       Each zone is setup to be an isolated boundary. If one zone goes down, other ones are not affected and continues to work.
       Availability zones are connected through high-speed, private fibre-optic networks.
            NB: To ensure resiliency, a minimum of 3 separate availability zones are present in all availability zone-enabled regions.
                However, not all Azure Regions currently support availability zones.
#### Use availability zones in your apps
       - You want to ensure your services and data are redaundant so you can protect your information in case of failure.
       - Azure can make your apps highly available through availability zones.
       - You an use availability zones to run mission-critical applications and build high-availability into your application architecture by co-location your
          compute, storage, networking, and data resources within an availability zone and replicating in other availability zones. NB: There may be cost in duplicating or transferring data between availability zones.
       - Availability zones are primary for V<s, managed disks, load balancers, and SQL databases. 
       - Azure services that support availability zones fall into 3 categories:
          -- Zonal services: You pin resources to a specific zone (eg. VMs, managed disks, IP addresses).
          -- Zonal-redaundant services: The platform replicates automatically across zones (eg. zone-redaundant storage, SQL database).
          -- Non-regional services: Services are always available from Azure geographies and are resilient to zone-wide outages as well as region-wide outages.
       It's possible that an event could be so large that it impacts multiple availability zones in a single region despite the addition resiliency that availability zones provide. 
       To proved further resiliency Azure uses Region pairs.
#### Region pairs:
       Most Azure regions are paired with another in the same geographical area  at least 300 miles away. This allows for the replication of resources across a geography that helps reduce the likelihood of interrupgions because of events susch as power outages, civil unrest, explosions, physical network outages that affect an
       entire region.
       Services automatically failover to the other region in its region pair in case it is unavailable.
         NB: Not all Azure services automatically replicate data or automatically fall back from a failed region to cross-replicate to another enabled region. 
             These require the customer to configure recovery and replication for those service.
       You can take advantage of the wide distance between regions in a pair to provide services that are resilient, reliable and data redaundant because these regions in the pair are connected directly and may be isolated from disasters.
##### Additional advantages of region pairs:
        - if an Azure extensive outages occurs, one of the regions in the pair is prioritized to make sure at least one is restored as quickly as possible for applications hosted in that region pair.
        - To minimize the down-time in case of Azure updates, updates are planned and rolled out to paired regions, one region at a time.
        - Data continues to reside within the same geography as its pair for tax and law-enforcement juridication purposes.
        Important:
          Most directions are paried in two directions, meaning thay are the backup for the region that provides a backup for them.
          However, some regions, such as West India and Brazil South, are paired in only one direction. In a one-direction pairing, the Primary region does not provide backup for its secondary region. So, even though West India’s secondary region is South India, South India does not rely on West India. West India's secondary region is South India, but South India's secondary region is Central India. Brazil South is unique because it's paired with a region outside of its geography. Brazil South's secondary region is South Central US. The secondary region of South Central US isn't Brazil South.
             
       
                
      
        
