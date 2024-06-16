---
marp: true
---

# ハッカソン TeamA 発表

### Member

![width:64px](https://github.com/koko-u.png) koko_u
![width:64px](https://github.com/aym-sekiguchi.png) aym-sekiguchi
![width:64px](https://github.com/LalaportK.png) LalaportK

---

# 作成したアプリケーション

## PersuadeMate

プレゼンテーションを補助する便利ツール

---

# アプリケーションの特徴

- 日常生活で「誘い文句の案出」が苦手な人に役に立つツール
- 誘う相手に応じていい感じの誘い文句を生成してくれます
- 生成された誘い文句を、AI が相手に成り代わって評価してくれます

---

# デモ

せきぐちさんによる素晴しいデモをご堪能ください。

[PersuadeMate](https://persuademate-frontend-ovkyr72pqq-an.a.run.app/)

---

# 所感

ハッカソンに参加してみて〜

---

## ![width:48px](https://github.com/aym-sekiguchi.png) せきぐち (1/3)

### 担当したこと

- フロントエンドの実装

---

## ![width:48px](https://github.com/aym-sekiguchi.png) せきぐち (2/3)

### 技術的なポイント

- Next.js を使用して SPA を実現
- 細々した工夫(form のバリデーション、ローディング、GOD のアニメーション)

---

## ![width:48px](https://github.com/aym-sekiguchi.png) せきぐち (3/3)

### フロントエンドを担当して

- 思いつきで実装した GOD だが採用されてしまった
- やりたいことが次々出てきて重かった
- でも楽しい(GOD 動かしたり)

---

## ![width:48px](https://github.com/LalaportK.png) ななみん (1/3)

### 担当したこと

- インフラ構築

---

## ![width:48px](https://github.com/LalaportK.png) ななみん (2/3)

### 技術的なポイント

- Google Cloud の Cloud Build を使った、main ブランチへのプッシュをトリガとしたデプロイ

![width:600px](./images/architecture.png)

---

## ![width:48px](https://github.com/LalaportK.png) ななみん (3/3)

### インフラを担当して

- なれない技術 (Next.js と ASP Core) のデプロイ環境の構築に手間取った
- ビルド失敗も含めてトライアンドエラー多数

![width:600px](./images/build.png)

---

## ![width:48px](https://github.com/koko-u.png) こざき (1/3)

### 担当したこと

- バックエンドの実装
- チームリーダーとしての何か

---

## ![width:48px](https://github.com/koko-u.png) こざき (2/3)

### 技術的なポイント

- ASP.NET Core Web API で実装。テンプレートで楽ちん
- Dependency Injection でダミーや GPT のモデルを切り替え

![width:600px](./images/backend.png)

---

## ![width:48px](https://github.com/koko-u.png) こざき (3/3)

### チーム運営所感

- 開発のモチベーションの維持が難しい。
  仕事なら納期もあるし、後工程の開発もあるしで否が応にも開発するしかないが。
- 縦割り(Frontend, Backend, Infra)の役割分担はよくない。
  機能ごとに分担できた方がより「楽しみ」があった

---

# 総括

---

## 良かった点

- ![width:32px](https://github.com/koko-u.png) これまで OpenAI を遠巻きに眺めているだけだったが、実際に触ってみることができた。
- ![width:32px](https://github.com/LaLaportK.png) 久しぶりにチーム開発できてよかった。
- ![width:32px](https://github.com/aym-sekiguchi.png) 役割分担をしてのチーム開発が個人的にはじめてだったので良い経験になった。

---

## 後悔の残る点

- ![width:32px](https://github.com/koko-u.png) もっと github の機能(例えば、Projects)などを活用しても良かったかもしれない。
- ![width:32px](https://github.com/LaLaportK.png) 自分だけ負担が少なかったのでヘルプに入れればよかった。
- ![width:32px](https://github.com/aym-sekiguchi.png) もっといろんな機能入れたかった。

---

# 以上

ハッカソンの企画・運営ありがとうございました。🙇
