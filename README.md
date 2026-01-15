<h1 align="center"><a href="https://github.com/shmkl">shmkl</a></h1>
![visitors](https://visitor-badge.laobi.icu/badge?page_id=shmkl.shmkl)
[![Website Badge](https://img.shields.io/badge/-website-white?style=flat&logo=google-chrome&)](https://itsmkl.com/)
[![RSS Badge](https://img.shields.io/badge/RSS-FFA500?logo=rss&logoColor=fff&style=flat)](https://itsmkl.com/rss.xml)

```hcl
# shmkl.tf

locals {
  name  = "shmkl"
  role  = "Cloud Solutions Architect"
  cloud = ["AWS", "Azure", "GCP"]

  greeting = "Hello and welcome! Thanks for stopping by."
  now      = "Right now I'm designing secure, scalable cloud solutions and helping teams ship them reliably."
}

output "hello" {
  value = local.greeting
}

output "current_focus" {
  value = local.now
}
```

<details open>
  <summary><span style="font-size: 25px; font-weight: bold">🛠️ Tech</span></summary>

  <h3>👨‍💻 Programming / Markup Languages</h3>

  <p>
    <a href="https://github.com/search?q=user%3Ashmkl+language%3Abash"><img alt="Bash" src="https://img.shields.io/badge/Bash-121011.svg?logo=gnu-bash&logoColor=white"></a>
    <a href="https://github.com/search?q=user%3Ashmkl+language%3Ahtml"><img alt="HTML" src="https://img.shields.io/badge/HTML-E34F26.svg?logo=html5&logoColor=white"></a>
    <a href="https://github.com/search?q=user%3Ashmkl+language%3Acss"><img alt="CSS" src="https://img.shields.io/badge/CSS-1572B6.svg?logo=css3&logoColor=white"></a>
    <a href="https://github.com/search?q=user%3Ashmkl+language%3Ajavascript"><img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-F7DF1E.svg?logo=javascript&logoColor=black"></a>
    <a href="https://github.com/search?q=user%3Ashmkl+language%3Ajavascript"><img alt="Node.js" src="https://img.shields.io/badge/Node.js-43853D.svg?logo=node.js&logoColor=white"></a>
    <a href="https://github.com/search?q=user%3Ashmkl+language%3AtypeScript"><img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-007ACC.svg?logo=typescript&logoColor=white"></a>
    <a href="https://github.com/search?q=user%3Ashmkl+language%3Apython"><img alt="Python" src="https://img.shields.io/badge/Python-14354C.svg?logo=python&logoColor=white"></a>
    <a href="https://github.com/search?q=user%3Ashmkl+language%3Aswift"><img src="https://img.shields.io/badge/Swift-F05138?logo=swift&logoColor=fff&style=flat" alt="Swift Badge"></a>
    <a href="https://github.com/search?q=user%3Ashmkl+language%3Amarkdown"><img alt="Markdown" src="https://img.shields.io/badge/Markdown-000000.svg?logo=markdown&logoColor=white"></a>
    <img src="https://img.shields.io/badge/JSON-000?logo=json&logoColor=fff&style=flat" alt="JSON Badge">
    <img src="https://img.shields.io/badge/YAML-CB171E?logo=yaml&logoColor=fff&style=flat" alt="YAML Badge">
  </p>

  <h3>🧰 Frameworks / Libraries</h3>

  <p>
    <img src="https://img.shields.io/badge/jQuery-0769AD?logo=jquery&logoColor=fff&style=flat" alt="jQuery Badge">
    <img alt="Express.js" src="https://img.shields.io/badge/Express.js-404d59.svg?logo=express&logoColor=white">
    <img alt="React" src="https://img.shields.io/badge/React-20232a.svg?logo=react&logoColor=%2361DAFB">
    <img alt="Tailwind CSS" src="https://img.shields.io/badge/Tailwind%20CSS-06B6D4?logo=tailwindcss&logoColor=fff&style=flat">
    <img alt="Svelte" src="https://img.shields.io/badge/Svelte-FF3E00?logo=svelte&logoColor=fff&style=flat">
    <img src="https://img.shields.io/badge/Django-092E20?logo=django&logoColor=fff&style=flat" alt="Django Badge">
    <img src="https://img.shields.io/badge/.NET-512BD4?logo=dotnet&logoColor=fff&style=flat" alt=".NET Badge">
    <img alt="WPF (.Net)" src="https://img.shields.io/badge/WPF-5C2D91?logo=.net&logoColor=white">
    <img src="https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow&logoColor=fff&style=flat" alt="TensorFlow Badge">
    <img src="https://img.shields.io/badge/NGINX-009639?logo=nginx&logoColor=fff&style=flat" alt="NGINX Badge">
    <img src="https://img.shields.io/badge/Cypress-17202C?logo=cypress&logoColor=fff&style=flat" alt="Cypress Badge">
    <img src="https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes&logoColor=fff&style=flat" alt="Kubernetes Badge">
    <img src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=fff&style=flat" alt="Docker Badge">
    <img alt="Jupyter" src="https://img.shields.io/badge/Jupyter-F37626.svg?logo=Jupyter&logoColor=white&style=flat">
  </p>

  <h3>☁️ Cloud / IaC</h3>
    
  <p>
    <img src="https://img.shields.io/badge/Terraform-7B42BC?logo=terraform&logoColor=fff&style=flat" alt="Terraform Badge">
    <img src="https://img.shields.io/badge/Amazon%20AWS-232F3E?logo=amazonaws&logoColor=fff&style=flat" alt="Amazon AWS Badge">
    <img src="https://img.shields.io/badge/Microsoft%20Azure-0078D4?logo=microsoftazure&logoColor=fff&style=flat" alt="Microsoft Azure Badge">
    <img src="https://img.shields.io/badge/Google%20Cloud-4285F4?logo=googlecloud&logoColor=fff&style=flat" alt="Google Cloud Badge">
    <img src="https://img.shields.io/badge/Azure%20DevOps-0078D7?logo=azuredevops&logoColor=fff&style=flat" alt="Azure DevOps Badge">
    <img src="https://img.shields.io/badge/Cloudflare-F38020?logo=cloudflare&logoColor=fff&style=flat" alt="Cloudflare Badge">
    <img src="https://img.shields.io/badge/AWS%20Lambda-F90?logo=awslambda&logoColor=fff&style=flat" alt="AWS Lambda Badge">
    <img src="https://img.shields.io/badge/Azure%20Functions-0062AD?logo=azurefunctions&logoColor=fff&style=flat" alt="Azure Functions Badge">
    <img src="https://img.shields.io/badge/Amazon%20EC2-F90?logo=amazonec2&logoColor=fff&style=flat" alt="Amazon EC2 Badge">
    <img src="https://img.shields.io/badge/Amazon%20EKS-F90?logo=amazoneks&logoColor=fff&style=flat" alt="Amazon EKS Badge">
    <img src="https://img.shields.io/badge/Amazon%20CloudWatch-FF4F8B?logo=amazoncloudwatch&logoColor=fff&style=flat" alt="Amazon CloudWatch Badge">
    <img src="https://img.shields.io/badge/Amazon%20SQS-FF4F8B?logo=amazonsqs&logoColor=fff&style=flat" alt="Amazon SQS Badge">
    <img src="https://img.shields.io/badge/Amazon%20API%20Gateway-FF4F8B?logo=amazonapigateway&logoColor=fff&style=flat" alt="Amazon API Gateway Badge">
    <img src="https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes&logoColor=fff&style=flat" alt="Kubernetes Badge">
  </p>

  <h3>🔐 Security / Monitoring / Incident</h3>

  <p>
    <img src="https://img.shields.io/badge/Tenable-00B2A9?style=flat&logoColor=fff" alt="Tenable">
    <img src="https://img.shields.io/badge/PagerDuty-06AC38?style=flat&logo=pagerduty&logoColor=fff" alt="PagerDuty">
    <img src="https://img.shields.io/badge/AlertOps-111111?style=flat&logoColor=fff" alt="AlertOps">
    <img src="https://img.shields.io/badge/ConnectWise-111111?style=flat&logoColor=fff" alt="ConnectWise">
    <img src="https://img.shields.io/badge/AWS%20CloudTrail-232F3E?style=flat&logo=amazonaws&logoColor=fff" alt="AWS CloudTrail">
    <img src="https://img.shields.io/badge/AWS%20GuardDuty-232F3E?style=flat&logo=amazonaws&logoColor=fff" alt="AWS GuardDuty">
    <img src="https://img.shields.io/badge/AWS%20Security%20Hub-232F3E?style=flat&logo=amazonaws&logoColor=fff" alt="AWS Security Hub">
    <img src="https://img.shields.io/badge/AWS%20WAF-232F3E?style=flat&logo=amazonaws&logoColor=fff" alt="AWS WAF">
    <img src="https://img.shields.io/badge/AWS%20KMS-232F3E?style=flat&logo=amazonaws&logoColor=fff" alt="AWS KMS">
    <img src="https://img.shields.io/badge/Microsoft%20Sentinel-0078D4?style=flat&logo=microsoftazure&logoColor=fff" alt="Microsoft Sentinel">
    <img src="https://img.shields.io/badge/Defender%20for%20Cloud-0078D4?style=flat&logo=microsoftazure&logoColor=fff" alt="Defender for Cloud">
    <img src="https://img.shields.io/badge/Azure%20Key%20Vault-0078D4?style=flat&logo=microsoftazure&logoColor=fff" alt="Azure Key Vault">
    <img src="https://img.shields.io/badge/Microsoft%20Entra%20ID-0078D4?style=flat&logo=microsoftazure&logoColor=fff" alt="Microsoft Entra ID">
    <img src="https://img.shields.io/badge/Azure%20Policy-0078D4?style=flat&logo=microsoftazure&logoColor=fff" alt="Azure Policy">
    <img src="https://img.shields.io/badge/GCP%20Security%20Command%20Center-4285F4?style=flat&logo=googlecloud&logoColor=fff" alt="GCP SCC">
    <img src="https://img.shields.io/badge/GCP%20Cloud%20KMS-4285F4?style=flat&logo=googlecloud&logoColor=fff" alt="GCP Cloud KMS">
    <img src="https://img.shields.io/badge/GCP%20Cloud%20Armor-4285F4?style=flat&logo=googlecloud&logoColor=fff" alt="GCP Cloud Armor">
</p>

  <h3>🗄️ Databases</h3>
  
  <p>
    <img src="https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=fff&style=flat" alt="MongoDB Badge">
    <img src="https://img.shields.io/badge/Amazon%20DynamoDB-4053D6?logo=amazondynamodb&logoColor=fff&style=flat" alt="Amazon DynamoDB Badge">
    <img src="https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=fff&style=flat" alt="Redis Badge">
    <img src="https://img.shields.io/badge/Amazon%20S3-569A31?logo=amazons3&logoColor=fff&style=flat" alt="Amazon S3 Badge">
    <img src="https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=fff&style=flat" alt="MySQL Badge">
    <img src="https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=fff&style=flat" alt="PostgreSQL Badge">
    <img src="https://img.shields.io/badge/Amazon%20RDS-527FFF?logo=amazonrds&logoColor=fff&style=flat" alt="Amazon RDS Badge">
    <img src="https://img.shields.io/badge/Elasticsearch-005571?logo=elasticsearch&logoColor=fff&style=flat" alt="Elasticsearch Badge">
    <img src="https://img.shields.io/badge/Amazon%20Redshift-8C4FFF?logo=amazonredshift&logoColor=fff&style=flat" alt="Amazon Redshift Badge">
    <img src="https://img.shields.io/badge/Cockroach%20Labs-6933FF?logo=cockroachlabs&logoColor=fff&style=flat" alt="Cockroach Labs Badge">
    <img src="https://img.shields.io/badge/Firebase-FFCA28?logo=firebase&logoColor=000&style=flat" alt="Firebase Badge">
  </p>

  <h3>💻 Software / Tools</h3>

  <p>
    <img alt="Git" src="https://img.shields.io/badge/Git-F05033.svg?logo=git&logoColor=white&style=flat">
    <img src="https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=000&style=flat" alt="Linux Badge">
    <img src="https://img.shields.io/badge/Ubuntu-E95420?logo=ubuntu&logoColor=fff&style=flat" alt="Ubuntu Badge">
    <img src="https://img.shields.io/badge/Red%20Hat-E00?logo=redhat&logoColor=fff&style=flat" alt="Red Hat Badge">
    <img src="https://img.shields.io/badge/Jenkins-D24939?logo=jenkins&logoColor=fff&style=flat" alt="Jenkins Badge">
    <img src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=fff&style=flat" alt="Docker Badge">
    <img alt="Jupyter" src="https://img.shields.io/badge/Jupyter-F37626.svg?logo=Jupyter&logoColor=white&style=flat">
    <img src="https://img.shields.io/badge/HubSpot-FF7A59?logo=hubspot&logoColor=fff&style=flat" alt="HubSpot Badge">
    <img alt="Adobe" src="https://img.shields.io/badge/Adobe-FF0000.svg?logo=adobe&logoColor=white&style=flat">
    <img alt="Brave" src="https://img.shields.io/badge/-Brave-FB542B?logo=brave&logoColor=white&style=flat">
    <img alt="OBS Studio" src="https://img.shields.io/badge/-OBS-302E31?logo=obs-studio&logoColor=white&style=flat">
    <img alt="Ableton Live" src="https://img.shields.io/badge/Ableton%20Live-000?logo=abletonlive&logoColor=fff&style=flat">
    <img alt="Blender" src="https://img.shields.io/badge/Blender-F5792A?logo=blender&logoColor=fff&style=flat">
    <img src="https://img.shields.io/badge/Debian-A81D33?logo=debian&logoColor=fff&style=flat" alt="Debian Badge">
    <img src="https://img.shields.io/badge/Raspberry%20Pi-A22846?logo=raspberrypi&logoColor=fff&style=flat" alt="Raspberry Pi Badge">
  </p>
</details>

<details>
  
<summary><span style="font-size: 25px; font-weight: bold">✅ Certifications</span></summary>

<img alt="AWS Certified Solutions Architect - Professional" src="https://images.credly.com/size/680x680/images/2d84e428-9078-49b6-a804-13c15383d0de/image.png" width="100" height="100" style="pointer-events: none;">
<img alt="AWS Certified DevOps Engineer - Professional" src="https://images.credly.com/size/680x680/images/bd31ef42-d460-493e-8503-39592aaf0458/image.png" width="100" height="100" style="pointer-events: none;">
<img alt="AWS Certified Solutions Architect - Associate" src="https://images.credly.com/size/680x680/images/0e284c3f-5164-4b21-8660-0d84737941bc/image.png" width="100" height="100" style="pointer-events: none;">
<img alt="AWS Certified Developer - Associate" src="https://images.credly.com/size/680x680/images/b9feab85-1a43-4f6c-99a5-631b88d5461b/image.png" width="100" height="100" style="pointer-events: none;">
<img alt="AWS Certified Data Engineer – Associate" src="https://images.credly.com/size/340x340/images/e5c85d7f-4e50-431e-b5af-fa9d9b0596e7/image.png" width="100" height="100" style="pointer-events: none;">
<img alt="AWS Certified Machine Learning Engineer – Associate" src="https://images.credly.com/size/340x340/images/1a634b4e-3d6b-4a74-b118-c0dcb429e8d2/image.png" width="100" height="100" style="pointer-events: none;">
<img alt="AWS Certified SysOps Administrator - Associate" src="https://images.credly.com/size/680x680/images/f0d3fbb9-bfa7-4017-9989-7bde8eaf42b1/image.png" width="100" height="100" style="pointer-events: none;">
<img alt="AWS Certified Cloud Practitioner - Foundational" src="https://images.credly.com/size/680x680/images/00634f82-b07f-4bbd-a6bb-53de397fc3a6/image.png" width="100" height="100" style="pointer-events: none;">
<img alt="AWS Certified AI Practitioner" src="https://images.credly.com/size/340x340/images/4d4693bb-530e-4bca-9327-de07f3aa2348/image.png" width="100" height="100" style="pointer-events: none;">
<img alt="AWS Certified Security - Specialty" src="https://images.credly.com/size/340x340/images/53acdae5-d69f-4dda-b650-d02ed7a50dd7/image.png" width="100" height="100" style="pointer-events: none;">
<img alt="AWS Certified Advanced Networking – Specialty" src="https://images.credly.com/size/340x340/images/4d08274f-64c1-495e-986b-3143f51b1371/image.png" width="100" height="100" style="pointer-events: none;">
<img alt="AWS Certified Machine Learning – Specialty" src="https://images.credly.com/size/340x340/images/778bde6c-ad1c-4312-ac33-2fa40d50a147/image.png" width="100" height="100" style="pointer-events: none;">

<img alt="HashiCorp Terraform Associate" src="https://images.credly.com/size/340x340/images/0dc62494-dc94-469a-83af-e35309f27356/blob" width="100" height="100" style="pointer-events: none;">

<img alt="MS Certified - Azure Solutions Architect Expert" src="https://github.com/shmkl/imgs/blob/main/misc/azure-solutions-architect-expert-600x600.png?raw=true" width="100" height="100" style="pointer-events: none;">
<img alt="MS Certified - Cybersecurity Architect Expert" src="https://github.com/shmkl/imgs/blob/main/misc/cybersecurity-architect-600x600.png?raw=true" width="100" height="100" style="pointer-events: none;">
<img alt="MS Certified - Windows Server Hybrid Administrator Associate" src="https://github.com/shmkl/imgs/blob/main/misc/azure-windows-server-hybrid-administrator-associate-600x600.png?raw=true" width="100" height="100" style="pointer-events: none;">
<img alt="MS Certified - Azure Security Engineer Associate" src="https://github.com/shmkl/imgs/blob/main/misc/azure-security-engineer-associate600x600.png?raw=true" width="100" height="100" style="pointer-events: none;">
<img alt="MS Certified - Azure Network Engineer Associate" src="https://github.com/shmkl/imgs/blob/main/misc/azure-network-engineer-associate-600x600.png?raw=true" width="100" height="100" style="pointer-events: none;">
<img alt="MS Certified - Azure Administrator Associate" src="https://github.com/shmkl/imgs/blob/main/misc/azure-administrator-associate-600x600.png?raw=true" width="100" height="100" style="pointer-events: none;">
<img alt="MS Certified - Security Operations Analyst Associate" src="https://github.com/shmkl/imgs/blob/main/misc/security-operations-analyst-associate-600x600.png?raw=true" width="100" height="100" style="pointer-events: none;">
<img alt="MS Certified - Identity and Access Administrator Associate" src="https://github.com/shmkl/imgs/blob/main/misc/identity-and-access-administrator-600x600.png?raw=true" width="100" height="100" style="pointer-events: none;">
<img alt="MS Certified - Information Protection and Compliance Administrator Associate" src="https://github.com/shmkl/imgs/blob/main/misc/information-protection-administrator-600x600.png?raw=true" width="100" height="100" style="pointer-events: none;">
<img alt="MS Certified - Azure Fundamentals Fundamentals" src="https://github.com/shmkl/imgs/blob/main/misc/azure-fundamentals-600x600.png?raw=true" width="100" height="100" style="pointer-events: none;">
<img alt="MS Certified - Azure AI Fundamentals" src="https://github.com/shmkl/imgs/blob/main/misc/azure-ai-fundamentals-600x600.png?raw=true" width="100" height="100" style="pointer-events: none;">

</details>
