# Data Science for Beginners - 一份課程大綱

[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://github.com/codespaces/new?hide_repo_select=true&ref=main&repo=344191198)

[![GitHub license](https://img.shields.io/github/license/microsoft/Data-Science-For-Beginners.svg)](https://github.com/microsoft/Data-Science-For-Beginners/blob/master/LICENSE)
[![GitHub contributors](https://img.shields.io/github/contributors/microsoft/Data-Science-For-Beginners.svg)](https://GitHub.com/microsoft/Data-Science-For-Beginners/graphs/contributors/)
[![GitHub issues](https://img.shields.io/github/issues/microsoft/Data-Science-For-Beginners.svg)](https://GitHub.com/microsoft/Data-Science-For-Beginners/issues/)
[![GitHub pull-requests](https://img.shields.io/github/issues-pr/microsoft/Data-Science-For-Beginners.svg)](https://GitHub.com/microsoft/Data-Science-For-Beginners/pulls/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

[![GitHub watchers](https://img.shields.io/github/watchers/microsoft/Data-Science-For-Beginners.svg?style=social&label=Watch)](https://GitHub.com/microsoft/Data-Science-For-Beginners/watchers/)
[![GitHub forks](https://img.shields.io/github/forks/microsoft/Data-Science-For-Beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/Data-Science-For-Beginners/network/)
[![GitHub stars](https://img.shields.io/github/stars/microsoft/Data-Science-For-Beginners.svg?style=social&label=Star)](https://GitHub.com/microsoft/Data-Science-For-Beginners/stargazers/)


[![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)

[![Microsoft Foundry Developer Forum](https://img.shields.io/badge/GitHub-Microsoft_Foundry_Developer_Forum-blue?style=for-the-badge&logo=github&color=000000&logoColor=fff)](https://aka.ms/foundry/forum)

微軟 Azure Cloud Advocates 很高興能提供一份為期 10 週、包含 20 課的資料科學課程大綱。每課都包含課前及課後小測、完成課程的文字指示、解答及作業。我們以專案為本的教學法讓你在實作中學習，這是讓新技能紮根的有效方式。

**誠摯感謝我們的作者：** [Jasmine Greenaway](https://www.twitter.com/paladique), [Dmitry Soshnikov](http://soshnikov.com), [Nitya Narasimhan](https://twitter.com/nitya), [Jalen McGee](https://twitter.com/JalenMcG), [Jen Looper](https://twitter.com/jenlooper), [Maud Levy](https://twitter.com/maudstweets), [Tiffany Souterre](https://twitter.com/TiffanySouterre), [Christopher Harrison](https://www.twitter.com/geektrainer)。

**🙏 特別感謝 🙏 我們的 [Microsoft Student Ambassador](https://studentambassadors.microsoft.com/) 作者、審核者及內容貢獻者，** 包括 Aaryan Arora, [Aditya Garg](https://github.com/AdityaGarg00), [Alondra Sanchez](https://www.linkedin.com/in/alondra-sanchez-molina/), [Ankita Singh](https://www.linkedin.com/in/ankitasingh007), [Anupam Mishra](https://www.linkedin.com/in/anupam--mishra/), [Arpita Das](https://www.linkedin.com/in/arpitadas01/), ChhailBihari Dubey, [Dibri Nsofor](https://www.linkedin.com/in/dibrinsofor), [Dishita Bhasin](https://www.linkedin.com/in/dishita-bhasin-7065281bb), [Majd Safi](https://www.linkedin.com/in/majd-s/), [Max Blum](https://www.linkedin.com/in/max-blum-6036a1186/), [Miguel Correa](https://www.linkedin.com/in/miguelmque/), [Mohamma Iftekher (Iftu) Ebne Jalal](https://twitter.com/iftu119), [Nawrin Tabassum](https://www.linkedin.com/in/nawrin-tabassum), [Raymond Wangsa Putra](https://www.linkedin.com/in/raymond-wp/), [Rohit Yadav](https://www.linkedin.com/in/rty2423), Samridhi Sharma, [Sanya Sinha](https://www.linkedin.com/mwlite/in/sanya-sinha-13aab1200),
[Sheena Narula](https://www.linkedin.com/in/sheena-narua-n/), [Tauqeer Ahmad](https://www.linkedin.com/in/tauqeerahmad5201/), Yogendrasingh Pawar , [Vidushi Gupta](https://www.linkedin.com/in/vidushi-gupta07/), [Jasleen Sondhi](https://www.linkedin.com/in/jasleen-sondhi/)

|![Sketchnote by @sketchthedocs https://sketchthedocs.dev](../../translated_images/zh-MO/00-Title.8af36cd35da1ac55.webp)|
|:---:|
| 初學者資料科學 - _手繪筆記由 [@nitya](https://twitter.com/nitya) 製作_ |

### 🌐 多語言支援

#### 透過 GitHub Action 支援（自動且持續更新）

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[阿拉伯語](../ar/README.md) | [孟加拉語](../bn/README.md) | [保加利亞語](../bg/README.md) | [緬甸語（Myanmar）](../my/README.md) | [中文（簡體）](../zh-CN/README.md) | [中文（繁體，香港）](../zh-HK/README.md) | [中文（繁體，澳門）](./README.md) | [中文（繁體，臺灣）](../zh-TW/README.md) | [克羅地亞語](../hr/README.md) | [捷克語](../cs/README.md) | [丹麥語](../da/README.md) | [荷蘭語](../nl/README.md) | [愛沙尼亞語](../et/README.md) | [芬蘭語](../fi/README.md) | [法語](../fr/README.md) | [德語](../de/README.md) | [希臘語](../el/README.md) | [希伯來語](../he/README.md) | [印地語](../hi/README.md) | [匈牙利語](../hu/README.md) | [印尼語](../id/README.md) | [義大利語](../it/README.md) | [日語](../ja/README.md) | [坎納達語](../kn/README.md) | [韓語](../ko/README.md) | [立陶宛語](../lt/README.md) | [馬來語](../ms/README.md) | [馬拉雅拉姆語](../ml/README.md) | [馬拉地語](../mr/README.md) | [尼泊爾語](../ne/README.md) | [尼日利亞皮欽語](../pcm/README.md) | [挪威語](../no/README.md) | [波斯語（法爾西）](../fa/README.md) | [波蘭語](../pl/README.md) | [葡萄牙語（巴西）](../pt-BR/README.md) | [葡萄牙語（葡萄牙）](../pt-PT/README.md) | [旁遮普語（Gurmukhi）](../pa/README.md) | [羅馬尼亞語](../ro/README.md) | [俄語](../ru/README.md) | [塞爾維亞語（西里爾字母）](../sr/README.md) | [斯洛伐克語](../sk/README.md) | [斯洛文尼亞語](../sl/README.md) | [西班牙語](../es/README.md) | [斯瓦希里語](../sw/README.md) | [瑞典語](../sv/README.md) | [他加祿語（菲律賓語）](../tl/README.md) | [泰米爾語](../ta/README.md) | [泰盧固語](../te/README.md) | [泰語](../th/README.md) | [土耳其語](../tr/README.md) | [烏克蘭語](../uk/README.md) | [烏爾都語](../ur/README.md) | [越南語](../vi/README.md)

> **想要本地克隆？**

> 本儲存庫包含 50 多種語言翻譯，會大幅增加下載量。若想克隆但不含翻譯，請使用稀疏簽出：
> ```bash
> git clone --filter=blob:none --sparse https://github.com/microsoft/Data-Science-For-Beginners.git
> cd Data-Science-For-Beginners
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> 這樣你就可以用更快的下載速度取得所有完成課程所需的資料。
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

**若您希望支持額外語言，請參閱[這裡](https://github.com/Azure/co-op-translator/blob/main/getting_started/supported-languages.md)**

#### 加入我們的社區  
[![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)

我們有正在進行的 Discord AI 學習系列，詳細信息及加入請見 [Learn with AI Series](https://aka.ms/learnwithai/discord)，活動時間為 2025 年 9 月 18 日至 30 日。你將會學習使用 GitHub Copilot 做資料科學的技巧與秘訣。

![Learn with AI series](../../translated_images/zh-MO/1.2b28cdc6205e26fe.webp)

# 你是學生嗎？

請先從以下資源開始：

- [學生中心頁面](https://docs.microsoft.com/en-gb/learn/student-hub?WT.mc_id=academic-77958-bethanycheum) 這頁面提供初學者資源、學生套件，甚至獲取免費認證券的途徑。這頁值得收藏並偶爾回來看看，因為內容每月至少調整一次。
- [Microsoft Learn 學生大使](https://studentambassadors.microsoft.com?WT.mc_id=academic-77958-bethanycheum) 加入全球學生大使社群，有可能是踏入微軟的契機。

# 上手指南

## 📚 文件

- **[安裝指南](INSTALLATION.md)** - 初學者一步步安裝教學
- **[使用指南](USAGE.md)** - 範例與常見工作流程
- **[疑難排解](TROUBLESHOOTING.md)** - 常見問題解決方案
- **[貢獻指南](CONTRIBUTING.md)** - 如何對本專案做出貢獻
- **[教師資源](for-teachers.md)** - 教學指導與課堂資料

## 👨‍🎓 學生專區
> **完全初學者**: 資料科學新手？請先從我們的[初學者友好範例](examples/README.md)開始！這些簡單且詳細註解的範例將幫助你在深入全課程前掌握基礎。
> **[學生們](https://aka.ms/student-page)**：欲自行使用課程，請 fork 整個倉庫並依序完成練習，從課前小測開始。閱讀講義並完成後續活動。建議以理解課程內容的方式完成專案，而非直接抄寫解答；不過每一專案導向課程的 /solutions 資料夾有完整解答碼。你也可以與朋友組成讀書會，共同研讀。欲進一步學習，我們推薦[Microsoft Learn](https://docs.microsoft.com/en-us/users/jenlooper-2911/collections/qprpajyoy3x0g7?WT.mc_id=academic-77958-bethanycheum)。

**快速開始：**
1. 查看[安裝指南](INSTALLATION.md)以設置你的環境
2. 閱讀[使用指南](USAGE.md)學習如何使用課程材料
3. 從第一課開始，按順序進行
4. 加入我們的[Discord 社群](https://aka.ms/ds4beginners/discord)尋求幫助

## 👩‍🏫 教師專區

> **教師們**：我們提供了[一些教學建議](for-teachers.md)，歡迎您在[討論區](https://github.com/microsoft/Data-Science-For-Beginners/discussions)留下您的反饋！
## 認識團隊

[![推廣影片](../../ds-for-beginners.gif)](https://youtu.be/8mzavjQSMM4 "推廣影片")

**動圖製作者** [Mohit Jaisal](https://www.linkedin.com/in/mohitjaisal)

> 🎥 點擊上方圖片觀看關於此專案與創建團隊的影片！

## 教學法

在建立本課程時，我們選擇了兩個教學原則：確保課程以專案為基礎，並且包含頻繁的小測驗。透過這系列課程，學生將學習數據科學的基本原理，包括倫理概念、數據準備、不同的數據處理方式、數據視覺化、數據分析、數據科學的實際案例等等。

此外，課前一個低風險的小測驗能幫助學生設定學習該主題的目標，課後的第二個小測驗則確保更好的記憶與吸收。本課程設計靈活且充滿趣味，可全部或部分進行。專案從小規模開始，逐漸變得更為複雜，直至10週的學習周期結束。

> 查閱我們的[行為守則](CODE_OF_CONDUCT.md)、[貢獻指南](CONTRIBUTING.md)、[翻譯指南](TRANSLATIONS.md)。歡迎您的建設性回饋！

## 每堂課包含：

- 選擇性的手繪筆記
- 選擇性的補充影片
- 課前熱身小測驗
- 課文講義
- 對於專案式課程，有一步步的專案製作指引
- 知識檢測
- 挑戰題
- 補充閱讀資料
- 功課
- [課後小測驗](https://ff-quizzes.netlify.app/en/)

> **關於測驗的小提示**：所有測驗都收納於 Quiz-App 資料夾，總計40個測驗，每個測驗含三個問題。測驗會從課程中連結，但也可以在本地執行或部署至 Azure；請參考 `quiz-app` 資料夾中的指示。這些測驗正逐步進行本地化。

## 🎓 初學者友善範例

**第一次接觸數據科學？** 我們創建了特別的[範例目錄](examples/README.md)，提供簡單且註解詳盡的程式碼幫助您入門：

- 🌟 **Hello World** - 您的第一個數據科學程式
- 📂 **資料載入** - 學習讀取並探索資料集
- 📊 **簡單分析** - 計算統計數據並尋找模式
- 📈 **基本視覺化** - 製作圖表與圖形
- 🔬 **實務專案** - 從頭到尾完成工作流程

每個範例都包含詳盡的註解說明每一步，非常適合完全的新手！

👉 **[從範例開始](examples/README.md)** 👈

## 課程

|![ @sketchthedocs 的手繪筆記 https://sketchthedocs.dev](../../translated_images/zh-MO/00-Roadmap.4905d6567dff4753.webp)|
|:---:|
| 初學者數據科學課程地圖 - _手繪筆記由 [@nitya](https://twitter.com/nitya) 製作_ |


| 課程編號 | 主題 | 課程分類 | 學習目標 | 連結課程 | 作者 |
| :-----------: | :----------------------------------------: | :--------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------: | :----: |
| 01 | 定義數據科學 | [介紹](1-Introduction/README.md) | 了解數據科學背後的基本概念，以及其與人工智能、機器學習及大數據的關係。 | [課程](1-Introduction/01-defining-data-science/README.md) [影片](https://youtu.be/beZ7Mb_oz9I) | [Dmitry](http://soshnikov.com) |
| 02 | 數據科學倫理 | [介紹](1-Introduction/README.md) | 數據倫理概念、挑戰和框架。 | [課程](1-Introduction/02-ethics/README.md) | [Nitya](https://twitter.com/nitya) |
| 03 | 定義數據 | [介紹](1-Introduction/README.md) | 瞭解數據如何分類及其常見來源。 | [課程](1-Introduction/03-defining-data/README.md) | [Jasmine](https://www.twitter.com/paladique) |
| 04 | 統計與機率導論 | [介紹](1-Introduction/README.md) | 使用機率與統計數學技術來理解數據。 | [課程](1-Introduction/04-stats-and-probability/README.md) [影片](https://youtu.be/Z5Zy85g4Yjw) | [Dmitry](http://soshnikov.com) |
| 05 | 使用關聯式數據 | [資料操作](2-Working-With-Data/README.md) | 介紹關聯式數據及如何使用結構化查詢語言(SQL，發音「see-quell」)來探索和分析關聯式資料的基礎。 | [課程](2-Working-With-Data/05-relational-databases/README.md) | [Christopher](https://www.twitter.com/geektrainer) |
| 06 | 使用 NoSQL 數據 | [資料操作](2-Working-With-Data/README.md) | 介紹非關聯式數據、各類型別以及如何探索和分析文件型資料庫的基礎。 | [課程](2-Working-With-Data/06-non-relational/README.md) | [Jasmine](https://twitter.com/paladique) |
| 07 | 使用 Python | [資料操作](2-Working-With-Data/README.md) | 使用 Python 及如 Pandas 等函式庫進行數據探索的基礎。建議具備 Python 程式設計基礎。 | [課程](2-Working-With-Data/07-python/README.md) [影片](https://youtu.be/dZjWOGbsN4Y) | [Dmitry](http://soshnikov.com) |
| 08 | 數據準備 | [資料操作](2-Working-With-Data/README.md) | 涵蓋清理與轉換數據的技術，應對遺失、不準確及不完整數據的挑戰。 | [課程](2-Working-With-Data/08-data-preparation/README.md) | [Jasmine](https://www.twitter.com/paladique) |
| 09 | 量化視覺化 | [數據視覺化](3-Data-Visualization/README.md) | 學習如何使用 Matplotlib 視覺化鳥類資料 🦆 | [課程](3-Data-Visualization/09-visualization-quantities/README.md) | [Jen](https://twitter.com/jenlooper) |
| 10 | 數據分布視覺化 | [數據視覺化](3-Data-Visualization/README.md) | 視覺化區間內的觀察與趨勢。 | [課程](3-Data-Visualization/10-visualization-distributions/README.md) | [Jen](https://twitter.com/jenlooper) |
| 11 | 比例視覺化 | [數據視覺化](3-Data-Visualization/README.md) | 視覺化離散與群組百分比。 | [課程](3-Data-Visualization/11-visualization-proportions/README.md) | [Jen](https://twitter.com/jenlooper) |
| 12 | 關係視覺化 | [數據視覺化](3-Data-Visualization/README.md) | 視覺化資料集及其變數間的連結與關聯。 | [課程](3-Data-Visualization/12-visualization-relationships/README.md) | [Jen](https://twitter.com/jenlooper) |
| 13 | 有意義的視覺化 | [數據視覺化](3-Data-Visualization/README.md) | 製作有效解決問題與洞察的有價值視覺化的技巧與指導。 | [課程](3-Data-Visualization/13-meaningful-visualizations/README.md) | [Jen](https://twitter.com/jenlooper) |
| 14 | 數據科學生命週期導論 | [生命週期](4-Data-Science-Lifecycle/README.md) | 介紹數據科學生命週期及其首步──獲取與擷取數據。 | [課程](4-Data-Science-Lifecycle/14-Introduction/README.md) | [Jasmine](https://twitter.com/paladique) |
| 15 | 分析階段 | [生命週期](4-Data-Science-Lifecycle/README.md) | 數據科學生命週期中專注於分析數據的階段技巧。 | [課程](4-Data-Science-Lifecycle/15-analyzing/README.md) | [Jasmine](https://twitter.com/paladique) |
| 16 | 溝通階段 | [生命週期](4-Data-Science-Lifecycle/README.md) | 數據科學生命週期中專注於以便於決策者理解的方式呈現數據洞察的階段。 | [課程](4-Data-Science-Lifecycle/16-communication/README.md) | [Jalen](https://twitter.com/JalenMcG) |
| 17 | 雲端數據科學 | [雲端數據](5-Data-Science-In-Cloud/README.md) | 介紹雲端數據科學及其優勢的系列課程。 | [課程](5-Data-Science-In-Cloud/17-Introduction/README.md) | [Tiffany](https://twitter.com/TiffanySouterre) 及 [Maud](https://twitter.com/maudstweets) |
| 18 | 雲端數據科學 | [雲端數據](5-Data-Science-In-Cloud/README.md) | 使用 Low Code 工具訓練模型。 | [課程](5-Data-Science-In-Cloud/18-Low-Code/README.md) | [Tiffany](https://twitter.com/TiffanySouterre) 及 [Maud](https://twitter.com/maudstweets) |
| 19 | 雲端數據科學 | [雲端數據](5-Data-Science-In-Cloud/README.md) | 使用 Azure Machine Learning Studio 部署模型。 | [課程](5-Data-Science-In-Cloud/19-Azure/README.md) | [Tiffany](https://twitter.com/TiffanySouterre) 及 [Maud](https://twitter.com/maudstweets) |
| 20 | 真實世界的數據科學 | [真實世界](6-Data-Science-In-Wild/README.md) | 真實世界中由數據科學驅動的專案。 | [課程](6-Data-Science-In-Wild/20-Real-World-Examples/README.md) | [Nitya](https://twitter.com/nitya) |

## GitHub Codespaces

請依照以下步驟以 Codespace 開啟此範例：
1. 點擊 Code 下拉選單並選擇 Open with Codespaces。
2. 在側邊欄底部選擇 + New codespace。
更多資訊請參見 [GitHub 文件](https://docs.github.com/en/codespaces/developing-in-codespaces/creating-a-codespace-for-a-repository#creating-a-codespace)。

## VSCode Remote - Containers
請依照以下步驟，透過本機與 VSCode 並利用 VS Code Remote - Containers 擴充功能，在容器中開啟此儲存庫：

1. 若首次使用開發容器，請確認系統符合先決條件（例如已安裝 Docker），詳見[入門文件](https://code.visualstudio.com/docs/devcontainers/containers#_getting-started)。

使用此儲存庫，可選擇以隔離的 Docker 磁碟區開啟：

**注意**：背後將使用 Remote-Containers: **Clone Repository in Container Volume...** 指令，在 Docker 磁碟區克隆原始碼，而非使用本地檔案系統。[Volumes](https://docs.docker.com/storage/volumes/) 是持久化容器數據的推薦方式。

或開啟本地克隆或下載的儲存庫版本：

- 將儲存庫克隆至本機檔案系統。
- 按 F1 並選擇 **Remote-Containers: Open Folder in Container...** 指令。
- 選擇該資料夾的複本，等候容器啟動後開始試用。

## 離線存取

您可以透過使用 [Docsify](https://docsify.js.org/#/) 離線瀏覽此文件。請先分叉此儲存庫，[在本機安裝 Docsify](https://docsify.js.org/#/quickstart)，然後在此儲存庫根目錄輸入 `docsify serve`。網站將在本機的3000埠運行：`localhost:3000`。

> 注意，使用 Docsify 時不會渲染筆記本內容，若需執行筆記本，請在 VS Code 中透過 Python 核心另行執行。

## 其他課程

我們的團隊也提供其他課程！敬請參考：

<!-- CO-OP TRANSLATOR OTHER COURSES START -->
### LangChain
[![LangChain4j 初學者指南](https://img.shields.io/badge/LangChain4j%20for%20Beginners-22C55E?style=for-the-badge&&labelColor=E5E7EB&color=0553D6)](https://aka.ms/langchain4j-for-beginners)
[![LangChain.js for Beginners](https://img.shields.io/badge/LangChain.js%20for%20Beginners-22C55E?style=for-the-badge&labelColor=E5E7EB&color=0553D6)](https://aka.ms/langchainjs-for-beginners?WT.mc_id=m365-94501-dwahlin)
[![LangChain for Beginners](https://img.shields.io/badge/LangChain%20for%20Beginners-22C55E?style=for-the-badge&labelColor=E5E7EB&color=0553D6)](https://github.com/microsoft/langchain-for-beginners?WT.mc_id=m365-94501-dwahlin)
---

### Azure / Edge / MCP / Agents
[![AZD for Beginners](https://img.shields.io/badge/AZD%20for%20Beginners-0078D4?style=for-the-badge&labelColor=E5E7EB&color=0078D4)](https://github.com/microsoft/AZD-for-beginners?WT.mc_id=academic-105485-koreyst)
[![Edge AI for Beginners](https://img.shields.io/badge/Edge%20AI%20for%20Beginners-00B8E4?style=for-the-badge&labelColor=E5E7EB&color=00B8E4)](https://github.com/microsoft/edgeai-for-beginners?WT.mc_id=academic-105485-koreyst)
[![MCP for Beginners](https://img.shields.io/badge/MCP%20for%20Beginners-009688?style=for-the-badge&labelColor=E5E7EB&color=009688)](https://github.com/microsoft/mcp-for-beginners?WT.mc_id=academic-105485-koreyst)
[![AI Agents for Beginners](https://img.shields.io/badge/AI%20Agents%20for%20Beginners-00C49A?style=for-the-badge&labelColor=E5E7EB&color=00C49A)](https://github.com/microsoft/ai-agents-for-beginners?WT.mc_id=academic-105485-koreyst)

---
 
### 生成式 AI 系列
[![Generative AI for Beginners](https://img.shields.io/badge/Generative%20AI%20for%20Beginners-8B5CF6?style=for-the-badge&labelColor=E5E7EB&color=8B5CF6)](https://github.com/microsoft/generative-ai-for-beginners?WT.mc_id=academic-105485-koreyst)
[![Generative AI (.NET)](https://img.shields.io/badge/Generative%20AI%20(.NET)-9333EA?style=for-the-badge&labelColor=E5E7EB&color=9333EA)](https://github.com/microsoft/Generative-AI-for-beginners-dotnet?WT.mc_id=academic-105485-koreyst)
[![Generative AI (Java)](https://img.shields.io/badge/Generative%20AI%20(Java)-C084FC?style=for-the-badge&labelColor=E5E7EB&color=C084FC)](https://github.com/microsoft/generative-ai-for-beginners-java?WT.mc_id=academic-105485-koreyst)
[![Generative AI (JavaScript)](https://img.shields.io/badge/Generative%20AI%20(JavaScript)-E879F9?style=for-the-badge&labelColor=E5E7EB&color=E879F9)](https://github.com/microsoft/generative-ai-with-javascript?WT.mc_id=academic-105485-koreyst)

---
 
### 核心學習
[![ML for Beginners](https://img.shields.io/badge/ML%20for%20Beginners-22C55E?style=for-the-badge&labelColor=E5E7EB&color=22C55E)](https://aka.ms/ml-beginners?WT.mc_id=academic-105485-koreyst)
[![Data Science for Beginners](https://img.shields.io/badge/Data%20Science%20for%20Beginners-84CC16?style=for-the-badge&labelColor=E5E7EB&color=84CC16)](https://aka.ms/datascience-beginners?WT.mc_id=academic-105485-koreyst)
[![AI for Beginners](https://img.shields.io/badge/AI%20for%20Beginners-A3E635?style=for-the-badge&labelColor=E5E7EB&color=A3E635)](https://aka.ms/ai-beginners?WT.mc_id=academic-105485-koreyst)
[![Cybersecurity for Beginners](https://img.shields.io/badge/Cybersecurity%20for%20Beginners-F97316?style=for-the-badge&labelColor=E5E7EB&color=F97316)](https://github.com/microsoft/Security-101?WT.mc_id=academic-96948-sayoung)
[![Web Dev for Beginners](https://img.shields.io/badge/Web%20Dev%20for%20Beginners-EC4899?style=for-the-badge&labelColor=E5E7EB&color=EC4899)](https://aka.ms/webdev-beginners?WT.mc_id=academic-105485-koreyst)
[![IoT for Beginners](https://img.shields.io/badge/IoT%20for%20Beginners-14B8A6?style=for-the-badge&labelColor=E5E7EB&color=14B8A6)](https://aka.ms/iot-beginners?WT.mc_id=academic-105485-koreyst)
[![XR Development for Beginners](https://img.shields.io/badge/XR%20Development%20for%20Beginners-38BDF8?style=for-the-badge&labelColor=E5E7EB&color=38BDF8)](https://github.com/microsoft/xr-development-for-beginners?WT.mc_id=academic-105485-koreyst)

---
 
### Copilot 系列
[![Copilot for AI Paired Programming](https://img.shields.io/badge/Copilot%20for%20AI%20Paired%20Programming-FACC15?style=for-the-badge&labelColor=E5E7EB&color=FACC15)](https://aka.ms/GitHubCopilotAI?WT.mc_id=academic-105485-koreyst)
[![Copilot for C#/.NET](https://img.shields.io/badge/Copilot%20for%20C%23/.NET-FBBF24?style=for-the-badge&labelColor=E5E7EB&color=FBBF24)](https://github.com/microsoft/mastering-github-copilot-for-dotnet-csharp-developers?WT.mc_id=academic-105485-koreyst)
[![Copilot Adventure](https://img.shields.io/badge/Copilot%20Adventure-FDE68A?style=for-the-badge&labelColor=E5E7EB&color=FDE68A)](https://github.com/microsoft/CopilotAdventures?WT.mc_id=academic-105485-koreyst)
<!-- CO-OP TRANSLATOR OTHER COURSES END -->

## 獲取幫助

**遇到問題？** 請查看我們的[故障排除指南](TROUBLESHOOTING.md)，以獲取常見問題的解決方案。

如果你卡住了或者對構建 AI 應用有任何疑問，加入其他學習者和有經驗的開發者，一起討論 MCP。這是一個支援性強的社群，歡迎提問並自由分享知識。

[![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)

如果你在構建過程中有產品反饋或發現錯誤，請訪問：

[![Microsoft Foundry Developer Forum](https://img.shields.io/badge/GitHub-Microsoft_Foundry_Developer_Forum-blue?style=for-the-badge&logo=github&color=000000&logoColor=fff)](https://aka.ms/foundry/forum)

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**免責聲明**：
本文件由人工智能翻譯服務 [Co-op Translator](https://github.com/Azure/co-op-translator) 翻譯而成。雖然我們致力於確保準確性，但請注意，自動翻譯可能包含錯誤或不準確之處。原始文件的母語版本應視為權威來源。對於重要資訊，建議使用專業人工翻譯。我們對因使用本翻譯而產生的任何誤解或誤釋概不負責。
<!-- CO-OP TRANSLATOR DISCLAIMER END -->