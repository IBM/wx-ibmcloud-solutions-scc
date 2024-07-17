# Toolchains

At the Generative application layer, we need to make sure that we follow DevSecOps best practices to develop, test and deploy the Gen AI application on a secure infrastructure.

The Deployable Architecture Stack for the RAG Application includes DevSecOps for Application which is supported through IBM Cloud Toolchain Service the CI/CD/CC pipelines were used to deploy the application on Code Engine Services checking for vulnerabilities and ensuring auditability.

The (CI) pipeline is used to develop the application, using DevSecOps best practices including evidence collection, artifact signing, and vulnerability checks.

The (CD) pipeline supports continuous deployment of the application, including evidence collection, GitOps flow, change management, and compliance scans. Once deployed on Code Engine, we can launch the application and make it available for end users.

1. Expand the **Navigation menu (A)** and select **DevOps (B) > Toolchains (C)**
![alt text](../images/2.5.1.png)

2. Make sure you on the right **Resource Group (A)** and correct **Location (B).** Select the **CI toolchain (C)**
![alt text](../images/2.5.2.png)

3. Select the **CI delivery pipeline (A)**
![alt text](../images/2.5.3.png)

4. Select the **webhook-trigger (A)**
![alt text](../images/2.5.4.png)

5. Select the most recent successful pipeline run
![alt text](../images/2.5.5.png)

6. Review the steps of the CI pipeline. 
![alt text](../images/2.5.6.png)