# Skills

这个目录放当前用户使用的创作类 skill。每个 skill 一个目录，结构统一。

## 目录约定

```
.kiro/skills/
├── README.md                   ← 本文件
├── wenan/
│   ├── wenan.md                ← skill 主文件
│   └── references/
│       ├── user-profile.md     ← 用户档案（写前必读，写后必更）
│       ├── evolution.md        ← 已验证方法（"以后怎么做"）
│       ├── anti-patterns.md    ← 已验证雷区（"以后不怎么做"）
│       └── style-guide.md      ← 长期沉淀的通用风格
└── xuanti/
    ├── xuanti.md
    └── references/
        ├── user-profile.md
        ├── evolution.md
        ├── anti-patterns.md
        └── style-guide.md
```

## 共用机制

两个 skill 共用同一套学习与进化机制：

1. **写前必读 user-profile.md**：决定这一轮怎么写
2. **写后必更 user-profile.md**：用户给出明确反馈就追加
3. **续轮原则**：常规续轮主轴 60-70% + 异质 30-40%；发散轮主轴 30-40% + 异质 60-70%
4. **学的是判断标准，不是表层句子**

## 共用尾巴格式

两个 skill 输出后都用 4 项编号尾巴，用户回复 `1/2/3/4` 直接按上下文承接，不再确认。

## 输出格式

两个 skill 都要求条目之间用 `---` 分隔、分隔线上下空行；xuanti 大类用 `━━━━━━━━━━━━━━━━━━━━` 包裹，方便扫一眼分清。
