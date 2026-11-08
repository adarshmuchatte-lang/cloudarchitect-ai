# ☁️ CloudArchitect AI

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F172A,50:2563EB,100:06B6D4&height=220&section=header&text=CloudArchitect%20AI&fontSize=48&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Design%20Smarter.%20Scale%20Better.&descAlignY=58&descSize=18" width="100%" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1000&color=38BDF8&center=true&vCenter=true&width=650&lines=AI-Powered+AWS+Architecture+Designer;Intelligent+Cloud+Recommendations;Powered+by+Amazon+Bedrock;Build.+Visualize.+Compare.+Innovate." alt="Typing SVG" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/AWS-Cloud-orange?style=for-the-badge&logo=amazonaws&logoColor=white" />
  <img src="https://img.shields.io/badge/AI-Amazon%20Bedrock-purple?style=for-the-badge&logo=amazonaws" />
  <img src="https://img.shields.io/badge/Node.js-20+-green?style=for-the-badge&logo=nodedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Status-Development-success?style=for-the-badge" />
</p>

---

## 🌌 About The Project

**CloudArchitect AI** is an AI-powered cloud architecture recommendation platform that transforms application requirements into intelligent, structured AWS architecture designs.

It combines deterministic architecture selection with Amazon Bedrock to explain the recommended infrastructure, helping developers make better cloud architecture decisions.

Instead of manually figuring out which AWS services to use, users can describe their application requirements and receive a visualized architecture recommendation.

## ✨ Features

<table>
<tr>
<td width="50%">

### 🤖 AI Architecture Assistant
Generate contextual architecture explanations using Amazon Bedrock and Amazon Nova Lite.

</td>
<td width="50%">

### 🏗️ Architecture Visualization
Explore interactive AWS architecture diagrams and service relationships.

</td>
</tr>
<tr>
<td width="50%">

### 💰 Cost Classification
Understand estimated cost categories through Low, Medium and High classifications.

</td>
<td width="50%">

### 🔐 Secure Authentication
User registration, email verification and login using Amazon Cognito.

</td>
</tr>
<tr>
<td width="50%">

### 📚 Recommendation History
Save and retrieve personalized architecture recommendations using DynamoDB.

</td>
<td width="50%">

### 📊 Architecture Comparison
Compare previously saved architecture recommendations.

</td>
</tr>
<tr>
<td width="50%">

### 📤 Export Architecture
Export architecture diagrams as PNG, SVG and JSON.

</td>
<td width="50%">

### ☁️ AWS Deployment
Deploy cloud infrastructure using AWS SAM and CloudFormation.

</td>
</tr>
</table>

---

## 🖥️ Architecture Preview

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:0F172A,100:1D4ED8&height=3" width="80%" />
</p>

<p align="center">
  <b>Application Requirements</b>
  <br>⬇️
  <br><b>Frontend Interface</b>
  <br>⬇️
  <br><b>Amazon API Gateway</b>
  <br>⬇️
  <br><b>AWS Lambda Recommendation Engine</b>
  <br>⬇️
  <br>┌─────────────────┴─────────────────┐
  <br>⬇️　　　　　　　　　⬇️
  <br><b>Amazon Bedrock</b>　　　 <b>Amazon DynamoDB</b>
  <br>⬇️　　　　　　　　　⬇️
  <br><b>AI Explanation</b>　　　 <b>Saved History</b>
  <br>└─────────────────┬─────────────────┘
  <br>⬇️
  <br><b>Interactive AWS Architecture</b>
</p>

---

## ⚙️ Technology Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=html,css,js,nodejs,aws,python" />
</p>

| Layer | Technology |
|---|---|
| Frontend | HTML, CSS, JavaScript |
| Backend | Node.js 20 |
| AI Engine | Amazon Bedrock / Nova Lite |
| Authentication | Amazon Cognito |
| API | Amazon API Gateway |
| Database | Amazon DynamoDB |
| Compute | AWS Lambda |
| Infrastructure | AWS SAM / CloudFormation |
| Hosting | Amazon S3 |
| Monitoring | Amazon CloudWatch |

---

## 🔄 How It Works

1. **Sign In:** Create an account using Amazon Cognito.
2. **Enter Requirements:** Specify application type, users, budget, database and availability.
3. **Generate Architecture:** The recommendation engine selects suitable AWS services.
4. **AI Explanation:** Amazon Bedrock explains the selected architecture.
5. **Visualize:** Explore the generated architecture and service connections.
6. **Save & Compare:** Store recommendations and compare previous designs.
7. **Export:** Download architecture diagrams in supported formats.

---

## 🚀 Getting Started

### Prerequisites

- Node.js 20+
- AWS CLI
- AWS SAM CLI
- Configured AWS account
- Required AWS IAM permissions
- Amazon Bedrock model access

### Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/cloudarchitect-ai.git

cd cloudarchitect-ai
```

### Install Dependencies

```bash
npm --prefix backend install
```

### Run Tests

```bash
node backend/recommendationEngine.test.js
```

### Deploy on AWS

**Windows PowerShell**

```powershell
.\scripts\deploy.ps1 -StackName cloudarchitect-ai -Region us-east-1
```

**Linux / macOS**

```bash
chmod +x scripts/deploy.sh

./scripts/deploy.sh cloudarchitect-ai
```

---

## 📁 Project Structure

```text
CloudArchitect-AI/
│
├── backend/
│   ├── app.js
│   ├── recommendationEngine.js
│   ├── recommendationEngine.test.js
│   └── package.json
│
├── frontend/
│   ├── index.html
│   ├── styles.css
│   ├── app.js
│   └── config.js
│
├── scripts/
│   ├── deploy.sh
│   ├── deploy.ps1
│   └── write_config.py
│
├── template.yaml
└── README.md
```

---

## 🎯 Project Vision

Making cloud architecture design more accessible, understandable and intelligent.

CloudArchitect AI aims to bridge the gap between application requirements and cloud infrastructure decisions through AI-assisted explanations and interactive visualization.

---

## ⚠️ Disclaimer

This is an educational cloud architecture recommendation prototype. It recommends AWS architectures but does not automatically provision every resource in the recommended application infrastructure. Cost classifications are qualitative, not exact monetary estimates.

---

## 👨‍💻 Developer

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&pause=1000&color=38BDF8&center=true&vCenter=true&width=450&lines=Adarsh+Muchatte;Information+Technology+Student;VIT+Vellore" />
</p>

<p align="center">
  <b>Building intelligent solutions with AI and Cloud Computing.</b>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:06B6D4,50:2563EB,100:0F172A&height=120&section=footer" width="100%" />
</p>

<p align="center">
  ⭐ If you like this project, consider giving it a star!
</p>
