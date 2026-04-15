# bu-ketao 專案規範

## 專案定位
繁體中文 LLM 輸出壓縮規則集。純 Markdown 規則檔，無程式碼依賴。

## 檔案結構
- `rules/` — 各平台壓縮規則（Claude Code skill, system prompt, cursorrules）
- `examples/` — before/after 實測對比
- `openspec/` — Spectra SDD 規格管理

## 開發規範
- 所有中文內容使用繁體中文
- 規則修改必須附 before/after 範例驗證
- 新增平台格式時，核心規則從 `rules/system-prompt.md` 衍生，不各自發明
