# Create Attachment and Run Scan

WRITE INTRODUCTION 

1. Navigate to the Secuirty and Compliance Center Dashboard (A)

2. Make sure you are on the instance that corresponds to your group number

3. Navigate to **Attachments (A)** and click **Create (B)**

    ![alt text](../images/2.2.3.png)

4. Configure your attachment <br>

    a. Give your attachment a name (A), click next (B)

    ![alt text](../images/2.2.4.a.png)

    b. Select the AI ICT Guardrails 2.0 (A), click next (B)

    ![alt text](../images/2.2.4.b.png)

    c. Select your resource group for the scope (A), click next (B)

    ![alt text](../images/2.2.4-c.png)

    d. Schedule: none (A), click next (B)

    ![alt text](../images/2.2.4.d.png)

    e. Review and click Create (A)

    ![alt text](../images/2.2.4.e.png)

5. Select the triple dot (A) on the right-hand side of your newly created attachment and select Run Scan (B). The scan will take about 5 minutes to run
    
    ![alt text](../images/2.2.5.png)

6. When your scan is complete, select the triple dot (A) on the right-hand side of your attachment and select View Scan Results (B)

    ![alt text](../images/2.2.6.png)

7. Click your scan to open the report (A)

    ![alt text](../images/2.2.7.png)

8. View the failed rules at the bottom on the Overview page and locate the Component “Cloud Object Storage” (A) <br>

    ![alt text](../images/2.2.8.png)

    You should see a rule that has failed with the Description: Check whether Cloud Object Storage can be accessed only through a private endpoint (Context-based restrictions or service) and allowed IPs (A)

    ![alt text](../images/2.2.8.a.png)


EXPLAIN WHAT THE FAILED RULE IS AND HOW IT WILL BE FIXED