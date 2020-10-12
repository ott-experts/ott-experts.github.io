---
title: "Wstępne przygotowania"
slug: "wstepne przygotowania"
date: 2020-10-11T22:11:08+02:00
authors: ["Jakub Gert"]
tags: [ffmpeg,bento4,shaka-packager]
---

W sieci dostępnych jest kilka fantastycznych narzędzi które pomogą Ci przygotować kontent audio oraz video.
Większość z przykładów będzie korzystać z trzech narzędzi
- [ffmpeg](https://ffmpeg.org/)
- [bento4](https://www.bento4.com/)
- [shaka-packager](https://google.github.io/shaka-packager/html/)

Każde z narzędzi ma bardzo dobrą dokumentację wraz z instrukcją, jak dane narzędzie zainstalować.
Ja na co dzień pracuję na MacOS. Aby uniknąć zbędnych komplikacji, użyłem [homebrew](https://brew.sh/) do instalacji dwóch narzędzi.
Pierwszym i najważniejszym będzie ffmpeg. Odpalamy terminal, a następnie polecenie:
```bash
brew instal ffmpeg
```
Podobnie bento4:
```bash
brew instal bento4
```

Shaka-packager dostępny jest na GitHub w sekcji [releases](https://github.com/google/shaka-packager/releases). Dostępne są programy dla MacOS, linux oraz MS Windows.

Przyda nam się także materiał audio i video do pracy. Użyjemy krótkometrażowej produkcji [Sintel](https://durian.blender.org/download/). Otwieramy stronę projektu a następnie:
- z sekcji 'Full Movie' ściągamy HD 1080p (~1GB, MKV, 5.1)
- z sekcji 'Uncompressed Files, Images and Audio' ściągamy [Soundtrack without voices, for dubbing](https://download.blender.org/durian/movies/sintel-m%2be-st.flac)
- z sekcji '*Subtitles (.srt)' wybieramy i ściągamy kilka wersj językowych napisów. Ja wybrałem polski, angielski, hiszpański, arabski oraz chiński.

Warto także mieć na pokładzie kilka dodatkowych narzędzi (nie są niezbędne, ale pomocne).
Ja podaję metodę instalacji (przeważnie) najszybszą z użyciem homebrew. 
Możesz użyć jakiejkolwiek innej metody czy to ze źródeł, czy auto-instalatora.
- git 
```bash
brew install git
``` 
- python3
```bash
brew install python3
```
- golang
  + [instalacja i konfiguracja golang za pomoca homebrew](https://medium.com/@jimkang/install-go-on-mac-with-homebrew-5fa421fc55f5)
```bash
brew install golang
```
- nodejs 
```bash
brew install node
```

Teraz mamy już wszystko aby zacząć zabawę.
