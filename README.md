# Tonight's Story · 共鸣剧场 Demo

Soul 嵌入式互动叙事 Demo：《凌晨 2:17 的小票》

## 在线体验

部署 GitHub Pages 后访问：

```text
https://yingruiji.github.io/Tonight-s-Story/
```

## 本地体验

```bash
cd soul-resonance-theater
python3 -m http.server 4173 --bind 0.0.0.0
```

浏览器打开：`http://127.0.0.1:4173/index.html`

或直接双击 `index.html`。

## 文件说明

| 文件 | 说明 |
|---|---|
| `index.html` | 可点击交互 Demo（单文件，零依赖） |
| `requirements.md` | 产品需求文档 |
| `PRD-共鸣剧场.md` | 原型 PRD |

## GitHub Pages 开启方式

1. 进入仓库 Settings → Pages
2. Source 选择 `Deploy from a branch`
3. Branch 选择 `main`，文件夹选择 `/ (root)`
4. 保存后等待 1-2 分钟
