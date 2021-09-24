---
layout: exhibition
permalink: /kyoto/exhibition/spirit-of-bijyutsu
title: 田中 信圭の展示ページ
author: spirit-of-bijyutsu
icon: true
---
- 名前： 田中　信圭（スクラッチネーム：spirit-of-bijyutsu）
- 学年：４１歳
- 住んでるところ：奈良市
- プログラミング歴：２０年と少し
- CoderDojo奈良：[https://coderdojo-nara-ikoma.connpass.com/](https://coderdojo-nara-ikoma.connpass.com/)

### やったことのあるプログラミング言語やツール

C言語、エクセル（マクロ、VBA）、Unity（初心者レベル）、Scratch

### 好きな（得意な）プログラミング言語やツール

エクセルのVBAで多面体画像を作るのが好きです。

### いつからプログラミングをやってますか？

大学生になってからです。

## 作品紹介

- 作品名：多面体画像
- 言語（ツール）：エクセル（VBA）

### 多面体画像１
![]({{ site.baseurl }}/assets/images/exhibition/{{ page.author }}/LusterReflection1.png)
![]({{ site.baseurl }}/assets/images/exhibition/{{ page.author }}/MirrorReflection1.png)
![]({{ site.baseurl }}/assets/images/exhibition/{{ page.author }}/CrystalReflection1.png)

### 作品の説明

　エクセルのVBAで、３次元空間内に頂点を配置し、その頂点のデータと、どの頂点によって三角形等が構成されているかというデータ、その三角形のカラーインデックスのデータを予めcsvファイルに作成した上で、逆光線追跡法により、それぞれの画素の色を計算してビットマップファイルに出力しています。

　乱反射モデル(Luster Reflection)の場合には、それぞれの観測点から逆に光線を追跡して多面体模型の表面に至るまでを計算しています。

　これに対して、鏡面反射モデル(Mirror Reflection)の場合には、それぞれの観測点から逆に光線を追跡して多面体模型の表面に達し、更にその面で反射した光が最終的に多面体模型の外側に配置されたスクリーン（光源）に到達するまでを計算しています。

　最後に、屈折反射モデル(Crystal Refraction)の場合には、上の鏡面反射モデルで多面体模型の表面で反射光に加えて屈折光を考慮しています。具体的には、一つの光線を追跡する際に多面体模型表面で光が反射光と屈折光の２つに分岐し、更にそれらの一つ一つの光線が多面体模型表面でさらに反射光と屈折光の２つに分岐するというプロセスを繰り返すことになります。

## これを作ろうと思った理由

　もともと、多面体の模型を画用紙を使って実際に作っていました。

　しかし、画用紙をセロテープや糊でくっつけていたため、経年劣化が激しく、長く鑑賞に耐えるものではありませんでした。それに加え、場所も取りますし、彩色を施すこともできませんでした。

　そこで、コンピュータで画像として出力すれば上記の問題を解決できると思い、手近にあったエクセルのVBAを用いて試行錯誤をしながら逆光線追跡法によるビットマップファイルの作成に辿り着きました。

## この作品はどのように進化しますか？もしくはこのあとどんな作品を作ろうと思っていますか？

　この後、多面体模型を構成する三角形等のサイズが小さくなり、もっと滑らかな表面を表現できるよう進化します。それに伴って、表現できる色彩もより多様になっていきます。

### 多面体画像2
![]({{ site.baseurl }}/assets/images/exhibition/{{ page.author }}/LusterReflection2.png)
![]({{ site.baseurl }}/assets/images/exhibition/{{ page.author }}/MirrorReflection2.png)
![]({{ site.baseurl }}/assets/images/exhibition/{{ page.author }}/CrystalReflection2.png)

### 多面体画像3
![]({{ site.baseurl }}/assets/images/exhibition/{{ page.author }}/LusterReflection3.png)
![]({{ site.baseurl }}/assets/images/exhibition/{{ page.author }}/MirrorReflection3.png)
![]({{ site.baseurl }}/assets/images/exhibition/{{ page.author }}/CrystalReflection3.png)

　そして、様々な外形を持つ多面体模型を作成できるよう進化します。

### 多面体画像作品集
![]({{ site.baseurl }}/assets/images/exhibition/{{ page.author }}/polyhedron01.png)
![]({{ site.baseurl }}/assets/images/exhibition/{{ page.author }}/polyhedron02.png)
![]({{ site.baseurl }}/assets/images/exhibition/{{ page.author }}/polyhedron03.png)
![]({{ site.baseurl }}/assets/images/exhibition/{{ page.author }}/polyhedron04.png)
![]({{ site.baseurl }}/assets/images/exhibition/{{ page.author }}/polyhedron05.png)
![]({{ site.baseurl }}/assets/images/exhibition/{{ page.author }}/polyhedron06.png)
![]({{ site.baseurl }}/assets/images/exhibition/{{ page.author }}/polyhedron07.png)
![]({{ site.baseurl }}/assets/images/exhibition/{{ page.author }}/polyhedron08.png)
![]({{ site.baseurl }}/assets/images/exhibition/{{ page.author }}/polyhedron09.png)
![]({{ site.baseurl }}/assets/images/exhibition/{{ page.author }}/polyhedron10.png)
![]({{ site.baseurl }}/assets/images/exhibition/{{ page.author }}/polyhedron11.png)
![]({{ site.baseurl }}/assets/images/exhibition/{{ page.author }}/polyhedron12.png)
![]({{ site.baseurl }}/assets/images/exhibition/{{ page.author }}/polyhedron13.png)
![]({{ site.baseurl }}/assets/images/exhibition/{{ page.author }}/polyhedron14.png)
![]({{ site.baseurl }}/assets/images/exhibition/{{ page.author }}/polyhedron15.png)
![]({{ site.baseurl }}/assets/images/exhibition/{{ page.author }}/polyhedron16.png)

　また、多面体模型同士を結合して新たな多面体模型を構成できるよう進化します。

### 多面体模型同士の結合
![]({{ site.baseurl }}/assets/images/exhibition/{{ page.author }}/CrystalRefrectionCombined.png)
![]({{ site.baseurl }}/assets/images/exhibition/{{ page.author }}/LusterReflectionCombined.png)

　また、多面体模型を光の速度に近いスピードで回転させた場合にどのように見えるかについて画像の作成ができるように進化します。

[特殊相対論的回転](https://www.notion.so/6b8c1dcf610a4f54a094050ea426c26f?v=b1f3950020844193939e63cb0c39c3f8)

<video controls width="100%">
    <source src="{{ site.baseurl }}/assets/images/exhibition/{{ page.author }}/20210402001_spe_rel_spin.mp4">
</video>

　更に、光のドップラー効果を考慮した場合どのように見えるかを画像で出力し、スクラッチを使って表示させることができるように進化します（[スクラッチのページへのリンクです](https://scratch.mit.edu/projects/510460707/){:target="_blank"}）。
