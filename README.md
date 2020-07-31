# Azure Sentinel
In the world of technology, cybersecurity is the #1 priority for any company. And with the almost infinite amount of threats any company can face, protection for your company seems almost impossible to do. In addition to that, there are many companies that only sell partial cybersecurity solutions but it gets cumbersome to make sure which version of software is compatible with other types of programs. Companies would be at ease if solutions were in one service. Microsoft heard that call and answered definitively with Azure Sentinel.

Azure Sentinel is both a SIEM (Security Information and Event Management) and a SOAR (Security Orchestration, Automation, and Response) solution that Microsoft created in 2019. Azure Sentinel delivers security and provides a single solution for alert detection, threat visibility, proactive hunting, and threat response.

Another advantage Azure Sentinel has is that there is a [Github repository](https://github.com/Azure/Azure-Sentinel) where you can see created custom workbooks, hunting queries, notebooks, and playbooks for Azure Sentinel.

## Data Connectors
With Azure Sentinel, you can connect all your data sources with data connectors. Sentinel comes with multiple built-in connectors for Microsoft solutions. This includes Microsoft Threat Protection solutions and Microsoft 365 sources. In addition there are built in data connectors to the broader security ecosystem for non-Microsoft solutions. Data connectors are made to connect to software and be able to ingest information from the software. 

## Workbooks
After you get your software connected, built in workbooks provides integrated visual data from those data connectors to help companies to deep dive into events generated into those services. For example, a company can  connect Azure Sentinel with their Azure Active Directory account to receive  information about sign-ins and audit logs over time. These Workbooks  also are able to visualize the data  into a graph format. For example, the picture below is a graph of Azure Activity in EITR's subscription.

![](images/graph.PNG)

From here you can examine data visually to ascertain problems, which benefits companies in detecting present security attacks. 
![](images/workbooks.PNG)

## Analytics
Analytics in Azure are rules that can help minimize the amount of threats that have to be reviewed and investigated. Analytics ranks the alert's severity from high to medium to low to informational. Azure Sentinel will automatically rank the rules from most severe to the least severe. Below is an example of what Analytics can look like in any company's workspace.

![](images/analytics.PNG)

## Incidents
Incidents are a group of related alerts that are created to investigate an solve any actionable threat. Like Analytics, incidents are also ranked by severity.

![](images/incidents.PNG)

## Automation
It should be noted that there are numerous tasks that need to be completed to confirm Azure resources are secure. Realistically, these tasks takes significant amounts of time. Companies need not devote resources and time to solve trivial  security issues . Luckily, Azure Sentinel has tools that can automate tasks for companies.

### Logic Apps
Azure Logic Apps is a service that assists companies to schedule, automate, and orchestrate certain tasks, ensuring ease and reliability . For example, you can automate security alerts from Azure Security Center and  post a message in a Slack channel.

Below is an example on how it works if you were to build it with the built-in functions Azure has by default.

![](images/logicapp.PNG)

Also, there is a [GitHub repository that has custom Logic Apps](https://github.com/Azure/logicapps) that anyone can deploy.

## Hunting
Hunting in Sentinel uses search and query tools to proactively hunt for security threats across all data sources before an alert is triggered. After a threat is dealt with, you can make custom detection rules based on the query. Here is list of built-in queries Azure provides.

![](images/hunting.PNG)

## Threat Intelligence
Threat Intelligence has become a hot topic in the security community as of late. Threat Intelligence is available knowledge that can mitigate or prevent cyberattacks. Threat Intelligence assists  companies in understanding what attackers are doing to their systems and how their companies should respond to those attacks. This additional component of Azure Sentinel  enhances any company's ability to detect and prioritize known threats. Azure Sentinel does this by having dedicated Analytics, Workbooks, Hunting Queries, Notebooks, and Data Connectors for Threat Intelligence.

Unfortunately, Azure Sentinel fails to include automattic threat intelligence built-ins. However, it does provide some options for companies to acquire threat intelligence. Azure Sentinel gives companies the ability to import threat indicators that they use.

There are multiple ways of streaming threat indicators to Azure Sentinel. You can use one of the Threat Intelligence Platform products that is integrated with Azure; you can connect a TAXII server to Azure Sentinel via a Data Connector; or you can use direct integration with the Microsoft Graph Security Indicators API.

Threat Intelligence can be an essential part of any company's effort towards being secure. Threat Intelligence is not about just ingesting data and putting it on a screen, it is absorbing data and preventing possible cyber attacks before they happen.

## Conclusion
In conclusion, Azure Sentinel can play an instrumental role in ensuring company's security.  It will take some time to learn and understand, but in the long term, Azure Sentinel can be a useful security tool for any company.

What I did this summer was instrumental in my development to becoming a computer science professional. Before this internship I only studied basic concepts in cloud computing. But now I have hands-on experience working with cloud computing which will help me in my professional career as cloud computing becomes more of a common practice for every company. Another thing I learn is not being afraid to fail. Asking questions and trying is essential to be a good worker in any profession.

This summer I had learned about Microsoft Azure and it has made a better computer scientist. The challenges of working with a cloud platform help made me improve with my problem solving and decision making skills. I am happy to know  that I will bring these skills I learned from EITR Technologies with me to my future endeavors.
