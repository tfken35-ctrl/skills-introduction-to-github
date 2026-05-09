## ステップ 1: ブランチを作成する

_「GitHub 入門」へようこそ！ :wave:_

**GitHub とは？**: GitHub は、バージョン管理に _[Git](https://docs.github.com/get-started/quickstart/github-glossary#git)_ を使うコラボレーションプラットフォームです。
GitHub は、[オープンソース](https://docs.github.com/get-started/quickstart/github-glossary#open-source) ソフトウェアを共有したり貢献したりするための人気のある場所です。

:tv: [動画: GitHub とは？](https://www.youtube.com/watch?v=pBy1zgt0XPc)

**リポジトリとは？**: _[リポジトリ](https://docs.github.com/get-started/quickstart/github-glossary#repository)_ とは、ファイルやフォルダーを含むプロジェクトのことです。
リポジトリでは、ファイルやフォルダーのバージョンを追跡できます。詳しくは、GitHub Docs の
「[リポジトリについて](https://docs.github.com/en/repositories/creating-and-managing-repositories/about-repositories)」を参照してください。

**ブランチとは？**: _[ブランチ](https://docs.github.com/en/get-started/quickstart/github-glossary#branch)_ とは、リポジトリの並行したバージョンのことです。
デフォルトでは、リポジトリには `main` という名前のブランチが 1 つあり、これが正式なブランチとみなされます。
追加のブランチを作成すると、リポジトリの `main` ブランチをコピーして、メインのプロジェクトに影響を与えず安全に変更を加えられます。
多くの人は、プロジェクトの他の部分に影響を与えずに特定の機能へ取り組むためにブランチを使います。

ブランチを使うことで、`main` ブランチから自分の作業を切り離せます。
つまり、あなたが貢献している間も、みんなの作業は安全に保たれます。
詳しくは、「[ブランチについて](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-branches)」を参照してください。

**プロフィール README とは？**: _[プロフィール README](https://docs.github.com/account-and-profile/setting-up-and-managing-your-github-profile/customizing-your-profile/managing-your-profile-readme)_ は、GitHub.com 上でコミュニティに向けて自分のことを紹介できる、GitHub プロフィールの「自己紹介」セクションのようなものです。
GitHub は、プロフィール README をプロフィールページの上部に表示します。詳しくは、「[プロフィール README を管理する](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-github-profile/customizing-your-profile/managing-your-profile-readme)」を参照してください。

![screenshot showing an example profile readme](../images/example-profile-readme.png)

### :keyboard: アクティビティ: 最初のブランチ

1. 新しいブラウザータブを開いて、作成したばかりのリポジトリ（この演習のあなたのコピー）に移動します。そして、このタブの指示を読みながら、もう 1 つのタブで操作を進めてください。

2. リポジトリのヘッダーメニューにある **< > Code** タブに移動します。

   ![screenshot highlighting the code tab](../images/code-tab-highlight.png)

3. **main** ブランチのドロップダウンをクリックします。

   <img width="300" alt="screenshot highlighting the branch selection" src="../images/branch-selection-dropdown.png">

4. **Find or create a branch...** のテキストボックスに `my-first-branch` と入力します。
   
   > **注:** 次のステップへ進むために、この名前がチェックされます。 :wink:

5. **Create branch: `my-first-branch` from main** というテキストをクリックして、ブランチを作成します。

   <img width="300" alt="screenshot highlighting the create branch prompt" src="../images/create-branch-prompt.png">

   - ブランチは自動的に、今作成したブランチへ切り替わります。
   - **main** ブランチのドロップダウンメニューに、新しいブランチ名が表示されます。

6. ブランチが GitHub に push されると、Mona がすぐにあなたの作業をチェックし始めます。少し待ってコメントを確認してください。進捗情報と次のステップが返信されます。


<details>
<summary>困っていますか？ 🤷</summary><br/>

フィードバックが表示されない場合は、次の点を確認してください。
- ブランチ名を正確に `my-first-branch` として作成したか確認してください。接頭辞や接尾辞は付けないでください。

</details>
