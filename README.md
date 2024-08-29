# laravel-project
Laravel環境構築用
```
php: 8.3
Mysql: 8.0
nginx:
```

## ディレクトリ構成
```
.
├── README.md (この名前にするとGitHubで見た時にHTMLに変換して表示してくれる)
├── infra (*1)
│   ├── mysql (*1)
│   │   ├── Dockerfile
│   │   └── my.cnf (*1)
│   ├── nginx (*1)
│   │   └── default.conf (*1)
│   └── php (*1)
│       ├── Dockerfile (この名前にするとファイル名の指定を省略できる)
│       └── php.ini (*1)
├── docker-compose.yml (この名前にするとファイル名の指定を省略できる)
└── src (*1)
    └── Laravelをインストールするディレクトリ
```

## 参考
[docker laravelハンズオン](https://qiita.com/ucan-lab/items/56c9dc3cf2e6762672f4#%E5%88%9D%E5%BF%83%E8%80%85%E5%90%91%E3%81%9120%E5%88%86%E3%81%A7laravel%E9%96%8B%E7%99%BA%E7%92%B0%E5%A2%83%E3%82%92%E7%88%86%E9%80%9F%E6%A7%8B%E7%AF%89%E3%81%99%E3%82%8Bdocker%E3%83%8F%E3%83%B3%E3%82%BA%E3%82%AA%E3%83%B3)