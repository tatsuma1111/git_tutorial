name: 改善提案フォーム
description: 新機能追加や改善点の提案を行うフォーム
title: "[改善提案] 簡潔なタイトルを入力"
labels:
  - enhancement
  - needs-triage
assignees:
  - your-github-username

body:
  - type: markdown
    attributes:
      value: |
        🚀 **改善案ありがとうございます！**  
        以下の項目をできるだけ詳しくご記入ください。  
        情報が多いほど検討がスムーズになります。

  - type: input
    id: summary
    attributes:
      label: 改善案の概要
      description: 何を改善・追加したいのかを一言でまとめてください。
      placeholder: 例) ダッシュボードのロード時間短縮

  - type: textarea
    id: details
    attributes:
      label: 詳細な説明
      description: なぜこの改善が必要か、背景や課題も含めて記載してください。
      placeholder: 現状の問題点や改善による利点など

  - type: dropdown
    id: impact
    attributes:
      label: 想定される影響範囲
      description: 改善によって影響を受ける領域を選んでください。（複数選択可）
      multiple: true
      options:
        - UI/UX
        - パフォーマンス
        - セキュリティ
        - 開発プロセス
        - ドキュメント

  - type: checkboxes
    id: verification
    attributes:
      label: 事前確認
      description: 以下の点を確認してください。
      options:
        - label: 既存のIssueやPRに同様の提案がないことを確認しました
        - label: この改善の利点とリスクを把握しています
        - label: 必要であればチーム内で事前相談しました

  - type: textarea
    id: additional-info
    attributes:
      label: 補足情報
      description: スクリーンショットや参考資料があれば添付してください。
      placeholder: URLや画像など
