# goshirase
twitter bot using golang

# memo
## goshirase簡易版
CLI化
テストコード追加
Dockerfileのメンテ
~~対象ユーザー追加~~
~~上限以上の場合フォロワー以外削除~~
~~フォロワー情報登録~~
~~お知らせ機能~~
## goshirase詳細版
~~フォロー時にユーザー登録、フォロワー格納~~
~~次回更新から１日以上たってたら再度取得~~
フォロー外したら、削除
~~メンションされたら比較して結果おしらせ~~

## build
`CGO_ENABLED=0 go build`