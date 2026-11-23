# 寸耕堂醫案（1793 年序刊，日本國立公文書館 303-0108） / Cungengtang yi’an [Medical Cases of Cungengtang]: Transcription Dataset

《寸耕堂醫案》是清代林玉友編寫的病例集，記求診經過、脈象、用藥及病程變化。底本為日本國立公文書館 303-0108 乾隆五十八年（1793）序刊本，含序、醫案與可辨版心。資料集提供逐幅對應原圖的漢文 TXT、JSON、TEI XML，可檢索病名、脈象與歷史診療記述。

Lin Yuyou’s Cungengtang yi’an (Medical Cases of Cungengtang) records patient histories, pulse findings, therapies and follow-up in Qing China. The base edition is catalogued with a 1793 preface and held at the National Archives of Japan (303-0108). Searchable Literary Chinese TXT, JSON and TEI XML link transcription units to their source images.

## 來源與範圍 / Source and coverage

涵蓋館方 43 幅影像。第 13 幅版心有「完」，第 14 幅右半無正文，左半接續印文本並有文意跳接。第 42 幅右半末欄的文句在冊內中斷，左半無正文，下一幅為封底。以館方影像序列為範圍，未補入其他版本。

Covers all 43 images in the holding institution’s sequence. Frame 13 has an ending mark in the margin. Frame 14 has no text on the right and resumes mid-passage on the left. The final printed passage breaks off on the right of frame 42. Its left half has no main text; frame 43 is the back cover. No other edition contributes text.

[館藏書目 / Catalogue](https://www.digital.archives.go.jp/file/1077787) · [IIIF manifest](https://www.digital.archives.go.jp/api/iiif/1077787/manifest.json) · [館方再利用政策 / Reuse](https://www.digital.archives.go.jp/secondary-use)

本版 **0.2.0 原圖覆核版**。43 幅，825 個定位單元，標題、正文與夾註共 12492 個 Unicode 碼點（含疑字標記）。目前 3 處以方框標出。以另一套獨立本機 OCR 逐欄比對，對差異、副文本、疑字及單方區塊回看原圖，保留未解。完整人類二校尚未進行。

**Version 0.2.0 · Image-checked revision.** Compared each source image with a separate local OCR pass. Reading disagreements, marginal text and ambiguous signs were checked against the images. Full human proofreading is pending.

## 使用檔案 / Files

| 檔案 | 用法 |
| --- | --- |
| [transcription.txt](transcription.txt) | 純文字，依影像編號與欄序閱讀。版心、題籤與印記另見 JSON 和 TEI。 |
| [transcription.json](transcription.json) | 逐幅、逐欄可檢索。每幅附館方來源與 SHA-256，每欄附近似像素框。 |
| [transcription.tei.xml](transcription.tei.xml) | TEI P5 編碼，含原圖區域、版面類別、疑字及欄位定位。 |
| [uncertainties.json](uncertainties.json) | 方框疑字的位置、狀態和原圖入口。 |
| [corrections.json](corrections.json) | 覆核訂正的位置與理由。 |
| [transcription-policy.md](transcription-policy.md) | 讀序、原字記錄規則與限制。 |
| [provenance.json](provenance.json) · [validation.json](validation.json) | 底本、逐幅狀態及格式實測紀錄。 |

以上正文為醫學史史料。格式、雜湊和 DOI 可用於定位與驗證檔案。讀字準確率、專家審定及同儕審查尚未量測或完成。公開包以來源連結回映影像，完整模型提示與專用辨識實作保留於工作端。

## 權利與引用 / Rights and citation

1793 年序刊原文屬公有領域。館方掃描依日本國立公文書館公告可再利用，請來自原件連結取圖並註明出處。新增編輯說明與資料編碼依 CC BY 4.0 提供。

The historical work is in the public domain. The National Archives of Japan permits reuse of its scans under the linked statement. Newly written documentation and original data encoding are provided under CC BY 4.0.

修改前文字由 [初錄 v0.1.0](https://github.com/poplolioi11/naj-303-0108-cungengtang-yian/releases/tag/v0.1.0) 保存。 建議依 [CITATION.cff](CITATION.cff) 引用所用版本。

## 固定封存 / Archived versions

[覆核版 v0.2.0](https://doi.org/10.5281/zenodo.24455522) · [初錄 v0.1.0](https://doi.org/10.5281/zenodo.24455414) · [版本系列 / All versions](https://doi.org/10.5281/zenodo.24455413)
