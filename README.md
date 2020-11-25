## Docker,Prometheus,grafanaの構築
環境
```
Windows10 1909 CPU:Core i9 10940X
Virtulbox 6.1.16 Ubuntu Server 20.04
```
公式ドキュメントを一部簡略化したもの。

#ディレクトリ構造
```
work
↳ docker-compose.yaml
↳prometheus
    ↳ prometheus.yaml
```

以上のディレクトリ配置のようになり、yamlファイルを記述したら
```
docker-compose up -d
```
で動く・・・はず




