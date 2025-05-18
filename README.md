 (cd "$(git rev-parse --show-toplevel)" && git apply --3way <<'EOF' 
diff --git a/README.md b/README.md
index 8aa09b9..9e1f858 100644
--- a/README.md
+++ b/README.md
@@ -1,2 +1,13 @@
 # Trialtetris
-練習用
+
+ブラウザで遊べる簡易テトリスのサンプルです。
+
+## 遊び方
+
+1. このリポジトリをクローンするかダウンロードします。
+2. `index.html` をブラウザで開くだけでプレイできます。
+   - 左右キー: ブロックの移動
+   - 下キー: ブロックを落とす
+   - `q` / `w`: 回転
+
+特別なビルド手順は必要ありません。
 
EOF
)
