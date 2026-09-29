# 🛎️ peo-plan — 全域技能調度官

> 這是整個 AI 廚房的**中央傳令樞紐**。所有已安裝的技能都必須向她「登記入職」。當任何任務進來時，由 peo-plan 自動調度，確保老闆心血打造的每一個 Skill 都被正確使用。

## 📁 倉庫結構

```
peo-plan/
├── SKILL.md                     ← 主技能文件（大腦）
├── README.md                    ← 本說明文件
└── registry/                    ← 技能登記所
    ├── _HOW_TO_REGISTER.md      ← 新技能入職指南
    ├── a-plan.md                ← 總管：全端架構與部署
    ├── ui-ux-plan.md            ← 主廚：前端設計與切版
    ├── ui-ux-pro-max-skill.md   ← 菜商：配色與字體資料庫
    ├── recipe.md                ← 金庫：獨門配方存取
    ├── fal-ai-mcp-server.md     ← 生圖：AI 圖片與影片
    └── speech.md                ← 語音：Asa & Wer 語音生成
```

## 🚀 如何使用

對 AI 說：
> `peo-plan，我需要 [描述任務]，請幫我找到對的技能並傳達。`

## 🆕 如何登記新技能

當你完成一個新的 Skill：
> `peo-plan，我做了一個新技能叫 [name]，它能做 [功能描述]，安裝在 [路徑]。`

peo-plan 會自動在 `registry/` 建立入職卡。

## 🔗 相關倉庫

- 主廚技能：[ui-ux-plan-skill](https://github.com/cw33c2/ui-ux-plan-skill)
- 傳家食譜：[antigravity-skills-backup](https://github.com/cw33c2/antigravity-skills-backup) (含 `/recipe`)
- 頂級菜商：[ui-ux-pro-max-skill](https://github.com/cw33c2/ui-ux-pro-max-skill)
