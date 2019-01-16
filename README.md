# SigmaPlus

SigmaPlus to program pozwalający stworzyć prezentację lub tutorial w prosty sposób.

## Instrukcja

Zapoznaj się z poniższymi tematami by dowiedzieć się więcej.

### Wymagania

Zalecane wymagania do uruchomienia programu

```
System operacyjny: Windows lub Linux (64bit)
Pamięć RAM: 1GB
Wolne miejsce na dysku: 1GB

```

### Instalacja

Program wystarczy [pobrać](https://github.com/Serq0/Sigma-Plus/releases "pobierz SigmaPlus"), wypakować i uruchomić.

System operacyjny Windows:

```
Uruchom S+.exe
```

System operacyjny Linux:

```
TODO
```


## Pierwsze kroki

Krótki opis jak obsługiwać program w podstawowy sposób

### Pierwsze okno

Zaraz po uruchomieniu programu pojawi się okno powitalne.

Do wyboru są 4 opcje:

```
Nowy Projekt
Załaduj Projekt
O nas
Zakończ
```

Wybieramy
```
Nowy Projekt
```
Program poprosi nas o wskazanie pliku o rozszerzeniu .PDF.
Gdy plik już wybierzemy załadowany on zostanie do programu. Wtedy możemy przystąpić do stworzenia pierwszego slajdu. Najprościej będzie gdy klikniesz opcję
```
Nagrywaj
```
Rozpocznie ona nagrywanie dźwięku, ruchu kursora oraz ewentualnych zaznaczeń co będzie widoczne na dolnym pasku (osi czasu) w kolorze jasnoniebieskim oraz różowym dla zaznaczeń.
Jeżeli Nagrywanie jest włączone przesuń kursor na ekran podglądu slajdu (po prawej stronie), kliknij lewy przycisk myszy, przytrzymaj go i przeciągnij w inny punkt na slajdzie oraz powiedz "Hello World".
Następnie kliknij przycisk
```
Zatrzymaj
```
Jeżeli już to zrobiłeś kliknij przycisk
```
Zresetuj odtwarzanie
```
Przeniesie on suwak odtwarzania na początek.
Teraz kliknij
```
Odtwórz
```
Jeżeli już obejrzałeś swoje kilka sekund twórczości możesz wyrenderować filmik.
Kliknij przycisk
```
Renderuj film
```
i wybierz lokalizację w którym ma on zostać zapisany.
Po skończonym renderowaniu odtwórz filmik za pomocą odtwarzacza obsługującego format .mp4.

### Kolejne kroki

Jeżeli zainteresował Cię program zachęcamy do przeczytania klawiszologii która jest poniżej i przetestowania każdego skrótu.


## Klawiszologia

LPM - lewy przycisk myszki
PPM - prawy przycisk myszki
MS - scrollowanie kółkiem od myszki

### Oś czasu

Przesuwanie suwaka w wybrane miejsce na osi czasu:
```
CTRL + LPM
```

Zaznaczenie całego 'kafelka' z nagraniem:
```
ALT + LPM
```

Zaznaczenie konkretnego fragmentu:
```
SHIFT + LPM (przeciągnij)
```

Odznaczenie:
```
SHIFT + PPM
```

Usunięcie zaznaczonego fragmentu:
```
DELETE
```

Usunięcie zaznaczonego fragmentu z przesunięciem (nie pozostawiając wolnej przestrzeni:
```
CTRL + DELETE
```

Przesunięcie suwaka na początek:
```
HOME
```

Przesunięcie markera na koniec:
```
END
```

Przesunięcie widoku środka osi czasu do wskazywanej pozycji:
```
CTRL + PPM
```

Przybliżenie na osi czasu:
```
MS w górę LUB '+'
```

Oddalenie na osi czasu:
```
MS w dół LUB '-'
```

### Opcje projektu

Zmiana slajdu na następny/poprzedni:
```
→ / ← LUB D / A
```

Zatrzymaj odtwarzanie lub nagrywanie:
```
SPACE
```

Nagrywaj:
```
R
```

Nagraj kursor:
```
CTRL + R
```

Nagrywaj dźwięk:
```
ALT + R
```

Cofnij akcję:
```
CTRL + Z
```

Ponów akcję:
```
CTRL + Y
```

Zapisz projekt:
```
CTRL + S
```

Załaduj projekt:
```
CTRL + L
```

Odtwórz od pozycji wskaźnika:
```
P
```

Odtwórz od początku:
```
CTRL + P
```

Stwórz nowy projekt:
```
CTRL + N
```

### Edycja zaznaczeń

Jeżeli nie chcesz usuwać scieżki dźwiekowej która została nagrana wraz z zaznaczeniem na slajdzie a chcesz pozbyć się tego zaznaczenia to najprostszym sposobem będzie:
```
1. Kliknij LPM na zaznaczenie w podglądzie (zmieni kolor na żółty)
2. Wciśnij klawisz DELETE
```
Zaznaczenie zostanie usunięte.

Jeżeli chcesz usunąć jedynie fragment zaznaczenia:
```
1. Kliknij LPM na zaznaczenie w podglądzie (zmieni kolor na żółty)
2. Trzymając wciśnięty klawisz CTRL kliknij LPM w dwa przeciwległe punkty (zostanie utworzony czerwony prostokąt)
2a. Jeżeli chcesz odznaczyć prostokąt wciśnij CTRL + PPM
2b. Jeżeli chcesz poprawić drugi wierzchołek po prostu jeszcze raz wciśnij CTRL + LPM
2c. Jeżeli chcesz poprawić pierwszy wierzchołek musisz wykonać punkt 2a. a następnie powtórzyć punkt 2.
3. Teraz wciskając klawisz DELETE usuniesz fragmenty zaznaczenia które jest zaznaczone (jest żółte) oraz znalazło się w czerwonym prostokącie.
```


## Stworzono z pomocą

* [Python](https://pl.python.org/) - Główna technologia
* [Tkinter](https://docs.python.org/3/library/tk.html) - Interfejs użytkownika
* [pyGame](https://www.pygame.org/news) - Ekran podglądu
* [pydub](https://pypi.org/project/pydub/) - Manipulacja dźwiękiem
* [openCV](https://docs.opencv.org/3.0-beta/doc/py_tutorials/py_tutorials.html) - Renderowanie filmu
* [mutool](https://mupdf.com/index.html) - Ładowanie plików .PDF
* [FFmpeg](https://www.ffmpeg.org/) - Łączenie dźwięku z filmem

## Coś nie działa prawidłowo?

[Zgłoś błąd tutaj](https://github.com/Serq0/Sigma-Plus/issues)

## Autorzy

* **Tomasz Burewicz** - *Projektowanie i tworzenie interfejsu aplikacji, wersja Linuxowa, wersja serwerowa* - [GitHub](https://github.com/pazdan1994)
* **Bartosz Gąsior** - *Oś czasu, nagrywanie i odtwarzanie kursora, dźwięku, zaznaczeń, mechanizm projektów, odczyt .pdf* - [GitHub](https://github.com/saekiamae)
* **Sergiusz Jańczura** - *Renderowanie dźwięków, filmów, testowanie aplikacji, wersja serwerowa, organizacja projektem* - [GitHub](https://github.com/Serq0)

