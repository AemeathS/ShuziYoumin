# 任务悬赏平台

一个类似闲鱼任务版的 Web 应用，用户可以发布任务、接取任务、完成交易。

## 快速开始

### 1. 安装依赖
```bash
pnpm install
```

### 2. 启动数据库
```bash
docker-compose up -d
```

### 3. 初始化数据库
```bash
pnpm db:migrate
pnpm db:seed
```

### 4. 启动开发服务器
```bash
pnpm dev
```

### 5. 访问应用
- 前端: http://localhost:5173
- 后端: http://localhost:3000

## 技术栈
- 前端: React 18 + TypeScript + Vite + Tailwind CSS + Ant Design
- 后端: Express + TypeScript + Prisma
- 数据库: PostgreSQL 15
- 缓存: Redis 7
- 容器: Docker + Docker Compose
