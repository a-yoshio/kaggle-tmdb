# Kaggle TMDB Box Office Prediction

Kaggle TMDB Box Office PredictionのKernelを共有するためのレポジトリです。

Kaggle TMDB Box Office Prediction: https://www.kaggle.com/c/tmdb-box-office-prediction

TMDB Web Site: https://www.themoviedb.org/

# Overview

## Description

このコンペティションでは、The Movie Databaseからの7,000本を超える過去の映画のメタデータをもとに、世界中の興行収入全体の試算を行います。提供されるデータには、キャスト、クルー、キーワードのプロット、予算、ポスター、リリース日、言語、制作会社、および国が含まれます。モデル予測に使用するために他の公に利用可能なデータを収集することもできますが、このコンペでは、映画の公開前に利用可能だったデータのみを使用することにします。

## Evaluation

各映画の国際興行収入を予測します。テストセット内のIDごとに、収益の値を予測する必要があります。
最終的な提出物は、予測値と実際の収入の間の二乗平均平方根誤差（RMSLE）で評価されます。

## Timeline

2019年5月30日23時59分まで

## Data Description

このデータセットでは、7398本の映画のデータとThe Movie Database（TMDB）から入手したさまざまなメタデータが提供されています。

（注）多くの映画は何年にもわたって作り直されているため、データ内に同様の映画が複数表示されているように思うかもしれませんが、それらは別々の映画と見なすべきです。さらに、一部の映画では同じようなタイトルがつけられているものがありますが、それらがまったく無関係であることもあります。
