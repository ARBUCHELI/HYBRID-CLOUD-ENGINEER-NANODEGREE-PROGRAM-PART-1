# HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-

# LESSON 1 INTRODUCTION TO THE HYBRID CLOUD

## Reflexions by the Instructor

Many customers newly discovered virtualization in relation to Cloud. Suddenly, many companies branded their products as Cloud-ready, not saying what “ready” really meant:
only backup in the Cloud, migration between physical systems and the Public Cloud, migration within  the Cloud, inclusion of Private Clouds, or Disaster Recovery in the Cloud.

Suddenly, many companies decided to go Cloud despite that Cloud not necessarily providing what on-prem had until then. Typically to move away from Capital Expenditure (CAPEX) 
with its upfront server-farm costs and in-house maintenance, to Operational Expenditures (OPEX).

Nutanix is a company with built-in functionality for virtualization and Cloud. Since that time, it has become clear that “The Cloud” is a concept that has different meanings to 
different people and companies: sometimes an intangible concept, but always showing the need for people who truly understand Cloud concepts and, perhaps more importantly, can
execute on them.

After an introduction in technology history related to the Cloud, we will discuss what makes a company cloud-ready, what the differences are between private/public/multi/hyper
cloud, what the pros and cons are of the various Cloud implementation, and how to place and migrate data.

## Prerequisites

In order to take this course, you should be comfortable with command line on Linux or Windows. It would also be helpful for you to have a background in working with VMs as well as
AWS or GCP cloud.

Please note: There are no AWS credits needed for this Nanodegree.

## Course Outline

In this course, we're going to cover:

* The Journey to the Modern Hybrid Cloud
* Introduce you to the Nutanix HCI
* Hybrid Cloud Security
* Networking
* Managing Virtual Machines in the Hybrid Cloud
* Data Protection
Let's get started!

![image](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/1.jpg)




# LESSON 2 JOURNEY TO THE MODERN HYBRID CLOUD

## Lesson Overview

Lesson Overview
Welcome to the Journey to the Modern Hybrid Cloud!

In this lesson, we’re going to cover:

* What the role of a Hybrid Cloud Engineer is

* The different models to support various Cloud initiatives

* The Engineer’s role in Service Level Agreements related to Cloud apps

* How to choose the optimal Cloud platform for an app, based on business requirements and SLAs

![image](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/2.jpg)

## Why are Hybrid Cloud Engineers needed?

Most companies have plans for transitioning their IT to a cloud-focused model. There are a few challenges when it comes to this because carrying out these plans and reaching these goals are a little easier said than done.

Here are the two main reasons for the difficulties:

* The first one is a lack of organizational readiness. Having a cloud-focused model affects many aspects of the organization outside of the tech-side, like people and processes. Each business has to prepare for these impacts during their Cloud adoption plans.

* Second, adding technology doesn't necessarily add value unless there's a clear goal or outcome to be achieved.

<strong>To avoid these challenges, you need to focus on business requirements first. Once you've figured out the business requirements, you can then match those requirements to technologies that help achieve those goals or requirements. Then, you need the right mix of skills to carry the plan out.</strong>

This is where the Hybrid Cloud Engineer comes in. The engineer is needed to help organizations successfully plan and implement their cloud transformation.

<strong>A hybrid cloud engineer can bring in new technologies quickly, analyze competition, and create comparisons between old and new ways of doing business. Hybrid cloud engineers are able to modernize any organization, but they will find every business increasingly requiring hybrid capabilities to compete on a global scale.</strong>

![image](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/3.jpg)

![image](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/4.jpg)

## What does a Hybrid Cloud Engineer do?

<strong>A hybrid cloud engineer can design, create, operate, and manage different types of workloads across multiple clouds and infrastructure providers.</strong>

The engineer should be able to:

* Consult and plan with business stakeholders
* Successfully execute this plan
* Validate outcomes through their technical skillset

The Hybrid Cloud Engineer helps organizations determine their readiness, and make suggestions if an organization isn't ready yet. <strong>One of the most important things to check is if business requirements are clearly defined</strong>. This is done through Service Level Agreements, or SLAs, need to be completely documented and enforceable. This is what you're going to use to choose the right infrastructure for every service.

This is followed by implementation.

<strong>Implementation involves planning and executing migration</strong>. This involves a few things like <strong>refactoring applications for the best possible Total Cost of Ownership, or TCO, and Return On Investment, or ROI</strong>. Once complete, the technical and organizational infrastructure needs to be <strong>continuously monitored to check if performance expectations that were created in the SLAs are met</strong>.

## Hybrid Cloud Engineer

![image](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/5.jpg)

## Digital Transformation

![image](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/6.jpg)

The need for complex and specialized silos for data center infrastructure was removed by public cloud providers through the commoditization of the IT industry. This is called <strong>digital transformation</strong> (or DX) in the industry and refers to traditional IT practices making the effort necessary to modernize. Naturally, this takes a lot of time and resources.

<strong>Now, companies that have on-prem data centers have more difficulty evolving than newer organizations that have always utilized the public cloud</strong>. The hybrid cloud helps bring both sides together by addressing their operations and their workloads. We're going to cover the evolution of IT that brought us to where we are today, to show how the hybrid cloud helps resolve a lot of these issues.

![image](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/7.jpg)

<strong>Businesses have changed their course of operations due to disruptive technology waves with digital transformation</strong>. According to a recent IDC study, digital transformation will consume half of all information technology budgets by 2023. Both delivery times and <strong>Moore’s Law</strong> have been show to disrupt how businesses operations historically.

An example of this is how data centers with their thousands of physical servers overtook mainframes.

Procuring, installing, configuring, and bring up a new server in their data center would take months. <strong>In order to significantly reduce the amount of time, data centers consolidated hundreds of physical servers running virtual machine workloads</strong>. The rise of public and private clouds came from the delivery of virtualization with on-demand consumption. This only needed half of the resources required from the virtualized data center.

<strong>As a hybrid cloud engineer, your role will be to help an organization modernize its operations and infrastructure, regardless of where they are at IT-wise.</strong>

You'll be able to help an organization’s growth by recognizing, understanding, and capitalizing on opportunities to migrate to more efficient technologies.

![image](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/8.jpg)

## Understanding the Cloud

### The Cloud is an Experience and a Mindset

![image](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/9.jpg)

NIST defines cloud computing as <strong>"a model for enabling ubiquitous, convenient, on-demand network access to a shared pool of configurable computing resources. For instance: networks, servers, storage, applications, and services that can be rapidly provisioned and released with minimal management effort or service provider interaction."</strong>

According to NIST, the cloud model has 5 essential characteristics, 3 service models, and 4 deployment models.

### Service Models

![image](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/10.jpg)

<strong>You're able to run both traditional and newer cloud-focused applications in a variety of places</strong>. The progression of managed service providers up the technology stack were driven by technology waves. From delivering Infrastructure as a Service, to on demand Virtual Machines, to platforms, and to full software.

Running applications on bare-metal are involved in traditional on-prem IT. An example of this is when, in the co-location mode, you can choose to run your applications in a third-party managed data center. This type of hosting model involves managing only your applications instead of the underlying hardware. The virtualization layer and above is the focus.

* With <strong>Infrastructure as a Service</strong>, or IaaS, you are only managing the workloads and applications that are running on virtual machines and containers.

* With <strong>Platform as a Service</strong>, or PaaS, you are only responsible for applications and their data.

* Finally, with a <strong>Software as a Service</strong>, or SaaS, model, every aspect of the infrastructure is provided to you. The only thing that you are required to manage is the data. Everything else is being managed by a provider.

<strong>Understanding all of these models is an area of expertise for hybrid cloud engineers in order to know which the best ones are to leverage</strong>.

You need to answer 4 main questions to start the organization's digital transformation:

* How do you leave traditional IT behind and become a Cloud consumer?
* How do you choose between application hosts? Infrastructure as a Service, Platform as a Service, or Software as a Service?
* How does your choice impact workload design, deployment, management, and costs?
* Can you leverage multiple models effectively?

Once you receive the answers, you're a lot closer.

![image](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/11.jpg)

## Application Design: The Monolith

![image](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/12.jpg)

Application development has been influenced by the technology stack. The application design was both constrained to one infrastructure vendor with past monolithic infrastructure. <strong>When we refer to <strong>monolithic</strong>, we mean there is one, single source of every component in the stack</strong>.

Only big businesses or government agencies could afford the monolithic infrastructure because the costs were so high. These applications are still around. For example, there's a banking application written in COBOL for a mainframe and that's been in use for the last 40 years.

Some challenges with applications like this are:

* It is a single application written in a single language.
* It is run in a batch, or is constantly executed on a single instance of infrastructure.
* To address performance issues and bottlenecks, it is necessary to scale up by increasing compute, storage, and memory resources. These resources are always constrained to a monolithic server’s capabilities.
* The infrastructure is also monolithic. It is provided by a single vendor, who potentially also controls the application development tools, database, and operating system layers that are running on their hardware.

These challenges can be mitigated despite monoliths existing everywhere and being both difficult and expensive to maintain.

![image](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/13.jpg)

## Application Design: Distributed Web Scale

The Internet and open source software lowered application design costs and changed to being distributed over the network. The functionality became a separation of duties from being monolithic.

You can easily see this was a typical three-tier web application, this includes:

* The web presentation-tier using JavaScript, HTML, and CSS
* The application logic tier using programming languages such as: Java, C++, Python, or Ruby
* A database cluster for persistence.

By having every tier operate independently of the other tiers, this allows infinitely scaling out to accommodate demand. This can either be done by increasing or decreasing the population of the tier and distributing work in parallel.

<strong>Micro-service architecture with further separation of tier function allows application architecture to evolve towards network APIs based on the web, called RESTful APIs, or REST APIs</strong>.

Today’s cloud infrastructure is networked, which isn't like the single vendor's technology stack in monolithic architecture. <strong>When any individual member fails load balancers distribute each application tier's requests and maintain high availability. Every endpoint behind the load balancer can be hosted anywhere and mixed between different technologies which allows hybrid cloud mixing of IaaS , PaaS, and SaaS</strong>.

![image](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/14.jpg)

Here is an example 3-tier web application that incorporates distributed web scale application design concepts such as load balancing and scale out fleet management of each application tier. A customer request comes to a web load balancer.

The web load balancer directs the request to any of the web presentation tier members, in this case Web4, to show a web page which needs to display application logic served through the AppServer Load Balancer from the Application Logic Tier members, in this case from AppServer2. AppServer2, in turn, reads data from the database cluster, in this case: the Database3 instance.

You can see that each tier can scale independently for performance and can survive partial failures for high availability. You could lose or maintain Web1, AppServer3, and Database4 without significant impact to the three-tier web application. <strong>Today's applications are multilingual with a distributed architecture over the network for vast scalability, leveraging web technologies for APIs. These apps can be hosted on any infrastructure in a hybrid cloud fashion</strong>.

Examples of these web-scale applications with a global reach are Facebook, Netflix, and Gmail.

![image](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/15.jpg)

## The Cloud Differentiator

There are many reasons that organizations are more and more interested in making the transition to the cloud. What differentiates the organizations that use it from the organizations that do not? Why is the cloud so important?

The NIST definition can provide some clarity on what the cloud is:

In the State of the DevOps Report 2019, it was determined that the highest performing teams are <strong>24 times</strong> more likely to execute on all five cloud capabilities, when compared to lower performing teams. The cloud, therefore, can be viewed as a differentiator for elite performers as well as a tool in general that drives high performance.

<strong>There are first two major aspects of cloud consumption that organizations need to take into consideration: fiscal consumption and workload predictability</strong>.

## Cloud Considerations

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/16.jpg)

Let's zoom out a bit. Think about this, <strong>there are two basic consumption models: renting and buying</strong>.

<strong>Renting can have low entry costs, but higher long-term costs. These can be described as operational expenditures verses capital expenditures that can be blended based on needs usually. The business model everyone wants, is to blend the best of both worlds: renting and buying, OpEx and CapEx, to address variable and fixed workloads.

Think about staying in a hotel as opposed to buying a house. Would you buy a house when you go on vacation? Would you stay in a hotel for year? When would you rent a car over buying one?

The public cloud’s optimal use-case is utility computing for workloads which can be turned on-and-off at will.

The private cloud’s optimal use-case is for fixed, long-running and ongoing workloads. In other words, a business can purchase on-prem private cloud and depreciate that investment as a capital expenditure, or CapEx, but also purchase off-prem private cloud resources for backup, burst load, and temporary workload needs as OpEx to augment their baseline workload capacity.

Control and management of workloads across public and private clouds is what the hybrid cloud allows</strong>.

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/17.jpg)

## Cloud Considerations: Workload Predictability

Depending on the nature of the workload determines where it will run best.

<strong>The public cloud is best for elastic workloads</strong>. The public cloud allows you to spin up or spin down resources to meet the workload’s demands quickly, easily, and efficiently when a workload is unpredictable.

<strong>The private cloud is great for predictable workloads</strong>. It is a secure and efficient way to run core workloads, with the agility and sit-back simplicity that IT teams want, and with the control that an organization needs for on-prem workloads.

<strong>A hybrid cloud blends these two worlds together</strong>.

Distribute workloads across public and private cloud, still allows you to control and manage them centrally. The overall management of your deployment is simplified this way. This provides the required flexibility to make the best financial choice for your workloads, and deploy them where they run best.

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/18.jpg)

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/19.jpg)

## Organizational Readiness Fundamentals

<strong>The first step in executing a cloud transformation plan is determining an organization’s cloud readiness</strong>. You need to understand how the organization is currently delivering IT, what technologies are being used, and what they mean for the organization’s ability to transition to the cloud to complete an organizational readiness assessment. This will determine if an organization is ready to make the transition, what the gaps are, and how those gaps need to be addressed for successful migration. It's critical that a hybrid cloud engineer understand these items.

<strong>Almost every business has a cloud transformation plan. Problems for businesses executing their digital and cloud transformation plans can be caused by their organizational models</strong>. Organizational models can refer to how an IT department is structured for example and how technology is actually used. These two models speak to organizational readiness. <strong>Organizational readiness</strong> refers to how ready a business is to execute their cloud transformation plan successfully.

<strong>Why do business think about fiscal consumption and their workload predictability? Usually, those conversations begin when a business is considering making the transition to the cloud</strong>.

The entire assessment begins with the org chart.

![](https://video.udacity-data.com/topher/2020/May/5eb43d4c_slide-41-organizational-readiness-fundamentals/slide-41-organizational-readiness-fundamentals.png)

One of the most important parts of the process is gathering detailed information and knowing the key stakeholders early on. There are different IT domains to learn as well as what they do to deliver business services.

Your findings will allow you to create a map of the technologies and organizational models used across the organization. Then, assign a cloud readiness score to each domain. We are going to use a very simple metric to assign that score that we'll cover next.

## What is Cloud Readiness?

<strong>The readiness of each organizational model or technology used is either ready or it's not</strong>. You'll notice this when you perform organizational assessments. You assign every items a high or low score.

<strong>Low Cloud Readiness</strong>
A low cloud readiness score means that technology and workforce skills are more traditional. This means the current environment is used exclusively to run legacy, shrink-wrapped applications.

The IT staff managing the physical infrastructure could be siloed, based on the 3-tier model. An example of this scenario, is if legacy technology and organizational models are currently supporting IT. Or, if many workloads are running on bare metal and traditional, monolithic applications are the norm. <strong>A platform upgrade and workforce up-skilling create the possibility to facilitate cloud transformation so adopting the hybrid cloud model is not a problem too great to overcome</strong>.

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/20.jpg)

<strong>High Cloud Readiness</strong>
High cloud readiness means that the technologies and workforce skills that support IT are aligned with what is required to <strong>successfully use the full capabilities of the public, private and hybrid cloud</strong>. A good example of this scenario is if catalog-based self-service is available to users.

<strong>Having a DevOps initiative and micro-service-based application architecture in use,​ or containers being used for some applications would make it easy to move to a hybrid cloud</strong>.

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/20.jpg)

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/22.jpg)

## Cloud Smart, Not Cloud First

![](https://video.udacity-data.com/topher/2020/June/5ed5a7f2_screen-shot-2020-06-01-at-9.13.38-pm/screen-shot-2020-06-01-at-9.13.38-pm.png)

The US government adopted a Cloud First strategy nine years ago. Most departments began implementing a lift-and-shift strategy. This was done to move their applications into the public cloud or multiple public clouds. We started to see this was becoming expensive and wasn't really benefitting the government very much. The way they handled moving to the cloud was a problem. The Cloud First approach is still popular, but being Cloud Smart is the right way to go.

<strong>Cloud Smart</strong>is about rationalizing applications, infrastructure, skills, and people across hybrid clouds and ensuring everything is where it fits best.

You can leverage the essential characteristics of the cloud over various deployment models by looking at the cloud as an experience and a mindset. Since everything is on demand, it doesn’t take ten hours or six months to get a cloud result. Rapid elasticity with service measurements allows these organizations to understand how well they’re managing their on-prem and off-prem resources.

That is the difference between Cloud First – where everyone starts – and Cloud Smart.

## Why Cloud Smart?

Cloud First was wasteful for many early adopters.

Organizations that used a lift-and-shift approach to the process took a VM disk, a snapshot of a server, and moved them to a single public cloud. This meant that there was downtime and that they were locking into a single public cloud. Running a workload 24 hours a day, 7 days a week was a huge operating expenditure. It's cheaper to run this type of workload on-prem.

The lock-in combined with the increased OpEx required a second lift and shift, to return to the on-prem CaPex model. This wound up wasting time, money, and effort on moving their workloads back and forth. After all this, they found themselves right back to where they started.

![](https://video.udacity-data.com/topher/2020/May/5eb33600_screen-shot-2020-05-06-at-6.11.02-pm/screen-shot-2020-05-06-at-6.11.02-pm.png)

<strong>What needs to change?</strong>
The short version is that lifting-and-shifting all of your workloads to a single provider is a mistake. What’s required is the cloud-smart model, which the US Government advocated in 2019.

![](https://video.udacity-data.com/topher/2020/May/5eb43a99_screen-shot-2020-05-07-at-12.42.50-pm/screen-shot-2020-05-07-at-12.42.50-pm.png)

What you’re seeing here is directly from the CIO of the US Government.

* It comes down to needing to move towards hybrid, multi-cloud environments to avoid lock-in.
* There’s a need to address the long-term inefficiencies of migrating applications as-is. This is what caused the OpEx burden from lifting and shifting into the public cloud.
* It’s necessary to rationalize the work and identify the immediate financial cost of modernization, so that it is easier to identify where the right place is to run a specific workload.

This is how you use the Cloud Smart model to move towards successful digital transformation.

## Legacy IT: The Mainframe

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/23.jpg)

To really look at how technology evolved to give us the cloud, let's start with the mainframe. <strong>Mainframes are still integral to many enterprises’ IT infrastructure. The mainframe is monolithic architecture that first appeared on the computing landscape in the 1940s</strong>.

Over 70% of the Fortune 500 companies still use mainframes for business-critical applications. <strong>Common use cases include Online Transaction Processing, or OLTP, for banking, Government, Utilities, Education, and Research</strong>. Mainframes also support Linux, Java, Scala, Python, TensorFlow, and Apache SparkML for machine learning and Artificial Intelligence. <strong>Their tremendous processing power and security capabilities also make mainframes ideal Blockchain hosts</strong>.

![](https://video.udacity-data.com/topher/2020/May/5eb43d03_slide-58-mainframes-advantages/slide-58-mainframes-advantages.png)

<strong>Advantages</strong>

There are several reasons for the mainframe’s continued popularity.

* The enormous resources and computing power that is provides via its monolithic, converged architecture. It is, for example, 18 times faster than an x86 platform.

* It also provides decades of uptime and provides high levels of security.

* It also supports virtualization, which is an increasingly critical element of computing infrastructure today.

![](https://video.udacity-data.com/topher/2020/May/5eb43de5_slide-59-mainframes-disadvantages/slide-59-mainframes-disadvantages.png)

<strong>Disadvantages</strong>

Despite its many advantages, the mainframe isn’t the perfect solution for all computing needs.

* Having access to the extensive amount of resources a mainframe provides requires a massive capital investment.

* Mainframes only get more expensive when they need to scale, because their monolithic architectures require massive blocks to expand.

* There’s also the concern of vendor lock-in, due to the use of proprietary hardware and software.

Finally, operating, managing, and maintaining such a complex piece of computing technology requires highly specialized skills.

## Quiz - Legacy IT: The Mainframe

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/24.jpg)

## Legacy IT: Distributed Computing

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/25.jpg)

In the 80s, there was a need for departmental computing, which coincided with advances in memory, storage, software, LAN, and WAN technologies.

Mass-produced microprocessors were suddenly everywhere. Commodity operating systems and competing manufacturers further accelerated innovation in software and hardware. Open networking standards, especially IEEE 802.3 and TCP/IP, and the push to establish global networks, began to break down the monolithic, proprietary computing models of the mainframe era. Smaller, cheaper servers could be used to build infrastructure one box at a time. LAN technologies and open standards like TCP/IP made it easier to network stand-alone servers and provided cheaper, faster scalability.

![](https://video.udacity-data.com/topher/2020/May/5eb43f34_slide-63-distributed-computing-advantages./slide-63-distributed-computing-advantages..png)

<strong>Advantages</strong>

* The low cost, making the barrier to entry very low. This was a dramatic change from the enormous investments required to stand up a mainframe.
* By design, these systems were also easier to scale, making it much easier to expand an environment to meet growing needs. Most standards were open and because hardware and software were commoditized, businesses had a wealth of choices when making purchases.
* Since these were commoditized systems, niche skills were no longer needed to operate and manage them.

![](https://video.udacity-data.com/topher/2020/May/5eb43fd4_slide-64-distributed-computing-disadvantages./slide-64-distributed-computing-disadvantages..png)

<strong>Disadvantages</strong>

* Underutilization was the norm, which resulted in low return on investment, and high total cost of ownership.
* Despite being scalable, these systems were not highly available, opening businesses to the risks of downtime and data loss.
* The inherent scalability of the distributed systems also led to sprawl, which made them difficult to secure and manage.
* Finally, because of the sheer number of components involved in different systems, IT organizations experienced sprawl as well, becoming disjointed and siloed.

## Quiz - Legacy IT: Distributed Computing

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/26.jpg)

## Legacy IT: Centralized Storage and 3-tier

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/27.jpg)

### Why Centralized Storage?

A key factor in the success of a business is its ability to store massive amounts of data and access it reliably. However, as distributed computing grew in popularity, this proved to be a problem. Data residing in direct attached storage grew massively, and organizations needed more space than what was locally available. At the same time, high availability was an increasingly important factor for storage, something that local storage could not provide.

The answer came in the form of centralized storage.

### What is Centralized Storage?

<strong>Centralized storage, as the name suggests, involves high volume, shareable storage that can be accessed by multiple servers over the network</strong>. It provides standalone servers with pools of storage and data protection via multiple network paths, multiple storage processors, and RAID protection at the disk level.

There are two important forms of centralized storage: <strong>SAN, or Storage Area Network</strong>, and <strong>NAS, or Network Attached Storage</strong>. <strong>A SAN is a dedicated, specialized, high speed network that provides access to block-level storage. A SAN typically consists of hosts, switches, and storage devices, all connected to each other</strong>. Previously, SAN used Fibre Channel fabrics to connect servers to storage arrays at the block level. Now, many use iSCSI or Fibre Channel over ethernet.

<strong>A NAS is a storage device that is connected to a network and allows data to be stored and retrieved from a centralized location. NAS devices use Ethernet to access shared storage devices at the file level</strong>.

![](https://video.udacity-data.com/topher/2020/May/5eb44982_slide-69-3-tier-architecture/slide-69-3-tier-architecture.png)

### 3-tier Architecture

Centralized storage works with distributed computing to create the 3-tier infrastructure architecture that is popularly used in datacenters today. In this computing model, servers and storage are separate entities, connected through a storage network.

![](https://video.udacity-data.com/topher/2020/May/5eb449b9_slide-70-centralized-storage-advantage/slide-70-centralized-storage-advantage.png)

### Advantages

* Centralized storage solved the data availability problem that was caused by distributed computing.

* The ability to add storage separately from computing resources also meant that companies could scale storage to meet the needs of their growing data.

* An added benefit was that application high-availability became easier in distributed environments, because centralized storage facilitated shared disk access for clustering.

![](https://video.udacity-data.com/topher/2020/May/5eb449f2_slide-71-centralized-storage-disdvantage/slide-71-centralized-storage-disdvantage.png)

### Disadvantages
However, there were disadvantages as well:

* Storage array and network management became a specialized IT domain, resulting in the need for specialized skills.

* As centralized storage increased in sophistication, it also brought increased complexity via concepts like SAN fabrics, WWPNs, RAID groups, volumes, spindle counts, and so on.

* The flexibility to add storage separately from computing meant that scaling was also uneven – storage was scaled in large blocks, while servers were scaled in smaller increments.

* This resulted in large CapEX commitments when storage was needed. Since storage was purchased in large blocks, it could sometimes take years to fill the available disk space, resulting in very long time to value.

## Quiz - Legacy IT: Centralized Storage

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/28.jpg)

## Legacy IT: x86 Virtualization

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/29.jpg)

Both distributed computing and 3-tier systems exhibit flaws when required to operate at scale.

First, applications running on bare metal, on a commodity operating system, cannot effectively share resources with other applications. As a result, overall resource utilization remains low – typically at less than 20% over a server’s lifetime.

The answer to the resource utilization problem was <strong>virtualization</strong>.

![](https://video.udacity-data.com/topher/2020/May/5eb44b4d_slide-75-x86-virtualization/slide-75-x86-virtualization.png)

<strong>Virtualization</strong> uses an abstraction layer and resource scheduler called a hypervisor to run virtual machines on shared hardware resources. Virtual machines, or VMs, can be run at 80% or higher resource utilization without contention, solving one of the major problems of distributed and 3-tier architecture.

In addition to resource utilization efficiency, VMs offer other advantages as well. They can be moved between hosts without downtime. And cloning, backup, and recovery of both servers and applications are simpler.

<strong>x86 hardware</strong> is a good fit for virtualization because, since the mid 2000s, each generation of the x86 processor has added features to improve virtualization performance. The latest generation supports virtualized network, storage, and server infrastructure, with performance that matches dedicated Application Specific Integrated Circuit, or ASIC-based hardware.

![](https://video.udacity-data.com/topher/2020/May/5eb44bd1_slide-76-x86-advantage/slide-76-x86-advantage.png)

### Advantages

x86 virtualization dramatically changed infrastructure resource utilization for the better:

* The ability to utilize 80% or more of the available infrastructure resources meant that businesses also experienced huge ROI gains with drastically lower TCO.

* An added benefit was that VMs could be moved between hosts without downtime, and operational processes such as cloning, deployment, backup, and recovery of servers and applications were simplified.

![](https://video.udacity-data.com/topher/2020/May/5eb44be9_slide-77-x86-disadvantage/slide-77-x86-disadvantage.png)

### Disadvantages

There were disadvantages with this model as well:

* VM sprawl and the need for high availability resulted in high demands on storage and network resources.

* If VM sprawl goes unmanaged, it can result in more complexity and increased costs.

* Mixed environments – which include both virtualized and non-virtualized workloads – can result in even more management complexity.

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/30.jpg)

![](https://video.udacity-data.com/topher/2020/May/5eb44c41_slide-78-from-x86-came-sddc/slide-78-from-x86-came-sddc.png)

x86 hardware innovations took place at a tremendous pace.

Not only was there a rapid release cadence for x86 hardware, but it also provided the ability to run all required datacenter components as commodity servers. It led to the development of the <strong>Software Defined Datacenter (SDDC)</strong>, which paved the way for <strong>Hyperconverged Infrastructure (HCI)</strong>, and fueled the Webscale revolution underpinning the Public, Private, and Hybrid Cloud.

## Quiz - Legacy IT: x86 Virtualization

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/31.jpg)

## Legacy IT: Hybrid Cloud Readiness

Before we move on to the software defined datacenter and the web scale revolution, let’s take a quick look at some cloud readiness guides for legacy infrastructure. Sometimes, determining a cloud readiness score for these technologies can be difficult, but the examples here should make matters easier.

In the case of a mainframe, depending on what an organization is using it for, they may or may not be in good shape to make the transition to the hybrid cloud. For example, if an organization is using a mainframe to:

* Host a private cloud
* There is modern application development
* A supporting DevOps team
* If it is used for Blockchain, AI, or Big Data integrations

Then cloud readiness is <strong>high</strong>.

However, if the organization primarily runs monolithic applications with no provision for integrations with modern applications in the private or public cloud, then cloud readiness is <strong>low</strong> and making the transition will be difficult.

![](https://video.udacity-data.com/topher/2020/May/5eb451a4_screen-shot-2020-05-07-at-2.20.49-pm/screen-shot-2020-05-07-at-2.20.49-pm.png)

Similarly, with distributed computing and 3-tier infrastructure, cloud readiness is high if there’s:

* Heavy use of virtualization in the organization
* Management of infrastructure and applications is centralized
* App development is modernized
* The public cloud supports and supplements on-prem infrastructure.

However, if the infrastructure is primarily bare-metal servers with legacy, shrink-wrapped applications, or if the IT organization is disjointed, then cloud readiness is <strong>low</strong>.

![](https://video.udacity-data.com/topher/2020/May/5eb45231_screen-shot-2020-05-07-at-2.21.02-pm/screen-shot-2020-05-07-at-2.21.02-pm.png)

## Legacy IT: The Software Defined Datacenter (SDDC)

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/32.jpg)

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/33.jpg)

### What is The Software Defined Datacenter (SDDC)?

<strong>The idea behind the software defined datacenter, or SDDC, is that everything is implemented in a single layer</strong>.

To put it in more technical terms, an <strong>SDDC</strong> is an integrated abstraction layer that defines a complete datacenter by means of a layer of software that presents the resources of the datacenter as pools of virtual and physical resources and allows their composition into arbitrary user-defined services. A modern SDDC deployment is defined by virtualized, software-defined resources that can be scaled up or down as required and can be deployed as needed in a number of distinct ways.

There are three key components to the SDDC:

* Software defined computing
* Software defined networking
* *Software defined storage

There's also often a fourth layer known as the orchestration management layer. Gartner's John Morency describes it as <strong>"The intelligence that enables the operations team to do the initial configuration in terms of defining the virtual machines, the storage, the network interconnections, and if they need to, support a specific application or set of applications."</strong>

SDDC as a concept began with virtualized compute, and so most enterprises tend to start with that layer as well. Forrester’s Robert Stroud goes so far as to say that software-defined computing is extremely well adopted, but that he is seeing growth in software-defined storage and networking as well.

The automation layer that an SDDC adds facilitates single-pane deployment and management of VMs, network resources, and storage required to provide any service requested by a user. By pooling all datacenter resources, an SDDC converges compute and networking in a software layer that logically spans the entire datacenter. <strong>However, the storage layer remains unvirtualized. It still has a different management plane. It still requires specialized skills to manage the physical network that it’s connected to and the storage devices as well</strong>.

A three-tier software-defined datacenter is close, but it isn’t completely converged.

![](https://video.udacity-data.com/topher/2020/May/5eb453a9_slide-94-what-is-a-software-defined-datacenter/slide-94-what-is-a-software-defined-datacenter.png)

### Management, Automation, and Orchestration

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/34.jpg)

![](https://video.udacity-data.com/topher/2020/May/5eb457ac_slide-98-management-automation-and-orchestration/slide-98-management-automation-and-orchestration.png)

SDDC allows for huge gains in productivity through API-addressable management, automation, and orchestration tools with virtual switches, firewalls, load-balancers, and other devices running on the hypervisor.

These tools provide a number of benefits, including:

* Consolidated infrastructure and user management
* Automated lifecycle management
* Increased security through network segmentation and traffic inspection
* Automatic scale out of VMs on demand
* Failover and failback
* Configuration management
* Automated updates, health checks
* Chargeback for resource usage

### Room for Improvement

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/35.jpg)

![](https://video.udacity-data.com/topher/2020/May/5eb457ce_slide-101-room-for-improvement/slide-101-room-for-improvement.png)

In 3-Tier SDDC implementations the shared storage may be logically pooled, but the devices are still hardware-based, SAN or NAS, and separated from physical servers by a dedicated network. This means that SAN, NAS and the networks supporting them are typically outside the natural SDDC management plane and must be managed separately.

SAN and NAS also scale in big blocks while the rest of the SDDC scales per server. This can lead to huge blocks of storage resources sitting idle for extended periods of time. It doesn’t make sense economically to have such a large mismatch between the way servers and storage need to scale. And finally, 3 Tier SDDC is only 66% converged by design. This means you’re missing a full one-third of the power of SDDC!

### Hybrid Cloud Readiness

![](https://video.udacity-data.com/topher/2020/May/5eb45879_screen-shot-2020-05-07-at-2.50.01-pm/screen-shot-2020-05-07-at-2.50.01-pm.png)

As with legacy IT, an SDDC’s cloud readiness can also be low or high.

Cloud readiness will be <strong>high</strong> if there is:

* Catalog-based self-service available to users
* A DevOps initiative
* Micro-serviced-based application architecture is in use
* Containers are being used for some applications.

Cloud readiness will be <strong>low</strong> if:

* The current SDDC environment is used to run legacy, shrink-wrapped applications exclusively
* The IT staff managing the physical infrastructure is still siloed and segregated based on the 3-tier model




# EXERCISE: LEGACY IT

Your employer, Consolidated BankCorp, is a Boston-based bank and financial services company with 131 branches across the Northeast USA. You have just been acquired by a competitor, AtlanticBank, which will add your assets to the 120 branches already in their portfolio. Your entire executive team recently attended an industry conference where a major national bank presented on their Hybrid Cloud transformation and the myriad benefits that came from the journey. Wendy, your CIO has received a directive from the AtlanticBank CEO to be “Cloud Smart” and use the upcoming merger as an opportunity to modernize Consolidated BankCorp’s IT, reduce costs, and drastically improve the end-user experience for all customers.

As part of this effort, you’ve been asked to visit the Core Banking Application Team at AtlanticBank to discuss their Cloud initiatives and assess how their efforts can be leveraged by your team.

As planned, you set up a time to interview Boris, Director of Core Banking Applications at AtlanticBank and at the appointed time you drive to the bank’s main datacenter in Cambridge. Boris greets you in the lobby and escorts you into the datacenter. You note they are very serious about physical security as you pass through a mantrap which requires a retinal scan to open the second door to the datacenter.

Boris takes you on a tour and shows you their <strong>brand-new IBM z15 multi-frame system</stron>. Boris is proud to tell you the core banking applications he’s responsible for have had <strong>zero unplanned downtime in the 20 years he’s been at the bank</strong>. “We’ve gone through 4 major hardware upgrades and dozens of OS and software upgrades and never missed a beat.” Boris says proudly. You find out after asking a few more questions that <stron>there is a second datacenter with an identical mainframe 25 miles away in Hopkinton</strong>. “What applications are you running that need that kind of horsepower?” You ask. Boris laughs and points out that the core banking application was written in <strong>COBOL</strong>. “It’s a dinosaur in some respects, but it really flies on the new hardware and it’s extremely reliable.”

You’re thinking “COBOL and Cloud, this is going to be interesting.” Boris can see you’re apprehensive and he’s quick to reassure you. “I’ve heard about the Cloud-smart mandate, and don’t worry, we’re ready to help.” He walks you out of the datacenter and into a busy office with dozens of cubicles. “This is the <strong>DevOps team</strong> – <strong>they build our Cloud-native portfolio and helped us modernize most of our legacy applications outside of the core</strong>. We’re a <strong>RedHat OpenShift</strong> shop and we have a <strong>z/OS Cloud Broker</strong> so we’re able to provide back-end services for private or public cloud and still maintain air-tight security for the core.” With the new hardware, we can support 8X the current peak transaction workload and still keep all of the data encrypted.” He laughs. “So, build all the apps you want, we can handle it on the back end.”

“OK I think I’ve got the gist of how you’re handling the core, but where are your <strong>Test/Dev and Production environments running</strong>, for everything else?” You ask. Boris looks at his watch and hands you off to one of the Developers. “This is Nayana, she’ll fill you in on the little box stuff.”

Nayana steers you to a whiteboard wall. “I just ran through this with your Mainframe Team last week”, she says as she starts sketching. “They didn’t seem very happy about the changes we’re pushing. We have a datacenter in the next building and another identical one in Hopkinton. <strong>As of this month, we’re finally 100% virtualized</strong>, mostly on <strong>VMware vSphere</strong> with some <strong>KVM</strong> in the mix. We’re running <strong>OpenShift</strong>, so we’re all in with <strong>Kubernetes</strong> as you probably heard.” You ask about <strong>HCI</strong> but she shakes her head. “We’re looking at it, but right now we’ve got a <strong>standard 3 Tier datacenter, mostly HP servers and network hardware with a mix of HP and NetApp storage</strong>. We just finished standing up our Private Cloud, it’s taken 2 years to get all of the automation and orchestration in place while getting the <strong>self-service catalog built</strong> and enabled at the same time. Plus, we’re going live with our <strong>IBM Public Cloud integration</strong> in 90 days, we’re running OpenShift there as well so we’re using <strong>containers for any new application deployments in the Public Cloud too.”</strong>

You spend the next hour with Nayana and some of her team going over details of the 3 Tier SDDCs and their plans to modernize the AtlanticBank application portfolio. You’re going to have a lot to tell your CIO!

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/36.jpg)




## The Rise of Public Cloud

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/37.jpg)

### Advantages

There are a number of major advantages to the public cloud:

![](https://video.udacity-data.com/topher/2020/June/5ed99599_slide-108-public-cloud-advantages/slide-108-public-cloud-advantages.png)

* It is available <strong>on-demand</strong>.
* When you do need to provision infrastructure it’s all <strong>self-service</strong> and <strong>catalog-based</strong>.
* You can provision infrastructure at <strong>massive scale</strong>.
* Low cost to entry. There’s no hardware cost and you <strong>pay-as-you-go</strong> for utilization.
* High <strong>resilience</strong> and </strong>availability</strong>.

### Disadvantages

Although there are many advantages to the public cloud, it isn’t a cure-all solution; there are several disadvantages you should be aware of.

![](https://video.udacity-data.com/topher/2020/June/5ed99834_slide-109-public-cloud-disdvantages/slide-109-public-cloud-disdvantages.png)

* <strong>Lift and shift</strong>. Moving applications and services to the public cloud is a lift-and-shift effort.
* <strong>Refactoring apps</strong>. Refactoring applications for the cloud requires both skill and a sizable budget.
* <strong>Readiness and Management</strong>. Organizational readiness and infrastructure management may be significant issues for an organization.
* <strong>Expensive for Always-on Apps</strong>. The pay-as-you-go model isn't always a good fit for every workload; always-on, heavyweight applications are expensive to run.
* <strong>Regulatory requirements</strong>. Regulatory requirements can make it difficult to impossible to move forward with a public cloud initiative. Some requirements limit where data can reside, and if you lose control of your cloud or the data stored there, you can incur heavy penalties as a result.

### Where do you use the Public Cloud?

Leveraging the strengths of the Public Cloud means understanding requirements and deploying workloads or services that are a good match. The public cloud is an excellent fit for:

![](https://video.udacity-data.com/topher/2020/June/5ed999fa_slide-110-so-where-do-you-use-the-public-cloud/slide-110-so-where-do-you-use-the-public-cloud.png)

* Dev/Test
* Web servers
* One-off Big Data projects
* Training infrastructure
* Cloud-based anti-spam and anti-virus engines
* CRM platforms
* Email

The key characteristic that all these workloads share is that they are <strong>lightweight</strong> or they <strong>only run for a portion of time</strong>. Since they don’t have to be constantly left on, you don’t have to make investments to support the workloads in your own datacenters.


## Quiz: The Rise of Public Cloud

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/38.jpg)

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/39.jpg)




# EXERCISE: PUBLIC CLOUD

Your CIO Wendy has sent you back to dig a bit deeper into AtlanticBank’s planned integration with <strong>IBM’s Public Cloud</strong>. You’re looking for details about the services they’re wanting to leverage and how it will help them get to a <strong>hybrid model</strong> that reduces cost and improves the customer experience. Your CIO is also interested in any opportunities to use the application modernization effort underway at AtlanticBank as a catalyst to accelerate the Cloud transformation at Consolidated BankCorp. The company execs feel they are behind the curve in a number of areas, especially application modernization. One of the main drivers behind the acquisition of AtlanticBank was their growing reputation as a leader in IT and their success in overhauling an ageing infrastructure while growing the bank’s business significantly.

You once again find yourself sitting down with Nayana and her team to discuss their strategy. “The key to our growth has been a host of remote banking services and <strong>feature-rich apps</strong> that let customers bank from anywhere on any device.” Nayana shows you the personal banking app on her phone. “We’ve also added Web-based mortgage applications with rapid approval, simplified documentation and closings, as well as easy to use loan programs for cars and other consumer goods.” Dexter, the head designer for IOS chimes in. “People love a well-designed app and our reputation as a thoroughly modern bank has created a lot of buzz, brought in a lot of new customers, and increased existing customer loyalty.”

You ask what the IBM Public Cloud integration is going to bring to the table. “That’s how we’re going to scale out development and manage bursts in activity without over-investing in our private infrastructure.” Dexter says. “We can get the same <strong>OpenShift Kubernetes development environment we’re running on our SDDC Cloud</strong> plus the ability to <strong>deploy workloads in containers at scale with the same level of security and compliance</strong>, and it’s IBM so we have the tools we need to support our <strong>z/OS Cloud Broker integration</strong>.” “We need a way to rehome <strong>test and dev</strong> and keep running 100% when we <strong>overhaul our 3 Tier</strong> datacenters next year.” Nayana is quick to add. “This integration gives us a lot of flexibility and a big safety net.”

You leave AtlanticBank with a lot of answers and some ideas about how to jump-start your team’s Cloud Transformation.

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/40.jpg)



## Hyperconverged Infrastructure (HCI)

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/41.jpg)

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/42.jpg)

<strong>Hyperconverged Infrastructure (HCI)</strong> converges the entire datacenter stack, including compute, storage, networking, and virtualization. Some key points to remember about HCI are:

* Software running on each server node distributes all operating functions across a cluster. This allows incremental scaling, so that a cluster can be grown one node at a time; performance increases as the environment grows.
* The software also creates clusters and pools local storage, eliminating the need for SAN or NAS infrastructure​.
* The removal of the physical storage fully unleashes the power of the SDDC.
* The use of solid state drives (SSDs), combined with data locality, provides excellent cluster performance without bottlenecks.

Note that unlike its 3-tier incarnation – which was only 66% converged – HCI is fully converged.

### SSDs and HCI

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/43.jpg)

They key points to remember about SSDs and HCI are:

* SSDs improve performance of the storage tier if they are bottlenecking on read-write performance at the disk level.
* To leverage the extreme advances in performance, the controllers and network need to be able to handle the vast I/O capabilities of SSDs.
* Data locality is a key component of HCI; not having to transit the network provides better utilization of an SSDs capabilities.

### HCI and Private Cloud

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/44.jpg)

Out of the box, HCI isn’t a true private cloud. To have a fully operational private cloud, you also need to have:

* Unified management support
* One-click upgrades
* Customizable security
* Built-in data services for file, block, and object storage
* Sophisticated backup and disaster recovery solutions
* Tools for automation and self-service; and cost governance

### Hybrid Cloud Readiness

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/45.jpg)

Having HCI infrastructure in place will bring you much closer to being hybrid cloud-ready vs. having your infrastructure stack built on legacy IT.

Your cloud readiness will be <strong>high</strong> if:

* A Private Cloud is deployed on the HCI
* There is catalog-based self-service available to users
* There is a DevOps initiative and micro-service-based application architecture is in use
* Containers are being used for some applications,
* The use of the Public Cloud is being considered to supplement the infrastructure where appropriate

In contrast, you can have an HCI deployment but still have <strong>low</strong> cloud readiness if:

* An HCI deployment is being used exclusively to run legacy, shrink-wrapped applications
* Automation and orchestration tools are not being leveraged
* There is no supplemental use of Public Cloud

## Quiz: Hyperconverged Infrastructure (HCI)

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/46.jpg)





# Adaptation as a repository: Andrés R. Bucheli.
