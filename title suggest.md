RISC-V　LLVM　自動ベクトル化　独自プロセッサ　アセンブリコード生成　バックエンド　

ベクトル処理機能を備えた独自プロセッサ向けのLLVMによる自動ベクトル化を用いたアセンブリコード生成バックエンドの開発

LLVMによる自動ベクトル化を用いたベクトル処理機能を備えた独自プロセッサ向けアセンブリコード生成のためのバックエンド開発

独自プロセッサのためのLLVMによる自動ベクトル化を用いたアセンブリコード生成バックエンドの開発

LLVMによる自動ベクトル化を用いた独自プロセッサのためのアセンブリコード生成バックエンドの開発

独自プロセッサ向けアセンブリコード生成のためのLLVMによる自動ベクトル化を用いたバックエンドの開発


独自にベクトル拡張したRISC-Vのアセンブリコードを生成するコンパイラの開発を目的として、コンパイラ基盤であるLLVMを用いた開発を行なう。
LLVMはフロントエンド、ミドルエンド、バックエンドに分かれておりそれぞれソースコードの中間表現への変換、中間表現の最適化、中間表現からアセンブリコードの生成を行っている。
LLVMにはすでにRISC-Vのアセンブリコードを生成するためのバックエンドがあるためこれを改良し、独自のベクトル拡張命令を生成を実現する。