# 需参考图补充包（2026-11-04）

从仓库筛出 **尚未被** [`cn-under-30s-2026-11-04`](../cn-under-30s-2026-11-04/) 覆盖、且明确依赖参考图 / `@image` / 角色锁定 / Main Subject 的提示词，本包补齐 **8 条 + 12 张**角色参考图，方便批量 I2V。

参考图由 Grok Bot 内置生图生成（**未使用、也未提交任何 API Key**）。

## 怎么用

1. 打开本仓库对应 `by-date/*.md`（或 `prompts.json`）复制完整提示词正文。
2. 在视频工具里粘贴提示词，再按下方「参考图映射」把本目录里的 PNG 作为 `@image1` / `@image2` / `[Image 1]` / `Main Subject` 上传。
3. 同一批生成固定同一组参考图，角色脸与服装才会更稳。
4. **不要**把任何 API Key 写进仓库、提示词或脚本。

## 清单

| # | 标题 | 时长 | 工具 | 参考图 |
|---|---|---|---|---|
| 1 | [红灯恋人：我们曾是我们](../../by-date/2026-10-29.md) | 30 秒 | Seedance 2.5 | `male.png`→@image1, `female.png`→@image2 |
| 2 | [青铜钟最后一响：寺院雨夜对决](../../by-date/2026-10-27.md) | 28 秒 | Seedance 2.5 | `hero.png`→@image1 |
| 3 | [雾山茶园跑酷一打十](../../by-date/2026-10-24.md) | 15 秒 | Seedance 2.5 | `heroine.png`→@image 1 |
| 4 | [雨夜月台重逢](../../by-date/2026-11-03.md) | 约 20 秒 | Seedance 2.5 | `girl.png`→角色1, `boy.png`→角色2 |
| 5 | [双图魔法少女变身](../../by-date/2026-10-31.md) | 15 秒 | Seedance 2.5 | `before.png`→[Image 1], `after.png`→[Image 2] |
| 6 | [印尼巷弄日常家录](../../by-date/2026-10-31.md) | 30 秒 | Seedance 2.5 | `main.png`→Main Subject |
| 7 | [母亲等子归来（朝鲜时代）](../../by-date/2026-10-28.md) | 30 秒 | Seedance 2.5 | `mother.png`→角色1, `son.png`→角色2 |
| 8 | [便携意式咖啡机晨间 UGC](../../by-date/2026-10-26.md) | 30 秒 | Seedance 2.5 | `character.png`→MAIN CHARACTER |

## 参考图映射（按条目）

### 1. 红灯恋人：我们曾是我们

- **时长**：30 秒 · **工具**：Seedance 2.5 · **分类**：创意趣味
- **来源**：见 `meta.json`
- **完整提示词**：[`by-date/2026-10-29.md`](../../by-date/2026-10-29.md)
- **目录**：`01-hongdeng-lianren/`
  - `male.png` — **男主** → **@image1**
  - `female.png` — **女主** → **@image2**

### 2. 青铜钟最后一响：寺院雨夜对决

- **目录**：`02-qingtongzhong/`
  - `hero.png` — **英雄** → **@image1**（黑衣武打 + 木杖）

### 3. 雾山茶园跑酷一打十

- **目录**：`03-wushan-chayuan/`
  - `heroine.png` — **女主** → **@image 1**（酒红上衣 + 米色工装裤）

### 4. 雨夜月台重逢

- **目录**：`04-yuye-yuetai/`
  - `girl.png` — **女主**（奶油色风衣）
  - `boy.png` — **男主**（深蓝外套，雨湿）

### 5. 双图魔法少女变身

- **目录**：`05-shuangtu-mofa/`
  - `before.png` — **[Image 1]** 变身前校服（2D）
  - `after.png` — **[Image 2]** 变身后魔装+杖（2D）

### 6. 印尼巷弄日常家录

- **目录**：`06-yinni-xiangnong/`
  - `main.png` — **Main Subject**

### 7. 母亲等子归来（朝鲜时代）

- **目录**：`07-muqin-dengzi/`
  - `mother.png` — **母亲**
  - `son.png` — **儿子**

### 8. 便携意式咖啡机晨间 UGC

- **目录**：`08-kafei-ugc/`
  - `character.png` — **MAIN CHARACTER**（产品外观仍跟提示词文字）

## 本轮未覆盖（仍缺参考图，可下次补）

- 丧尸都市最后一战（@image1/2/3）
- 午夜血脉：最后一战（@image1/2/3）
- 二战梦境战场（@image1/2/3）
- 雨夜胶囊通勤悬崖（Image1/2/3）
- 翡翠黄昏獠牙之战（@image1 + werewolf @image2）
- 西班牙阳光与阴影旅行日记（@image1）
- REVISION 护肤广告（image1/image2）
- 球场大乱斗：熊猫拳手戏耍鲨鱼恶霸（角色设定图）
- 永不抵达的列车（脸一致性，无显式 @image）

纯文生视频（无明显挂图依赖）约 **30** 条，本包跳过。

## 目录结构

```
needs-refs-2026-11-04/
  README.md
  meta.json
  01-hongdeng-lianren/   # male + female
  02-qingtongzhong/       # hero
  03-wushan-chayuan/      # heroine
  04-yuye-yuetai/         # girl + boy
  05-shuangtu-mofa/       # before + after
  06-yinni-xiangnong/     # main
  07-muqin-dengzi/        # mother + son
  08-kafei-ugc/           # character
```

## 说明

- 提示词原文仍以仓库主索引为准，本包只打包「可直接批量用的参考图 + 映射说明」。
- 图片为角色一致性参考，商用前请自行确认合规。
