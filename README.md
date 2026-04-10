# GuardianBox 🔐

![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white)

> 🇬🇧 [English](#english) · 🇵🇪 [Español](#español)

---

## English

IoT smart locker management system with remote control, real-time synchronization and native Android app.

### Index

- [Overview](#overview)
- [Repositories](#repositories)
- [Architecture](#architecture)
- [Features](#features)

### Overview

GuardianBox is a full IoT system that allows remote management of physical lockers through a web admin panel and a native Android app, with real-time sync across all components via Firebase.

### Repositories

| Component | Stack | Link |
|---|---|---|
| Web Panel + Backend | Django, React, DRF, Firebase | [GuardBoxing](https://github.com/RedDeadth/GuardBoxing) |
| Android App | Kotlin, MVVM, LiveData, Firebase | [WasabiDefinitive](https://github.com/RedDeadth/WasabiDefinitive) |

### Architecture

- **Web backend** — Django REST Framework API with Firebase Authentication and Realtime Database integration
- **Web frontend** — React SPA for locker administration and real-time monitoring
- **Android app** — Kotlin with MVVM pattern and LiveData for reactive UI
- **Real-time sync** — Firebase Realtime Database keeps web panel and Android app in sync instantly
- **Firmware** — Arduino C++ for physical locker open/close control

### Features

- Remote locker open/close via web or Android
- Real-time status monitoring across all components
- Firebase Authentication for secure access
- Native Android app with reactive UI (LiveData)
- Admin panel built with React for full locker management

---

## Español

Sistema IoT de gestión de casilleros inteligentes con control remoto, sincronización en tiempo real y aplicación Android nativa.

### Índice

- [Descripción](#descripción)
- [Repositorios](#repositorios)
- [Arquitectura](#arquitectura)
- [Funcionalidades](#funcionalidades)

### Descripción

GuardianBox es un sistema IoT completo que permite gestionar casilleros físicos de forma remota a través de un panel web administrativo y una app Android nativa, con sincronización en tiempo real entre todos los componentes mediante Firebase.

### Repositorios

| Componente | Stack | Link |
|---|---|---|
| Panel Web + Backend | Django, React, DRF, Firebase | [GuardBoxing](https://github.com/RedDeadth/GuardBoxing) |
| App Android | Kotlin, MVVM, LiveData, Firebase | [WasabiDefinitive](https://github.com/RedDeadth/WasabiDefinitive) |

### Arquitectura

- **Backend web** — API con Django REST Framework, integración con Firebase Authentication y Realtime Database
- **Frontend web** — SPA en React para administración y monitoreo en tiempo real de casilleros
- **App Android** — Kotlin con patrón MVVM y LiveData para UI reactiva
- **Sincronización en tiempo real** — Firebase Realtime Database mantiene panel web y app Android sincronizados al instante
- **Firmware** — Arduino en C++ para control físico de apertura y cierre de casilleros

### Funcionalidades

- Apertura/cierre remoto de casilleros desde web o Android
- Monitoreo de estado en tiempo real entre todos los componentes
- Firebase Authentication para acceso seguro
- App Android nativa con UI reactiva (LiveData)
- Panel de administración en React para gestión completa de casilleros
