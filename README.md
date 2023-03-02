# nstrum.netのWebサイト

## 環境構築から編集作業を始めるまでの手順

Linux/macOS(Windowsはわかりません):

1. goをインストールする(aptで入れないで公式手順で)
2. `~/go/bin/`にPATH通す
3. hugoのインストール
    ```bash
	go install -tags extended github.com/gohugoio/hugo@latest
	```
4. git cloneして作業開始
	```bash
	git clone --recursive https://github.com/nstrum-net/nstrum-web.git
	cd nstrum-web
	```

## 新ページを作る方法

固定ページ
```
hugo new pages/hoge.md
```

ブログ
```
hugo new blog/hoge.md
```
