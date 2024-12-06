# FastChat

MT-Bench & MT-Bench-TW w/Azure OpenAI Client

## 注意事項
這是一個 Fork 分支，我們進行了一些較為**暴力**的改動，使該框架的 MT-Bench 能夠被整合在我們的環境中，關於 Fast-Chat 的其他功能可能會無法使用。

具體變動如下:
- 使用 Azure OpenAI Client (無提供 OpenAI Client選項)
- 升級至 OpenAI Package 1.0+
- 升級至 Pydantic v2
- 整合 MT-Bench-TW

### Usage
見 fastchat/llm_judge/README.md