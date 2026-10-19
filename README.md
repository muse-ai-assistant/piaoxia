# 🧾 票匣 · Piaoxia

电子发票批量识别建台账。上传发票文件，自动提取关键信息生成台账，可导出 CSV。

**在线体验 → https://muse-ai-assistant.github.io/piaoxia/**

## 功能

- 📥 支持 PDF / OFD / 图片（拍照/截图 OCR）
- 🔍 自动识别：发票类型、发票代码、发票号码、开票日期、价税合计、不含税金额、税额、销售方
- 🧮 价税合计 / 税额自动汇总
- 📤 导出 CSV、一键复制台账
- ⚠️ 重复发票提示；台账本地持久化（localStorage）
- 🗑️ 未识别文件可单独删除

## 技术

pdf.js（PDF 解析）、JSZip + XML 坐标排序（OFD 解包）、Tesseract.js（图片 OCR，首次使用按需下载）。

## 隐私

所有解析在本地完成，发票内容不上传服务器。

## License

MIT
