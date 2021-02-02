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




________________________________________________________________________________________________________________________________________________________________________________
________________________________________________________________________________________________________________________________________________________________________________




# SECOND COURSE INTRO TO PRIVATE AND HYBRID CLOUD AUTOMATION




# LESSON 1 INTRO TO PRIVATE AND HYBRID CLOUD AUTOMATION 

## Reflections by the Intructor

Hello my new friends, I'm Mark Lavi, the Principal DevOps Advocate at Nutanix. With over twenty years’ experience working as an engineering and operations manager in Silicon Valley, I’ve seen the birth of the commercial Internet and the world wide web, the rise of virtualization and birth of the public cloud. I’ve worked as a practitioner and as an industry advocate for advancing information technology and software development. My career has been at some of the world’s largest media and innovative technology companies including News Corporation, CNN, Netscape, Silicon Graphics, and multiple Silicon Valley startups. Since the beginning of my career, I’ve spanned engineering and operations. Ten years ago, the name for my work was invented: DevOps. Five years ago, I began at an automation startup that was acquired by Nutanix and I’ve worked for the last three years with customers as Nutanix’s first DevOps Solutions Architect. My experience covers developing, scaling, securing, and managing systems, people, and products together.

I have deep experience on both sides of the private and public cloud and that is why I can help you advance to the hybrid cloud. I learned high availability, distributed architectures and operations on Linux bare metal servers and then jumped into building and operating the entire software development tool chain, e-commerce, and product demo sites on the public cloud. As Nutanix’s Principal DevOps Advocate, I adapt advanced engineering methods, technology, and culture to accelerate the business needs of Nutanix customers, partners, employees and now you! I get up every day excited to do my job because we empower people to go further, work smarter, and enjoy their work and personal life balance more through automation and DevOps culture.

## Prerequisites

 order to understand the concepts and master the skills in these courses, you will need at the outset:

* Comfort with using the command line on Linux or Windows
* Experience working with Virtual Machines (VMs) using on-premise hypervisors or the public cloud
* Basic web server familiarity
* Basic database and SQL familiarity

## Intro to Private and Hybrid Cloud Automation

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/287.jpg)

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/286.jpg)

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/288.jpg)

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/289.jpg)

Infrastructure and operations teams have struggled with visibility since the dawn of client/server, and today’s disaggregated services make that even worse. The increasing complexity and scale of enterprise cloud almost necessitate automation tools.

Unfortunately, manual processes are still the norm in many IT organizations despite the cost savings and increased speed from automating repetitive operations. Gartner forecasts that by 2024, organizations will lower operational costs by 30% by combining hyper-automation technologies with redesigned operational processes, a transition that might accelerate in response to the current global situation.

### Automation alone is not sufficient
Still, automation alone cannot be the panacea for reining in cost and managing infrastructure at scale. Workloads change quickly, and the process of keeping up with application configuration and deployment changes is complex and prone to errors. The results are often service interruptions, wasted resources, and performance bottlenecks—which can defeat the purpose of automation.

## An overhaul triggered by digital transformation

![](https://video.udacity-data.com/topher/2020/October/5f760569_screen-shot-2020-10-01-at-9.34.59-am/screen-shot-2020-10-01-at-9.34.59-am.png)

Digital transformation has triggered a major overhaul in the way organizations think about tried-and-true business models and operationalize day-to-day processes. Yesterday’s products are being replaced with new information- and service-driven offerings, particularly in markets saddled with a high degree of commoditization.

In the retail industry, for example, companies are embracing ways to repackage products, innovate in purchasing practices, and add intelligence to buyer recommendations. Thanks to technology such as advanced analytics, machine learning, IoT/advanced sensors and universal connectivity, retailers are now able to target consumers beyond store fronts and even automate ordering based on stock levels and consumer behavior.

With the rise of DX and supporting technologies like IoT, data processing, and visualization, the role of software development has become increasingly important. To quickly deliver new applications and services, IT teams are transitioning to DevOps models that close the gap between development and operations.

### QUIZ QUESTION
True or false: The only way to rein in costs and manage infrastructure at scale is automation.

* False, automation alone is not the solution. Companies also need to re-examine business models and processes through the lens of digital transformation.

## DevOps and Digital Transformation

DevOps emerged originally from what’s been termed a convergence of theories and practical advances in manufacturing (such as the Toyota Production System and the Lean Manufacturing management philosophy) and in software development, such as the Agile movement.

![](https://video.udacity-data.com/topher/2020/October/5f7604b3_screen-shot-2020-10-01-at-9.31.49-am/screen-shot-2020-10-01-at-9.31.49-am.png)

Technically, we’ve witnessed a massive paradigm shift in the last 15 years with the emergence of virtualization, truly distributed systems, and the cloud, which have reset expectations at every level both for external and internal customers.

Users and consumers expect everything on demand—for this generation of developers and engineers, that means they expect near-instant access to the resources they need to develop new apps—long waits, downtime, and change controls are anathema. They are accustomed to tools that allow easy version control and collaboration. Business apps should behave like mobile apps, and you should pay only for what you use.

To remain competitive, companies must be able to run their business anywhere, anytime, at any scale—and fast. What’s fast? If it takes you more than a minute to implement a code change—yes, a minute—then you’ve got a bottleneck.

The world’s most advanced companies ship hotfixes hundreds, even thousands of times a day, and it’s invisible to users. The competitive advantages of agility—faster time to market; better, more innovative products and services—are why developers and engineers deserve credit for the lion’s share of value for the world’s most profitable companies.

How do you unleash the full value of your developers and engineers? DevOps. When fully realized, DevOps enables non-disruptive innovation at scale, anywhere in the world.

DevOps (“Development and Operations”) is the process of removing friction between the developer and customer.

DevOps is a process. It is not static, it is constantly evolving, and practitioners are constantly improving the state of the art. It is about removing friction - any non-heuristic or automatable operation, process, or human manual intervention should be minimized. It is about connecting the developer to the customer and vice-versa, so there is a feedback mechanism to ensure value is delivered and maintained.

When fully realized, DevOps enables non-disruptive innovation at scale, anywhere in the world.

### Enabling Innovation at Scale

Many Nutanix customers start their IT modernization journeys by adopting hyperconverged infrastructure (HCI). But once you’ve reduced the complexity of managing your infrastructure stack, the next step is to increase levels of integration and automation.

IT teams are constantly tasked with delivering infrastructure and applications to their end business units. What if there were a self-service portal that IT could create for provisioning? Likewise, if the end-user could themselves start, stop, and scale an application based on their requirements and team roles, it would empower the end users and at the same time free up cycles from the IT team.

While many of the fundamental building blocks have long been available, IT teams miss a unified, full-stack, orchestration layer that works across hybrid multi-cloud environments. Nutanix Calm orchestrates the provisioning, scaling and management of applications across environments, making the entire IT infrastructure more agile and application-centric.

### Creating IT as a Service

Self-service of applications dramatically streamlines daily operations and significantly reduces the wait for specialized resources to realize the vision for IT-as-a-Service (ITaaS).

Calm uses blueprints to control all aspects of the application’s lifecycle, such as creating, provisioning, scaling, and cleanup. By adhering to open API standards, blueprints allow developers and administrators to deploy applications across hybrid multi-cloud environments.

In fact, to accelerate automation, in addition to GUI based creation of blueprint, Calm also supports Python-based domain-specific language (DSL) for readable, version-controlled blueprints that can handle even the most complex application scenarios. Once created, a blueprint can be easily published to end users through the Nutanix Marketplace, instantly transforming a complex provisioning ticket into a simple one-click request.

This creates the perfect DevOps environment, where improvements for software development and testing with continuous integration (CI), delivery, and deployment (CD) pipelines, reducing complexity while improving quality and speeding delivery of full-stack application environments expressed as infrastructure and operations as code.

![](https://video.udacity-data.com/topher/2020/October/5f760503_screen-shot-2020-10-01-at-9.33.11-am/screen-shot-2020-10-01-at-9.33.11-am.png)

# QUIZ QUESTION
Which of the following statements are true of Nutanix Calm? Select all that apply.

* Calm uses blueprints to control all aspects of the application’s lifecycle

* Calm supports Python-based domain-specific language

* Calm orchestrates the provisioning, scaling and management of applications across environments

## When Will You Apply This Knowledge?

In 2020, most companies have a plan for how they’re going to make their transition to the cloud. But, at the same time, those companies are either struggling to execute their plans, or are not achieving their desired goals.

And they are facing challenges for two reasons. The first is a lack of organizational readiness. Moving to the cloud affects people and processes just as much as it does technology. A business that doesn’t fully understand and plan for the impact of these changes is going to struggle with cloud adoption.

The second is the main driver of the cloud strategy. Technology is only as valuable as the outcomes that it helps achieve. To succeed at cloud transformation, it’s essential to focus on business requirements first, and then match those requirements to technologies that will enable or facilitate them. Then, once the technologies that serve the business have been identified, the right mix of skills is needed to implement and execute that plan.

![](https://video.udacity-data.com/topher/2020/October/5f76065e_screen-shot-2020-10-01-at-9.39.02-am/screen-shot-2020-10-01-at-9.39.02-am.png)

As a hybrid cloud engineer, your role will be to help an enterprise plan and execute a successful cloud transformation.

A hybrid cloud engineer needs to be able to work with an organization to determine their readiness, and suggest corrective measures if an organization is not fully prepared. Among other things, this involves ensuring that all business requirements are clearly defined. SLAs need to be completely and clearly documented, as well as enforceable. Then, using these SLAs, the right infrastructure for each service needs to be chosen.

Once the business requirements have been defined, documented, and agreed upon, the next major task before the hybrid cloud engineer is implementation. The hybrid cloud engineer needs to plan and execute the migration, which includes refactoring applications for the best possible TCO and ROI.

After migration is complete, the hybrid cloud engineer needs to continuously monitor organizational and technical infrastructure. This is to ensure that performance is as projected and expected, and also to ensure that the SLAs defined during the planning stage are being met.

## Working with Business Stakeholders

Making the transition to the cloud touches nearly every major aspect of a business. So, it’s important to understand the current status of your people, processes, technology use, and application design and requirements, because these elements inform a cloud strategy decision.

To do this, you will need to have conversations with teams and business owners that:

Own, run, and manage applications
Handle compliance and security
Are responsible for the cost of making the transition to the cloud
Ultimately, your conversations will revolve around 8 major requirements:

Application portability
Compliance and security
Cost, including TCO and ROI
Scalability
Resilience and availability
Performance
Manageability
Data protection and recoverability
Having to address these items will eventually involve establishing dialogue with every decision maker in the business. But their role will only be to provide you with their requirements and the details of their business needs. From their input, you will derive the framework and requirements of your solution. You should also have mapped out the attributes of your required solution to specific business needs.

From that point forward, your role will be to take these attributes and turn them into SLAs. Those SLAs will provide a performance framework which can be monitored, managed, and enforced. They will also help with vendor evaluation. You’ll have a checklist against which to determine whether a solution provider can meet your needs and at what cost.

And finally, if modifications are needed to any aspect of the requirements, you can perform a cost-benefit analysis, determine the impact, and move forward with whatever is best for the business.

Gathering business requirements, determining solution attributes, and designing SLAs will help a business determine their cloud strategy and the solution that meets their needs

![](https://video.udacity-data.com/topher/2020/October/5f7606a8_screen-shot-2020-10-01-at-9.40.13-am/screen-shot-2020-10-01-at-9.40.13-am.png)

## Overview of the Upcoming Two Courses

### What will you learn in these courses?
Seasoned IT and cloud technology professionals must run their organization in the most efficient manner. The current revolution in the industry is the hybrid cloud, a blended experience of on-premise and multiple public clouds which offers choice for capacity, features, and fiscal management.

But having a hybrid cloud is just the beginning. The next step is to automate self-service workloads, governed with resource access, quotas, and life cycle operations delivered with an on-premises, private cloud, which offers capital expenditure cost, ultimate control, and high security. This is what we will be covering in these two courses.

The two courses that you’re about to begin as part of this nanodegree program are actually a single story told in two parts. You should know now that one of your goals as a Hybrid Cloud Engineer will be to leverage infrastructure, platform, and software as a service, both on-prem and off, so that you can establish a truly hybrid cloud. At its most basic level, that requires you to understand how to set up your workloads for the private cloud and, when needed, move those same workloads or extend them to the public cloud. So, in the next two courses, that’s exactly what we’re going to do.

Now, the centerpiece is going to be Nutanix Calm, which provides advanced application-level orchestration that transforms how IT teams manage applications and support the business. Very simply put, Calm automates how applications are created, consumed and governed.

So, in this course, we’re going to focus on Calm and application automation, but for a private cloud. Alongside a deep dive into Calm, we’re going to set up an application blueprint - a repeatable, reusable, automated application framework - that you can deploy on your private cloud with just a few clicks.

Then, in the following course, we’re going to broaden our perspective considerably and shift focus to the public cloud instead. We’ll talk about essential DevOps concepts that you’ll need to know to establish development and deployment workflows, and others that will shape the way you approach the problem of moving workloads to the cloud and setting up a hybrid cloud for your organization. Then, we’ll talk about the public cloud itself, focusing specifically on AWS, and use that knowledge to extend the private cloud you created in this course into the public cloud.

And by the time you’re done with both courses, you’ll have a clear and practical understanding of what it means to build and design application blueprints for hybrid cloud deployments.

### Course Outline: On-Premises Private Cloud Automation
### Lesson 1: Managing Multiple Cluster and Workload Resources
* Prism Element vs. Prism Central
* Understanding Prism Central
* Prism Central and Governance
* Prism Central: Identity Management
* Prism Central: Role Based Access Control
* Prism Central: Categories
* Prism Self Service
* Prism Central: Image Management
### Lesson 2: Calm Automation for Application Lifecycle Management
* Calm basics
* VM IaaS for Self-Service IT
* Components of Calm Governance
* Calm Providers
* Calm Projects
* Calm RBAC
* The Nutanix Marketplace
### Lesson 3: Creating and Publishing a Single VM Blueprint
* The Importance of Calm Blueprints and Marketplace Publishing
* Publishing Your Own Application Blueprints
* Calm Marketplace Recap
* Calm Blueprints: Overview
* Working with Calm Blueprints
* Managing Blueprints
* Working with the Marketplace Manager
### Lesson 4: Creating and Publishing a Multi-VM Calm Blueprint
* Lesson Overview
* Calm Blueprint Lifecycle: Cloning a Blueprint
* Calm Blueprint Lifecycle: Downloading a Blueprint
* Calm Blueprint Lifecycle: Uploading a Blueprint
* Calm Services and Substrates
* alm Macros
* Calm Application Profiles
* Calm Actions
* Calm Library Overview
* The LAMP Stack
* Linux Administration
* Web Server Administration
* Load Balancers
* Creating a Multi-VM Calm Blueprint
### Lesson 5: Calm Automation for a Three-Tier Web Application with Lifecycle Management
* MySQL Database Server Administration
* Orchestration Dependencies Across Services
* Advanced Calm Actions
* Calm Orchestration and Macros
* Load Balancers
### Course Outline: Public and Hybrid Cloud Management
### Lesson 1: Strategies for Hybrid Cloud Design
* Infrastructure Provider Strategies
* Pets vs Livestock for Scalability
* DevOps for Agility and Operational Maturity
* Advanced Automation
* Immutable infrastructure and Build Artifacts
* Continuous Integration, Delivery, and Deployment
* Continuous Operations
* Advanced Calm Features
* Analogs to Linux, Cloud-init, Shell
* Protecting AHV VM Workloads with Microsegmentation and Flow Policies
* Nutanix Calm DSL
* Runbooks
* Prism Central APIs
### Lesson 2: Working with a Public Cloud Infrastructure Provider
* Public Cloud Overview
* Understanding Amazon Web Services
* Free tier: t2.micro and t3.micro
* EC2 Regions and Availability Zones
* AMI
* Security Groups
* SSH Keypairs
* IAM
* VPC
* Elastic IPs and DNS
### Lesson 3: Implementing Hybrid Cloud Scalability and Deployment Choice
* Adding an AWS Provider to Calm
* Scalability and Global Load Balancing Considerations
* Global Load Balancing Between Infrastructure Providers
* Architecting for Access
* Calm Application Profiles: Advanced
* Application Profiles Recap
* Multiple Application Profiles
* Application Profile Best Practices
### Lesson 4: Hybrid Cloud Governance
* Managing Costs in a Hybrid Cloud Environment
* Elements of a Cost Optimization Solution
* Cost Governance with Xi Beam
* Configuring a Cost Governance Policy in Xi Beam
* Configuring Cost Policies
* Creating a Scope
* Nutanix and AWS Cost Configuration
* Eliminating Unused Resources
* Rightsizing Underutilized Resources
* Reserved Instance Purchases and Exchanges
* Nutanix TCO Configuration
* Cluster and VM Costing
* Driving Financial Accountability Through Chargeback
* Budget Alerts
* Custom Reports

## Tools, Environment & Dependencies

You do not need to install any software for the exercises or projects in these courses, and it is not possible for you to execute the software on your local system.

The Udacity workspaces you are provided in the classroom are all that you need. These workspaces provide access to:

* Nutanix Frame virtual desktop: Windows 10
* Nutanix Private Cloud cluster:
* Acropolis with AHV hypervisor: AOS 5.15
* Prism Central with Nutanix Calm 3.x enabled

## Project Overviews

### Project Overviews
Each of the following courses has a project at the end of it, where you will have a chance to further develop and demonstrate your skills and understandings.

### Project - Private Cloud SaaS: Three-Tier Web Application
In the project at the end of the On Premises Private Cloud Automation course, you will:

* Create a three-tier web application blueprint that satisfies the IaaS business requirements for self-service private cloud deployment and security scenarios.
* Enhance the blueprint to provide PaaS by configuring the web application and creating web-tier scaling. Test the web application works by confirming scale-out load balancing across the web tier and database write updates.
* Enhance the blueprint to provide an action to update the database password and update the web application to use the new password, achieving a SaaS-like experience for developers with delegated, post deployment operations. Test the web application works with the new password.

### Project - Hybrid Cloud SaaS: Three-Tier Web Application
In the project at the end of the Public and Hybrid Cloud Management course, you will extend your three-tier web application blueprint to the public cloud in order to maximize high availability and provide scalable performance. In addition, you will be tasked with creating small and medium deployment scenarios.

### Good Luck!




________________________________________________________________________________________________________________________________________________________________________________
________________________________________________________________________________________________________________________________________________________________________________




# THIRD COURSE ON-PREMISES PRIVATE CLOUD AUTOMATION 

# LESSON 1 MANAGING MULTIPLE CLUSTER AND WORKLOAD RESOURCES

# Course Overview

### Welcome and Course Overview
Welcome to the course On-Premises Private Cloud Automation!

In your earlier studies about the modern private cloud infrastructure, you’ve learned about the evolution of the modern hybrid cloud. We discussed the drawbacks of legacy IT infrastructure in keeping up with the speed of business today. We introduced you to the Nutanix hybrid cloud by explaining how it is a modern, software-defined solution that natively integrates all IT resources to run any application. We also walked you through how this solution provides a simple, yet effective approach to maintain security, manage VMs, simplify networking, and implement disaster recovery.

In this course, we will cover various tools and features that Nutanix provides to eliminate the tedious, time-consuming process of manually operating parts of the cloud. We will walk you through how Nutanix Prism and Nutanix Calm increase visibility and eliminate IT intervention in performing repetitive, laborious tasks.

We will discuss how Nutanix Prism helps you manage multiple clusters and workloads. We will also illustrate how Nutanix Calm delivers simple, repeatable, and automated management of application creation, consumption, and governance. We have also included demo videos explaining these features and processes in the Nutanix environment.

## Lesson Overview

Welcome to the first lesson of this course, Managing Multiple Cluster and Workload Resources.

In this lesson, Prism will be our prime focus. Prism is our management plane of the hybrid cloud solution responsible for providing visibility into the cloud infrastructure. In this lesson, we will explain the difference between Prism Element and Prism Central. We will describe some of the key features of Prism Central such as identity management, role-based access control, image management, self-service, and categories. These features contribute in effective management of VMs and workloads.

By the end of this lesson, you will be familiar with how to manage categories, images, and create custom roles. You will also explore how to configure projects using Prism Self Service.

Let’s get started!

## The Big Picture

In your previous studies about modern private cloud infrastructure, you learned how to operate VM workloads on a single Nutanix cluster with the AHV hypervisor. When you have more than one Nutanix cluster, management can become split and uncoordinated between each cluster. You must reproduce your work in each cluster to have a consistent configuration, governance policy, and resources. The on-premise management problem compounds quickly when you have multiple Nutanix clusters with different hypervisors, as many of our customers do! Furthermore, the public cloud typically represents even further fragmentation as a separate silo for IT governance, operations, and security, so we will address hybrid cloud management in a later course.

In this first lesson of this course, we'll introduce you to the advanced version of the Prism control plane, which manages multiple clusters and provides additional facilities across those clusters, allowing management at scale. Nutanix Prism Central unites management across all different types of Nutanix clusters and their workloads, from a single pane of glass preventing the need for multiple consoles. Rather than learn about all of the capabilities and features of Prism Central, we will focus on governance with projects and roles, AHV VM image management, and Calm automation.

## Introduction to Cluster and Workload Management

It is easy and simple to work with one of anything because configuration and operations are instant and atomic. As soon as you have a second cluster, your configuration and operational work can easily double in order to maintain consistency! You have crossed over to the new world of scale, where we work to eliminate any single points of failure in our infrastructure, architecture, operations, and culture. Working at scale provides many new challenges for failures and remediation, but this is how organizations mature to tackle bigger initiatives with faster time to market.

![](https://video.udacity-data.com/topher/2020/September/5f527ad0_need-for-application-automation/need-for-application-automation.png)

![](https://video.udacity-data.com/topher/2020/September/5f729138_screen-shot-2020-09-28-at-6.42.03-pm/screen-shot-2020-09-28-at-6.42.03-pm.png)

To enable delegation for customer self-service as well as automation, there must be guard rails for safety, security audits, and resource management. All of these topics fit under the umbrella of governance and they must be addressed altogether systematically. When governance and operations are divided across multiple systems, the fragmentation it causes makes it harder to achieve consistency while also driving up complexity. As a hybrid cloud engineer, the trade offs between governance, consistency, and convenience are critical evaluations you must make for short-term and long-term business requirements.

## Prism Element vs. Prism Central

Nutanix Prism provides central access for administrators to configure, monitor, and manage virtual environments in a simple and elegant way. Prism is a part of every Nutanix deployment and has two core components, Prism Element and Prism Central. Let us explore the difference between the two.

### Management
The primary difference between Prism Element and Prism Central is its capability of management. Prism Element provides the ability to fully configure, manage, and monitor Nutanix clusters running any hypervisors. However, Prism Element can only be used to manage a single cluster.

Alternatively, Prism Central allows you to manage different clusters across separate physical locations on one screen and offers an organizational view into a distributed environment.

### Example
To simplify, think of Prism Central as the manager of managers. Whether you have a single Nutanix cluster in your datacenter or as an example, let us say you have 10 remote offices each running a Nutanix cluster, and you also have a Nutanix cluster at HQ, Prism Element is the one managing the individual clusters.

Prism Central is your single pane of glass that allows you to simply manage all of your Nutanix clusters no matter where in the world they are located.

### Architecture
Prism Element is a distributed service within every Nutanix cluster and provides users access to the distributed system. Prism runs on every node in the cluster and, like other components, it elects a leader. The system forwards all requests from followers to the leader. If the Prism leader fails, the system elects a new leader. This configuration allows administrators to access Prism using the cluster IP or any Controller VM (CVM) IP address.

![](https://video.udacity-data.com/topher/2020/July/5f15f728_prism-element-vs-prism-central-image1/prism-element-vs-prism-central-image1.png)

Prism Central is an application you can deploy in a VM – that is, a Prism Central VM – or in a scale-out cluster of Prism Central VMs, a Prism Central instance. This can be done either manually, by importing a VM template, or through one click from Prism Element.

![](https://video.udacity-data.com/topher/2020/September/5f527f26_prism-element-vs-prism-central-image2/prism-element-vs-prism-central-image2.png)

The Prism architecture allows users to scale an instance up and out to address changing conditions.

This extensible architecture allows you to enable value-added features and products, such as Prism Pro enhanced features, Calm automation, Flow networking within the Prism Central. These additional features operate within a single Prism Central VM or clustered Prism Central instance and do not require you to design, install, or deploy separate products.

## Quiz: Prism Element vs. Prism Central

### Quiz: Prism Element vs. Prism Central
QUESTION 1 OF 2
Which core component of Prism provides a single pane of glass for managing multiple clusters?

* Prism Central

### QUESTION 2 OF 2
In a datacenter with 30 remote offices with each running a Nutanix cluster. Which core Prism component is responsible for managing the individual Nutanix cluster at each remote office?

* Prism Element

## Understanding Prism Central

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/291.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/292.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/293.jpg)

Prism is powered by advanced data analytics and heuristics and rich automation and combines several aspects of infrastructure management into a single, easy-to-use solution.

Prism Central provides a comprehensive set of features, we will focus on five primary features. Let us go through them one by one.

![](https://video.udacity-data.com/topher/2020/September/5f527bd4_understanding-prism-central-image1/understanding-prism-central-image1.png)

### Identity Management
The primary aspect of security is ensuring that only trusted users are provided with access to the cloud environment. Prism offers two types of user accounts for authentication.

The first type is local accounts where you can create and manage users within the given Prism instance. The second type of account is authentication based on Identity Provider (IDP), which serves as an authentication source to control access to Prism.

### Role-based Access Control (RBAC)
Prism Central provides IT administrators with role-based governance that limits user operations based on their role and permissions. You can maintain granular control over which IT staff can perform specified actions on entities such as VMs, applications, reports, and clusters.

### Categories
Prism Central enables you to group entities into a key-value pair called category. Typically, new entities are assigned to a category based on some criteria. Policies can then be tied to those entities that are assigned a specific category value.

Categories allow you to implement various policies across entity groups, and Prism Central allows you to quickly view any established relationships.

### Self-Service
One of the core capabilities that developers and business users love in the hybrid cloud is the ability to provision applications and virtual machines without the intervention of IT. Having development teams and lines of business satisfy IT needs through self-service using a private cloud model can help them be more productive, decrease time to market, and save IT staff time.

Prism Self Service radically simplifies application development and delivery, and brings automation to the process.

### Image Management
Image management plays a vital role when dealing with a higher number of clusters. Prism Central provides a highly available repository for your images. These images may be guest OS ISOs or your application disk images, which are uploaded through Prism Central and stored on a cluster.

## Quiz: Understanding Prism Central

### QUESTION 1 OF 2
Which Prism Central feature enables you to group entities into a key-value pair?

* Categories

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/294.jpg)

## Prism Central and Governance

Governance of resources is another primary aspect of Prism Central. Now that we’ve covered the various features of Prism Central that help in management of multiple clusters and workload, let’s next explore how Prism Central helps you achieve IT governance. If you are new to IT governance, don't worry, we will cover the basics.

### Introduction to IT Governance
IT governance is an element of corporate governance, intended at enhancing the overall administration of IT and reaping improved value from investment in information and technology.

It empowers businesses to manage their IT risks effectively and assure that the activities connected with information and technology are aligned with their overall business objectives.

### Challenges of Achieving IT Governance
In a real-time environment, tracking cloud consumption for efficient use is often a manual process.

A general lack of visibility into who is using what resources make it challenging for managers to predict future consumption, manage resources, and analyze risk. This lack of visibility into cloud usage can also result in resources being overutilized and becoming unavailable to the users for whom they were initially provisioned.

### IT Governance Using Prism Central
IT governance can be achieved only when there is a provision to visualize IT resource consumption, analyze risks, and plan for future requirements. Prism Central caters to these requirements through the following capabilities:

![](https://video.udacity-data.com/topher/2020/September/5f527c94_prism-central-and-it-governance-image1/prism-central-and-it-governance-image1.png)

### Infrastructure Management
Prism Central can manage your global Nutanix HCI infrastructure from one console. Prism simplifies and streamlines common workflows to make hypervisor and workload management as easy as checking your email.

### Just in Time Forecast
Prism provides IT teams with visibility into how capacity is being used, an accurate forecast on how it will meet business demands, and a real-time insight of any hidden waste.

### Automatic Remediation
It provides you with real-time performance behaviour of VMs, detects anomalies automatically, and enables the IT team to automate remediation.

### One Click Upgrades
Prism solves update reluctance by offering one-click upgrades for each product within a cluster. The one-click upgrade process downloads the next version or allows you to upload manually as needed.

## Quiz: Prism Central and Governance

### QUIZ QUESTION
Select the four capabilities of Prism Central that help in achieving IT governance.

* Infrastructure management
* Automatic remediation
* One click upgrades
* Just in time forecast

## Identity Management

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/295.jpg)

Previously, we had briefly covered various features of Prism Central that help organizations manage a multi-cluster environment. Going forward, we will dive deep into each of these features and explain its significance.

The first feature we will be discussing is identity management. Let’s understand how authentication and authorization are the key components of identity management.

Authentication is all about verifying a user's identity against a trusted source of truth like Active Directory or any other IDP (Identity Provider). Once the identity has been authenticated, the next piece is to determine what they are authorized to do or what they can access; this is the authorization piece.

To ensure that trusted users are provided with access to Prism, Prism Central supports user authentication. It is important to know user authentication because it is the fundamental requirement to configure other Prism Central features such as Role-Based Access Control and Prism Self Service. The user accounts configured are later used to assign Role-Based Access Control and create a project using Prism Self Service. There are three authentication options within Prism Central.

### Local User Authentication
Each Nutanix cluster includes a Prism Central admin user account that is created automatically. You can add more locally defined users as needed and update the permissions as necessary.

### Active Directory Authentication
Users can authenticate using their Active Directory or OpenLDAP credentials when Active Directory support is enabled for Prism Central.

Active Directory (AD) is a directory service implemented by Microsoft for Windows domain networks. OpenLDAP is a free, open source directory service, which uses the Lightweight Directory Access Protocol (LDAP), developed by the OpenLDAP project. Nutanix currently supports the OpenLDAP 2.4 release running on CentOS distributions only.

### SAML Authentication
Users can authenticate through a qualified identity provider when SAML support is enabled for Prism Central. The Security Assertion Markup Language (SAML) is an open standard for exchanging authentication and authorization data between two parties, ADFS as the identity provider (IDP) and Prism Central as the service provider.

As mentioned earlier, once user authentication is configured, you can later use these user groups/accounts to assign explicit roles and permissions.

## Quiz: Identity Management

### QUESTION 1 OF 2
Which are the three authentication options available in Prism Central?

* Local User Authentication
* Active Directory Authentication
* SAML Authentication

### QUESTION 2 OF 2
Which authentication option in Prism Central when enabled lets users authenticate using their OpenLDAP credentials?

* Active Directory authentication

## Exercise: Identity Management

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/296.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/297.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/298.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/299.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/300.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/301.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/302.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/303.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/304.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/305.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/306.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/307.jpg)

## Role-Based Access Control

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/308.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/309.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/310.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/311.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/312.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/313.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/314.jpg)

In large enterprises, it is essential to control the level of access across users. For instance, hardware resources are costly, shared, and in limited supply. Allowing all users to consume, manage, and monitor IT resources can lead to fast and inefficient consumption of resources. Thus, we want to restrict a selected group of users to manage them - someone like an infrastructure admin. However, entities like VMs, applications, clusters, etc. are best defined by the corresponding administrators. So you would want to allow corresponding administrators to access such entities but prevent them from altering hardware resources.

Consider another example, where you are dealing with vendors or contractors. Allowing these users to view or edit sensitive and confidential information can lead to a security breach. In such scenarios, you would want to restrict them from editing certain details of a project and also selectively limit access to certain resources.

All this can be implemented with Role-Based Access Control and Prism Central makes it a simpler process.

Role-based access control ensures that only specified individuals get access to the data they should have access to and all access, requests, and grants are fully auditable.

Prism Central supports role-based access control (RBAC) that you can configure to provide customized access permissions for users based on their assigned roles.

## Built-in Roles
To simplify the process of creating roles and providing access permissions, Prism Central includes a set of pre-built roles that are defined by default. Let us explore each of these roles and their corresponding access permission.

* Super admin: Full administrator privileges.
* Prism admin: Full administrator privileges but cannot create or modify user accounts.
* Prism viewer: View-only privileges.
* Self-Service admin: Permissions to manage cloud-oriented resources and services.
* Project admin: Manages cloud objects such as roles, VMs, apps, and marketplace belonging to a project.
* Developer: Has access to develop, troubleshoot, and test applications in a project.
* Consumer: Has access to deploy applications and blueprints in a project.
* Operator: Has access to the run actions on deployed applications in a project.
* The project admin, developer, consumer, and operator roles are available when assigning roles in a project.

### Custom Roles
If the built-in roles are not sufficient for your needs, you can create one or more custom roles. But these features are restricted to AHV only.

### Creating a Custom Role
To create a custom role:

* Go to the roles dashboard.
* Click the Create Role button.
* Enter a name for the new role and describe the role.
* Select an entity, the permissions listed for that entity are listed.
* Select the permissions you want to apply. If you want to specify custom permissions, click the Change link and check all the permissions you want to enable.
* Click Save.

![](https://video.udacity-data.com/topher/2020/September/5f527d17_role-based-access-control-image1/role-based-access-control-image1.png)

### Modifying a Custom Role
To modify a custom role:

* Go to the roles dashboard.
* Select the desired role from the list.
* Select Update Role from the Actions pull-down list.
* Update the field values as desired.
* Click Save.

## Quiz: Role-Based Access Control

## QUESTION 1 OF 3
Which of the following statements are true about Role-based Access Control (RBAC)? Select two.

* RBAC ensures that only specified individuals get access to the data they should have access to.
* Prism Central supports RBAC that you can configure to provide customized role based access permissions for users.

### QUESTION 2 OF 3
What is the access privilege for a Prism Administrator?
* Full administrator privileges but cannot create or modify user accounts.

### Matching Quiz - Scenario
Consider a scenario in which you are the Super Admin, where one of your main responsibilities is managing all user access. You also have 4 users you wish to support:

* Alice is your Prism expert. You wish to give enough access such that Alice can administer the cluster but you don’t want Alice to have access to manage user accounts.
* Rayshawn is an infrastructure admin within your organization, so you wish to give him the ability to deploy and manage cloud-oriented resources.
* Olivia and Owen are developers in your organization working on a project, so they need to be able to test, develop, and troubleshoot the applications in a project.
* Additionally, you also have a group of users, let’s call them Group A, who should only be able to deploy applications in the project.}

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/315.jpg)

## Categories

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/316.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/317.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/318.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/319.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/320.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/321.jpg)

## Introduction to Categories
Categories are used to define groups of entities in which policies and enforcement are applied. They typically apply, but are not limited to: environment, application type, application tier, etc.

These categories can then be used by policies to determine what rules/actions to apply.

For example, you might have a Department category that includes values such as engineering, finance, and HR. In this case, you could create one backup policy that applies to engineering and HR and a separate backup policy that applies to finance. Categories allow you to implement various policies across entity groups, and Prism Central allows you to quickly view any established relationships.

The following hypothetical example illustrates the relationship of four policies (BackUpBasic, EngineeringEnvironment, Hourly alerts, and Daily backup) tied to three departments (Engineering, Finance, and HumanResources) that apply to 30+ VMs in each department.

![](https://video.udacity-data.com/topher/2020/September/5f527d70_categories-image1/categories-image1.png)

### Creating a Category
To create a category:

* Go to the categories dashboard.
* Click the Create Category button.
* Enter a name, and describe the category purpose.
* Enter a category value in the Value field.

You can add a second and subsequent value for a category. To do that, click the plus sign (+). Enter the next value. Repeat this step for all the values you want to include in the category and click Save.

For example, if the category name is Departments, values might include Engineering, HR, Sales, Marketing, and so on.

![](https://video.udacity-data.com/topher/2020/September/5f527daf_categories-image2/categories-image2.png)

## Modifying a Category
Built-in categories cannot be modified or deleted. To update an existing custom category:

* Go to the Categories dashboard.
* Select the desired category from the list.
* Select Update from the Actions pull-down menu.
* Update the field values as desired.
* Click Save.

### Deleting a Category
* Go to the Categories dashboard.
* Select the desired category from the list.
* Select Delete from the Actions pull-down menu.
* Click OK when prompted.

Note: You cannot delete a category if it is used in an existing policy. All associations with existing policies must be removed before a category can be deleted.

### Assigning a Category
To assign a category value to one or more entities, such as cluster, VM, image, or subnet:

* Go to the entity type dashboard.
* Select all the entities of that type you want to tag with the same category value.
* Select Manage Categories from the Actions pull-down menu.
* In the Manage [Cluster|VM|Image|Subnet] Categories page: a. Enter a category name. b. Select the target value from the list. c. Click the plus sign (+) to assign that category value to the selected entities. Repeat this step to assign a value for a second category.
* Click Save.

Note: Categories support multi-cardinality, which means you can assign multiple category values to the same entity.

## Categories

### QUESTION 1 OF 3
What is the purpose of Categories?
* Categories are used to define groups of entities in which policies and enforcement are applied to.

### QUESTION 2 OF 3
An entity can be assigned with multiple category values. State true or false.

* True

### QUESTION 3 OF 3
You are heading a project in which you are deploying 100 Linux VMs and around 150 Windows VMs. You want a set of users, Group A, to only have view access to the Linux VMs and the Windows VMs. You also want another set of users, Group B, to have edit access to the Windows VMs. Thus, you create 2 roles, one for edit access to VMs and the other for view access to VMs.

Many more Windows and Linux VMs are expected to be eventually added. As the number of VMs is expected to grow, you do not want to manually configure the roles every time a VM is added. How will you create the newly added VMs to automatically obtain the permissions?

* Create 2 categories, one for Windows VMs and one for Linux VMs. Assign Group A with view access to Windows and Linux Category. Assign Group B with edit access to the Windows VMs.

## Prism Central Projects

A well-designed hybrid cloud can allow IT users—such as developers and line-of-business managers—to gain access to IT infrastructure and services through a self-service portal. This not only gives administrators with immediate access to services, but also reduces the burden on IT since it no longer has to serve as the middleman.

Prism Self Service represents a special view within Prism Central. While Prism Central enables infrastructure management across clusters, Prism Self Service allows end users to consume that infrastructure in a self-service manner.

Administrators can then set up self-service access for their Nutanix environment in a few clicks out of Prism Self Service.

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/322.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/323.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/324.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/325.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/326.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/327.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/328.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/329.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/330.jpg)

### Working with Projects in Prism
The Prism Self Service feature allows you to create projects where consumers of IT infrastructure within an enterprise—individual users or teams such as development, test, and DevOps—can provision and manage VMs in a self-service manner, without having to engage IT in day-to-day operations.

### What is a Project?
A project defines a set of Active Directory users and groups with a common set of requirements or a common function, such as a team of people collaborating on an engineering project.

### Creating a Project

Before creating a project ensure to configure authentication.

To create a project, navigate to the Projects dashboard and click the Create Project button. On the page that is displayed, you must provide information in five major sections: General Settings; Cluster; User, Groups, and Roles; Network; and Quotas. Of these, Quotas is optional.

A quota specifies a usage limit on an infrastructure resource (compute, memory, or storage) for the project. Project members cannot use more than the specified limit.

A quota does not guarantee the project a certain amount of infrastructure resources. Instead, it ensures that a single project or a small number of projects do not overrun the infrastructure.

If the Nutanix cluster runs out of a resource, project members might not be able to use the resource even if the project has not reached its specified limit. However, if a project requires more resources, you can increase its quota.

If you do not specify a quota, no usage limit is applied. However, usage statistics are collected even if you do not specify a quota.

On the Create Project page:

* In the General Settings section, enter a name and description for the new project.
* In the Cluster section, select the target cluster on which the project has to be created.
* Add Users, Groups, and Roles.
* Check Allow Collaboration, to allow any group member to see the VMs, applications, and other objects created by other members of the group.
* Select the usable network and the default network for the project.
* Optionally, you can check the Quotas box to specify usage limits for compute, storage, and memory.
* Click Save.

![](https://video.udacity-data.com/topher/2020/September/5f527e39_prism-self-service-image1/prism-self-service-image1.png)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/331.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/332.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/333.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/334b.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/335.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/336.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/337.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/338.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/339.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/340.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/341.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/342.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/343.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/344.jpg)

### Modifying a Project
To modify an existing project:

* Go to the projects dashboard.
* Select the target project.
* Select Update Project from the Actions pull-down menu.
* Update the field values as desired.
* Click Save.
* Deleting a Project

### To delete a project:

* Go to the projects dashboard.
* Select the target project.
* Select Delete from the Actions pull-down menu.
* Click OK.

Note: Before you can delete a project, you must first remove any VMs and networks, in that order, from the project.

## Quiz: Prism Central Projects

### QUESTION 1 OF 3
How does Prism Self Service benefit the business?
* Reduces IT intervention

### QUESTION 2 OF 3
What happens if a quota is not specified when creating a project?
* No usage limit is applied for a project.

### QUESTION 3 OF 3
A project administrator creates a project on an AHV cluster and specifies a quota for storage. After a few days of usage, the project runs out of storage space. But when the project admin looks at the usage statistics, the project storage consumption is still below the specified quota.

What could be the possible reason for insufficient storage?

* The reason could be that the AHV cluster ran out of storage. A quota does not guarantee the project a certain amount of infrastructure resources.

## Image Management

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/345.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/346.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/347.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/348.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/349.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/350.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/351.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/352.jpg)

### Introduction to Image Management
Prism Central provides a centralized location to manage the images you require on registered AHV clusters.

The steps are shown in the next video:

[![IMAGE ALT TEXT](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/353.jpg)](https://www.youtube.com/watch?v=0iWBvGyTfKs&feature=emb_logo "Uploading An Image from a Remote Server")

## Uploading An Image from a Remote Server

The process of uploading an image from a Remote Server is very similar to the process of uploading from a workstation. The difference is instead of uploading an image file, you will specify the URL of the image in the Add Image page. You can also specify URLs to multiple images as part of a single operation.

When you specify image URLs, Prism Central uploads the images to all registered clusters. Uploading from a remote server also allows you to overcome file size limitations imposed by modern browsers. The file size limitation is usually 2 GB.

### Modifying an Image
To modify an image:

* Go to Images.
* Select the image you want to modify.
* Select Update Image from the Action pull-down menu.
* Make the desired changes.
* Click Save.

To delete an image, select the target image and then select Delete from the Action pull-down menu.

### Importing Images to Prism Central
You can import images from registered clusters and manage the images centrally from Prism Central. An image imported to Prism Central continues to reside on the cluster that owns it. Prism Central only creates and stores image metadata locally, and it uses that metadata when you perform an action on the image.

After you import an image, the image remains visible on the cluster from which you imported it, but you cannot update the image from the cluster. You can update the image only from Prism Central.

To import images:

* Go to Images.
* Click the import Images button.
* Select Import type. a. To import all images from all registered clusters, click All Images. b.To import all images from a selection of registered clusters, click Images On a Cluster, and then select the clusters. c. To import specific images from a given cluster, click the Select Images link provided for the cluster. Select the images that you want to import and click Done. d. Repeat this step for all the clusters from which you want to import images.
* To begin the import, click Save.

Prism Central imports the metadata of the selected images and marks the images as read-only entities on the clusters.

![](https://video.udacity-data.com/topher/2020/September/5f527e7a_image-management-image1/image-management-image1.png)

Before introducing image management, the image service ensured that uploaded images were saved to a cluster, and copied to additional clusters whenever you needed them, on-demand. As the number of clusters grew, on-demand replication of images became too slow. If you had narrow network links to remote locations, this could add to copy time, making this process frustrating.

Prism Central image management now enables you to upload images to the clusters and maintains an inventory of the images on them.

### Benefits of Image Management
The first key benefit is hands-free image replication to your clusters. Nutanix has built a simple, policy-based method to replicate images to the clusters where you decide they are needed. Simply upload new or updated images, and Nutanix Prism Central copies them everywhere you want them automatically.

The second key benefit is a simple, straightforward option to upload images through Prism Central and directly choose the clusters to copy them to. You can also simply place your images where you need them and then decide on replication later.

### Adding an Image

You can add an image by uploading it from a workstation or a remote server.

### Uploading an Image from a Workstation
Using this method, you can select multiple images and upload them as part of a single operation.

With this method of upload, Prism Central identifies a single registered cluster for each specified image and uploads the image to it. The choice of a cluster is random.

The image becomes active in Prism Element on the selected cluster and inactive on other clusters registered to Prism Central.

To upload an image from a workstation:

* Go to Images.
* Click the Add Image button.
* Navigate and upload the image file. a. Give the image a unique name. b. Select the image type. c. Describe the image. Repeat step 3 to add as many images as you want.
* Click Next.
* In the Placement Method, you can either assign categories to the images or manually select the target clusters.
* Click Save.

When you assign categories to images, image placement decisions are delegated to configured policies. When you choose to manually select the target clusters, you have the option to place on all clusters registered to the PC or only on a subset of registered clusters.

Here is a demo that provides you with a detailed explanation on the procedure.

## Quiz: Image Management

### QUESTION 1 OF 3
What happens when an image is imported to Prism Central?

* Prism Central imports the metadata of the selected images and marks the images as read-only entities on the clusters.

### QUESTION 2 OF 3
Which image upload method helps you overcome image file size limitations of modern browsers?

* Uploading an image from a remote server

### QUESTION 3 OF 3
An administrator wants to upload a 4 GB image file from a workstation. The administrator navigates to the Add Image page and then clicks the Add Image button. He then navigates to the location of the image, selects the image of his choice and clicks Open. The image upload fails. What could be the possible reason and how can it be fixed?

* Most modern browsers impose file size limitations that affect this upload method. If you must upload images larger than 2 GB, then you must upload the images from a remote server.

## Using Udacity Workspaces with Nutanix

### Using Workspaces in the Remainder of this Course

In this demo video, we walk you through how to use the workspaces in the classroom here to complete the exercise on the next page about image management, and all the upcoming exercises and projects that will be done in Nutanix Frame sessions.

The steps are shown in the next video:

[![IMAGE ALT TEXT](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/354.jpg)](https://www.youtube.com/watch?v=Pxmbm1FZ9FY&feature=emb_logo)


# VERY IMPORTANT FOR SOLVING THE THIRD PROJECT
## Exercise: Image Management

### Solution

* From the Frame desktop, open Windows Explorer (File Manager) on the Windows task bar and navigate to C:\Scripts. Double-click the CentOS8_URL.txt file. Copy the URL by highlighting the entire URL in the file, right-click and choose Copy from the menu. Close the file.

* From the Prism Central browser tab, select the <strong>Entities</strong> menu (the three-lined hamburger icon, upper left) and go to <strong>Virtual Infrastructure</strong> > <strong>Images</strong>.

* On the <strong>Images</strong> page, click <strong>Add Image</strong>.

* Click the URL radio button and paste the URL copied in step 1 to the <strong>Enter Image URL</strong> field:

https://cloud.centos.org/centos/8/x86_64/images/CentOS-8-GenericCloud-8.2.2004-20200611.2.x86_64.qcow2

* Click <strong>Upload file</strong>.

* Change the Image Name to <strong>CentOS.qcow2</strong>.

* Click <strong>Next</strong>.

* Leave the defaults and click <strong>Save</strong>.

* Go to the <strong>Tasks</strong> view and follow the import progress. This will take approximately 5 minutes to complete.

* Return to <strong>Entities > Infrastructure > Images</strong> page to verify the CentOS 8 image is present.

## Glossary

### Glossary of Key Terms in this Lesson
### Authentication
* Authentication is about verifying a user's identity against a trusted source of truth like Active Directory or any other IDP (Identity Provider).

### Authorization
* After a user has been authenticated, authorization determines what permissions/access they have, and what they are allowed or not allowed to do.

### Categories
Categories are used to define groups of entities in which policies and enforcement are applied.

### Image management
A Prism Central feature that enables you to upload images to clusters and maintain an inventory of the images on them.

### Image service
Ensures that uploaded images are saved to a cluster, and copied to additional clusters whenever you need them, on-demand.

### IT governance
IT governance is an element of corporate governance, intended at enhancing the overall administration of IT and reaping improved value from investment in information and technology.

### Prism Central
The Nutanix scale-out control plane to manage multiple joined Nutanix clusters and provide advanced management capabilities from a single pane of glass web console.

### Project
A project defines a set of Active Directory with a common set of requirements or a common function, such as a team of people collaborating on an engineering project.

### Quota
A quota specifies a usage limit on an infrastructure resource (compute, memory, or storage) for the project.

### Role-Based Access Control (RBAC)
Role-Based Access Control ensures that only specified individuals get access to the data they should have access to and all access, requests, and grants are fully auditable.

## Lesson Conclusion

To summarize, Prism Central manages multiple clusters across different locations and Prism Element manages an individual cluster. Prism is rich with various features that help to achieve IT governance.

In order to manage multiple clusters and workloads Prism supports:

* User authentication to authorize user’s identity.
* Role-Based Access Control to ensure right users have access to the right resources.
* Categories to define groups of entities for which policies and enforcement can be applied.
* Prism Self Service to create projects without IT intervention.
* Image management to manage images from a centralized location.


________________________________________________________________________________________________________________________________________________________________________________



# LESSON 2 CALM AUTOMATION FOR APPLICATION LIFECYCLE MANAGEMENT


## Lesson Overview

In the last lesson, we spoke at length about Prism Central and its capabilities, because Prism lays the foundation for automation in both private and hybrid clouds.

To give you some context, although they’re beyond the scope of this lesson, other Nutanix products – Karbon, for containers; Era, for databases; Prism Pro, a license that adds machine learning, analytics, and advanced automation to Prism – are all closely integrated with Prism. And to truly make the most of Calm, which automates application deployment and simplifies lifecycle management, it was important that you understand Prism in more detail than we covered in the <strong>Modern Private Cloud Infrastructure</strong> course.

Now that we’ve crossed that bridge, we can dive into the centerpiece of this Private Cloud Automation course – a product called Nutanix Calm.

Calm answers the growing challenge of enterprise application management, a problem that IT teams across the world have been wrestling with for years. It allows enterprises to address the challenges that arise from both the increasing volume of applications, as well as the increased complexity of the apps themselves. Calm accomplishes this by turning application management into streamlined, automated, and repeatable work.

In the rest of this course, we’ll walk through the various Calm capabilities that enable our vision of application automation.

We will start by introducing you to Nutanix Calm. We’ll talk about what Calm is, why it exists, and what it helps you accomplish. We’ll walk through several key capabilities, including providers, projects, role-based access control, and marketplace publishing.

By the end of this lesson, you will be familiar with how to publish blueprints to the marketplace for customer self-service, on-demand application workloads. You will also understand how to complete a deployment, audit, and deprovision for VM IaaS.

Let’s get started.

## A Growing Need for Simplification

Managing applications in an enterprise environment has grown increasingly challenging over the years.

The sheer number of applications has resulted in increased complexity. There is no single, central owner for apps – different teams own their own applications. Fragmented ownership results in knowledge silos, which in turn leads to a lack of productivity.

And finally, the growing popularity of hybrid models – with applications distributed across both private and public clouds – introduces management challenges as well.

To address the problem of increasingly complex application management, Nutanix offers Calm.

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/356.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/357.jpg)
![](https://video.udacity-data.com/topher/2020/September/5f528233_growing-need-for-simplification/growing-need-for-simplification.png)

## Application Management with Blueprints in Nutanix Calm

The success of the public cloud is generally due to rapid provisioning of facilities in an on-demand fashion under a "pay as you go" Operational Expenditure model. In order to replicate the cloud experience on-premise, a private cloud must offer self-service of automated facilities. There is a maturity in progression from IaaS to PaaS to SaaS to provide these experiences in a private cloud, and later you’ll learn to do this for a public, then hybrid cloud.

![](https://video.udacity-data.com/topher/2020/September/5f528451_importance-of-blueprints/importance-of-blueprints.png)

Blueprints are the heart of Calm - they model a business process for infrastructure, operations, and governance together. This unifies the different IT and application silos that normally fragment and slow the business. Blueprints can be exported as a JSON file and shared between people and unfederated Calm instances. It is a typical practice for blueprints to be placed under revision control, there are many Calm blueprints freely available in public Git repositories. In other words, Calm blueprints are software artifacts and they can encompass advanced software engineering practices, but do not be alarmed: we will progressively build up your familiarity with Calm capabilities over the remaining lessons through the easy-to-use Prism Central web console.

## What is Nutanix Calm?

Calm provides advanced application-level orchestration that transforms how IT teams manage applications and support the business. Fully integrated into the Nutanix platform, Calm delivers a powerful, common management framework that can be simultaneously leveraged by multiple IT teams to rapidly create and deliver applications.

By approaching applications as complete entities, not just virtual machines (VMs), Calm automates how applications are created, consumed and governed. Calm delivers simple, repeatable and automated management of applications across a variety of environments, including private and public clouds.

<srong>Automate, Empower, and Relax</strong>

Calm builds on the foundation laid by the Nutanix Enterprise Cloud. That foundation, as we discussed in the previous course consists of AOS, AHV, and Prism – providing an abstraction of hardware resources, native virtualization, and one-click operations.

On top of this, Calm provides two key capabilities: application automation and multi-cloud management.

Calm, whose name arose historically as an acronym for Cloud Application Lifecycle Management, has the ability to manage applications on and off of Nutanix infrastructure, giving hybrid cloud engineers the power to meet diverse business requirements across multiple providers and lifecycle operations from the birth to death of an application across hybrid cloud scenarios. As its name suggests, you should be able to automate, empower, and have a relaxing experience with Calm!

![](https://video.udacity-data.com/topher/2020/August/5f356908_screen-shot-2020-08-13-at-9.22.11-am/screen-shot-2020-08-13-at-9.22.11-am.png)

Application automation consists of three capabilities: app-centric automation and lifecycle management, policy-based governance, self-service provisioning.

Of these, self-service and governance themselves have three major components:

* Publishing blueprints to different groups using a policy-driven model
* Reducing miscommunication between teams
* Providing an alternative to roll-your-own cloud services while maintaining complete control and visibility over operations

Multi-cloud management involves abstracting applications from cloud infrastructure; deploying and managing applications on any cloud; and visibility and control of resource consumption.

<strong>Accessing Calm</strong>
Calm is accessed from Prism Central. Click the menu icon at the top right of the screen, select Services, and then click Calm.

Please watch the video:

[![IMAGE ALT TEXT](https://video.udacity-data.com/topher/2020/September/5f528493_accessing-calm-1/accessing-calm-1.png)](https://www.youtube.com/watch?v=2bp3cA_6qVY&feature=emb_logo)

Calm opens within the Prism Central window of your browser and you will see a new sidebar to the left of the page that gives you access to Calm’s capabilities. By default, when Calm opens, the Applications page will be displayed.

The sidebar options, in order from top to bottom, are Marketplace, Blueprints, Applications, Library, Settings, Marketplace Manager, and Projects. As we progress through this course, we will discuss these options in more detail.

![](https://video.udacity-data.com/topher/2020/September/5f5284bb_accessing-calm-2/accessing-calm-2.png)

## Quiz: What is Nutanix Calm?

### QUESTION 1 OF 3
Which of the following statements are true about Nutanix Calm? (Choose all that apply.)

* Calm treats applications as complete entities
* Calm automates how applications are created, consumed, and governed

### QUESTION 2 OF 3
How is Nutanix Calm accessed?

*Through Prism Central

You are working with the Senior IT Manager of a large financial services company, helping her and her team modernize their IT infrastructure. One of the items on their list - and yours - is to introduce some amount of automation to the ecosystem to reduce the company’s dependence on IT for manual, cumbersome tasks.

Because they are already running Nutanix, one of the applications that you have been evaluating is Nutanix Calm. After some study, you make a presentation of your findings to the IT Manager. She is interested, but having spent many years working with traditional, 3-tier architecture, she is concerned about adding another brand new piece of software with a brand new interface (and its own potential nuances) to the ones that her team is already working with.

Every new piece of specialized software requires specialized skills to use and she does not want to have to hire new team members exclusively to use one new product, especially when she isn’t yet confident of the benefits it will bring.

How do you respond to her concern?

### QUESTION 3 OF 3
Read the scenario above and choose the most appropriate response to the Senior IT Manager’s concern.

* Calm integrates with and follows the same UI design as Nutanix Prism. Since the team is already running Nutanix, Calm’s UI will be instantly familiar to them. Calm doesn’t add a new interface, it adds on to an existing one.

## Exercise: Enable Nutanix Calm

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/358.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/359.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/360.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/361.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/362.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/363.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/364.jpg)

## Generate an SSH Key Pair

### VM IaaS for Self-Service IT

### Linux OS, CentOS for a fast, license free base OS
For simplicity in operating system (OS) licensing and speed to provision a virtual machine (VM), we will focus on using Linux for our courses. Calm works equally well with Windows and nearly every facility we’ll learn with Linux has a compatible or analogous Windows feature.

Linux belongs to the family of Unix-like operating systems. It was written by Linus Torvalds and has the features that are typical of a modern Unix OS, including multitasking, virtual memory, shared libraries, demand loading, shared copy-on-write executables, proper memory management, and multistack networking including IPv4 and IPv6.

To use Linux, you need to download a distribution, which is a complete Linux system including the kernel and applications. Multiple distributions are available for download and one popular choice is CentOS.

The Community Enterprise Operating System (or CentOS) is a Linux distribution that provides a free, community-supported computing platform functionally compatible with its upstream source, Red Hat Enterprise Linux (RHEL) and uses open source licensing.

### SSH key pairs for secure access to Linux VMs
Public key authentication is preferred over the use of passwords, because it provides stronger cryptographic strength that even very long passwords cannot offer. Each SSH key pair includes two keys, a public key and a private key.

A public key is copied to a user account on the operating system, which is then used to encrypt data and allow secure access. This secured access requires using the corresponding private key to make the connection and unlock the OS user account on the VM.

A private key remains with a user and acts as proof of that user’s identity. A user will only be able to authenticate successfully with a server if they have a private key that corresponds to the public key used for encryption. Private keys can be password protected for further security if desired.

### Cloud-init for basic, dynamic, secure configuration
Cloud-init is the industry standard method across multiple Linux distributions for OS initialization. It is supported across all major public cloud providers, provisioning systems for private cloud infrastructure, and bare-metal installations. Linux distributions sometimes distinguish their variants between desktop, server, and cloud editions with only the latter having cloud-init facilities. Increasingly server and cloud editions have combined to offer cloud-init everywhere.

Cloud-init can identify the host infrastructure provider it is running on during boot, read any provided metadata, and initialize the system accordingly. This may involve setting up the network, adding storage devices, provisioning SSH access keys, and configuring many other aspects of the OS. Cloud-init will also parse and process any optional user or vendor data that was passed to the instance.

## Quiz: Generate an SSH Key Pair

### QUESTION 1 OF 2
What is a Linux distribution?

* A complete Linux system

### QUESTION 2 OF 2
SSH key pairs involve two keys, namely __.

*A public key and a private key

## Exercise: Generate an SSH Key Pair

In this exercise, you will create and configure an SSH key pair.

You will use this key pair in future exercises by inserting it into Calm blueprints to ensure secure access to Linux VMs.

After this exercise, there will be a video walkthrough.

<strong>Note: The vertical black bar on this page can be dragged as needed to adjust the size of the display fields.</strong>

* 1. Start your lab session by clicking “Access Lab,” and then, after a moment, “Start Streaming.”

* 2. Click the <strong>Start</strong> menu on your Frame desktop and select <strong>Cygwin64 Terminal.</strong>

* 3. Type the following commands in the Cygwin64 Terminal. After creating the .ssh folder, use the <strong>cd</strong> command to make <strong>.ssh</strong> your working directory:

```
cd /cygdrive/c/cygwin64/workspace

 mkdir .ssh

 cd .ssh
 ```

* 4. Create a new SSH key pair with the RSA algorithm. To do this, type:

```
ssh-keygen -t rsa
```

* 5. hen prompted to enter the file where the key will be saved, enter the file path:

```
./id_rsa 
```
 
* 6. Press <strong>Enter</strong>. Leave the <strong>Enter passphrase</strong> (empty for no passphrase): prompt empty and press <strong>Enter</strong> to use no passphrase.

* 7. Leave the prompt blank and press <strong>Enter</strong> again to confirm using an empty passphrase.

A key fingerprint and randomart image will populate the screen, confirming you have successfully changed the SSH key pair. Press <strong>Enter.</strong>

View the keys.

```
    ls -a
```

On the following new command prompt, type:
```
    ssh-keygen -t rsa -p -N "" -m pem -f /cygdrive/c/cygwin64/workspace/.ssh/id_rsa
```
<strong>This</strong> modifies the <strong>private</strong> key to ensure that the <strong>public</strong> key may be extracted <strong>from</strong> it and that the key pair can be used <strong>for</strong> password-less SSH authentication.

* 8. Close the Cygwin64 Terminal window.

## Exercise Solution - Generate an SSH Key Pair

Watch video for solution 

[![IMAGE ALT TEXT](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/365.jpg)](https://www.youtube.com/watch?time_continue=21&v=CKDBjZn7zQU&feature=emb_logo)

## Components of Calm Governance

Calm allows you to empower different groups in the organization to provision and manage their own applications, giving application owners and developers on-demand workloads while elevating infrastructure managers to cloud operators.

Calm provides powerful, application-centric self-service capabilities, while maintaining control with role-based governance that limits user operations based on role, such as IT operator, developer, or manager. Calm allows administrators to safely delegate different levels of operational management, reducing administrative staff work while simultaneously accelerating end-users.

Additionally, Calm logs all critical activities and changes for end-to-end traceability, aiding security teams with key compliance initiatives. For example, you can enable the development team to create, scale, and destroy test and development environments without filing IT ticket requests.

Development teams benefit from rapid provisioning times, while IT maintains control, traceability of user operations, and visibility into resource consumption.

So, in the context of Calm Governance, there are four major capabilities that we need to discuss:

![](https://video.udacity-data.com/topher/2020/September/5f52850f_components-of-calm-governance/components-of-calm-governance.png)

### Providers
Providers are public and private cloud service providers to deploy and govern your workloads and applications. Essentially, configuring a provider provides the required authorization for Calm to manage your applications using the provider’s resources.

### Projects
A project defines a set of users and groups with a common set of requirements or a common structure and function, such as a team of engineers collaborating on a product. The project also specifies the roles to associate with its members, networks that they can use, infrastructure to deploy onto, and (optionally) usage limits on infrastructure resources. You can also define the environment associated with a project, in case you want to publish the applications into the Marketplace.

### Role-Based Access Control
Role-Based Access Control (RBAC) lets you define different roles in an organization and assign permissions accordingly. Within Calm, RBAC enables organizations to control who can perform specific actions, including:

* Marketplace (publish, clone, provision)
* Blueprint (create, update, clone, delete, launch)
* Applications (manage, edit, create)
* Projects (add, update, assign resources)
* User (add, change, remove, roles)

### Marketplace Publishing
Before we discuss the Marketplace, it is necessary to talk about Blueprints. A Blueprint is the framework for every application that you model with Nutanix Calm. Blueprints are templates that describe all the steps that are required to provision, configure, and execute tasks on the services and applications that are created.

The Marketplace provides a set of pre-seeded application Blueprints that are available for you to use. The Marketplace is a common platform for both the publisher and the consumer, and provides you with the ability to provision an application instantly.

The Marketplace provides a one-click deployment experience for requesting applications or services. It presents a user with all the applications or services their projects and roles have the rights to access. The user can then select an application and deploy it, enjoying fully automated provisioning and scaling for both traditional multitiered applications and modern distributed services.

And finally, the Marketplace empowers organizations to consume services in a fully self-service manner at their own speed and includes built-in versioning to allow access to multiple revisions of blueprints.

## Quiz: Components of Calm Governance

### QUESTION 1 OF 3
Why is it necessary to configure a Provider in Calm?

* A configured Provider allows Calm to manage applications using the provider’s virtualization resources

### QUESTION 2 OF 3
What sort of information does a Calm Project specify? (Choose all that apply.)

* Roles of members in a project

* Infrastructure usage limits

* Infrastructure resources that project members can use

### QUESTION 3 OF 3
What is the Marketplace?

* A collection of application blueprints

## Calm Providers

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/366.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/367.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/368.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/369.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/370.jpg)

As discussed earlier, Providers are public and private clouds that you can use to deploy, monitor, and govern your applications.

### Supported Providers
Nutanix Calm supports the following hypervisors and cloud providers as of version 3.0, with additional support options planned for future releases:

AHV (the native Nutanix hypervisor)
VMware vSphere (ESXi) on any infrastructure (Nutanix and non-Nutanix)
Amazon Web Services (AWS) and AWS GovCloud
Google Cloud Platform (GCP)
Microsoft Azure and Azure GovCloud
Nutanix Xi (public cloud)
Kubernetes (Nutanix Karbon and GKE)
In general, you can configure one or more of these platforms as service providers if you want to create and use a blueprint to consume them. You can optionally specify costs for CPU, Memory, and Disk and these “show back” costs will be displayed during blueprint design and launch.

When using Nutanix as a Provider, note that all AHV clusters that are registered to the Prism Central instance from which you are running Calm are automatically added as providers. If you want to add a remote Prism Central instance as a provider, you must add that remote Prism Central instance as an account in Calm.

All other providers need to be configured manually, depending on the clouds that you intend to use.

### Configuring New Service Providers
At a very high level, to add a new service provider, you need to:

* Navigate to the Settings page in Calm.
* Click Providers at the top of the screen. By default, the Settings page opens on the General tab.
* Click + Add Provider.
* Name your provider and select the Type from the drop down menu.

You will then be required to provide configuration information specific to the type of provider you have selected.

For example, if you select Nutanix with the intention of using a remote Prism Central cluster, you will need to provide the Prism Central IP and port, as well as administrative credentials (username and password) for Calm to use.

On the other hand, if you select AWS, you will need to specify the Access Key ID, the Secret Access Key, and regions that you want included.

Please watch the video for instructions:


[![IMAGE ALT TEXT](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/371.jpg)](https://www.youtube.com/watch?v=rUum_ORNppY&feature=emb_logo)

## Quiz: Calm Providers

### QUESTION 1 OF 2
Which of the following infrastructure providers does Calm support? (may be more than one answer)

* AWS
* Azure
* AHV

### QUESTION 2 OF 2
What are the steps you need to follow to create and configure a Provider in Calm?

* Navigate to the Settings page in Calm.
* Click Providers.
* Click + Add Provider. 4.Name your provider, select the type, and configure the provider.

## Calm: Projects

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/372.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/373.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/374.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/375.jpg)

A Project is a set of users and groups with a common set of requirements or a common structure and function, such as a team of engineers collaborating on an engineering project. A Project also specifies the roles to associate with its members, networks that they can use, infrastructure to deploy onto, and (optionally) usage limits on infrastructure resources.

By using different projects assigned to different clusters and users, administrators can ensure that workloads are deployed the right way each time. For example, a developer can be a Project Admin for a dev/test project, so they have full control to deploy to their development clusters or to a cloud, while having Read Only access to production projects, allowing them access to logs but no ability to alter production workloads.

### Infrastructure
Infrastructure defines the type of Providers for a Project, and a Project can involve multiple types of infrastructure. As we discussed earlier, the Providers that Nutanix supports are Nutanix AHV, Nutanix Xi, VMware, AWS, Azure, GCP, and Kubernetes.

### Environment
The Project’s Environment allows you to add multiple credentials and the default infrastructure configuration for each selected Provider, these are typically your organization’s VM standards. You must configure the Environment before launching a pre-seeded blueprint from the Marketplace: the blueprint will use the environment settings to provision workloads.

An additional benefit to creating a project Environment, you can clone that configuration for the VM while configuring a Blueprint, saving design time while increasing adoption for a standard configuration.

### Credentials
Credentials help in abstracting identity settings while connecting to an external system. You can configure multiple types of credentials (either SSH key or password) and define them as part of the Environment configuration. You can use these configured project environment credentials when launching a pre-seeded application Blueprint.

### Creating a Project
To create a project, you need to click Projects on the Calm sidebar, and click + Create Project. On the page that is displayed, you need to provide information in four major sections: General Settings; Users, Groups, and Roles; Infrastructure; and Quotas. Of these, Quotas is optional.

A quota specifies a usage limit on an infrastructure resource (compute, memory, or storage) for the project. Project members cannot use more than the specified limit.

A quota does not guarantee the project a certain amount of infrastructure resources. Instead, it ensures that a single project or a few projects do not overrun the infrastructure.

If a Nutanix cluster runs out of a resource, project members cannot use the resource even if the project has not reached its specified limit. However, if a project requires more resources, you can increase its quota.

If you do not specify a quota, you cannot apply usage limits because the project has unlimited consumption. However, project usage statistics are collected on AHV workloads even if you do not specify a quota.

On the Create Project page:

* In the General Settings section, name the project and provide a description.
* In the Users, Groups, and Roles section, add users or user groups and specify the level of permissions they will have in Calm. User roles supported in Calm are:
* Project Admin
* Developer
* Consumer
* Operator
* In the Infrastructure section, select a Provider for use with your Project. Providers are configured separately, from the Settings page, as we discussed in the previous section.
* Optionally, in the Quotas section, specify usage limits for vCPUs, storage, and memory.

After you complete the required sections for the Project, click Save & Configure Environment. The next step in creating a project is setting up the Environment.

![](https://video.udacity-data.com/topher/2020/September/5f528551_projects-4/projects-4.png)

### Configuring the Environment
The Environment specifies the default VM infrastructure configuration used when launching a pre-seeded Marketplace blueprint for each provider.

Environment configuration depends on the provider(s) used in the project. For simplicity’s sake, we will describe the Environment configuration process for AHV.

After clicking the Environment tab, you will need to:

* Add credentials
* Select the Nutanix provider under VM Configuration
* Select an operating system (either Windows or Linux).
* Specify VM details, including name, images to be used, vCPUs and cores per vCPU, memory, disk size, vGPUs, network adapters, and so on.
* Confirm whether or not to check log on status after the VM is created, and specify the connection type and port.

Once you have provided all the required information, click Save to complete the process.

![](https://video.udacity-data.com/topher/2020/September/5f52857f_project-environment-1/project-environment-1.png)

### Modifying a Project
Modifying a Project gives you access to all of the same fields as creating one. To modify a Project, you need to:

* Navigate to the Projects page.
* Open the Project you want to modify.
* Update the sections as needed.
* Save your changes.

### Deleting a Project
Deleting a Project removes it entirely from Calm, with no way to recover it. For you to delete a Project, it must not be associated with an application or a blueprint. Calm will verify this when you attempt to delete a project and, if an association is found, it will prevent you from proceeding.

To delete a Project:

* Navigate to the Projects page.
* elect the checkbox next to the Project you want to delete.
* Select Delete from the Actions drop down menu.
* Click Delete when prompted for confirmation.

![](https://video.udacity-data.com/topher/2020/September/5f5285aa_project-delete/project-delete.png)

## Quiz: Calm - Projects

### QUESTION 1 OF 2
Why do you need to configure the Environment when creating a Project?
* The Environment specifies the VM configurations that are used when launching a pre-seeded blueprint from the Marketplace.

### QUESTION 2 OF 2
What are the steps involved in configuring a Project in Calm?

* Click Projects on the sidebar.
Click Create New Project.
Specify general settings; users, groups, and roles; and quotas (optionally).
Configure the environment.
Save the completed Project.

## Calm: Role-Based Access Control (RBAC)

As we briefly discussed in the previous section, Calm supports four different user roles:

* Project Admin
* Developer
* Consumer
* perator

Each role provides a different level of access to various Calm capabilities related to the Marketplace, Blueprints, Applications, Settings, the Task Library, Projects, and Users.

For example, in the Marketplace, a user with the Developer role can clone and edit app blueprints, make a publishing request for an application. A Project Admin, can do both those things, and send the app publishing request to an administrator. On the other hand, Consumers can only launch blueprints while Operators can only choose operations on existing, deployed workloads in their project. In other words, lower roles are subsets of higher roles.

It’s important to note here that the four roles listed here are also roles in Prism Central, and this speaks to how tightly integrated Prism Central and Calm are. By design, Calm inherits the RBAC configuration that you define in Prism. If you assign someone the role of Project Admin in Prism Central, for example, they will have access to Project Admin permissions in Calm as well.

For details about the permissions associated with each role, see the Roles and Responsibilities table of the Calm Admin Guide.

![](https://video.udacity-data.com/topher/2020/October/5f87d8cf_screen-shot-2020-10-14-at-9.54.22-pm/screen-shot-2020-10-14-at-9.54.22-pm.png)

## Quiz: Calm - RBAC

### QUESTION 1 OF 2
True or False: Roles in Calm must be configured to determine whether a user can access Calm from Prism Central or not.

* False, Roles provide different levels of access to various Calm capabilities related to projects, settings, users, and so on.

### QUESTION 2 OF 2
Study the table of Calm Roles and Access/Permissions available [here](https://portal.nutanix.com/page/documents/details?targetId=Nutanix-Calm-Admin-Operations-Guide-v271:nuc-roles-responsibility-matrix-c.html) and then answer the following question.

You have been assigned some blueprint creation work in Nutanix Calm. Based on the way your tasks have been explained to you, you understand that you need to be able to:

Create, update, and launch blueprints
Delete blueprints if necessary
Clone blueprints from the marketplace
Delete applications if needed
What is the minimum level of permissions and the associated role that you will need to perform these tasks? When choosing the role, apply the principle of least privilege. That is, choose the role that grants you the bare minimum permissions that you need to perform your work.

### QUESTION 2 OF 2
Study the table of Calm Roles and Access/Permissions available here and then answer the following question.

You have been assigned some blueprint creation work in Nutanix Calm. Based on the way your tasks have been explained to you, you understand that you need to be able to:

Create, update, and launch blueprints
Delete blueprints if necessary
Clone blueprints from the marketplace
Delete applications if needed
What is the minimum level of permissions and the associated role that you will need to perform these tasks? When choosing the role, apply the principle of least privilege. That is, choose the role that grants you the bare minimum permissions that you need to perform your work.

* Developer

## The Nutanix Marketplace

At the beginning of this lesson, we briefly talked about blueprints and the Marketplace. Let’s take a moment to discuss blueprints in a little more detail.

A blueprint is the framework for every application that you model with Nutanix Calm. Blueprints are templates that describe all the steps that are required to provision, configure, and execute tasks on the services and applications that are created.

Blueprints are essentially recipes for applications. These recipes encompass application architecture and Infrastructure choices, provisioning and deployment steps, application binaries, command steps, monitoring endpoints, remediation steps, licensing and monetization, and policies. Every time a blueprint is executed it results in an application deployment, these workloads can be managed from the Applications menu.

A blueprint turns an application into a single unit that can be managed by an infrastructure team. This makes application lifecycle management and deployment both automated and repeatable, freeing up the time that infrastructure teams are presently devoting to deploying and managing infrastructure and applications.

The Marketplace provides a set of pre-seeded application blueprints that are available for you to use. The Marketplace is a common platform for both the publisher and the consumer, and provides you with the ability to provision an application instantly.

Generally, the Marketplace displays a collection of blueprints available to the user’s projects. You can view application details, filter and search for custom or pre-seeded blueprints, clone a blueprint, or launch a blueprint from the Marketplace.

Please watch the video for instructions:

[![IMAGE ALT TEXT](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/376.jpg)](https://www.youtube.com/watch?v=NgEPwGe6aBk&feature=emb_logo)

### Viewing Application Details

licking a blueprint in the Marketplace will display a page with details about the associated application. Information includes hardware requirements, resources installed, platforms, limitations, and more.

![](https://video.udacity-data.com/topher/2020/September/5f5285d7_marketplace-app-details/marketplace-app-details.png)

### Filtering Blueprints

Creating a blueprint allows you to package automation steps into one centralized package that can be reused in any locale, updated as a whole bundle, and versioned to show the full lifecycle of an application or set of applications. Blueprints in the Marketplace are sorted into categories. You can use the category drop down menu to filter blueprints and find applications in specific categories. These categories are helpful in determining the purpose of the blueprint, and narrowing down your search - making it even easier to quickly deliver value to the business.

![](https://video.udacity-data.com/topher/2020/September/5f528611_marketplace-filter/marketplace-filter.png)

### Searching for Blueprints

The Marketplace also includes a search bar that allows you to search for a specific set of keywords appropriate to the type of blueprint you would like to use. Unlike Categories, where you are browsing a subset of a specific type of blueprint, searching can provide a more targeted list of results that can narrow the resulting scope to exactly what you are looking for.

![](https://video.udacity-data.com/topher/2020/September/5f52862d_marketplace-search/marketplace-search.png)

### Cloning a Blueprint
If you need to duplicate a blueprint and make customizations, the Marketplace allows you to clone a blueprint. All you need to do is:

* Select the Blueprint.
* Click Clone.
* ame the Blueprint.
* Assign it to a Project.

![](https://video.udacity-data.com/topher/2020/September/5f528655_marketplace-clone/marketplace-clone.png)

### Launching a Marketplace Item

Finally, you can also launch a Marketplace item to deploy the blueprint. We will cover this in more detail in a later lesson, but the basic process is quite straightforward.

On the Marketplace page, you need to:

* Click the application you want to launch and then click Launch.
* Name the application.
* Select an application profile.
* Verify the VM Configuration and Credentials.
* Click Create.

You can see a walkthrough video of these steps in the solution for the upcoming exercise.

![](https://video.udacity-data.com/topher/2020/September/5f52866e_marketplace-launch/marketplace-launch.png)

## Quiz: The Nutanix Marketplace

### QUESTION 1 OF 2
Which of the following activities can you perform in the Marketplace? (check all that apply)

* View application details

* Clone blueprint

* Search for application

* Launch application

You are consulting for the IT Department of a large outsourcing company. As part of their digital transformation and modernization efforts, the IT team is investing in technologies that enable self-service for their users, as well as several other automation efforts. They are already running Nutanix and have very recently introduced application automation via Calm to their portfolio of capabilities.

However, they’re stuck on the self-service portion of their activities. While they’re now starting to create Calm blueprints to make apps available to users, they haven’t yet decided on a distribution mechanism. Presently, they are discussing leveraging their internal engineering team to build a custom web portal for them, to which they can upload these Calm blueprints and make them available for their internal users to download and work with.

Do you agree with their approach?

### QUESTION 2 OF 2
Read the scenario above and choose the best way for the IT Department to move forward with enabling user self-service.

* No, they should be using Calm instead. Since they’re already creating blueprints in Calm, publishing to the Marketplace is the easiest way to enable self-service.

## Exercise: Create a Calm Project

### Series of Four Exercises
In this series of exercises on this and the upcoming pages, you will:

* Create a Calm project
* Use the project you created to publish a default blueprint to the Calm Marketplace.
* Launch the blueprint from the marketplace, name the application and audit the deployment process.
* Delete the application.

In each exercise, we will walk you through the steps to perform these tasks. There is also a video walkthrough on each of the following “Solution” pages.

### Creating a Calm Project
* 1. From the Prism Central browser tab, select the <strong>Entities</strong> menu (the three-lined hamburger icon, upper left) and go to <strong>Services</strong> and click <strong>Calm</strong>. If the <strong>Welcome to Calm</strong> pop-up window appears, close it.

* 2. Hover your mouse cursor over the icons at the far left of the Calm page to see each name. Click the <strong>Projects</strong> icon.

* 3. Click the <strong>+ Create Project</strong> button and use the values below to complete the General Settings section.

>>* Project Name: <strong>Test-Project</strong>
>>* Description: <strong>Test workload</strong>

* 4. To the right of <strong>Infrastructure</strong>, click <strong>Select Provider</strong> and select <strong>Nutanix</strong>:

>>* The pre-selected account should be: <strong>NTNX_LOCAL_AZ</strong>
>>* Click <strong>Select Clusters & Subnets.</strong>
>>* In the Select Subnets dialog box, select your cluster.
>>* Click the check box next to default-net and click <strong>Confirm.</strong>

* 5. Use the values below to set Quotas:

>>* <strong>vCPUs:</strong> 20
>>* <strong>storage:</strong> 1000
>>* <strong>Memory:</strong> 48

* 6. Click <strong>Save & Configure Environment.</strong>

A message showing <strong>Project data successfully accepted by server</strong> briefly appears. You will be switched to the Environment page. The <strong>Environment</strong> page allows you to define the components necessary to deploy a VM.

* 7. On the Environment page, the Linux configuration should already be expanded. Use the values below to configure the VM:

>>* <strong>vCPUs:</strong> 1
>>* <strong>Cores per vCPU:</strong> 1
>>* <strong>Memory (GiB):</strong> 2

* 8. Click the check box next to <strong>Guest Customization</strong>. In the Script field, hover your mouse cursor over the up-arrow icon in the upper right corner to reveal <strong>Upload script</strong>. Click <strong>Upload script</strong> and navigate to <strong>C:\Scripts)). Select the</strong> cloud-init.txt <strong>file and click</strong> Open**. This will upload the script to the script field:
```
 #cloud-config
     users:
      - name: centos
     ssh-authorized-keys:
 - @@{superuser.public_key}@@
 sudo: ['ALL=(ALL) NOPASSWD:ALL']
 ```
 * 9. Scroll down and expand the DISK (1) section to see the disk configuration. Use the information below to configure the disk:

>>* Type: <strong>Disk</strong>
>>* Bus Type: <strong>SCSI</strong>
>>* Operation: <strong>Clone from Image</strong>
>>* Image: <strong>Select the CentOS8 image</strong>
>>* Bootable: <strong>Select the check box</strong>

* 10. Scroll down to <strong>NETWORK ADAPTERS (NICS)</strong> and click the plus button to the right to add a NIC. Use the table below to configure the NIC:

>>* NIC 1: <strong>default-net</strong>
>>* Private IP: <strong>Select Dynamic</strong>

* 11. Scroll down to <strong>Connection</strong>. Click the <strong>Credential</strong> drop-down menu and select <strong>Add New Credential</strong>. Use the following information to configure the new credential:

>>* Credential Name: <strong>superuser</strong>
>>* Username: <strong>centos</strong>
>>* Secret Type: <strong>SSH Private Key</strong>
>>* SSH Private Key: In the upper right corner of the key field, click the box with the arrow, navigate to: <strong>C:\cygwin64\workspace.ssh\id_rsa</strong> and select <strong>Open.</strong> Ensure the inserted key text has <strong>-----BEGIN RSA PRIVATE KEY-----</strong> shown at the top. Click <strong>Done.</strong>

<strong>Note:</strong> Adding new credentials can also be done from the top of the page by clicking the + next to Credentials.

* 12. Ensure the box next to <strong>Check Log-in upon create</strong> is selected.
* 13. Scroll to the bottom of the page and click <strong>Save.</strong>
* 14. Click the <strong>Projects</strong> icon in the left column to see <strong>Test-Project</strong> in the Projects list.

Note: The <strong>HybridCloudEngineer</strong> project shown in the Projects list has the same configuration as your Test-Project.

## Exercise Solution: Create a Calm Project

Watch the video to follow the tutorial:

[![IMAGE ALT TEXT](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/377.jpg)](https://www.youtube.com/watch?v=stqznywSDd0&feature=emb_logo)

## Exercise: Publish Blueprint to Marketplace

* 1. Select the <strong>Entities</strong> menu (the three-lined hamburger icon) > <strong>Services</strong> and click <strong>Calm</strong>.

* 2. Hover your mouse cursor over the icons to the far left of the browser. Click the icon named <strong>Marketplace Manager</strong>. On the <strong>Marketplace Manager</strong> page, under the <strong>Marketplace Blueprint</strong> tab, you will find a default blueprint called <strong>ExpressLaunch</strong>.

* 3. Click the check box next to <strong>ExpressLaunch</strong> (default blueprint) in the <strong>Marketplace Blueprints</strong> view.

* 4. In the <strong>ExpressLaunch</strong> panel at the far right of your browser, remove the default project in <strong>the Projects Shared With</strong> drop-down menu. Select <strong>Test-Project</strong> and click <strong>Apply</strong>.

* 5. In the <strong>ExpressLaunch</strong> panel, click <strong>Publish</strong> and verify that the Status column for the blueprint shows <strong>Published</strong>.

* 6. Hover your mouse cursor over the icons to the far left of the browser. Click the <strong>Marketplace</strong> icon. You should see <strong>ExpressLaunch</strong> listed.

## Exercise Solution: Publish Blueprint to Marketplace

Watch the video to follow the tutorial:

[![IMAGE ALT TEXT](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/377.jpg)](https://www.youtube.com/watch?v=ovJNuzETmH4&feature=emb_logo)

## Exercise: Launch a Blueprint

* 1. Select the <strong>Entities</strong> menu > <strong>Services</strong> and click <strong>Calm</strong>.

* 2. Click the <strong>Marketplace</strong> icon in the left column.

* 3. Click the <strong>ExpressLaunch</strong> blueprint and click <strong>Launch</strong>.

* 4. Select <strong>Test-Project</strong>.

* 5. In the <strong<Name of the Application</strong> field, type Test-App and click <strong>Create</strong>.

* 6. When the view changes and you see <strong>PROVISIONING</strong>, click <strong>Audit</strong>. Expand the provisioning view. Continue to expand each new component as it appears to follow the provisioning progress to completion.

## Exercise Solution: Launch Blueprint

Watch the video to follow the tutorial:

[![IMAGE ALT TEXT](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/378.jpg)](https://www.youtube.com/watch?v=4rxk4fdZFEM&feature=emb_logo)

## Exercise: Delete an Application

* 1. Select the <strong>Entities</strong> menu > <strong>Services</strong> and click <strong>Calm</strong>.

* 2. Hover your mouse cursor over the icons at the far left of the browser. Click the <strong>Applications</strong> icon.

* 3. Select the checkbox next to <strong>Test-App</strong>.

* 4. Select <strong>Delete</strong> from the <strong>Action</strong> drop-down menu.

* 5. Click <strong>Confirm</strong> in the <strong>Delete Application</strong> dialog box.

* 6. Click <strong>Audit</strong> to monitor the <strong>Delete</strong> process.

<strong>NOTE: Make sure to delete applications when directed to do so. If left running, you will run out of cluster resources and will be unable to launch applications in future exercises.</strong>

## Exercise Solution: Deleting Application

Watch the video to follow the tutorial:

[![IMAGE ALT TEXT](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/379.jpg)](https://www.youtube.com/watch?v=u6A-1rpDFNE&feature=emb_logo)

## Glossary

### Blueprint - 
Blueprints are essentially recipes for applications. These recipes encompass application architecture and Infrastructure choices, provisioning and deployment steps, application binaries, command steps, monitoring endpoints, remediation steps, licensing and monetization, and policies. Every time a blueprint is executed it results in an application.

### Calm - 
See: Nutanix Calm, below.

### CentOS - 
A Linux distributable. For more information, see: Linux, below.

### Cloud-init - 
Cloud-init is the industry standard multi-distribution method for cross-platform cloud instance initialization. It is supported across all major public cloud providers, provisioning systems for private cloud infrastructure, and bare-metal installations.

### Linux - 
Linux belongs to the family of Unix-like operating systems. It was written by Linus Torvalds and has the features that are typical of a modern Unix OS. To use Linux, you need to download a distributable, which is a complete Linux system.

### Marketplace 
The Marketplace is a common platform for both the publisher and the consumer, and provides you with the ability to provision an application instantly.

### Nutanix Calm -
Nutanix Calm is a software product that provides advanced application-level orchestration that transforms how IT teams manage applications and support the business. Fully integrated into the Nutanix platform, Calm delivers a powerful, common management framework that can be simultaneously leveraged by multiple IT teams to rapidly create and deliver applications.

### Project - 
A project defines a set of Active Directory groups with a common set of requirements or a common structure and function, such as a team of engineers collaborating on a product. The project also specifies the roles to associate with its members, networks that they can use, infrastructure to deploy onto, and (optionally) usage limits on infrastructure resources.

### Providers -
Providers are cloud service providers, bare-metals, or existing machines that you can use to deploy, monitor, and govern your applications.

### Role-Based Access Control (RBAC) - 
Role-Based Access Control lets you define different roles in an organization and assign permissions accordingly.

## Lesson Conclusion

In this lesson, we described a number of key features in Calm – Providers, Projects, RBAC, and the Marketplace.

To quickly recap what we discussed:

* Providers are cloud service providers, bare-metals, or existing machines that you can use to deploy, monitor, and govern your applications.
* Projects specify the roles to associate with their members, networks that project members can use, infrastructure to deploy onto, and (optionally) usage limits on infrastructure resources.
* Role-Based Access Control (RBAC) lets you define different roles in an organization and assign permissions accordingly.
* And finally, the Marketplace is a common platform for both the publisher and the consumer, and provides you with the ability to provision an application instantly.

In later lessons, we’ll walk through how these capabilities come together to allow you to automate application deployments in Calm, so your users can deploy applications with just a few clicks.

________________________________________________________________________________________________________________________________________________________________________________

# LESSON 3 CREATING AND PUBLISHING A SINGLE VM BLUEPRINT 

## Lesson Overview

In this lesson and the next, we’re going to focus on <strong>blueprints</strong>. Blueprints are recipes for applications and infrastructure combined with their operations and governance. Enterprises derive a number of benefits from the one-click simplicity that they provide.

We’ll talk about this in more detail shortly, but the ability to turn an application into a repeatable, automated blueprint offers enterprises a number of benefits:

* Greater agility while minimizing human error
* Broader self-service capabilities while allowing IT to retain centralized control
* The ability to modernize app development by pairing Calm with a certified Kubernetes solution
* The ability to automate provisioning across multi-cloud architectures from a single management interface.

That’s why we’re going to spend the next two lessons on a deep dive into blueprints. In the previous lesson, you used one of the pre-seeded blueprints to deploy an application from the Marketplace. Now, we’re going to talk about how to turn an application into a marketplace blueprint that can be launched with a couple of clicks.

You can create two different types of blueprints based on the complexity of the application that you need to automate, and we will be teaching you how to use both in succession. In this lesson, we will walk through the creation of a single VM blueprint to help you familiarize yourself with blueprints themselves, the components of a blueprint, and the steps involved in creating and publishing one.

Then, with this foundation well-established, in the next lesson we’ll focus on multi-VM blueprints.

So, before we move on, let’s summarize what you will learn in this lesson. We will discuss how you can create, manage, and publish your own application blueprints. We will start with a single-VM blueprint and discuss the various concepts you need to be familiar with.

We will walk through:

The different elements of a Calm blueprint
Single-VM and multi-VM blueprints
The various tasks involved in managing blueprints such as uploading, downloading, editing, and deleting
How to use the Marketplace Manager to publish, unpublish, and delete blueprints.
Let’s begin.

## The Importance of Calm Blueprints and Marketplace Publishing

While we have very briefly discussed both blueprints and the Marketplace in the previous lesson, we will now explore both subjects in more detail.

Nutanix Calm, as we learned previously, is a multi-cloud application management framework. And, as we will see in this lesson, it transforms the way that enterprises work with applications.

In Calm, applications are defined via simple blueprints that can be easily created using industry standard skills and control all aspects of the application’s lifecycle, such as provisioning, scaling, and cleanup. These blueprints can be created through the UI, or via code with a Python-based DSL, including seamless conversion.

Once created, a blueprint can be easily published to end users through the Nutanix Marketplace, instantly transforming a complex provisioning ticket into a simple one-click request.

The ability to turn applications into automated blueprints brings a number of benefits to any enterprise that uses Nutanix Calm.

![](https://video.udacity-data.com/topher/2020/September/5f5288dd_blueprint-benefits-all/blueprint-benefits-all.png)

### Better Agility, Fewer Errors
A blueprint incorporates relevant VMs, configurations, related binaries, and other elements of each app into a single unit that can be managed by the infrastructure team. This makes application lifecycle management and deployment both automated and repeatable, freeing up the time that infrastructure teams are presently devoting to managing their applications.

### Self-service, Central Control
As we’ve seen in the previous lessons, self-service and RBAC allow IT teams to empower different groups to provision and manage their own applications. Activities and changes are logged with end-to-end traceability, helping security teams with compliance initiatives.

### Modernized App Development
When paired with a certified Kubernetes solution, Calm allows you to modernize app development without losing policy control. In addition, Calm natively integrates with Jenkins to empower Continuous Integration and Continuous Delivery (CI/CD) pipelines with automatic infrastructure provisioning or upgrades for all applications.

### Unified Multi-Cloud Orchestration
Calm unifies the management of all your clouds into a single pane of glass, removing the need to move back and forth between multiple management interfaces. Calm automates the provisioning of multi-cloud architectures, scaling both multi-tiered and distributed applications across different cloud environments.

## Quiz: Importance of Blueprints and Marketplace

### QUIZ QUESTION
How does Calm turn apps into simple units that can be managed by infrastructure teams?

* By incorporating relevant VMs, configurations, binaries, and other application components into a single blueprint

## Understanding the Full Potential of Blueprints

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/380.jpg)

The reason it’s so important to understand blueprints - so important that we’re spending two lessons in this course on the subject - is because of how Calm contributes to fully realising the potential of a hybrid cloud IT environment.

The Nutanix Enterprise Cloud OS provides a single operating system across multiple cloud environments, while Nutanix Calm delivers application automation and lifecycle management with self-service capabilities.

So, an IT organization can quickly embrace the various clouds that the business wants to consume and satisfy a broader range of needs, while providing the same end-user and administrative experience across clouds. Since Nutanix Prism and Calm provide native capabilities for application automation, application lifecycle management, and self-service, your IT consumers can leverage the Nutanix marketplace to deploy infrastructure services or applications.

When deploying applications from the Marketplace, your customers not only get a simple, one-click experience, but you also get to ensure governance requirements are followed.

You can work with teams in your organization to define specific application policies that must be enforced. Nutanix Calm enables you to optimize the application lifecycle by tailoring application blueprints for each of your end-user groups and making them accessible in a customised service catalog. Nutanix Calm acts as a front-end portal to deploy services.

In addition to Calm, you can also leverage the IaaS self-service capabilities built into the Nutanix Prism management interface. You can work with each customer to define the necessary projects, quotas, and role assignments. For example, DB administrators might be allowed to deploy and manage DB instances but restricted from accessing other application services.

Ultimately, Calm stands to vastly expand on the service and self-service capabilities that IT can deliver to their end users, but as you may have noticed everything begins with blueprints. So, now, let’s talk about them.

![](https://video.udacity-data.com/topher/2020/September/5f52898e_operational-flexibility-calm/operational-flexibility-calm.png)

## Publishing Your Own Application Blueprints

Blueprints are essentially recipes for applications. These recipes encompass application architecture and Infrastructure choices, provisioning and deployment steps, application binaries, command steps, monitoring endpoints, remediation steps, licensing and monetization, and policies. Every time a Blueprint is executed it results in an application.

Calm uses Services, Packages, Substrates, Deployments, and Application Profiles as building blocks for a blueprint. Together they fully define applications. By encoding these into a blueprint, Calm can understand the application as a whole and properly automate its lifecycle.

And as we discussed in the previous topic, being able to turn application deployment into an automated, repeatable activity can have a significant impact on an IT team’s productivity and efficiency.

This is why this lesson and the one after it are focused entirely on the centerpiece of Calm – application blueprints. In this lesson, we will lay the foundation for everything you need to know about blueprints: key concepts, process overviews, different elements of the Calm interface, and so on. At the end of this lesson, we will bring those concepts together into an exercise to create a single-VM blueprint.

Then, in the next lesson, we will recap some old concepts, introduce some advanced concepts, and tie them all together with a more complex blueprint – a multi-VM blueprint for a web server using a Linux VM.

So, since everything ties together to form the complete picture of application automation, before we move on, let’s quickly recap the Marketplace.

## Quiz: Publishing Your Own Application Blueprints

### QUIZ QUESTION
Which of these statements is an accurate description of a blueprint?

* Blueprints are recipes for applications

## Recap: The Nutanix Marketplace

As we discussed in the previous lesson, the Marketplace allows you to:

* View details of an application
* Publish applications for use by specific users and/or groups
* Control application state e.g. “Approved” or “Pending Approval”
* Carry out test deployments that ensure an applications functions as expected before publication

### View Details of an Application

![](https://video.udacity-data.com/topher/2020/September/5f5285d7_marketplace-app-details/marketplace-app-details.png)

### Search For and Filter Applications

![](https://video.udacity-data.com/topher/2020/September/5f528611_marketplace-filter/marketplace-filter.png)

### Clone an Application Blueprint

![](https://video.udacity-data.com/topher/2020/September/5f528655_marketplace-clone/marketplace-clone.png)

### Launch a Marketplace Item

![](https://video.udacity-data.com/topher/2020/September/5f52866e_marketplace-launch/marketplace-launch.png)

Take a moment to ensure that you remember these tasks and are familiar with the various capabilities of the Marketplace, as shown in the preceding images.

### Enabling Nutanix Marketplace Applications
To help you get started with one-click app deployment, Calm offers a collection of pre-seeded blueprints – these are essentially ready-to-use applications that address a number of common use cases.

However, by default, you will not see these applications in the Marketplace. To enable them, navigate to the Settings page in Calm, and click the Nutanix Marketplace Apps toggle.

![](https://video.udacity-data.com/topher/2020/September/5f528a53_enable-nutanix-marketplace-apps/enable-nutanix-marketplace-apps.png)

## Quiz: Marketplace Recap

### QUIZ QUESTION
What are Nutanix Marketplace applications?

* Ready to use applications that are available in Calm out-of-the-box

## Calm Blueprints: Overview

As we briefly discussed earlier, Blueprints are recipes for applications. Now let’s take a little time to explore what those recipes typically contain.

The eleven main components of a Calm Blueprint are:

* Application Profiles
* Services
* Substrates
* Application Profile Actions
* System Defined Profile Actions
* Custom Profile Actions
* Service Actions
* System Defined Service Actions
* Custom Service Actions
* Package Install/Uninstall
* VM Pre-create/Post-create

Let’s go over each of these in a little more detail.

Calm Blueprint Canvas

![](https://video.udacity-data.com/topher/2020/September/5f528a8e_calm-blueprint-canvas/calm-blueprint-canvas.png)

### Application Profiles 
(number 1 in the image above) expose simple choices to your end users. These choices are often about where an application should run (AHV or AWS), but they can also be used for ‘t-shirt’ sizing (small or large), or a combination of the two (small AHV or large AHV or small AWS). You, as an IT operator or developer, should have a good grasp of the underlying differences of these choices, while abstracting that complexity from your end users.

### Services 
(number 2 in the image) are logical entities exposed by an IP, which span all application profiles, and are managed by Calm. End users and services communicate amongst each other over a network via their exposed IPs and ports. Services are typically deployed based on a disk image that is managed by Prism Central. Take a moment to think back to previous lessons, and to the Image Management topic that we discussed. Services in Calm are one reason why it’s important to understand how to work with images in Prism Central.

### Substrates 
(number 3 in the image) are a combination of the underlying cloud and the virtual machine instance. When the desired cloud is selected in the Calm UI, all of the fields required for creating a virtual machine instance on that particular cloud are displayed — the combination of all these fields make up a substrate. Substrates do not span application profiles, so it’s considered a best practice to name substrates as a combination of the service name and app profile name (DB_AHV or DB_AWS or DB_Small or DB_Large).

### Calm Application Profiles and Actions

![](https://video.udacity-data.com/topher/2020/September/5f528ab7_calm-application-profiles-and-actions/calm-application-profiles-and-actions.png)

### Application Profile Actions
(or Profile Actions for short, number 4 in the image above) are a set of operations that you can run on your application. For example, when launching a blueprint, the ‘Create’ action is run. If your application is not needed for a period of time, you could then run the ‘Stop’ action to gracefully stop your application. When you’re ready to resume work, running the ‘Start’ action will bring the app back up. There are two different types of profile actions, system defined profile actions and custom profile actions.

### System Defined Profile Actions
(5 in the image) are automatically created by Calm in every blueprint and underlying application. Since these are created for you, you cannot directly edit the tasks or the order of tasks within the canvas. However there are ways to control the order of operations, called Dependencies.

### Custom Profile Actions 
(6 in the image) are created by the blueprint developer, and should be added whenever you need to expose a set of operations to the end user. Common custom profile actions are ‘Upgrade’, ‘Scale In’, and ‘Scale Out’. Since the actions are custom, individual tasks can be manually added in any order desired by the developer.

### Calm Service Actions

![](https://video.udacity-data.com/topher/2020/September/5f528ad3_calm-service-actions/calm-service-actions.png)

### Service Actions
(7 in the image above) are a set of operations to be run on an individual service. As we discussed earlier, services span application profiles, so their actions (and the operations underlying those actions) do as well. If you create a service action in the ‘AHV’ profile, the same service action will be available in the ‘AWS’ profile. As with profile actions, there are also two different types of service actions: system-defined service actions and custom service actions.

### System Defined Service Actions 
(8 in the image) are automatically created by Calm in every blueprint and underlying application. While these actions cannot be individually invoked, they are called when the corresponding profile action is run. For instance, any operations placed under the ‘Stop’ service action will be run when an end user invokes the ‘Stop’ profile action.

### Custom Service Actions 
(9 in the image) are created by the blueprint developer, and should be added for any repeatable operations within the blueprint, like a function definition in a programming language. For instance, during both the ‘Create’ and ‘Upgrade’ profile actions, the ‘App’ service should pull new code from a source code control repository. Rather than maintaining two separate tasks that perform the same set of operations, you could create a single custom service action which is then referenced in both the ‘Create’ and ‘Upgrade’ actions.

### Package Install/Uninstall
(10 in the image) are operations which are run during the ‘Create’ or ‘Delete’ profile actions. In other words, they are operations that run when a user first launches a blueprint, or finally deletes the entire application. Package Install and Uninstall are unique to each application profile, which means your tasks or the task contents can vary depending upon the underlying cloud or the app’s ‘t-shirt’ size.

### VM Pre-create/Post-delete
(11 in the image) are operations which are run before the substrate is created, or after it is deleted. A common use case for this is to make an API call into an IP Address Management (IPAM) system to get an IP for a to-be-created VM. Since other operations described so far are run after the substrate has already been created, VM pre-create is necessary if a property of your substrate relies on a 3rd party system.

## Quiz: Blueprints Overview

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/381.jpg)

## Working with Blueprints

Watch the video to follow the tutorial:

[![IMAGE ALT TEXT](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/382.jpg)](https://www.youtube.com/watch?time_continue=3&v=JkJebVRaPEY&feature=emb_logo)

Now we’re going to focus on creating blueprints themselves. Whenever you need to work with Blueprints, you’ll need to navigate to the Blueprints page of Calm, pictured below.

![](https://video.udacity-data.com/topher/2020/September/5f528b72_blueprints-page-main/blueprints-page-main.png)

As you can see, the options available to you are very similar to those that you’ll see on other pages in Calm. You can create, upload, filter, launch, download, delete, and clone blueprints from this page.

You’ll also see a table in the middle of the page that lists every available blueprint, as well as some basic information: the type, a description, the project it’s associated with, and so on. You can click the name of a blueprint to open the Blueprint Canvas screen, pictured below.

![](https://video.udacity-data.com/topher/2020/September/5f528bc5_calm-blueprint-canvas-no-labels/calm-blueprint-canvas-no-labels.png)

The Blueprint Canvas screen is a complete view of your blueprint, consisting of all of the elements that we talked about earlier. Here, you can modify the configuration of a blueprint, publish, download, or launch it.

## Creating a Blueprint
Based on the type of application you intend to deploy, you will find yourself creating one of two different types of blueprints: single VM or multi-VM. And to create a blueprint, you simply need to click + Create Blueprint on the Blueprints page. There, you will see two options:

* Single VM Blueprint
* ulti-VM/Pod Blueprint

![](https://video.udacity-data.com/topher/2020/September/5f528bf6_create-blueprint-options/create-blueprint-options.png)

In this lesson, we will spend some time on single VM blueprints and follow up with an exercise that will allow you to create one. In the next lesson, we will look at multi-VM blueprints in detail.

## Quiz: Working with Blueprints

### QUIZ QUESTION
How many types of blueprints can you create?
* Two: single-VM, and multi-VM

Like the name suggests, a single VM blueprint is a framework that you can use to create an instance, provision, and launch applications that require only a single VM. You can define the underlying infrastructure of the VM, application details, and actions that are carried out on a blueprint until the termination of the application.

### Types of Single VM Blueprints
The choices that you have when setting up your Providers extend to creating blueprints as well. You can create a single VM blueprint for Nutanix, VMware, AWS, Azure, and GCP.

### Demo: UI for Single VM Blueprints
Let’s walk you through the user interface for some of the creation steps below.

Watch the video to follow the tutorial:

[![IMAGE ALT TEXT](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/383.jpg)](https://www.youtube.com/watch?time_continue=3&v=gcToVM6H9ms&feature=emb_logo)

In general, the process of setting up a single VM blueprint is similar irrespective of the infrastructure you choose to use. While details may vary, as we saw when creating Providers, there are four broad tasks involved in creating a single VM blueprint:

* Updating blueprint settings
* Providing VM details
* Specifying VM configuration
* (Optional) Configuring advanced options

### Blueprint Settings
Here, you’ll provide a name and a description for the project, and specify the project that it needs to be associated with.

![](https://video.udacity-data.com/topher/2020/September/5f528c34_create-blueprint-1-blueprint-settings/create-blueprint-1-blueprint-settings.png)

### VM Details
On the VM Details page, you need to provide a name for the VM, choose the infrastructure it will run on, and specify an operating system. If you have already configured an environment as described in the previous lesson, you can simply click the Clone from environment link to duplicate your settings. That allows you to skip this step entirely, and proceed directly to the VM configuration page.

![](https://video.udacity-data.com/topher/2020/September/5f528c4c_create-blueprint-2-vm-details/create-blueprint-2-vm-details.png)

### VM Configuration
On the VM Configuration page, you will need to provide details about the VM itself, such as the number of vCPUs, cores per vCPU, memory, disks, network details, vGPUs, and so on. As you can see on the right of the screen, you will need to provide information in 7 different categories:

* General configuration
* Guest configuration
* Disks
* vGPUs
* Categories
* NICs
* Serial ports

Take note of the Categories step in this process and think back to earlier lessons where we discussed Categories in Prism Central — this is one example where you would apply any categories you may have set up at that time.

![](https://video.udacity-data.com/topher/2020/September/5f528c6b_create-blueprint-3-vm-configuration/create-blueprint-3-vm-configuration.png)

### (Optional) Configure Advanced Options
Finally, the last major task is to configure advanced options. This page allows you specify four additional areas for M provisioning:

* Provide credentials: SSH keys and Passwords
* Check the log on status of the VM after provisioning the blueprint
* Add pre-create and post-delete tasks in the blueprint
* Add packages and actions in the blueprint

This is entirely optional and can be skipped if you do not have a need to update any of these settings.

![](https://video.udacity-data.com/topher/2020/September/5f528c84_create-blueprint-4-advanced-settings/create-blueprint-4-advanced-settings.png)

Once you have provided all of the necessary information, review your settings and click Save. You will see your blueprint listed on the Blueprints page, and can then use it to model your application.

## Quiz: Single VM Blueprints

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/384.jpg)

## Exercise: Create a Single VM Blueprint

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/385.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/386.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/387.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/388.jpg)

## Exercise Solution: Create Single VM Blueprint

### Exercise Solution
### Creating a Single VM Blueprint
Let’s walk you through in this video the steps we discussed above for creating a single VM blueprint. We will create a CentOS VM that is configured by Calm settings and cloud-init that uses your SSH key and creates a login user account named “centos.”

In this solution video, you will see us upload a cloud-init configuration file that refers to your SSH key with Calm macros. The two Calm macros are:

* @@{superuser.username}@@
* @@{superuser.public_key}@@

Watch the video to follow the tutorial:


[![IMAGE ALT TEXT](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/389.jpg)](https://www.youtube.com/watch?v=qrOpxr4MgV4&feature=emb_logo)

### Downloading and Launching the Blueprint

Watch the video to folow the tutorial:

[![IMAGE ALT TEXT](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/390.jpg)](https://www.youtube.com/watch?v=fu10nUn0yzI&feature=emb_logo)

## Multi-VM Blueprints

A multi-VM blueprint is a framework that you can use to create an instance, provision, and launch applications that require multiple VMs. Just like single VM blueprints, you can define the underlying infrastructure of the VMs, application details, and actions that are carried out on a blueprint until the termination of the application.

And, once again, you can choose which infrastructure to leverage when creating a multi-VM blueprint, with Nutanix, VMware, AWS, Azure, and GCP available as options.

### Creating a Multi-VM Blueprint
Creating a multi-VM blueprint is a little more involved than a single VM blueprint. The process involves 6 major tasks, which are:

* Adding a service
* Configuring the VM, package, and service for your provider
* Setting up service dependencies
* Adding and configuring an application profile
* (Optional) Adding and configuring scale out and scale in
* Creating an action

Multi-VM blueprints are discussed in much more detail in the next lesson, but it’s helpful for you to have an overview of them now.

## Managing Blueprints: Overview

Watch the video to follow the tutorial 

[![IMAGE ALT TEXT](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/391.jpg)](https://www.youtube.com/watch?v=I2WrDc4mVRE&feature=emb_logo)

There are a number of tasks that you can perform after you have a blueprint set up and saved. In no particular order, there are 10 tasks that you should be aware of in the context of managing blueprints:

* Publishing blueprints
* Launching blueprints
* Uploading blueprints
* Downloading blueprints
* Configuring blueprints
* Viewing blueprints
* Editing blueprints
* Deleting blueprints
* Viewing blueprint errors
* Recovering deleted blueprints

While most of these are self-explanatory, there are a few details worth noting here. Configuring a blueprint, like most things in Calm, involves filling out a form that requires a name, a description, downloadable image configuration, and so on, as shown in the following figure.

![](https://video.udacity-data.com/topher/2020/September/5f528cc2_blueprint-configuration/blueprint-configuration.png)

Viewing blueprint errors is relevant only if a blueprint has been configured incorrectly, or if an unforeseen issue occurred during development. If you receive an error when saving or publishing a blueprint, look for an exclamation mark icon in the UI, beside the undo and redo buttons. You can click the icon to view details of each error and take corrective action as needed.

![](https://video.udacity-data.com/topher/2020/September/5f528cd8_blueprint-error/blueprint-error.png)

After you configure a blueprint, you can publish, unpublish, launch, or delete it.

Publishing a blueprint allows you to make the blueprint available in the Marketplace, so that other users can use it. This requires administrator approval. Unpublishing a blueprint allows you to remove the blueprint from the Marketplace.

And finally, launching a blueprint allows you to deploy the application associated with the blueprint and start using it

## QUIZ QUESTION

### QUIZ QUESTION
Which of the following tasks are involved in managing blueprints? (may be more than one answer)

* Uploading

* Downloading

* Publishing

* Unpublishing

* Launching

* Deleting

## Working with the Marketplace Manager

Watch the video to follow the tutorial


[![IMAGE ALT TEXT](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/392.jpg)](https://www.youtube.com/watch?v=YQ-1RjGyBvE&feature=emb_logo)

The last major topic that we’re going to discuss in this lesson is working with the Marketplace Manager. Like the Marketplace itself, the Marketplace Manager has its own page in Calm.

It allows you to manage the list of custom blueprints and the marketplace application blueprints. You can view the list of published blueprints under the Marketplace Blueprints tab and the list of blueprints that are pending for approval under the Approval Pending tab. The Marketplace Manager page provides the following details about a blueprint:

* Name of the blueprint
* Name of the entity who created the blueprint
* The number of projects for which the blueprint is available
* The category of the blueprint
* Status of the blueprint

![](https://video.udacity-data.com/topher/2020/September/5f528cfd_marketplace-manager-page/marketplace-manager-page.png)

After you select a blueprint, the inspector panel displays the operations you can perform on the selected blueprint. The inspector panel also displays a brief overview of the blueprint and allows you to select the category and projects for the available blueprint.

Broadly, there are three operations that you are likely to perform on the Marketplace Manager page: publishing a blueprint, unpublishing a blueprint, and deleting an unpublished blueprint.

### Publishing a Blueprint
It’s worth noting that, if your blueprint is properly set up, publishing, unpublishing and deleting don’t involve more than one or two clicks. To publish a blueprint, for example, you simply need to:

* Navigate to the Approval Pending tab
* Select an unpublished blueprint from the list
* Click Approve
* Assign the blueprint to a Category
* Click Publish

### Unpublishing a Blueprint
Unpublishing a blueprint removes it from the Marketplace, but does not delete the blueprint itself. It can also be republished if there is a need.

To unpublish a blueprint:

* On the Marketplace Blueprints tab, select a blueprint from the list
* Click Unpublish

![](https://video.udacity-data.com/topher/2020/September/5f528d1a_unpublish-a-blueprint/unpublish-a-blueprint.png)

## Deleting a Blueprint
Deleting a blueprint removes the blueprint itself, and the operation can only be performed on an unpublished blueprint. As you can see in the previous figure, you can only unpublish or launch a published blueprint.

However, with an unpublished blueprint, as shown in the figure below, you will see options to either publish the blueprint or delete it. Simply click the Delete button to remove the blueprint.

![](https://video.udacity-data.com/topher/2020/September/5f528d31_publish-or-delete-a-blueprint/publish-or-delete-a-blueprint.png)

## Quiz: Working with Marketplace Manager

### QUESTION 1 OF 2
True or false: Any blueprint created in Calm can be deleted later.

*True, any blueprint created in Calm can be deleted. However, it must be unpublished before it can be deleted.

You have just finished taking inventory of all the applications that your company has created blueprints for in Calm. Of the lot, you have found two applications that may no longer need to be in the Marketplace. Application A was a popular image editing application that was being used company wide, until it was replaced by a suite of cloud-based tools from another vendor entirely. Metrics for the blueprint indicate that it has not been used even once in several quarters, so it’s just taking up an unnecessary spot on the Marketplace.

Application B is a web application that it seems only a small number of people have used in the past. Unlike App A, you’re not entirely certain what this one is for. The Marketplace entry isn’t very detailed and there isn’t a lot of information about the application itself. You only know that it’s a web app that was last deployed six months ago and never since. The blueprint hasn’t been updated either, and the person who created it left the company some time ago.

What should you do with these two application blueprints?

### QUESTION 2 OF 2
Read the scenario above and decide what you should do with the two application blueprints. Remember that App A is the image editing software, and App B is the web application.

* Delete the blueprint for App A and unpublish the blueprint for App B.

## Exercise: Publish Blueprint to Marketplace

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/393.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/394.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/395.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/396.jpg)

## Exercise Solution

### Publishing a Single VM Blueprint to the Marketplace

Watch the video to follow the tutorial:

[![IMAGE ALT TEXT](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/392.jpg)](https://www.youtube.com/watch?v=_7rl8c0Us4A&feature=emb_logo)

### Launching a Blueprint from the Marketplace

Watch the video to follow the tutorial:

[![IMAGE ALT TEXT](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/392.jpg)](https://www.youtube.com/watch?v=Vz4PzWdZQ_A&feature=emb_logo)

### Unpublishing and Deleting a Blueprint

[![IMAGE ALT TEXT](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/392.jpg)](https://www.youtube.com/watch?v=PjIUOcXHwfI&feature=emb_logo)

## Glossary

### Application Profile Actions -
Application Profile Actions (or Profile Actions for short) are a set of operations that you can run on your application. For example, when launching a blueprint, the ‘Create’ action is run.

### Application Profiles - 
Application Profiles expose simple choices to your end users. These choices are often about where an application should run (AHV or AWS), but they can also be used for ‘t-shirt’ sizing (small or large), or a combination of the two (small AHV or large AHV or small AWS).

### Blueprint -
Blueprints are essentially recipes for applications. These recipes encompass application architecture and Infrastructure choices, provisioning and deployment steps, application binaries, command steps, monitoring endpoints, remediation steps, licensing and monetization, and policies. Every time a Blueprint is executed it results in an application.

### CI/CD - 
CI/CD stands for Continuous Integration/Continuous Delivery or Continuous Integration/Continuous Deployment. It is a term that is commonly used when discussing modern software development and is the solution to the problems that integrating new code can cause for development and operations teams. CI/CD solves those problems by requiring ongoing automation and continuous monitoring through the lifecycle of an application, from integration and testing to delivery and deployment.

### Custom Profile Actions -
Custom Profile Actions are created by the blueprint developer, and should be added whenever you need to expose a set of operations to the end user.

### Custom Service Actions
- Custom Service Actions are created by the blueprint developer, and should be added for any repeatable operations within the blueprint, like a function definition in a programming language.

### Marketplace Manager - 
The Marketplace Manager is a section of the Calm UI that allows you to manage both custom blueprints and marketplace application blueprints. From the Marketplace Manager, you can publish, unpublish, and delete blueprints.

### Multi-VM Blueprints
A multi-VM blueprint is a framework that you can use to create an instance, provision, and launch applications that require multiple VMs.

### Package Install/Uninstall -
Package Install/Uninstall are operations which are run during the ‘Create’ or ‘Delete’ profile actions. In other words, they are operations that run when a user first launches a blueprint, or finally deletes the entire application.

### Profile Actions - 
See: Application Profile Actions, above.

### Service Actions - 
Service Actions are a set of operations to be run on an individual service. Services span application profiles, so their actions (and the operations underlying those actions) do as well.

### Services - 
Services are logical entities exposed by an IP, which span all application profiles, and are managed by Calm.

### Single VM Blueprint -
A single VM blueprint is a framework that you can use to create an instance, provision, and launch applications requiring only a single VM.

### Substrates -
Substrates are a combination of the underlying cloud and the virtual machine instance. When the desired cloud is selected in the Calm UI, all of the fields required for creating a virtual machine instance on that particular cloud are displayed — the combination of all these fields make up a substrate.

### System Defined Profile Actions - 
System Defined Profile Actions are automatically created by Calm in every blueprint and underlying application.

### System Defined Service Actions - 
System Defined Service Actions are automatically created by Calm in every blueprint and underlying application. While these actions cannot be individually invoked, they are called when the corresponding profile action is run.

### VM Pre-create/Post-delete - 
VM Pre-create/Post-delete are operations which are run before the substrate is created, or after it is deleted.

## Lesson Conclusion

Now we come to the end of this lesson. Before we move on, let’s quickly recap some of the highlights of this lesson.

Blueprints are essentially recipes for applications. These recipes encompass application architecture and Infrastructure choices, provisioning and deployment steps, application binaries, command steps, monitoring endpoints, remediation steps, licensing and monetization, and policies. Every time a Blueprint is executed it results in an application.

Calm uses Services, Packages, Substrates, Deployments, and Application Profiles as building blocks for a blueprint. Together they fully define applications. By encoding these into a blueprint, Calm can understand the application as a whole and properly automate its lifecycle.

Blueprints are also incredibly important. The ability to turn an application into a repeatable, automated blueprint offer enterprises a number of benefits: greater agility while minimizing human error; broader self-service capabilities while allowing IT to retain centralized control; the ability to modernize app development by pairing Calm with a certified Kubernetes solution; and the ability to automate provisioning across multi-cloud architectures from a single management interface.

You can create two types of blueprints: single-VM and multi-VM. A single-VM blueprint is a framework that you can use to create an instance, provision, and launch applications that require a single VM. A multi-VM blueprint is a framework for applications that require multiple VMs.

Blueprints can be downloaded, uploaded, viewed, configured, edited, deleted, published, unpublished, and launched. Publishing, unpublishing, and deleting blueprints involves using the Marketplace Manager, which is what determines whether or not your blueprints are available to users of the Nutanix Marketplace.

If you’re comfortable with these concepts, you’ll find yourself in a good position to delve deeper into Calm. So, in the next lesson, we’ll explore blueprints even further, by discussing multi-VM blueprints and how you can use them for more complex, sophisticated automation tasks.



________________________________________________________________________________________________________________________________________________________________________________



# LESSON 4 CREATING AND PUBLISHING A MULTI-VM BLUEPRINT

## Lesson Overview

As mentioned in earlier lessons, you can create two different types of blueprints based on the complexity of the application that you need to automate. In the previous lesson, we walked you through the creation of a single VM blueprint to help you familiarize yourself with blueprints.

Now that you know how to create a single VM blueprint, in this lesson, we’ll focus on multi-VM blueprints.

We will start the lesson by covering some of the common blueprint lifecycle management tasks such as cloning, downloading, and uploading a blueprint.

To create a blueprint, you must first create a project and configure the environment. Therefore, we will briefly cover Calm services and substrates and walk you through the process of configuring a Nutanix environment as an example.

We will introduce you to various advanced Calm constructs such as macros, variables, dependencies, library, etc. These concepts will serve as a foundation to understand the process of creating a multi-VM Calm blueprint. Finally, we will wrap-up the lesson by covering each task involved in creating a multi-VM Calm blueprint.

By the end of this lesson, you will be able to perform blueprint lifecycle management tasks, configure a Nutanix environment and create a multi-VM Calm blueprint.

In addition, we will give you an overview of the LAMP stack, the foundation on which we will build our web application. We’ll cover load balancer design with a scaling web service tier to address our “two tier” web application’s high availability and performance.

Let’s get started!

## Cloning a Blueprint

### Calm Blueprint Lifecycle: Cloning a Blueprint

Watch the video to follow the tutorial:

[![IMAGE ALT TEXT](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/397.jpg)](https://www.youtube.com/watch?v=xHm4v2NH-vk&feature=emb_logo)

This is a topic we’ve discussed earlier in the context of the Calm Marketplace. As you may remember, it’s a very straightforward process which you can complete with a couple of clicks.

You can clone an application blueprint from a pre-seeded application blueprint. Cloning a blueprint is a simple process.

* 1. From the Marketplace, click the application blueprint you want to clone.
* 2. Click Clone.
* 3. Enter a name and select the project that you want to assign it to.
* 4. Click Clone again.

![](https://video.udacity-data.com/topher/2020/September/5f528655_marketplace-clone/marketplace-clone.png)

## Quiz: Cloning a Blueprint

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/398.jpg?token=ADDIJ7MUYM4PPUG5NTDA5LDACKQPS)

## Downloading a Blueprint

### Calm Blueprint Lifecycle: Downloading a Blueprint

Watch the video to follow the tutorial:

[![IMAGE ALT TEXT](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/399.jpg)](https://www.youtube.com/watch?v=85r6DHQGrUI&feature=emb_logo)

The ability to download a blueprint is one of the many blueprint management tasks that we talked about in the previous lesson. And while we went over them at a very high level, it’s worth taking a few moments to go into a little more detail on some of those tasks here.

You can download a configured blueprint to your local machine for later use. You also have the option to download the blueprint with the credentials and secrets used in the blueprint.

To download a blueprint:

* 1. Click the blueprint icon.
* 2. Click the blueprint that you want to download.
* 3. Click Download.
* 4. Select the check box, if you want to include credentials and secrets and type a password.
* 5. Click Continue.

You can also perform the same operation by selecting the blueprint and clicking the Download option under the Actions dropdown.

![](https://video.udacity-data.com/topher/2020/September/5f52ac7b_downloading-a-blueprint-image1/downloading-a-blueprint-image1.png)

## Quiz: Downloading a Blueprint

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/400.jpg)

## Uploading a Blueprint

### Calm Blueprint Lifecycle: Uploading a Blueprint

Watch the video to follow the tutorial:

[![IMAGE ALT TEXT](https://github.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/blob/main/images/401.jpg)](https://www.youtube.com/watch?v=-Ed3mod0W0g&feature=emb_logo)

Much like the ability to download a blueprint, the ability to upload one is also one of the eleven blueprint management tasks that we briefly discussed in Lesson 3.

You can also upload configured blueprints to the Blueprints tab. To do that:

* 1. Click the Blueprint icon.
* 2. Click Upload Blueprint.
* 3. Browse and select the saved blueprint.
* 4. Give the blueprint a name and select the project you want to assign it to.
* 5. Click Upload.

If you have previously downloaded the blueprint with credentials and secrets, then during upload you must provide the same password as previously specified.

![](https://video.udacity-data.com/topher/2020/September/5f52ac96_uploading-a-blueprint-image1/uploading-a-blueprint-image1.png)

## Quiz: Uploading a Blueprint

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/402.jpg)

## Calm Services and Substrates

We’ve covered some of the tasks involved in managing the blueprint lifecycle. We will next discuss all of the necessary topics to understand the creation of a multi-VM blueprint. Services, substrates, application profile, and actions are primary elements required to create a multi-VM blueprint.

In this section, we will dive into the process of configuring the substrates, and also discuss its importance. Before that, let’s do a quick recap of services and substrates.

### Services Overview
Services are logical entities exposed by an IP that span all application profiles and are managed by Calm. End users and services communicate with each other over a network using their exposed IPs and ports.

### Configuring Substrates
Substrates are combinations of the underlying cloud and the VM instance. When you select the desired cloud in the Calm UI, all the fields required to create a VM instance on that particular cloud are displayed. The combination of these fields is a substrate.

The substrate or VM details are configured in the environment.

The environment depends on the cloud provider selected during the project creation process. The environment consists of the cloud provider and the operating system details. For example, if you choose Nutanix as the provider. You have two options, Nutanix+Linux and Nutanix+Windows.

![](https://video.udacity-data.com/topher/2020/September/5f52acb3_creating-an-environment-image1/creating-an-environment-image1.png)

Calm supports Nutanix AHV, Nutanix Xi Cloud, AWS, VMware, GCP, and Azure as providers for your project. For simplicity, we will be covering the process to configure a Nutanix AHV environment.

### Configuring a Nutanix Environment
The Environment allows you to add multiple credentials and configure VM details for the selected provider. You can configure an environment when creating a project.

If you have configured the environment when creating a project, you can use the configured details while creating a blueprint or launching an application from the marketplace.

Environment is mandatory to publish the applications into the marketplace. If you do not define VM configuration while creating a blueprint, you must define the configuration as part of the environment. Also, during the application blueprint launch from the marketplace, the values are picked from the environment.

Before configuring a Nutanix environment, ensure that you have configured a project with Nutanix as a provider.

To configure the environment for Nutanix:

In the Create Project page, Under the environments tab, select Nutanix.

Under the Nutanix tab:

* 1. Enter credential details. Nutanix supports both password based and SSH private key based secret type.
* 2. Select the operating system type.
* 3. Provide VM configuration details such as name, image, firmware, vCPU, device bus, memory, etc.
* 4. Confirm whether or not to check log on status after the VM is created.
* 5. Specify the connection type and port.

## Quiz: Calm Services and Substrates

### QUIZ QUESTION
Environment is mandatory to ___.

* Publish the applications into the marketplace.

## Calm Macros

efore we talk about macros, it is important to understand variables.

The properties such as IP addresses, DNS names, and instance IDs that are associated with the services provisioned in blueprints are called variables. They can be static, provided at run time, or generated during blueprint or action runs. Variables can have various data types (strings, integers, dates, or times) and various inputs (generated using single value, single input arrays, multiple input arrays, or an API call), and can be validated through regular expressions (regex).

### Macros Overview
Macros enable you to access the value of variables and properties set on entities, and help you make generic scripts and create reusable workflows.

For instance, a web server install script could use a macro to reference the IP address of a database. At deployment, the system replaces the macro with the actual IP address. Macros begin with “@@{“ and end with “}@@”.

The syntax of a macro is "@@{variable_name}@@", where "variable_name" is the name of the variable.

The syntax to access the value of variables or properties of other entities or dependencies is "@@{.<variable/attribute name>}@@".

* "entity name" is the name of the other entity or dependency
* "variable/attribute" name is the name of the variable or attribute.

For example, if a blueprint contains a service by the name of app_container, you can access the IP address of the app_container service in any other service using "@@{app_container.address}@@" syntax.

Calm macros are part of a templating language for Calm scripts. These are evaluated by Calm's execution engine before the script is run.

Let’s further explore the supported entities, types of variables, access credentials as macros, access macros of an array service, and a lot more.

### Supported Entities
Entities supported by macros include:

* Application
* Service
* Package
* Virtual machine

### Types of Variables
There are two types of variables:

* User-defined
* Built-in.

There are various built-in macros available for use based on different providers. Refer to the links below to view a list of built-in variables for the following providers.

* [Nutanix Variables](https://portal.nutanix.com/page/documents/details?targetId=Nutanix-Calm-Admin-Operations-Guide-v2_9_8:nuc-macros-ahv-c.html)
* [AWS Variables](https://portal.nutanix.com/page/documents/details?targetId=Nutanix-Calm-Admin-Operations-Guide-v2_9_8:nuc-nucalm-aws-variables-c.html)
* [GCP Variables](https://portal.nutanix.com/page/documents/details?targetId=Nutanix-Calm-Admin-Operations-Guide-v2_9_8:nuc-macros-gcp-variables-c.html)
* [Azure Variables](https://portal.nutanix.com/page/documents/details?targetId=Nutanix-Calm-Admin-Operations-Guide-v2_9_8:nuc-macros-azure-variables-c.html)
* [Kuberenetes Variables](https://portal.nutanix.com/page/documents/details?targetId=Nutanix-Calm-Admin-Operations-Guide-v2_9_8:nuc-macros-kubernetes-c.html)
* [VMware Variables](https://portal.nutanix.com/page/documents/details?targetId=Nutanix-Calm-Admin-Operations-Guide-v2_9_8:nuc-macros-vmware-variables-c.html)

### Credentials as Macros
You can also access credentials as macros. The format to access credential is:

"@@{cred_name.username}@@" and "@@{cred_name.secret}@@" "cred_name": Name of the credential with which the cred is created.

### Access Macros of an Array Service
Nutanix Calm allows you to access macros of an array service using a special macro, which starts with "calm_array". You can configure a VM with replicas and access the common macros of all the replicas.

Let’s look at some of the examples:

* Use the following macro to retrieve the name of all the instances of VM separated by commas. "@@{calm_array_name}@@"
* Use the following syntax to retrieve the IP address of all the instances of VM separated by commas. "@@{calm_array_address}@@"
* Use the following syntax to retrieve the ID of all the instances of VM separated by commas. "@@{calm_array_id}@@"

### Supported Data Types
Macro supports string and numbers data types. You can use them in the following format:

* <strong>String</strong>: "@@{"some string"}@@" or "@@{'some string'}@@" Newline or other such special characters are not supported. You can use \ to escape quotes.
* <strong>Numbers</strong>: Supports integer and float. For example, "@@{ 10 + 20.63 }@@"

### Supported Operations
Following are the supported macro operations:

* Basic binary operations or numbers. For example, "@@{(2 * calm_int(variable1) + 10 ) / 32 }@@".
* String concatenation. For example, "@@{ foo + bar }@@".
* Slicing for strings. For example, "@@{foo[3:6]}@@".

## Quiz: Calm Macros

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/403.jpg)

### QUESTION 2 OF 2
Consider a scenario where you want to use a script to add an array of VM IP addresses of a service named WebServer to a HAProxy configuration file. Which Macro will you use in the script in order to retrieve a comma delimited list of all IPs of the VMs within WebService?

* @@{WebServer.address}@@

## Calm Application Profiles

One of the tasks involved in creating a multi-VM blueprint is to add an application profile. You must select an application profile while you launch a blueprint.

As we discussed in the previous lesson, application profiles often include choices about where an application should run (AHV or AWS), but they can also be about sizing (small or large), or a combination of the two (small AHV or large AHV or small AWS).

An IT operator or developer should have a good understanding of the underlying differences between these choices, while abstracting that complexity from end users.

Let’s look at some of the tips and best practices when creating an application profile.

### Application Profile Tips and Best Practices
### Using default profile

Every blueprint has a default profile - it can be thought of as a base layer of the blueprint.

* The default profile is used in the single-VM blueprint, but it is invisible to the user.
* If needed, the default profile can be renamed for a better description for operators.

### Using additional profiles

Additional application profiles provide the operator role (or higher) deployment choices when using an application deployment.

* This increases blueprint reuse (of actions and governance) by eliminating the need to make separate blueprints for each permutation of deployment.
* Use application profiles to reduce the number of delegated run-time properties. Less choice reduces complexity and increases productivity.

### Naming convention

When naming an application profile:

* Make it as simple and user-friendly as possible.
* Use nouns that reflect the audience use case or jargon.
* Capitalized noun, ideally without spaces.
* Make application profiles a set of mutually exclusive choices.
* Avoid overly specific or jargon names when possible.
* Some examples of right naming conventions are as follows:
* Production, Staging, UserAcceptanceTesting, Test, QualityAssurance, Development, ContinousIntegration
* Public, Private, Hybrid
* AHV, AWS, Azure, GCP, ESX, K8s
* DataCenter1, BranchOffice9, Colo3, DisasterRecoveryWest, DisasterRecoveryCentral
* Small, Medium, Large, Jumbo
* Titanium, Gold, Silver, Bronze

### Sample Usage of Application Profiles

Application profiles express the intent of the blueprint developer to allow end-user choice between multiple deployment scenarios. Some typical choices include:

* Capacity Size: small versus medium versus large resource consumption for different needs on different days. For example, developers may need to frequently create new, small deployments with less CPU, storage, and memory using the latest version of today’s application code, so they would choose a “small” application profile. At the beginning of each week, testers could run a new performance test on a large resource environment using double the CPU, the same amount of memory, and quadruple the storage, so they would choose a “large” application profile, which may also be used by operations for production deployments.

* Infrastructure Provider: for a public, private, and/or hybrid deployment using different infrastructure providers. For example, developers may be restricted by governance to deploy daily workloads only on the private cloud, testers may deploy performance testing only on the public cloud when they need ephemeral resources, and staging and production workloads might always be deployed in a hybrid cloud fashion with a mix of multiple public and private clouds.

* Location and Environmental Resources: different scenarios may need different resources, for example a database address with user and password credentials may vary by location or by environment.

For example, you may have developer teams based in Asia, Europe, and the Americas. An application profile named “Asia” might have a Database variable set for db.asia.example.com, while an application profile named “Europe” might have the same database variable set to db.europe.example.com. Another example could incorporate choice for using development versus a staging database, each with different username and password credentials.

A “development” application profile variables may be set for username = development and password = development_password, while an application profile named “staging” could set the same variables to different values for username = staging and password = staging_password. or Limited to full configuration delegation with run-time property overrides.

* Any combination of the above: a hypothetical “Asia Development” application profile could incorporate all of these elements and more, such as: small capacity size, private cloud provider, located in Asia, and a development environment database variables, including allowing run-time override for any of the properties if desired.

## Quiz: Application Profiles

### QUIZ QUESTION
Select the 2 best practices that apply when naming an application profile.

* Make it as simple and user-friendly as possible.

* Use nouns that reflect the audience use case.

## Calm Actions

Now that we have covered Application Profiles, let’s next learn about application profile actions. An application profile consists of several actions.

Application Profile Actions, or Profile Actions, in short, are a set of operations that you can run on your application. For example, when launching a blueprint, the ‘Create’ action is run. If your application is not needed for a period of time, you could then run the ‘Stop’ action to gracefully stop your application. When you’re ready to resume work, running the ‘Start’ action will bring the app back up.

The default application profile also contains several actions, which appear as gray ovals on a service. Actions consist of one or more tasks. Tasks are executed sequentially on each service. The types of tasks are Execute, Set Variable, HTTP, and Delay.

![](https://video.udacity-data.com/topher/2020/September/5f52ad0b_actions-and-tasks-on-a-service/actions-and-tasks-on-a-service.png)

All services execute their actions and tasks in parallel unless a dependency is created to control orchestration, allowing operational control across the entire application.

Let's review the simplest life cycle actions for IaaS.

### Create and Delete
Create: This action is invoked upon a blueprint launch and covers all services to allow orchestration. It provisions and configures the service in the provider.

Delete: This action deprovisions the services with the provider.

### Start, Stop, and Restart
These actions are available to operate the entire deployment. But in the simplest blueprints, these typically remain empty until populated with tasks. In addition, when the create action is complete, it will immediately call the start action on each service.

Correspondingly, the delete action will call and complete the stop action before performing its tasks on each service.

## Quiz: Calm Actions

### QUESTION 1 OF 2
Which action provisions and configures the service in the provider?
* Create

### QUESTION 2 OF 2
An administrator is running a complex application with databases, web servers, and load balancers. He wants to create a few actions in order to convert his daily routine tasks to one click operation. What type of tasks can he create for each of these services? Select all that apply.

* Execute

* Set Variable

* HTTP

* Delay

## Calm Library Overview

We covered tasks and variables in the previous sections. Let’s see how these can be reused when configuring an application blueprint.

Calm Library allows you to save user-defined tasks (scripts) and variables that can be used by other application blueprints. By using existing user-defined tasks and variables, you do not have to define the same tasks and variables again. You can share tasks and variables listed as part of the library across different projects. You can also customize an existing task or variable.

### Variable Types Overview
Users can create custom variable types for added flexibility and utility. Beyond just string and integer data types, you can create more data types such as Date/Time, list, and multi-line string. List values can be defined as a static list of values or attach a script (eScript or HTTP task) to retrieve the values dynamically at runtime.

While creating a custom variable type, you are required to select a project. However, you can share the variable type with multiple other projects using the "Share" option on the same page.

### Calm Library Overview
You can create tasks while configuring a blueprint and publish these tasks to the library. Nutanix Calm allows you to import these published tasks while configuring other blueprints across multiple projects.

Tasks can be browsed and loaded from or saved to the library, to promote reuse across blueprints. Tasks from the library are copied into a blueprint. They do not update when the library changes, which keeps the blueprints safe.

Let’s see a quick demo on how the Calm library allows you to reuse tasks across blueprints.

Watch the video to follow the tutorial:

[![IMAGE ALT TEXT](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/404.jpg)](https://www.youtube.com/watch?v=PFZmmhJ49xg&feature=emb_logo)

## Quiz: Calm Library

### QUESTION 1 OF 3
When tasks in the library update, the blueprints using these tasks are also updated automatically. State true or false.

* False

### QUESTION 2 OF 3
While creating a custom variable type, you are required to select a ___.

* Project

### QUESTION 3 OF 3
An administrator recognises that a user-defined task (script) can be reused as is by multiple other application blueprints. Hence, he saves the task to the library.

When creating new application blueprints, the admin simply navigates to the task library to copy the task and reuse it, instead of creating one from scratch. This way he has re-used the task for 4 different blueprints.

After a few days, the admin wants to make a few modifications to the task and also ensure that this change is reflected across all the blueprints that are currently reusing this task. So, he manually updates every blueprint using this task.

Should he have updated the task in the task library, instead?

* No, updates to the task library do not affect the blueprint. He has to manually update every blueprint.

## The LAMP Stack

* LAMP = Linux, Apache, MySQL, PHP

LAMP is the most common example of a web service stack, and is popularly used to build dynamic websites and web applications.

Over time, LAMP has become a term used to refer to a generic software model, and the model itself has been adapted to include different components. Three common examples are:

* A variant in which Linux is replaced by Windows, abbreviated as WAMP
* A variant in which Apache is replaced by Nginx, abbreviated as LEMP. Although it may seem odd to have an ‘E’ in the acronym, that comes from the pronunciation of Nginx, which is read as ‘Engine-X’
* A variant in which Apache is replaced by Internet Information Services (or IIS), amusingly abbreviated as WIMP

The original LAMP stack continues to remain popular, however, largely for its flexibility and because it is capable of hosting a variety of web frameworks. For example, if you are familiar with WordPress, Joomla, or Drupal, you may be interested to know that they run on the LAMP stack.

Owing to both its flexibility and popularity, you are likely to encounter the LAMP stack when working with web applications — which is why we are going to build our three-tier Calm web app on the LAMP stack as well.

But first let’s talk about each component of the LAMP stack.

![](https://video.udacity-data.com/topher/2020/September/5f52ad39_lamp-stack/lamp-stack.png)

### Linux
Linux belongs to the family of Unix-like operating systems. It was written by Linus Torvalds and has the features that are typical of a modern Unix OS, including multitasking, virtual memory, shared libraries, demand loading, shared copy-on-write executables, proper memory management, and multistack networking including IPv4 and IPv6.

To use Linux you need to download a distribution, which is a complete Linux system including the kernel and applications. Multiple distributions are available for download and, as you may remember, one that we discussed in an earlier lesson is CentOS.

In the LAMP stack, Linux is the foundation. Everything else runs on top of this layer.

### Apache
The second layer, the web server, is typically the Apache HTTP Server but can also be IIS or Nginx. Apache is used simply because it is a mature, feature-rich product and is arguably the most popular web server on the Internet.

Apache HTTP Server (commonly shortened to just ‘Apache’) is a free, open-source, cross-platform web server that played a pivotal role in the initial growth of the World Wide Web. It overtook NCSA HTTPd, has remained popular since 1996, and became the first web server to host more than one hundred million websites.

Apache’s features include Secure Sockets Layer (SSL) and Transport Layer Security (TSL) support, proxying, large file support, custom log files, and so on. Many features are also implemented as compiled modules, which extend the core functionality of the web server. These include authentication, authorization, support for server-side programming languages such as Perl and Python, and so on.

### MySQL
The third layer is the database layer and has traditionally been filled by MySQL. Popular alternatives include MariaDB and PostgreSQL, as well as NoSQL databases such as MongoDB.

MySQL is a free, open source relational database management system (RDBMS). As with any relational database, it organizes data into one or more data tables, in which the data types are related to each other. These relations help structure data. And from the perspective of the LAMP stack, MySQL stores data that, when queried via scripts, can be used to construct a website.

### PHP
The fourth and final layer of the LAMP stack is the application programming language. While this is commonly PHP, the role can be filled by other languages such as Perl and Python.

PHP was created in 1994 by Rasmus Lerdorf, who wrote a number of common gateway interface programs in C. He extended these programs to work with web forms and communicate with databases, and called this implementation Personal Home Page/Forms Interpreter — which is abbreviated as PHP/FI.

PHP is a general purpose scripting language that is especially useful for web development, and is also used as a general purpose programming language. PHP code is interpreted by a web server via a PHP processor module, which generates the resulting web page.

## Quiz: The LAMP Stack

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/405.jpg)

## Linux Administration

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/406.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/407.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/408.jpg)

### Linux Administration Overview
If you’ve never administered Linux, here is a quick overview with some tips on how to manage a system to give you some familiarity with Linux environments. You’ll see that we leverage this knowledge to automate VM operations.

Every user on a Linux system has an account and programs will execute and run under their account name. Programs have file permissions for user ownership and access; they run under your user account.

Remote access to a Linux VM can be accomplished with command line access via SSH. You will use your SSH key to login to a user account on the Linux system. Since we will be creating new VMs from scratch, we'll usually access ephemeral Linux VMs by IP address.

System maintenance requires programs to be run by an administrative user. The administrative account is called the superuser, so administrative tools often start with su. The first administrative account on every Linux system is user root, but for security purposes, root logins are blocked from SSH access.

Therefore, user accounts can be added to the sudo-ers list to be allowed access to administrative tools. This enables user accounts to preface <strong>sudo</strong> before any command or program, granting superuser access.

To tie this altogether, you will see us add new user accounts with SSH key credentials and sudo permissions in cloud-init!

### Linux Administration Tips
Because Linux derives from Unix, it shares a history and terminology going back to 1971. There can be many interchangeable terms that are synonyms which can confuse new learners, but the following tips will help you.

Case matters, but everything on Linux defaults to use lower-case letters.

Programs are installed by package managers, so application, package, command, and program are roughly equivalent. A whole class of programs provide advanced Internet server functionality on top of an operating system, so synonyms exist for the class of application infrastructure packages: server, service, daemon, facility, and sometimes listener.

We will use the following Internet services for the three tier web application:

* mysqld (MySQL daemon)
* httpd (Apache daemon)
* sshd (SSH daemon)

You will see frequent use of <strong>sudo</strong> on these server facilities in the automation shell scripts. They will use sudo to execute installation, configuration, and operations of the HAProxy load balancer, Apache web server, and MySQL database.

If you ever wonder what a command is or how to use it, you can learn detailed technical usage on most facilities by prefixing <strong>man</strong> on the program, which is an abbreviation for manual page. <strong>E.g.: man httpd</strong>

### CentOS and Red Hat Linux Administration
If you’ve never used a recent CentOS or Red Hat Linux distribution, there are some very basic administrative patterns you should learn. We will use the same release of CentOS and Red Hat in order to keep parity for administrative programs and operations, but there can always be subtle to major differences between Linux distributions and even different releases of the same distribution!

For Firewall and security group access, the SSH service resides on TCP port 22.

Package management uses the command: <strong>yum</strong>
```
sudo yum install -y haproxy
```
Operations of the load balancer, web server, and database use: <strong>systemctl</strong>
```
sudo systemctl start haproxy
```
The standard journal log viewer is: <strong>journalctl</strong>
```
sudo journalctl -u mysqld 
```
Note that you can use <strong>journalctl -f</strong> to keep watching log updates, use Control+C to cancel and return to the command prompt.

Configuration files reside under the <strong>/etc/</strong> directory.

Troubleshooting any logs you can’t find with with <strong>journalctl</strong> mostly reside under <strong>/var/log/</strong> directory. The following are important examples to help you understand the essential facilities of SSH and cloud-init:

* /var/log/messages
> * for general Linux system operation messages

* /var/log/secure
> * for SSH login information

* /var/log/cloud-init.log and /var/log/cloud-init-output.log
> * for cloud-init troubleshooting

One of the benefits of many Linux distributions is that most of the standards outlined above are upheld. When administering Internet services, you will use the above commands and directory locations!

### QUESTION 1 OF 3
Administrative tools often start with _.

* su

### QUESTION 2 OF 3
On CentOS and RedHat Linux systems, on which port does SSH service reside for firewall and security group access?

* TCP 22

### QUESTION 3 OF 3
When you do not know how to use a tool or command, which command helps you by giving access to manual pages for command line utilities and tools?

* man

## Web Server Administration

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/409.jpg)

### Apache Web Server Administration
The Apache web server has a standard install and maintenance cycle using:
```
sudo yum install -y httpd
sudo systemctl {enable,start,status,stop,restart} httpd
```
Firewall and security group access details:

* http is TCP port 80
* https is TCP port 443 (outside of the scope of our course)

Configuration files are under the <strong>/etc/httpd/</strong> directory and the web document root where programs and web pages reside in the <strong>/var/www/html/</strong> directory.

Troubleshooting logs:
```
sudo journalctl -u httpd
tail /etc/httpd/logs/\*.log
```

Further reference: [Apache HTTP Server Project: Documentation](http://httpd.apache.org/docs/)

* Apache version: httpd -v

Tip: Although httpd started the project, the Apache project has grown to a large open source organization for many software projects, so the term is used for both the httpd web server and the umbrella parent organization.

Humor: Apache was named after "a patchy server" to indicate the project’s early days of software development.

### QUIZ QUESTION
Configuration files are under the ___ directory.

* /etc/httpd/

## Load Balancers

Load Balancers are a critical architectural function in modern infrastructure and application design, they serve as a front-end for a service and distribute “load” across service resources. In our lesson, we’ll use a load balancer to split web traffic across the network to a web service array. Often, you will hear the terms request, load, traffic, and transaction used interchangeably. They have very close meanings that may be used separately in each service’s terminology.

For our simple needs, our load balancer will use the simplest distribution mechanism called “round robin.”

![](https://video.udacity-data.com/topher/2020/September/5f52adb6_round-robin-load-balancing/round-robin-load-balancing.png)

A web request from a web client is directed to the load balancer, which picks one web server from the array for the first web request and delivers the web request to it. The web server answers the request and returns the answer through the load balancer back to the web client requestor. For the next web request to the load balancer, it will pick the next web server available in the array. This repeats for each subsequent web request across the entire web server population and will cycle around to the beginning of the web server array.

The load balancer allows flexibility for web operations:

* Performance: distributes web requests, allowing us to scale in and scale out the web tier as transactions grow more complex or resource hungry.
* High uptime: allows removal of an individual web server for maintenance and return once complete while the remaining web servers handle traffic.

Contrast the above benefits to previous strategies to scale up the resources of a single web server to handle more traffic, but this has definite physical limits to scale combined with increasing expense for more CPU and memory and incurs downtime for maintenance.

### Designing the Load Balancer Tier
We’ll use a very popular, open source load balancer called HAProxy, which is included in many Linux distributions, including our choice of CentOS. We’ll install HAProxy and configure it to accept web connections on TCP port 80. Furthermore, we’ll configure HAProxy to distribute requests to the web server array specified using Calm macros for the web service array.

### HAProxy Load Balancer Server Administration

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/410.jpg)

HAProxy uses the standard install and maintenance cycle:
```
sudo yum install -y haproxy
sudo systemctl {enable,start,status,stop,restart} haproxy
```
We are using HAProxy to direct traffic to web servers, so the Firewall and security group access is for http on TCP port 80.

The HAProxy configuration file is <strong>/etc/haproxy/haproxy.cfg</strong>

For troubleshooting logs:

```
sudo journalctl -u haproxy
```
Further reference: HAProxy Project: Documentation

* HAProxy 1.8 Configuration
* HAProxy version: haproxy -v

Tip: HAProxy stands for High Availability Proxy.

### QUIZ QUESTION
What is a load balancer?

* A front-end for a service that distributes “load” across service resources

## Creating a Multi-VM Calm Blueprint

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/411.jpg)

Now that you are aware of all the elements required to create a multi-VM blueprint, let’s now learn about the process to create one.

We gave an overview of multi-VM blueprint in the last lesson. Let’s do a recap and explore further.

Multi-VM blueprint is a framework that you can use to create an instance, provision, and launch applications requiring multiple VMs. You can define the underlying infrastructure of the VMs, application details, and actions that are carried out on a blueprint until the termination of the application.

You can create and configure multi-VM blueprints for the Nutanix, AWS, VMware, GCP, and Azure providers. For simplicity we will cover the process for Nutanix.

Once a provider is configured and a project is created, you can then create a multi-VM Calm blueprint. The process involves six tasks:

* 1. Adding a service.
* 2. Configuring VM, package, and service for your provider.
* 3. Setting up the service dependencies.
* 4. Adding and configuring an application profile.
* 5. Optionally, adding and configuring scale-out and scale in.
* 6. Creating an action

Let’s explore each of these tasks one by one.

### Adding a Service
Services are the virtual machine instances, existing machines or bare-metal machines, that you can provision and configure using Nutanix Calm. You can either provision a single service instance or multiple services based on the topology of your application. A service exposes an IP address and ports on which the request is received.

To add a service, from the Blueprint page, click + Create Blueprint and select Multi VM/Pod Blueprint from the dropdown.

In the Blueprint Setup window:

* 1. Enter the name and description for the blueprint.
* 2. Select a project. The available cloud options depend on the selected project.
* 3. Click Proceed.
* 4. Click + next to the Services. The service inspector panel is displayed.

### Configuring VM, Package, and Service for your Provider
This task involves defining the underlying infrastructure of the VM, application details, and actions that are carried out on a blueprint until the termination of the application on a Nutanix platform.

In the service inspector panel, enter a name for the service. The panel includes three tabs, VM, package and service.

Under the VM tab:

* 1. Enter a name for the VM.
* 2. Select either the existing machine or Nutanix for platform.
* 3. Select the OS type .
* 4. Specify the environment details or clone from the existing one.
* 5. Add credential details.
* 6. Specify the connection details such as port, type and protocol.

Under the Package tab:

* 1. Enter the package name.
* 2. Click Configure Install to install a package.
* 3. Configure tasks.
* 4. You can even add the default system actions, if needed.

Similarly, you can configure the tasks for uninstalling a package. When configuring the tasks, you have the choice to either reuse a system task or create one based on your requirement.

Under the Service tab:

* 1. Enter the service name
* 2. Enter the number of default, minimum and maximum service replicas that you want to create.
* 3. Add variables.

Once you provide all these details and click Save, the blueprint is saved and listed under the blueprints tab.

### Setting Up Service Dependencies
Dependencies define the order in which the system runs the tasks; Calm visualizes this process in the design phase with arrows indicating the direction of Nutanix Calm execution. You can manually define dependencies—a web server depends on a database—or automatically define them with the Calm engine when macros are referenced.

To set up a service dependency:

* 1. Select the service.
* 2. Click the dependency icon.
* 3. Drag-and-drop to the service on which you need to create the dependency.

### Adding and Configuring an Application Profile
You need to apply the application profile while launching a blueprint. To add and configure an application profile:

* 1. Click + icon in the Application Profiles.
* 2. Enter an application profile name.
* 3. Enter the name and value of the variable.
* 4. Check the Secret check-box to hide the variable value.

### Adding and Configuring Scale Out and Scale In
Before creating an action, you can optionally add and configure the scale out and scale in task. The scale-in and scale-out functionality lets you decrease or increase the number of service replicas. When you configure the scaling task as part of a profile action, you can define the number of instances to add or remove for the service per scale action or choose to define the number at runtime.

To add a scale in and scale out tasks, under the Application Profile, click + against Actions.

* 1. Enter the name of the task.
* 2. Select Scaling from the Type drop-down menu.
* 3. Select either Scale In or Scale Out.
* 4. Enter the number in the Scaling Count field.
* 5. Click Save.
The scaling out and scaling in number should be less than the minimum and maximum number of replicas defined for the service.

### Creating an Action
An <strong>action</strong> is a set of operations that you can run on your application that are created as a result of running a blueprint. To create an action:

* 1. Click the + icon in the Actions pane.
* 2. Select the service on which you want to create the task.
* 3. Enter the action details.
* 4. Enter the task details.

Once you have performed all these tasks, you can now see the blueprint in the Blueprints page.

![](https://video.udacity-data.com/topher/2020/September/5f52ade7_creating-an-action-image1/creating-an-action-image1.png)


## Quiz: Creating Multi-VM Calm Blueprint

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/412.jpg)

### QUESTION 2 OF 2
An administrator wants to configure the scale-out functionality when creating a multi-VM Calm blueprint. Thus, he navigates to the Application Profile, clicks + against Actions, enters a name for the task, and selects Scale Out from the Type drop-down menu.

What is that he should remember when entering a number in the Scaling Count field?

* The scale count number must be less than or equal to the maximum number of replicas defined for the service.

# VERY IMPORTANT FOR SOLVING THE SECOND PROJECT
### Exercise - Create a Multi-VM Blueprint
In this series of exercises, you will pull all of the concepts you’ve learned together to build a load-balanced multi-VM web application using the LAMP stack. This is commonly referred to as a “two-tier” web application. You will use a current CentOS distribution for the Linux OS and host the web application on the private cloud with Nutanix AHV as the VM hypervisor.

We’ll walk through these steps together.

In the first exercise, you’ll create a new multi-VM blueprint:

* Add your SSH key credentials
* Add a WebServer VM and configure CentOS with cloud-init and shell tasks
* Install and configure an Apache web server
* Configure a one page PHP web application

In the second exercise, you’ll add a load balancer service:

* Add an HAProxy VM and configure CentOS with cloud-init and shell tasks
* Install and configure HAProxy load balancer to serve requests to the WebServer

And in the third exercise, you’ll add scalability to the WebServer to increase application performance, making it a web-tier array!

(In the next lesson, you will address orchestration between the Web Server and Load Balancer service dependencies.)

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/413.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/414.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/415.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/416.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/417.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/418.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/419.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/420.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/421.jpg)

## Exercise Solution: Create Multi-VM Blueprint

Please watch the videos to follow the tutorial

[![IMAGE ALT TEXT](https://github.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/blob/main/images/422.jpg)](https://www.youtube.com/watch?v=NquHQtPiTXI&feature=emb_logo)

[![IMAGE ALT TEXT](https://github.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/blob/main/images/422.jpg)](https://www.youtube.com/watch?v=ilFzJl_I030&feature=emb_logo)

[![IMAGE ALT TEXT](https://github.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/blob/main/images/422.jpg)](https://www.youtube.com/watch?v=kLx5Rq-WLMU&feature=emb_logo)

# VERY IMPORTANT FOR SOLVING THE SECOND PROJECT
## Exercise: Add Load Balancer Service

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/423.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/424.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/425.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/426.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/427.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/428.jpg)

## Exercise Solution: Add Load Balancer

Please watch the videos to follow the tutorial

[![IMAGE ALT TEXT](https://github.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/blob/main/images/422.jpg)](https://www.youtube.com/watch?time_continue=3&v=Z2Bz3xx72lU&feature=emb_logo)

# VERY IMPORTANT FOR SOLVING THE SECOND PROJECT
## Exercise: Add Web Server Scaling

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/429.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/430.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/431.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/432.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/433.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/434.jpg)

## Exercise Solution: Add Web Server Scaling

Please watch the videos to follow the tutorial

[![IMAGE ALT TEXT](https://github.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/blob/main/images/422.jpg)](https://www.youtube.com/watch?v=tjTA3o04Zro&feature=emb_logo)

## Glossary

### Actions - 
A set of sequentially executed tasks in a blueprint. Basic actions included in every blueprint consist of: Create, Delete, Stop, Start, Restart.

### Application profiles - 
Application profiles often include choices about where an application should run (AHV or AWS), but they can also be about sizing (small or large), or a combination of the two (small AHV or large AHV or small AWS).

### Dependency - 
A logical sequential connection between services, orchestrating their basic actions together.

### Macro - 
Either a Calm built-in or blueprint specified variable that can be used in tasks and variables.

### Multi-VM Blueprint - 
Multi-VM blueprint is a framework that you can use to create an instance, provision, and launch applications requiring multiple VMs.

### Service - 
An instance of a substrate, typically a virtual machine, existing machine, or a Kubernetes pod.

### Substrate - 
An infrastructure provider instance, a blueprint can use all the providers enabled in a project.

### Task - 
An individual stage of operational execution in an action.

### Variable - 
A blueprint property: statically set by the developer role with a default value, used as a macro in task, and specified with a runtime property to delegate setting by an operator role during blueprint launch.

## Lesson Conclusion

This concludes our lesson, Creating and Publishing a Multi-VM Calm Blueprint. Before we move to the next lesson, let's do a quick recap of what was covered.

Some of the common blueprint lifecycle management tasks are cloning, deleting, and uploading a blueprint. You can clone an application blueprint from a pre-seeded application blueprint. You can download the blueprint with the credentials and secrets. You can upload a configured blueprint to the blueprints tab.

The environment is mandatory to publish the application into the marketplace. You can define the environment either when creating a project or when creating a blueprint. If you have configured the environment when creating the project, you can clone that configuration for the VM while configuring a blueprint.

Macros enable you to access the value of variables and properties set on entities. Calm macros are part of a templating language for Calm scripts.

Application profiles often include choices about where an application should run (AHV or AWS), but they can also be about sizing (small or large), or a combination of the two (small AHV or large AHV or small AWS). Every blueprint has a default application profile, it can be thought of a base layer of the blueprint.

Profile Actions are a set of operations that you can run on your application. Actions consist of one or more tasks. Tasks are executed sequentially on each service.

Calm Library allows you to save user-defined tasks (scripts) and variables that can be used by other application blueprints.

Finally, a Multi-VM blueprint is a framework that you can use to create an instance, provision, and launch applications requiring multiple VMs. Creating a multi-VM blueprint involves adding a service, configuring the VM, package and service for the provider, setting up the service dependencies, adding and configuring an application profile, and creating an action.

This completes all the topics necessary to configure a blueprint. So far, we have covered all Calm constructs and walked you through the process to create a single and multi-VM Calm blueprint. In the next lesson, we will explore how Calm automates a 3 tier web application.



________________________________________________________________________________________________________________________________________________________________________________



# LESSON 5 CALM AUTOMATION FOR A 3-TIER WEB APPLICATION 

## Lesson Overview

In this lesson, the final lesson of this course, we’re going to bring everything together. So far, we have focused on deepening your understanding of the various components of Calm.

We began by discussing Prism Central, and how some Prism Central capabilities tie directly into Calm. Examples of these interrelated features are:

* How Prism Central Role Based Access Control (RBAC) feeds into Calm roles
* How image management in Prism supports service definitions in Calm

Then we moved on to Calm itself. We explored several major Calm features and took a close look at their UI elements, as well as the ways in which you would typically interact with these features. So far, we’ve gone into detail about:

* Providers: Providers are cloud service providers, bare-metals, or existing machines that you can use to deploy, monitor, and govern your applications. Essentially, configuring a provider provides the required authorization for Calm to manage your applications using the provider’s virtualization resources.

* Projects: A project defines a set of Active Directory groups with a common set of requirements or a common structure and function, such as a team of engineers collaborating on a product. The project also specifies the roles to associate with its members, networks that they can use, infrastructure to deploy onto, and (optionally) usage limits on infrastructure resources. You can also define the environment associated with a project, in case you want to publish the applications into the Marketplace.

* Role-Based Access Control (RBAC): RBAC lets you define different roles in an organization and assign permissions accordingly. Within Calm, RBAC enables organizations to control who can perform specific actions.

* Blueprints: Blueprints are recipes for applications. These recipes encompass application architecture and Infrastructure choices, provisioning and deployment steps, application binaries, command steps, monitoring endpoints, remediation steps, licensing and monetization, and policies. Every time a Blueprint is executed it results in an application deployment, these workloads can be managed from the Applications menu.

* The Marketplace: The Marketplace is a common platform for both the publisher and the consumer, and provides you with the ability to provision an application instantly. It provides a set of pre-seeded application Blueprints that are available for you to use.

* Application Profiles: Application Profiles expose simple choices to your end users. These choices are often about where an application should run (AHV or AWS). They can also be used for ‘t-shirt’ sizing (small or large), or a combination of location and sizing (small AHV or large AHV or small AWS).

* Services: Services are logical entities exposed by an IP that span all application profiles and are managed by Calm. End users and services communicate with each other over a network using their exposed IPs and ports.

* Substrates: Substrates are combinations of the underlying cloud and the VM instance. When you select the desired cloud in the Calm UI, all the fields required to create a VM instance on that particular cloud are displayed. The combination of these fields is a substrate.

* Service Actions: Services Actions are a set of operations that you can run on your application. For example, when launching a blueprint, the ‘Create’ action is run. If your application is not needed for a period of time, you could then run the ‘Stop’ action to gracefully stop your application.

* Variables: The properties such as IP addresses, DNS names, and instance IDs that are associated with the services provisioned in blueprints are called variables. They can be static, provided at run time, or generated during blueprint or action runs.

Macros: Macros enable you to access the value of variables and properties set on entities, and help you make generic scripts and create reusable workflows.

Each of these features represents an essential element of Calm’s development workflow and overall application lifecycle.

And in this lesson, we are going to bring all of this knowledge together. We are going to use Calm’s various capabilities to create a web server application and understand — from a real-world development perspective — what Calm is really capable of.

To achieve a three tier web application, we will be discussing:

* Databases
* Calm Orchestration for order of operations across dependent services
* Advanced Calm Actions, in a little more detail than we have in previous lessons

Let’s begin.

## Big Picture

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/435.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/436.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/437.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/438.jpg)

Before we move on with this lesson, which is the culmination of everything you have learned so far, let’s take a moment to circle back to the beginning and see how everything ties together.

As you may remember, we spoke about how businesses constantly seek to improve overall IT agility and responsiveness to enable more rapid innovation. However, application development and delivery is growing in complexity, making it challenging for teams to keep up with increasing expectations to move faster.

As a result, when thinking about the applications that drive and support a business, there are a number of important factors to consider about the applications themselves, as well as their deployment and maintenance:

* Today’s mission critical and complex business processes need a plethora of applications to work in harmony
* The growing number of interdependent components, and reliance on manual processes, lead to frequent unplanned downtime due to errors
* Knowledge silos force everyone to work in a partial state of isolation, leading to a lack of productivity in the business
* Hybrid clouds introduce inoperable and disparate platforms, adding significant management challenges

![](https://video.udacity-data.com/topher/2020/September/5f52b103_advanced-app-level-orchestration/advanced-app-level-orchestration.png)

Hyperconverged solutions provide a much simpler infrastructure that scales linearly and radically reduces the complexity inherent to traditional data center architectures. But to truly transform how IT teams can support the business, a new approach that automates all aspects of how applications are created, consumed and governed is needed.

Melding advanced application-level orchestration with a full cloud-driven infrastructure stack can achieve repeatable, simple and automated management of applications – across a variety of environments including private and public clouds.

And as we’ve seen in this course, that advanced application-level orchestration is provided by Nutanix Calm.

![](https://video.udacity-data.com/topher/2020/September/5f52b129_advanced-app-level-orchestration-with-calm/advanced-app-level-orchestration-with-calm.png)

Calm provides a single pane for application automation and lifecycle management for Nutanix, VMWare, and public clouds, as part of the Nutanix Enterprise Cloud Platform.

Calm orchestrates the provisioning, scaling and management of applications across multiple environments to make the entire IT infrastructure more agile and application centric.

And this lesson illustrates how the various components of Calm come together to address the needs of enterprise applications. Using a three-tier web application as our example, you will explore how Calm delivers app-centric automation and lifecycle management, policy-based governance, self-service provisioning to any enterprise in need of these capabilities.

## Quiz: Big Picture

### QUIZ QUESTION
Which of the following statements are common challenges when working with enterprise applications? (may be more than one answer)

* Mission critical and complex business processes need a plethora of applications to work in harmony
* Knowledge silos lead to a lack of productivity in the business

## When and When Not to Use Calm Automation

After everything we’ve seen, a good question to be asking yourself is ‘When am I likely to use Calm?’. Helpfully, the answer is remarkably straightforward.

Much of Calm’s power lies in its universality: whenever you need to work with an application, whether you’re deploying it in a single cloud or multiple clouds, if there’s a need for automation and orchestration Calm will be useful to you.

![](https://video.udacity-data.com/topher/2020/September/5f52b174_graphic-2/graphic-2.png)

When you’re considering whether or not to use Calm for an application deployment, there are three key factors that you need to consider.

### How the application will be deployed
* Will it be on-prem?
* Will it be on the cloud?
* Will it be both on-prem and on the cloud?
* Will part of the application be on-prem and part of it on the cloud?

### The users of the application
* Is it beneficial for users to be able to deploy the application without intervention from IT?
* Will this application be deployed frequently?
* Is the application likely to be deployed multiple times?

### The application itself
* Is there value in automating deployment?
* Is there value in automating management?
* Is there value in making application deployment consistent and repeatable?

If the answer to a good number of these questions is yes, then you have a good use case for Calm on your hands. And, as we’ve learned so far — and will see in this lesson as well — irrespective of the nature and the complexity of the application itself, Calm brings simplicity and ease of use to both your experience, as IT, and to your users’ experience as well.

## MySQL Database Server Administration

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/439.jpg)

The MySQL database upholds the standard install and maintenance command tools:
```
sudo yum install -y mysqld
sudo systemctl {enable,start,status,stop,restart} mysqld
```
The {1,2,3} list is shorthand for all of the standard operations you can choose to perform on most services with <strong>systemctl.</strong>

For Firewall and security group access, mysqld listens on TCP port 3306.

The configuration file is <strong>/etc/my.cnf</strong>

For troubleshooting database logs:
```
sudo journalctl -f -u mysqld
sudo tail /var/log/mysqld.log
```
The configuration of data, users, and operations inside the database requires the database to be started, then administered via the <strong>mysql</strong> client. Databases contain their own users, credentials, and role permissions. Everything inside the database is independent of operating system user credentials, so the database user root is not the same as Linux user root. <strong>mysqldump</strong> is included in the MySQL package for creating a database backup.

Accessing MySQL from the command line requires database user credentials, e.g.:
```
mysql --user=root --password=example
mysqldump --all-databases --user=root --password=example
```
After authenticating with database credentials, commands can be issued. The standard for database commands is SQL: Structured Query Language. While MySQL can deviate from the standard and vary between different MySQL major releases, the majority of SQL is compatible across most different database and versions.

You will see the automation scripts leverage <strong>mysql</strong> command to authenticate as database user root and then perform SQL operations. Those operations will include creating users, granting roles to users, and creating database structures.

Database structures are organized as: databases and tables, which are addressed by database_name.table_name. You can think of a database as a spreadsheet and a database table as a tab or layer in that spreadsheet. So a database is a collection of tables.

Any application not on the database VM can authenticate with a database user over the network and issue SQL commands to interact with a specific database and database table. The web application will need these pieces of information: a database server address, database user and password, and a database name and table. The PHP language database MySQL driver will use the default MySQL TCP port, so it is omitted unless there is a need for custom configuration.

A database structure, called a database schema, defines the types of data it will store. Building on the spreadsheet example, think of a database table as the different columns with data formats in a spreadsheet. Finally, the data is populated into the table via SQL statements such as INSERT, UPDATE, and DELETE. This can be thought of as editing the data cells in spreadsheet rows.

Further reference:

* [MySQL Documentation](https://dev.mysql.com/doc/)
* [MySQL server administration](https://dev.mysql.com/doc/refman/8.0/en/using-systemd.html)
MySQL version: ```mysqld -v```

# VERY IMPORTANT FOR SOLVING THE SECOND PROJECT
## Exercise: Add Database Service

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/440.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/441.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/442.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/443.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/444.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/445.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/446.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/447.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/448.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/449.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/450.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/451.jpg)

## Exercise Solution: Add Database Service

Please watch the videos to follow the tutorial

[![IMAGE ALT TEXT](https://github.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/blob/main/images/422.jpg)](https://www.youtube.com/watch?v=jOLJ0MB56pU&feature=emb_logo)

## Orchestration Dependencies Across Services

By default, tasks are executed sequentially on each service for each action in a blueprint and each service will operate in parallel, fully independent of each other. However, this is rarely useful for multiple services: they often work together and require operational coordination. Orchestration is how Calm drives the order of operations across all services in the blueprint.

Calm automatically determines orchestration dependencies between services when a task in an action uses a macro value from another service in the blueprint. An orange orchestration arrow, or "edge," represents the order in which Calm initiates the various tasks. For example, we saw that the load balancer service configuration depended on knowing each web server IP address using the web service address macro, which is shown with an orange orchestration edge going from the web server "create" task to the load balancer "package install" task.

Calm will validate all dependency arcs when a blueprint is saved and alert if there are any cyclical or ambiguous errors. This is why you may not see dependencies during the creation or editing of a multi-VM blueprint until saving the blueprint.

### Orchestration Dependencies across Services
A dependency, as the name suggests, it used to define which services in your application depend on another service (or multiple services) for properties or information, such as IP addresses and DNS names.

In essence, since services require operational coordination, dependences allow you to define the order in which tasks must be executed.

If you do not use macros in your blueprint for automated orchestration as covered in the previous section, a simpler method exists to allow logical orchestration across multiple services during all of the standard actions (create, start, stop, restart, delete). Simply use the white arc to connect one service to another, starting from the dependent and ending on the source of the dependency.

When you save the blueprint, you will see orchestration dependency arcs created for each of the actions, even if each action has no tasks. Furthermore, you will notice that the orchestration is reversed in create versus delete and start versus stop actions.

### Setting Up Service Dependencies
As described earlier, without the use of macros, setting up dependencies is quite literally a matter of drag-and-drop. When you select a service, you will see the Create Dependency icon, as shown in the following figure.

![](https://video.udacity-data.com/topher/2020/September/5f52b205_drag-and-drop-service-dependencies/drag-and-drop-service-dependencies.png)

Simply click that Create Dependency icon and drag it to the dependent service in order to create your dependency. If done correctly, you will see white arcs/lines connecting your services to each other, indicating which services are dependent upon which other services.

## Quiz: Orchestration Dependencies

### QUESTION 1 OF 2
What is a dependency in Nutanix Calm?

* A way to define the order in which tasks must be executed

## QUESTION 2 OF 2
How can you create a dependency between services in Calm?

* Click the Create Dependency icon
* Drag it to the dependent service

# VERY IMPORTANT FOR SOLVING THE SECOND PROJECT
## Exercise: Add Dependencies

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/452.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/453.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/454.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/455.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/456.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/457.jpg)

## Exercise Solution - Add Dependencies

This pair of videos will walk through the same steps of the solution we went through above.

[![IMAGE ALT TEXT](https://github.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/blob/main/images/422.jpg)](https://www.youtube.com/watch?v=P0BBEio7NMc&feature=emb_logo)

[![IMAGE ALT TEXT](https://github.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/blob/main/images/422.jpg)](https://www.youtube.com/watch?v=6vx9_MghS94&feature=emb_logo)

## Advanced Calm Actions

As we’ve discussed in previous lessons, an action is a set of operations that you can run on an application or a service. There are two major types of actions: Profile Actions and Service Actions.

Profile Actions are run on applications and are of two types: system-defined profile actions, and custom profile actions. System-defined profile actions are automatically created by Calm in every blueprint and underlying application. These actions are typically Create, Start, Stop, Delete, and so on. Custom profile actions are created by the person developing the blueprint, and are typically Upgrade, Scale In, Scale Out, and so on.

Service Actions are run on individual services and typically span application profiles. So, for example, consider that you have two profiles set up in a blueprint, AWS and AHV. If you create a service action for the AHV profile, it will be available in the AWS profile as well. As with profile actions, there are two types of service actions: system-defined and custom.

For this lesson specifically, we need to take a closer look at how Calm actions can handle more complex PaaS and SaaS needs. This is typically achieved through:

* Additional Create stages
* Additional Delete stages
* Scale-in and Scale-out
* Custom actions for ongoing maintenance and operations

### Additional Create Stages: Pre-create and Package Install
Pre-create actions are run before the substrate is created. A common use case for this is to make an API call into an IP Address Management (IPAM) system to get an IP for a to-be-created VM.

Package Install actions, on the other hand, are operations which are run during the Create profile action. In other words, they are operations that run when a user first launches a blueprint. Package Install is unique to each application profile, which means your tasks or the task contents can vary depending upon the underlying cloud or the app’s size.

### Additional Delete Stages: Package Uninstall and Post-Delete
Package Uninstall actions are operations which are run during the Delete profile action. That is, they are operations that run when a user finally deletes the entire application. Like Package Install, Package Uninstall is also unique to each application profile, so tasks or task contents can vary depending upon the underlying cloud or app size. An example of a package uninstall task might be to cancel or release a license entitlement when the software is removed from the service or to orchestrate dependent changes on other services required for the uninstall process.

Post-delete actions are run after the substrate is deleted. For example: when a VM is deleted, the post-delete action would trigger removing the VM server property held by external systems. Typical use cases would involve deprovisioning the IP, DNS, and/or MAC addresses of VMs with various different inventory, monitoring, or change management database (CMDB) systems. For example: when a VM is deleted, the post-delete action would trigger removing the VM server property from any of the following:

* Retire the IP address from the IPAM system, such as Infoblox, BlueCat, Redhat Satellite, etc.
* Delete all associated DNS records from the DNS provider, such as Bind, PowerDNS, AWS Route53, etc.
* Remove VM from asset inventory in ServiceNow.

In other words, post-delete action and package uninstall tasks help clean up and remove everything necessary outside of the application services when an application is deleted.

### Scale-in and Scale-out
Although we’ve discussed these topics previously, let’s take a moment to recap them both here.

Scale-in functionality enables you to decrease the number of replicas of a service deployment. The number of instances to be removed from a service for each scale-in action is defined in the blueprint, or by utilizing macros, can be configured to be set when the action is initiated by an end user. This is typically done when configuring the task in the profile action. The scale count number must be less than or equal to the minimum number of replicas defined for the service. The VM that is created last is deleted first.

Scale-out functionality is the opposite of scale-in — it enables you to increase the number of replicas of a service deployment. The number of instances to be added to a service for each scale-out action is defined in the blueprint, when configuring the task in the profile action. The scale count number must be less than or equal to the maximum number of replicas defined for the service.

### Custom Actions for Maintenance and Operations
As you’ve learned from the Create action, complex orchestration across the entire application services can be configured during deployment of the application and infrastructure. We’ve also covered the scaling actions for changing a running application’s replica services. How could one perform any other change to a running application?

Custom actions can be created in Calm blueprints by the developer role for post-deployment or “day two” operations, to allow any simple or complex operation to be orchestrated during the running state of the application. Aside from the existing start/stop/restart and delete actions, custom actions allow life cycle operations and updates after the birth, but before the death or termination of the application workload.

Here are some typical maintenance examples:

* Add/update/reset a user credential to a service, e.g.: add a new database user
* Add/update/reinstall a new version of a package, e.g.: a web application update
* Add/update a configuration and reload a service, e.g.: a web server change
* Backup/restore a VM disk or service, e.g.: a database backup
* Update an operating system, e.g.: install security updates
* Any combination of the above

Because these custom actions can be delegated to any user or group in the project with Operator role or higher, these auditable actions can be made self-service for end users, freeing valuable time to IT and Operations staff. Even better, periodic scheduling systems or monitoring systems can detect problems that trigger these custom actions for automated, continuous operations via Calm APIs to allow “lights-out” remediation and maintenance of applications around the clock.

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/458.jpg)

# VERY IMPORTANT FOR SOLVING THE SECOND PROJECT
## Exercise: Add Database Backup

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/459.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/460.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/461.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/462.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/463.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/464.jpg)

## Exercise Solution: Add Database Backup

Please watch the videos to follow the tutorial

[![IMAGE ALT TEXT](https://github.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/blob/main/images/422.jpg)](https://www.youtube.com/watch?v=wGYZ0-2mJ28&feature=emb_logo)

## Glossary

### Dependency - 
Defines which services in your application depend on another service (or multiple services) for properties or information, such as IP addresses and DNS names.

### Orchestration dependency - 
The determination of the order in which dependent tasks are executed across services.

### Profile action - 
A set of operations run on an application.

### Service action - 
A set of operations run on a service.

### System-defined profile actions - 
Basic profile actions offered by default by the system, such as Create, Start, Stop, and Delete.

### Custom profile actions - 
Profile actions created by the creator of the blueprint for tailored purposes.

### Pre-create actions - 
Actions that are run before a substrate is created.

### Package Install actions -
Operations run during the Create profile action, when a user first launches a blueprint.

### Package Uninstall actions - 
Operations run during the Delete profile action.

### Post-delete actions -
Actions run after a substrate is deleted.

## Lesson Conclusion

With this, we come to the end of both this lesson and this course. Let’s take a brief moment to recap all that we’ve discussed. We have taken a close look, both conceptually and practically, at:

* Prism Central and how it allows you to efficiently manage multiple clusters and multiple users at scale
* The Calm interface, how to access it, and its elements
* Blueprints, which are the heart of Calm’s automation and orchestration capabilities, and turn applications into repeatable, reusable, automated units
* The Marketplace, which enables true self-service for users and frees up IT time for more strategic initiatives in service of the business
* The various features that you need to understand in order to work with blueprints and the Marketplace, such as providers, projects, environments, macros, variables, actions, RBAC, and more

And although we’ve spent a lot of time on Calm’s major capabilities, we hope your key takeaway from this course is broader in scope than just the features of a software product.

Calm is valuable only because automation itself is so critical.

For example, why do users like the cloud? With the availability of easily accessible and usable cloud resources, IT is no longer the only provider of infrastructure. In many cases, IT is seen as too slow. How did we get here and how can IT close this gap?

We often talk about cloud adoption in terms of OPEX/CAPEX and saving by closing data centers, but why do end users create their own cloud account? In AWS spinning up a new ‘VM’ is only a few clicks (and credit card swipe) away. The AWS marketplace has over 5000 different applications, ready to launch when you are. It doesn’t require you to fill out a standardized form that doesn’t really meet what you need, doesn’t require waiting, doesn’t require interacting with another person, and doesn’t require fixing misconfigurations from the inevitable game of telephone that follows. One-click and you’re off. How can IT compete with that?

Automation is the public cloud’s true differentiator. Automation is what allows these instant-on experiences and the only way to operate at massive scale. Luckily, automation isn’t a tool exclusive to public clouds and is the key for IT to rise to these new agility demands. With automation, IT can turn complex, multi-step, multi-day provisioning cycles into one-click actions that span across teams and siloed expertise. IT can use automation to provide the same cloud experience that their users expect, while ensuring that corporate policy is properly applied, no matter where it’s deployed. That security rules are followed. That IT is still in control. Automation is the key to a true cloud-like experience on-premises.

Simply using this automation in the cloud is limiting. There is never a single right answer in IT; it’s always a balancing act based on the current situation. New information or capabilities could change our decision calculus. If we use an inflexible automation tool or one locked to a cloud, we’re handcuffed. We can’t extend the automation to existing machines and are forced to use an inferior technology.

This inherent flexibility is a core benefit of Nutanix Calm. And that is what we’ve really explored in this course: How IT can turn self-service into the expectation, instead of the exception.

## Congratulations

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/465.jpg)



________________________________________________________________________________________________________________________________________________________________________________
________________________________________________________________________________________________________________________________________________________________________________



# FOURTH COURSE PUBLIC AND HYBRID CLOUD MANAGEMENT

________________________________________________________________________________________________________________________________________________________________________________

# LESSON 1 STRATEGIES FOR HYBRID CLOUD DESIGN 

## Lesson Overview

Welcome to the final course of your Hybrid Cloud Engineer Nanodegree program. In this course, we’re going to elevate and wrap up the conversation that we’ve been having about Nutanix Calm automation.

In the very first course of this Nanodegree, we spoke about the hybrid cloud: everything you needed to know to understand what it means to be hybrid and to transition your company to being cloud smart. Then, in the next course, we covered several key principles of automation and a product that will help you implement them — Nutanix Calm. And now, as we begin this course, we’re going to take a step back and upwards, and look at our subject from twenty thousand feet.

At the very beginning of the previous course, we spoke about how automation alone isn’t enough. Workloads change rapidly and keeping up with configuration and deployment changes is both complicated and error prone. At the same time, digital transformation has changed the way organizations think about business models and processes.

As a result, IT teams are transitioning to DevOps models to deliver new applications and services, close the gap between development and operations, and keep pace with the evolving needs of the business.

That mindset, the DevOps mindset, is what we’re going to focus on in this lesson. DevOps isn’t about just implementing processes here or optimizing a workflow there. DevOps changes the way you evaluate, analyze, and design solutions for business problems.

We will discuss:

* Your role in evaluating infrastructure providers and avoiding lock-in, as well as tools and resources that you can use to move workloads between clouds
* The pets vs. livestock view of infrastructure to remove single points of failure, implying that resources be distributed, fungible, and ephemeral
* How thinking about push button environments, configuration management, and automation across hybrid and multi-cloud deployments accomplish agility
* The rise of immutable infrastructure and the benefits it offers to a business
* Four key concepts for the software development lifecycle — continuous integration, delivery, deployment, and operations
* Advanced Calm features, such as Windows alternatives to Linux and various associated components, and the options available to you when working with Prism Central APIs

If that sounds weighty…well, that’s because it is. But by the end of this course, you will have learned how to extend your previously created blueprint into the public cloud and will have a clearer, firmer grasp of how to think about, design, and architect truly hybrid solutions.

Let’s begin.

## Overview

![](https://video.udacity-data.com/topher/2020/September/5f63e881_big-picture-nutanix-c3/big-picture-nutanix-c3.png)

The goal for a hybrid cloud engineer is to design and execute the organization's business to run in a uniform and scalable manner for consistent operations and governance. In the <strong>Modern Private Cloud Infrastructure</strong> course, you learned how to operate a modern private cloud and in the <strong>On-Premises Private Cloud Automation</strong>course, you learned how to automate private cloud workloads from an IaaS to PaaS to SaaS cloud experience. We'll use everything covered so far, map the parallels to the public cloud, and then augment our existing automation to use the public cloud in a hybrid manner.

In the <strong>Modern Private Cloud Infrastructure</strong> course, we covered the NIST definition of cloud and the common mistake to conflate the term exclusively with public cloud. Furthermore, we showed how (public) cloud first has not always been the best choice and the strategy has evolved to cloud smart. Hence the industry has emphasized hybrid cloud solutions in order to achieve cloud smart.

Correspondingly, we will tackle the difference between creating and moving workloads; moving or translating a workload between two infrastructure providers does not achieve the goal of cloud smart.

The definition of hybrid from Wiktionary: "Something of mixed origin or composition; often, a tool or technology that combines the benefits of formerly separate tools or technologies." We will explore hybrid in a few manners during this course:

* Combining public and private clouds into a hybrid cloud application deployment for scalable performance
* Combining different deployment scenarios under the same governance and operational model for consistency

Accomplishing these simple goals can be hard when tools and providers are typically domain specific, resulting in separate silos of abilities and fragmentation. The hybrid cloud engineer must always arbitrate this natural conflict: that is, evaluate a new capability that satisfies a new business requirement (for a single platform, cloud, tool, etc.) against the complexity required to reproduce it in a hybrid model.

![](https://video.udacity-data.com/topher/2020/September/5f63e8ea_developing-your-intuition-nutanix-c3-l1/developing-your-intuition-nutanix-c3-l1.png)

In other words, many bottoms-up and domain-specific automation approaches, methods, and tools challenge the ability to inter-operate consistently with multiple providers. Fortunately, Nutanix Calm blueprints incorporate internal and external technologies and providers which can be blended together easily to create, consume, and manage the workload life cycle: this is an inherently hybrid approach!

## Infrastructure Provider Strategies

Infrastructure providers are similar in that they offer compute, memory, and storage often consumed as VMs. They also offer many advanced PaaS and SaaS-like facilities and applications, although these can be proprietary in their feature set and operation. The potential proprietary nature of any PaaS and SaaS feature, operation, and API can form a dependency which causes fragmentation and provider lock-in. On the other hand, making advanced features and applications work in a provider-independent fashion also has costs to develop and operate.

### The First Problem: Lock-ins and Leaving Providers
The first problem encountered when we speak to customers who ask how to make one public cloud SaaS offering work the same way on another public cloud or private cloud, is not realizing they have taken on a proprietary arrangement.

A hybrid cloud engineer must be aware of these business lock-ins and negotiate requirements and tradeoffs when adopting or avoiding them. Simply put, a hybrid cloud engineer should advise when the evaluation to leave a provider must be added as a business requirement.

![](https://video.udacity-data.com/topher/2020/September/5f63ea43_the-first-problem-lockins-and-leaving-providers/the-first-problem-lockins-and-leaving-providers.png)

Therefore, treating compute, memory, and storage for VMs should be considered a safe target for hybrid cloud applications to preserve infrastructure provider independence for a cloud smart strategy.

### The Second Problem: The Fallacy of Lift-and-Shift
The second problem customers ask to solve is for tools or services to move VM workloads between public and private clouds.

The most common strategy for migrating workloads among datacenters, infrastructure providers, hypervisors, clouds (or even from physical to virtual machine, or from virtual machine to container) is through a storage conversion. This strategy is often called “lift and shift,” because it represents the equivalent of a fork-load uplift of the entire captured state of the machine - moving the disk image (and any potential conversion) and dropping it off at the new destination to complete reinstantiation.

“Lift and shift” is the easiest strategy to adopt because it can be accomplished with backup and restoral procedures and tooling. Most IT practitioners are familiar with this process given that:

There is an entire industry dedicated to storage backups.
Backup and restoral should be a standard operation for most IT organizations.
Backups are often a component for disaster recovery, which is another critical facility for IT organizations.

![](https://video.udacity-data.com/topher/2020/September/5f63ea8f_the-second-problem-the-fallacy-of-lift-and-shift/the-second-problem-the-fallacy-of-lift-and-shift.png)

The ultimate issue with a lift and shift strategy is that it is a large, complex state transfer that entails the entire operational effort and history to maintain the workload up to the date of the snapshot or backup. The backup preserves every undocumented change control and pet operation done by hand, such as adjustments to the operating system, application, and server configuration, security updates, and patches.

Of course, any undetected nefarious, bad practices, or temporary and accidental changes, are also preserved and these changes are compounded over the lifecycle of years for a typical workload. Without extreme diligence in tooling and audits for change control operations, the state of the workload is unknowable.

A large auditing industry exists around business documentation and enforcement of operational procedures for change, but short of a disaster recovery event, no audit can empirically test and validate those procedures.

### Working with Different Migration Tools
There are many tools available for migration, and which one you use depends often on the environment you have and the workload you’re moving.

![](https://video.udacity-data.com/topher/2020/September/5f63eabd_working-with-diff-migration-tools-all/working-with-diff-migration-tools-all.png)

Let’s consider vSphere, as an example. If your migration is relatively simple, you could use Shared Nothing vMotion. vMotion is a very common choice for the vast majority of VMware to VMware migrations and works really well.

But let’s say you have a migration scenario in which orchestration is needed and you need to move large datasets in the background before a cutover occurs. Zerto might be a better solution, and it also works if you’re going between systems that don’t support vMotion for one reason or another.

What about per-VM migration? For that, you have vSphere Replication, which can be used as a standalone, tactical migration tool. You’d typically use this if there’s no vMotion support, if you’re going from AMD to Intel, moving between physical sites, or if you’re preseeding data.

Then, if you have physical workloads that you need to convert to virtual machines, you could always use VMware Converter for those P2V migrations. And then if you want a general-purpose migration tool, there’s Sureline, which supports a wide variety of sources and targets, including physical, virtual, and cloud.

But all of this is only really applicable if you have a vSphere environment.

If you’re running on Hyper-V, Microsoft provides native tooling. Hyper-V also has a shared nothing migration feature that works for systems that are Windows Server 2012 or later.

And finally, Nutanix has a product called Move, which migrates VMs from other platforms to the Nutanix Enterprise Cloud with just a few clicks. It’s available at no cost to any licensed Prism users, so if you have a Prism license, you could go to the downloads area of the Nutanix Support Portal and get Move right now.

You can use Move to migrate from:

* ESXi, Hyper-V, and AWS EC2 to AHV
* ESXi on legacy infrastructure to ESXi on Nutanix
* AHV to AWS EC2

And VM migration is a four-step process, largely automated, and fairly simple to execute.

### What a Hybrid Cloud Engineer Needs To Do
So, as you can see, providers and technologies evolve their capabilities and business models to compete for your business: a hybrid cloud engineer surveys the market to see what their current and competing solutions offer to better improve business operations and requirements. Re-evaluating your current workloads for hybrid cloud deployment can be a difficult task. The best first step is often to reproduce what you currently have with automation to make it IaaS and evolve to PaaS if required. At that point, when you can synthesize a new workload from a blueprint with a few clicks, it becomes easier to reproduce.

## Quiz: Infrastructure Provider Strategies

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/466.jpg)

A company that you are consulting for is considering transitioning some services and applications to the cloud. They’ve narrowed down their selection to two providers: FancyCloud and EasyCloud.

FancyCloud boasts of having cutting edge technology, and is widely considered one of the most powerful, feature-rich public cloud solutions on the market. They attribute this to their proprietary hardware and software setup. They have a consulting team that will help you migrate your applications from your on-prem datacenter to their cloud, and have proprietary tools that will assist with migration and conversion of all VMs and associated resource dependencies to FancyCloud-specific formats.

EasyCloud, on the other hand, has interoperability and ease of use as two of its biggest selling points. While it isn’t necessarily as widely used as FancyCloud, it seems to have feature parity with FancyCloud. EasyCloud’s customer testimonials speak about how easy it is to get up and running, how simple it is to move workloads between on-prem and EasyCloud as needed, and how EasyCloud makes it simple to move workloads between other public clouds as well.

The company you are consulting for asks for your opinion. They want to choose the best cloud for a potentially long-term engagement, but they want to avoid vendor lock-in. Which cloud do you think would be the right choice for them — FancyCloud, or EasyCloud?

### QUESTION 2 OF 2
Read the scenario above and then determine which cloud would be the right choice for the company to use — FancyCloud, or EasyCloud?

* EasyCloud

## Pets vs Livestock for Scalability

If you take a moment to think back to the beginning of the previous course, you may remember that we spoke about DevOps. We spoke about how digital transformation has triggered an overhaul in the way organizations think about tried-and-true business models and operationalize day-to-day processes.

With the rise of digital transformation and supporting technologies like IoT, data processing, and visualization, the role of software development has become increasingly important. To quickly deliver new applications and services, IT teams are transitioning to DevOps models that close the gap between development and operations.

So even though we’ve been discussing software products and concepts, the underlying message — the perspective that we’ve been providing — is about transitioning to a DevOps mindset. And the traditional values and practices for creating stable, long-lasting infrastructure do not apply when progressing to a DevOps mindset.

IT infrastructure resources, both technological and human, have long been treated as unique and special--that is, treated like irreplaceable and extremely valuable “pets.” For example, most IT shops rely on servers that are bespoke (custom built) and maintained laboriously by hand. But these resources also constitute single points of failure that, when unavailable, can bring a mission-critical application, or even an entire organization, to its knees.

Conversely, DevOps requires that your material resources be distributed, fungible, and ephemeral. When one resource goes down, another takes its place without any disruption to the business. Technical resources like servers are more like members of a herd of livestock or a fleet — no single member is irreplaceable or more valuable than the others, and one is as good as another.

![](https://video.udacity-data.com/topher/2020/September/5f63eb0f_pets-vs-livestock-for-scalability/pets-vs-livestock-for-scalability.png)

In terms of staffing, DevOps also democratizes required skill sets, so that the company is not dangerously reliant on any single “heroic” resource. The overall system should be smart enough so that no single employee possesses such specialized knowledge that their absence would significantly interrupt the flow of work. DevOps also dictates that, whenever possible, businesses should automate menial, error-prone, and repeatable tasks, freeing staff to devote their time and energy towards work that brings real value to the business.

## Quiz: Pets vs Livestock for Scalability

You have been brought in to consult for a company called RandomOrg. For your first task, you have been added to a Digital Transformation Committee that’s helping RandomOrg modernize their IT infrastructure and improve their processes and overall efficiency.

You notice that RandomOrg has a series of custom-built servers in their datacenter, that have been maintained by an IT team consisting of more or less the same people for the last nine years.

While RandomOrg does back up their data, their backups are all on tape and other long-term storage/archival formats. They also run a number of mission-critical applications in their datacenter, but their failover site also consists of similar, custom servers which are managed and maintained by the same IT team.

Some amount of custom documentation is available for the hardware and software. However, since the IT team is so familiar with the system, they only have cursory information written down and manage their environment largely based on their experience.

All of their infrastructure management interfaces have custom-built, and most tasks require either manual input or manual intervention. This keeps the IT team largely focused on making sure the infrastructure is running smoothly, and generally keeping the lights on.

After a few days of exploring their environment and talking to the right people, you believe you have some general observations and concerns that you can share with RandomOrg, so they can start making changes.

### QUIZ QUESTION
Read the scenario above and select all of the things that RandomOrg is doing wrong in their environment and with their IT team, so that they can make changes.

Choose all that apply.

* Custom-built servers maintained by hand constitute single points of failure

* The IT environment requires too much specialized knowledge to maintain

* There are too many manual tasks, which increases the risk of errors and keeps staff too busy to add value to the business

* The IT team has so much specialized knowledge that the absence of one or more resources could potentially and significantly interrupt the flow of work

## Exercise: Dual Web Tier

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/467.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/468.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/469.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/470.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/471.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/472.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/473.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/474.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/475.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/476.jpg)

## Exercise Solution: Dual Web Tier

### Dual Web Tier Exercise Solution
These four videos walk through the same steps for the exercise that we provided in text on the previous page.

[![IMAGE ALT TEXT](https://github.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/blob/main/images/422.jpg)](https://www.youtube.com/watch?v=z_eyERlF184&feature=emb_logo)

[![IMAGE ALT TEXT](https://github.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/blob/main/images/422.jpg)](https://www.youtube.com/watch?v=fBvza4fWP00&feature=emb_logo)

[![IMAGE ALT TEXT](https://github.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/blob/main/images/422.jpg)](https://www.youtube.com/watch?v=k_BsVN3T-hM&feature=emb_logo)

[![IMAGE ALT TEXT](https://github.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/blob/main/images/422.jpg)](https://www.youtube.com/watch?v=XZkLASS10Io&feature=emb_logo)

## DevOps for Agility and Operational Maturity

Decades of habits and traditions can make it difficult to see alternative strategies for solving problems, especially when there’s significant risk involved. Until fairly recently, it’s been taken as a given that medium to large companies organized themselves into separate silos of functional expertise and responsibilities, with projects following a linear “waterfall” process.

But legacy approaches have proven not only slow, inefficient, and costly, they also lead to buggy, substandard products that disappoint customers (or worse) and wreak havoc on the production environment. These shortcomings have become even more glaring with the advent of virtualization, distributed systems, and cloud computing. The search for agility has prompted some to go “all-in” on public cloud, but for most workloads, this is an extremely expensive way of doing business (as borne out by monthly sticker shock) and can end up being another form of vendor lock-in.

A reasonable person might ask, why do companies need DevOps when IT and Operations are successfully delivering security and uptime, using administrative tools to maintain, backup, and restore those systems? The answer is that if Operations is ever going to become a force multiplier that helps the business drive innovation, instead of a cost center whose primary function is to keep the lights on, it must become agile. For this to happen, Operations must be documented, democratized, and distributed.

So, in the following sections, we’re going to describe and discuss three important considerations that you — as a hybrid cloud engineer — need to keep in mind when working with a business to help facilitate and ease the transition to cloud smart.

## Push Button Environments

This refers to changing your existing, brownfield workloads (which have a lot of hard-coded configuration, data, and state in them) to push-button simplicity for new workload instances.

How often does your software development and test team ask for a new environment and then wait around for days and weeks for IT to manually fulfill the requests? Nobody can afford to have developers wait to become productive anymore. With the advent of continuous integration, the demand for a new environment could happen with every developer check-in, multiple times per hour.

![](https://video.udacity-data.com/topher/2020/September/5f63eb4e_push-buttons-environments/push-buttons-environments.png)

## Configuration Management

![](https://video.udacity-data.com/topher/2020/September/5f63ebe4_configuration-management-set/configuration-management-set.png)

Configuration Management (CM) is a category of software that can be considered the next generation of scripting. It may also be beneficial to bootstrap from community contributions for web and database, potentially allowing you to change operating system versions, which may help with your workload portability. Many provisioning tools can orchestrate configuration management on each VM guest — client-only CM has been very popular for adopting this new ability. More advanced CM systems support client-server models with change management database (CMDB) features, secure orchestration of secrets, fleet management, and more.

Blueprints can easily bootstrap, configure, and run a configuration management client tool. In fact, you can mix and match your old procedures and new CM procedures, or even multiple CM systems, inside a blueprint. This flexibility is crucial for expressing your work using your current skill sets alongside new facilities, while also leaving open the option to refactor for future efficiencies. Also, given that different teams typically adopt different tools, your system should be able to accommodate this heterogeneity through orchestration — bringing all of the knowledge in your organization under one roof to deliver business with a single click.

Perhaps the most interesting benefit of CM is that after the initial provisioning and execution, periodic rerunning of CM on each VM can identify and (if desired) remediate configuration drift back to the desired state. This capacity constitutes one aspect of self-healing infrastructure and is an essential tool for establishing on-going security of your environments. (Some CM tooling can work in a client-only mode; we assume this capacity below for simplicity of adoption.)

CM communities offer official and community-supported workload automation, which can accelerate new workload adoption. After you are comfortable with the benefits of configuration management, CM support may become a new requirement or qualification for any new vendor, workload, or solution. CM can also expand to large client-server systems to manage large fleets of datacenters and VMs.

The configuration management option has begun to wane, however, with the onset of Docker containers and Kubernetes. These technologies have led application architecture towards immutable infrastructure artifacts, which are built and orchestrated with a minimum of runtime configuration — in contrast to entirely synthesized configuration during provisioning time. These more lightweight options optimize time, storage, and compute, so the next stage begins down that path.

## Quiz: Configuration Management

### QUIZ QUESTION
Which of the following statements are TRUE of configuration management?

* Periodic rerunning of configuration management on VMs can identify and remediate configuration drift back to the desired state

* Configuration management can expand to large client-server systems to manage large fleets of datacenters and VMs

* Configuration management systems support client-server models with change management database (CMDB) features, secure orchestration of secrets, fleet management, and more

## Enterprise, Hybrid, and Multi-Cloud Deployments

Expanding deployments to multiple providers is yet another refinement of the blueprint to ensure that one can deploy and blend workloads across on-prem and off-prem infrastructure offerings, achieving a hybrid cloud stance. Most importantly, the business must retain a consistent governance and operational model so that workloads can meet fiscal and customer performance service level objectives, no matter where the workload lands.

![](https://video.udacity-data.com/topher/2020/September/5f63ec1f_enterprise-hybrid-and-multi-cloud-deployments/enterprise-hybrid-and-multi-cloud-deployments.png)

You can clone and refactor a blueprint for parallel deployments to multiple hypervisors, public clouds, and datacenters. You can also schedule and orchestrate a mixture of VMs and containers into Kubernetes pods for hybrid deployments across multiple clouds, supporting teams at different stages of container maturity. This flexibility allows all of the infrastructure market to compete for your business service level agreements. Freedom of choice among vendors empowers you to not only select the best products and services, but the optimal fiscal and operational models.

## Advanced Automation Concepts

Now, we’re going to spend a little time on a few concepts that are extremely critical to your understanding of DevOps and your ability to architect an environment that follows agile, modern development principles.

![](https://video.udacity-data.com/topher/2020/September/5f63ec47_advanced-automation-concepts/advanced-automation-concepts.png)

We’re going to discuss:

* Immutable infrastructure and build artifacts
>> * Immutable infrastructure refers to a system that does not change after deployment. This means that no updates, patches, or configuration changes are made to production systems. -If changes are needed, a new version of the architecture is built and deployed into production.

* Continuous integration, delivery, and deployment
>> * These are terms that you may already be familiar with, but we’ll explore them in a little more detail.
>> * Continuous integration is a software engineering practice that involves multiple developers merging their individual code changes into the main repository as frequently as possible, usually multiple times a day.
>> * Continuous delivery is an extension of continuous integration and involves keeping code in a state in which it is ready to deploy at any given time.
>> * Continuous deployment is about the frequent, automated release of this code to production.

* Continuous operations
>> * Gartner defines continuous operations as “Those characteristics of a data-processing system that reduce or eliminate the need for planned downtime, such as scheduled maintenance. One element of 24-hour-a-day, seven-day-a-week operation.”
>> * To simplify this definition even further, continuous operations is about ensuring that IT operations are non-disruptive to users.

![](https://raw.githubusercontent.com/ARBUCHELI/HYBRID-CLOUD-ENGINEER-NANODEGREE-PROGRAM-/main/images/477.jpg)

## Immutable Infrastructure and Build Artifacts

Before we talk about immutable infrastructure, let’s take a moment to understand what traditional infrastructure management is like. This is something that happens every day, everywhere, perhaps even in your organization, but it isn’t always something we pay attention to.

With traditional infrastructure, updates to servers happen ‘in-place’. That is, after a server is deployed, someone connects to it, updates it, makes configuration changes and optimizations, and so on. These servers are mutable — that is, they change after they have been deployed.

![](https://video.udacity-data.com/topher/2020/September/5f63ec7b_immutable-infrastructure-and-build-artifacts-1/immutable-infrastructure-and-build-artifacts-1.png)

While this is a common practice, it results in a number of common problems. The first and most common is that because these configuration changes are so small, they are rarely documented. And second, they lead to configuration drift.

Configuration drift, if you’re unfamiliar with the term, refers to active configurations diverging from the configuration that was originally tested, approved, and deployed. Configuration drift is largely the result of manual processes, since these changes usually involve an actual person connecting to the server to make changes.

A significant portion of configuration drift is often largely the result of simply needing to get a job done. During an outage, for example, a one-time edit to a configuration file can save the day — but that edit never makes it into documentation. Cron jobs running critical functions that only a handful of people are familiar with make their way onto the server. Application code is deployed without using the normal, source control process.

![](https://video.udacity-data.com/topher/2020/September/5f63ec9c_immutable-infrastructure-and-build-artifacts-2/immutable-infrastructure-and-build-artifacts-2.png)

As these changes accumulate in infrastructure, your servers become finicky. Deployments can only be performed in certain, specific ways. Init scripts don’t work unless something very specific and unexpected is done.

And, over time, the system becomes a house of cards.

The solution to this problem is immutable infrastructure. Like the name suggests, with immutable infrastructure, the system simply does not change after deployment. This means that no updates, patches, or configuration changes are made to production systems. If changes are needed, a new version of the architecture is built and deployed into production.

### An Example of Mutable and Immutable Infrastructure
Let’s use web servers as an example here, since we touched on web server blueprints in a previous project. Consider an environment in which you have spun up a VM, deployed Apache as your web server, and have deployed your application as well. This is your v1 setup. Over time, you may want to upgrade Apache to a newer version, or perhaps change your web server from Apache to Nginx.

![](https://video.udacity-data.com/topher/2020/September/5f63ecd5_an-example-of-mutable-and-immutable-infrastructure-1/an-example-of-mutable-and-immutable-infrastructure-1.png)

In a mutable infrastructure environment, you would do this with a configuration management tool such as Chef or Ansible.

If everything works as expected and the upgrade proceeds smoothly, both your web server and web application will be deployed and running. But what if it doesn’t? Perhaps due to network issues, perhaps DNS is down at the time, perhaps repos aren’t responsive — whatever the reason, there are plenty of ways in which something could go wrong during an upgrade.

Perhaps during the process, the Nginx installation doesn’t go as planned but the web application deploys successfully. In this scenario, your environment doesn’t go from v1 (Apache + web app v1) to v2 (Nginx + web app v2). It shifts to some partial, problematic version in between the two (Apache + web app v2).

![](https://video.udacity-data.com/topher/2020/September/5f63ecf2_an-example-of-mutable-and-immutable-infrastructure-2/an-example-of-mutable-and-immutable-infrastructure-2.png)

While this isn’t a commonplace occurrence, it is a very, very important consideration at scale. When you’re upgrading one VM, one server, this may seem like a very small problem with a very low probability of occurring. But when you’re upgrading hundreds of VMs or servers? Thousands? Then the potential for problems increases exponentially. And this is where immutable infrastructure demonstrates its value.

With immutable infrastructure, in this same scenario, after Apache and the web application are deployed, a snapshot is taken (let’s call it version1) and that system is never touched again. When the time comes to upgrade, a new VM will be created, but with Nginx and a new version of the web application — let’s call this version2. The old one (i.e., version1) will be left intact.

![](https://video.udacity-data.com/topher/2020/September/5f63ed0f_an-example-of-mutable-and-immutable-infrastructure-3/an-example-of-mutable-and-immutable-infrastructure-3.png)

During deployment, if there’s an error with version2, the process of spinning up the VMs and deploying the application will simply start over with no impact to the production environment. If everything goes as planned, once version2 is up and running, traffic will be switched over and version1 will be decommissioned.

In this situation, despite the potential for errors, the production environment remains unaffected and there’s much lower risk overall.

## Quiz: Immutable Infrastructure and Build Artifacts

Consider the following scenario.

You’re running a web application on a traditional LAMP stack – Linux is the OS, on top of which Apache and MySQL are running. You want to upgrade both Linux and Apache, and want to follow immutable infrastructure principles to do it.

So, you consider your current Linux and Apache installation as v1 and take a snapshot of the current, working state of the system. Then, in preparation for v2, you set up, test, and debug your new system consisting of upgraded versions of both Linux and Apache. The v1 system continues to run at this time.

Once v2 is ready for launch, you perform the following tasks in the order they are listed below:

Decommission v1 of the system.
Deploy v2 of the system.
Route traffic to the v2 system.
Test to make sure that the v2 system is running as expected in production.

### QUIZ QUESTION
Read the scenario above. Based on the sequence of tasks described there, have you correctly followed the principles of immutable infrastructure?

* No

## Continuous Integration, Delivery, and Deployment Overview

Three terms that you’ll hear very often in the context of DevOps are continuous integration, continuous delivery, and continuous deployment. And while it’s often assumed that they’re similar or overlapping terms, the truth is that they’re distinct and it’s important to be aware of those distinctions.

They are concepts that have arisen as a result of the increasing complexity of applications, the teams that build these applications, and the development practices that are commonplace in the industry. And ultimately, these three concepts allow organizations to develop, test, and release software in a way that is fast, consistent, and automated.

### Continuous Integration
To understand continuous integration, think about how a shirt is sewn. Then imagine that you have two people working on the sleeves, one person creating the body, and a fourth person sewing the collar. If you only put these pieces together at the moment you have to deliver a shirt to your customer, you’re going to discover errors too late – things like mismatched sleeves, a too-large collar, an ill-fitting body, and so on.

![](https://video.udacity-data.com/topher/2020/September/5f63ed52_continuous-integration/continuous-integration.png)

On the other hand, if you check the pieces early and often to see how they fit together, when the time comes to deliver a shirt, you’re much more likely to deliver a quality product.

In the same way, continuous integration is a software engineering practice that involves multiple developers merging their individual code changes into the main repository as frequently as possible, usually multiple times a day. The overarching goal is to ensure that the main branch of the repository has the most recent version of the source code, so developers are always using the latest possible version.

This helps prevent scenarios in which code works independently on individual machines, but falls apart when combined. It also helps developers by providing immediate feedback on integration errors early and regularly during development, which allows for swift resolution as the code is still fresh in the developers’ minds. As these integration errors are corrected, testing tools report when code is working and accepted, forming a feedback loop that helps improve developer productivity.

### Continuous Delivery

Continuous delivery is an extension of continuous integration and is entirely about the state of the code. The goal is to keep code in a state in which it is ready to deploy at any given time. That means code has been tested and debugged, and can be deployed at a moment’s notice. Whether or not that code is actually deployed is a secondary concern — the key consideration is: “can it be deployed?”

![](https://video.udacity-data.com/topher/2020/September/5f63ed71_continuous-delivery/continuous-delivery.png)

Essentially this refers to a build cycle with short sprints, that allow bugs to be identified quickly and early — which in turn allows for faster bug fixes and a more stable code base.

Continuous delivery has the added advantage of benefiting business users. Because code is always production-ready, it can be released to users for rapid feedback. And this process can take either a few hours or a few days, which is a dramatic improvement from waterfall models of development in which users sometimes have to wait for months to see new features in a product.

### Continuous Deployment
And finally, continuous deployment is about the frequent, automated release of this code to production. Since code is always ready to deploy (from continuous delivery), release to production can happen as soon as the code is accepted into the system. Continuous deployment makes it possible to move hundreds of releases into production on a daily basis with no manual intervention.

![](https://video.udacity-data.com/topher/2020/September/5f63ed9a_continuous-deployment/continuous-deployment.png)

## Continuous Integration, Delivery, and Deployment Quiz

You have been brought onboard as a consultant to assist a medium-sized software company in making the transition to a proper DevOps mindset. Some internal training sessions have been conducted already, new processes have been put in place, and by the time you are required to assist them, their engineering team has run into some problems.

They are finding a dramatic increase in rejected code from their automated tests and are unable to determine the source of the problem. You conduct a series of meetings in an attempt to understand what the problem is.

You discover that the engineering team has roughly 100 members. Recently, while making the shift to DevOps, they’ve implemented continuous integration, delivery, and deployment processes. They also use two types of development sprints — one that takes one week for smaller, easier to implement features, and a second, two-week sprint for work that is slightly more time-consuming. Within a single team or sub-team, based on an individual’s assigned task, an engineer can be working on code for either one week or two weeks.

In adherence with Continuous Integration principles, all engineers check code out on Monday of a given week. Depending on whether they are part of a one-week sprint or a two-week sprint, they will check their code back in when finished. Some developers check their code in on Friday of that week. The rest check their code in on Friday two weeks later.

However, when integration tests are run, they are failing repeatedly. Engineers are having to repeatedly rework their code and are more frustrated now than they were before DevOps workflows were implemented.

### QUIZ QUESTION
Read the scenario above. Based on the situation described there, what do you think the company is doing wrong? Why are engineers having to repeatedly rework their code?

* Their implementation of a continuous integration workflow is incorrect

## Continuous Operations

Helpfully, there is a widely accepted, clear, succinct definition of what continuous operations is. Gartner defines continuous operations as “Those characteristics of a data-processing system that reduce or eliminate the need for planned downtime, such as scheduled maintenance. One element of 24-hour-a-day, seven-day-a-week operation.”

To simplify this definition even further, continuous operations is about ensuring that IT operations are non-disruptive to users. If we return to the web server example that we used to talk about immutable infrastructure, you’ll see that an aspect of continuous operations is already built into the workflow.

Users will stay on version1 of the application, which is live until version2 has been successfully deployed. Once version2 is deployed, traffic is switched over — which means users move seamlessly from the old version of the application to the new. And, because of this approach, users will simply not realize that the upgrade has taken place until they are enjoying new features and functionality.

![](https://video.udacity-data.com/topher/2020/September/5f63edcc_continuous-operations/continuous-operations.png)

A fairly high level of automation is required to ensure that the user experience is non-disruptive. It also requires an established continuous integration, delivery, and deployment workflow, simply because they are the foundation on which continuous operations is built.

And finally, it’s worth noting that setting up continuous operations in a DevOps pipeline can potentially be a costly endeavor. However, since it minimizes the downtime of core systems, the cost involved is more than recovered over the long term.



# Adaptation as a repository: Andrés R. Bucheli.









