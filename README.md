# 叩いたコマンド

アプリケーションをスタート
```
kubectl apply -f docker/templates/main.yml --validate=fals
```

# サービスのログ取得

```
kubectl logs -n default service/ssdemo-lb
```

# podを消す

```
kubectl delete -f docker/templates/main.yml
```

# 参考

https://qiita.com/suzukihi724/items/241f7241d297a2d4a55c

https://qiita.com/Takagi_/items/fe6ad7f7dc4115f9dfb3

https://kubernetes.io/ja/docs/reference/kubectl/cheatsheet/