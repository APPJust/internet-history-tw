# 來源清單

查閱日：2026-10-17。主張與來源的對應見 project.json 的 coverage.*.source_ids。

| id | 來源 | 發表 | 連結 |
|---|---|---|---|
| kleinrock | Leonard Kleinrock, The Day the Infant Internet Uttered its First Words (UCLA) | — | https://www.lk.cs.ucla.edu/internet_first_words.html |
| ucla | UCLA Alumni, UCLA History: first host-to-host ARPANET message | — | https://alumni.ucla.edu/ucla-history-45/ |
| isoc | Leiner et al., A Brief History of the Internet (Internet Society) — four hosts by end of 1969 | — | https://www2.cs.arizona.edu/classes/cs525/papers/Brief_History_of_the_Internet.pdf |
| cerfkahn | Cerf & Kahn, A Protocol for Packet Network Intercommunication, IEEE Trans. Comm. COM-22(5) | 1974-05 | https://ethw.org/w/images/9/9d/Ref4_HistoryOfInformation_Cerf-Kahn_TCP-Paper.pdf |
| flagday | Google Blog, Marking the birth of the modern-day Internet (NCP→TCP/IP on 1983-01-01) | — | https://blog.google/inside-google/googlers/marking-birth-of-modern-day-internet/ |
| cernweb | CERN, Web History (1989 proposal; 1993-04-30 public domain) | — | https://web30.web.cern.ch/web-history.html |
| tanet | Wikipedia, TANet (1990 founding; 1991-12-03 64 kbit/s link to JvNCnet, Princeton) | — | https://en.wikipedia.org/wiki/TANet |
| nccu | 政大學術集成：台灣學術網路發展相關論文 | — | https://ah.lib.nccu.edu.tw/bitstream/140.119/114941/1/781.pdf |
| hinet30 | ETtoday，中華電信 HiNet 30 年（1995-04 撥接商轉、1999 ADSL、2007 光世代） | — | https://finance.ettoday.net/news/2949155 |
| ptt | 鏡週刊，PTT 1995-09-14 於台大誕生 | — | https://www.mirrormedia.mg/story/20201120pol001 |
| 4g | 數位時代，中華電信 4G LTE 開台（2014-05-29） | 2014-05-29 | https://www.bnext.com.tw/article/32421/BN-ARTICLE-32421 |
| 5g | 科技新報，台灣進入 5G 時代（2020-06-30 開台） | 2020-07-01 | https://technews.tw/2020/07/01/taiwan-5g-new-life-qa/ |
| matsu1 | 科技新報，台馬海纜 2/2、2/8 相繼受損 | 2023-02-17 | https://technews.tw/2023/02/17/the-submarine-cable-was-damaged-suspected-to-be-caused-by-chinese-ship/ |
| matsu2 | 公視新聞網，馬祖斷纜約 50 天後修復、微波備援頻寬不足 | — | https://news.pts.org.tw/article/623476 |
| leo | 中央社，台灣強化網路韌性 數位部推低軌衛星 2 年計畫 | 2023-02-17 | https://www.cna.com.tw/news/afe/202302170276.aspx |
| twnic | TWNIC，2025 台灣網路報告（摘要） | 2025-12-17 | https://report.twnic.tw/2025/en/assets/download/TWNIC_TaiwanInternetReport_2025_CH_summary.pdf |
| cna2025 | 中央社，2025 台灣網路報告：上網率 88.75%、5G 40.76%、生成式 AI 43.19% | 2025-12-17 | https://www.cna.com.tw/news/afe/202512170362.aspx |

## 五部分對應

- **origin**：1969-10-29 晚間 UCLA 經 ARPANET 傳送 LOGIN 給 SRI，只傳出 LO 即當機，約一小時後登入成功；年底 4 台主機相連。（來源：kleinrock, ucla, isoc）
- **principle**：封包交換：切成帶地址與編號的封包、各自路由、斷線繞道、終點依號重組；對照電路交換。TCP/IP 1974 提出、1983-01-01 ARPANET 全面採用；網際網路（道路）與 WWW（服務）的區別。（來源：cerfkahn, flagday, cernweb）
- **comparison**：台灣上網世代以同一任務（下載 5 MB）與標稱速率換算比較：撥接 56 kbps≈12 分、ADSL 2 Mbps≈20 秒、光纖 100 Mbps≈0.4 秒；行動網路依訊號而定。並列優缺點：光纖需拉線、行動受基地台與訊號影響。（來源：hinet30, 4g, 5g）
- **application**：問題：2023-02-02、02-08 台馬二號、三號海纜相繼斷裂；過程：封包改走微波備援，頻寬遠低於海纜，影片、刷卡、視訊變慢；結果：約 50 天後修復；限制：繞道需要真的有替代路徑且容量足夠。（來源：matsu1, matsu2）
- **outlook**：已公布：數位部 2023 起低軌衛星韌性驗證計畫；現況：2025 個人上網率 88.75%、5G 40.76%、生成式 AI 43.19%；研究中：6G；推測：海纜、微波、衛星多路備援與數位落差是未解問題。（來源：leo, twnic, cna2025）

## 限制與待確認

- TANet 成立年採 1990 年 7 月（教育部電算中心邀集大學）；有鏡像資料寫 1980，判斷為誤植，未取得教育部原始公文。
- 馬祖修復「約 50 天」來自新聞報導，畫面與旁白皆標「約」。
- 速度比較為標稱速率上限的換算（5 MB = 40 Mb），非實測；行動網路不給單一數字。
- 展望中的 6G 屬研究中，多路備援常態化屬推測，畫面以不同標籤區分。
