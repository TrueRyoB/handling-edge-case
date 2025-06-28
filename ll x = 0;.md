#define int long longのみでは、安心できない<br>
単位元(?)をint x = 0;などして放置してると、<br>
integer (32 bits)のまま処理されて、オーバーフロー<br>
<br>
すべての数値のあとにLLをつけよう
