# circleci.hiroga.cc
CircleCI Practice

# ローカル実行
```
circleci local execute --job build
```

# 正規表現
```
# 1.0.9 に対応させたい場合

# WRONG (なぜか)
\d+\.\d+\.\d+\

# RIGHT
/[0-9]+\.[0-9]+\.[0-9]+/
```


# その他
? workflowを設定していないのにjobが実行されるのはどうして？
