# 各 API の正常系

# 基本的なユースケース

1. 学習
2. 解析 (1 に対する確認: 学習結果が 1 を反映していること)
3. モデル Save
4. モデル Clear
5. 解析 (4 に対する確認: 結果が空であること)
6. モデル Load
7. 解析 (3, 6 の動作確認: 学習結果が 1 を反映していること)
8. 学習
9. 解析 (8 の動作確認: 学習結果が 1, 8 を反映していること)
10. 常に同じ値を返す API 群: get\_config, get\_status, get\_client