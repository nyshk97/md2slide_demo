# reveal-pon

markdown + GitHub Actions + GitHub Pages
でスライドを作成、共有できるサービスを触ってみた

---

# 良いと思ったところ

- データを全て自分の GitHub リポジトリで管理できる
- 自動でデプロイしてくれて楽
- URL を共有すればどの端末からでも手軽に閲覧できる
- 常に最新版が表示されるので、発表ギリギリまで編集できる
- 独自の記法が無いので学習コストがかからない
- デザインも普通にいい感じ

---

# 使い方

1. [GitHub](https://github.com/mikkame/reveal-pon)で**Use this template**をクリック
2. **src/slide.md**を編集
3. Commit→Push すると自動で CI が動く
4. GitHub Pages を有効化(Settings > GitHub Pages > Source : select gh-pages)
5. README を編集(任意)

---

# Markdown テスト 1

- apple
- banana
- orange

[link](https://google.com)

```rb
@user = User.find(params[:id])
```

`Baseball`、`Football`、`Basketball`

> Quotation

---

# Markdown テスト 2

## h2

### h3

#### h4

![d0ne1sのプロフィール画像](https://pbs.twimg.com/profile_images/1178198791070998530/dKRSgiza_400x400.jpg)
