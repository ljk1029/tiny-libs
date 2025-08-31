### 目录结构

```
tiny-libs/
├── README.md                  # 仓库说明文档，包含学习路线和贡献指南
├── docs/                      # 相关文档资料
│   ├── lib-introduction.md    # 各库的简介和适用场景
│   └── learning-notes.md      # 学习笔记汇总
├── libs/                      # 按功能分类的开源库学习
│   ├── logging/               # 日志库 (如spdlog, glog等)
│   │   ├── examples/          # 库的使用示例代码
│   │   ├── notes.md           # 学习笔记和使用心得
│   │   └── practice/          # 基于该库的练习项目
│   ├── network/               # 网络库 (如libcurl, mongoose等)
│   │   ├── examples/
│   │   ├── notes.md
│   │   └── practice/
│   ├── json/                  # JSON处理库 (如nlohmann/json等)
│   │   ├── examples/
│   │   ├── notes.md
│   │   └── practice/
│   ├── container/             # 容器库 (如absl, folly等)
│   │   ├── examples/
│   │   ├── notes.md
│   │   └── practice/
│   └── other/                 # 其他类别库
│       ├── examples/
│       ├── notes.md
│       └── practice/
└── scripts/                   # 辅助脚本，如编译脚本等
    ├── build.sh
    └── run_app.sh
└── tool/                      # 工具类
```

### version
- v1.0.0


### changlog
- v1.0.0 : init