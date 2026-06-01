# 🌍 Better Earth

---

## 中文

### 每次调用，都在消耗地球 🌍

你的 AI Agent 每读一个文件、搜一次代码、写一行内容——背后都是真实的 GPU 在转、数据中心在散热、电表在跳。

如果你用的是按次计费的 Coding Plan，那它同时在消耗你的钱包。

**Better Earth** 是一个 Agent Skill，安装后它会默默引导你的 Agent：

- 🔒 能一次读三个文件，绝不分三次读
- 🧠 调用前先想清楚，不做返工
- 📦 每次调用多输出、多思考，把单次调用的价值榨干
- 💻 能用一次 bash 执行多条命令的，绝不拆成多次调用
- 🚫 杜绝无意义的重复搜索、反复验证、多余的读写

### 一句话

> 省一次调用，地球少烧一点电，你少花一分钱。

### 安装

安装全部（中文 + 英文）：

```bash
npx skills add https://github.com/bluseliu50/better-earth
```

只装中文版：

```bash
npx skills add https://github.com/bluseliu50/better-earth --skill better-earth
```

只装英文版：

```bash
npx skills add https://github.com/bluseliu50/better-earth --skill better-earth-en
```

### 它怎么工作

Skill 的 `description` 字段包含了全部核心理念。Agent 在新会话启动时就会读取到——不需要额外加载 body。它被告知：

1. **批量操作**优先
2. **先思考再调用**，避免返工浪费
3. 每次调用**多输出一些**
4. 一次 bash 能跑多条命令就**不拆开**
5. **零浪费**，不做多余的读写搜索
6. compact / handoff / goal / plan 时**必须继承**这些原则

### 许可

[MIT](LICENSE)

---

## English

### Every Call Costs the Earth 🌍

Every time your AI Agent reads a file, searches code, or writes output — real GPUs spin up, data centers dissipate heat, and the meter ticks.

If you're on a per-call Coding Plan, it's also draining your wallet.

**Better Earth** is an Agent Skill that silently guides your Agent to:

- 🔒 Read three files in one call, not three separate calls
- 🧠 Think before acting — no rework, no wasted calls
- 📦 Squeeze maximum value out of every single invocation
- 💻 Run multiple commands in one bash call instead of splitting them
- 🚫 Eliminate pointless duplicate searches, redundant verification, unnecessary reads/writes

### In One Line

> Save one call, the planet burns a bit less electricity, you spend a bit less money.

### Install

Install all (Chinese + English):

```bash
npx skills add https://github.com/bluseliu50/better-earth
```

Chinese only:

```bash
npx skills add https://github.com/bluseliu50/better-earth --skill better-earth
```

English only:

```bash
npx skills add https://github.com/bluseliu50/better-earth --skill better-earth-en
```

### How It Works

The skill's `description` field carries the entire core philosophy. Agents read it at session startup — no need to load the body. They're told to:

1. **Batch** operations whenever possible
2. **Think before calling** — avoid rework and waste
3. **Output more** per invocation
4. **Combine commands** in a single bash call instead of multiple
5. **Zero waste** — no unnecessary reads, writes, or searches
6. **Inherit** these principles during compact / handoff / goal / plan

### License

[MIT](LICENSE)
