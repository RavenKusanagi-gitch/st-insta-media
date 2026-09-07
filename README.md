# st_insta publish_media

Instagram へ渡す**公開済み画像だけ**を置く。
Meta は画像を受け取らず、URL を cURL しに来るので、この木が公開面になる。

**ここへ手で置かない。** 入るのは床・機械検査・目視判定を通った `cut_NN.jpg` だけで、
`python3 tools/ig_render.py --candidate <候補> --stage` が入れる。
