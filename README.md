# 我的听书 在线书源（x-qzone 定制版）

本仓库存放 4 个定制书源 jar 及对应在线订阅 json，App 内「源管理 → 添加书源 → 粘贴 json 地址」即可在线安装/更新，无需手动换包。

## 四个在线源

| 书源 | json 导入地址（App 里粘贴这个） |
|---|---|
| 收藏版(35源) | https://cdn.jsdelivr.net/gh/x-qzone/tingshu-sources@main/sources_soys123.json |
| 精选版(20源) | https://cdn.jsdelivr.net/gh/x-qzone/tingshu-sources@main/sources_2026_old.json |
| 音乐源 | https://cdn.jsdelivr.net/gh/x-qzone/tingshu-sources@main/sources_music.json |
| 视频源 | https://cdn.jsdelivr.net/gh/x-qzone/tingshu-sources@main/sources_video.json |

## 文件清单
- sources_soys123.jar / sources_soys123.json —— 收藏版（懒人分类拉全+VIP/精品标记可见、爱听书集数修复）
- sources_2026_old.jar / sources_2026_old.json —— 精选版（懒人分类拉全+VIP/精品标记可见）
- sources_music.jar / sources_music.json —— 音乐源
- sources_video.jar / sources_video.json —— 视频源

## 更新机制
修改 jar 后重新上传同名 jar，并把 json 里 version 数字 +1，App 端会提示更新。

## 说明
- json 里的 download_url 指向 gh-proxy.com 国内加速镜像（GitHub raw 的转发），手机可直接下载 jar；
  若镜像失效，可改为 https://raw.githubusercontent.com/x-qzone/tingshu-sources/main/对应文件名.jar
