# すこん部員のなにがし

sukonbu.xyz のポータルサイトです。

## 構成

```
.
├── index.html    # ポータルページ
├── Dockerfile    # Nginx配信用
└── README.md
```

## ローカル確認

ブラウザで `index.html` を直接開くだけで確認できます。

## Docker での起動

```bash
docker build -t sukonbu-portal .
docker run -p 8080:80 sukonbu-portal
```

起動後、http://localhost:8080 でアクセスできます。

## リンク

| サービス | URL |
|---|---|
| 積みログ | https://pmm.sukonbu.xyz |
