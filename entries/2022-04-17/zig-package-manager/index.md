---
title: Ziglangのパッケージマネージャ
description: サイトのインフラをCloudflare Pagesに移行した
createdAt: 2022-04-18T20:57:32+09:00
---

Ziglangにはまだ公式のパッケージマネージャが存在してない。

そのため、exeやlibで他のパッケージを利用する場合には、`git submodule`かサードパーティのパッケージマネージャを使う必要がある。

submoduleはよいとして、サードパーティのパッケージマネージャは現状自分が調べた範囲内だと以下の2つが存在している。

- Gyro
  - <https://github.com/mattnite/gyro>
  - <https://astrolabe.pm/>
  - 322 Stars(22/4/17時点)
- Zigmod
  - <https://github.com/nektro/zigmod>
  - <https://aquila.red/>
  - <https://nektro.github.io/zigmod/>
  - 253 Stars(22/4/17時点)

ただ、現状はサードパーティのパッケージマネージャを使うよりはsubmoduleを使うほうが無難な気がする。

依存パッケージが増えて管理ができないみたいな困りごとが発生したら使うくらいだろうか。
