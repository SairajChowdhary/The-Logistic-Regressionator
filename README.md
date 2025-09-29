<div align="center">

<!-- Animated Header with SVG -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,14,18,20,24&height=200&section=header&text=Logistic%20Regressionator&fontSize=60&fontAlignY=35&animation=twinkling&fontColor=fff" />

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3000&pause=1000&color=4CAF50&center=true&vCenter=true&width=600&lines=Automated+Logistic+Regression+Pipeline;Cloud-Native+%7C+Scalable+%7C+Production-Ready;Powered+by+n8n+%2B+Supabase+%2B+Quadratic" alt="Typing SVG" />
</p>

<p align="center">
  <strong>An intelligent, automated pipeline for logistic regression analysis</strong><br>
  Combining cloud databases, workflow automation, and statistical computing
</p>

<!-- Animated Badges -->
<p align="center">
  <img src="https://img.shields.io/badge/Status-Active-success?style=for-the-badge&logo=statuspage&logoColor=white" alt="Status" />
  <img src="https://img.shields.io/badge/Version-1.0.0-blue?style=for-the-badge&logo=semver&logoColor=white" alt="Version" />
  <img src="https://img.shields.io/badge/License-MIT-purple?style=for-the-badge&logo=opensourceinitiative&logoColor=white" alt="License" />
  <img src="https://img.shields.io/badge/PRs-Welcome-brightgreen?style=for-the-badge&logo=github&logoColor=white" alt="PRs" />
</p>

<!-- Tech Stack Badges -->
<p align="center">
  <img src="https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white" alt="n8n" />
  <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white" alt="Supabase" />
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white" alt="Google Cloud" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
</p>

</div>

<br>

<!-- Animated Divider -->
<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="100%">

## 📋 Table of Contents

- [✨ Features](#-features)
- [🏗️ Architecture](#️-architecture)
- [🚀 Quick Start](#-quick-start)
- [⚙️ Installation](#️-installation)
- [📊 Usage](#-usage)
- [🔧 Configuration](#-configuration)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)

<br>

## ✨ Features

<div align="center">
  <img src="https://user-images.githubusercontent.com/74038190/212284158-e840e285-664b-44d7-b79b-e264b5e54825.gif" width="400">
</div>

<table>
<tr>
<td width="50%">

### 🔄 **Automated Workflows**
- **End-to-end automation** with n8n
- **Event-driven processing** pipelines
- **Error handling** and retry logic
- **Real-time monitoring** and logging

</td>
<td width="50%">

### 🗄️ **Cloud-Native Database**
- **Supabase** PostgreSQL backend
- **Row-level security** for data protection
- **Real-time subscriptions** support
- **Automatic backups** and scaling

</td>
</tr>
<tr>
<td width="50%">

### 📈 **Statistical Analysis**
- **Logistic regression** modeling
- **Feature engineering** pipelines
- **Model validation** and metrics
- **Quadratic** integration for analysis

</td>
<td width="50%">

### 🔐 **Secure Integration**
- **OAuth 2.0** authentication
- **Google Cloud** API integration
- **Environment-based** config
- **Encrypted credentials** storage

</td>
</tr>
</table>

<br>

## 🏗️ Architecture

<div align="center">
  <img src="https://user-images.githubusercontent.com/74038190/212749447-bfb7e725-6987-49d9-ae85-2015e3e7cc41.gif" width="500">
</div>

```mermaid
graph LR
    A[📊 CSV Files] -->|Upload| B[n8n Workflow]
    B -->|Ingest| C[(Supabase PostgreSQL)]
    C -->|Query| D[Quadratic Analysis]
    D -->|Results| E[📧 Gmail API]
    E -->|Notify| F[👤 End User]
    
    G[☁️ Google Cloud OAuth] -.->|Authenticate| B
    
    style A fill:#4CAF50,stroke:#2E7D32,stroke-width:2px,color:#fff
    style B fill:#EA4B71,stroke:#C62828,stroke-width:2px,color:#fff
    style C fill:#3FCF8E,stroke:#00897B,stroke-width:2px,color:#fff
    style D fill:#2196F3,stroke:#1565C0,stroke-width:2px,color:#fff
    style E fill:#FBBC04,stroke:#F57C00,stroke-width:2px,color:#fff
    style F fill:#9C27B0,stroke:#6A1B9A,stroke-width:2px,color:#fff
    style G fill:#4285F4,stroke:#1565C0,stroke-width:2px,color:#fff
```

### 🔄 **Data Flow Pipeline**

1. **📥 Data Ingestion** - CSV files uploaded and validated
2. **🔄 ETL Processing** - n8n orchestrates data transformation
3. **💾 Storage** - Cleaned data stored in Supabase PostgreSQL
4. **📊 Analysis** - Quadratic performs logistic regression
5. **📤 Output** - Results delivered via Gmail API

<br>

## 🚀 Quick Start

<div align="center">
  <img src="https://user-images.githubusercontent.com/74038190/229223156-0cbdaba9-3128-4d8e-8719-b6b4cf741b67.gif" width="400">
</div>

### ⚡ One-Command Setup (Docker)

```bash
# Clone the repository
git clone https://github.com/yourusername/logistic-regressionator.git
cd logistic-regressionator

# Start all services with Docker Compose
docker-compose up -d

# Access n8n at http://localhost:5678
```

<br>

## ⚙️ Installation

### 📋 **Prerequisites**

<table>
<tr>
<td align="center" width="25%">
<img src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/nodejs/nodejs.png" width="60"><br>
<strong>Node.js</strong><br>
v18+ LTS
</td>
<td align="center" width="25%">
<img src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/docker/docker.png" width="60"><br>
<strong>Docker</strong><br>
v20+
</td>
<td align="center" width="25%">
<img src="https://avatars.githubusercontent.com/u/54469796?s=200&v=4" width="60"><br>
<strong>Supabase</strong><br>
Account
</td>
<td align="center" width="25%">
<img src="https://www.gstatic.com/images/branding/product/2x/cloud_96dp.png" width="60"><br>
<strong>Google Cloud</strong><br>
OAuth Setup
</td>
</tr>
</table>

<br>

### 📥 **Step-by-Step Installation**

<details>
<summary><b>1️⃣ Clone Repository & Install Dependencies</b></summary>

```bash
# Clone the repository
git clone https://github.com/yourusername/logistic-regressionator.git
cd logistic-regressionator

# Install Node.js dependencies
npm install

# Or using Yarn
yarn install
```

</details>

<details>
<summary><b>2️⃣ Configure Environment Variables</b></summary>

```bash
# Copy the example environment file
cp .env.example .env

# Edit .env with your configuration
nano .env
```

**Required Environment Variables:**

```env
# Supabase Configuration
SUPABASE_URL=your_supabase_project_url
SUPABASE_ANON_KEY=your_supabase_anon_key
SUPABASE_SERVICE_KEY=your_supabase_service_key

# n8n Configuration
N8N_BASIC_AUTH_ACTIVE=true
N8N_BASIC_AUTH_USER=admin
N8N_BASIC_AUTH_PASSWORD=your_secure_password

# Google Cloud OAuth
GOOGLE_CLIENT_ID=your_client_id
GOOGLE_CLIENT_SECRET=your_client_secret
GOOGLE_REDIRECT_URI=http://localhost:5678/oauth/callback

# PostgreSQL (if not using Supabase)
DATABASE_URL=postgresql://user:password@localhost:5432/logistic_regression
```

</details>

<details>
<summary><b>3️⃣ Set Up Supabase Database</b></summary>

1. Create a new project in [Supabase](https://supabase.com)
2. Run the database migration:

```sql
-- Create tables for data storage
CREATE TABLE raw_data (
    id SERIAL PRIMARY KEY,
    created_at TIMESTAMP WITH TIME ZONE DEFAULT NOW(),
    data JSONB NOT NULL
);

CREATE TABLE regression_results (
    id SERIAL PRIMARY KEY,
    created_at TIMESTAMP WITH TIME ZONE DEFAULT NOW(),
    model_params JSONB,
    coefficients JSONB,
    accuracy DECIMAL,
    confusion_matrix JSONB
);
```

3. Enable Row Level Security (RLS) for secure access

</details>

<details>
<summary><b>4️⃣ Configure Google Cloud OAuth</b></summary>

1. Go to [Google Cloud Console](https://console.cloud.google.com)
2. Create a new project or select existing
3. Enable Gmail API
4. Create OAuth 2.0 credentials:
   - Application type: Web application
   - Authorized redirect URIs: `http://localhost:5678/oauth/callback`
5. Copy Client ID and Client Secret to `.env`

</details>

<details>
<summary><b>5️⃣ Start n8n</b></summary>

**Option A: Using npm**
```bash
npm install -g n8n
n8n start
```

**Option B: Using Docker**
```bash
docker run -it --rm \
  --name n8n \
  -p 5678:5678 \
  -v ~/.n8n:/home/node/.n8n \
  n8nio/n8n
```

**Option C: Using Docker Compose**
```bash
docker-compose up -d
```

Access n8n at: **http://localhost:5678**

</details>

<br>

## 📊 Usage

### 🎯 **Running the Complete Pipeline**

<div align="center">
  <img src="https://user-images.githubusercontent.com/74038190/212749171-b84692a8-2848-41a2-99a3-5c1778eafc80.gif" width="500">
</div>

#### **1. Data Ingestion Workflow**

Import your workflow into n8n:

1. Open n8n at `http://localhost:5678`
2. Click **"Import from File"**
3. Select `workflows/data_ingestion.json`
4. Configure credentials for Supabase and Gmail

**Workflow Steps:**
```
📁 CSV File Trigger → 🧹 Data Cleaning → ✅ Validation → 💾 Supabase Insert → 📧 Notification
```

#### **2. Regression Analysis Workflow**

```
⏰ Schedule Trigger → 🔍 Fetch Data → 📊 Quadratic Analysis → 💾 Store Results → 📧 Email Report
```

### 📝 **Example: Running Analysis**

```javascript
// Trigger the workflow programmatically
const response = await fetch('http://localhost:5678/webhook/run-regression', {
  method: 'POST',
  headers: { 'Content-Type': 'application/json' },
  body: JSON.stringify({
    dataset: 'customer_churn',
    features: ['age', 'tenure', 'monthly_charges'],
    target: 'churn'
  })
});

const result = await response.json();
console.log('Model Accuracy:', result.accuracy);
```

### 📈 **Interpreting Results**

The pipeline generates comprehensive outputs:

- **📊 Model Coefficients** - Feature importance weights
- **🎯 Accuracy Metrics** - Precision, recall, F1-score
- **📉 Confusion Matrix** - Classification performance
- **📧 Email Report** - Automated summary delivered to inbox

<br>

## 🔧 Configuration

### ⚙️ **n8n Workflow Settings**

<details>
<summary><b>Credential Configuration</b></summary>

**Supabase Credential:**
- Name: `Supabase Production`
- Type: `PostgreSQL`
- Host: From Supabase project settings
- Port: `5432`
- Database: `postgres`
- Username: From connection string
- Password: Your database password
- SSL: Enabled

**Gmail OAuth2 Credential:**
- Name: `Gmail API`
- Type: `OAuth2`
- Client ID: From Google Cloud Console
- Client Secret: From Google Cloud Console
- Scope: `https://www.googleapis.com/auth/gmail.send`

</details>

### 🎛️ **Customization Options**

Edit `config/pipeline.json`:

```json
{
  "model": {
    "type": "logistic_regression",
    "solver": "lbfgs",
    "max_iterations": 1000,
    "regularization": 0.01
  },
  "preprocessing": {
    "scaling": "standard",
    "handle_missing": "median",
    "encode_categorical": true
  },
  "validation": {
    "test_size": 0.2,
    "cross_validation_folds": 5,
    "random_state": 42
  }
}
```

<br>

## 🤝 Contributing

<div align="center">
  <img src="https://user-images.githubusercontent.com/74038190/212284087-bbe7e430-757e-4901-90bf-4cd2ce3e1852.gif" width="500">
</div>

We love contributions! Here's how you can help:

### 🌟 **Contribution Process**

```bash
# 1. Fork the repository
# 2. Create your feature branch
git checkout -b feature/AmazingFeature

# 3. Commit your changes
git commit -m '✨ Add some AmazingFeature'

# 4. Push to the branch
git push origin feature/AmazingFeature

# 5. Open a Pull Request
```

### 📝 **Contribution Guidelines**

- ✅ Follow the existing code style
- ✅ Add tests for new features
- ✅ Update documentation
- ✅ Use conventional commit messages
- ✅ Ensure all tests pass

### 🐛 **Found a Bug?**

[Open an issue](https://github.com/yourusername/logistic-regressionator/issues) with:
- Clear bug description
- Steps to reproduce
- Expected vs actual behavior
- Environment details

<br>

## 📄 License

<div align="center">

**Distributed under the MIT License**

See [`LICENSE`](LICENSE) for more information.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

</div>

<br>

---

<div align="center">

### 🌟 **Star this repo if you find it useful!** 🌟

<img src="https://user-images.githubusercontent.com/74038190/216122041-518ac897-8d92-4c6b-9b3f-ca01dcaf38ee.png" width="200" />

**Made with ❤️ and ☕ by the Logistic Regressionator Team**

<p>
  <a href="https://github.com/yourusername/logistic-regressionator">🏠 Homepage</a> •
  <a href="https://github.com/yourusername/logistic-regressionator/issues">🐛 Report Bug</a> •
  <a href="https://github.com/yourusername/logistic-regressionator/issues">✨ Request Feature</a>
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,14,18,20,24&height=100&section=footer" width="100%"/>

</div>
