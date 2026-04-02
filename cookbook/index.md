## Cookbook

欢迎来到 happy-code 项目的使用指南！这里将解答你最关心的几个问题。

### 本项目与claudcode官方cli的区别是什么？

happy-code 是一个基于官方 Claude Code CLI 的逆向工程项目，具有以下特点：

- **开源性质**：与官方闭源的 CLI 不同，我们的代码完全开源，便于社区贡献和学习研究
- **本地化定制**：允许用户根据自身需求进行功能定制和修改
- **功能保留**：保留了官方 CLI 的核心功能，包括 REPL 对话、文件操作、Git 集成等
- **技术栈开放**：采用 TypeScript + Bun 技术栈，方便开发者理解和扩展
- **社区驱动**：由社区驱动开发，快速响应用户反馈和需求

### 如何在本地启动？

按照以下步骤即可在本地启动项目：

1. **安装 Bun 运行环境**：
   如果你还没有安装 Bun，请先安装：
   - 方式一：使用 Homebrew (macOS)
     ```bash
     brew install bun
     ```
   - 方式二：使用安装脚本
     ```bash
     curl -fsSL https://bun.sh/install | bash
     ```
   - 安装完成后重启终端或重新加载 shell 配置

2. **确认环境要求**：
   ```bash
   # 检查 Bun 版本 (需要 >= 1.3.11)
   bun --version
   ```

3. **克隆并安装依赖**：
   ```bash
   # 克隆项目
   git clone <your-fork-url>
   cd happy-code
   
   # 安装依赖
   bun install
   ```

4. **启动开发模式**：
   ```bash
   # 开发模式运行 (版本号应显示 888)
   bun run dev
   ```
