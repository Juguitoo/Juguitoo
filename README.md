<div align="center">

<img src="https://github.com/Juguitoo.png" width="220" alt="Hugo Juan Gómez">

# Hugo Juan Gómez

**Computer engineer.** I build local-first apps I actually use.  
Android, Flutter, and Java — with architecture you can read in the repo.

![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)&nbsp;
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)&nbsp;
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)&nbsp;
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)&nbsp;
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)&nbsp;
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

[JuguitoReader](https://github.com/Juguitoo/JuguitoReader) · [Aegis](https://github.com/Juguitoo/Aegis)

</div>

---



# About

Most Android reading apps are EPUB viewers. Most productivity apps assume a cloud account. I wanted tools that still work when the book is paper, the network is gone, or I simply do not want an account.

I studied Computer Engineering. The public work here is **local-first** when it can be: files and data stay on the device, there is no account, and offline use is a product decision, not a workaround.

I am currently taking **[JuguitoReader](https://github.com/Juguitoo/JuguitoReader)** through closed testing toward the Play Store.

---

# Projects

<div align="center">
  
## JuguitoReader

<br>

<img src="https://raw.githubusercontent.com/Juguitoo/JuguitoReader/dev/docs/icons/JuguitoReaderBanner.png" alt="JuguitoReader" width="640">

</div>

<br>

**Digital books and physical ones. One local app.**

Import EPUBs, read them on the device, and log books you read on paper — dates, rating, notes, status, and session stats — with no account and no backend.

Built with **Kotlin, Jetpack Compose, Hilt and Room**. Clean Architecture + MVVM.

```
UI (Compose + ViewModel) → UseCase → Repository → Room / DataStore
```

- Digital library — import, folders and genres
- Built-in reader — chapter progress, themes, zoom, session time and WPM
- Reading manager — the same status/dates/notes flow for files *and* paper books
- Local-first — Room + DataStore; ES / EN in-app

<div align="center">

<img src="https://raw.githubusercontent.com/Juguitoo/JuguitoReader/dev/docs/screenshots/home.png" alt="JuguitoReader home" width="180" hspace="8">&nbsp;
<img src="https://raw.githubusercontent.com/Juguitoo/JuguitoReader/dev/docs/screenshots/library.png" alt="JuguitoReader library" width="180" hspace="8">&nbsp;
<img src="https://raw.githubusercontent.com/Juguitoo/JuguitoReader/dev/docs/screenshots/reader.png" alt="JuguitoReader reader" width="180" hspace="8">&nbsp;
<img src="https://raw.githubusercontent.com/Juguitoo/JuguitoReader/dev/docs/screenshots/registry.png" alt="JuguitoReader registry" width="180" hspace="8">

Home · Library · Reader · Registry

</div>

[Repository](https://github.com/Juguitoo/JuguitoReader) · Pre-release, closed testing

---

<div align="center">

## Aegis

<br>

</div>

**Tasks, focus, and habits on phone and desktop.**

Final-year project (TFG) in Computer Engineering, graded **9.5 / 10**. Aegis is a Flutter app for Android and desktop: tasks with estimates and tags, a calendar, an immersive Pomodoro timer, weekly habits, a diary, and stats. On Android it can block distracting apps during a focus session. Everything lives in a local Drift / SQLite database, with JSON backup.

```
UI (Flutter + Riverpod) → ViewModel → Repository → Drift / SQLite
```

<div align="center">

<p align="center">
  <a href="https://www.youtube.com/watch?v=SNBkrVXFYzE">
    <img src="https://img.youtube.com/vi/SNBkrVXFYzE/hqdefault.jpg" alt="Demo de la app" />
  </a>
</p>

[Repository](https://github.com/Juguitoo/Aegis) · Flutter · Dart · Riverpod · Drift

</div>

---


## Earlier coursework

[SolidarityHub](https://github.com/Juguitoo/SolidarityHubTareas) was a third-year Computer Engineering **team** project (Java, Spring Boot, Vaadin): a prototype for coordinating volunteers, resources and tasks. It is not maintained and is not a running product.

---



# Stack


| Area           | Technologies                                      |
| -------------- | ------------------------------------------------- |
| Languages      | Kotlin · Dart · Java · SQL                        |
| Mobile / UI    | Jetpack Compose · Material 3 · Flutter            |
| Architecture   | Clean Architecture · MVVM · Hilt · Riverpod       |
| Persistence    | Room · DataStore · Drift                          |
| Backend        | Spring Boot · some Vaadin                         |
| Also           | some Unity                                        |
| Async          | Coroutines · Flow                                 |
| Tests          | JUnit · MockK · Turbine · Flutter Test            |


Java, Spring Boot and a bit of Vaadin come from university work — including SolidarityHub — not from a product I ship today. Unity is the same kind of line: I have used it on team projects, but those repos are not mine and they are not part of this profile.

I care about **local-first design**, **explicit domain models**, and tests that lock the behavior I would not want to regress — especially around persistence and foreign keys.

---



# Currently

Shipping **JuguitoReader** to closed testers, then Play Store.  
Kotlin / Compose day to day; Flutter when the product needs it.

---



# Contact

[![GitHub](https://img.shields.io/badge/GitHub-Juguitoo-181717?style=flat-square&logo=github)](https://github.com/Juguitoo)

Open an issue on a repo, or follow along there. Source on GitHub is the portfolio.
