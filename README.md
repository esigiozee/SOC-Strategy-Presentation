# SOC-Strategy-Presentation


 


Eseosa Igiozee \
Springboard \
Cybersecurity \
 \
December 20, 2023



**Mini Project 27: SOC Strategy Presentation**

Global energy services firm has 600 sites across over sixty countries, and employees over 24,000 people. The IT environment that is currently used is mostly Windows-based and uses Active Directory for authentication, but has some systems running	Red Hat Enterprise Linux and Solaris. As you can see the company has grown quickly over the last few years, mainly as a result of mergers and acquisitions and because of this, it has become increasingly difficult to manage its security operations. Management wants to address this situation as quickly as possible and they need to know what their options are. 

So there are 3 strategies or options to choose from. The first is to create an in-house SOC (Security operations center) using FOSS (Free and Open Source Software) solutions. The second strategy is to create an in-house SOC using commercial solutions. Lastly, is to outsource the SOC to a third party MDR (Managed Detection and Response) or SOCaaS (Security operations center as a Service). Also assuming that no members of the IT Security team will need to be terminated if this option is selected since the vendor would be an extension of the existing team.

Each of these options has its own benefits and drawbacks.For each option I will be outlining its advantages, disadvantages and estimated costs. I will also outline any challenges associated with monitoring multiple operating systems across multiple global locations.

Before we dive into the three strategies, let us take a look at what an SOC is and what it can do for organizations. A SOC or Security operations center sometimes called an information security operations center or ISOC is an in-house or outsourced team of IT security professionals that monitor an organization's entire IT infrastructure, 24/7, to detect cybersecurity events in real time and address them as quickly and effectively as possible. A SOC plays a crucial role within an organization by serving as basically the central unit that deals with security issues. A SOC has a wide range of functions and responsibilities. Just to name a few, an SOC can continuously monitor and analyze the network traffic, endpoints, servers, databases, applications, and other systems within the organization to detect, prevent, and respond to cyber threats and incidents. SOC uses a variety of tools to identify potential security threats. It can also do vulnerability management and risk assessments and do security awareness and training for the organization’s staff.

The first strategy that I will compare is creating an in-house SOC using FOSS solutions. Just like the other two options, creating an in-house SOC using FOSS solutions has its own set of advantages and disadvantages. The first advantage is the cost effectiveness. FOSS solutions normally have no licensing fees and very few up-front costs making them a cost-effective choice, especially for organizations with tight budgets. Another is that open source tools can be beneficial for organizations that have infrastructure developers who either have knowledge in security or do not mind learning about it. FOSS allows companies to have more control and customization over the systems to allow companies to modify the source code to suit their specific needs. This also can help enhance the company's in-house team’s expertise in security and infrastructure development. 

Now of course we have to list out the disadvantages of using FOSS. The first is that setting up and maintaining an in-house SOC with FOSS can be resource intensive. It requires significant manpower and expertise and the time it takes to move to an FOSS technology can be quite lengthy. In 2014, Etsy moved its security log collection and analysis from Splunk to ELK stack. The entire process took a year to do. There will also be a heavy reliance on the employees. This can be risky as talented people in this field might be hard to come by and you have to take into account if people within the company with that expertise leave.

The next option is creating an in-house SOC using commercial solutions. This of course offers a different but a few similar set of advantages and disadvantages compared to using FOSS solutions. The first being the ease of use and support. Commercial products offer more user-friendly interfaces compared to using an open-sourced software for SOC. It also comes with more comprehensive documentation, making it easier to set up and manage especially if your staff isn't as knowledgeable with security. Many commercial SOC solutions offer integrated tool sets which can reduce the need for complex custom integrations that could potentially take a very long time to do. This will ensure seamless operation between different security functions. Commercial tools regularly update their products to counter new threats. They also include features made to help organizations comply with various regulatory standards.

For the disadvantages of using commercial solutions tools. The first is that it might not be as cost-effective as using FOSS. Commercial tools can be expensive, adding up the costs of licensing fees, support contracts, and potential costs for additional modules or upgrades. The next is the customization compared to using FOSS will be limited. Commercial solutions offer many features but as far as customization, that will often be limited which could be a potential drawback for companies that have specific or unique needs. Since it comes with a lot of features, that also could mean that there are some features that will not be used or relevant to the company, potentially leading to paying for unused abilities. 

The final option is to outsource the SOC to a third party MDR or SOCaas (Security Operations Center as a Service). An MDR is a Managed Detection and Response which is primarily focused on detecting and responding to cybersecurity threats. An SOCaas is a security operations center as a service that provides organizations with an outsourced solution for managing their security operations. These are two models of outsourced cybersecurity services that companies can use to enhance their security posture.

Let's start off with the advantages of outsourcing the SOC to a third party MDR or SOCaaS. The first advantage is the 24/7 monitoring and response. Your organization will get continuous monitoring and rapid response capabilities, which might be challenging for some organizations to achieve using in-house SOC because of for example, once the company’s employees are done working for the day they won't be able to monitor their systems anymore so having an outsourced SOC would be beneficial in that situation. The next advantage is that your third party SOC will already have experienced personnel available immediately, which will save the company time and money by not having to hire and train the dedicated people needed. The next advantage is the third party SOC will already have the infrastructure and tools required which also saves more time and the upfront expense of building your own in-house SOC.

There are of course a few disadvantages to using a third party SOC. The first is the analysis of alerts. Third party SOCs do not usually provide features such as multi-tier analysis of alerts or an incident response service. They may only provide the equivalent of a level 1 cybersecurity operations analysis. The next disadvantage is the amount of potential false-positives. Since the third party SOC is not within the organization like an in-house SOC would be, they might not know the employees who work in that organization which can trigger the SOC to send out a lot of false positives of every employee's action. There is also a concern about data privacy and security because sensitive information is being handled by a third party company.

Establishing an effective SOC is crucial for organizations that are trying to enhance their cybersecurity posture. Each option has its own unique set of advantages and disadvantages but ultimately the choice depends on an organization's specific requirements, needs, and resources.



**References**


    Chkadmin. (2022, September 19). _MDR security - what is managed detection and response?_. Check Point Software. https://www.checkpoint.com/cyber-hub/threat-prevention/what-is-managed-detection-and-response-mdr/#:~:text=Managed%20detection%20and%20response%20is,them%20on%20an%20organization’s%20network.


    Chris Brook                        on Wednesday December 28, Chris Brook                                      Chris Brook is the editor of Digital Guardian’s Data Insider blog. He is a cybersecurity writer with nearly 15 years of experience reporting and writing about information security, Brook, C., Chris Brook is the editor of Digital Guardian’s Data Insider blog. He is a cybersecurity writer with nearly 15 years of experience reporting and writing about information security, Bradley, B., & Roberts, P. (n.d.). _How to build a Security Operations Center (SOC): Peoples, Processes, and technologies_. Digital Guardian. https://www.digitalguardian.com/blog/how-build-security-operations-center-soc-peoples-processes-and-technologies


    Lemos, R. (2021, June 19). _Is an open-source SOC right for your organization?_. TechBeacon. https://techbeacon.com/security/open-source-soc-right-your-organization


    Sullivan, P. (2020, December 8). _Pros and cons of an outsourced SOC vs. in-house soc: TechTarget_. Security. https://www.techtarget.com/searchsecurity/tip/In-house-vs-outsourced-cybersecurity-operations-center-capabilities


    _What is Security Operations Center (SOC)?_. IBM. (n.d.). https://www.ibm.com/topics/security-operations-center 

