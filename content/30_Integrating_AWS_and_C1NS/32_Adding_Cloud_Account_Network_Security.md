---
title: "Adding Cloud Account"
chapter: false
weight: 32
pre: "<b>4.2 </b>"
---

### Integrating AWS with Cloud One Network Security.

{{% notice info %}}
<p style='text-align: left;'>
A Cloud One Account is required to proceed. If you have not registered for a Cloud One account please go <a href="https://www.trendmicro.com/en_us/business/campaigns/cloud-one-trial.html?utm_campaign=RGEV2022_Cloud-One_SMKT&utm_medium=Webinar&utm_source=Immersion-Day_Network_PR&utm_content=Cloud-One-Trial" target="_top">here.</a>
</p>
{{% /notice %}}

----

#### 1. Log in [Cloud One](https://cloudone.trendmicro.com/)
- Select the **Integrations** tile. 

![C1NS2](/images/ns/intergration1.jpg) 

---

#### 2. Manage your Cloud One Account.
- Click on **Cloud Accounts**.
- Select the **AWS** tab.
- Click on **+New**.

![C1NS2](/images/ns/intergration2.jpg) 

---

#### 3. Intergrate Cloud One with AWS using the common connector CloudFormation template.
- Step1: Select the ```us-east-1``` region.
- Step2: Expand **view configuration**.
- Disable Cloud Sentry.
- Enable Network Security with hosted infrastructure.i
- Click on **Launch Stack**.

![C1NS2](/images/ns/integration3.jpg) 

---

#### 4. Clicking Launch Stack will navigate you to AWS CloudFormation.
- Do NOT edit any of the stack parameters.
- Check the box to acknowledge resources.
- Click on **Create Stack**

![C1NS2](/images/ns/integration4.jpg)
![C1NS2](/images/ns/integration5.jpg)

---

#### 5. Once the Stack has completed successfully.
- Select the tab **Outputs** 
- Copy the **ARN value** for the CloudOneRoleArn key.

![C1NS2](/images/ns/integration6.jpg) 

---

#### 6. Navigate back to Cloud One - Network Security.
- Paste in the ARN value copied from the CloudFormation Outputs.
- Optional: Name the account and provide a description.
- Click on **Connect**

![C1NS2](/images/ns/integration7.jpg)


---

#### 7. Confirm the account has been created successfully.

![C1NS2](/images/ns/integration8.jpg)
![C1NS2](/images/ns/integration10.jpg)



---
#### Congrats!! You have successfully integrated your AWS Account with Cloud One - Network Security :cloud: :laptop: :rocket:
