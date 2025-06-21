## 运行环境

- Java 17
- Node.js 18+
- MySQL 8
- DashScope API KEY（或者其他）
- Redis-Stack
  redis基础上拓展向量查询功能
- neo4j 5+
- 
建议docker部署

运行：

将application放到resource包下

本地ollama下载：https://ollama.ai/download

下载会话模型与嵌入模型并进行配置

修改application.yml中的API-KEY, MySQL, Redis-Stack, Neo4j配置


启动项目
前端先启动api载启动dev
