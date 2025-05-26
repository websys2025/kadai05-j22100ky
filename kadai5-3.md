## 外部APIの呼び出しのミニレポート
### Q3-1. 郵便番号APIについて説明せよ。
* エンドポイントと機能
  * 概要：郵便番号検索APIは、日本郵便が公開している郵便番号データを検索する機能をRESTで提供している。現在使用しているデータは、「2025年4月30日更新分の全国一括データ（加工済バージョン）」である。
  * 機能：郵便番号をクライアント側に出力してもらい、番号通りの住所地を表示する。
* リクエストとレスポンスのフォーマット
  * const zipcode = myForm.zipcode.value;で郵便番号を取得する。const results = data.results;で郵便番号の情報を取得する。const address =　`${results[0].address1}${results[0].address2}${results[0].address3}`;で結果の情報を整形する。document.getElementById("result").innerHTML = address;で結果の取得する。

### Q3-2. 各自で調査したAPIについて説明せよ。
* APIの名称と参照URL
  * Advice Slip API:"https://api.adviceslip.com/advice" 
* エンドポイントと機能
  * APIを読み込みするとadvice英字でランダムな表現が出力される。
* リクエストとレスポンスのフォーマット
  * 
### Q3-3. 感想
* 今回の課題で苦労したこと
* 演習を通して理解できたこと
* Web APIの利便性や課題など
