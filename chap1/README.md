# 第1章 アルゴリズムと計算量
## 1.1 導入問題
### A01
- 1文字の入力の受け取りは `N = int(input())`

### B01
- 2文字の入力の受け取りは `A, B = map(int, input().split())`

## 1.2 全探索(1)
- 複数の入力の受け取りは `A = list(map(int, input().split()))`

## 1.3 全探索(2)
### B03
- 一つのリストの中で3つの数字を選んでそれらの和を求める、という処理を全探索でやっている（ [b03.py](https://github.com/TakutoHashimoto/atcoder_tessoku/blob/main/chap1/src/b03.py) ）
- `combintations` 関数を使うともう少しスマートに書ける（ [b03_2.py](https://github.com/TakutoHashimoto/atcoder_tessoku/blob/main/chap1/src/b03_2.py) ）