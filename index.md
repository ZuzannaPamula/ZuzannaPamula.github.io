---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: Moje Projekty
---

# Breloczek

Celem ćwiczenia było zaprojektowanie świecącego breloczka. Projekt tworzony był w dwuosobowym zespole. 

![Render breloczka](/images/breloczek_render.png)

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


# Moduł stolika liniowego

![Rysunek złożeniowy](/images/MSL_rys_zlozeniowy.png)

Celem projektu było stworzenie modułu stolika liniowego (MSL), który umożliwi dokładne pozycjonowanie elementów wzdłuż jednej osi. Zapewniłam możliwość łączenia ze sobą modułów w celu uzyskania manipulatora XY. 

Wykonałam [obliczenia](/images/MSL-22_Pamula_obliczenia.pdf) konstrukcyjne oraz dobrałam odpowiednie elemety z katalogów. Całość rozważań przedstawiłam w dokumentacji. Na tym etapie korzystałam z narzędzi takich jak arkusz **Excel** i **LaTeX**.

Następnie wykonałam [rysunek](/images/MSL-22_Pamula_rysunek.pdf) złożeniowy MSL oraz rysunki części. Przedstawiłam również sposób łączenia modułów, co umożliwia precyzyjne pozycjonowanie elementów na płaszczyźnie. Rysunki wykonałam w programie **AutoCAD**.

![Rysunek łączenie](/images/MSL_rys_laczenie.png)


# Zespół napędu liniowego

Celem projektu było utworzenie zespołu napędu liniowego (ZNL), który umożliwia precyzyjne pozycjonowanie obiektów. Przeprowadziłam szereg obliczeń, które umożliwiły spełnienie wymagań konstrukcyjnych. Utworzyłam [dokumentację techniczną](/images/ZNL-23_Pamula_obliczenia_1.pdf) oraz [dokumentację dotyczącą obliczeń konstrukcyjno - sprawdzających](/images/ZNL-23_Pamula_obliczenia_2.pdf). Na tym etapie korzystałam z narzędzi takich jak arkusz **Excel** i **LaTeX**.

Obecnie pracuję nad rysunkiem złożeniowym oraz rysunkami części. W tym celu korzystam z programu **AutoCAD**.
