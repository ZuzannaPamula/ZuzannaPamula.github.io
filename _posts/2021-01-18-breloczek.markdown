---
layout: post
title:  "Breloczek"
date:   2021-01-18 09:17:58 +0200
categories: jekyll update
---

![Render breloczka](/images/breloczek_render.png)

Celem ćwiczenia było zaprojektowanie świecącego breloczka. Projekt tworzony był w dwuosobowym zespole. 

Breloczek posiada jednostronną płytkę PCB z zamontowanym układem elektronicznym, w którym umieszczono widoczną diodę oraz włącznik. Całość umieściłyśmy w otwieranej obudowie, która umożliwia łatwą wymianę baterii.

Utworzyłyśmy płytkę PCB w programie **Eagle**, zaprojektowałyśmy obudowę w **Fusion 360** oraz wykonałyśmy [dokumentację](/images/Breloczek_Pamula_Mierzejewska.pdf) w **LaTeX**.

## Płytka PCB

![Układ elektroniczny](/images/breloczek_uklad.png)

Stworzyłyśmy układ elektroniczny zapewniający miganie diody po włączeniu za pomocą przełącznika. Dobrałyśmy odpowiednie elementy elektroniczne. Obwód wykonałyśmy przy pomocy programu **Eagle**.  Następnie utworzyłyśmy płytkę PCB. Zapewniłyśmy odpowiednią szerokość ścieżek i odległość między nimi. W płytce wykonałyśmy otwory montażowe.

![Płytka PCB](/images/breloczek_PCB.png)

## Obudowa
Kolejnym etapem tworzenia breloczka było zaprojektowanie 3D obudowy za pomocą programu **Fusion 360**. Wykonałyśmy podwójny spód, co umożliwia wymianę baterii bez narażenia układu elektronicznego na uszkodzenia. W podstawie zaplanowałyśmy podstawki stabilizujące płytkę PCB, a także wykonałyśmy wypustki, które zapewniły unieruchomienie baterii. Montaż elementów zapewniłyśmy dzięki insertom osadzanym na gorąco lub ultradźwiękowo.

![Widok STL](/images/breloczek_stl.png)

W projekcie zachowałyśmy odpowiednią minimalną grubość ścianek. Utworzyłyśmy plik STL umożliwiający druk za pomocą technologii FDM. Dobrałyśmy materiał - ABS. Zapewniłyśmy widoczność diody dzięki krążkowi z czerwonej transparentnej płyty PMMA, który przykleiłyśmy w miejscu nosa renifera. Włącznik umiejscowiłyśmy tak, aby imitował ząb zwierzęcia.

Wykonałyśmy również render elementu.

![Render breloczka](/images/breloczek_render_2.png)
