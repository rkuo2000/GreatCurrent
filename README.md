# Great Current Music Player
提示詞：
你是一位資深的 WebGL / Three.js 互動前端工程師與創意技術指導。
請用下列歌曲及其Youtube連結的素材製作一個大洋流作品集網頁：
1. [Great_Current](https://youtu.be/JjE2V3kd7kM)
2. [Puma_Wave_Winds](https://youtu.be/SyId28uJqhg?list=PLFG1flT5vVYA)
3. [Puma_March](https://youtu.be/XkIkIrOssVs)
4. [RisingCurrents_TaipeiForward](https://youtu.be/wVKO9PKojRs)
5. [Sunny_After_Rain](https://youtu.be/DI32bnlhJ3o)
6. [Taipei_deserves_Puma](https://youtu.be/obUSoRRy2As)

【首頁】
- 使用上傳的台北大洋流當主視覺背景 (Front_Page.webp)
- 全螢幕循環播放 （預設開啟聲音自動播放，右下角可關閉聲音）
- 影片用 Three.js 著色器渲染，加上跟隨滑鼠的互動效果
- 中央大標題 + 一個「進入作品集」按鈕
- 按下後用全螢幕著色器轉場進入作品頁（往下捲動也能進入）
- 網頁式點唱機，可以整頁翻面換歌曲

【作品頁】
- 每首歌曲使用之靜態畫面 (./assets/*.png)
- 點播放會播放歌曲的mp3 (.assets/*.mp3)
- 點一下，從點擊位置開始用著色器轉場變成動態影片
- 再點一下回到靜態
- 每件首歌曲有 歌名 作者 作詞 作曲、放大觀看按鈕
- 放大觀看時，圖片跟首頁一樣滿版放大到整個視窗，並採用與首頁完全相同的著色器特效（跟隨滑鼠的水波、洋流漂移、緩推鏡與視差、色差、調色、變形鏡頭光斑、暗角、底片顆粒，並隨音樂起伏）
- 作品按響應式設計，左文右圖或上文下圖

【技術要求】
- Three.js 用 cdnjs 的 r128 版本
- 不支援 WebGL 時，退回一般的圓形展開轉場
- 手機版改為單欄
- 支援鍵盤操作與 prefers-reduced-motion

【風格】
好萊塢史詩奇幻預告片風格：黑底、寬銀幕黑邊、Cinzel 字體、
底片顆粒、變形鏡頭光斑、底片燒穿轉場。


