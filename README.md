# NUTANIX

This repository includes the theoretical courses of the Udacity's Hybrid Cloud Engineer Nanodegree Program and the solution of the quizzes and projects.  This material was created with the purpose of self reference.

# HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-

# FIRST COURSE MODERN PRIVATE CLOUD INFRAESTRUCTURE  

# NUTANIX

Nutanix, Inc. is a cloud computing company that sells hyper-converged infrastructure (HCI) software, cloud services (such as Desktops as a service, Disaster Recovery as a service, and cloud monitoring), and software-defined storage.

Nutanix provides an enterprise cloud platform which combines storage, computing, and virtualization for clients. The company's software product families include Acropolis and Prism. In 2015, Nutanix was reported to have built a hypervisor in order to make managing computer infrastructure easier.

# HYPER CONVERGED INFRAESTRUCTURE

Hyper-converged infrastructure (HCI) is a software-defined IT infrastructure that virtualizes all of the elements of conventional "hardware-defined" systems. HCI includes, at a minimum, virtualized computing (a hypervisor), software-defined storage and virtualized networking (software-defined networking). HCI typically runs on commercial off-the-shelf (COTS) servers.

The primary difference between converged infrastructure (CI) and hyper-converged infrastructure is that in HCI, both the storage area network and the underlying storage abstractions are implemented virtually in software (at or via the hypervisor) rather than physically, in hardware. Because all of the software-defined elements are implemented within the context of the hypervisor, management of all resources can be federated (shared) across all instances of a hyper-converged infrastructure.

Nutanix is considered a leader in hyper-converged infrastructure. Nutanix's backers include Lightspeed Venture Partners, Khosla Ventures, and Blumberg Capital.

As of 2020, the company is working to shift to a subscription-based model for billings.

Hyperconvergence evolves away from discrete, hardware-defined systems that are connected and packaged together toward a purely software-defined environment where all functional elements run on commercial, off-the-shelf (COTS) servers, with the convergence of elements enabled by a hypervisor. HCI infrastructures are usually made up of server systems equipped with Direct-Attached Storage (DAS). HCI includes the ability to plug and play into a data-center pool of like systems. All physical data-center resources reside on a single administrative platform for both hardware and software layers. Consolidation of all functional elements at the hypervisor level, together with federated management, eliminates traditional data-center inefficiencies and reduces the total cost of ownership (TCO) for data centers.

The potential impact of the hyper-converged infrastructure is that companies will no longer need to rely on different compute and storage systems, though it is still too early to prove that it can replace storage arrays in all market segments. It is likely to further simplify management and increase resource-utilization rates where it does apply.

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

### Virtual Machine

In computing, a virtual machine (VM) is the virtualization/emulation of a computer system. Virtual machines are based on computer architectures and provide functionality of a physical computer. Their implementations may involve specialized hardware, software, or a combination.

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


________________________________________________________________________________________________________________________________________________________________________________


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

### Hypervisor

A hypervisor (or virtual machine monitor, VMM, virtualizer) is computer software, firmware or hardware that creates and runs virtual machines. A computer on which a hypervisor runs one or more virtual machines is called a host machine, and each virtual machine is called a guest machine. The hypervisor presents the guest operating systems with a virtual operating platform and manages the execution of the guest operating systems. Multiple instances of a variety of operating systems may share the virtualized hardware resources: for example, Linux, Windows, and macOS instances can all run on a single physical x86 machine. This contrasts with operating-system-level virtualization, where all instances (usually called containers) must share a single kernel, though the guest operating systems can differ in user space, such as different Linux distributions with the same kernel.

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

## Quiz - SSDs

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/47.jpg)



# Exercise: Hyperconverged Infrastructure (HCI)

It’s a Monday and you find yourself back at AtlanticBank, this time to discuss their planned <strong>SDDC</strong> upgrade. Nayana and Boris have introduced you to Kelly, their Principal Architect and the person in charge of the Cambridge and Hopkinton datacenters. She looks a bit anxious.

“We just finished a 3-year financial lookback analysis and we’re way in the red on <strong>total cost of ownership (TCO)</strong> and definitely not getting our expected <strong>return on investment (ROI)</strong> from the current infrastructure, even with the level of automation we have. We really need to <strong>reduce costs, Capex and Opex</strong> or our <strong>Private Cloud</strong>expansion is in trouble, and that means our plans for Hybrid Cloud are in trouble too.” This sounds familiar, you had the same experience last year when you did the same analysis. You may be way behind AtlanticBank when it comes to modernizing your applications, but you did manage to migrate your main datacenter <strong>from 3 Tier to HCI</strong> last year and the savings have been substantial.

You share some of the results including a <strong>60% reduction in overall operating costs due to savings on infrastructure</strong> (no SAN or NAS) and going from 125 racks to 20 with corresponding savings on space, power and cooling. You also had an <strong>80% decrease in unplanned downtime</strong> due to the architecture being designed for high availability. “Everything is just so much easier. Implementation, incremental scaling, provisioning, management.” You have their attention. “If we could take what you’ve built on your 3 Tier platform and migrate it to HCI we’d have the best of both worlds and you’d finally be able to control everything from a single management plane.” Kelly is a bit skeptical, but a plan is already forming in your mind. “Let’s look at the portfolio of applications and your Test/Dev environment and see what it would look like if we stood up your Private Cloud on HCI vs. 3 Tier. What have we got to lose?”

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/48.jpg)



## Hybrid Cloud: When To Use It And When Not To

### When Not to Use the Hybrid Cloud

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/49.jpg)

Remember, hybrid cloud <strong>is not a good fit</strong> when:

* A business has non-portable applications
* Security and regulatory compliance requirements do not allow public cloud exposure
* Delegation of management responsibilities to a service provider is not allowed
* The Public Cloud is too expensive

For businesses born in the public cloud, a hybrid cloud does not make sense without the ability to invest in private, on-premises infrastructure, a supporting operations team, and ongoing skill growth.

### When to Use the Hybrid Cloud

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/50.jpg)

Examples of where the hybrid cloud <strong>is a good fit</strong> are:

* Workloads with constantly changing populations
* Large scale workload management
* Short-lived ephemeral workloads
* Dev/Test
* Training infrastructure
* Anti-spam and anti-virus engines
* CRM platforms
* E-mail
* Web servers
* One-off big data projects

## Cloud Smart Examples

You can find the three examples we just discussed below, for your reference. Once you've had a chance to think over the examples, have a look at the quiz at the bottom of the page.

### A Data Processing Firm

This data processing firm had strict governance requirements that their customer data remain on-premises, so they had a private cloud hosting their data lake of customer data. However, they wanted to burst compute capacity for large end-of-the-month, quarterly, and annual reporting. So, they provided a virtual private network between their public and private clouds.

This allowed them to spin up and scale out analytics with high memory and GPU-accelerated public cloud infrastructure, save the results back on-prem, and then shut-down the analytics workloads. Because of the shared data, their analytics is a hybrid cloud application, even though the workload mainly runs in the public cloud.

![](https://video.udacity-data.com/topher/2020/June/5ee17f73_slide-142-a-data-processing-firm/slide-142-a-data-processing-firm.png)

### A Retail Outlet Business

This retail outlet business with many remote locations had local services (file and print sharing) in each store, but it used private networks to its private cloud datacenter for virtual desktops. This is how the IT organization has slowly modernized its infrastructure at the edge and in the datacenter.

A new initiative for a data lake with analytics kicked off and a team with skillsets favoring the public cloud got their project up and running quickly. The organization is running with both public and private infrastructure. None of the applications or data are shared though, so each cloud is a silo, and it is not a hybrid cloud model.

![](https://video.udacity-data.com/topher/2020/June/5ee17f97_slide-143-a-retail-outlet-business/slide-143-a-retail-outlet-business.png)

### An E-Commerce Company

This e-commerce company has a large inventory and customer database that they keep on-prem. They backup this database to the public cloud, but this is hybrid cloud storage use. If you’re wondering why, it’s because they operate the database application on-prem, and back-up the database itself to the public cloud. So, true to the hybrid model, there’s some sharing going on here.

Their developers use multiple public cloud compute for rapid and short-lived test workloads. This means they’re using multiple public clouds in a cloud-smart manner, but no data or applications are shared. This makes each public cloud a silo and it is not hybrid cloud use. Finally, they operate their web tier by load balancing across on-prem web servers and public cloud web servers, which is a hybrid cloud web tier.

![](https://video.udacity-data.com/topher/2020/June/5ee17fb3_slide-144-an-e-commerce-company/slide-144-an-e-commerce-company.png)

### What do these examples demonstrate?

Ultimately, to be truly hybrid is to not have silos. But it’s also possible – as the e-commerce company illustrated – to be cloud-smart and not hybrid. Workloads that were the right fit for the public cloud were on the public cloud, and those that needed to be shared between on-prem and public were.

What matters is the best fit. Where a workload belongs is where it should be, based entirely on what’s best for the business.

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/51.jpg)

## Gathering and Analyzing Business Requirements

### Laying your Foundation: Gathering and Analyzing Business Requirements}

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/52.jpg)

Throughout this lesson, we’ve talked a lot about best fit—and insuring a good fit requires talking to your stakeholders. This will give you a 360-degree view of the workloads and services you need to support.

When you’re having that discussion, it’s important to structure the conversation around 8 major requirements:

* Application portability
* Compliance and security
* Cost, including TCO and ROI
* Scalability
* Resilience and availability
* Performance
* Manageability
* Data protection and recoverability

Let’s look at each of these requirements in a little more detail.

### Deeper Dive: Application Portability

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/53.jpg)


<strong>Application portability</strong> describes how easily an application can be moved between different kinds of infrastructure.

* Applications that are designed with portability in mind (e.g., containerized applications) do not require major refactoring in order to move from private to public cloud providers.

* In contrast, monolithic applications require an expensive “lift and shift” process in order to move between different platforms or even to change hypervisors.

* Another approach is to employ a data-centric strategy, where you share data between services running on multiple cloud platforms without porting applications between them. This avoids "lift and shift" campaigns and leverages applications designed to take advantage of native infrastructure and toolsets.

### Deeper Dive: Compliance and Security

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/54.jpg)

Companies are subject to many regulations regarding security and data-handling—and these regulations can have a significant impact on how you utilize the cloud. These are some of the main regulations that it’s important to be familiar with:

<strong>GDPR:</strong> The General Data Protection Regulation (GDPR) protects EU citizens from data breaches and misuse. It applies to all companies with data for EU citizens, even if those companies are not located in the EU.

<strong>HIPAA:</strong> The Health Insurance Portability and Accountability Act (HIPAA) regulates the data security of healthcare patients. Companies that handle healthcare data (e.g., hospitals, clinics and insurance companies) are required to comply with HIPAA regulations.

<strong>Sarbanes-Oxley Act (SOX):</strong> The Sarbanes-Oxley Act (SOX) requires U.S. company boards, management, and accounting firms to follow best practices and maintain financial records for seven years. The intent is to prevent incidents like the Enron scandal.

<strong>FISMA:</strong> The Federal Information Security Management Act of 2002 (FISMA) treats information security as a matter of national security. All federal agencies are required to develop compliant data protection methods.

<strong>PCI-DSS:</strong> The Payment Card Industry Data Security Standard (PCI-DSS) regulations reduce fraud by protecting customer credit card information. PCI-DSS compliance is required for all companies handling credit card information.

<strong>GPG13:</strong> The Protective Monitoring for HMG ICT Systems regulation (GPG13) is a U.K. general data-protection regulation for business processes. It is compulsory for businesses managing high-impact data.

### Deeper Dive: Cost (TCO and ROI)

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/55.jpg)

When comparing the public cloud with on-prem hybrid cloud infrastructure, it's important to consider the <strong>Total Cost of Ownership (TCO)</strong> and <strong>Return on Investment (ROI).</strong>

* Because public cloud infrastructure is rented (not owned), it has no upfront capital cost—and can thus seem better than investing in on-prem hybrid cloud infrastructure.
* However, the public cloud requires significantly more operating expenditure; thus, despite the higher up-front costs, the hybrid cloud can have significantly better long-term TCO and ROI.

### Deeper Dive: Scalability

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/56.jpg)

The need to scale an application or the resources supporting an application up/out can be driven by:

* An increasing number of users
* Increased demand from existing users
* A growing data set
* Increased computational complexity

In addition, many workloads are cyclical, requiring the ability to <strong>scale up/out during periods of high demand and pull back during periods of low demand</strong>. Monolithic applications require different scale up/out strategies than modular or micro-service-based applications. If application design and other requirements permit, it is possible to have individual application components or application tiers <strong>running on Private and Public Cloud simultaneously</strong>.

When you need to decide on a scaling strategy, it’s important to consider:

* The application architecture. Is it legacy-monolithic, multi-tier, modular, or micro-services based?
* What the triggers points for scaling up or scaling out are?
* Seasonality and complete demand cycles

## Deeper Dive: Resilience and Availability

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/57.jpg)

Applications need to be designed for <strong>resiliency</strong>, meaning that <strong>they can suffer a failure or degradation in one or more components and still provide service</strong>.

* Applications must take the infrastructure providing resources into account.
* Many organizations implement software across multi-tier, multiple technology infrastructures, which can make designing for resilience more complicated.
* Resilience can be provided at any or every layer of the stack.

<strong>Resilience goes hand-in-hand with availability</strong>, but availability requirements need to be clearly defined.

* For example, hardware or operating system availability does not necessarily translate to application availability.
* It’s common to underestimate the cost and complexity of providing availability, as well as overstate availability requirements.
* Understanding what’s required is critical to determining the right infrastructure for a given workload or service.

## Deeper Dive: Performance

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/58.jpg)

<strong>Performance</strong> has many dimensions and dependencies, and this portion of the stakeholder conversation will likely result in a large variety of requirements. You’re likely to hear about <strong>application response times, storage performance, CPU and memory requirements for workloads, and so on</strong>.

When rolling in performance data, it’s important to be mindful of the breadth and complexity of this particular requirement. For example, <strong>application response time can be influenced by network architecture, CPU type, storage architecture, or memory type</strong>. In a multi-tenant environment, CPU saturation, storage contention, or memory oversubscription can degrade performance.

Deploying multi-tiered applications requires <strong>careful planning, especially if the infrastructure is hybrid</strong>. In the case of multi-tiered applications, <strong>performance will only be as good as the least performant tier</strong>.

## Deeper Dive: Manageability

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/59.jpg)

Infrastructure and application <strong>manageability</strong> is greatly influenced by tool integrations and the availability of automation for routine and repetitive tasks.

<strong>Lack of manageability can drastically increase OPEX and degrade performance of a Private Cloud</strong>. It is especially detrimental in Hybrid Cloud deployments when tasks such as updates, troubleshooting, and scaling are delayed or fail outright.

<strong>It’s also important to consider the relative complexity of a workload from the perspective of manageability. Does it need to be on-prem because every aspect needs to be managed, or can a provider be trusted to manage a part of it?</strong>

When gathering requirements and planning your strategy, remember that <strong>a well-designed management plan show allow for SLAs to be met and monitored, in order to verify performance</strong>.

## Deeper Dive: Data Protection and Recoverability

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/60.jpg)

<strong>Every application or service will have specific requirements for data protection and recoverability</strong>. At a minimum, you should determine and document the requirements for each application and service in terms of:

* <strong>The Recovery Time Objective (RTO)</strong>, which refers to how long an application can be down without causing damage to the business
* <strong>The Recovery Point Objective (RPO)</strong>, which refers to how much data can be lost before damage to the business occurs.

100% uptime (RTO) with no lost data (RPO) requires an investment in continuous data replication and mirrored infrastructure, but not every application or service will require this level of protection. When 100% uptime requirements or zero data loss requirements do exist, <strong>cloud-based options for backup and recovery can provide low-cost alternatives</strong>.

## Turning Business Requirements into SLAs

Once you have the answers to all of your questions, you’ll have the framework and requirements of your solution. You will also have successfully mapped out the attributes of your required solution to specific business needs.

![](https://video.udacity-data.com/topher/2020/May/5eb476bf_slide-175-turning-business-requirements-into-slas/slide-175-turning-business-requirements-into-slas.png)

Taking these attributes and turning them into SLAs will provide a performance framework that can be monitored, managed, and enforced. <stron>These attributes and SLAs will also help with vendor evaluation</strong>. You’ll have a checklist you can use to determine whether a solution provider can meet your needs and at what cost.

If modifications are needed to any aspect of the requirements, you can perform a cost-benefit analysis, determine the impact, and move forward with whatever is best for the business.

## Lesson Recap

![](https://video.udacity-data.com/topher/2020/June/5eecfa4b_screen-shot-2020-06-19-at-1.47.21-pm/screen-shot-2020-06-19-at-1.47.21-pm.png)

In this lesson, we covered:

* What the role of a Hybrid Cloud Engineer is

* The different models to support various Cloud initiatives

* The Engineer’s role in Service Level Agreements related to Cloud apps

* How to choose the optimal Cloud platform for an app, based on business requirements and SLAs


________________________________________________________________________________________________________________________________________________________________________________


# LESSON 3 INTRODUCTION TO NUTANIX HCI (Hyper Converged Infraestructure)


## Lesson Overview

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/61.jpg)

![](https://video.udacity-data.com/topher/2020/June/5eecfaa1_screen-shot-2020-06-19-at-1.49.11-pm/screen-shot-2020-06-19-at-1.49.11-pm.png)

In this lesson, we're going to introduce you to the Nutanix HCI by going over the following:

* The what and why of Nutanix HCI
* The components of a cluster
* The software components of a Nutanix cluster
* How to work with the Prism interface

## Why Nutanix HCI?

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/62.jpg)

### Quick Review of the Legacy Infrastructure

There are a few reasons legacy infrastructure is not well suited to meet the increasing requirements of enterprise applications or the fast pace of modern business:

* The silos created by traditional infrastructure have become a barrier to change and progress, adding complexity to every step of the IT process from ordering to deployment to management.

* <strong>New business initiatives require cooperation from multiple teams</strong>. <strong>They also need organizations to predict IT infrastructure 3 to 5 years in advance</strong>. For context, this is pretty hard to get right.

* Vendor lock-in and rising licensing costs are significantly increasing budgets.

HCI addresses these pain points by combining standard datacenter hardware using locally attached storage resources with intelligent software to create flexible building blocks. These flexible building blocks can replace legacy infrastructure with separate servers, storage networks, and storage arrays.

### Benefits of the Nutanix HCI

![](https://video.udacity-data.com/topher/2020/May/5eb47a84_screen-shot-2020-05-07-at-5.15.25-pm/screen-shot-2020-05-07-at-5.15.25-pm.png)

Nutanix provides the public cloud benefits that organizations want <strong>with the control that they need on-prem</strong>. There are six major benefits to Nutanix HCI specifically:

* <strong>Full-cloud:</strong> It’s a full-cloud stack that integrates all compute, storage, virtualization, and networking resources to run any application.

* <strong>One-click simplicity:</strong> This entire stack is managed via a single pane of glass that streamlines IT lifecycle management and makes hybrid and multi-cloud management easy .

* <strong>Deployed in minutes:</strong> The applications themselves can be deployed in minutes, instead of weeks or months. This is true for new infrastructure as well.

* <strong>Automation application management:</strong> Application management can also be automated, along with other common IT tasks. Application owners and developers can also be given on-demand IT services.

* <strong>Lower cloud costs:</strong> You can also reduce your datacenter TCO by up to 60%. This will help optimize your public cloud spend with lower cloud costs.

* <strong>True hybrid cloud:</strong> This refers to the ability for you to combine both public and private cloud operations with unified management.

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/63.jpg)

## What is Nutanix HCI?

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/64.jpg)

![](https://video.udacity-data.com/topher/2020/June/5ed6e59c_nutanix-software-components-graphics/nutanix-software-components-graphics.png)

Nutanix HCI is fully <strong>software-defined</strong>, which is required from a true HCI solution. This means that the intelligence of the solution comes from the software, which runs on a variety of hardware platforms.

There are two key components to the software:

* <strong>Acropolis:</strong> The data plane
* <strong>Prism:</strong> The management plane

### Data Plane

The data plane is the part of the software that processes the data requests. By contrast, the control plane is the part of the software that configures and shuts down the data plane.

The conceptual separation of the data plane from the control plane has been done for years. An early example is Unix, where the basic file operations are open, close for the control plane and read, write for the data plane.

### Management Plane

In computer networking, the management plane of a networking device is the element of a system that configures, monitors, and provides management, monitoring and configuration services to, all layers of the network stack and other parts of the system. It should be distinguished from the control plane, which is primarily concerned with routing table and forwarding information base computation.

In system diagrams, the management plane is typically shown in three dimensions as overlapping the network stack, separated by a dimension that delineates the power plane, data plane, control plane and management plane.

This software can be run on a number of different servers, from manufacturers such as <strong>Dell, Lenovo, HPE, Cisco, IBM, Inspur, and so on</strong>. In general, the hardware platforms themselves are structured as <strong>nodes, blocks, and clusters</strong>.

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/65.jpg)

## Hardware Components: Nodes, Blocks, and Clusters

![](https://video.udacity-data.com/topher/2020/May/5eb47ca4_screen-shot-2020-05-07-at-5.24.41-pm/screen-shot-2020-05-07-at-5.24.41-pm.png)

A <strong>node</strong> is an x86 server with compute and storage resources. A single Nutanix cluster can have an unlimited number of nodes. <strong>Different hardware platforms are available to address varying workload needs for compute and storage</strong>.

### x86 Architecture:

The x86 architecture is an instruction set architecture (ISA) series for computer processors. Developed by Intel Corporation, x86 architecture defines how a processor handles and executes different instructions passed from the operating system (OS) and software programs.

The “x” in x86 denotes ISA version.

Designed in 1978, x86 architecture was one of the first ISAs for microprocessor-based computing. Key features include:
Provides a logical framework for executing instructions through a processor
Allows software programs and instructions to run on any processor in the Intel 8086 family
Provides procedures for utilizing and managing the hardware components of a central processing unit (CPU)
The x86 architecture primarily handles programmatic functions and provides services, such as memory addressing, software and hardware interrupt handling, data type, registers and input/output (I/O) management.

Classified by bit amount, the x86 architecture is implemented in multiple microprocessors, including 8086, 80286, 80386, Core 2, Atom and the Pentium series. Additionally, other microprocessor manufacturers, like AMD and VIA Technologies, have adopted the x86 architecture.

### Each node in the cluster:

* Runs a standard hypervisor
* Contains processors, memory, and local storage such as SSDs and hard disks.
* A Nutanix Controller VM that enables the pooling of local storage from all nodes in the cluster.

All nodes in a Nutanix cluster converge to deliver a unified pool of tiered storage and present resources to VMs for seamless access. <strong>A global data system architecture integrates each new node into the cluster, allowing you to scale the solution to meet the needs of your infrastructure</strong>.

A <strong>block</strong> is a chassis that holds one to four nodes, and contains power, cooling, and the backplane for the nodes. <strong>The number of nodes and drives depends on the hardware chosen for the solution</strong>.

A <strong>cluster</strong> is a collection of multiple blocks. It refers to the physical servers, logically associated with one another, that deliver a unified pool of infrastructure resources. It can handle the failure of a single node when specific cluster conditions are met. In the case where multiple nodes in a block fail, guest VMs can continue to run because cluster configuration data has been replicated on other blocks.

### A Sample Block

![](https://video.udacity-data.com/topher/2020/May/5eb47cd4_slide-12-sample-block/slide-12-sample-block.png)

This graphic shows a 4-node block in which each node takes up one node position identified as A, B, C, or D. In this block chassis example, the node ports are accessible from the rear of the chassis and the storage is at the front. A Nutanix block is a rack-mountable enclosure that contains one to four Nutanix nodes. It can handle the failure of a single node when specific cluster conditions are met. In the case where multiple nodes in a block fail, guest VMs can continue to run because cluster configuration data has been replicated on other blocks.

### Sample Cluster

![](https://video.udacity-data.com/topher/2020/May/5eb47d93_slide-13-sample-cluster/slide-13-sample-cluster.png)

What you see here is a visualization of a cluster, with both its physical and logical components highlighted. This particular example contains three nodes, each of which has a controller VM, locally attached storage, and has guest VMs running. All of the locally attached storage is presented as a single pool to the guest VMs, via the Controller VM.

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/66.jpg)

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/67.jpg)

## Software Components: Acropolis

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/68.jpg)

<strong>Acropolis</strong> is a distributed data plane for either VMs or container-based applications that <strong>runs across a cluster of nodes delivering enterprise storage and virtualization services</strong>. <strong>Acropolis is also the foundation of an HCI solution that transforms HCI into a Hybrid Cloud OS</strong>.

Here are the main components:

* The Distributed Storage Fabric (DSF)
* The Acropolis Hypervisor (AHV)
* Scale-out storage services
* Advanced virtual networking

Let's take a look at each of these below!

## Acropolis: Distributed Storage Fabric

### SCSI CONTROLLER

A SCSI controller, also called a host bus adapter (HBA), is a card or chip that allows a Small Computer System Interface (SCSI) storage device to communicate with the operating system across a SCSI bus.

### CVM

“Nutanix Controller VM (CVM) is what runs the Nutanix software and serves all of the I/O operations for the hypervisor and all VMs running on that host.” Nutanix-bible.

The Controller VM recourses are shown under the VM page In the Nutanix Prism, but you will not be able to change the resources configuration, unless you connected to the Acropolis hypervisor (Host) and modified the configurations using virsh.

![](https://video.udacity-data.com/topher/2020/May/5eb47f70_slide-19-distributed-storage-fabric/slide-19-distributed-storage-fabric.png)

Here is a representation of the <strong>Distributed Storage Fabric (DSF)</strong>. The DSF simplifies storage and data management for virtual environments, by pooling flash and hard disk drive storage across a Nutanix cluster and exporting it as a data store to the virtualization layer as <strong>Small Computer Systems Interface (iSCSI)</strong>, <strong>Network File System (NFS)</strong>, and </strong>Server Message Block (SMB)</strong> which are all different ways of data sharing.

DSF offer capabilities:

* Snapshots
* Compression
* Cloning
* Data locality
* Deduplication
* Erasure coding
* Tiering
* Replication
* Reflect

### Acropolis: AHV

### PCI Passthrough

PCI passthrough allows guests to have exclusive access to PCI devices for a range of tasks. PCI passthrough allows PCI devices to appear and behave as if they were physically attached to the guest operating system.

### PCI Device

A PCI device is any piece of computer hardware that plugs directly into a PCI slot on a computer’s motherboard. PCI, which stands for Peripheral Component Interconnect, was introduced to personal computers by the Intel Corporation in 1993.

![](https://video.udacity-data.com/topher/2020/May/5eb47fb4_slide-22-ahv/slide-22-ahv.png)

Acropolis Hypervisor (or AHV) is a comprehensive virtualization solution that’s included as part of the Nutanix solution, bundled with Acropolis.

AHV is the virtualization layer in the illustration example. It enables a variety of key capabilities including:

* Backup
* Disaster recovery
* Host and VM high availability
* Dynamic scheduling

### Acropolis: Scale-out Storage Services

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/69.jpg)

### SMB 2.1

In computer networking, Server Message Block (SMB), one version of which was also known as Common Internet File System (CIFS /sɪfs/), is a communication protocol for providing shared access to files, printers, and serial ports between nodes on a network. It also provides an authenticated inter-process communication mechanism. Most usage of SMB involves computers running Microsoft Windows, where it was known as "Microsoft Windows Network" before the introduction of Active Directory. Corresponding Windows services are LAN Manager Server for the server component, and LAN Manager Workstation for the client component.

SMB 2.1, introduced with Windows 7 and Server 2008 R2, introduced minor performance enhancements with a new opportunistic locking mechanism.

### NFS

Network File System (NFS) is a distributed file system protocol originally developed by Sun Microsystems (Sun) in 1984, allowing a user on a client computer to access files over a computer network much like local storage is accessed. NFS, like many other protocols, builds on the Open Network Computing Remote Procedure Call (ONC RPC) system. NFS is an open standard defined in a Request for Comments (RFC), allowing anyone to implement the protocoL.

### S3 Compatible REST API 

Representational state transfer (REST) is a de-facto standard for a software architecture for interactive applications that typically use multiple Web services. In order to be used in a REST-based application, a Web Service needs to meet certain constraints; such a Web Service is called RESTful. A RESTful Web service is required to provide an application access to its Web resources in a textual representation and support reading and modification of them with a stateless protocol and a predefined set of operations. By being RESTfull, Web Services provide interoperability between the computer systems on the internet that provide these services. REST offers an alternative to, for instance, SOAP as method of access to a Web Service.

Nutanix allows you leverage scale-out, fully software-defined storage services via <strong>Nutanix Files, Nutanix Volumes, and Nutanix Objects</strong>.

* Nutanix Files file services provides <strong>access to Microsoft Windows via SMB 2.1 and to Linux and Unix via the NFS v4 protocol</strong>. It also scales and load balances multiple nodes in the cluster, growing capacity and performance as needed.

* Nutanix Volumes block services provides iSCSI access to applications that require direct access to block storage. This can be non-virtualized systems, or virtual machines with specific requirements. <strong>Volumes uses the DSF to scale I/O across the entire cluster and can load balance and accelerate specified Volume Groups</strong>.

* Nutanix Buckets object storage services is a software-defined object storage solution that <strong>non-disruptively scales out while lowering overall costs</strong>. It supports an <strong>industry-standard S3-compatible REST API</strong> to handle petabytes of unstructured data.

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/70.jpg)

### Acropolis: Virtual Networking

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/71.jpg)

Nutanix Flow:

* Delivers advanced networking and security services, providing visibility into the virtual network, application-centric protection from network threats and automation of common networking operations.

* Allows organizations to deploy <strong>software-defined virtual networking</strong> without having to install and manage additional products that have separate management and independent software maintenance requirements.

* Provides detailed visualization of communications between VMs, making it simple and straight-forward to set the right policies for the environment.

* Micro-segmentation provides granular control and governance of all traffic into and out of a VM, or groups of VMs. It ensures that only permitted traffic between application tiers or other logical boundaries is allowed and protects against advanced threats propagating within the virtual environment.

* Provides API-based notifications enabling third-party network devices to observe VM lifecycle events, such as the instantiation of a new VM into the Nutanix environment.

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/72.jpg)

## Software Components: Prism

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/73.jpg)

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/74.jpg)

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/75.jpg)

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/76.jpg)

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/77.jpg)

![](https://video.udacity-data.com/topher/2020/May/5eb48262_prism-home-dashboard/prism-home-dashboard.png)

This is Prism, the single dashboard from which you can manage your entire Nutanix solution.

<strong>Prism</strong> is a distributed management plane that uses advanced data analytics and heuristics to simplify and streamline common workflows, eliminating the need for separate management solutions for servers, storage networks, storage, and virtualization. It provides a <strong>unified management interface</strong> that can generate actionable insights for optimizing virtualization, provides infrastructure management and everyday operations.

In Prism, Nutanix administrators can easily manage and operate their end-to-end virtual environments.

Just as Acropolis creates a data plane that spans the entire cluster for performance and resiliency, Prism creates the same resiliency for management and operational intelligence.

The information in Prism focuses on common operational tasks grouped into four areas:

* Infrastructure management
* Operational insight
* Capacity planning
* Performance monitoring

We’ll discuss each of these in more detail when we cover managing a Nutanix cluster.

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/78.jpg)

## Exercise: Logging Into Prism

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/79.jpg)

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/80.jpg)

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/81.jpg)

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/82.jpg)

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/83.jpg)

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/84.jpg)


## Prism - Infrastructure Management: Cluster Management

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/85.jpg)

### Four Common Operational Areas

* Infrastructure Management
* Operational Insight
* Capacity Planning
* Performance Monitoring

### The Prism Home Dashboard

![](https://video.udacity-data.com/topher/2020/May/5eb483d0_prism-home-dashboard/prism-home-dashboard.png)

<strong>Infrastructure management</strong> refers to cluster management, upgrades, storage management, virtual machine management, networking, data protection, entity management, user management, localization, and a handful of other key features.

<strong>Cluster management</strong> refers the overall view of your entire cluster that you see on the Prism home screen.

The Home dashboard is a summary overview of your Nutanix cluster:

* A count of blocks and hosts with model numbers
* A summary of storage
* VMs
* Hardware
* Cluster-wide controller IOPS
* Latency
* CPU usage
* Memory usage
* Alerts and events

### Infrastructure Management

![](https://video.udacity-data.com/topher/2020/May/5eb48d86_prism-home-drop-down/prism-home-drop-down.png)

There are a lot of different dashboard available to you here depending on what type of information you'll need. We'll go through some of these dashboards during the course, but here's an opportunity to see what the options are. The Home drop down menu has a number of dashboards you can explore, each tailored around providing details on a specific area of your cluster.

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/86.jpg)

## Prism - Infrastructure Management: Storage Management

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/87.jpg)

### IOPS

Input/output operations per second (IOPS, pronounced eye-ops) is an input/output performance measurement used to characterize computer storage devices like hard disk drives (HDD), solid state drives (SSD), and storage area networks (SAN). Like benchmarks, IOPS numbers published by storage device manufacturers do not directly relate to real-world application performance.

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/88.jpg)

### GiB

When purchasing disk drives, 1 GB is often defined as 1,000,000,000 bytes. However, when viewed by an operating system, the capacity displayed is often less than this. For example, a new 1 TB hard drive would be reported by the OS as 931 GB (this is 931 GiB). GiB (Gibibytes) is a standard unit used in the field of data processing and transmission and is defined as base 1024 rather than base 1000.

For example, 1 GB is defined as 1000³ bytes, whereas 1 GiB is defined as 1024³ bytes.

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/89.jpg)

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/90.jpg)

### Storage Dashboard: Overview

![](https://video.udacity-data.com/topher/2020/May/5eb48e38_storage-dashboard-overview/storage-dashboard-overview.png)

The image above is the Overview display of the Storage dashboard. The Storage dashboard view shows you an overview of the storage environment, important performance charts, data reduction metrics, capacity summaries, and important alerts and warnings. If an administrator needs more details about certain storage services, then they can use the table view.

This screen provides three views that offer insight into the storage constructs within a cluster:

* Volume groups
* Containers
* Storage pools

The table view displays the configuration settings for each container, capacity metrics, and several performance charts.

### Storage Dashboard: Diagram View

![](https://video.udacity-data.com/topher/2020/May/5eb48ede_storage-dashboard-diagram-view/storage-dashboard-diagram-view.png)

### Storage Dashboard: Table View

![](https://video.udacity-data.com/topher/2020/May/5eb48f08_storage-dashboard-table-view/storage-dashboard-table-view.png)

The different views of the Storage dashboard are fundamentally the same, each view allows you to interact with and drill down into various components in different ways. The table view puts the storage containers, volume groups, and storage pools front and center. It provides a number of details at a glance about each of these components:

* Controller IOPS, total capacity, free and used capacity, status of various space optimization features, and more.
* Usage and performance summaries, as well as storage alerts and events.

The information you need from the Storage dashboard will determine which view you'll use and interact with.

### Creating Storage Containers and Volume Groups

![](https://video.udacity-data.com/topher/2020/May/5eb48f64_screen-shot-2020-05-07-at-6.44.43-pm/screen-shot-2020-05-07-at-6.44.43-pm.png)

From the Storage dashboard, you can also create new Storage Containers and new Volume Groups by filling in details in a simple form based on your requirements.

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/91.jpg)

## Exercise: Using Prism Dashboard

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/92.jpg)

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/93.jpg)

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/94.jpg)

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/95.jpg)

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/96.jpg)

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/97.jpg)

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/98.jpg)

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/99.jpg)

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/100.jpg)

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/101.jpg)

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/102.jpg)

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/103.jpg)

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/104.jpg)

## Prism - Infrastructure Mgmt.: Virtual Machine Management

### VM Dashboard: Table View

![](https://video.udacity-data.com/topher/2020/May/5eb49028_vm-dashboard-overview/vm-dashboard-overview.png)

The VM Dashboard provides the same kind of overview summary that the cluster and storage management views offer.

* The VM summary delivers VM counts as well as VM power status.
* Highlighted CPU and memory usage statistics focus on provisioned amounts versus reserved amounts.
* You can also see the top VM consumers for IOPS, latency, memory usage, and CPU usage, enabling you to identify which VMs are using the most resources and detect any outliers.

### VM Dashboard: Table View

![](https://video.udacity-data.com/topher/2020/May/5eb490bb_vm-dashboard-table-view/vm-dashboard-table-view.png)

Following the user experience in the other sections, the VM-focused view in Prism also offers a table-based layout for VM management. Similar to the detailed host data in the cluster view, the VM-based view provides a greater number of VM-focused data points.

This VM-focused view allows organizations to easily compare the CPU and memory settings configured versus the actual amounts of CPU and memory used. You can also access storage metrics for read versus write IOPS, combined IOPS, storage bandwidth, and latency. Prism tracks each of these data points on a per-VM basis to give a quick overview and locate potential issues faster.

### Creating a VM

![](https://video.udacity-data.com/topher/2020/May/5eb49185_create-vm/create-vm.png)

Similar to creating Storage Containers and Volume Groups, creating a Virtual Machine is also a simple process – you need to fill out a form that requires CPU, memory, disk, network adapter, and host affinity information. After that, clicking Save will create your VM.

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/105.jpg)

## Prism - Infrastructure Management: Data Protection

### Remote Site

After you have created a local site, you can then associate a remote site for deployment. A remote site can either be on a server that is on the local network (using a mapped drive) or on another server on the Internet (using FTP).

### protection domain 

A set of access privileges to protected resources. Where many processes coexist, each process having differing access permission to a number of protected resources via some form of key, it may be convenient to group together a set of such keys in order to provide a single process with access to the resources that it requires. Access control can then be manipulated independent of the processes concerned. The protection domain is either the set of keys, or equivalently, the set of resources to which the keys give access.

![](https://video.udacity-data.com/topher/2020/May/5eb49288_data-protection-dashboard-overview/data-protection-dashboard-overview.png)

While there are many other dashboards in Prism, the last one we’ll talk about in this section is the Data Protection dashboard. The data protection overview summarizes the number of remote sites and protection domains, giving you a quick look into the cluster’s data protection. Charts report replication data transfer bandwidth, as well as a list of the top remote sites by bandwidth consumption. This report lets an organization easily understand the bandwidth that replication is consuming, whether something is operating abnormally, and which sites use the most resources. Administrators also gain awareness of ongoing replication, pending replication, and successful replication tasks, so they can recognize if any tasks are being held up or simply verify that replication is completing successfully.

### Data Protection Dashboard: Table View

![](https://video.udacity-data.com/topher/2020/May/5eb492d8_data-protection-dashboard-table-view/data-protection-dashboard-table-view.png)

The data protection table view summarizes the configuration, performance, and status of the protection domains that provide backup and disaster protection in your cluster. From this view you can see how many resources each protection domain consumes, what is contained within a protection domain, when taking a snapshot was last successful, and if there are any pending jobs. When you select a specific protection domain or remote site, a greater amount of data becomes available through additional charts and tables. These entity-specific data points provide extensive details on the contents, schedules, alerts, and metrics for each item.

### Creating Protection Domains and Remote Sites

![](https://video.udacity-data.com/topher/2020/May/5eb49326_screen-shot-2020-05-07-at-7.00.23-pm/screen-shot-2020-05-07-at-7.00.23-pm.png)

Again, creating protection domains and remote sites involves filling a form with details, after which both entities will be created for you. A protection domain is a set of policies that govern the local backup and remote replication functions for one or more VMs. A schedule attached to each protection domain controls the rate at which snapshots are taken and how long they are retained. This architecture allows you to create protection domains that can protect either a single VM or groups of VMs. The flexibility to use multiple protection domains within a cluster means that you can create different policies to protect diverse applications and groups of VMs, and control replication to different sites and clusters.

## Prism - Managing a Nutanix Cluster: Operational Insights

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/106.jpg)

The second of the four key areas in which Prism helps organizations manage their Nutanix clusters is operational insights. Operational insights focus on providing administrators with alerts, metrics, and the ability to analyze data. As with infrastructure management, this also involves a number of different dashboard and Prism capabilities, including:

* Alerts and user-created alerts
* Alert-driven root cause analysis
* Analytics
* Analysis
* Network visualization

### Operational Insights: Alerts Dashboard

#### Alerts Dashboard: Alerts View

![](https://video.udacity-data.com/topher/2020/May/5eb49440_alerts-dashboard-alerts-view/alerts-dashboard-alerts-view.png)

Alerts in Prism provide administrators with information about informational, warning, and critical alerts. The Alerts dashboard has two views – Alerts and Events. The Alerts view presents all notifications and events in an easy-to-consume table format. The table presents each alert with a color-coded severity level, a description of the alert, a timestamp, which entities the alert involves, and cause and resolution guidance.

#### Alerts Dashboard: Events View

![](https://video.udacity-data.com/topher/2020/May/5eb494bf_alerts-dashboard-events-view/alerts-dashboard-events-view.png)

The Event view displays a list of event messages. Event messages describe cluster actions such as adding a storage pool or taking a snapshot. This view is read-only and you do not need to take any action like acknowledging or resolving generated events.

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/107.jpg)

## Prism Operational Insights: Analysis Dashboard

![](https://video.udacity-data.com/topher/2020/May/5eb5e754_analysis-dashboard/analysis-dashboard.png)

The Analysis dashboard stacks multiple charts and lines them up in time sync.

Above the stack of charts, Prism adds all alerts and events, represented with colors and counts. This visual layout lets an administrator click on a chart at any point in time, placing a vertical line stretched through all charts for easy correlation. By focusing on a specific point and syncing all metrics, administrators can reduce the effort it takes to identify possible root causes. The rightmost column of the screen provides a summary of any alerts and events, so you don’t need to leave the analysis page.

The analysis view allows you to fully customize the number and size of the analytical charts you see and to add charts to your screen or remove them as needed. You can export each chart to a .csv or .json file.

## Prism Capacity Planning: Capacity Runway

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/108.jpg)

Capacity planning is available as part of Prism and focuses on consumption from three resource buckets:

* Storage capacity
* CPU
* Memory

![](https://video.udacity-data.com/topher/2020/May/5eb5e836_capacity-runway/capacity-runway.png)

Capacity results are illustrated as a chart that shows the historical consumption for the capacity metric along with the estimated capacity runway. The capacity runway is the number of days remaining before the resource item is fully consumed. The Capacity Runway view provides overall and detailed runway information for each cluster managed by Prism Central. Clicking any of the clusters listed in the row will allow you to view more detailed information.

![](https://video.udacity-data.com/topher/2020/May/5eb5e876_capacity-runway-demo-ahv/capacity-runway-demo-ahv.png)

In this case, for example, we can see the total runway, and we can click to view:

* Specific storage
* CPU
* Memory details

On the Storage Runway view for DEMO-AHV, as seen here, we can view runway details either by usage or by storage container. On the CPU and memory pages, we can view details either as an overall view or by host.

![](https://video.udacity-data.com/topher/2020/May/5eb5e8bd_capacity-runway-hove-over-chart/capacity-runway-hove-over-chart.png)

Finally, hovering over the any point in the chart will show you projected capacity and runway information for that point in time. For example, as we’re seeing here, live usage has gone up from 1.07 TiB to 5 TiB, and Snapshot Usage has increased from 124.06 GiB to 282 GiB.

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/109.jpg)

## Prism Capacity Planning: Scenarios

![](https://video.udacity-data.com/topher/2020/May/5eb5e91d_scenarios/scenarios.png)

The other major capability of Prism’s Capacity Planning is scenario creation. Scenarios allow you to create projections and estimates of resource utilization over a period of time, if you were to add new workloads, or both.

### Creating a Scenario

![](https://video.udacity-data.com/topher/2020/May/5eb5e955_scenario-9-months/scenario-9-months.png)

Creating a new scenario presents you with a number of different options. Here, we’re trying to create a scenario to determine resource utilization in 9 months, if no new workloads are added. As you can see, based on current utilization data, Prism projects that we’ll run out of storage well before that time.

![](https://video.udacity-data.com/topher/2020/May/5eb5e9a2_scenario-9-months-recommended/scenario-9-months-recommended.png)

In this case, clicking the Recommend button gives us suggestions for which nodes we could add, how many we should add, and what their configuration should be for us to meet our runway needs. This particular feature can be a powerful tool in understand what your current and future capacity needs are, and can empower you to make informed, incremental purchasing decisions.

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/110.jpg)


## Prism Performance Monitoring: Dynamic Monitoring

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/111.jpg)

We’ve already briefly touched upon this in the Operational Insights section, specifically when we discussed the Analysis dashboard. The Analysis dashboard is a key part of Prism’s performance monitoring capabilities, because it provides you with a single, holistic view of cluster data and allows you to drill down into details as required. However, what we haven’t yet discussed is how performance monitoring works in Prism.

Prism offers Dynamic Monitoring, using VM behavioral learning. The system learns the behavior of each VM and establishes a dynamic threshold as a performance baseline for each resource assigned to that VM. Each of the resource charts represents the baseline as a blue shaded range. If a given data point for a VM strays outside the baseline range (higher or lower), the system detects an anomaly and generates an alert. The anomaly is noted on the performance charts for easy reference and follow-up.

If the data point’s anomalous results persist over time, the system learns the VM’s new behavior and adjusts the baseline for that resource. With behavioral learning, performance reporting delivered via Prism helps organizations better understand their workloads and have early knowledge of issues that traditional static threshold monitoring would not otherwise discover.

## Prism Performance Monitoring: Creating Charts

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/112.jpg)

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/113.jpg)

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/114.jpg)

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/115.jpg)

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/116.jpg)

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/117.jpg)

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/118.jpg)

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/119.jpg)

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/120.jpg)

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/121.jpg)

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/122.jpg)

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/123.jpg)

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/124.jpg)

In addition to the default charts that Prism presents you with, you can also create custom charts to monitor specific elements of your cluster. You can create two types of charts: metric or entity.

A metric chart monitors the performance of a single metric on one or more entities. For example, you can create a single chart that monitors the content cache hits for multiple hosts within a cluster.

An entity chart monitors the performance of one or more metrics for a single entity. For example, you can create a single metric chart that monitors a particular host, for metrics such as Disk I/O Bandwidth for Reads, Disk I/O Bandwidth for Writes, and Disk IOPS.

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/125.jpg)

## Prism Performance Monitoring: Alert Emails

### Alert Emails: Settings

![](https://video.udacity-data.com/topher/2020/May/5eb5eb6d_alert-settings/alert-settings.png)

By default, Alert email notifications are enabled. This feature sends alert messages automatically to Nutanix customer support through customer-opened ports 80 or 8443. To receive email notification alerts, you need to ensure that nos-alerts and nos-asup recipients are added to the accepted domain of your SMTP server.

### Alert Emails: Settings

![](https://video.udacity-data.com/topher/2020/May/5eb5ebd3_alert-rules/alert-rules.png)

You can also customize your Alert emails. To aid in your cluster monitoring efforts, you can schedule the frequency of these Alert emails, the recipients, and the conditions under which an email will be sent.

### Alert Emails: Templates

![](https://video.udacity-data.com/topher/2020/May/5eb5ec39_alert-template/alert-template.png)

You can also edit the contents of the email itself.

## Lesson Recap

![](https://video.udacity-data.com/topher/2020/June/5eecfab3_screen-shot-2020-06-19-at-1.49.11-pm/screen-shot-2020-06-19-at-1.49.11-pm.png)

* The hardware and software components of HCI
* Acropolis: AHV, DSF, Virtual Networking, Storage Services
* Prism: Infrastructure Management, Operational Insights, Capacity Planning, and Performance Monitoring

________________________________________________________________________________________________________________________________________________________________________________

# LESSON 4 HYBRID CLOUD SECURITY 

## Lesson Overview

![](https://video.udacity-data.com/topher/2020/June/5eecfaf0_screen-shot-2020-06-19-at-1.50.16-pm/screen-shot-2020-06-19-at-1.50.16-pm.png)

## Lesson Overview

* Introduction to Security
* Security Standards
* Security Development Life Cycle
* Securing the Hybrid Cloud

## Introduction to Hybrid Cloud Security

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/126.jpg)

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/127.jpg)

Security today is more complicated than it’s ever been. There are more workloads than the industry has ever had to deal with before. <strong>As a result of virtualization, these workloads are often sitting on a single hardware platform</strong>.

With traditional infrastructure, stacks are composed of products from multiple vendors, each with a narrow and limited view of security. Validating and maintaining a security baseline through continuous software upgrades, is time-consuming and often involves error-prone manual processes that take away from innovation and productivity.

Traditional security solutions such as firewalls are often blind to the internal communication between virtual machines and applications. Once cybercriminals infiltrate the network, they can take up residence and move laterally without being detected. The inherent complexity of this infrastructure has led to increased risks.

## Security Standards

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/128.jpg)

Since there’s always that risk of someone getting in, a lot of organizations find themselves in a risky place. More often than not, they deal with large volumes of sensitive data around with a high standard of security must be maintained. In order to ensure there are standards organizations can hold themselves to, a number of widely accepted and enforced definitions have been developed.

There are five major government standards for security that IT needs to take into consideration. They are TAA Compliance, NSA Suite B, 508 Compliance, FIPS Compliance, and Common Criteria.

### TAA Compliance

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/129.jpg)

The <strong>Trade Agreements Act</strong> refers to a law requiring the U.S. government purchase only “U.S.-made or designated country end products.” Companies and contractors are considered TAA-compliant if they follow TAA guidelines.

End products are “articles, materials and supplies to be acquired for public use," according to the text of the law. Designated countries include Free Trade Agreement countries, countries that have signed the World Trade Organization Agreement on Government Procurement, Caribbean basin countries and some "least-developed" countries.

China, Taiwan, India, Thailand and Malaysia are not considered designated countries in the TAA. However, U.S. contractors can use supplies from these countries and other non-designated countries, as long as they substantially transform them into different final products that meet the criteria. Contractors and companies that do not comply with TAA rules may face lawsuits or have trouble obtaining government contracts.

### NSA Suite B

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/130.jpg)

<strong>NSA Suite B</strong> is a set of commercially available encryption algorithms, published by the US’s National Security Agency, for use in commercial applications as well as some types of classified information.

Suite B specifies a mode of operation in which only a specific set of secure cryptographic algorithms should be used. Suite B specifies the encryption algorithm, the key exchange algorithm, the digital signature algorithm, and the hashing algorithms.

### 508 Compliance

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/131.jpg)

In 1998, the United States Congress amended the Rehabilitation Act to require Federal agencies to make their electronic and information technology accessible to people with disabilities.

<strong>Section 508</strong> was enacted to eliminate barriers in information technology, to make available new opportunities for people with disabilities, and to encourage development of technologies that will help achieve these goals. The law applies to all Federal agencies when they develop, procure, maintain, or use electronic and information technology.

<strong>508 Compliance</strong>, involves ensuring accessibility in technology. While it’s popularly and more commonly known in the context of website accessibility, 508 Compliance is a key part of systems and platform development as well. Although it isn’t technically a security standard, it’s here because – just like security – 508 compliance needs to be built into a product from the ground up.

It needs to be considered in UI design, navigation, menus and interactions, labelling, and so much more.

### FIPS Compliance

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/132.jpg)

FIPS 140-2 stands for Federal Information Processing Standard 140-2 and, like the other standards listed here, is US-government specific. The standard itself is used to approve cryptography modules and is required when working in any capacity with the United States government. FIPS 140-2 is derived from the Federal Information Security Management Act of 2002 (FISMA) and the Federal Information Security Modernization Act of 2014.

The Federal Information Security Management Act of 2002 is a United States federal law that recognized the importance of information security to the economic and national security interests of the United States. The act requires each federal agency to develop, document, and implement an agency-wide program to provide information security for the information and information systems that support the agency. This also includes information and system that were provided or managed by another agency, contractor, or other sources.

FISMA was superseded by the Federal Information Security Modernization Act of 2014, which removed some elements from FISMA and amended other aspects for changes in cybersecurity and oversight.

### Common Criteria

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/133.jpg)

![](https://video.udacity-data.com/topher/2020/May/5ebaf319_slide-24-common-criteria-evaluation-process-complete/slide-24-common-criteria-evaluation-process-complete.png)

The Common Criteria for Information Technology Security Evaluation, also called Common Criteria, is an international standard for computer security. It allows the users of a system to specify their functional and functional assurance requirements for a specific product. Technology vendors can then, based on these requirements, evaluate their products against these requirements to confirm compliance.

Common Criteria provides assurance that the process of specification, implementation and evaluation of a computer security product has been conducted in a rigorous, and standard manner at a level that corresponds with its target use environment. Once this process is completed successfully, a vendor achieves Common Criteria certification.

There are two major components to Common Criteria. The first, is a Protection Profile, which is a document that specifies the requirements for a class of security devices, such as firewalls. This document is what vendors evaluate their products against to determine Common Criteria Compliance.

The second component is the Evaluation Assurance Level, which – as the name suggests – refers to the evaluation itself. More specifically, it is a numerical rating that described the rigor and depth of an evaluation.

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/134.jpg)

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/135.jpg)

## How Secure Are Your Clouds?

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/136.jpg)

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/137.jpg)

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/138.jpg)

Leveraging the public cloud doesn’t mean you give up all control over security. There are still measures that you can implement, but they only go so far. In practice, you’ll find that you can control and secure about 80% of a public cloud’s capabilities. While that is a considerable amount of control, it does still mean that roughly 20% is left to the cloud provider and their security measures. Most public cloud providers do an excellent job of securing that 20%, but that doesn’t mean breaches are an impossibility.

On the other hand, with the private cloud, you have full control over your security. That means you can potentially be more secure than the public cloud but, simply having an on-prem setup doesn’t bolster security by itself. That is one of the reasons that these security standards are so important. They represent a benchmark against which you can measure your own security profile, determine what areas of your environment are well set up and which ones are in need of some tightening. Your on-prem cloud is only as secure as the products you use to build your technology stack. This is why security needs to be built into those products from the ground up.

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/139.jpg)

## Securing Clouds from the Ground Up

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/140.jpg)

Why are the standards we just talked about are so important?

Each of these standards represents a set of considerations for the way a product is conceptualized, designed, programmed, and tested - and ultimately determines who it can be sold to. These considerations aren’t things that can be bolted on at the last minute.

For a system – any system – to be as protected as it can be, security needs to be built in from the ground up. This is why compliance is something you consider even before you start development. When you’re gathering requirements, determining functionality, and figuring out the sort of product that you’re going to build, you need to consider how security will affect decisions you make during development.

Because of this, it’s important to understand the security development life cycle.

## Security Development Life Cycle

![](https://video.udacity-data.com/topher/2020/May/5ebaf496_slide-34-secdl/slide-34-secdl.png)

This is a high-level overview of the Security Development Life Cycle. It is a process with different phases that contain security activities that sits inside of the classic people-process-technology triangle. The SecDL forms the process portion.

It includes both the central security team that governs the process and updates it, as well as the product or development teams that perform security activities. The technology portion consists of tools that assist in finding vulnerabilities in source code or discovering vulnerabilities in a running instance of the product or application.

The SecDL is methodology-neutral. Security activities fit within any product development methodology, whether waterfall, or DevOps. Methodology differences show up in the cadence of security activities.

The SecDL was developed during the time of waterfall, so it is usually portrayed as a linear process that begins with requirements and ends with the release. When the SDL is extended to agile, some security activities get integrated into the normal sprint schedule, while others are pursued out-of-band. With DevOps, activities are embedded into the build pipeline using automation, while additional activities happen outside the pipeline.

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/141.jpg)

## SecDL: Analyze

![](https://video.udacity-data.com/topher/2020/May/5ebaf50c_secdl-1-analyze/secdl-1-analyze.png)

The first phase is essentially requirements gathering. In this phase, the goal is to defined the security best practices that will be integrated into a product. These practices may come from industry standards or be based on responses to problems that have occurred in the past. Requirements exist to define the functional security requirements implemented in the product, and include all the activities of the SDL. They are used as an enforcement point to ensure that all pieces are properly considered.

Requirements may take the classic form, stating that the product or application must, can, or should, do something. An example might be that the product must enforce a minimum password length of eight characters. In the agile world, requirements are expressed as user stories. These stories contain the same information as do the requirements, but security functionality is written from the user's perspective.

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/142.jpg)

## SecDL: Design

![](https://video.udacity-data.com/topher/2020/May/5ebaf59d_secdl-2-design/secdl-2-design.png)

The design phase of the SDL consists of activities that ideally occur before code is written. Secure design is about quantifying an architecture, for a single feature or the entire product, and then searching for problems.

The key to identifying problems is threat modeling. Threat modeling is the process of thinking through how a feature or system will be attacked, and then mitigating those future attacks in the design before writing the code. If you’ve seen the 2002 film Minority Report, that’s kind of the function that threat modeling serves – it’s about preventing crimes before they happen.

A solid threat model understands a feature's, or product's, attack surface. It then defines the most likely attacks that will occur across those interfaces. A threat model is only as good as the mitigations it contains to fix the problems. It is crucial to identifying security issues early in the process.

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/143.jpg)

## SecDL: Implement

![](https://video.udacity-data.com/topher/2020/May/5ebaf5c6_secdl-3-implement/secdl-3-implement.png)

The next phase is implementation, which involves actually writing secure code. The SecDL contains a few things programmers must do to ensure that their code has the best chance of being secure. The process involves a mixture of standards and automated tools.

On the standards front, a solid SecDL defines a secure coding guide, that defines what is expected and provides guidance for when developers hit a specific issue and need insight. Implementation tools include Static Application Security Testing, or SAST, and Dynamic Application Security Testing, or DAST, software.

SAST is like a spell-checker for code, identifying potential vulnerabilities in the source code. SAST runs against a nightly build or may be integrated into your IDE. It may find and open new bugs in the bug management system nightly or prompt the developer to pause while coding to fix a problem in real time.

DAST checks the application's runtime instantiation. It spiders through an application to find all possible interfaces and then attempts to exploit common vulnerabilities in the application. These tools are primarily used on web interfaces.

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/144.jpg)

## SecDL: Test

![](https://video.udacity-data.com/topher/2020/May/5ebaf640_secdl-4-test/secdl-4-test.png)

Formal test activities include security functional test plans, vulnerability scanning, and penetration testing. Vulnerability scanning uses industry-standard tools to determine if any system-level vulnerabilities exist with the application or product.

Penetration testing involves testers attempting to work around the security protections in a given application and exploit them. Penetration testing also stretches the product and exposes it to testing scenarios that automated tools cannot replicate. Because penetration testing is resource-intensive, it is usually not performed for every release.

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/145.jpg)

## SecDL: Update

![](https://video.udacity-data.com/topher/2020/May/5ebaf68d_secdl-5-update/secdl-5-update.png)

The findings from tests are updated as necessary and the product itself is then prepared for release.

Release occurs when all the security activities are confirmed against the final build and the software is sent to customers or made available for download. After the software is released, an interface is typically provided for external customers and security researchers to report security problems in products.

Part of this response interface should ideally include a product security-incident response team that focuses on triaging and communicating product vulnerabilities, both individual bugs and those that will require industry-wide collaboration such as Heartbleed, Bashbug, etc.

Finally, there are other security activities are also important to the success of a SecDL, including security champions, bug bounties, and education and training.

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/146.jpg)

## SecDL and Nutanix

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/147.jpg)

Our security development life cycle integrates security into every step of product development, rather than applying it as an afterthought. It is a foundational part of product design. The pervasive culture and processes built around security harden the Hybrid Cloud OS and eliminate zero-day vulnerabilities.

For example, research and development teams work together to fully understand all the code in the product, whether it is produced in-house or inherited from dependencies. We schedule product updates to handle known common vulnerabilities and exposures, or CVEs, for minor release cycles, and backport all dependencies to their latest release versions in major release cycles. This approach significantly reduces zero-day risks without slowing down product evolution.

Efficient one-click operations and self-healing security models enable automation to maintain security in an always-on hyperconverged solution. Finally, Nutanix also delivers validated joint solutions with security-focused vendors.

## Security in the Hybrid Cloud

![](https://video.udacity-data.com/topher/2020/May/5ebaf7ac_screen-shot-2020-05-12-at-3.23.10-pm/screen-shot-2020-05-12-at-3.23.10-pm.png)

As a result of the Nutanix approach to SecDL, and with the way we built security into our products from the ground up, you’ll find that the Hybrid Cloud has a number of security features available out of the box.

While there’s more to Nutanix security than the five points you’re seeing here, these are the major topics we’re going to talk about in this lesson. Broadly, we’re going to cover two-factor authentication, cluster lockdown, key management and administration, STIG implementation, data-at-rest encryption, and role-based access control.

## Two-Factor Authentication

![](https://video.udacity-data.com/topher/2020/May/5ebb118d_screen-shot-2020-05-12-at-5.13.35-pm/screen-shot-2020-05-12-at-5.13.35-pm.png)

Several different types of authentication exist, including one way, two way, and two-factor.

<strong>One way authentication</strong> involves simply authenticating to the server. <strong>Two-way</strong> involves the server also authenticating the client.

<strong>Two-factor authentication</strong> is a subset of multi-factor authentication, which involves presenting two or more pieces of evidence to an authentication mechanism. These pieces of evidence are typically combinations of three things: something the user knows, something the user has, and something the user is.

A good example of this is typically bank transactions. Very often, when performing an online transaction, you’ll also be asked to confirm the transaction by entering a time-limited password sent to your mobile phone via text message, or to your email account. In this case, entering your card or account details represent knowledge as the first factor, and the password comes from something you have or own – in this example, your phone or email account.

Two-factor authentication simply involves two pieces of information. In the case of Nutanix’s implementation, it involves a username and password combination, and a client certificate. For two-factor authentication, Nutanix administrators can use either local accounts, or Active Directory.

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/148.jpg)

## Cluster Lockdown

### SSH

SSH or Secure Shell is a cryptographic network protocol for operating network services securely over an unsecured network. Typical applications include remote command-line, login, and remote command execution, but any network service can be secured with SSH.

SSH provides a secure channel over an unsecured network by using a client–server architecture, connecting an SSH client application with an SSH server. The protocol specification distinguishes between two major versions, referred to as SSH-1 and SSH-2. The standard TCP port for SSH is 22. SSH is generally used to access Unix-like operating systems, but it can also be used on Microsoft Windows. Windows 10 uses OpenSSH as its default SSH client and SSH server.

Cluster lockdown is the ability to disable password-based CVM access and/or only allow key based access.

![](https://video.udacity-data.com/topher/2020/May/5ebb11e3_screen-shot-2020-05-12-at-5.15.01-pm/screen-shot-2020-05-12-at-5.15.01-pm.png)

However, you can add your public SSH-key via Prism and still login via SSH by using your ssh key. This adds a layer of non-repudiation to the connection, since the key used to access the emergency account on the shell is logged. This adds a layer of cryptographic exchange to the connection instead of just a source IP.

All CVMs have a set of ssh-keys that are generated at installation, so all CVMs in a cluster can still communicate with each other using keys, and you can ssh between them using keys once you gain access.

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/149.jpg)

## Key Management and Administration

![](https://video.udacity-data.com/topher/2020/May/5ebb1255_screen-shot-2020-05-12-at-5.16.55-pm/screen-shot-2020-05-12-at-5.16.55-pm.png)

Nutanix nodes are authenticated by a key management server, or KMS. SEDs generate new encryption keys, which are uploaded to the KMS. In the event of power failure or a reboot, keys are retrieved from the KMS and used to unlock the SEDs. These security keys can also be instantly reprogrammed. And finally, Crypto Erase can be used to instantly erase all data on an SED while generating a new key.

### SED

Self Encryption Devices

## Security Technical Implementation Guides

![](https://video.udacity-data.com/topher/2020/May/5ebb12f2_screen-shot-2020-05-12-at-5.19.19-pm/screen-shot-2020-05-12-at-5.19.19-pm.png)

<strong>Security Technical Implementation Guides</strong>, or STIGs, are the configuration standards for DoD Information Assurance, or IA, and IA-enabled devices/systems. STIGs specify how a computing device must be configured to maximize security.

A STIG describes how to minimize network-based attacks and prevent system access when the attacker is interfacing with the system, either physically at the machine or over a network. STIGs also describe maintenance processes such as software updates and vulnerability patching. Advanced STIGs cover the design of a corporate network, covering the configurations of routers, firewalls, domain name servers, and switches.

Once deployed, STIGs lock down IT environments and reduce security vulnerabilities in infrastructure. Traditionally, using STIGs to secure an environment is a manual process that is highly time-consuming and error prone. Because of this, only the most security-conscious IT shops follow the required process. Nutanix has created custom STIGs that are based on the guidelines outlined by The Defense Information Systems Agency, or DISA, to keep the Hybrid Cloud Platform within compliance and reduce attack surfaces.

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/150.jpg)

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/151.jpg)

## Data-at-Rest Encryption

![](https://video.udacity-data.com/topher/2020/May/5ebb13a0_screen-shot-2020-05-12-at-5.22.25-pm/screen-shot-2020-05-12-at-5.22.25-pm.png)

<strong>Data-at-Rest Encryption</strong> secures data while at rest using self-encrypting drives and key-based access management. For customers who require enhanced data security, Nutanix provides a software-only encryption option for data-at-rest security which does not require self-encrypting drives.

With Nutanix’s Data-at-Rest Encryption implementation data is encrypted on all drives at all times, data is inaccessible in the event of drive or node theft, data on a drive can be securely destroyed, protection can be enabled or disabled at any time, and no performance penalty is incurred despite encrypting all data.

## Role-Based Access Control

![](https://video.udacity-data.com/topher/2020/May/5ebb13e9_screen-shot-2020-05-12-at-5.23.38-pm/screen-shot-2020-05-12-at-5.23.38-pm.png)

The last security capacity that we’re going to discuss in this lesson is role-based access control. Prism supports role-based access control that you can configure to provide customized access permissions to users based on their assigned roles. The roles dashboard allows you to view information about all defined roles and the users and groups assigned to those roles.

Prism includes a set of predefined roles. You can also define additional custom roles. Configuring authentication confers default user permissions that vary depending on the type of authentication like full permissions from a directory service, or no permissions from an identity provider. You can configure role maps to customize these user permissions. Finally, you can refine access permissions even further by assigning roles to individual users or groups that apply to a specified set of entities.

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/152.jpg)

## Lesson Recap

![](https://video.udacity-data.com/topher/2020/June/5eecfb01_screen-shot-2020-06-19-at-1.50.16-pm/screen-shot-2020-06-19-at-1.50.16-pm.png)

### Lesson Recap

In this lesson we:

* Introduced you to security
* Went over security standards
* Discussed the Security Development Life Cycle
* Discussed how to secure the Hybrid Cloud

________________________________________________________________________________________________________________________________________________________________________________

# LESSON 5 NETWORKING

## Lesson Overview

### Lesson Overview

* Introduction to Physical and Virtual Networking
* Components of AHV Networking
* Working with VLANs

![](https://video.udacity-data.com/topher/2020/June/5eecfb4e_screen-shot-2020-06-19-at-1.51.41-pm/screen-shot-2020-06-19-at-1.51.41-pm.png)

## Introduction to Networking

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/153.jpg)

### What is Networking?

<strong>Networking</strong> is the practice in which nodes transport and exchange data over a shared medium.

It is commonly associated with the design, construction, and use of a network. Networking also includes the management, maintenance, and operation of the network’s physical infrastructure. It also involves all the associated software and policies.

In this lesson we’re going to be focusing on two specific topics – physical networking and virtual networking.

## Introduction to Networking: Physical Networking

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/154.jpg)

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/155.jpg)

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/156.jpg)

<strong>Physical networking</strong> is about the network topology – the devices, their location, and the physical cables that connect those devices to each other. The network is a key component in ensuring high performance and availability, and successful deployments combine the right physical switches with the right physical designs.

A Nutanix environment should use datacenter switches designed for transmitting large amounts of server and storage traffic at low latency.

Datacenter switches have the following characteristics:

* <strong>Line rate</strong>: Ensures that all ports can simultaneously achieve advertised throughput.
* <strong>Low latency</strong>: Minimizes port-to-port latency, measured in microseconds or nanoseconds.
* <strong>Large per-port buffers</strong>: Handle speed mismatch from uplinks without dropping frames.
* <strong>Nonblocking, with low or no oversubscription</strong>: Reduces chance of drops during peak traffic periods.
* <strong>10 Gbps or faster links for Nutanix CVM traffic</strong>: Only use 1 Gbps links either for additional user VM traffic or when 10 Gbps connections are not available, such as in a ROBO deployment. Limit Nutanix clusters using 1 Gbps links to eight nodes.

Once you’ve found the right switch, that’s one big decision dealt with. The other is which networking design to use. And whether you’re designing a new network or transitioning an older network into cloud-scale architecture, it is important to know the differences and characteristics of two prominent network topologies: Core-Aggregation-Access networking, which is also called 3-Tier networking, and Leaf-Spine architecture.

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/157.jpg)

## Physical Networking Topology: Core-Aggregation-Access

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/158.jpg)

This architecture contains three layers: Core, Aggregation, and Access.

The core layer provides fast transport between distribution layer switches. The core layer provides routing services to other parts of the data center, as well as to services outside of the data center such as the Internet, geographically separated data centers and other remote locations. The network core delivers routing services, making complex routing decisions for optimized networking traffic, advertises routes, stores network configurations, and provides a gateway for all networks to communicate internally and externally.

The aggregation layer has redundant connections to access layer switches and connects to the core layer.

The access layer is where host devices are connected to the network. It plays a vital role in meeting server requirements such as NIC teaming, clustering, and broadcast containment.

In the Core-Aggregation-Access networking model, devices are connected to each other within a layer, as well as across layers for redundancy. This model scales somewhat well, but it is subject to bottlenecks if uplinks between layers are oversubscribed. This can come from latency incurred as traffic flows through each layer and from blocking redundant links. Also, the cost per port is fairly high. The hardware and logic contained within core switches made them cost-prohibitive to scale.

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/159.jpg)

## Using 3-Tier in a Nutanix Depoloyment

![](https://video.udacity-data.com/topher/2020/May/5ebda253_using-core-aggregation-access-in-a-nutanix-deployment/using-core-aggregation-access-in-a-nutanix-deployment.png)

The <strong>core-aggregation-access</strong> (or three-tier) design is a modular layout that allows you to upgrade and scale layers independently.

However, there’s one important best practice that you need to consider and that’s the three-switch-hop rule.

Nutanix nodes send storage replication traffic to each other in a distributed fashion over the top-of-rack network. One Nutanix node can therefore send replication traffic to any other Nutanix node in the cluster. The network should provide low and predictable latency for this traffic. So, it’s important to ensure that there are no more than three switches between any two Nutanix nodes in the same cluster.

Essentially, when using Core-Aggregation-Access, you need to ensure that all nodes in a Nutanix cluster share the same aggregation layer to meet the three-switch-hop rule.

![](https://video.udacity-data.com/topher/2020/May/5ebda26c_scaling-core-aggregation-access-in-a-nutanix-deployment/scaling-core-aggregation-access-in-a-nutanix-deployment.png)

Scaling the three-tier network design may require adding another aggregation and access layer to the core. In this case, there would be more than three switch hops between the two access layers. To continue to align with the three-switch-hop rule, ensure that you add Nutanix nodes in separate aggregation and access layers to separate clusters. In the example you’re seeing here, Cluster 1 connects to one aggregation layer and Cluster 2 connects to another.

However, since there are many ways to connect switches in the core-aggregation-access design, your deployment may look a little different from this one.

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/160.jpg)

## Physical Networking Topology: Leaf-Spine

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/161.jpg)

The <strong>leaf-spine network design</strong> is popular in new datacenter deployments because it’s easy to deploy and easy to scale after deployment. A leaf-spine topology requires at least two spine switches and two leaf switches. Every leaf connects to every spine using uplink ports. There are no connections between the spine switches or between the leaf switches in the conventional leaf-spine design. This architecture maintains consistent performance without any reduction in throughput.

Spine switches contain the routing, switching, and network services required for core network functions. Leaf switches exclusively provide high port density for network communications and extend the network configuration of the core out to the endpoints. Leaf-Spine switching focuses on east-west traffic, capitalizing on the fact that a majority of network communication now relies upon communication within the LAN to other adjacent servers and services. Spine leaf provides a high-bandwidth, low latency alternative to 3-tiered architecture, as any given network node is simply one hop away from any adjacent node through the leaf switches.

Spine and leaf architecture provides consolidated management and scale-out networking in a simplified network design. Scaling the architecture normally involves adding a single leaf, enabling the new switch in the fabric, and then cabling the endpoints as needed.

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/162.jpg)

## Leaf Spine: Using Leaf-Spine in a Nutanix Deployment

![](https://video.udacity-data.com/topher/2020/May/5ebda2fd_using-leaf-spine-in-a-nutanix-deployment/using-leaf-spine-in-a-nutanix-deployment.png)

Nutanix recommends a leaf-spine network architecture to ensure true linear scaling. Other best practices include using uplinks that are a higher speed than the edge ports to reduce uplink oversubscription. To increase uplink capacity, add spine switches or uplink ports as needed.

![](https://video.udacity-data.com/topher/2020/May/5ebda31a_scaling-leaf-spine-in-a-nutanix-deployment/scaling-leaf-spine-in-a-nutanix-deployment.png)

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/163.jpg)

## Introduction to Networking: Virtual Networking

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/164.jpg)

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/165.jpg)

To understand virtual networking, we need to first take a quick step back and understand network virtualization. And although they sound similar – and that’s because they’re related – they do mean slightly different things.

Network virtualization involves combining hardware and software network resources, along with network functionality, into a single, software-based administrative entity. The elements that can be combined include switches, network adapters, firewalls, load balancers, virtual LANs, and so on. The outcomes of this – the single, software-based entity – is a virtual network.

And <strong>virtual networking</strong>, to put it very simply, facilitates communication between virtual machines. It’s based on physical networking principles, but its functions are software-driven. For example, a virtual switch contains the same packet forwarding logic that a physical switch does, but as software.

There are four major components that we need to talk about: virtual switches, bridges, ports, and bonds.

This <strong>virtual switch</strong> controls and directs communication between the existing physical network and virtual parts of the network, like virtual machines. <strong>A virtual network</strong> adapter allows VMs to connect to a network, and allows the VMs on a LAN to connect to a larger network as well.

## Virtual Networking: Virtual Switches

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/166.jpg)

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/167.jpg)

As we discussed earlier, virtual switches allow communication between virtual machines. More specifically, they intelligently direct communication on a network by checking data packets before sending them along to their destination.

Using virtual switches simplifies the complexity that comes with configuring and managing a network. This is because virtual switches help reduce the number of switches that need to be managed after factoring in the size of the network, data packets, and architecture. Because they’re entirely software-based, it’s easier to roll out new functionality for virtual switches as compared to physical, hardware-based ones.

Nutanix AHV uses <strong>Open vSwitch</strong>, or OVS, to manage the network across all nodes in the Nutanix cluster. OVS is an open source software switch implemented in the Linux kernel and designed to work in a multi-server virtualization environment. By default, OVS behaves like a layer-2 learning switch that maintains a MAC address table. The hypervisor host and VMs connect to virtual ports on the switch.

OVS supports many popular switch features, including VLAN tagging, Link Aggregation Control Protocol (LACP), port mirroring, and quality of service (QoS), to name a few. Each AHV node maintains an OVS instance, and all OVS instances combine to form a single logical switch. Constructs called bridges manage the switch instances residing on the AHV hosts.

Let's break down some of these virtual networking components that make up Nutanix AHV.

## Virtual Networking: Bridges

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/168.jpg)


<strong>Bridges</strong> act as virtual switches that manage network traffic between physical and virtual network interfaces.

The default AHV configuration includes an OVS bridge called br0 and a native Linux bridge called virbr0. The virbr0 Linux bridge carries management and storage communication between the CVM and AHV host. All other storage, host, and VM network traffic flows through the br0 OVS bridge. The AHV host, VMs, and physical interfaces use ports for connectivity to the bridge. Next, let's discuss ports.

## Virtual Networking: Ports

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/169.jpg)

<strong>Ports</strong> are logical constructs created in a bridge that represent connectivity to the virtual switch. Nutanix uses several port types, including internal, tap, VXLAN, and bond.

An internal port provides access for the AHV host.

Tap ports act as bridge connections for virtual NICs presented to VMs.

VXLAN ports are used for the IP address management functionality provided by Acropolis.

Bonded ports provide NIC teaming for the physical interfaces of the AHV host.

## Virtual Networking: Bonds

### Load Balancing

In computing, load balancing refers to the process of distributing a set of tasks over a set of resources (computing units), with the aim of making their overall processing more efficient. Load balancing techniques can optimize the response time for each task, avoiding unevenly overloading compute nodes while other compute nodes are left idle.

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/170.jpg)

It is possible to balance traffic across bond uplinks, via one of three bond modes: active-backup, balance-slb, and LCAP with balance-tcp. Let’s take a quick look at each of these bond modes next.

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/171.jpg)

## Bond Modes: active-backup

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/172.jpg)

![](https://video.udacity-data.com/topher/2020/May/5ebda518_active-bacup-bond-mode/active-bacup-bond-mode.png)

With the active-backup bond mode, one interface in the bond carries traffic and other interfaces in the bond are used only when the active link fails. <strong>Active-backup</strong> is the simplest bond mode, easily allowing connections to multiple upstream switches without any additional switch configuration. The active-backup bond mode requires no special hardware and you can use different physical switches for redundancy.

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/173.jpg)

## Bond Modes: Balance-slb

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/174.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/175.jpg)

![](https://video.udacity-data.com/topher/2020/May/5ebda562_balance-slb-bond-mode/balance-slb-bond-mode.png)

To take advantage of the bandwidth provided by multiple upstream switch links, you can use the <strong>balance-slb</strong> bond mode. The balance-slb bond mode in OVS takes advantage of all links in a bond and uses measured traffic load to rebalance VM traffic from highly used to less used interfaces.

When the configurable bond-rebalance interval expires, OVS uses the measured load for each interface and the load for each source MAC hash to spread traffic evenly among links in the bond. Traffic from some source MAC hashes may move to a less active link to more evenly balance bond member utilization.

Perfectly even balancing may not always be possible, depending on the number of source MAC hashes and their stream sizes. Each individual VM NIC uses only a single bond member interface at a time, but a hashing algorithm distributes multiple VM NICs’ multiple source MAC addresses across bond member interfaces.

As a result, it is possible for a Nutanix AHV node with two 10 GB interfaces to use up to 20 Gbps of network throughput. Individual VM NICs have a maximum throughput of 10 Gbps, the speed of a single physical interface. A VM with multiple NICs could still have more bandwidth than the speed of a single physical interface, but there is no guarantee that the different VM NICs will land on different physical interfaces.

The default rebalance interval is 10 seconds, but Nutanix recommends setting this interval to 30 seconds to avoid excessive movement of source MAC address hashes between upstream switches. Nutanix has tested this configuration using two separate upstream switches with AHV. If the upstream switches are interconnected physically or virtually, and both uplinks allow the same VLANs, no additional configuration, such as link aggregation is necessary.

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/176.jpg)

## Bond Modes: Balance-tcp

### LACP

LACP, a subcomponent of IEEE 802.3ad, provides additional functionality for link aggregation groups (LAGs). Use the link aggregation feature to aggregate one or more Ethernet interfaces to form a logical point-to-point link, known as a LAG, virtual link, or bundle.

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/177.jpg)

Taking full advantage of bandwidth provided by multiple links to upstream switches, from a single VM, requires dynamically negotiated link aggregation and load balancing using balance-tcp. Nutanix recommends dynamic link aggregation with LACP instead of static link aggregation due to improved failure detection and recovery.

With link aggregation negotiated by LACP, multiple links to separate physical switches appear as a single layer-2 link. A traffic-hashing algorithm such as <strong>balance-tcp</strong> can split traffic between multiple links in an active-active fashion. Because the uplinks appear as a single L2 link, the algorithm can balance traffic among bond members without any regard for switch MAC address tables. Nutanix recommends using balance-tcp when using LACP and link aggregation, because each TCP stream from a single VM can potentially use a different uplink in this configuration.

With link aggregation, LACP, and balance-tcp, a single guest VM with multiple TCP streams could use up to 20 Gbps of bandwidth in an AHV node with two 10 GB adapters.

### QUIZ QUESTION
Why does Nutanix recommend dynamic link aggregation with LCAP, instead of static link aggregation?

* Better failure detection and recovery

## VLAN

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/178.jpg)

A virtual LAN, or <strong>VLAN</strong>, is a subgroup of a network, which combines multiple networking devices into a single domain and partitions them off from the rest.

VLANs offer a number of benefits over their more physical-based counterparts: Better network speed and performance More efficient traffic routing between domains More control over network devices and traffic Security benefits by isolating data within a VLAN No need to add cabling or make significant infrastructure changes

AHV supports two different ways to provide VM connectivity: managed and unmanaged networks.

### QUIZ QUESTION
What is a VLAN?

* A network subgroup, which combines multiple networking devices into a single domain and partitions them off from the rest

# VERY IMPORTANT FOR SOLVING THE FIRST PROJECT
## Unmanaged Network

![](https://github.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/blob/main/images/179.jpg)

With <strong>unmanaged networks</strong>, VMs get a direct connection to their VLAN of choice. Each virtual network in AHV maps to a single VLAN and bridge. All VLANs allowed on the physical switch port to the AHV host are available to the CVM and guest VMs. Acropolis binds each virtual network it creates to a single VLAN. During VM creation, you can create a virtual NIC and associate it with a network and VLAN. Or, you can provision multiple virtual NICs each with a single VLAN or network.

### QUIZ QUESTION
What is an unmanaged network?

* VMs get a direct connection to their VLAN of choice

# VERY IMPORTANT FOR SOLVING THE FIRST PROJECT
## Exercise: Creating an Unmanaged Network

What makes virtual networking with Nutanix really interesting, is that you can create and manage virtual networks without any additional AHV host configuration, using Prism Element, the Acropolis Command Line Interface, or REST API. So, to close this lesson out, we’re going to be creating one managed and one unmanaged network in Prism just so you can experience how simple the process really is.

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/180.jpg)

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/181.jpg)

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/182.jpg)

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/183.jpg)

# VERY IMPORTANT FOR SOLVING THE FIRST PROJECT
## Managed Networks

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/184.jpg)

A <strong>managed network</strong> is a VLAN plus IP Address Management. IPAM is the cluster capability to function like a DHCP server, to assign an IP address to a VM that sits on the managed network. Administrators can configure each virtual network with a specific IP subnet, associated domain settings, and group of IP address pools available for assignment.

The Acropolis Master acts as an internal DHCP server for all managed networks. The OVS is responsible for encapsulating DHCP requests from the VMs in VXLAN and forwarding them to the Acropolis Master. VMs receive their IP addresses from the Acropolis Master’s responses. The IP address assigned to a VM is persistent until you delete the VNIC or destroy the VM.

The Acropolis Master runs the CVM administrative process to track device IP addresses. This creates associations between the interface’s MAC addresses, IP addresses and defined pool of IP addresses for the AOS DHCP server.

### QUIZ QUESTION
What is a managed network?

A VLAN plus IP Address Management

# VERY IMPORTANT FOR SOLVING THE FIRST PROJECT
## Exercise: Create a Managed Network

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/180.jpg)

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/181.jpg)

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/185.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/186.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/187.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/188.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/189.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/190.jpg)

## Lesson Recap

![](https://video.udacity-data.com/topher/2020/June/5eecfb5d_screen-shot-2020-06-19-at-1.51.41-pm/screen-shot-2020-06-19-at-1.51.41-pm.png)

In this lesson we covered:

* Physical and Virtual Networking
* Components of AHV Networking
* How to work with VLANs


________________________________________________________________________________________________________________________________________________________________________________


# LESSON 6 MANAGING VIRTUAL MACHINES IN THE HYBRID CLOUD

## Lesson Overview

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/191.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/192.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/193.jpg)

![](https://video.udacity-data.com/topher/2020/June/5eecfba1_screen-shot-2020-06-19-at-1.53.05-pm/screen-shot-2020-06-19-at-1.53.05-pm.png)

### Lesson Overview
* Introduction to VM management
* Working with Disc Images
* Creating and Managing VMs
* Understanding VM High Availability

Let’s start at the very beginning, with a simple question - what is a virtual machine? <strong>A virtual machine, or VM</strong>, is an emulation of a computer system. It’s based on computer architectures, is typically called an image, and provides the functionality of a physical computer.

As we’ve seen in previous lessons, it’s also a core part of a virtualized system since it’s created by abstracting the resources of a physical machine. VMs are used to provide the end users of a virtualized system with a familiar, comfortable substitute for a real machine.

And VM management refers to activities such as starting and stopping a VM, updating a VM’s configuration, and migrating, cloning, or deleting a VM. With Nutanix specifically, all of these activities are performed in Prism, and on the VM dashboard that we discussed briefly in lesson 2. So, before we move on to these operations, let’s quickly look at the VM dashboard again, but in a little more detail.

### QUIZ QUESTION
Which of these statements accurately describes a virtual machine? (Choose all that apply.)

* A virtual machine is an emulation of a computer system and provides the functionality of a physical computer

## The VM Dashboard

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/194.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/195.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/196.jpg)

![](https://video.udacity-data.com/topher/2020/May/5ebf0df1_vm-dashboard-table-view/vm-dashboard-table-view.png)
![](https://video.udacity-data.com/topher/2020/May/5ebf0dfe_vm-table-no-selection/vm-table-no-selection.png)
![](https://video.udacity-data.com/topher/2020/May/5ebf0dc7_vm-table-test-vm-01-selected/vm-table-test-vm-01-selected.png)

All of the VM management tasks that were listed earlier are performed here, on the table view of the VM dashboard. As you can see here, the Table view has three major sections – a table in the center of the screen that contains a list of all VMs on the cluster; a VM Summary box at the bottom left with information like total number of VMs, provisioned and reserved CPU and memory, etc.; and two tabs for VM performance summary and VM tasks respectively.

What we’re interested in right now is the VM table, which you’re seeing here. If you look below the table, you’ll see that there’s nothing of note – just the “Summary” heading and that’s it. However, if we were to select a VM from the table things look a little different.

As you can see, with Test VM 001 selected, we now have access to a variety of different management options. You can manage Nutanix Guest Tools, Launch the VM’s console, power the VM on or off, take a snapshot, and migrate, clone, update, or delete the VM.

So, now that you know how to access these options, let’s look at VM creation and management in more detail.

### QUIZ QUESTION
Which of the following tasks can you perform on the VM dashboard?

* Create VM

* Clone VM

* Power On/Off

* Update VM

# VERY IMPORTANT FOR SOLVING THE FIRST PROJECT
## Working with Images

The first step in creating virtual machines is learning how to work with images.

You can use Prism to import and configure operating system ISO and disk image files using the Image Service. This image service allows you to assemble a repository of image files in different formats including raw, vhd, vhdx, vmdk, vdi, iso, and qcow2. You can later use these images when creating virtual machines.

Adding an image to the image service is a fairly straightforward upload process. The upload process is performed on the Storage dashboard (not the VM dashboard). You simply select the image, name it, select the image type, and that’s it - your image is now in Prism and ready for use.

After you upload an image to Prism, there are several things you can do with it. You can use it to create a VM, you can leave it in the image service for use in future deployments and, if you no longer need that image at a later date, you can simply delete it from Prism.

Before we move on to an exercise in which you can practice uploading images, let’s watch a short video walkthrough of the process.

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/197.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/198.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/199.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/200.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/201.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/202.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/203.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/204.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/206.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/207.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/208.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/209.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/210.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/211.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/212.jpg)

### QUIZ QUESTION
Which dashboard do you use to upload images for use in VM creation?

* The Storage dashboard

# VERY IMPORTANT FOR SOLVING THE FIRST PROJECT
## Exercise: Uploading Images to the Image Service

Please follow the tutorial showed above this lines.


# VERY IMPORTANT FOR SOLVING THE FIRST PROJECT
## Creating a VM

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/214.jpg)

# QUIZ QUESTION
You can create a VM in Prism using _

* A form that allows you to specify compute, memory, storage, and network details

## Exercise: Creating a VM

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/215.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/216.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/217.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/218.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/219.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/220.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/221.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/222.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/223.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/224.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/225.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/226.jpg)

## Updating/Modifying a VM

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/227.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/228.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/229.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/230.jpg)

Managing VMs involves a handful of tasks. Now, specifically, we’re going to be focusing on a few of them. Let’s start with modification. You can update or modify a VM at any point after you create it. And, you have access to the same dialog that’s used when creating a VM, so you can modify everything from CPU, memory, and storage to networking and host affinity details.

![](https://video.udacity-data.com/topher/2020/May/5ecda173_update-vm-screen-1/update-vm-screen-1.png)

On the update VM dialog, change the VM’s configuration to suit your needs. In this case, we’ve updated the number of cores per vCPU to 2, and the memory from 8 GB to 16. When all your changes have been made, click Save.

![](https://video.udacity-data.com/topher/2020/May/5ecda1b0_update-vm-screen-3/update-vm-screen-3.png)

![](https://video.udacity-data.com/topher/2020/May/5ecda1c0_update-vm-screen-4/update-vm-screen-4.png)

### QUIZ QUESTION
Which of a VM's configuration details can you modify when updating a VM?

* All of them

## Exercise: Updating CPU and Memory on a VM

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/231.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/232.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/233.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/234.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/235.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/236.jpg)

# VERY IMPORTANT FOR SOLVING THE FIRST PROJECT
## Cloning a VM

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/237.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/238.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/239.jpg)

![](https://video.udacity-data.com/topher/2020/May/5ecda20d_update-vm-screen-2/update-vm-screen-2.png)

To clone a VM select it and then, from the row of option below the VM table, select Clone.

![](https://video.udacity-data.com/topher/2020/May/5ecda238_clone-a-vm-screen-1/clone-a-vm-screen-1.png)

![](https://video.udacity-data.com/topher/2020/May/5ecda245_clone-a-vm-screen-2/clone-a-vm-screen-2.png)

In the Clone VM dialog, you can change the configuration as required and specify the number of clones you want. If you want to create more than one clone – if you look at this example, we’re creating five – then you’ll also be prompted to specify a starting index number.

Once you’ve made all of your changes, click Save and your VM clones will be created.

### QUIZ QUESTION
* True or false: When cloning a VM, you can change the VM's configuration and create multiple clones at the same time.

True

## Deleting a VM

Deleting a VM is as straightforward as it sounds. Simply select the VM you want to delete and, from the row of options below the VM table, select Delete.

You’ll be prompted to confirm deletion. If the VM is powered on, as is the case here, the dialog will explicitly state that. You’ll also be asked if you want to delete all snapshots of this VM. Make your selections and, once you’re sure, click Delete to remove the VM from Prism.

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/240.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/241.jpg)

## Migrating a VM

Like a lot of the capabilities we’ve talked about already, migrating a VM to a different host in the cluster also a one-click operation. If you need to migrate a VM, you can either choose the host yourself, or allow Prism to do it for you. Since the former is extremely straightforward, let’s look at a quick example of the latter.

![](https://video.udacity-data.com/topher/2020/May/5ecda394_update-vm-screen-2/update-vm-screen-2.png)

On the Migrate VM screen, click the dropdown and select the host that you want to migrate to.

![](https://video.udacity-data.com/topher/2020/May/5ecda3c9_migrate-a-vm-screen-1/migrate-a-vm-screen-1.png)

Here, we have 3 options – Demo 1, Demo 2, and the host that the VM is already on, Demo 3. Let’s move the VM to Demo 2. To do this, we just need to select DEMO-AHV-2 from the list and click Migrate.

![](https://video.udacity-data.com/topher/2020/May/5ecda3e3_migrate-a-vm-screen-2/migrate-a-vm-screen-2.png)

Prism will take a few seconds to complete the process and, once it finishes, we can see the results. In the column to the right of the VM name, we can see that our test VM is now on DEMO-AHV-2.

![](https://video.udacity-data.com/topher/2020/May/5ecda403_migrate-a-vm-screen-3/migrate-a-vm-screen-3.png)

## What is VM High Availability?

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/242.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/243.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/244.jpg)

<strong>High availability</strong> refers to the ability of a system to run continuously without failure. This doesn’t mean that the system or components of it cannot fail; It just means that the system is designed to account for and compensate for failures when they happen. And, since VMs represent the interface with which end users interact with a virtualized system, being able to provide high uptime and strong tolerance for failure is especially important.

By default, Nutanix uses a system called best effort availability for VMs. Other options are available and can be manually turned on, but this one is on by default.

If a host fails, the VMs that were running on that host are restarted on any available space on other hosts in the cluster. One the failed host is up and running, VMs are migrated back to their original host. This type of VM high availability is implemented without reserving any resources. But because admission control is not enforced, there may not be enough resources to restart all VMs.

The other option is using host-based reservations.

In this method, the cluster is divided into segments to ensure enough space is reserved for any host failure. Each segment corresponds to the largest VM that is guaranteed to be restarted in case the failure occurs. The other factor is the number of host failures that can be tolerated. Using these inputs, the scheduler implements admission control to always have enough resources reserved so that the VMs can be restarted upon failure of any host in the cluster.

### QUIZ QUESTION
Which of the following statements is TRUE about best effort availability?

* With Best Effort, when a VM goes down, it will only be restarted if there are enough resources available to do so

## Enabling VM HA

![](https://video.udacity-data.com/topher/2020/May/5ecda849_enabling-vm-ha-screen-1/enabling-vm-ha-screen-1.png)

To enable VM HA, click the gear icon at the top right of the screen to open the Settings page.

![](https://video.udacity-data.com/topher/2020/May/5ecda870_enabling-vm-ha-screen-2/enabling-vm-ha-screen-2.png)

As you can see here, HA Reservation is disabled by default. The dialog informs you that resources are not reserved, and in case of a failure VMs will be restarted based on the amount of resources that are available to the cluster. To enable VM HA, select the Enable HA Reservation checkbox.

![](https://video.udacity-data.com/topher/2020/May/5ecda898_enabling-vm-ha-screen-3/enabling-vm-ha-screen-3.png)

The dialog updates to inform you that a certain amount of resources will be reserved to provide protection in case of a host failure. To save this change and enable VM HA, click Save.

![](https://video.udacity-data.com/topher/2020/May/5ecda8b2_enabling-vm-ha-screen-4/enabling-vm-ha-screen-4.png)

### QUIZ QUESTION
True or false: By default, a Nutanix cluster does not reserve resources to restart VMs in case of a failure.

* True, VM HA reservation must be manually enabled

## Lesson Recap

![](https://video.udacity-data.com/topher/2020/June/5eecfbb0_screen-shot-2020-06-19-at-1.53.05-pm/screen-shot-2020-06-19-at-1.53.05-pm.png)

* Introduced you to VM management
* Worked with Disc Images
* Showed you how to create and manage VMs
* Discussed VM High Availability


________________________________________________________________________________________________________________________________________________________________________________


# LESSON 7 DATA PROTECTION 

## Lesson Overview

### Lesson Overview
* The state of data protection
* The complexities of data protection in a hybrid cloud world
* Data protection trends
* Data protection in the hybrid cloud

![](https://video.udacity-data.com/topher/2020/June/5eecfbe4_screen-shot-2020-06-19-at-1.54.26-pm/screen-shot-2020-06-19-at-1.54.26-pm.png)

Businesses of all sizes are modernizing IT with the goal of:

* Reducing costs
* Increasing productivity
* Addressing digital transformation needs.

However, not all businesses are paying the same amount of attention to changing requirements for data protection, nor have they made the same investments for data protection as they have for other areas of IT. At the same time, uptime and availability of critical applications is becoming increasingly important. The result is a steadily widening gap between the amount of data protection being delivered, and the level of protection needed.

## The Cost of a Disaster

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/247.jpg)

Disaster risks are growing on many fronts. Over the last several years, there has been a steady increase in both natural and man-made disasters. In 2018 alone, U.S. climate disasters cost the nation around $91 billion dollars.

Unplanned outages due to system failure, cybercrime, and simple human error are also on the rise. In March 2019, Facebook had a massive day-long meltdown caused by a routine maintenance operation that triggered a bug. No company is immune.

According to Gartner, the average cost that large businesses incur due to downtime is 300 thousand dollars per hour. Organizations need to review their business continuity practices. But, at the same time, a number of factors make comprehensive data protection more challenging than ever.

## Data Protection Challenges

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/248.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/249.jpg)

The amount and type of stored data continues to grow. The diversity of places where data is being stored – such as desktops, SAN and NAS storage, and multiple clouds – also continues to grow.

At the same time, the widespread adoption of the hybrid cloud is changing the way data protection is being implemented. In many cases, the cloud is seen as the preferred target for backup and Disaster Recovery, in short: DR. Backup as a Service and DR as a Service are rising as popular alternatives to traditional approaches.

On top of that, businesses are seeking higher levels of protection. Recovery Time Objectives, or RTO, and Recovery Point Objectives, or RPO, are all shrinking. This makes for a challenge: as the amount of data increases, the time for backup tasks continues to decrease. For many applications, the backup window has effectively shrunk to zero.

### QUIZ QUESTION
What are the three main challenges that companies are facing with data protection today?

* Growing data; widespread adoption of the hybrid cloud; businesses needed better protection

## Data Protection Trends

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/250.jpg)

Many of the trends in data protection are a direct response to the challenges that we just discussed. Broadly, we’re interested in three specific trends:

* <strong>Application-centric protection:</strong> Applications often have their own data protection and disaster recovery methods. While this can be attractive in terms of level of protection for a given application, it can also result in additional silos of software and hardware that add to overall complexity.

* <strong>Automation:</strong> Because of the complexity and importance of data protection and disaster recovery workflows, significant efforts have been made to automate tasks and simplify orchestration of custom workflows to: reduce administrative overhead, accelerate recovery, and eliminate the chance of operator error.

* <strong>Copy data management:</strong> This refers to the rapidly proliferating number of full data copies that must be stored and managed for, for instance, backup, replication, and development. Solutions are emerging to control and manage this growth.

* QUIZ QUESTION
Which of the following trends is the result of the growing complexity of data protection and DR workflows?

* Automation

## RTO and RPO

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/251.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/252.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/253.jpg)

Before we move on to data protection in the hybrid cloud, let’s take a minute to go over two terms that were just introduced – Recovery Time Objective, or RTO, and Recovery Point Objective, or RPO.

Both parameters are extremely important to data protection because, in many ways, RPO and RTO are the foundation of data protection and disaster recovery decisions that many businesses make.

<strong>Recovery Time Objective</strong> refers to the time allowed to restore normal operations when an IT failure or disruption occurs, in order to avoid unacceptable consequences associated with a break in business continuity. An RTO of one hour means an application or a data-set will be back online within one hour after a failure occurs.

<strong>Recovery Point Object</strong> refers to the quantity of data that a business can lose, before the amount of data lost during that period, exceeds a maximum allowable threshold which would result in unacceptable consequences associated with a break in business continuity.

### QUIZ QUESTION
What is RTO?

* The time required to restore normal operations when an IT failure or disruption occurs

## Data Protection in the Hybrid Cloud

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/254.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/255.jpg)

Businesses of all sizes are discovering that hybrid cloud with Nutanix – which is built with web-scale engineering and consumer-grade design – simplifies IT, increases availability, and accelerates the entire IT environment, including data protection and Disaster Recovery.

Nutanix combines a highly resilient, scale-out infrastructure with efficient snapshot, cloning, and replication technologies, as well as intelligent software to provide a higher level of protection with less complexity and lower cost.

As a result, the Nutanix hybrid cloud brings six major capabilities to data protection.

### Six Major Capabilities

* <strong>Application-centric automation:</strong>With Nutanix, you can quickly and easily group application VMs, and protect them together, as a set.
* <strong>Multi- and cross-hypervisor support:</strong> VMware vSphere, Microsoft Hyper-V, and Nutanix AHV.
Not only can you use data protection functionality with all three hypervisors, you can also perform cross-hypervisor replication to optimize costs.
* <strong>Simple Management:</strong>Data protection with multiple solutions, devices, and interfaces – can be a problem. Prism can be used to manage all Nutanix data protection and DR functionality.
* <strong>Policy-based data protection:</strong> Data protection and DR are based on policies you define up front, allowing you to deliver the right protections for every application and workload with ease.
* <strong>API-driven automation:</strong> Nutanix provides a full set of REST APIs to facilitate automation. Every action that can be performed from the Prism UI, through PowerShell, or using application programs.
* <strong>Copy efficient protection:</strong> Nutanix data protection and data reduction help you minimize the number of full data copies and the bandwidth needed for replication. This saves on space and cost, providing complete data protection, while allowing you to quickly provision clones for analytics, development, and testing.

### QUIZ QUESTION
Which of the following are Nutanix data protection capabilities? (Choose all that apply.)

* Application-centric automation

* API-driven automation

* Cross-hypervisor support


## Infrastructure Resilience

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/256.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/257.jpg)

Infrastructure resiliency is the first line of defense for your data and applications. One of the things that differentiates Nutanix from conventional infrastructure with separately sourced servers, storage, and storage networks is that the platform is fault resistant, with no single point-of-failure or bottlenecks.

The system uses a shared-nothing architecture with data, metadata, and services distributed across all nodes within a cluster. It is designed to detect, isolate, and recover from failures in order to survive system malfunctions and maintain data availability should there be any hardware unavailability, software glitches, or hypervisor issues.

With respect to infrastructure resilience, it is important to understand 4 key capabilities that Nutanix provides:

* Tunable redundancy
* Erasure coding
* Integrity checks
* Availability domains

### QUIZ QUESTION
Which of the following characteristics differentiates Nutanix data protection from conventional infrastructure? (Choose all that apply.)

* Nutanix is fault resistant, with no single point-of-failure or bottlenecks

* Nutanix uses a shared-nothing architecture with data, metadata, and services distributed across all nodes within a cluster

* Nutanix is designed to detect, isolate, and recover from failures, and maintain data availability

## Infrastructure Resilience: Tunable Redundancy

<strong>Tunable redundancy</strong>, replaces traditional, hardware-centric RAID. Each Nutanix data container, which is the equivalent of a VM datastore, has a data Replication Factor, or “RF”, of 2 or 3. This means that either two or three copies of data are maintained at all times.

![](https://video.udacity-data.com/topher/2020/May/5ec71447_screen-shot-2020-05-21-at-7.52.18-pm/screen-shot-2020-05-21-at-7.52.18-pm.png)

In this image, you can see how RF2 allows a cluster to survive the failure of one node or drive, while RF3 allows a cluster to survive two simultaneous failures of the same components.

If a node or drive fails, the copy of that data is automatically read from another node in the cluster. If the node does not come back online, all data on the affected node is automatically reconstructed to ensure full redundancy and data protection.

Because the workload is spread across the cluster, the performance impact is small. The larger the cluster is, the faster the data is reconstructed, and the smaller the impact of a failure. The system returns to full redundancy quickly and without intervention.

Next, we’ll discuss erasure coding, which provides the same level of data resilience while removing storage capacity overhead.

### QUIZ QUESTION
How many node or drive failures can a cluster sustain in RF2?

* 1

## Infrastructure Resilience: Erasure Coding

![](https://video.udacity-data.com/topher/2020/May/5ec714b2_screen-shot-2020-05-21-at-7.54.04-pm/screen-shot-2020-05-21-at-7.54.04-pm.png)

Let’s take a closer look at Erasure Coding, or “EC-X”.

<strong>Erasure Coding</strong> encodes a strip of data blocks that reside on different nodes in the cluster, and calculates parity using software, instead of physical disk controllers.


With the parity blocks in place, the second and/or third copies of the original data are then removed. In the event of a disk or node failure, parity blocks are used to re-calculate missing data blocks. Each data block in a strip is on a different node and belongs to a different vDisk. The number of data and parity blocks in a strip is dynamic, it's configuration based on the number of nodes in the cluster and the chosen data replication factor.

Erasure coding increases usable capacity over 50%. EC-X also reduces data storage capacity, and therefore capacity cost without taking away any of the resiliency benefits, and with no impact on write performance.

### QUIZ QUESTION
What does Erasure Coding do?

* Encodes a strip of data blocks that reside on different nodes in the cluster, and calculates parity.

## Infrastructure Resilience: Integrity Checks

Nutanix integrity checks are a combination of features that proactively identify and fix issues related to data consistency, data integrity, and hard disk corruption.

There are three items that are worth calling out specifically. These are:

* The system scans data in the background and verifies it against stored checksums in the distributed metadata store. If an error is detected, bad data is overwritten using a good copy.

* A checksum is computed for all data being read, and compared with stored checksums. This essentially provides automatic data integrity checks for every read operation.

* If a drive fails, the system automatically replicates all data that is no longer redundant, to ensure fault tolerance. During the failure and recovery process, both data and access to it are preserved.

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/258.jpg)

## Infrastructure Resilience: Availability Domains

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/259.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/260.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/261.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/262.jpg)

Availability domains, our final discussion point under infrastructure resilience, offers even greater protection from hardware failures than we’ve talked about already. It allows a cluster to survive the failure of a node, a block, or even a datacenter rack. The three types we’re going to discuss are:

* <strong>Node Awareness</strong>: Exactly how a cluster survives node failures without losing access to its data.
* <strong>Block Awareness</strong>: Block awareness takes node awareness a step further, by distributing data replicas across multiple blocks. A block, incidentally, is a multi-node enclosure that can contain up to four nodes. In the case of block awareness, if a block fails, there is always at least one replica of all data on the node of another block.
* <strong>ack Awareness</strong>: Rack awareness builds on block awareness in the same way, and provides data availability in case of a rack-level failure, for instance a power outage.

### QUIZ QUESTION
What are availability domains?

* They allow a cluster to survive the failure of a node, block, or rack

## Backups Overview

<strong>Regular backups</strong> are the second line of defense in data protection, and the only protection against user, administrator, and application errors that result in data being deleted or corrupted. The Nutanix hybrid cloud provides <strong>three</strong> levels of backup:

* Converged local backup with snapshots
* Integrated remote backup
* Cloud backups

Using these capabilities, you can easily implement disk-to-disk, disk-to-cloud, or disk-to-disk-to-cloud backup models. For any of these modes you can tailor the number of retained backups to your exact needs.

# VERY IMPORTANT FOR SOLVING THE FIRST PROJECT

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/263.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/264.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/265.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/266.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/267.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/268.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/269.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/270.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/271.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/272.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/273.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/274.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/275.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/276.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/277.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/278.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/279.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/280.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/281.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/282.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/283.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/284.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/285.jpg)

## Converged Local Backup with Nutanix Snapshot

Backup remains one of the biggest challenges in enterprise IT environments. With Nutanix, you can create unlimited local backups with VM-level and application-level consistency, allowing you to recover data instantly to meet a wide range of backup and data protection requirements.

Nutanix snapshots provide production-level data protection without sacrificing performance. A redirect-on-write algorithm dramatically improves system efficiency. Once a snapshot has been created, it can be accessed without affecting production activity.

You can backup a snapshot to tape for long-term retention, replicate it to another Nutanix cluster, or replicate it to the cloud.

## Integrated Remote Backup

Nutanix can efficiently replicate snapshots of individual VMs from a primary system to one or more secondary systems at different sites.

Replication is flexible and bi-directional, enabling: one-to-one, one-to-many, many-to-one, and many-to-many topologies. By supporting fan-out, fan-in, and multi-way replication, Nutanix allows you to create a flexible multi-master virtualization environment.

VM snapshots can be asynchronously replicated or backed up to another datacenter through a user-defined schedule. Only changes between snapshots of VMs, the byte-level delta, are sent over the network to the remote cluster, and data is compressed to minimize Wide-Area-Network, or “WAN”, bandwidth consumption.

Deduplicated data sent to remote sites can effectively cut the bandwidth requirement by more than 50% when compared with host-based, full-copy backup solutions.

Replication, like other system functions, is fully distributed across the nodes in a cluster, ensuring maximum replication performance.

Prism provides a simplified view of all local and remote snapshots, allowing administrators to restore a VM from a snapshot with a single click. In case of disaster, you can failover using the backed up data-copy at a secondary datacenter, providing a single replication stream for backup.

## Cloud Backups

Nutanix allows you to use public cloud services, such as Amazon Web Services, as a backup destination for all types of workloads, making the public cloud a logical extension of your own datacenter. You can backup to, and recover from, the public cloud with just a few clicks, similar to backing up to a remote physical Nutanix cluster.

You can snapshot an individual VM, or a collection of VMs, to multiple geographically dispersed regions, utilizing Nutanix Xi Leap cloud services. Recovery is the same as from a remote Nutanix site. Data transfer is WAN optimized, reducing the storage footprint and network bandwidth by more than 50%.

## Lesson Recap

* The state of data protection
* The complexities of data protection in a hybrid cloud world
* Data protection trends
* Data protection in the hybrid cloud

![](https://video.udacity-data.com/topher/2020/June/5eecfbf8_screen-shot-2020-06-19-at-1.54.26-pm/screen-shot-2020-06-19-at-1.54.26-pm.png)

## Course Recap

Congratulations! You’ve successfully completed Course One of the hybrid cloud engineer nanodegree program.

At this point, it’s safe to say you should have an understanding of how technology evolved over the years to bring us to the hybrid cloud of today.

You should be familiar with the basics of hybrid cloud networking, security, virtual machine management, and data protection.

And, of course, you should be a little more comfortable with hyperconverged infrastructure and the hybrid cloud itself.

But this is just the first step.

At the beginning of this course I said that you’re starting a journey. Someone in your position will always be learning, always be growing, and always be improving, because that is simply the nature of IT.

But the six lessons that we’ve gone through here are the bedrock of your future.

Everything new that you learn will add to this foundation until you build your own career in the same way IT professionals around the world built the hybrid cloud itself – one innovation, one piece, and one step at a time.

![](https://video.udacity-data.com/topher/2020/June/5eecfc1a_screen-shot-2020-06-19-at-1.55.28-pm/screen-shot-2020-06-19-at-1.55.28-pm.png)






































































# Adaptation as a repository: Andrés R. Bucheli.








