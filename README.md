<div align="center">
  <h1 align="center">
    🚄 Travel Companion - 旅行伴侣
  </h1>
  <p align="center">
    一款专注于行程规划、铁路旅行和成本核算的智能旅行助手。
    <br />
    An intelligent travel assistant focusing on detailed planning, railway journeys, and cost management.
  </p>
</div>

<p align="center">
  <a href="#-简体中文">简体中文</a> | <a href="#-english">English</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="License">
  <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg" alt="PRs Welcome">
  <img src="https://img.shields.io/badge/status-planning-lightgrey.svg" alt="Status: Planning">
</p>

---

## 简体中文

### 📌 项目简介

**Travel Companion (旅行伴侣)** 是一个旨在简化旅行规划流程的开源项目。无论你是在策划一次复杂的跨国铁路旅行，还是一个轻松的周末短途，本项目都致力于为你提供一个清晰、智能且用户友好的解决方案。我们特别关注铁路旅行的独特需求，并集成了强大的成本核算工具，帮助你轻松掌控预算。

### ✨ 核心功能

1.  **🗓️ 计划详情安排 (Detailed Itinerary Planning)**
    * **可视化行程创建**：通过时间线或日历视图直观地创建和管理每日行程。
    * **兴趣点(POI)管理**：轻松添加、编辑景点、餐厅、酒店等，并附上笔记、照片和链接。
    * **智能提醒**：根据行程安排，自动推送出发提醒、预订提醒等。
    * **模板与分享**：保存你的行程为模板，或与朋友、家人一键分享。

2.  **🚆 铁路旅程 (Railway Journey Management)**
    * **多站点路线规划**：轻松规划包含多个中途站点的复杂火车旅程。
    * **车次信息查询**：(未来集成)对接各国铁路API，实时查询车次、票价和余票信息。
    * **换乘方案优化**：智能计算最优换乘时间和方案，避免行程延误。
    * **电子票据管理**：集中管理所有电子火车票，告别手忙脚乱。

3.  **💰 成本核算 (Cost Calculation)**
    * **多维度预算设定**：可按总预算、天数、消费类别（交通、住宿、餐饮等）设置预算。
    * **快捷记账**：提供简洁的记账界面，随时随地记录每一笔开销。
    * **可视化报表**：自动生成饼图、折线图等，清晰展示消费结构和趋势。
    * **多人账本(AA制)**：支持团队旅行，轻松计算和分摊费用。

### 🛠️ 技术栈 (设想)

* **前端**: Vue 3 / React 18 (使用 TypeScript) - 备选移动端: Flutter / React Native
* **后端**: FastAPI (Python) / Spring Boot (Java) - 提供高性能的 API 接口
* **数据库**: PostgreSQL - 存储结构化数据, 如用户、行程、账单等
* **缓存**: Redis - 用于缓存热点数据，如车次信息、用户信息
* **部署**: Docker / Kubernetes - 实现容器化部署和弹性伸缩

### 🚀 快速开始

> **注意**: 项目正处于规划阶段，以下为未来实现后的操作指南。

1.  **克隆仓库**
    ```bash
    git clone [https://github.com/your-username/travel-companion.git](https://github.com/your-username/travel-companion.git)
    cd travel-companion
    ```

2.  **安装依赖 (以 Python 后端为例)**
    ```bash
    pip install -r requirements.txt
    ```

3.  **配置环境**
    * 复制 `.env.example` 文件为 `.env`
    * 在 `.env` 文件中填写你的数据库连接信息及其他密钥

4.  **运行项目**
    ```bash
    uvicorn main:app --reload
    ```

### 🗺️ 项目路线图

-   [ ] **Q4 2025**: 完成核心后端 API 开发及数据库设计。
-   [ ] **Q1 2026**: 发布 MVP (最小可行产品) 版本，包含基础的行程规划和记账功能。
-   [ ] **Q2 2026**: 集成首个国家/地区的铁路数据API。
-   [ ] **Q3 2026**: 开发移动端 App。
-   [ ] **长期**: 引入 AI 智能推荐、社交分享、离线模式等高级功能。

### 🤝 如何贡献

我们热烈欢迎任何形式的贡献！无论是代码、文档、设计还是测试，都对我们至关重要。

1.  Fork 本仓库
2.  创建你的特性分支 (`git checkout -b feature/AmazingFeature`)
3.  提交你的修改 (`git commit -m 'Add some AmazingFeature'`)
4.  推送到分支 (`git push origin feature/AmazingFeature`)
5.  提交一个 Pull Request

### ⚖️ 开源协议

本项⽬采⽤ [MIT license](https://opensource.org/licenses/MIT) 开源协议。

---

## English

### 📌 Overview

**Travel Companion** is an open-source project designed to streamline the travel planning process. Whether you're orchestrating a complex, multi-country railway adventure or a simple weekend getaway, this project aims to provide a clear, intelligent, and user-friendly solution. We place a special emphasis on the unique needs of railway travel and integrate powerful cost-management tools to help you keep your budget under control.

### ✨ Core Features

1.  **🗓️ Detailed Itinerary Planning**
    * **Visual Itinerary Creation**: Intuitively create and manage daily schedules using a timeline or calendar view.
    * **Point of Interest (POI) Management**: Easily add and edit attractions, restaurants, hotels, and more, complete with notes, photos, and links.
    * **Smart Reminders**: Automatically receive departure alerts, booking reminders, and other notifications based on your schedule.
    * **Templates & Sharing**: Save your itineraries as templates for future use or share them with friends and family with a single click.

2.  **🚆 Railway Journey Management**
    * **Multi-Stop Route Planning**: Effortlessly plan complex train journeys involving multiple stopovers.
    * **Schedule & Fare Inquiry**: (Future Integration) Connect with national railway APIs to query real-time schedules, fares, and ticket availability.
    * **Transfer Optimization**: Intelligently calculate the best transfer times and options to avoid delays.
    * **E-Ticket Consolidation**: Manage all your electronic train tickets in one place, saying goodbye to last-minute scrambles.

3.  **💰 Cost Calculation**
    * **Multi-Dimensional Budgeting**: Set budgets by total amount, per day, or by category (e.g., transport, lodging, food).
    * **Quick Expense Tracking**: A simple interface to log every expense anytime, anywhere.
    * **Visual Reports**: Automatically generate pie charts, line graphs, and other reports to clearly visualize spending patterns.
    * **Shared Ledgers (Splitting Bills)**: Perfect for group travel, making it easy to calculate and split costs.

### 🛠️ Proposed Tech Stack

* **Frontend**: Vue 3 / React 18 (with TypeScript) - Mobile Alternative: Flutter / React Native
* **Backend**: FastAPI (Python) / Spring Boot (Java) - For high-performance APIs
* **Database**: PostgreSQL - For structured data like users, itineraries, and expenses
* **Cache**: Redis - To cache hot data like train schedules and user information
* **Deployment**: Docker / Kubernetes - For containerized deployment and scaling

### 🚀 Getting Started

> **Note**: This project is currently in the planning phase. The following instructions are a guideline for when it is implemented.

1.  **Clone the repository**
    ```bash
    git clone [https://github.com/your-username/travel-companion.git](https://github.com/your-username/travel-companion.git)
    cd travel-companion
    ```

2.  **Install dependencies (example for Python backend)**
    ```bash
    pip install -r requirements.txt
    ```

3.  **Configure your environment**
    * Copy `.env.example` to `.env`
    * Fill in your database connection details and other secrets in the `.env` file

4.  **Run the project**
    ```bash
    uvicorn main:app --reload
    ```

### 🗺️ Roadmap

-   [ ] **Q4 2025**: Complete core backend API development and database design.
-   [ ] **Q1 2026**: Release the MVP (Minimum Viable Product) version with basic itinerary and expense features.
-   [ ] **Q2 2026**: Integrate the first national/regional railway data API.
-   [ ] **Q3 2026**: Develop the mobile application.
-   [ ] **Long-term**: Introduce advanced features like AI-powered recommendations, social sharing, and offline mode.

### 🤝 Contributing

Contributions of any kind are welcome! Whether it's code, documentation, design, or testing, your help is invaluable.

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

### ⚖️ License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
