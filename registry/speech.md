# speech — 語音生成（Asa & Wer）
**觸發時機**：需要把文字轉成語音、需要 Asa（台灣女聲）或 Wer（台灣男聲）朗讀任何內容、或需要雙人 Podcast 對話語音。
**能力摘要**：
- Asa（女聲預設）：`zh-TW-HsiaoChenNeural`，清新溫柔，語速 +20%
- Wer（男聲）：`zh-TW-YunJheNeural`，陽光穩重，語速 +20%
- 雙人 Podcast 模式：Asa + Wer 一搭一唱，類似 Google NotebookLM 風格
- 自動輸出語音檔至 `output/`
**無法處理**：客製化聲音、影片配音剪接、非中文語音（需確認模型支援）。
**安裝位置**：`C:\Users\ASUS\.gemini\config\skills\speech\SKILL.md`
**傳達方式**：直接說「請讓 Asa 朗讀以下文字：[文字內容]」即自動調度。
