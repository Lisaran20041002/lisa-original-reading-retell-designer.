# Lisa Original Reading · Retell Designer

这是一个本地 Codex Skill，用于把英语阅读教材转化为有教学判断、可完成、具有手工绘本视觉语言的复述单。

## 安装

将整个 `lisa-original-reading-retell-designer` 文件夹复制到 Codex skills 目录（通常为 `C:\Users\<用户名>\.codex\skills\`），重启或刷新 Codex 后即可自动发现。也可显式调用 `$lisa-original-reading-retell-designer`。

## 调用示例

“请读取这份阅读教材，先做教材诊断，再按 Lisa Original Reading 方法设计一张复述单。不要直接复刻教材构图，先输出 Character Lock、Scene Lock 和 3–5 张关键事件插图方案。”

## 重要边界

这是本地 Codex Skill，不会自动安装到 ChatGPT 的自定义 GPT 列表。若要在 ChatGPT 中使用，请把 `SKILL.md` 的核心指令和 `references/` 中需要的文件手动加入自定义 GPT 或 Project。
