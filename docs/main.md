---
marp: true
theme: gaia
paginate: true
backgroundImage: url('https://marp.app/assets/hero-background.jpg')
---

# Git and GitHub tutorial

**@ 2020-11-10 / by Akio Taniguchi (A-lab, postdoc)**

- **目的：**
    - 世界標準のバージョン管理システム[Git](https://git-scm.com/)と開発プラットフォーム[GitHub](https://github.com/)を使ったソフトウェア開発の方法をざっくり学ぶ
- **目標：**
    - 実際にGitを使って[A研のGitHub organization](https://github.com/a-lab-nagoya)上のリポジトリにコミット（コードを登録）することで開発の流れを理解する

---

## Contents

1. バージョン管理とは何か・なぜ必要か
1. バージョン管理システムGit
1. ソフトウェア開発プラットフォームGitHub
1. GitとGitHubを使った開発の流れ
1. [a-lab-nagoya/playground](https://github.com/a-lab-nagoya/playground)を使ったチュートリアル

---

## バージョン管理とは何か

- **バージョン管理（en: version control）**
    - ファイルやディレクトリ内容のバージョン（変更履歴＝誰がいつどのような変更を加えたか）を保存して、変更内容を確認したり任意の時点に戻したりできるようにすること
- **バージョン管理システム（en: version control system or VCS）**
    - バージョン管理を支援するコマンドラインツールやアプリ
- **色々なバージョン管理システム**
    - Git, Subversion, Mercurial: コマンドラインツール
    - macOS Time Machine: Mac全体のバックアップ

