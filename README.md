# Platform Engineering for Architects

<a href="https://www.packtpub.com/en-us/product/platform-engineering-for-architects-9781836203599?utm_source=github&utm_medium=repository&utm_campaign=9781786461629"><img src="https://content.packt.com/_/image/xxlarge/B31164/cover_image_large.jpg" alt="" height="256px" align="right"></a>

This is the code repository for [Platform Engineering for Architects](https://www.packtpub.com/en-us/product/platform-engineering-for-architects-9781836203599?utm_source=github&utm_medium=repository&utm_campaign=9781786461629), published by Packt.

**Crafting modern platforms as a product**

## What is this book about?
This book is for engineering professionals who want to advance their cloud native platform adoption by transitioning to IDPs with a product-centric platform approach. It emphasizes integrating platform strategy with the organization’s goals.

This book covers the following exciting features:
* Make informed decisions based on your organization’s platform needs
* Identify missing platform capabilities and technical debt
* Develop a critical user journey through your platform capabilities
* Define the purpose, principles, and key performance indicators (KPIs) for your platform
* Utilize relevant data points for making data-driven product decisions
* Implement your own platform reference and target architectures

If you feel this book is for you, get your [copy](https://www.amazon.com/dp/1836203594) today!

<a href="https://www.packtpub.com/?utm_source=github&utm_medium=banner&utm_campaign=GitHubBanner"><img src="https://raw.githubusercontent.com/PacktPublishing/GitHub/master/GitHub.png" 
alt="https://www.packtpub.com/" border="5" /></a>

## Instructions and Navigations
All of the code is organized into folders. For example, Chapter02.

The code will look like the following:
```
apiVersion: apiextensions.k8s.io/v1beta1
kind: CustomResourceDefinition
metadata:
  name: crontabs.stable.example.com
spec:
  group: stable.example.com
  version: v1
  scope: Namespaced
  names:
    plural: crontabs
    singular: crontab
    kind: CronTab
    shortNames:
    - ct
```

**Following is what you need for this book:**
This book is for platform architects and solutions architects seeking to enhance their skills in designing and building a platform as a product. It also offers valuable insights for decision-makers, platform engineers, and DevOps professionals. While familiarity with cloud-native concepts, CI/CD, and Kubernetes is beneficial, the book builds on these topics to address self-service, cost management, and technical debt. It’s particularly suited to experts tackling the challenge of integrating diverse domains to create effective internal developer platforms with top-notch operational readiness.

With the following software and hardware list you can run all code files present in the book (Chapter 1-10).
### Software and Hardware List
 | Software required | 
 | ------------------------------------ | 
 | Kubernetes | 
 | Backstage | 
 | CI/CD solutions such as GitHub Actions | 
 | Keptn | 
 | Argo CD | 
 | Crossplane | 
 | Prometheus | 
 | OpenTelemetry | 
 | Harbor | 
 | OpenFeature | 
 | Renovate Bot | 


### Related products
* Modern DevOps Practices [[Packt]](https://www.packtpub.com/en-us/product/modern-devops-practices-9781805121824?utm_source=github&utm_medium=repository&utm_campaign=) [[Amazon]](https://www.amazon.com/dp/1800562381)

* Embracing DevOps Release Management [[Packt]](https://www.packtpub.com/en-us/product/embracing-devops-release-management-9781835461853?utm_source=github&utm_medium=repository&utm_campaign=) [[Amazon]](https://www.amazon.com/dp/1835461859)

## Get to Know the Authors
**Max Körbächer**
is a technology advisor and platform architect who focuses on utilizing cloud-native technologies and open source to simplify the challenges of complex systems. He is the founder and managing director of Liquid Reply, a cloud-native engineering and consulting company. His work history includes roles as an enterprise architect in the media and power utility industry and as a demand manager planning medium and large IT projects. Max is also the founder and, currently, co-chair of the CNCF Environmental Sustainability Technical Advisory Group, CNCF Ambassador, Linux Foundation Europe Advisory Board member, and initiator and organizer of the Kubernetes Community Days Munich and Ukraine.

**Andreas Grabner**
is a technical advocate for making distributed systems observable and making automated data-driven decisions across the software development lifecycle. In his capacity as a CNCF ambassador and a DevRel at Dynatrace, he connects and educates global software engineering communities on building and continuously validating digital services for resiliency, high availability, and security.
Since his early days, he has been passionate about software quality and performance engineering as it results in building excellent digital products. Andi uses his advocacy platforms to share best practices on topics such as observability, progressive delivery, DevOps, site reliability engineering, platform engineering, and digital business operations!

**Hilliary Lipsig**
is an autodidact and start-up veteran who has frequently learned and applied technologies to get a job done. She’s had her hand in every part of the application delivery process, honing her skills originally as a quality engineer. Hilliary is an IT polyglot, able to talk the lingo of both the Operations and Development teams. She’s currently a Principal Site Reliability Engineer at Red Hat Inc., working on Kubernetes-based platforms. She’s passionate about GitOps, continuous integration, scalable processes, consistency in tooling, and good developer documentation. Her open source activities include contributions to the CNCF Glossary and she’s a member of the Code of Conduct Committee for Kubernetes.
