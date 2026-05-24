<div align="center">

<!-- HERO BANNER -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0ea5e9&height=220&section=header&text=Pranay%20Singuluri&fontSize=48&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Java%20Full%20Stack%20Engineer&descAlignY=55&descAlign=50" alt="Pranay Singuluri Banner" width="100%" />

<!-- TYPING SUBTITLE -->
<a href="https://github.com/pranaysinguluri">
  <img src="https://readme-typing-svg.demolab.com?font=Inter&weight=400&size=15&pause=2500&color=0ea5e9&center=true&vCenter=true&width=600&lines=Building+high-performance+React+%2B+TypeScript+UIs;Architecting+scalable+distributed+Java+backends;Engineering+high-throughput+event-driven+APIs;Designing+resilient+cloud-native+infrastructure" alt="Engineering Focus" />
</a>

<!-- PREMIUM CONTACT BADGES -->
<a href="mailto:singuluripranay@gmail.com"><img src="https://img.shields.io/badge/Email-000000?style=for-the-badge&logo=gmail&logoColor=0ea5e9" alt="Email" /></a>
<a href="https://www.linkedin.com/in/pranay-singuluri/"><img src="https://img.shields.io/badge/LinkedIn-000000?style=for-the-badge&logo=linkedin&logoColor=0ea5e9" alt="LinkedIn" /></a>
<a href="https://github.com/pranaysinguluri"><img src="https://img.shields.io/badge/GitHub-000000?style=for-the-badge&logo=github&logoColor=0ea5e9" alt="GitHub" /></a>

<!-- SUBTLE VIEW COUNTER -->
<img src="https://komarev.com/ghpvc/?username=pranaysinguluri&color=0ea5e9&style=flat-square&label=SYSTEM+VIEWS" alt="Profile Views" />

</div>

### ❯ Identity & Focus

**Full Stack Engineer** specializing in the end-to-end delivery of fault-tolerant, distributed enterprise systems. Proficient in engineering resilient Java backends and marrying them with high-performance, component-driven React applications. Currently driving full-stack solutions for supply chain operations at **Green Bay Packaging**. 

M.S. in Information Science · **Missouri S&T**
*Domain Expertise: Supply Chain · Healthcare · Telecom*

### ❯ Engineering Philosophy

<table width="100%" style="border: none;">
  <tr style="border: none;">
    <td width="50%" valign="top" style="border: none;">
      <h4>⚛️ Type-Safe & Performance-Driven Frontend</h4>
      <p>Architecting scalable user interfaces utilizing <b>React</b> and <b>TypeScript</b>. Focused on state optimization, reusable component lifecycles, and modern semantic layouts using strict <b>JavaScript (ES6+)</b>, <b>HTML5</b>, and <b>CSS3</b> design systems.</p>
    </td>
    <td width="50%" valign="top" style="border: none;">
      <h4>⚡ Reactive & Cloud-Native Backend</h4>
      <p>Building high-throughput, non-blocking APIs with <b>Spring WebFlux</b> and decoupled microservices via <b>Kafka</b>. Multi-node container orchestration orchestrated smoothly via <b>AWS</b>, <b>Docker</b>, and <b>Kubernetes</b>.</p>
    </td>
  </tr>
</table>

### ❯ Technology Stack

**Frontend Architecture**
<img src="https://img.shields.io/badge/React-000000?style=for-the-badge&logo=react&logoColor=0ea5e9" alt="React" />
<img src="https://img.shields.io/badge/TypeScript-000000?style=for-the-badge&logo=typescript&logoColor=0ea5e9" alt="TypeScript" />
<img src="https://img.shields.io/badge/JavaScript-000000?style=for-the-badge&logo=javascript&logoColor=0ea5e9" alt="JavaScript" />
<img src="https://img.shields.io/badge/HTML5-000000?style=for-the-badge&logo=html5&logoColor=0ea5e9" alt="HTML5" />
<img src="https://img.shields.io/badge/CSS3-000000?style=for-the-badge&logo=css3&logoColor=0ea5e9" alt="CSS3" />

**Backend & Data Layer**
<img src="https://img.shields.io/badge/Java-000000?style=for-the-badge&logo=openjdk&logoColor=0ea5e9" alt="Java" />
<img src="https://img.shields.io/badge/Spring_Boot-000000?style=for-the-badge&logo=springboot&logoColor=0ea5e9" alt="Spring Boot" />
<img src="https://img.shields.io/badge/Spring_WebFlux-000000?style=for-the-badge&logo=spring&logoColor=0ea5e9" alt="Spring WebFlux" />
<img src="https://img.shields.io/badge/PostgreSQL-000000?style=for-the-badge&logo=postgresql&logoColor=0ea5e9" alt="PostgreSQL" />

**Cloud, Messaging & Infrastructure**
<img src="https://img.shields.io/badge/Apache_Kafka-000000?style=for-the-badge&logo=apachekafka&logoColor=0ea5e9" alt="Kafka" />
<img src="https://img.shields.io/badge/AWS-000000?style=for-the-badge&logo=amazonwebservices&logoColor=0ea5e9" alt="AWS" />
<img src="https://img.shields.io/badge/Docker-000000?style=for-the-badge&logo=docker&logoColor=0ea5e9" alt="Docker" />
<img src="https://img.shields.io/badge/Kubernetes-000000?style=for-the-badge&logo=kubernetes&logoColor=0ea5e9" alt="Kubernetes" />

### ❯ Featured Production Architecture

> ### 🚘 AutoCare Platform
> **Enterprise-grade full-stack automotive service platform engineered for high availability.**
>
> * **Frontend Client:** Engineered an intuitive, single-page dashboard using **React** and **TypeScript**. Implemented granular client-side state management, responsive grid layouts utilizing advanced CSS3/HTML5 semantic structuring, and high-efficiency API polling to visualize real-time asset telemetry.
> * **Backend & Event Streaming:** Designed a distributed Java backend utilizing microservices to handle concurrent service requests and inventory updates. Integrated **Apache Kafka** to handle asynchronous message processing, dropping system API latency under heavy scale.

#### Core Event-Driven Flow
```mermaid
graph TD
    Client([React + TypeScript UI]) --> Gateway[API Gateway / Load Balancer]
    
    Gateway --> ServiceA[Inventory Microservice]
    Gateway --> ServiceB[Booking Microservice]
    
    ServiceA --> DB1[(PostgreSQL Cluster)]
    ServiceB --> DB2[(PostgreSQL Cluster)]
    
    ServiceA -- Publishes Events --> Kafka{{Apache Kafka Event Bus}}
    ServiceB -- Subscribes to Events --> Kafka
