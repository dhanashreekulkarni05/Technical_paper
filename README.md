---
# APACHE SNOWFLAKE

---

## Abstract
We live in the era of distributed computing where public cloud platforms offer unlimited compute and storage resources virtually. On the other hand, the software-as-a-service (SaaS) model introduces an enterprise-class system to its users. Which eradicated the user problem of expensive and complexity of usage. Whereas the traditional data warehousing systems are incapable of coping with this new environment as they are incapable of leveraging the cloud's elasticity. Hence, there is a need for enterprise-ready data warehousing solutions for the cloud. resulting in emerging of the new concept of "Snowflake" also called as snowflake elastic data warehouse. Snowflake is a highly scalable, transactional, multi-tenant, secure, and Elastic system with full SQL support and built-in extensions for semi-structured and schema-less data. It is structured as a pay-as-you-go service in the Amazon clouds.

## Introduction
#### What is snowflake?
Snowflake is the first-ever analytics database which is built with the cloud and delivered as a **"data warehouse as a service"**. It is mainly built for running on popular public providers like AWS, Azure and Google Cloud platforms, it cannot run on private that forms. There is no need to install configure and manage any kind of hardware or software to run it. It entirely runs on public cloud infrastructure. It is mainly used for data warehousing, data engineering, data lakes, data science and developing data applications. But, what makes it stand out of the crowd is snowflake's architecture and data sharing capabilities.
History: Snowflake implementation began in late 2012 but, it is deployed generally in the june month of 2015. It was implemented by three data warehousing experts: Benoit Dageville, Thierry Cruanes and Marcin Żukowski.

#### why snowflake?
Snowflake enables data storage processing and analytics solutions that are faster, easier to use, and far more flexible than any traditional offerings. The snowflake data platform is not built on any existing database Technology or big data platforms like Hadoop. The main benefits of using snowflake over the other existing data warehouses are as follows:

* **storage capacity**: Snowflake has a high storage capacity which makes it ideal to use by businesses that handle a large amount of data.


* **server capacity**: In Legacy data warehouses the server and other hardware expenses were significantly high but, when it comes to the snowflake it offers a much greater capacity without the need of updating the equipments hence, reducing the cost of upgrading.


* **multi-cloud**: The most preferred clouds to work in many organizations are Microsoft Azure Google Cloud and Amazon Web Services (AWS). With these three hosting options, integration with snowflake provides a great data warehouse solution for companies across many industries.


* **security**: In many organizations maintaining confidentiality is the biggest task. An organization's sensitive data needs to be adequately protected. Hence, snowflake offers a very high quality of data security with AES 256 encryption, along with the fact that it encrypts both data in transit and at rest.


* **disaster recovery**: Some organizations worry about not having physical server access to where that data gets stored in the event of a failure. Snowflake databases have contingencies for disaster recovery and ensure that multiple data centers replicate and provide easy access to your data if disaster recovery is needed.

---
### Key differentiator of Snowflake :

---

1) **Relational**: Snowflake has comprehensive support for ANSI SQL and ACID transactions. Most users are able to migrate existing workloads with little to no changes.


2) **Semi-Structured**: Snowflake offers many built-in functions and SQL extensions for flattening, traversing, and nesting semi-structured data. It supports the popular formats such as JSON and Avro.


3) **Elastic**: Storage and compute resources can be scaled independently and seamlessly, without impact on data availability or performance of concurrent queries.


4) **Highly Available**: Snowflake tolerates node, cluster, and even full data center failures. There is no downtime during software or hardware upgrades.


5) **Durable**: Snowflake is designed for extreme durability with extra safeguards against accidental data loss: cloning, undrop, and cross-region backups.


6) **Cost-efficient**: Snowflake is highly compute-efficient and all table data is compressed. Users pay only for what storage and compute resources they actually use.
---
## Snowflake Architecture 

---
Snowflake's unique architecture consists of three key layers. They are:
1) **Database Storage Layer**
2) **Query processing/Virtual Warehouse Layer**
3) **Cloud service Layer**

---
![Snowflake Architecture](https://centricconsulting.com/wp-content/uploads/2021/11/Graphics_SnowflakeArchitectureBlog_11.11.21.png)

---
As we can see in this picture the bottom layer is called the database storage layer where a large amount of data is being stored. And above it, we have a query processing layer where we create virtual warehouses to process the queries to the bottom layer. And in the top, we have the Cloud Service layer where we run the query that is processed in the previous layer. Snowflake's architecture is a hybrid of traditional shared-disk database architecture and shared-nothing database architecture. Hence, it has the features of both database architectures. Similar to shared-disk architecture, snowflake uses a central repository for persistent data that is accessible from all compute nodes in the data warehouses. In other words, it stores data in the database storage layer similar to shared-disk architecture but similar to shared-nothing architectures snowflake process queries using MPP compute clusters where each node in the cluster stores a portion of the entire dataset locally. This approach offers the data management simplicity of a shared-disk architecture but with the performance and scalability benefits of the shared-nothing architectures.

---
### Feature Highlights

---
1) **Pure Software-as-a-Service (SaaS) Experience**: With this enabled users need not buy any kind of Machines or devices, hire database administrators or install any software. Users either already have their data in the cloud or they need to upload it to the cloud. Then they can immediately manipulate and query data using snowflake's graphical interface or standardized interface such as ODBC, JDBC and Python PEP-0249 etc.


2) **Continuous Availability**: Continuous availability is an approach to computer system and application design that protects users against downtime, whatever the cause and ensures that users remain connected to their documents, data files and business applications. When we go back in the time data warehousing solutions were completely well-hidden backend systems, isolated from the outer world. In such environments, downtimes both planed and unplanrd usually did not have a large impact on any operations. But as data
   analysis became critical to more and more business tasks,
   continuous availability became an important requirement
   for any data warehouse. This lead to usage of applications with no down-time. This problem is completely solved using snowflake which meets all these expectations by it's features called **Fault resilience** and **Online upgrades**.

- Some of the important concepts including Schema-Less Data and Time Travel and Cloning are also an important features of snowflake.

---

## Conclusion
Snowflake Data Warehouse is a secure, scalable, and popular cloud data warehousing solution. It has achieved this status by constantly re-engineering and catering to a wide variety of industrial use cases that helped win over so many clients.

---
## Bibliography / Reference
* [DWgeek.com](https://dwgeek.com/unique-features-of-snowflake-date-warehouse.html/)
* [Snowflake concepts and Fundamentals Udemy course](https://www.udemy.com/course/snowflake-fundamentals-theory/?LSNPUBID=PPe1bPYHvDA&ranEAID=PPe1bPYHvDA&ranMID=39197&ranSiteID=PPe1bPYHvDA-RJKgBLHhYaNaj3C4Abw.XQ&utm_medium=udemyads&utm_source=aff-campaign)
* [Snowflake officila site](https://resources.snowflake.com/)
* [Snowflake Architecture (Youtube video)](https://www.youtube.com/watch?v=Vah_yweweso&t=348s)
---
