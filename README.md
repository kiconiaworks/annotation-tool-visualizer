# How to use

## 0.1. fontのダウンロード(初回のみ)

```
sh init.sh
```

# 0.2. ライブラリのインストール

```
pipenv --python 3.5
pipenv sync
```

## 1. Annotation toolからデータをダウンロードする

## 2. AWSのクレデンシャル情報をexportする

```
export AWS_ACCESS_KEY_ID="<$AWS_ACCESS_KEY_ID>"
export AWS_SECRET_ACCESS_KEY="<$AWS_SECRET_ACCESS_KEY>"
```

## 3. コマンドを実行する

```
python main.py <$ANNOTATION_FILEPATH> <$OUTPUT_DIR> --bucket <$BUCKET_NAME> --font-size 8
```


# Trouble shooting

## 出力した文字が小さくて読めない

`--font-size` を大きくしましょう

