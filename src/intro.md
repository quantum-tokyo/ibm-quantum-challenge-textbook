# IBM Quantum Challengeで学ぶ量子コンピューティング

このページは Quantum Tokyoコミュニティが作成した、IBM Quantum Challenge を題材とした量子コンピューティングの学習教材です。

IBM Quantum Challenge は IBM が主催する量子コンピューターのプログラミングコンテストのことで、2019 年から半年に一度（Spring/Autumn）開催されています。  
オープンソースの量子開発キットの Qiskit を活用して、量子コンピューティングに関する基礎から応用までを学びながら腕を競っています。

本教材では過去の Quantum Challenge の問題を扱いながら量子コンピューティングを学ぶことを目的としています。

## 目次
```{tableofcontents}

```

## Labを始める前に
一部のLabでは実行するにあたってIBM QuantumのAPIトークンを必要とするものがあります。  
自分でハンズオンを進めたい方は以下の手順に沿ってAPIトークン情報の配置を行ってください。

![APIトークンの取得](./resources/ibmq_get_apitoken.png)

1.   [IBM Quantum Platform](https://quantum.ibm.com/)に移動します。
1.   右上にある API トークン (上の図参照) をクリックしてコピーします。
1.   このプロジェクトのルートディレクトリの配下に`.env`ファイルを作成します。
1.   `.env.sample`を参考に、3でコピーしたAPI トークンを`QXToken`の値に貼り付けます。

```
QXToken=[.envを作成し、ここにAPIトークンを貼り付けます]
```