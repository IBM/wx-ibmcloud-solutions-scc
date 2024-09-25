# View Scan Results

In this section, you will first view a scan that has already been ran on your environment. This scan will provide a report highlighting any resources that are not compliant with the enforced security and compliance policies, based on the IBM Cloud Framework for Financial Services and AI ICT Guardrails profiles. The goal is to identify which resource needs attention before moving on to resolving these issue.

1. Navigate to the Security and Compliance Center by selecting the **Navigation menu (A)**. Hover over **Security and Compliance Center (B)**, and select **Dashboard (C)**.

    ![alt text](../images/2.2.1.png)

2. Select **Attachments (A)**. 
    ADD SCREENSHOT

3. View your scan results. Select the **triple dot (A)** on the right-hand side of your attachment and select **View Scan Results (B)**.

    ![alt text](../images/2.2.6.png)

4. Click your scan to open the report **(A)**

    ![alt text](../images/2.2.7.png)

5. View the failed rules at the bottom on the Overview page and locate the Component ***Cloud Object Storage*** **(A)** <br>

    ![alt text](../images/2.2.8.png)

    You should see a rule that has failed with the Description: Check whether Cloud Object Storage can be accessed only through a private endpoint (Context-based restrictions or service) and allowed IPs **(A)**

    ![alt text](../images/2.2.8.a.png)


The reason this rule is failing is because the context-based restrictions rule is not configured with private endpoint-allowed IP addresses for Cloud Object Storage. We will now go through the steps on how to remediate this issue. 
