---
layout: post
title:  "Aplikator kropli do oczu - praca inżynierska"
date:   2023-09-10 09:17:58 +0200
categories: jekyll update
---

![Prototyp aplikatora](/images/zdj_zakraplacz.png)

Celem mojej pracy inżynierskiej jest zaprojektowanie, wykonanie i zaprogramowanie urządzenia umożliwiającego monitorowanie regularności stosowania lekarstw po operacjach okulistycznych.

## Założenia
Podstawowe założenia projektu:

•	Urządzenie zapisuje datę i godzinę aplikacji kropli

•	Obudowa przystosowana do zbiornika z kroplami

•	Nienaruszenie zbiornika z lekarstwem (oryginalne opakowanie)

•	W czasie pomiędzy aplikacjami medykament wraz z urządzeniem musi znajdować się w lodówce

•	30 dni pracy urządzenia (3 zakroplenia dziennie) bez potrzeby ładowania

•	Automatyczne uruchamianie zapisu w trakcie próby aplikacji leku (niewymagane dodatkowe działania pacjenta)

•	Łatwa i intuicyjna obsługa

•	Zapewnienie medykowi łatwego dostępu do danych

## Zakres pracy
Dobrano odpowiednie podzespoły, a następnie zaprogramowano urządzenie, którego głównym elementem jest **STM32 L432KC**. Zaprojektowano obudowę w programie **Fusion 360** i wykonano ją za pomocą techniki **FDM**. Wykonano obliczenia dotyczące poboru mocy oraz porównano je z wynikami doświadczenia. Przez miesiąc testowano aplikator w warunkach pracy, a następnie przeprowadzono wstępną analizę danych.
![Analiza danych - czas między zakropleniami](/images/zdj_zakraplacz_analiza_1.png)
![Analiza danych - dzienna liczba zakropleń](/images/zdj_zakraplacz_analiza_2.png)

## Podsumowanie
Zakraplacz może być przechowywany przez 30 dni w lodówce bez potrzeby ładowania. Urządzenie zapisuje datę i godzinę podjęcia próby zakroplenia oczu przez pacjenta. Dane przechowywane są na karcie microSD. Medyk ma zapewniony łatwy dostęp do danych oraz może samodzielnie je przeanalizować za pomocą np. podstawowych arkuszy kalkulacyjnych. Urządzenie jest proste w obsłudze, a zapis czasu dokonywany jest automatycznie podczas podawania kropli do oczu przez pacjenta. Dodatkowo za pomocą dźwigni zapewniono polepszenie chwytu i nacisku na krople do oczu.
