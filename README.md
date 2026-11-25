# 中文物理教材编写 Skill

根据教师讲义和习题集编写或修订中文物理教材，让知识讲解、完整题目、分步解析与必要黑白题图相邻呈现。

## 适用任务

- 按教师讲义的范围和顺序整理中文物理教材。
- 将习题集中的题目安排到对应的重要知识点后。
- 补全题干，为每题编写详细解析和明确答案。
- 绘制必要的黑白物理示意图，核对方向、几何关系和电路连接。
- 检查题源、题号对应、公式、物理结论和最终页面。

## 目录

```text
README.md
skills/
  physics-textbook-cn/
    SKILL.md
    agents/
      openai.yaml
    references/
      project-retrospective.md
```

[技能正文](skills/physics-textbook-cn/SKILL.md)包含制作流程与检查要求；[项目复盘](skills/physics-textbook-cn/references/project-retrospective.md)记录一次电磁学教材编写中的实际经验。

## 在 Codex 中安装

把下面的仓库网址替换为本仓库的实际网址，再将整段话发给 Codex：

```text
请用 $skill-installer 安装这个 GitHub 仓库中的 skills/physics-textbook-cn：
https://github.com/你的用户名/physics-textbook-cn
```

安装后，使用以下调用名：

```text
$physics-textbook-cn
```

## 使用示例

```text
使用 $physics-textbook-cn，根据我提供的讲义和习题集编写中文物理教材。
依照讲义顺序讲解，重要知识点后配1至3道合适题目。
题干必须完整，每题后立即给出详细解析与答案；必要题目配黑白图。
按我指定的格式输出，并检查题源、公式、题图和排版。
```

开始制作教材时，提供该课程实际使用的讲义、习题集及输出要求。Skill 只包含流程说明和项目经验，不包含原课程PDF、教材成品、学校标志或本机字体。

## 本次实践中的经验

- 先确定一节样稿的组织方式，再展开全书。
- 用稳定标识关联题干、解析、来源和题图，显示题号随顺序生成。
- 详细解析以建模、推导和检验是否清楚为准，不把字数当成质量标准。
- 题图同时接受物理检查与版面检查。
- 区分公式能显示、物理结论经过复核和成品页面可读这三类检查。

项目复盘中的138页、147个带解答题目单元和53幅新增黑白题图，是该项目的结果，不是新项目的固定指标。
