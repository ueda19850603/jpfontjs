# Vertial File System in pdfmake

> このプログラムはttfフォントデータを、PDFMakeで扱えるようにjs化したものです。

このフォントデータはIPAフォントを利用しています
https://ipafont.ipa.go.jp/old/ipafont/download.html

IPAフォントをPDFMakeによってコンバートし、膨大な文字コードから、次章のサブセットデータだけ抜き出しています。
サブセットに含まれる文字はsubset.txtを参照してください