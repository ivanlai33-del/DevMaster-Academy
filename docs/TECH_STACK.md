# DevMaster Academy - 技術棧詳情

## 📦 完整技術棧

### 前端技術棧

```yaml
框架和構建:
  ├─ React 18.2.0
  ├─ TypeScript 5.1.6
  ├─ Vite 4.4.9
  └─ Node.js 18 LTS

UI 和樣式:
  ├─ Tailwind CSS 3.3.3
  ├─ shadcn/ui (組件庫)
  ├─ Radix UI (無頭 UI)
  └─ Lucide React (圖標)

狀態管理和數據:
  ├─ Zustand 4.4.0 (狀態管理)
  ├─ TanStack Query 4.32.0 (數據獲取)
  ├─ Axios 1.4.0 (HTTP 客戶端)
  └─ React Hook Form 7.45.4 (表單管理)

驗證和數據:
  ├─ Zod 3.22.2 (數據驗證)
  ├─ Date-fns 2.30.0 (日期處理)
  └─ Lodash 4.17.21 (工具庫)

國際化:
  ├─ i18next 23.5.0
  ├─ react-i18next 13.1.0
  └─ i18next-browser-languagedetector 7.2.0

認證:
  ├─ @next-auth/prisma-adapter (會話管理)
  ├─ jsonwebtoken (JWT 解析)
  └─ js-cookie (Cookie 管理)

支付集成:
  ├─ @stripe/react-stripe-js 2.1.1
  ├─ @stripe/stripe-js 1.46.0
  └─ Alipay SDK (中國支付)

測試:
  ├─ Vitest 0.34.1
  ├─ @testing-library/react 14.0.0
  ├─ @testing-library/jest-dom 6.1.4
  └─ Playwright 1.38.0 (E2E)

代碼質量:
  ├─ ESLint 8.49.0
  ├─ Prettier 3.0.3
  ├─ Pre-commit hooks (husky)
  └─ commitlint

性能和監控:
  ├─ Sentry (錯誤追蹤)
  ├─ Web Vitals
  └─ Lighthouse

工具和開發:
  ├─ Storybook 7.4.0 (組件開發)
  ├─ dotenv 16.3.1 (環境變數)
  └─ cross-env 7.0.3
```

### 後端技術棧

```yaml
運行時和框架:
  ├─ Node.js 18 LTS
  ├─ Express 4.18.2
  ├─ TypeScript 5.1.6
  └─ NestJS (可選, 未來升級)

數據庫:
  ├─ PostgreSQL 15
  ├─ Prisma 5.2.0 (ORM)
  ├─ Redis 7.0 (緩存)
  ├─ Elasticsearch 8.9 (搜尋)
  └─ InfluxDB (時間序列數據, 可選)

認證和安全:
  ├─ Passport.js 0.6.0
  ├─ jsonwebtoken 9.0.2
  ├─ bcrypt 5.1.0 (密碼加密)
  ├─ helmet 7.0.0 (安全頭)
  ├─ express-rate-limit (速率限制)
  ├─ cors 2.8.5
  └─ dotenv 16.3.1

驗證和數據:
  ├─ Joi 17.11.0
  ├─ class-validator (可選)
  ├─ zod 3.22.2
  └─ date-fns 2.30.0

API 和文檔:
  ├─ swagger-ui-express 4.6.3
  ├─ swagger-jsdoc 6.2.8
  └─ OpenAPI 3.0

支付集成:
  ├─ stripe 13.4.0
  ├─ PayPal SDK
  ├─ 支付寶 SDK
  └─ 微信支付 SDK

郵件和通知:
  ├─ Nodemailer 6.9.5 (郵件)
  ├─ SendGrid (可選)
  ├─ Socket.io 4.7.2 (實時)
  └─ Bull 4.11.4 (隊列)

AI/ML 集成:
  ├─ OpenAI SDK 4.12.0
  ├─ @anthropic-ai/sdk (Claude)
  ├─ Langchain.js (AI 編排)
  └─ Chroma (向量存儲)

文件存儲:
  ├─ AWS SDK v3 (S3)
  ├─ Multer 1.4.5 (文件上傳)
  └─ Sharp 0.32.6 (圖片處理)

日誌和監控:
  ├─ Winston 3.10.0
  ├─ Sentry 7.81.1
  ├─ Prometheus 14.16.0
  └─ Morgan (HTTP 日誌)

測試:
  ├─ Jest 29.7.0
  ├─ Supertest 6.3.3
  ├─ @faker-js/faker (測試數據)
  └─ dotenv-cli

數據庫遷移:
  ├─ Prisma Migrate
  ├─ TypeORM Migrations (可選)
  └─ db-migrate

代碼質量:
  ├─ ESLint 8.49.0
  ├─ Prettier 3.0.3
  ├─ Husky + commitlint
  └─ SonarQube (可選)
```

### DevOps 和部署

```yaml
容器化:
  ├─ Docker 24.0
  ├─ Docker Compose 2.20
  └─ Docker Hub Registry

編排 (生產):
  ├─ Kubernetes 1.27+ (可選)
  ├─ Helm (K8s 包管理)
  └─ ArgoCD (GitOps)

CI/CD:
  ├─ GitHub Actions
  ├─ Docker build and push
  ├─ Automated testing
  └─ Automated deployment

基礎設施:
  ├─ AWS EC2 (應用服務器)
  ├─ AWS RDS (PostgreSQL)
  ├─ AWS ElastiCache (Redis)
  ├─ AWS S3 (文件存儲)
  ├─ AWS CloudFront (CDN)
  ├─ AWS Lambda (無服務器任務)
  └─ AWS Route 53 (DNS)

監控和日誌:
  ├─ Prometheus + Grafana
  ├─ ELK Stack (Elasticsearch, Logstash, Kibana)
  ├─ Datadog (全棧監控)
  ├─ Sentry (錯誤追蹤)
  └─ New Relic (應用性能)

安全:
  ├─ Let's Encrypt (SSL/TLS)
  ├─ HashiCorp Vault (密鑰管理)
  ├─ Snyk (依賴掃描)
  ├─ SonarQube (代碼質量)
  └─ OWASP ZAP (安全測試)

備份和恢復:
  ├─ AWS Backup
  ├─ Backup scripts (定期)
  └─ 災難恢復計劃
```

---

## 🚀 本地開發環境設置

### 前置要求

```bash
# 安裝以下軟件
- Node.js 18 LTS (https://nodejs.org/)
- Docker Desktop (https://www.docker.com/products/docker-desktop)
- Git (https://git-scm.com/)
- VSCode (https://code.visualstudio.com/)
```

### 快速開始

```bash
# 1. 克隆項目
git clone https://github.com/ivanlai33-del/DevMaster-Academy.git
cd DevMaster-Academy

# 2. 安裝依賴
npm install

# 3. 設置環境變數
cp .env.example .env.local

# 4. 啟動 Docker 容器 (PostgreSQL, Redis)
docker-compose up -d

# 5. 運行數據庫遷移
npm run db:migrate

# 6. 啟動開發服務器
npm run dev

# 7. 訪問應用
# 前端: http://localhost:3000
# 後端 API: http://localhost:3001
# API 文檔: http://localhost:3001/api/docs
```

---

## 📁 項目結構

```
DevMaster-Academy/
├─ .github/
│  ├─ workflows/           # GitHub Actions CI/CD
│  └─ ISSUE_TEMPLATE/
│
├─ src/
│  ├─ frontend/            # React 應用
│  │  ├─ components/       # React 組件
│  │  ├─ pages/            # 頁面組件
│  │  ├─ hooks/            # 自定義 Hooks
│  │  ├─ stores/           # Zustand 狀態存儲
│  │  ├─ services/         # API 服務
│  │  ├─ utils/            # 工具函數
│  │  ├─ locales/          # i18n 翻譯文件
│  │  ├─ types/            # TypeScript 類型
│  │  ├─ styles/           # 全局樣式
│  │  ├─ App.tsx           # 主應用組件
│  │  ├─ main.tsx          # 入口文件
│  │  └─ vite-env.d.ts
│  │
│  └─ backend/             # Express API
│     ├─ routes/           # API 路由
│     ├─ controllers/      # 請求處理器
│     ├─ services/         # 業務邏輯
│     ├─ middleware/       # 中間件
│     ├─ models/           # 數據模型
│     ├─ validators/       # 數據驗證
│     ├─ utils/            # 工具函數
│     ├─ types/            # TypeScript 類型
│     ├─ config/           # 配置文件
│     ├─ database/         # 數據庫設置
│     ├─ mail/             # 郵件服務
│     ├─ payment/          # 支付服務
│     ├─ auth/             # 認證邏輯
│     ├─ ai/               # AI 服務集成
│     ├─ tests/            # 測試文件
│     ├─ app.ts            # Express 應用
│     ├─ server.ts         # 服務器入口
│     └─ index.ts
│
├─ docs/
│  ├─ PROJECT_PLAN.md      # 項目計劃
│  ├─ UX_UI_DESIGN.md      # UI/UX 規範
│  ├─ TECH_STACK.md        # 技術棧 (此文件)
│  ├─ API.md               # API 文檔
│  ├─ DATABASE.md          # 數據庫文檔
│  └─ DEPLOYMENT.md        # 部署指南
│
├─ database/
│  ├─ schema.prisma        # Prisma Schema
│  ├─ migrations/          # 數據庫遷移
│  └─ seed.ts              # 初始數據
│
├─ docker/
│  ├─ Dockerfile           # Docker 鏡像配置
│  ├─ docker-compose.yml   # Docker Compose 配置
│  └─ .dockerignore
│
├─ config/
│  ├─ .env.example         # 環境變數示例
│  ├─ .eslintrc.json       # ESLint 配置
│  ├─ .prettierrc.json     # Prettier 配置
│  ├─ tsconfig.json        # TypeScript 配置
│  ├─ vite.config.ts       # Vite 配置
│  └─ jest.config.js       # Jest 配置
│
├─ scripts/
│  ├─ db-migrate.sh        # 數據庫遷移腳本
│  ├─ db-seed.sh           # 初始數據腳本
│  ├─ docker-build.sh      # Docker 構建腳本
│  └─ deploy.sh            # 部署腳本
│
├─ .github/
├─ .gitignore
├─ .env.example
├─ .dockerignore
├─ package.json
├─ package-lock.json
├─ tsconfig.json
├─ docker-compose.yml
├─ README.md
└─ LICENSE
```

---

## 📦 依賴安裝指南

### 前端依賴安裝

```bash
# 基礎依賴
npm install react@18.2.0 react-dom@18.2.0
npm install -D typescript@5.1.6 vite@4.4.9
npm install -D @vitejs/plugin-react @vitejs/plugin-vue

# UI 框架和樣式
npm install tailwindcss@3.3.3 postcss autoprefixer
npm install -D tailwindcss@3.3.3 postcss autoprefixer
npm install @radix-ui/react-dialog @radix-ui/react-dropdown-menu
npm install lucide-react

# 狀態管理
npm install zustand@4.4.0
npm install @tanstack/react-query@4.32.0

# HTTP 和表單
npm install axios@1.4.0
npm install react-hook-form@7.45.4
npm install zod@3.22.2

# 國際化
npm install i18next@23.5.0 react-i18next@13.1.0
npm install i18next-browser-languagedetector@7.2.0
npm install i18next-http-backend@4.3.1

# 認證
npm install js-cookie@3.0.5

# 支付
npm install @stripe/react-stripe-js@2.1.1 @stripe/stripe-js@1.46.0

# 工具
npm install lodash@4.17.21 date-fns@2.30.0
npm install classnames@2.3.2

# 測試
npm install -D vitest@0.34.1 @testing-library/react@14.0.0
npm install -D @testing-library/jest-dom@6.1.4

# 代碼質量
npm install -D eslint@8.49.0 prettier@3.0.3
npm install -D eslint-config-prettier eslint-plugin-prettier
npm install -D husky lint-staged
```

### 後端依賴安裝

```bash
# 基礎依賴
npm install express@4.18.2
npm install -D typescript@5.1.6 ts-node@10.9.1

# 數據庫
npm install @prisma/client@5.2.0
npm install -D prisma@5.2.0

# Redis
npm install redis@4.6.10 ioredis@5.3.2

# 認證
npm install jsonwebtoken@9.0.2
npm install bcrypt@5.1.0
npm install passport@0.6.0 passport-jwt@4.0.1 passport-local@1.0.0

# 驗證
npm install joi@17.11.0
npm install zod@3.22.2

# 安全
npm install helmet@7.0.0
npm install express-rate-limit@7.0.0
npm install cors@2.8.5

# API 文檔
npm install swagger-ui-express@4.6.3
npm install swagger-jsdoc@6.2.8

# 支付
npm install stripe@13.4.0

# 郵件和通知
npm install nodemailer@6.9.5
npm install socket.io@4.7.2
npm install bull@4.11.4

# AI/ML
npm install openai@4.12.0

# 文件處理
npm install aws-sdk@2.1467.0
npm install multer@1.4.5
npm install sharp@0.32.6

# 日誌
npm install winston@3.10.0
npm install @sentry/node@7.81.1
npm install morgan@1.10.0

# 環境變數
npm install dotenv@16.3.1

# 工具
npm install lodash@4.17.21 date-fns@2.30.0

# 測試
npm install -D jest@29.7.0 supertest@6.3.3 @faker-js/faker@8.2.0

# 代碼質量
npm install -D eslint@8.49.0 prettier@3.0.3
npm install -D husky lint-staged commitlint

# 開發工具
npm install -D nodemon@3.0.1 ts-loader@9.4.4
```

---

## 🔄 常用命令

### 開發命令

```bash
# 安裝依賴
npm install

# 啟動開發服務器 (前端)
npm run dev:frontend

# 啟動開發服務器 (後端)
npm run dev:backend

# 同時啟動前後端 (使用 concurrently)
npm run dev

# 構建前端生產版本
npm run build:frontend

# 構建後端生產版本
npm run build:backend

# 預覽生產版本
npm run preview:frontend
```

### 數據庫命令

```bash
# 生成 Prisma 客戶端
npm run prisma:generate

# 創建新的遷移
npm run db:migrate:create

# 運行遷移
npm run db:migrate

# 重置數據庫 (清空所有數據)
npm run db:reset

# 初始化數據庫 (seed 數據)
npm run db:seed

# 打開 Prisma Studio
npm run db:studio
```

### 測試命令

```bash
# 運行所有測試
npm test

# 以監視模式運行測試
npm test:watch

# 運行覆蓋率報告
npm test:coverage

# 運行 E2E 測試
npm run test:e2e
```

### 代碼質量命令

```bash
# 檢查 ESLint
npm run lint

# 自動修復 ESLint 問題
npm run lint:fix

# 格式化代碼 (Prettier)
npm run format

# 檢查代碼質量
npm run format:check
```

### Docker 命令

```bash
# 構建 Docker 鏡像
docker build -t devmaster-academy .

# 啟動容器
docker run -p 3000:3000 -p 3001:3001 devmaster-academy

# 使用 Docker Compose 啟動
docker-compose up

# 後台運行
docker-compose up -d

# 停止和移除容器
docker-compose down

# 查看日誌
docker-compose logs -f
```

---

## 🌍 環境變數

### 前端環境變數 (.env.local)

```env
# API 配置
VITE_API_BASE_URL=http://localhost:3001/api
VITE_WS_URL=ws://localhost:3001

# 認證
VITE_GOOGLE_CLIENT_ID=your_google_client_id
VITE_GITHUB_CLIENT_ID=your_github_client_id

# 支付
VITE_STRIPE_PUBLIC_KEY=pk_test_your_key
VITE_STRIPE_PUBLISHABLE_KEY=pk_test_your_key

# 分析和監控
VITE_SENTRY_DSN=your_sentry_dsn
VITE_POSTHOG_API_KEY=your_posthog_key

# 功能開關
VITE_ENABLE_DEMO_MODE=false
VITE_ENABLE_DEBUG_MODE=true
```

### 後端環境變數 (.env)

```env
# 服務器配置
NODE_ENV=development
PORT=3001
LOG_LEVEL=debug

# 數據庫
DATABASE_URL=postgresql://user:password@localhost:5432/devmaster
REDIS_URL=redis://localhost:6379

# 認證
JWT_SECRET=your_jwt_secret_key_change_in_production
JWT_EXPIRATION=7d
REFRESH_TOKEN_SECRET=your_refresh_token_secret

# OAuth
GOOGLE_CLIENT_ID=your_google_client_id
GOOGLE_CLIENT_SECRET=your_google_client_secret
GITHUB_CLIENT_ID=your_github_client_id
GITHUB_CLIENT_SECRET=your_github_client_secret

# 支付 (Stripe)
STRIPE_SECRET_KEY=sk_test_your_key
STRIPE_PUBLISHABLE_KEY=pk_test_your_key
STRIPE_WEBHOOK_SECRET=whsec_test_your_secret

# 支付 (支付寶, 微信)
ALIPAY_APP_ID=your_alipay_app_id
ALIPAY_PRIVATE_KEY=your_alipay_private_key
WECHAT_PAY_MERCHANT_ID=your_wechat_merchant_id
WECHAT_PAY_API_KEY=your_wechat_api_key

# 郵件
MAIL_FROM=noreply@devmaster.academy
MAIL_HOST=smtp.gmail.com
MAIL_PORT=587
MAIL_USER=your_email@gmail.com
MAIL_PASSWORD=your_email_password

# AWS
AWS_ACCESS_KEY_ID=your_aws_access_key
AWS_SECRET_ACCESS_KEY=your_aws_secret_key
AWS_REGION=us-east-1
AWS_S3_BUCKET=devmaster-academy

# AI/ML
OPENAI_API_KEY=your_openai_api_key
ANTHROPIC_API_KEY=your_anthropic_api_key

# 監控
SENTRY_DSN=your_sentry_dsn

# 功能開關
ENABLE_EMAIL_VERIFICATION=true
ENABLE_TWO_FACTOR_AUTH=false
ENABLE_DEMO_MODE=false
```

---

## 💻 IDE 推薦配置

### VSCode 推薦擴展

```
- ESLint
- Prettier - Code formatter
- TypeScript Vue Plugin
- Tailwind CSS IntelliSense
- Prisma
- Thunder Client 或 REST Client
- Git Graph
- Better Comments
```

### VSCode settings.json

```json
{
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.formatOnSave": true,
  "[typescriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true
  },
  "prettier.semi": true,
  "prettier.singleQuote": true,
  "prettier.trailingComma": "es5",
  "editor.tabSize": 2,
  "editor.insertSpaces": true,
  "files.trimTrailingWhitespace": true
}
```

---

## 📚 參考資源

- [React 文檔](https://react.dev)
- [TypeScript 文檔](https://www.typescriptlang.org/docs/)
- [Express 文檔](https://expressjs.com/)
- [Prisma 文檔](https://www.prisma.io/docs/)
- [Tailwind CSS 文檔](https://tailwindcss.com/docs)
- [i18next 文檔](https://www.i18next.com/)
- [Stripe 文檔](https://stripe.com/docs)

---

**版本**: 1.0
**最後更新**: 2026-06-29
**狀態**: 準備開發
