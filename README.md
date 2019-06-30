# original-row-reduction
自作した行列における掃き出し法です。

# 目的
現在大学で取り扱っている線形代数の講義で楽するため。また自身のプログラミングの力を向上させるために他のサイトを参考にせず自力で作ることとしました。

# コンセプト
勿論、正方行列の掃き出し法を解けることです。他にも、ループは3回まで、（誤差を嫌って）必ず整数で取り扱う、など自身に制限を課しました。

# 結果
2秒で1000×1000の正方行列程度なら解けます。ただしint型なのでオーバーフロウの可能性があります、もし使うときは適宜long long型にしてください。
