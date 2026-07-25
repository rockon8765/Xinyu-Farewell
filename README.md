# 欣賞宇宙 · 給欣宇的送舊卡片

師大領袖社夥伴們的祝福卡片：28 段祝福、40 張合照、1 段影片。

## 部署到 GitHub Pages

要上傳的檔案有 **兩個**，且必須放在同一層目錄：

- `index.html` — 卡片本體（照片、字體、程式都已內嵌，約 6 MB）
- `xinyu.mp4` — 影片（約 18 MB，`index.html` 用相對路徑讀取，檔名不能改）

1. 在 GitHub 建一個新的 repository（例如 `farewell-xinyu`），設為 Public。
2. 把 `index.html` 和 `xinyu.mp4` 上傳到 repo 根目錄（Add file → Upload files）。
3. 進入 repo 的 **Settings → Pages**，Source 選 `Deploy from a branch`，Branch 選 `main` / `root`，按 Save。
4. 等 1–2 分鐘，網址會是 `https://<你的帳號>.github.io/farewell-xinyu/`，直接傳給欣宇即可。

手機、電腦都能看；點照片可放大（左右鍵切換），影片點播放即可（播放時會自動停掉背景音樂），右下角可開關背景音樂。

## 檔案說明

| 檔案 | 用途 |
| --- | --- |
| `index.html` | 部署用的成品，單一檔案 |
| `xinyu.mp4` | 影片，需與 `index.html` 一起上傳 |
| `Farewell-Card.dc.html` | 可編輯的原始設計檔（讀取 `img/` 裡的照片） |
| `img/` | 壓縮後的 40 張照片（原檔在 `uploads/`） |

改內容時請編輯 `Farewell-Card.dc.html`，再重新產生 `index.html`。
