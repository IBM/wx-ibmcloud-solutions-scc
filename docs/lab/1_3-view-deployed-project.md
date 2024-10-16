# View Deployed Project

---

In this section we will be viewing the already deployed stack. We will take a closer look at a couple different layers of the stack to gain a better understanding of what is being created at that layer of the DA. 

---

1. Expand the **Navigation menu (A)** on the upper right-hand corner. Select **Projects (B)**
![alt text](../images/1.3.1-n.png)

2. Select the **deployed project (A)** that matches your group number (rag-stack-lab-##, where ## is replaced with your group number). <br>
For example: rag-stack-lab-00
![alt text](../images/1.3.2-n.png)

3. Switch to the **Configurations tab (A)**
![alt text](../images/1.3.3-n.png)

4. In the Projects view, inside your rag-stack-lab-## that corresponds to your group number **(A)**. <br> 
For example: rag-lab-00

    Click the **arrow (B)** to expand the list of components. You are able to expand the colum size so you are able to see the full name of the components. Find the **Essential Security - Security Compliance Center** and select **Deployed details (C)**.  
    ![alt text](../images/1.3.4-a-n.png)

    b. Select the arrow **(A)** to expand the Validation successful section. Click the green number that indicates the number of resources created to view the resources **(B)**. 
    ![alt text](../images/1.3.4-b-n.png)

    c. Here is a list of created resources by that specific section of the DA. 
    ![alt text](../images/1.3.4-c-n.png)

    The following two items are created in the **Essential Security - Security Compliance Center** section of the DA:

    - **COS Instance (ibm_resource_instance.cos_instance):** An IBM Cloud Object Storage (COS) instance provides scalable and secure storage for data in the cloud.
  
    - **COS Bucket (ibm_cos_bucket.cos_bucket):** A COS bucket is a logical container within a COS instance where data is stored.

    Repeat the same steps for the **Workload - Sample RAG App Configurations** section of the DA. Use the breadcrumbs at the top left to navigate back to the project. 

5. Now let's look at the list of resources that have been created by the DA. <br>
    
    Expand the **Navigation menu (A)** on the upper right-hand corner. Select **Resource list (B)** from the Navigation menu. <br>
![alt text](<../images/1.3.5-a-n.png>)

    Filter for your resource group (for example: rag-lab-00-service-rg) and **rag-common-services** under **Group (A)** to view all resources deployed by the DA.  <br>
    
![alt text](../images/1.3.5-n-b.png)
