<div align="center">

<img src="https://github.com/Juguitoo.png" width="110" alt="Hugo Juan Gómez">

# Hugo Juan Gómez

**Computer engineer.** I build local-first apps I actually use.  
Android, Flutter, and Java — with architecture you can read in the repo.

![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)&nbsp;
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)&nbsp;
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)&nbsp;
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)&nbsp;
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

[JuguitoReader](https://github.com/Juguitoo/JuguitoReader) · [Aegis](https://github.com/Juguitoo/Aegis) · [SolidarityHub](https://github.com/Juguitoo/SolidarityHubTareas)

</div>

---



# About

Most Android reading apps are EPUB viewers. Most productivity apps assume a cloud account. I wanted tools that still work when the book is paper, the network is gone, or I simply do not want an account.

I studied Computer Engineering. The public work here is **local-first** when it can be: files and data stay on the device, there is no account, and offline use is a product decision, not a workaround. When the problem needs a server — volunteers, inventories, disaster logistics — I write Java and Spring the same way: explicit models, tests, and a UI operators can actually run.

I am currently taking **[JuguitoReader](https://github.com/Juguitoo/JuguitoReader)** through closed testing toward the Play Store.

---



# Projects

## JuguitoReader

<div align="center">
<img src="https://raw.githubusercontent.com/Juguitoo/JuguitoReader/dev/docs/icons/JuguitoReaderBanner.png" alt="JuguitoReader" width="640">
</div>

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



## Aegis

**Tasks, focus, and habits on phone and desktop.**

Final-year project (TFG) in Computer Engineering. Aegis is a Flutter app for Android and desktop: tasks with estimates and tags, a calendar, an immersive Pomodoro timer, weekly habits, a diary, and stats. On Android it can block distracting apps during a focus session. Everything lives in a local Drift / SQLite database, with JSON backup.

```
UI (Flutter + Riverpod) → ViewModel → Repository → Drift / SQLite
```

<div align="center">

| Desktop | Mobile |
| :---: | :---: |
| <img src="https://raw.githubusercontent.com/Juguitoo/Aegis/main/docs/images/VistaTareasEscritorio.png" alt="Aegis desktop tasks" width="520"> | <img src="https://raw.githubusercontent.com/Juguitoo/Aegis/main/docs/images/VistaTareasMovil.png" alt="Aegis mobile tasks" width="220"> |

</div>

[Repository](https://github.com/Juguitoo/Aegis) · Flutter · Dart · Riverpod · Drift

---



## SolidarityHub

A university **team** project: a platform for coordinating volunteers, resources, donations, and tasks during a catastrophe.

Spring Boot REST API + Vaadin UI + MySQL. Needs become tasks; urgency drives assignment (Builder); resource changes notify the rest of the system (Observer); lists are filtered with the Criteria pattern.

```
Vaadin UI → REST → Spring Boot → JPA / MySQL
```

Largest contributor on the public repo (task and resource flows, backend services).

[Repository](https://github.com/Juguitoo/SolidarityHubTareas) · Java · Spring Boot · Vaadin · JPA

---



# Stack


| Area           | Technologies                                      |
| -------------- | ------------------------------------------------- |
| Languages      | Kotlin · Dart · Java · SQL                        |
| Mobile / UI    | Jetpack Compose · Material 3 · Flutter            |
| Architecture   | Clean Architecture · MVVM · Hilt · Riverpod       |
| Persistence    | Room · DataStore · Drift · JPA · MySQL            |
| Backend        | Spring Boot · Vaadin                              |
| Async          | Coroutines · Flow · Streams                       |
| Tests          | JUnit · MockK · Turbine · Flutter Test            |


I care about **local-first design**, **explicit domain models**, and tests that lock the behavior I would not want to regress — especially around persistence and foreign keys.

---



# Currently

Shipping **JuguitoReader** to closed testers, then Play Store.  
Kotlin / Compose day to day; Flutter and Java when the product needs them.

---



# Contact

[![GitHub](https://img.shields.io/badge/GitHub-Juguitoo-181717?style=flat-square&logo=github)](https://github.com/Juguitoo)

Open an issue on a repo, or follow along there. Source on GitHub is the portfolio.
