# 待ち行列理論

## 待ち行列理論に関するコード
1. MMc.ipynb:  M/M/c に関するシミュレーション
- 客の到着間隔とサービス時間はそれぞれ独立な指数分布に従い, サーバー数c個でサービスを行う.

2. priority_2type_jobs.ipynb: 2種類のジョブの優先付きシステム (M/M型)
- ジョブ1は優先権を持っており, 行列で待っているジョブ2よりも先に処理される.

3. preemptive_2type_jobs.ipynb: ２種類のジョブの割り込みシステム (M/M型)
- ジョブ2がサービス中であってもジョブ1が到着した際はジョブ2のサービスは停止し, ジョブ1のサービスを開始する.

4. jsq.ipynb: 2サーバーのうち, 行列が短いほうに並ぶ.

5. 冗長化システム

### 1. M/M/c


### 2. 冗長化モデル
#### (a) N型
2種類のジョブがシステムに到着し, サービスを受ける

#### (b) W型

#### (c) M型

![redundancy](https://user-images.githubusercontent.com/78849474/152199948-30e9cd91-7e6d-4de3-9487-99f09201dfcc.png)


### 参考資料
- https://www.youtube.com/watch?v=eSNfC-HOl44

- https://simpy.readthedocs.io/en/latest/topical_guides/resources.html

- https://medium.com/swlh/simulating-a-parallel-queueing-system-with-simpy-6b7fcb6b1ca1

- Mor Harchol-Balter, Open problems in queueing theory inspired by datacenter computing, 2021, Queueuing Systems
https://link.springer.com/article/10.1007/s11134-016-9485-y
