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
      Shared responsiblity describes what and which computing resources that either the cloud provider or the consumer is responsible for. 
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
              In a multi-cloud environment you use one or more cloud providers and manage resources and security in both environments.
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
      
      
        
