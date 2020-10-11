---
title: "Wstępne przygotowania"
slug: "wstepne przygotowania"
date: 2020-10-11T22:11:08+02:00
authors: ["Jakub Gert"]
tags: [ffmpeg,bento4,shaka-packager]
---

W sieci dostępnych jest kilka narzędzi które pomogą Ci zacząć przygodę z przygotowaniem kontentu audio oraz video.
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

