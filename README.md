# volterra-hands-on

## 最初に

このドキュメントはVolterraの各種機能を習得するためのハンズオントレーニング資料です。

必要条件

* Teams以上のVolterraテナント
* 2つ以上のVolterra Site
* kubectlが動作する端末
* Volterra APIに接続できるインターネット等の環境
* vesctlを使用する場合はMacOSまたはLinux端末
* FirefoxまたはChrome (または互換ブラウザ)

<b>契約によってはInstance料などの課金がかかる場合があります。</b>

## ハンズオントレーニングシナリオ

1. [vesctlの使用方法](<how_to_use_vesctl.md>)
1. [Siteの作成(Multi NIC/Managed K8s/GPUなど)](<./how_to_create_site.md>)
1. [Site to Siteの暗号化トンネル通信](<./how_to_create_site_2_site.md>)
1. Service policy/Network policyによる通信制御
1. Forward proxyによるEgress 制御
1. Multi cluster Service MeshとService Mesh Graph
