Working Links for the Project:-
1.	Web Application hosted on Azure: Link(HOSTING)
2.	Github Repository: Link
3.	Project Documentation With Project Video: Link(DRIVE JISME SAB HO)
4.	Short video: VIDEO LINK
5.	Full detailed video: VIDEO BADA WALA LINK
6.	Documentation: document link
7.	PDF File With ScreenShoots and explanation about the project: Link
 <hr>  
Project Summary: 
  The project is an e-commerce platform designed as an online jewellery store, enabling users to browse, search, buy, pay, and update their profiles seamlessly. Leveraging various Azure and AI services, it provides a reliable, efficient, and user-friendly experience. Key features include an intuitive interface, comprehensive Azure integration with virtual machines for hosting, monitoring services for system performance, backup and restore services to protect data, file share services for collaboration, and log analytics for insights. AI services, such as an AI ChatBot, enhance customer support. The notification system ensures users receive emails and SMS alerts for operations and critical actions. Regular backups and quick restoration options ensure data safety, while continuous monitoring maintains system health. This integration of technology enhances operational efficiency, boosts customer satisfaction, and supports business growth.

Overview: 
  Our e-commerce platform seamlessly integrates various Azure components to deliver a reliable, efficient, and user-friendly experience. Azure VMs host our platform, providing scalable computing power to handle user traffic and workload fluctuations effectively. Azure monitoring services track system performance and user interactions in real-time, logging and monitoring operations for performance and security. These events trigger alerts via email or SMS to keep stakeholders informed. Azure's backup and restore services ensure the safety of our data with regular backups and quick restoration options. Azure file shares facilitate seamless collaboration among team members, while Azure Log Analytics offers valuable insights into system behaviour and user activity. An AI-powered chatbot enhances customer support, reducing the workload on human agents and improving overall efficiency and customer satisfaction. This integration ensures operational excellence, data security, and enhanced user engagement, with a monitoring and notification system providing timely alerts for critical actions, enabling proactive response and ensuring a smooth user experience.

Azure Services Used:
1.	Virtual Machine (VM) and Deployment in VM
      1.	Virtual Machine (VM):
      a.	Definition: A VM is an emulation of a computer system. It runs an operating system and applications just like a physical computer.
      b.	Role: In your project, VMs are used to host your AI services and other applications, providing a scalable and flexible environment.
      2.	Deployment in VM:
      a.	Definition: This involves installing and configuring software applications and services on a VM.
      b.	Role: Ensures that your AI service chatbot and other applications are up and running within the VM environment.

2.	AI Service Chatbot
      1.	Definition: An AI chatbot is a software application that uses artificial intelligence to conduct conversations with users through text or voice.
      2.	Role: Provides automated customer support, information retrieval, and user interaction in your project.

3.	Monitoring and Alert
      1.	Definition: Monitoring involves tracking the performance and health of your applications and infrastructure. Alerts are notifications triggered by specific conditions or thresholds.
      2.	Role: Ensures the reliability and performance of your AI services by notifying you of issues that require attention.

4.	Log Analytics Workspace
      1.	Definition: A Log Analytics Workspace is a centralized repository for collecting, analyzing, and querying log data from various sources.
      2.	Role: Helps in monitoring, troubleshooting, and gaining insights into the performance and health of your AI services and infrastructure.

5.	File Share
      1.	Definition: A file share is a network shared folder that can be accessed by multiple users and systems.
      2.	Role: Provides a common storage space for files that need to be accessed or shared across your AI services and VMs.

6.	Backup and Restore through Service Vaults of VM
     1.	Backup:
            a.	Definition: The process of creating copies of data to protect against data loss.
            b.	Role: Ensures data protection and disaster recovery for your VMs and their applications.
    2.	Restore:
            a.	Definition: The process of retrieving data from backups.
            b.	Role: Allows recovery of data in case of accidental deletion, corruption, or other data loss scenarios.
     3.	Service Vaults:
            a.	Definition: Specialized storage locations used for securely storing backup data.
            b.	Role: Provides a secure and reliable repository for backup data of your VMs.

7.	Storage Account Container
    1.	Definition: A container within a storage account is a grouping of blobs (binary large objects), which can store unstructured data like text or binary data.
    2.	Role: Organizes and manages the storage of data used by your AI services.

8.	Storage Account with Soft Delete, Change the Date of Soft Delete, and Versioning
       1.	Storage Account:
              a.	Definition: A storage account provides a unique namespace in Azure for your data objects.
              b.	Role: Houses all your Azure Storage data objects, including blobs, file shares, queues, and tables.
     2.	Soft Delete:
              a.	Definition: A feature that temporarily retains deleted data, allowing recovery within a specified retention period.
              b.	Role: Protects against accidental deletions by allowing you to restore deleted data.
       3.	Change the Date of Soft Delete:
              a.	Definition: Adjusting the retention period for softdeleted data.
              b.	Role: Gives you flexibility in managing how long deleted data is retained.
        4.	Versioning:
              a.	Definition: A feature that maintains previous versions of data objects, enabling recovery of earlier versions.
              b.	Role: Allows you to revert to previous states of your data in case of accidental changes or corruption.

Web Technologies Used:
  1.	HTML
  2.	PHP
  3.	JS
  4.	TAILWIND CSS

Resource Visualizer:

![RES](https://github.com/02vandup11/Azureproject/assets/138954560/444048a6-3171-43d5-9e53-9a4f33c25626)


Azure Resources Overview:
   1)	Virtual Machine and Deployment
   ![image](https://github.com/02vandup11/Azureproject/assets/138954560/0f0d1481-a8a7-4b7d-bbff-034b8fa2201c)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/bcee7a1d-caec-445f-afc8-286cbeb1212b)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/a61197b0-fd35-4787-85ce-d3c0f9c23e7b)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/3a006afa-106f-4d95-8398-0914c08e6263)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/de607b6c-610b-4ac4-9ae6-fe336e0c1716)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/2f2813fd-d0c7-45ea-b62b-bc7d692b72a3)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/6dcaec8b-4e30-4cde-84a3-26d0124b4b03)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/6dc22f8a-3988-4a04-ad39-cbfc75894879)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/0e34c5f9-ed63-4a08-8115-2eae78edcfaf)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/b0228a17-92a1-41a5-a010-b91aafc3b8cf)

   2)	AI Service Chatbot
![image](https://github.com/02vandup11/Azureproject/assets/138954560/c2cfda09-64d3-482e-8042-97c150905600)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/20216bc6-74d0-488d-9db2-d49a4396abc6)
  ![image](https://github.com/02vandup11/Azureproject/assets/138954560/34a93533-fc62-418a-a30d-6712bf26843a)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/67d4f25b-8686-4105-8424-9bc53a5a1deb)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/6fec991b-4d69-4df5-9169-14c74d8eff96)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/7657b039-b86a-4964-9ffd-b95255d97be3)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/fa58463d-e39e-42e0-8b17-3cdef27d1fac)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/69b2628d-ec4b-49b5-8efa-b15032e15a55)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/9eb7bffa-3132-45e0-9c1d-35c2c37b71ab)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/0bfc6664-bc82-4d2d-bb2d-958a0f674b43)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/f54eb293-c8d7-462e-90f4-9bcdbf03f095)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/d2b3c899-061b-40a9-9d91-0468e2c8a4f7)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/71bd666c-c134-4ced-8e2f-7c66a025489f)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/e0c36392-f3f8-4218-b015-12f88d62c0cd)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/dedd3fc6-4c6c-4dda-ab88-b7dce0e917a6)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/deee60d1-0669-4900-b8e5-c5c9c2e674ed)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/ddc6b826-fa16-4d68-95ac-6584929dc05a)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/364ba538-9865-4b09-8086-f2467c0756c3)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/91f8546c-fc7d-4897-82d7-d8fdc7459d6d)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/616dc4d1-dabd-4d58-b34f-502212dbc406)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/e1929322-dd0c-486a-8ebc-4c8b8bc6baaa)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/5b20c8f6-1ee5-4e4b-ac1f-795437196c53)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/207af198-8071-43a7-88e1-620e95dfef85)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/0d7589cb-7354-4fd1-9a87-8f6d9895f398)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/ce366d2e-6b5a-4569-aa66-ed614c71236a)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/e845398f-c81a-48fb-9aa8-163f80bacaf4)

   3)	Monitoring and Alert
![image](https://github.com/02vandup11/Azureproject/assets/138954560/3e9266a4-b799-48dc-825d-0c32bd8f0e9a)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/fe2606e3-7305-46e6-a021-177572d7d8ba)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/03c1543a-fa9d-4c54-abc4-14832d5b06fa)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/8c3d5700-6ff0-4ddd-8af4-66d0da8b6730)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/73e39929-20d2-42c4-b003-0db3e9964b95)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/be7eed2d-6d32-40e4-8e1e-273a0ff0a1ea)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/ff7247c6-5c2d-4fab-ae0d-4a3bfbf0cf17)

   4)	Log Analytics Workspace

![image](https://github.com/02vandup11/Azureproject/assets/138954560/9efd296a-180f-4404-8efe-dc110c2e5be8)

![image](https://github.com/02vandup11/Azureproject/assets/138954560/6d2e8561-84b2-41ad-b4f0-8a02a8e11b7b)









