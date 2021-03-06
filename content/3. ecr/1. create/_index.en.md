---
title: "Create Repositories"
weight: 21
---

{{% notice note %}}
You will create two ECR repositories for cats and dogs docker image management. Amazon Elastic Container Registry (Amazon ECR) provides API operations to create, monitor, and delete image repositories and set permissions that control who can access them. Amazon ECR also integrates with the Docker CLI allowing you to push and pull images from your development environments to your repositories. 
{{% /notice %}}


1. Move to [Amazon ECR.](https://console.aws.amazon.com/ecr) If it is your first time to use ECR, you will see welcome page. Click **Get Started** or **Repositories** on the left navigation bar.
![MoveToECR](../../../static/images/ecr/ecr_3.png)
1. Create repository: name **cats**, **dogs** 
![CreateECR](../../../static/images/ecr/ecr_4.png)
1. Check if the two repositories created successfully. 
![CheckECR](../../../static/images/ecr/ecr_5.png)