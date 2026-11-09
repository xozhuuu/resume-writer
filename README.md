# Resume Writer

Resume Writer 是一个面向求职者的简历 Skill，帮助把真实经历整理成重点清晰、便于招聘者快速阅读和后续追问的简历内容。

## 功能

- 审阅简历，指出最影响岗位匹配和信息理解的问题。
- 提炼最多三条有事实支撑、与目标岗位相关的个人综述。
- 按“目标/问题—行动—结果”梳理工作、实习和项目经历。
- 根据职位描述调整内容重点；没有职位描述时，提供通用表达优化。
- 按信息价值决定简历篇幅，不机械要求一页。
- 标出待核实的数据，区分个人贡献与团队成果，不编造职责或业绩。

## 安装

使用 Skills CLI：

```bash
npx skills add xozhuuu/resume-writer
```

在 Cursor 项目中，也可以将本仓库放入：

```text
.cursor/skills/resume-writer/
```

请保留 `SKILL.md` 和 `references/` 目录。

## 使用示例

```text
使用 $resume-writer 审阅我的简历，并按这份产品分析师 JD 调整重点。不要编造经历或数据。
```

```text
帮我把这段实习经历按“目标、行动、结果”整理；缺少的数据请标成待核实。
```

也可以直接提出简历撰写、审阅、改写、个人综述、项目经历整理或 JD 定向优化需求。

## 项目结构

```text
resume-writer/
├── SKILL.md
├── README.md
├── README_EN.md
├── LICENSE
├── agents/
│   └── openai.yaml
└── references/
    ├── examples.md
    └── review-checklist.md
```

## 适用边界

本 Skill 主要处理简历内容和结构，不要求固定页数、照片或邮箱类型。个人信息和版式按用户偏好及申请要求处理。缺少事实时会标出待补信息，不会把团队成果写成个人独立成果。

## 许可证

本项目采用 MIT License，详见 [LICENSE](LICENSE)。

英文说明见 [README_EN.md](README_EN.md)。
