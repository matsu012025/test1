---
description: "説明文を入力"
model: GPT-4.1
tools: ['edit/editFiles', 'search', 'runCommands', 'atlassian/fetch', 'atlassian/search', 'usages', 'problems', 'fetch', 'githubRepo']
mode: agent
---

## 目的

ファイルの更新を行う

## 手順

1. **[pタグのテキストを変更する]**

現在時刻を取得し、YYYYMMDDdddd形式に変換する。その値をpタグのテキストとして上書きする。

7. **全ての問題が解決するまで繰り返す**

8. **完了報告**
   - 完了したことを報告する。

## 注意事項
- 修正は最小限かつ正確に行う。
- 既存の動作やテストを壊さないように注意する。
- 修正内容はコミットメッセージ指示書に従い記録する。