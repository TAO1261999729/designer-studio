# designer-studio · 美工设计 Skill

扮演资深商业美工：先看参考图拆解版式、配色与风格，再定出有高级感的框架，最后产出可由运营自行替换真人照片和文案的营销视觉模板。

## 什么时候会用到

- 做海报、团队/设计师阵容图、活动主视觉、社媒配图、封面；
- 给了参考图，要求照着它的风格和版式复刻；
- 懂一点基础设计，但不会排版、不会配色、把握不住"高级感"；
- 需要可编辑模板（以后自己换图、改字），而不是一张改不了的位图。

## 仓库结构

| 路径 | 作用 |
|---|---|
| `SKILL.md` | 主工作流：看稿拆解 → 锁定 Brief → 选路线 → 产出 → 质检交付 |
| `references/design-rubric.md` | 参考图拆解清单、配色/字体/留白尺子、高级感检查项与常见跑偏 |
| `references/html-template-spec.md` | 可编辑 HTML 模板的固定画布、占位逻辑、字体加载、质检与交付规范 |
| `assets/team-poster-template.html` | 竖版团队阵容海报可编辑样板（错落卡片 + 字母穿插 + 中部标题压版） |

## 安装到豆包

### 方式一：cocoloop 安装（公开仓库，无需认证）

在豆包对话里让 cocoloop 安装仓库：

```
用 cocoloop 安装 TAO1261999729/designer-studio
```

### 方式二：手动 clone

把仓库克隆到豆包的 `.user_skills` 目录：

```bash
git clone https://github.com/TAO1261999729/designer-studio.git <豆包目录>/.user_skills/designer-studio
```

### 方式三：离线迁移包

拿到 `designer-studio-skill.zip` 后解压，把里面的 `designer-studio` 文件夹整体放进 `.user_skills` 目录，重开豆包即可识别。

### skills 目录定位

- Windows：`C:\Users\<用户名>\AppData\Local\Doubao\User Data\Default\.doubao\agent_mode\workspace\.user_skills\`
- 其他平台：找到当前环境的 `workspace/.user_skills` 目录，把 `designer-studio` 放进去即可。

## 更新

1. 在本机改好 Skill 文件；
2. 提交并推送到 `main`：

```bash
git add .
git commit -m "更新 designer-studio"
git push
```

3. 其他设备重新安装，或在本地目录 `git pull` 取最新版。

## 合规提醒

- 不照搬参考图里的他人人脸、品牌名、Logo、水印与奖项；
- 人物素材只用真实照片或品牌方公开资料图，不用 AI 生成人物图对外宣传；
- 年限、价格、参数、资质、案例等事实信息以真实口径为准，占位文案对外发布前必须替换。
