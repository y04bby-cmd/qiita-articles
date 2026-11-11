---
title: Python基本コマンド(print編)
tags:
  - Python
  - 初心者
private: false
updated_at: '2026-11-11T12:16:24+09:00'
id: a6fedc61a09fe2ed2a38
organization_url_name: null
slide: false
ignorePublish: false
posting_campaign_uuid: null
agreed_posting_campaign_term: false
---
# python基本関数(print編)
## print
標準出力を行う関数です。
```python
print(*objects, sep=' ', end='/n')
```
sepは区切り文字を指定(デフォルト値は半角スペース)、endは末尾を指定します(デフォルト値は改行)。  
### 例1:
```python
name = '山本'
print('こんにちは', name, 'さん')
print('こんばんは')
```
出力
```text
こんにちは 山本 さん
こんばんは
```
のように1つめのprint関数で半角スペースで区切られかつ、改行されています。

### 例2：
```python
name = '山本'
print('こんにちは', name, 'さん', sep = '+', end = '　')
print('こんばんは')
```
このように区切り文字を+に指定し、末尾を空白に指定すると
```text
こんにちは+山本+さん こんばんは
```
のような出力になります。  
もちろん以下のように数式をprintすることも可能です。  
### 例3:
```python
print(6 * 2)
```
出力
```text
12
```
## 参考文献

- 山田祥寛 『独習Python 第2版』 翔泳社
