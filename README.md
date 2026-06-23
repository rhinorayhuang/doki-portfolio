# Doki GSAP CCTV Video Demo

## 使用方式

解壓縮後用本機 server 開啟：

```bash
cd doki-gsap-video-demo
python -m http.server 5173
```

然後開 `http://localhost:5173`。

## 內容

- 影片作為全螢幕監視器畫面
- ScrollTrigger 控制影片 currentTime
- 加上 CCTV HUD、REC、掃描線、雜訊
- 貓接近鏡頭時加 zoom、blur、shake
- 最後出現 DOKI'S ROOM 主選單
