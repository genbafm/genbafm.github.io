---
title: '#2 WASM on 現場'
date: 2017-07-05 17:16:00
tags:
  - WebAssembly
category: podcast
media: /genba-fm-2-wasm.mp3
image: /genbafm-logo.png
type: audio/mpeg
---

<amp-audio>
  <source type="audio/mpeg" src="https://genba.fm/raw-assets/genba-fm-2-wasm.mp3">
</amp-audio>

- [@mizchi](https://twitter.com/mizchi)
- [@armorik83](https://twitter.com/armorik83)
- [likr0](https://www.facebook.com/likr0)

likr0(尾上) さんをゲストにお迎えして WebAssembly 周辺について話を聞きました。
mizchi がちょっと酒入って酔ってる + 83さんの音声の収録を失敗したので、思い出しながら後付で別撮りしたという感じになってます。

## タイムテーブル

- 00:00 挨拶とゲスト尾上さんの自己紹介
- 00:58 尾上さんをゲストに招いた経緯
- 02:07 WebAssemblyはなぜ必要とされたか
- 04:40 「WASMはもう使えるようになってきたなっていう印象を持っている」
- 05:23 WASMはasm.jsよりパース速度、実行速度を改善した
- 06:11 WASMとasm.jsを比較すると
- 08:20 ES Modulesのローディング周り
- 08:46 WASMをどんなものに使った？
- 09:55 SIMD.js
- 10:47 WASMとJSでは線形代数ライブラリの実行速度の桁が違う
  - ベンチマークとってみた https://likr.github.io/matmul-bench/
- 11:50 巨大なWASMライブラリのファイルサイズ問題
- 13:33 main関数からすべて他の言語で書いて最適化する
- 15:18 WASMの現実的な用途
- 16:02 Virtual DOMのWASM実装
- 16:45 WASMを動作させる環境とブラウザによる実装の差
- 17:35 Emscripten、大統一抽象言語LLVM IR
  - GNUも頑張るらしいよ https://sourceware.org/ml/binutils/2017-03/msg00044.html
- 19:19 手書きasm.js
- 21:23 手書きWASMとWAST
- 23:40 WASMの当初の目論見と現在の高速さ
- 24:21 もし将来JavaScriptに型が付いたらWASMと親和性が上がる？
- 27:00 AssemblyScript
- 27:33 パフォーマンス・チューニングの現場でのWASMの選択肢
- 29:53 GC Integration
- 30:07 あらゆる言語でWebを書く未来はくるか
  - 今wasmがかける言語 https://github.com/mbasso/awesome-wasm#languages
- 32:13 JSの言語仕様でどうしようもないこと
- 33:10 Rustはメジャーな言語
- 36:25 [Quasar](https://github.com/anowell/quasar)
- 37:13 Universal JavaScriptに対するUniversal(好きな言語)という発想
- 38:30 「人類はJavaScriptを手放すべきだ」
- 39:54 Dartの失敗から学ぶことは多い
- 40:45 WASMは標準として生き残り続けるか
- 41:43 将来どんな言語になってもWeb APIに熟知しといたらいい
- 42:04 WASMのスレッドの扱いとWorkerの関係
- 43:25 Vulkan, WebGL, Metal, Web GPU
- 45:30 ブラウザsandbox内の世界とWASM
- 47:19 JavaScriptは難読化されても頑張れば読める、WASMは？
- 49:40 [facebook/prepack](https://github.com/facebook/prepack)
- 51:50 JavaScriptを事前にコンパイルすれば高速になるか？
- 52:37 Rustは楽しい
- 53:30 mizchiのやってみたいこと
- 54:28 ライブラリ読み込みの工夫
- 56:10 いまWASMに足りないものはあるか
- 56:46 EmscriptenのEmbind
- 57:25 複数のWASMモジュールとグルー言語としてのJavaScript
- 58:36 光の速度はどうにもならない、どうやって読み込みを速くするか、あるいはPWA
- 60:04 分割が難しいなら全部WASMでやるか
- 60:50 Emscriptenの機能と学び方
- 62:40 エンドトーク 我々は今のうちに何ができるか
