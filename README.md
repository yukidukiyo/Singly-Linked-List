# Singly-Linked-List<br>
HSPで単方向リストを使えるようにするモジュールです。

リストは一次元で構成されており、各要素に任意の数だけ値を格納できます。

格納できる値は「整数型」、「実装型」、「文字列型」の中から任意の型を選べます。
<pre>
リスト
  ├─要素id0 = 値1, 値2 
  ├─要素id1 = 値1, 値2, 値3, 値4 
  ├─要素id2 = 値1, 値2, 値3
  ・
  ・
  ・
</pre>
## 関数一覧<br>
### sllist
リストを宣言します。

「sllist arr」と書くと、「arr」変数をリストとして定義します。
### sladd
リストの要素に、値を追加します。

「sladd arr,0,1024」と書くと、リスト「arr」の「要素id0」の末尾に整数値「1024」を追加します。
### slget
リストの要素から、任意の位置の値を取得します。

「res = slget(arr,0,1)」と書くと、リスト「arr」の「要素id1」に格納されている先頭の値を取得し、変数「res」に設定します。

「res = slget(arr,1,0)」と書くと、リスト「arr」の「要素id0」に格納されている二番目の値を取得し、変数「res」に設定します。
### sllength
リストの要素の、値の格納数を取得します。

「res = sllength(arr,1)」と書くと、リスト「arr」の「要素id1」に格納されている値の数を取得し、変数「res」に設定します。
<pre>
リスト
  ├─要素id0 = 値1, 値2 
  ├─要素id1 = 値1, 値2, 値3, 値4 
</pre>
の場合は「4」が取得されます。
