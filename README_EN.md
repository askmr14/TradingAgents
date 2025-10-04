# TradingAgents Chinese Enhanced Edition

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Python](https://img.shields.io/badge/Python-3.10%2B-blue.svg)](https://www.python.org/)
[![Version](https://img.shields.io/badge/Version-cn--0.1.15-green.svg)](./VERSION)
[![Documentation](https://img.shields.io/badge/docs-Chinese%20Docs-green.svg)](./docs/)
[![Original](https://img.shields.io/badge/Based%20on-TauricResearch/TradingAgents-orange.svg)](https://github.com/TauricResearch/TradingAgents)

> 🚀 **Latest Version cn-0.1.15**: Major upgrades for developer experience and the LLM ecosystem! Added Baidu Qianfan model support, a complete dev toolchain, academic research resources, and enterprise-grade workflow standards!
>
> 🎯 **Core Features**: Native OpenAI support | Full Google AI integration | Custom endpoint configuration | Smart model selection | Multi-LLM provider support | Persistent model selection | Dockerized deployment | Professional report export | Full A-share support | Chinese localization

A **Chinese financial trading decision framework** based on multi-agent large language models. Optimized for Chinese users, with full A-share/HK/US stock analysis capabilities.

## 🙏 Tribute to the Original Project

Thanks to the [Tauric Research](https://github.com/TauricResearch) team for creating the revolutionary multi-agent trading framework [TradingAgents](https://github.com/TauricResearch/TradingAgents)!

**🎯 Our Mission**: Provide a complete localized experience for Chinese users, support A-share/HK markets, integrate domestic LLMs, and promote the adoption of AI finance within the Chinese-speaking community.

## 🆕 v0.1.15 Major Update

### 🤖 Big Upgrade to the LLM Ecosystem

- **Baidu Qianfan Support**: Full integration of Baidu Qianfan (ERNIE) LLMs
- **LLM Adapter Refactor**: Unified OpenAI-compatible adapter architecture
- **Multi-vendor Support**: More domestic LLM providers supported
- **Integration Guides**: Complete LLM integration docs and testing tools

### 📚 Academic Research Support

- **TradingAgents Paper**: Full Chinese translation and in-depth interpretation
- **Technical Blogs**: Detailed technical analysis and implementation insights
- **Academic Materials**: PDF papers and related research resources
- **Citation Support**: Standard academic citation formats and references

### 🛠️ Developer Experience Upgrades

- **Dev Workflow**: Standardized development process and branch management rules
- **Install Verification**: Complete installation tests and verification scripts
- **Docs Refactor**: Structured documentation system and quick start guides
- **PR Templates**: Standardized PR template and code review process

### 🔧 Enterprise-grade Tooling

- **Branch Protection**: GitHub branch protection policies and security rules
- **Emergency Procedures**: Complete incident response and recovery procedures
- **Test Framework**: Enhanced test coverage and validation tools
- **Deployment Guide**: Enterprise deployment and configuration management

## 📋 v0.1.14 Recap

### 👥 User Access Management System

- **Full User Management**: New user registration, login, and permissions control
- **Role-based Permissions**: Multi-level user roles and access control
- **Session Management**: Secure user sessions and state handling
- **User Activity Logs**: Full audit and operation logs

### 🔐 Web Authentication System

- **Login Component**: Modern login UI
- **Auth Manager**: Unified authentication and authorization management
- **Security Enhancements**: Password hashing, session security, etc.
- **User Dashboard**: Personalized activity dashboard

### 🗄️ Data Management Optimization

- **MongoDB Integration**: Improved connection and data management
- **Data Directory Restructure**: Optimized storage structure and management
- **Data Migration Scripts**: Complete migration and backup tools
- **Cache Optimization**: Faster loading and analysis-result caching

### 🧪 Test Coverage Enhancements

- **Functional Test Scripts**: 6 new targeted test scripts
- **Tool Handler Tests**: Verification for Google tool handler fixes
- **Auto-hide Onboarding Tests**: UI interaction tests
- **Online Tool Config Tests**: Tool configuration and selection logic
- **Real-world Scenario Tests**: End-to-end tests for real usage
- **US Stock Independence Test**: Independence verification for US analysis

---

## 🆕 v0.1.13 Major Update

### 🤖 Native OpenAI Endpoint Support

- **Custom OpenAI Endpoint**: Configure any OpenAI-compatible API endpoint
- **Flexible Model Choice**: Use any OpenAI-format model, not limited to official ones
- **Smart Adapter**: New native OpenAI adapter for better compatibility and performance
- **Config Management**: Unified endpoint and model configuration system

### 🧠 Full Google AI Ecosystem Integration

- **3 Google AI Packages**: langchain-google-genai, google-generativeai, google-genai
- **9 Validated Models**: gemini-2.5-pro, gemini-2.5-flash, gemini-2.0-flash, etc.
- **Google Tool Handler**: Dedicated tool-call handler for Google AI
- **Smart Downgrade**: Auto fallback to basic features on advanced failure

### 🔧 LLM Adapter Architecture Optimization

- **GoogleOpenAIAdapter**: OpenAI-compatible adapter for Google AI
- **Unified Interface**: One calling interface across all LLM providers
- **Improved Error Handling**: Better exception handling and auto retries
- **Performance Monitoring**: LLM call performance metrics and stats

### 🎨 Web UI Intelligence Optimizations

- **Smart Model Selection**: Auto-choose the best model based on availability
- **KeyError Fixes**: Fully resolved KeyError issues in model selection
- **UI Responsiveness**: Faster switching and better UX
- **Helpful Errors**: More friendly error messages and suggestions

## 🆕 v0.1.12 Major Update

### 🧠 Intelligent News Analysis Module

- **AI News Filter**: Relevance scoring and quality evaluation
- **Multi-layer Filtering**: Basic / Enhanced / Integrated three-level pipeline
- **News Quality Assessment**: Auto-detect and filter low-quality/duplicate/irrelevant news
- **Unified News Tool**: Aggregate multiple sources with a single interface

### 🔧 Fixes and Optimizations

- **DashScope Adapter Fix**: Tool-call compatibility issues resolved
- **DeepSeek Infinite Loop**: Fixed endless loop in news analyst
- **LLM Tool Calling**: More reliable tool invocations
- **News Retriever**: Stronger data fetching and processing

### 📚 Tests and Docs

- **Broad Test Coverage**: 15+ new test files covering all new features
- **Technical Write-ups**: 8 new technical analyses and fix reports
- **User Guides**: News filtering how-to and best practices
- **Demo Scripts**: Full demo of news filtering

### 🗂️ Project Structure

- **Docs Categorization**: Docs organized under `docs` by function
- **Examples Folder**: Demos consolidated in `examples`
- **Clean Root**: Cleaner root directory for a more professional project

## 🎯 Core Features

### 🤖 Multi-agent Collaboration

- **Division of Labor**: Fundamental, technical, news, and social-media analysts
- **Structured Debate**: Bullish/bearish researchers for deep analysis
- **Intelligent Decisions**: Trader makes final recommendation from all inputs
- **Risk Management**: Multi-layer risk assessment and controls

## 🖥️ Web UI

### 📸 Screenshots

> 🎨 **Modern Web UI**: Streamlit-based responsive web app for intuitive stock analysis

#### 🏠 Home – Analysis Configuration

![1755003162925](images/README/1755003162925.png)

![1755002619976](images/README/1755002619976.png)

*Smart config panel with multi-market analysis, five research-depth levels*

#### 📊 Live Analysis Progress

![1755002731483](images/README/1755002731483.png)

*Live progress tracking, visualized workflow, intelligent time estimates*

#### 📈 Results Display

![1755002901204](images/README/1755002901204.png)

![1755002924844](images/README/README/1755002924844.png)

![1755002939905](images/README/1755002939905.png)

![1755002968608](images/README/1755002968608.png)

![1755002985903](images/README/1755002985903.png)

![1755003004403](images/README/1755003004403.png)

![1755003019759](images/README/1755003019759.png)

![1755003033939](images/README/1755003033939.png)

![1755003048242](images/README/1755003048242.png)

![1755003064598](images/README/1755003064598.png)

![1755003090603](images/README/1755003090603.png)

*Professional investment reports, multidimensional results, one-click export*

### 🎯 Key UI Capabilities

#### 📋 **Smart Analysis Configuration**

- **🌍 Multi-market**: US, A-share, and HK in one place
- **🎯 5 Depth Levels**: From 2-minute quick views to 25-minute in-depth research
- **🤖 Agent Selection**: Technical, fundamental, news, social media analysts
- **📅 Flexible Time**: Analyze any point in historical time

#### 🚀 **Live Progress Tracking**

- **📊 Visual Progress**: See analysis status and remaining time
- **🔄 Step Detection**: Auto-detect current analysis stage
- **⏱️ Accurate ETA**: Data-driven time estimates
- **💾 Persistence**: Refresh the page without losing progress

#### 📈 **Professional Results**

- **🎯 Decisions**: Clear Buy/Hold/Sell
- **📊 Multidimensional**: Technical + Fundamental + News
- **🔢 Quant Metrics**: Confidence, risk score, target price
- **📄 Reports**: Export to Markdown/Word/PDF

#### 🤖 **Multi-LLM Model Management**

- **🌐 4 Providers**: DashScope, DeepSeek, Google AI, OpenRouter
- **🎯 60+ Models**: From budget to flagship
- **💾 Persistent Config**: Store settings in URL; survive refresh
- **⚡ Quick Switch**: One-click top 5 popular models

### 🎮 Web UI Guide

#### 🚀 **Quick Start**

1. **Run App**: `python start_web.py` or `docker-compose up -d`
2. **Open**: `http://localhost:8501`
3. **Choose Model**: Pick provider and model in sidebar
4. **Enter Ticker**: e.g., AAPL, 000001, 0700.HK
5. **Select Depth**: Level 1–5
6. **Start**: Click "🚀 Start Analysis"
7. **View**: Follow live progress and results
8. **Export**: One-click professional report export

#### 📊 **Supported Ticker Formats**

- **🇺🇸 US**: `AAPL`, `TSLA`, `MSFT`, `NVDA`, `GOOGL`
- **🇨🇳 A-share**: `000001`, `600519`, `300750`, `002415`
- **🇭🇰 HK**: `0700.HK`, `9988.HK`, `3690.HK`, `1810.HK`

#### 🎯 **Research Depth**

- **Level 1 (2–4 min)**: Quick overview, basic technicals
- **Level 2 (4–6 min)**: Standard analysis, technical + fundamentals
- **Level 3 (6–10 min)**: Deeper with news sentiment ⭐ **Recommended**
- **Level 4 (10–15 min)**: Full analysis with multi-round debates
- **Level 5 (15–25 min)**: Deepest analysis, full research report

#### 💡 **Tips**

- **🔄 Safe Refresh**: Refresh anytime; progress persists
- **📱 Mobile**: Works on phones/tablets
- **🎨 Dark Mode**: Auto theme adaptation
- **⌨️ Shortcut**: Press Enter to submit
- **📋 History**: Recent configs auto-saved

> 📖 **Detailed Guide**: See [🖥️ Web Interface Detailed Guide](docs/usage/web-interface-detailed-guide.md)

## 🎯 Feature Matrix

### 🚀 Intelligent News Analysis ✨ **v0.1.12 Upgrade**

| Feature                    | Status     | Details                                        |
| -------------------------- | ---------- | ---------------------------------------------- |
| **🧠 Intelligent News**    | 🆕 v0.1.12 | AI filtering, quality scoring, relevance       |
| **🔧 News Filters**        | 🆕 v0.1.12 | Multi-layer: basic/enhanced/integrated         |
| **📰 Unified News Tool**   | 🆕 v0.1.12 | Aggregated sources, unified API, smart search  |
| **🤖 Multi-LLM Providers** | 🆕 v0.1.11 | 4 providers, 60+ models, smart categorization  |
| **💾 Persistent Models**   | 🆕 v0.1.11 | URL-based persistence, shareable configs       |
| **🎯 Quick Buttons**       | 🆕 v0.1.11 | One-click popular model switching              |
| **📊 Live Progress**       | ✅ v0.1.10 | Async tracking, step detection, ETA            |
| **💾 Smart Sessions**      | ✅ v0.1.10 | Persistent state, auto-downgrade, cross-page   |
| **🎯 One-click Report**    | ✅ v0.1.10 | Open results instantly post-analysis           |
| **🖥️ Streamlit UI**       | ✅ Full     | Modern, responsive, real-time visualization    |
| **⚙️ Config Management**   | ✅ Full     | API key mgmt, model selection, parameters      |

### 🎨 CLI UX ✨ **v0.1.9 Improvements**

| Feature                      | Status     | Details                                  |
| --------------------------- | ---------- | ---------------------------------------- |
| **🖥️ UI/Log Separation**    | ✅ Full     | Clean UI; technical logs isolated        |
| **🔄 Smart Progress**       | ✅ Full     | Multi-stage progress; no duplicate hints |
| **⏱️ Time Estimates**       | ✅ Full     | Per-stage ETA display                    |
| **🌈 Rich Output**          | ✅ Full     | Colored progress, status icons, visuals  |

### 🧠 LLM Model Support ✨ **v0.1.13 Comprehensive**

| Provider         | Supported Models                  | Highlights                     | New |
| ---------------- | --------------------------------- | ------------------------------ | --- |
| **🇨🇳 Alibaba**  | qwen-turbo/plus/max               | Chinese-optimized, cost-effective | ✅ Integrated |
| **🇨🇳 DeepSeek** | deepseek-chat                     | Tool use, great value          | ✅ Integrated |
| **🌍 Google AI** | **9 validated models**            | Latest Gemini 2.5 series       | 🆕 Upgraded |
| ├─**Flagship**  | gemini-2.5-pro/flash              | Latest, ultra-fast             | 🆕 New |
| ├─**Stable**    | gemini-2.0-flash                  | Recommended balance            | 🆕 New |
| ├─**Classic**   | gemini-1.5-pro/flash              | Stable, high-quality analysis  | ✅ Integrated |
| └─**Light**     | gemini-2.5-flash-lite             | Lightweight, fast              | 🆕 New |
| **🌐 Native OpenAI** | **Custom endpoint**            | Any OpenAI-compatible endpoint | 🆕 New |
| **🌐 OpenRouter** | **60+ aggregated models**         | One API for major models       | ✅ Integrated |
| ├─**OpenAI**    | o4-mini-high, o3-pro, GPT-4o      | Latest o-series, reasoning     | ✅ Integrated |
| ├─**Anthropic** | Claude 4 Opus/Sonnet/Haiku        | Top performance variants       | ✅ Integrated |
| ├─**Meta**      | Llama 4 Maverick/Scout            | Latest Llama 4 series          | ✅ Integrated |
| └─**Custom**    | Any OpenRouter model ID           | Unlimited extensibility        | ✅ Integrated |

**🎯 Quick Picks**: 5 popular models | **💾 Persistence**: URL parameters | **🔄 Smart Switching**: One click across providers

### 📊 Data Sources & Markets

| Market          | Data Sources                | Coverage                                      |
| --------------- | --------------------------- | --------------------------------------------- |
| **🇨🇳 A-share** | Tushare, AkShare, Tongdaxin | Shanghai/Shenzhen, real-time quotes, financials |
| **🇭🇰 HK**      | AkShare, Yahoo Finance      | HKEX, real-time quotes, fundamentals          |
| **🇺🇸 US**      | FinnHub, Yahoo Finance      | NYSE/NASDAQ, real-time data                   |
| **📰 News**     | Google News                 | Real-time, multi-language                     |

### 🤖 Agent Teams

**Analysts**: 📈 Market | 💰 Fundamentals | 📰 News | 💬 Sentiment  
**Researchers**: 🐂 Bullish | 🐻 Bearish | 🎯 Trader  
**Management**: 🛡️ Risk Manager | 👔 Research Director

## 🚀 Quick Start

### 🐳 Docker Deployment (Recommended)

```bash
# 1. Clone
git clone https://github.com/hsliuping/TradingAgents-CN.git
cd TradingAgents-CN

# 2. Env vars
cp .env.example .env
# Edit .env and add your API keys

# 3. Start
docker-compose up -d --build      # first time or after code changes
docker-compose up -d              # normal start

# Smart start
# Windows
powershell -ExecutionPolicy Bypass -File scripts\smart_start.ps1
# Linux/Mac
chmod +x scripts/smart_start.sh && ./scripts/smart_start.sh

# 4. Open
# Web: http://localhost:8501
```

### 💻 Local Deployment

```bash
# 1. Upgrade pip (important)
python -m pip install --upgrade pip

# 2. Install deps
pip install -e .

# 3. Run
python start_web.py

# 4. Open http://localhost:8501
```

### 📊 Start Analyzing

1. **Choose Model**: DeepSeek V3 / Qwen / Gemini
2. **Enter Ticker**: `000001` (A-share) / `AAPL` (US) / `0700.HK` (HK)
3. **Start**: Click "🚀 Start Analysis"
4. **Track**: Watch live progress and steps
5. **View Report**: Click "📊 View Analysis Report"
6. **Export**: Word/PDF/Markdown supported

## 🔐 User Access Control

### 🔑 Default Accounts

Created automatically on first run:

| Username | Password  | Role   | Permission Notes                                   |
|---------|-----------|--------|----------------------------------------------------|
| **admin** | **admin123** | Admin  | Full system access, user mgmt, system config        |
| **user**  | **user123**  | User   | Stock analysis, view reports, basic features        |

> ⚠️ **Security**: Change default passwords after first login!

### 🛡️ Permission Framework

- **🔐 Login Auth**: Username/password authentication
- **👥 Roles**: Admin, user, etc.
- **⏰ Sessions**: Auto-timeout and secure logout
- **📊 Audit**: Full activity logging

### 🛠️ User Management Tools

**Windows (PowerShell)**

```powershell
.\scripts\user_manager.ps1 list
.\scripts\user_manager.ps1 change-password admin
.\scripts\user_manager.ps1 create newuser trader
.\scripts\user_manager.ps1 delete olduser

# or batch
.\scripts\user_manager.bat list
```

**Python (cross-platform)**

```bash
python scripts/user_password_manager.py list
python scripts/user_password_manager.py change-password admin
python scripts/user_password_manager.py create newuser --role trader
python scripts/user_password_manager.py delete olduser
python scripts/user_password_manager.py reset
```

**Config File**: `web/config/users.json`  
More: [scripts/USER_MANAGEMENT.md](scripts/USER_MANAGEMENT.md)

**Current Limitations**

- ❌ No online self-registration
- ❌ No role mgmt in Web UI
- ✅ Full CLI user management
- ✅ Full permission framework

---

## 🎯 Advantages

- **🧠 AI News Analysis**: v0.1.12—AI-driven filtering and quality scoring
- **🔧 Multi-layer Filters**: Basic, Enhanced, Integrated
- **📰 Unified News Tool**: Multi-source, single interface
- **🆕 Multi-LLM**: v0.1.11—4 providers, 60+ models
- **💾 Persistent Config**: URL param storage
- **🎯 Quick Switching**: 5 hot models
- **🆕 Live Progress**: v0.1.10 async tracking
- **💾 Smart Sessions**: Refresh-safe
- **🔐 User Access**: v0.1.14 full auth and RBAC
- **🇨🇳 China-optimized**: A-share/HK data + domestic LLMs + Chinese UI
- **🐳 Containerized**: One-click Docker deploy
- **📄 Pro Reports**: Multi-format export
- **🛡️ Robust**: Multi-source, smart fallback, error recovery

## 🔧 Tech Stack

**Core**: Python 3.10+ | LangChain | Streamlit | MongoDB | Redis  
**Models**: DeepSeek V3 | Alibaba Qwen | Google AI | OpenRouter (60+ models) | OpenAI  
**Data**: Tushare | AkShare | FinnHub | Yahoo Finance  
**Deploy**: Docker | Docker Compose | Local

## 📚 Docs & Support

- **Docs**: [docs/](./docs/) — Installation, usage, API
- **Troubleshooting**: [docs/troubleshooting/](./docs/troubleshooting/)
- **Changelog**: [CHANGELOG.md](./docs/releases/CHANGELOG.md)
- **Quickstart**: [QUICKSTART.md](./QUICKSTART.md)

## 🆚 Chinese Enhancements

**Beyond the original**: Intelligent news analysis | Multi-layer news filtering | News quality scoring | Unified news tool | Multi-LLM integration | Persistent model selection | Quick switch buttons | Live progress display | Smart session management | Chinese UI | A-share data | Domestic LLMs | Docker deployment | Professional report export | Unified logging | Web config UI | Cost optimization

**Docker services included**:

- 🌐 **Web App**: TradingAgents-CN
- 🗄️ **MongoDB**: Persistent storage
- ⚡ **Redis**: High-speed cache
- 📊 **MongoDB Express**: DB admin UI
- 🎛️ **Redis Commander**: Cache admin UI

#### 💻 Option 2: Local Deployment

**Use cases**: Dev environment, custom config, offline

### Requirements

- Python 3.10+ (3.11 recommended)
- 4GB+ RAM (8GB+ recommended)
- Stable internet

### Installation

```bash
git clone https://github.com/hsliuping/TradingAgents-CN.git
cd TradingAgents-CN

python -m venv env
# Windows
env\Scripts\activate
# Linux/macOS
source env/bin/activate

python -m pip install --upgrade pip
pip install -r requirements.txt
# or install project
pip install -e .
```

### Configure API Keys

```bash
# Copy template
cp .env.example .env

# Required keys
DASHSCOPE_API_KEY=your_dashscope_api_key_here
FINNHUB_API_KEY=your_finnhub_api_key_here

# Recommended (A-share)
TUSHARE_TOKEN=your_tushare_token_here
TUSHARE_ENABLED=true

# Optional models
GOOGLE_API_KEY=your_google_api_key_here
DEEPSEEK_API_KEY=your_deepseek_api_key_here

# DB (optional performance)
MONGODB_ENABLED=false
REDIS_ENABLED=false
MONGODB_HOST=localhost
MONGODB_PORT=27017
REDIS_HOST=localhost
REDIS_PORT=6379

# Docker mode
# MONGODB_HOST=mongodb
# REDIS_HOST=redis
```

### Deployment Modes

_Local:_
```bash
MONGODB_ENABLED=true
REDIS_ENABLED=true
MONGODB_HOST=localhost
MONGODB_PORT=27017
REDIS_HOST=localhost
REDIS_PORT=6379
```

_Docker:_
```bash
MONGODB_ENABLED=true
REDIS_ENABLED=true
MONGODB_HOST=mongodb
MONGODB_PORT=27017
REDIS_HOST=redis
REDIS_PORT=6379
```

> 💡 Tips:
> - Local: start MongoDB/Redis manually
> - Docker: services start via docker-compose
> - Port conflicts: change docker-compose.yml mappings if needed

### Databases (MongoDB + Redis)

**Capabilities**

- **📊 Stock Cache**: Reduce API calls, faster responses
- **🔄 Smart Fallback**: MongoDB → API → Local cache
- **⚡ High-performance Cache**: Redis for hot data
- **🛡️ Persistence**: MongoDB for history and offline analysis

**Docker (Recommended)**

```bash
docker-compose up -d --build
# Web 8501, MongoDB 27017, Redis 6379, admin UIs 8081/8082
```

**Local DB Only**

```bash
docker-compose up -d mongodb redis mongo-express redis-commander
docker-compose ps
docker-compose down
```

**Native Local Installs**

```bash
mongod --dbpath ./data/mongodb
redis-server
```

**Env Vars**

```bash
MONGODB_HOST=localhost
MONGODB_PORT=27017
MONGODB_DATABASE=trading_agents
MONGODB_USERNAME=admin
MONGODB_PASSWORD=your_password

REDIS_HOST=localhost
REDIS_PORT=6379
REDIS_PASSWORD=your_redis_password
REDIS_DB=0
```

**Config File Example**

```python
DATABASE_CONFIG = {
    'mongodb': {
        'host': 'localhost',
        'port': 27017,
        'database': 'trading_agents',
        'username': 'admin',
        'password': 'your_password'
    },
    'redis': {
        'host': 'localhost',
        'port': 6379,
        'password': 'your_redis_password',
        'db': 0
    }
}
```

**MongoDB Features**: basics, historical price cache, analysis results, user configs, auto sync  
**Redis Features**: real-time price cache, API response cache, session state, hot preload, distributed locks

**Data Retrieval Order**

```
1) Redis cache (ms)
2) MongoDB store (s)
3) Tongdaxin API (s)
4) Local file cache (fallback)
5) Error
```

**Fallback Config**

```python
ENABLE_MONGODB=true
ENABLE_REDIS=true
ENABLE_FALLBACK=true

# TTLs (seconds)
REDIS_CACHE_TTL=300
MONGODB_CACHE_TTL=3600
```

**Perf Tuning (Prod)**

```bash
MONGODB_MAX_POOL_SIZE=50
MONGODB_MIN_POOL_SIZE=5
MONGODB_MAX_IDLE_TIME=30000

REDIS_MAX_CONNECTIONS=20
REDIS_CONNECTION_POOL_SIZE=10
REDIS_SOCKET_TIMEOUT=5
```

**Admin Tools**

```bash
python scripts/setup/init_database.py
python scripts/validation/check_system_status.py
python scripts/maintenance/cleanup_cache.py --days 7
```

**Troubleshooting Highlights**

1) **Windows 10 ChromaDB Issue**

```
MEMORY_ENABLED=false
# or use scripts\fix_chromadb_win10.ps1
# run PowerShell as Administrator
```

See: `docs/troubleshooting/windows10-chromadb-fix.md`

2) **MongoDB Connection**

```bash
docker-compose logs mongodb
docker-compose restart mongodb
# or check processes / restart service
```

3) **Redis Timeout**

```bash
redis-cli ping
redis-cli flushdb
```

> 💡 Even without DBs, the system runs (direct API mode). DB config is optional for performance.

> 📚 More: [Database Architecture](docs/architecture/database-architecture.md)

### 📤 Report Export

**Formats**

- **📄 Markdown (.md)**
- **📝 Word (.docx)**
- **📊 PDF (.pdf)**

**Contents**

- 🎯 Decision summary (Buy/Hold/Sell, confidence, risk)
- 📊 Detailed analysis (technical, fundamentals, sentiment, news)
- ⚠️ Risk disclaimer
- 📋 Configuration & model info

**How-to**

1. After analysis, find “📤 Export Report”
2. Choose Markdown/Word/PDF
3. Click export to download

**Dependencies**

```bash
pip install markdown pypandoc
# install pandoc + wkhtmltopdf via your OS package manager
```

### 🚀 Run the App

**Docker**

```bash
# App, DB, and cache already running
# Web: http://localhost:8501
# Mongo Express: 8081
# Redis Commander: 8082
docker-compose ps
docker-compose logs -f web
```

**Local**

```bash
# activate venv, install with: pip install -e .
python start_web.py
# or
python web/run_web.py
# or
streamlit run web/app.py
```

**Web Highlights**

- 🇺🇸 US: AAPL, TSLA, NVDA…
- 🇨🇳 A-shares: 000001, 600519, 300750…
- 📊 Real-time A-share via Tongdaxin
- 🤖 Agent selection
- 📤 Export to Markdown/Word/PDF
- 🎯 5 research depths (2–25 minutes)
- 🔄 Live progress
- 📈 Structured outputs (decision, target price, confidence, risk)
- 🇨🇳 Fully Chinese UI

**Depth Levels**

- **L1 – Quick** (2–4 min)
- **L2 – Basic** (4–6 min)
- **L3 – Standard** (6–10 min) – Recommended
- **L4 – Deep** (10–15 min)
- **L5 – Full** (15–25 min)

### 💻 Programmatic Usage (for Developers)

```python
from tradingagents.graph.trading_graph import TradingAgentsGraph
from tradingagents.default_config import DEFAULT_CONFIG

# Configure Alibaba DashScope
config = DEFAULT_CONFIG.copy()
config["llm_provider"] = "dashscope"
config["deep_think_llm"] = "qwen-plus"      # deep analysis
config["quick_think_llm"] = "qwen-turbo"    # quick tasks

# Create the trading agent graph
ta = TradingAgentsGraph(debug=True, config=config)

# Analyze a ticker (e.g., Apple)
state, decision = ta.propagate("AAPL", "2024-01-15")

print(f"Action: {decision['action']}")
print(f"Confidence: {decision['confidence']:.1%}")
print(f"Risk Score: {decision['risk_score']:.1%}")
print(f"Reasoning: {decision['reasoning']}")
```

**Quick Demos**

```bash
# Alibaba DashScope demos
python examples/dashscope/demo_dashscope_chinese.py
python examples/dashscope/demo_dashscope.py
python examples/dashscope/demo_dashscope_simple.py

# OpenAI demo (requires external API)
python examples/openai/demo_openai.py

# Integration test
python tests/integration/test_dashscope_integration.py
```

### 📁 Data Directory Configuration

```bash
# View current data directory
python -m cli.main data-config --show

# Set custom data directory
python -m cli.main data-config --set /path/to/your/data

# Reset to default
python -m cli.main data-config --reset
```

**Environment Variables**

```bash
# Windows
set TRADING_AGENTS_DATA_DIR=C:\MyTradingData
# Linux/macOS
export TRADING_AGENTS_DATA_DIR=/home/user/trading_data
```

**Programmatic**

```python
from tradingagents.config_manager import ConfigManager

cm = ConfigManager()
cm.set_data_directory("/path/to/data")
print(f"Data directory: {cm.get_data_directory()}")
```

**Priority**: Program setting > Environment variable > Config file > Default

### Interactive CLI

```bash
python -m cli.main
```

## 🎯 **Fast Navigation** - Find what you need

| I want to…      | Recommended Document                                    | Time |
| --------------- | -------------------------------------------------------- | ---- |
| **Get started** | [🚀 Quick Start](docs/overview/quick-start.md)           | 10m  |
| **Understand**  | [🏛️ Architecture](docs/architecture/system-architecture.md) | 15m  |
| **See code**    | [📚 Basic Examples](docs/examples/basic-examples.md)     | 20m  |
| **Fix issues**  | [🆘 FAQ](docs/faq/faq.md)                                 | 5m   |
| **Go deep**     | [📁 Full Docs Index](#-full-documentation-system--highlights) | 2h+  |

> 💡 Our `docs/` include **50,000+ Chinese characters** of detailed content—this is the biggest difference from upstream!

## 📚 Full Documentation System – Highlights

> **🌟 Major difference from upstream!** We built an industry-leading Chinese documentation system for a financial AI framework: **50,000+ characters**, **20+** pro docs, **100+** code samples.

### 🎯 Why Our Docs?

| Dimension        | Upstream TradingAgents | 🚀 **Chinese Enhanced**           |
| ---------------- | ---------------------- | --------------------------------- |
| **Language**     | English basics         | **Full Chinese system**           |
| **Depth**        | Brief intro            | **Deep technical breakdowns**     |
| **Architecture** | Conceptual             | **Detailed designs + diagrams**   |
| **Guides**       | Basic examples         | **Beginner → Expert full pathway**|
| **Troubleshoot** | None                   | **Detailed FAQ + solutions**      |
| **Examples**     | Limited                | **100+ practical examples**       |

### 📖 Docs by Learning Path

- **Beginner Path**: Overview → Installation → Quick Start → Basic Examples  
- **Architecture Path**: System Architecture → Agent Architecture → Data Flow → Graph Structure  
- **Agent Deep Dive**: Analysts → Researchers → Trader → Risk Management → Managers  
- **Data Topics**: Sources → Processing → Caching  
- **Config & Tuning**: Config Guide → LLM Config  
- **Advanced**: Basic + Advanced Examples  
- **Help**: FAQ

(Directory tree preserved as in original.)

## 💰 Cost Control

**Typical Costs**

- **Economy**: $0.01–0.05/run (gpt-4o-mini)
- **Standard**: $0.05–0.15/run (gpt-4o)
- **High-Accuracy**: $0.10–0.30/run (gpt-4o + debates)

**Optimization Example**

```python
cost_optimized_config = {
    "deep_think_llm": "gpt-4o-mini",
    "quick_think_llm": "gpt-4o-mini",
    "max_debate_rounds": 1,
    "online_tools": False  # use cached data
}
```

## 🤝 Contributing

We welcome contributions:

- 🐛 **Bug Fixes**
- ✨ **New Features**
- 📚 **Docs Improvements**
- 🌐 **Localization**
- 🎨 **Code Optimization**

**Process**

1. Fork
2. Create feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit (`git commit -m 'Add some AmazingFeature'`)
4. Push (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

**Contributors**: See **[🤝 Contributors](CONTRIBUTORS.md)**

## 📄 License

Open-sourced under Apache 2.0. See [LICENSE](LICENSE).

**License Notes**

- ✅ Commercial use
- ✅ Modification & distribution
- ✅ Private use
- ✅ Patent use
- ❗ Keep copyright notices
- ❗ Include the license copy

## 🙏 Acknowledgements

### 🌟 Upstream Respect

We thank the [Tauric Research](https://github.com/TauricResearch) team:

- **🎯 Vision**: Forward-looking innovation in AI finance
- **💎 Code**: Valuable open-source contributions
- **🏗️ Architecture**: Elegant, scalable multi-agent design
- **💡 Pioneering**: Cutting-edge AI + finance integration
- **🔄 Ongoing Work**: Continuous maintenance and improvement

### 🤝 Community Thanks

Thanks to all contributors and users of TradingAgents-CN! See **[📋 Contributors](CONTRIBUTORS.md)**.

Including (but not limited to):

- 🐳 **Docker** — deployment optimization
- 📄 **Report Export** — multi-format output
- 🐛 **Bug Fixes** — stability improvements
- 🔧 **Code Optimization** — UX enhancements
- 📝 **Docs** — guides and tutorials
- 🌍 **Community** — feedback and advocacy

**Special thanks**: The upstream [TradingAgents](https://github.com/TauricResearch/TradingAgents) project for the solid foundation. We respect Apache 2.0 and the value of every line of code.

### 🇨🇳 Our Motivation

- **🌉 Spread Technology** in China
- **🎓 Education** for AI finance
- **🤝 Cultural Bridge** between communities
- **🚀 Innovation** in Chinese fintech

### 🌍 Open Source Community

We commit to:

- **Respect** the original IP and license
- **Contribute Back** improvements
- **Continuous Improvement** of the CN edition
- **Open Collaboration** with upstream and global devs

## 📈 Version History

- **v0.1.13** (2025-08-02): 🤖 Native OpenAI + full Google AI integration ✨ **Latest version**
- **v0.1.12** (2025-07-29): 🧠 News module + structure optimization
- **v0.1.11** (2025-07-27): 🤖 Multi-LLM + persistent selection
- **v0.1.10** (2025-07-18): 🚀 Live progress + smart sessions
- **v0.1.9** (2025-07-16): 🎯 CLI UX + unified logging
- **v0.1.8** (2025-07-15): 🎨 Web UI polish
- **v0.1.7** (2025-07-13): 🐳 Docker + report export
- **v0.1.6** (2025-07-11): 🔧 DashScope fixes + data source upgrade
- **v0.1.5** (2025-07-08): 📊 DeepSeek support
- **v0.1.4** (2025-07-05): 🏗️ Architecture + config refactor
- **v0.1.3** (2025-06-28): 🇨🇳 Full A-share support
- **v0.1.2** (2025-06-15): 🌐 Web UI + config mgmt
- **v0.1.1** (2025-06-01): 🧠 Domestic LLM integration

📋 **Changelog**: [CHANGELOG.md](./docs/releases/CHANGELOG.md)

## 📞 Contact

- **GitHub Issues**: [Submit issues & ideas](https://github.com/hsliuping/TradingAgents-CN/issues)
- **Email**: hsliup@163.com
- QQ Group: 782124367
- **Upstream**: [TauricResearch/TradingAgents](https://github.com/TauricResearch/TradingAgents)
- **Docs**: [Full Docs Index](docs/)

## ⚠️ Risk Notice

**Important**: This framework is for research and education only and is **not** financial advice.

- 📊 Trading performance varies
- 🤖 LLM predictions are uncertain
- 💰 Investing carries risk
- 👨‍💼 Consult a professional advisor

---

<div align="center">

**🌟 If this project helps you, please give us a Star!**

[⭐ Star this repo](https://github.com/hsliuping/TradingAgents-CN) | [🍴 Fork this repo](https://github.com/TauricResearch/TradingAgents/fork) | [📖 Read the docs](./docs/)

</div>
