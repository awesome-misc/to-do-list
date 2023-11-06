# To-do-list 识别

## 临时紧急重要任务 (2023-10-29)
  1. AppSevice (Console/webApi) 环境变量不生效?无法加载?读取?
  1. publish ~~CI/CD~~ Az App Service command line (WebApi)

## `ThreadingTasksScheduler`
  1. 实现跑批任务测试
    - 远程调用 
  3. 确认 `send/post` 时序

## `Semantic Kernal`
  1. Retry 策略

## `AutoGen` (2023-10-29)
  1. 场景创意启发
     - 样例调试成功
  1. 如何定制专用 `role agent`, `system message`
     - 参数化 `User_Proxy` 应答
  1. 并发/调用 `llm` 的效果
  1. 深度学习、挖掘 `autogen` 源码，定制 `agent`
  1. `RetrieveAssistantAgent` 专用的内置 `Agent` 有哪些
  1. `QdrantRetrieveUserProxyAgent` 开源代码研究

  下面是两个场景。
  营销活动策略-落地：
  1. 读取多个数据表，获得用户、销售、活动洞察
  2. 总结洞察，形成新活动策略
  3. 拆解策略（活动名，用户群，活动商品，活动折扣等）
  4. 执行策略（生成短信/邮件，生成规则，发送）
  
  运营活动落地：
  1. 每日按照用户输入活动主题，选择用户群
  2. 选择商品，匹配不同用户群
  3. 为不同用户群-商品生成活动文案
  4. 发送短信

我们在研究Autogen的时候，需要想想：
 - 哪个Agent/角色负责哪一块？
 - 有几个user_proxy，分别负责什么？


## PDF to Markdown
  1. PDF to Markdown DOM/Tree .NET Core C# 封装
     - C#/.NET Core MuPDF
       - https://github.com/arklumpus/MuPDFCore
  1. 干掉目录生成 markdown
  1. 干掉页眉页脚 markdown
     
  

