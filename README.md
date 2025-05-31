pybitcoin/
├── blockchain/               # 区块链核心实现
│   ├── block.py              # 区块类定义
│   ├── blockchain.py         # 区块链管理
│   ├── proof_of_work.py      # 共识机制(PoW)
│   └── validation.py         # 区块/交易验证
│
├── transactions/             # 交易系统
│   ├── transaction.py        # 交易类
│   ├── tx_input.py           # 交易输入
│   ├── tx_output.py          # 交易输出
│   ├── coinbase.py           # 创世交易
│   └── utxo_set.py           # UTXO管理
│
├── wallet/                   # 钱包系统
│   ├── wallet.py             # 钱包核心(密钥管理)
│   ├── keys.py               # 密钥生成与签名
│   └── address.py            # 地址生成
│
├── network/                  # 网络层
│   ├── node.py               # 节点实现
│   ├── peer.py               # 节点间通信
│   ├── messages.py           # P2P消息协议
│   └── api_server.py         # REST API接口
│
├── utils/                    # 工具函数
│   ├── crypto.py             # 加密工具(SHA256, RIPEMD160等)
│   ├── serialization.py      # 序列化/反序列化
│   ├── merkle_tree.py        # 默克尔树实现
│   └── difficulty.py         # 难度调整
│
├── config.py                 # 全局配置(创世区块、端口等)
└── main.py                   # 主入口(节点启动)
