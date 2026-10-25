━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  オーディオスペクトラム表示テンプレ(?) ver_1.00
                                              author:Halkaze

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

### 目次 ###

・概要
・利用方法
・更新履歴
・ライセンス表示

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

### 概要 ###

ダウンロードありがとうございます！
こちらは、コードを用いて音楽を再生し、その音楽の波形を表示するため
のテンプレ(?)となっております。

不具合報告などはこちらまでどうぞ
  ブログ ：https://halkaze.fc2.net/
  Twitter：@halkazeMUGEN1

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

### 利用方法 ###

1. キャラクターのdefファイルに
   [AudioSpectrum]
   dll = (AudioSpectrum.dllへのパス)
   という記述を追加する。

2. Audio.defを形式に従って用意する。
   詳細はAudio.defおよび、Sampleフォルダを参照ください。

3. DLLCALL.cnsを登録する。

以上。

なお、このテンプレ(?)ではあくまでオーディオスペクトラムの表示を可能にする
情報をキャラクターに与えるのみであり、実際のスペクトラムの表示は
キャラクター側の記述により実現しています。
表示のための記述については、Sampleフォルダを参照ください。

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

### 更新履歴 ###

2022/ 1/28: ver_1.00公開

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

### ライセンス表示 ###

コード実現のために利用したFFTSSライブラリの利用にかかるライセンス表示です。
本コードの利用の際にこのライセンスを表示する必要はありません。


Copyright 2002-2007 Akira Nukada. All rights reserved.
Copyright 2002-2007 The SSI Project. All rights reserved.
The Scalable Infrastructure Project, supported by "Development of Software
Infrastructure for Large Scale Scientific Simulation" Team, CREST, JST.
Akira Nishida, Department of Computer Science, The University of Tokyo,
7-3-1 Hongo, Bunkyo-ku, Tokyo 113-8656, Japan.

Redistribution and use in source and binary forms, with or without
 modification, are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice, 
   this list of conditions and the following disclaimer. 
2. Redistributions in binary form must reproduce the above copyright notice,
   this list of conditions and the following disclaimer in the documentation
   and/or other materials provided with the distribution. 
3. Neither the name of the University nor the names of its contributors may 
   be used to endorse or promote products derived from this software without
   specific prior written permission. 

THIS SOFTWARE IS PROVIDED BY THE SCALABLE SOFTWARE INFRASTRUCTURE PROJECT 
``AS IS'' AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED
TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR
PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE SCALABLE SOFTWARE INFRASTRUCTURE
PROJECT BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY,
OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF
SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS
INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN
CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE)
ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE
POSSIBILITY OF SUCH DAMAGE.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
