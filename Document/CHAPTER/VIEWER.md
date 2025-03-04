# CHAPTER/VIEWER #

## Endpoint ##

```
/title/viewer
```

## PUT ##

ビューワーのAPI。

### LOGIN ###

不要

### Request ###

|   パラメータ名    |    必須     |  型   | 説明 |
|:-----------:|:---------:|:----:|:---|
| chapter_id  |    yes    |  id  |    |

### Response ###

|       |                   Proto                   |
|:-----:|:-----------------------------------------:|
| レスポンス | [ViewerView](../../View/ViewerView.proto) |
