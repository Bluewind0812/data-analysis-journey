# GitHub 學習日誌：用指令上傳

## 先懂三個詞
- **Repository（repo）**：放在 GitHub 上的專案資料夾
- **Commit**：存一次檔，附一句說明改了什麼
- **Push**：把電腦上的 commit 上傳到 GitHub

每天 commit，GitHub 個人頁的格子就會變綠，這就是「過程」。

## 已經設定好的
- 這個資料夾已經是 git repo，連到 GitHub 上的公開 repo `data-analysis-journey`
- commit 用 GitHub 的 noreply email，真實 email 不會公開
- `.gitignore` 裡列的檔案（例如 `private/`）不會被上傳

## 每天上傳（2 行指令）

在這個資料夾打開 PowerShell（VS Code 的終端機也可以），執行：

```powershell
git add -A; git commit -m "Day 2: Kaggle Python L2"
```

```powershell
git push
```

- `git add -A`：把今天新增、修改的檔案都放進這次 commit
- `git commit -m "..."`：存檔，引號裡寫今天做了什麼，格式 `Day N: 做了什麼`
- `git push`：上傳到 GitHub

上傳前想確認會傳哪些檔案，可以先執行 `git status`。

## 常見狀況
- **`nothing to commit`**：今天沒有改任何檔案，先寫日誌或存練習再 commit
- **跳出 GitHub 登入**：用自己的 GitHub 帳號登入並按授權，之後就會記住

## 注意

- 計量作業答案不要放進公開 repo（同學會抄，也可能違反課程規定）
- 不要上傳密碼、學號、個人資料
- 漏一天沒關係，誠實記錄比連續打卡重要
