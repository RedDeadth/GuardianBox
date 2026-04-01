# GuardianBox 🔐

![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white)

Sistema IoT de gestión de casilleros inteligentes con control remoto, 
sincronización en tiempo real y aplicación Android nativa.
## Repositorios

| Componente | Stack | Link |
|---|---|---|
| Panel Web + Backend | Django, React | [WasabiDefinitive](https://github.com/RedDeadth/GuardBoxing) |
| App Android | Kotlin, MVVM, Firebase | [GuardBoxing](https://github.com/RedDeadth/WasabiDefinitive) |

## Arquitectura

- Panel web con Django (MVC) y React para administración y monitoreo
- App Android con patrón MVVM y LiveData para UI reactiva
- Firebase Realtime Database para sincronización instantánea entre todos los componentes
- Firmware Arduino en C++ para control físico de apertura y cierre de casilleros
