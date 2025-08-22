# 👋 Welcome to two-castle!

안녕하세요! 효율적인 근무 환경을 위한 솔루션을 개발하는 **two-castle** 팀입니다.

저희는 **Shift Planner** 프로젝트를 중심으로, 안정적이고 확장 가능한 백엔드 시스템과 사용자 친화적인 모바일 애플리케이션을 만들고 있습니다. 공통 라이브러리 `two-castle-lib`를 통해 코드의 재사용성을 높이고, 기술 표준을 유지하며 개발 생산성을 극대화하고 있습니다.

---

## 🚀 Our Main Project: Shift Planner

**Shift Planner**는 복잡한 근무 스케줄을 손쉽게 관리할 수 있도록 돕는 서비스입니다.

### 📦 `shift-planner-api`
> 근무 스케줄 관리를 위한 핵심 비즈니스 로직과 API를 제공하는 서버입니다.

- **역할**: 사용자 인증, 스케줄 생성 및 관리, 데이터 처리 등 서버의 모든 기능을 담당합니다.
- **주요 기술**: Spring Boot를 기반으로 안정적인 API를 구축하며, Spring Security와 JWT를 통해 안전한 인증/인가 시스템을 구현했습니다.
- **데이터 관리**: JPA를 사용하여 데이터를 관리하고, Redis를 통해 토큰 및 캐시 데이터를 효율적으로 처리합니다.

### 📱 `shift-planner-mobile`
> 언제 어디서든 스케줄을 확인하고 관리할 수 있는 모바일 애플리케이션입니다.

- **역할**: 백엔드 API와 통신하여 사용자에게 스케줄 조회, 신청, 변경 등의 기능을 직관적인 UI/UX로 제공합니다.
- **주요 기술**: Flutter를 사용하여 iOS와 Android에서 모두 동작하는 크로스플랫폼 앱을 개발하고 있습니다.

---

### 📦 Shared Library: `two-castle-lib`
> `Shift Planner` 프로젝트의 개발 효율성과 코드 일관성을 위한 공통 라이브러리입니다.

- **역할**: 백엔드와 앱에서 공통으로 사용되는 인증 로직, 데이터 모델, 상수, 응답 포맷 등을 중앙에서 관리합니다.
- **배포**: Java 라이브러리는 **GitHub Packages**를 통해 버전이 관리되고 각 서버 프로젝트에 배포됩니다.

---

### 💻 Our Tech Stack

| Category      | Technologies                                                                                                                               |
| :------------ | :----------------------------------------------------------------------------------------------------------------------------------------- |
| **Backend** | `Java`, `Spring Boot`, `Spring Security`, `JPA`                                                                                            |
| **App** | `Flutter`, `Dart`                                                                                                                          |
| **Database** | `MySql`, `Redis` (for Caching & Token Management) |
| **Auth** | `JWT`             |
| **API Doc** | `Swagger` |
| **Build** | `Gradle`          |
| **Package** | `GitHub Packages`                                                                                                                          |

---

### 👨‍💻 Our Team

아래 형식에 맞춰 `two-castle`을 만들어나가는 팀원들을 소개해 주세요!

| Name       | Role                    | GitHub                                     |
| :--------- | :---------------------- | :----------------------------------------- |
| `김학성`  | `Backend Developer`     | `[https://github.com/haksung59]: https://github.com/haksung59`      |
| `탁지성`  | `Flutter Developer`     | `[https://github.com/jiseongTak]: https://github.com/jiseongTak`      |
