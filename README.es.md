<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=200&section=header&text=Henry%20Mosquera&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Senior%20DevOps%20%7C%20Multi-Cloud%20Specialist&descAlignY=58&descSize=20" alt="Henry Mosquera banner" width="100%"/>

<a href="https://github.com/henryd24">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&duration=3000&pause=1000&color=38BDF8&center=true&vCenter=true&width=600&lines=Senior+DevOps+Engineer;Multi-Cloud%3A+AWS+%7C+Azure+%7C+GCP;Platform+Engineering+%26+Developer+Tooling;Software+Defined+Everything" alt="Typing SVG" />
</a>

[English](README.md) · [Español](README.es.md)

</div>

Conecto el desarrollo con las operaciones construyendo automatización robusta y plataformas cloud-native. Experto en orquestación de infraestructura y en crear herramientas a medida para desarrolladores en entornos de alta escala.

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%" alt="divider">

## 🌱 Actualmente

- 🔭 Construyendo operadores de Kubernetes y componentes de IDP en **Go**
- ⚙️ Publicando extensiones de Azure DevOps en **TypeScript**
- 💬 Pregúntame sobre: **Terraform, Kubernetes, GitOps, Azure DevOps, multi-cloud**

## 🛠 Stack Tecnológico

<div align="center">

**Cloud y Orquestación**

<img src="https://skillicons.dev/icons?i=aws,azure,gcp,terraform,kubernetes,docker,openshift&perline=7" alt="cloud and orchestration"/>

<br/>

<img src="https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white" alt="Helm"/>
<img src="https://img.shields.io/badge/Argo%20CD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white" alt="Argo CD"/>
<img src="https://img.shields.io/badge/Pulumi-8A3391?style=for-the-badge&logo=pulumi&logoColor=white" alt="Pulumi"/>
<img src="https://img.shields.io/badge/Crossplane-1B2A3A?style=for-the-badge&logo=crossplane&logoColor=white" alt="Crossplane"/>
<img src="https://img.shields.io/badge/Terragrunt-5C4EE5?style=for-the-badge&logo=terraform&logoColor=white" alt="Terragrunt"/>

**Programación y Automatización**

<img src="https://skillicons.dev/icons?i=go,ts,py,bash,githubactions,jenkins,linux,git&perline=8" alt="languages and CI/CD"/>

</div>

- **IaC:** Terraform, Terragrunt, Pulumi, Crossplane
- **CI/CD & GitOps:** Azure DevOps, GitHub Actions, Jenkins, Argo (CD, Rollouts, Workflows)
- **Containers:** Kubernetes, OpenShift, Docker, Helm

## 🏅 Certificaciones

<div align="center">

[![GitHub Administration](https://img.shields.io/badge/GitHub-Administration-181717?style=for-the-badge&logo=github&logoColor=white)](https://www.credly.com/badges/f4a78224-919e-484b-8c60-3a21c28111c7)
[![AWS Solutions Architect Associate](https://img.shields.io/badge/AWS-Solutions%20Architect%20Associate-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)](https://www.credly.com/badges/eefd06c7-b225-4115-9b9e-74cd64f40c46)
[![Azure Fundamentals](https://img.shields.io/badge/Microsoft-Azure%20Fundamentals%20(AZ--900)-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)](https://www.credly.com/badges/15d5f031-733c-4d28-b9e2-76bac2120c9e)

</div>

## 📂 Proyectos Destacados

<div align="center">

[![kubernetes-operator-tag-images](https://github-readme-stats.vercel.app/api/pin/?username=henryd24&repo=kubernetes-operator-tag-images&theme=tokyonight&hide_border=true)](https://github.com/henryd24/kubernetes-operator-tag-images)
[![azure_devops_cli](https://github-readme-stats.vercel.app/api/pin/?username=henryd24&repo=azure_devops_cli&theme=tokyonight&hide_border=true)](https://github.com/henryd24/azure_devops_cli)

[![azdevops-extension-exec-pipeline](https://github-readme-stats.vercel.app/api/pin/?username=henryd24&repo=azdevops-extension-exec-pipeline&theme=tokyonight&hide_border=true)](https://github.com/henryd24/azdevops-extension-exec-pipeline)
[![azdevops-sonarcloud-create-project](https://github-readme-stats.vercel.app/api/pin/?username=henryd24&repo=azdevops-sonarcloud-create-project&theme=tokyonight&hide_border=true)](https://github.com/henryd24/azdevops-sonarcloud-create-project)

</div>

### 🛠 Ecosistema de Extensiones para Azure DevOps
Extensiones propias usadas por varias organizaciones para agilizar procesos DevOps:

| Extensión | Qué hace |
|---|---|
| [**SonarCloud Automator**](https://github.com/henryd24/azdevops-sonarcloud-create-project) | Provisión sin intervención: verifica si el proyecto existe en SonarCloud y lo crea si no. |
| [**SonarQube Automator**](https://github.com/henryd24/azdevops-sonarqube-create-project) | Mismo flujo para SonarQube autoalojado. |
| [**Pipeline Execution Manager**](https://github.com/henryd24/azdevops-extension-exec-pipeline) | Ejecuta pipelines, espera su fin y verifica éxito, fallo o cancelación en dependencias complejas. |
| [**azure_devops_cli**](https://github.com/henryd24/azure_devops_cli) | CLI no oficial de Azure DevOps escrita en Go. |

### ⚓ Desarrollo Cloud-Native
[**kubernetes-operator-tag-images**](https://github.com/henryd24/kubernetes-operator-tag-images) es un operador en Go que observa Argo Rollouts y, cuando un despliegue está saludable, retaguea la imagen en Amazon ECR con tags por entorno y un tag activo para facilitar promoción y trazabilidad.

```mermaid
flowchart LR
    A[Argo Rollout] -->|despliegue saludable| B[K8s Operator<br/>Go]
    B -->|retag image| C[(Amazon ECR)]
    C --> D[env tag: dev / stg / prod]
    C --> E[active tag]
    E -.->|promotion| A
```

## 🧠 Filosofía
> "No te limites a gestionar infraestructura; construye las herramientas que la gestionen por ti."
> Me enfoco en **Software Defined Everything**: infraestructura, pipelines y seguridad como código para lograr consistencia y velocidad.

## 🚀 Impacto y Visibilidad

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=henryd24&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true" alt="GitHub stats"/>
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=henryd24&layout=compact&theme=tokyonight&hide_border=true&langs_count=6" alt="Top languages"/>

<p align="center"><img src="https://streak-stats.demolab.com/?user=henryd24&theme=tokyonight&hide_border=true" alt="GitHub streak"/></p>

<p align="center"><img src="https://raw.githubusercontent.com/henryd24/henryd24/output/github-snake-dark.svg" alt="Contribution snake" width="100%"/></p>

</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%" alt="divider">

## 📫 Conecta conmigo

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hendam/)

![Profile Views](https://komarev.com/ghpvc/?username=henryd24&color=0e75b6&style=flat-square&label=PROFILE+VIEWS)

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,100:0f2027&height=100&section=footer" width="100%" alt="footer"/>
