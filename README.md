# パスワードマネージャー
パスワードを管理するパスワードマネージャーを作成しました。

## 使用方法
1. メニューが表示されるので、希望のメニューを選択してください。
2. `Add Password`: サービス名、ユーザー名、パスワードを入力して下さい。
入力内容を暗号化する為、パスフレーズの設定が求められます。尚、復帰処理が未実装の為、パスフレーズを紛失した場合、情報が取得できなくなります。パスフレーズの管理には十分にご注意ください。
3. `Get Password`: 情報を取得したいサービス名を入力して下さい。暗号化ファイル復号化の為、パスフレーズが求められます。
4. `Exit`:パスワードマネージャーを終了します。
5. 復号化の為に入力したパスフレーズは、一定時間キャッシュされる為、その間は入力がスキップされます。

## 注意事項
1. `bash`以外での動作確認が出来ておりません。スクリプトを実行する際は、`bash`にて操作お願いします。
2. パスフレーズを紛失した場合、保存した情報が取得できなくなります。パスフレーズの管理には十分にご注意ください。 
   
