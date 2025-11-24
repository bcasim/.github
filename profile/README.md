<div align="center">

<img src="https://bcasim.github.io/images/logo.png" alt="BCASim Logo" width="200" height="auto" />

# BCASim (Blockchain Attack Simulator)

**攻撃分析のためのオープンソース・ブロックチェーンシミュレータ**
<br>
*An Open Source Blockchain Simulator for Attack Analysis*

[公式サイト (Documentation)](https://bcasim.github.io/) • [デモを見る (Demo)](https://github.com/bcasim/bcasim#demo) • [日本語ドキュメント](https://bcasim.github.io/index-jp.html)

---
</div>

## 📖 About BCASim

**BCASim** は、ブロックチェーンネットワークに対する攻撃シミュレーションを行うためのJavaベースのツールです。ノードの動作シナリオやプロトコル特性を柔軟にカスタマイズでき、以下の攻撃シナリオなどを再現・分析することが可能です。

BCASim is a Java-based tool designed to simulate attacks on blockchain networks. Users can customize node behavior scenarios and protocol specifications to analyze various attack vectors, including:

- 💥 **Double Spending Attack** (二重支払い攻撃)
- ⛏️ **Selfish Mining** (セルフィッシュマイニング)
- 🎭 **Sybil Attack** (シビル攻撃)

## 🚀 Key Repositories

| Repository | Description | Tech Stack |
| :--- | :--- | :--- |
| 📦 [**bcasim/bcasim**](https://github.com/bcasim/bcasim) | **Simulator Core**<br>シミュレータ本体。攻撃シナリオの実行とデータ生成を行います。 | `Java` `Maven` |
| 📊 [**bcasim/bcasim-visualization**](https://github.com/bcasim/bcasim-visualization) | **Visualization Tool**<br>シミュレーション結果をブラウザ上で視覚的に確認するためのツールです。 | `JavaScript` |
| 📝 [**bcasim/bcasim.github.io**](https://github.com/bcasim/bcasim.github.io) | **Documentation**<br>利用マニュアルおよび公式サイトのソースコードです。 | `HTML` `CSS` |

## 🛠️ Getting Started

まずは本体のクローンとビルドから始めてください。
To get started, clone and build the core simulator:

```bash
git clone [https://github.com/bcasim/bcasim](https://github.com/bcasim/bcasim)
cd bcasim
mvn clean install
