# 功能需求文档
这个文档主要是用来增加新的功能需求。总的架构和技术选型还是请参考 instruction.md 文档。

## 1 **Supabase 集成**
- **初始化**：
  - 初始化 Supabase 客户端，并配置 Supabase 的 URL 和 API Key。
- **连接测试**：
  - 测试 Supabase 是否连接成功。
- **用户系统**：
  - 用户登录、注册、登出。
  - 用户信息管理，包括用户名、头像、邮箱等。
  - 操作历史记录。
- **对话系统**：
  - 创建新的对话，加载老的历史对话。
  - 对话需要跟当前用户关联，所以需要用户登录。通过用户ID索引。
  - 对话需要记录对话内容，包括对话ID、对话内容、对话时间、对话状态等。
  - 支持查看历史记录，并重新发送历史消息。

- 以上需求更新时间为2025年1月14日上午11点50分。后续有更新我们再追加。


## 2 **会话历史记录列表**
- **左边导航栏**：
  - 添加按钮，点击跳转到会话历史记录列表，可以查看所有会话历史记录。
- **会话历史记录列表页**：
  - 显示所有会话历史记录。
  - 
- **用户系统**：
  - 用户登录、注册、登出。
  - 用户信息管理，包括用户名、头像、邮箱等。
  - 操作历史记录。
- **对话系统**：
  - 创建新的对话，加载老的历史对话。
  - 对话需要跟当前用户关联，所以需要用户登录。通过用户ID索引。
  - 对话需要记录对话内容，包括对话ID、对话内容、对话时间、对话状态等。
  - 支持查看历史记录，并重新发送历史消息。

- 以上需求更新时间为2025年1月15日上午16点00分。后续有更新我们再追加。