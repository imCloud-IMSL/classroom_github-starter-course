# :wave: GitHub 的基礎知識

## 🤓 課程概述和學習成果

本課程的目標是向您簡要介紹 GitHub。我們還將為您提供進一步學習的材料和一些想法，以説明您開始使用我們的平臺。 🚀

## :octocat: Git 與 GitHub

Git 是一個 **分散式版本控制系統(distributed Version Control System, VCS)**, 這意味著它是一個有用的工具，可以輕鬆跟蹤代碼更改、協作和共用。使用 Git，您可以跟蹤對專案所做的更改，以便始終記錄您所做的工作，並在需要時輕鬆恢復到舊版本。它還使與他人合作變得更加容易 - 一組人可以在同一專案上一起工作，並將他們的更改合併到一個最終來源中！

GitHub 是一種通過易於使用的介面在線使用 Git 相同功能的方式。它在整個軟體世界內外用於協作和維護項目的歷史。

GitHub 擁有世界上一些最先進的技術。無論您是在可視化數據還是構建新遊戲，GitHub 上都有一個完整的社區和一套工具可以讓您進入下一步。本課程從 GitHub 的基礎知識開始，但我們稍後將深入探討其餘部分。

## :octocat: 瞭解 GitHub flow 

GitHub flow 是一個羽量級工作流，可讓您輕鬆地在專案上進行試驗和協作，而不會有丟失以前工作的風險。

### 存儲庫 (Repositories)

存儲庫是專案工作發生的地方 - 將其視為項目資料夾。它包含專案的所有文件和修訂歷史記錄。 您可以單獨在儲存庫中工作，也可以邀請其他人與您協作處理這些檔。

### 複製 (Cloning) 

使用 GitHub 建立儲存庫時，該儲存函式庫將遠端☁️儲存在 .您可以克隆儲存庫以在計算機上創建本地副本，然後使用 Git 同步兩者。這樣可以更輕鬆地修復問題、添加或刪除檔以及推送更大的提交。您還可以使用您選擇的編輯工具，而不是 GitHub UI。克隆存儲庫還會提取 GitHub 在該時間點擁有的所有儲存庫數據，包括專案的每個文件和資料夾的所有版本！如果您嘗試使用專案，然後意識到您更喜歡以前的版本，這將很有説明。 
要了解有關複製(Cloning)的更多資訊，請閱讀 ["Cloning a Repository"](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository). 

### 提交(Committing)和推送(Pushing)
**提交** 與 **推送** 是將您在本地計算機上所做的更改添加到GitHub中的遠端存儲庫的方法。這樣，當您準備共用最新作品時，您的教師和/或隊友就可以看到您的最新作品。當您對專案進行了要「檢查點」的更改時，可以進行提交。您還可以添加有用的 **提交消息(commit message)**，以提醒您自己或您的隊友您所做的工作（例如，“添加了包含我們專案相關信息的自述檔”）。

一旦您有一個或多個提交，您準備添加到您的存儲庫，您可以使用 push 命令將這些更改添加到您的遠端儲存庫。承諾和推動起初可能會讓人感覺很新鮮，但我們保證你會習慣的 🙂

## 💻 需要瞭解的 GitHub 術語 

### 存儲庫(Repositories) 
我們已經提到了存儲庫，它們是您的專案工作發生的地方，但讓我們更多地討論它們的細節！隨著你在 GitHub 上工作得越來越多，你會有很多存儲庫，一開始可能會讓人感到困惑。幸運的是，您的 ["GitHub dashboard"](https://docs.github.com/en/github/setting-up-and-managing-your-github-user-account/about-your-personal-dashboard) 有助於輕鬆導航到您的存儲庫並查看有關它們的有用資訊。確保您已登錄以查看它！

存儲庫還包含 **README**s. 您可以將 README 添加到存儲庫中，以告訴其他人您的項目為什麼有用，他們可以對您的項目執行哪些操作，以及他們如何使用它。我們正在使用此自述檔與您交流如何學習 Git 和 GitHub。😄 
要瞭解有關存儲庫的更多資訊，請閱讀 ["Creating, Cloning, and Archiving Repositories"](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/about-repositories) 與 ["About README's"](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/about-readmes). 

### 分支(Branches)
您可以使用 GitHub 上的分支來隔離您不希望合併到最終專案中的工作。分支允許您開發功能，修復錯誤，或在存儲庫的包含區域中安全地試驗新想法。通常，您可以從儲存庫的預設分支 （ main） 建立新分支。這將創建存儲庫的新工作副本供您試驗。一旦您的新更改經過隊友的審閱，或者您對它們感到滿意，您就可以將更改合併到存儲庫的預設分支中。
要了解有關分支的更多資訊，請閱讀 ["About Branches"](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/about-branches).

### 分叉(Forks)
分叉是複製存儲庫的另一種方法，但通常在您想要為其他人的專案做出貢獻時使用。分叉存儲庫允許您在不影響原始項目的情況下自由嘗試更改，並且在為開源軟體專案做出貢獻時非常受歡迎！
要了解有關分叉的更多資訊，請閱讀 ["Fork a repo"](https://docs.github.com/en/github/getting-started-with-github/fork-a-repo)

### 拉取請求(Pull requests)
使用分支時，可以使用拉取請求向其他人告知您要進行的更改，並徵求他們的反饋。拉取請求開啟後，您可以與協作者討論和查看潛在的更改，並在需要時添加更多更改。您可以添加特定人員作為拉取請求的審閱者，這表明您希望他們提供有關更改的反饋！一旦拉取請求，就可以將其合併到您的主分支中。
要了解有關拉取請求的更多資訊，請閱讀 ["About Pull Requests"](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-requests). 

### 問題(Issues)
問題是跟蹤 GitHub 上工作的增強功能、任務或 Bug 的一種方法。問題是跟蹤您要為項目處理的所有任務並讓其他人知道您計劃處理的內容的好方法。您還可以使用問題來告訴最喜歡的開源專案您發現的錯誤或您認為可以添加的功能！

對於較大的專案，您可以在專案板上跟蹤許多問題。GitHub 專案可説明您組織工作並確定其優先順序，您可以閱讀有關它們的更多資訊 ["About Project boards document"](https://docs.github.com/en/github/managing-your-work-on-github/about-project-boards)。您可能不需要專案板來完成任務，但是一旦您轉到更大的項目，它們就是組織團隊工作的好方法！

您還可以將拉取請求和問題連結在一起，以顯示正在進行修復，並在有人合併拉取請求時自動關閉問題。
要瞭解有關問題並將其連結到拉取請求的更多資訊，請閱讀 ["About Issues"](https://docs.github.com/en/github/managing-your-work-on-github/about-issues). 

### 個人資料(User profile)

您的個人資料頁面通過您感興趣的存儲庫，您所做的貢獻以及您進行的對話，告訴人們您的工作故事。您還可以通過您的個人資料自述檔為世界提供一個獨特的視角，瞭解您是誰。您可以使用您的個人資料讓未來的僱主瞭解您的一切！ 
要瞭解有關您的個人資料頁面與添加和更新README，請閱讀 ["Managing Your Profile README"](https://docs.github.com/en/github/setting-up-and-managing-your-github-profile/managing-your-profile-readme). 

### 在 GitHub 上使用 markdown 

您可能已經注意到了，但是您可以為問題，拉取請求和檔添加一些有趣的樣式。["Markdown"](https://guides.github.com/features/mastering-markdown/) 是一種使用一些簡單語法描述問題、拉取請求和文件樣式的簡單方法。這有助於組織您的資訊，並使其他人更容易閱讀。您還可以放入GIF和圖像來説明傳達您的觀點！
要了解有關使用 GitHub 的 markdown 風格的更多資訊，請閱讀 ["Basic Writing and Formatting Syntax"](https://docs.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax). 

### GitHub 社群互動

GitHub社區是巨大的。有很多類型的人在日常中使用GitHub - 像您這樣的學生，專業開發人員，從事開源專案的業餘愛好者以及剛剛自己進入軟體開發世界的探索者。您可以通過多種方式與更大的 GitHub 社區進行交互，但這裡有三個地方可以從這裡開始。 

#### 收藏(Starring)存儲庫 

如果您發現某個存儲庫很有趣，或者您想跟蹤它，請為其加註星標！當您為存儲庫加註星標時，它也被用作一個信號，以顯示有關 github.com/explore 的更好建議。如果您想返回已加星標的存儲庫，可以通過您的使用者配置檔執行此操作。
要瞭解有關為存儲庫加星標的更多資訊，請閱讀 ["Saving Repositories with Stars"](https://docs.github.com/en/github/getting-started-with-github/saving-repositories-with-stars). 

#### 關注使用者

您可以在 GitHub 上關注使用者，以接收有關其活動的通知，並在其社區中發現專案。當您關注使用者時，他們的公共 GitHub 活動將顯示在您的儀錶板上，以便您可以看到他們正在處理的所有很酷的事情。
要瞭解有關關注使用者的更多資訊，請閱讀 ["Following People"](https://docs.github.com/en/github/getting-started-with-github/following-people).

#### 瀏覽 GitHub Explore

GitHub Explore是一個很好的地方來做到這一點...探索 :smile: 您可以找到新的專案，活動和開發人員進行交互。

您可以查看 GitHub Explore 網站 [github.com/explore](https://github.com/explore)。


## 📝 可選的後續步驟 

* 打開拉取請求，讓您的老師知道您已完成本課程。  
* 在此存儲庫中創建新的 markdown. 讓他們知道你學到了什麼，對甚麼仍然感到困惑！嘗試不同的風格！
* 創建您的個人資料 README。讓世界更多地瞭解你！你對學習什麼感興趣？你在做什麼？你最喜歡的愛好是什麼？要瞭解有關創建個人資料 README 的更多資訊，請參閱文檔 ["Managing Your Profile README"](https://docs.github.com/en/github/setting-up-and-managing-your-github-profile/managing-your-profile-readme).
* 到用戶儀錶板並創建新的儲存庫。試驗該存儲庫中的功能以熟悉它們。
* [讓我們知道您喜歡或不喜歡本課程內容的內容](https://support.github.com/contact/education). 您希望看到更多什麼？什麼對你的學習之旅感興趣或有説明？

## 📚  補充資料 
* [A short video explaining what GitHub is](https://www.youtube.com/watch?v=w3jLJU7DT5E&feature=youtu.be) 
* [Git and GitHub learning resources](https://docs.github.com/en/github/getting-started-with-github/git-and-github-learning-resources) 
* [Understanding the GitHub flow](https://guides.github.com/introduction/flow/)
* [How to use GitHub branches](https://www.youtube.com/watch?v=H5GJfcp3p4Q&feature=youtu.be)
* [Interactive Git training materials](https://githubtraining.github.io/training-manual/#/01_getting_ready_for_class)
* [GitHub's Learning Lab](https://lab.github.com/)
* [Education community forum](https://education.github.community/)
* [GitHub community forum](https://github.community/)
