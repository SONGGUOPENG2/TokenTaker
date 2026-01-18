# TokenTaker
TokenTaker专注于 BNB Smart Chain（BSC）区块链网络的代币深度分析工具，能根据代币合约地址获取区块链完整信息，包括持币者分布、转账记录、成本估算、流动性池分析、持币分析、持有比例、持币地址验证、Excel/Word导出等，并提供完整的代币分析全流程。
# 主要功能
🔍 代币信息获取

1.查询代币基础信息：名称、符号、精度、总供应量等

2.获取代币创建时间、历史所有交易哈希

3.BscScan API 与 Web3节点双数据源

👥 持币者分析

1.获取代币所有持币地址及余额（支持最多 100,000+ 地址）

2.计算持币占比、持币排名、交易次数

3.支持从 BscScan 官方 Excel 文件导入持币者数据

4.验证持币地址是否在指定列表（反洗钱/合规检查）

💸 转账历史分析

分析代币所有转账记录（时间、数量、发送/接收地址）

支持从 BscScan 官方 Excel 文件导入转账记录

计算地址首次/最后交易时间、交易次数

📊 持仓成本估算

基于转账历史估算每个地址的平均持仓成本

计算估算盈亏（PNL）与盈亏百分比

识别合约地址与非合约地址

🏊 流动性池分析

分析 Uniswap V3 流动性池

获取池子配对代币、流动性、手续费等信息

计算池子关键参数（sqrtPriceX96、tick、feeProtocol）

🛡️ 安全与验证

持币地址验证：检查地址是否在允许列表中

缺失地址报告与余额排序

支持本地数据库缓存与共享内存

💾 数据导出

导出持币者数据到 CSV/Excel/Word/Txt

导出分析摘要

选择导出个别数据

支持大文件拆分保存（超过 Excel 最大行数限制）

<img width="3200" height="2000" alt="2026-01-18-17-53-26" src="https://github.com/user-attachments/assets/d56bc805-16d1-48e3-8619-09be59abb00f" />

# 适用场景

代币项目方：监控代币分布，识别大额持币者

投资者：分析代币持有结构，评估项目风险

审计机构：进行代币合规性检查与反洗钱分析

研究人员：研究 BSC 代币生态与持币行为模式

社区管理者：空投前验证地址资格，分析代币流向

# Windows 版本软件地址

https://github.com/SONGGUOPENG2/TokenTaker/releases

# 快速开始

1.数据导入（可选）

从 BscScan 导出持币者 Excel 文件，通过本软件导入

从 BscScan 导出转账记录 Excel 文件，通过本软件导入

2.分析代币

输入代币合约地址（例如：0x99d9f5186d03e55e8857a96a9b4411fe33124e1b）

输入流动性池地址（可选）

点击“分析”按钮开始完整分析流程

3.查看结果

查看代币基本信息

查看前10大持币地址

查看分析摘要统计

导出数据到本地文件（word文档或excel工作表）

导出数据到本地数据库（默认）

# 警告

⚠️ 该软件禁止用作非法用途。

禁止用于跟踪特定个人或组织的资产

禁止将分析结果用于市场操纵或恶意攻击

禁止结合其他工具进行非法套利或市场操纵

禁止用于未经授权的商业监控

# 系列软件

TokenTaker 是 SONGGUOPENG 区块链工具集的一部分，其他相关工具包括：

TokenMaker：一键部署 BSC 智能合约并创建代币

Token-Transfer：代币批量转移与管理工具

更多工具：https://github.com/SONGGUOPENG2?tab=repositories

# 联系我

如有问题、建议或合作意向，欢迎联系：

Telegram: https://t.me/SONGGUOPENG

GitHub: https://github.com/SONGGUOPENG2

# 技术架构

前端: Tkinter (Python GUI)

区块链交互: Web3, BscScan API, Alchemy API，Ethereum API

数据处理: Pandas, NumPy

数据存储: SQLite 本地缓存，共享内存

加密: AES-256 加密存储敏感配置

# 后置提醒

Copyright © 2026 SONGGUOPENG All rights reserved

本软件仅供学习与合法用途，使用者需自行承担风险。开发者不对因本软件造成的任何损失负责。

使用前请确保已连接国际互联网，以便访问 BSC 区块链数据。建议先使用测试代币地址熟悉软件功能。
