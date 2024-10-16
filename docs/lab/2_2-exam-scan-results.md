# View Scan Results

In this section, you will first view a scan that has already been ran on your environment. This scan will provide a report highlighting any resources that are not compliant with the enforced security and compliance policies, based on the IBM Cloud Framework for Financial Services and AI ICT Guardrails profiles. The goal is to identify which resource needs attention before moving on to resolving these issue.

---

1. Expand the **Navigation menu (A)** and then hover over **Security (B)** and select **Resources (C).**

    ![alt text](../images/2.2.1-new.png)

2. Select the resource **rag-lab-##-base-security-services-scc (A)** (where ## is replaced with your group number). <br>
For example: rag-lab-00-base-security-services-scc

    ![alt text](../images/2.2.2-new.png)

3. Select **Dashboard (A)**

    ![alt text](../images/2.2.3-new.png)

4. Make sure you are on the SCC instance that matches your group number **(A)**. Select **Attachments (B)**
    ![alt text](../images/2.2.4-new.png)

5. View your scan results. Select the **triple dot (A)** on the right-hand side of your attachment and select **View Scan Results (B)**.

    ![alt text](../images/2.2.5-new.png)

6. Click your scan to open the report **(A)**

    ![alt text](../images/2.2.6-new.png)

7. In the list of noncompliant resources, find the project that matches your group number. <br>
For example **rag-lab-00-RAG-sample-project (A)**. <br>

    ![alt text](../images/2.2.7-new.png)

   Expand the resource **(A)** You should see a rule this rule: Check whether Cloud Object Storage can be accessed only through a private endpoint (Context-based restrictions or service) and allowed IPs **(B)**

    ![alt text](../images/2.2.7-rule-new.png)

The reason this rule is failing is because the context-based restrictions rule is not configured with private endpoint-allowed IP addresses for Cloud Object Storage. We will now go through the steps on how to remediate this issue. 
