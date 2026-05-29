# Folder Structure: Vera Website

## Revision History
| [Version](ca://s?q=Explain_Col_1) | [Date](ca://s?q=Explain_Col_2) | [Description](ca://s?q=Explain_Col_3) | [Authors](ca://s?q=Explain_Col_4) |
|--------------------------------|--------------------------------|--------------------------------|--------------------------------|
|V 1.0 | May 28th 2026 | First draft of Vera's Folder Structure for the Front-End. Subject to change.| Ximena Alvarez|
| Row 2                          | Value                          | Value                          | Value                          |

---

## Introduction

This document will showcase the folder structure for the Front-End and Back-End of Vera Website.

## Folder Structure for Front-End
### Feature-based Structure
The decision of using this approach for folder structure relies on promoting modularity and scalability.
```
src/
├── features/
│   ├── auth/
│   │   ├── components/      # LoginForm.jsx, SignupForm.jsx
│   │   ├── pages/           # LoginPage.jsx, SignupPage.jsx
│   │   ├── services/        # authApi.js
│   │   ├── hooks/           # useAuth.js
│   │   ├── assets/
│   │   ├── tests/
│   │   └── types/
│   │
│   ├── home/
│   │   ├── components/      # Hero.jsx, StatsBox.jsx
│   │   ├── pages/           # HomePage.jsx
│   │   ├── hooks/
│   │   ├── assets/
│   │   └── index.js
│   │
│   ├── upload/
│   │   ├── components/      # UploadCard.jsx
│   │   ├── pages/           # UploadPage.jsx
│   │   ├── hooks/           # useUpload.js
│   │   ├── assets/
│   │   └── services/        # uploadApi.js (future)
│   │
│   ├── plants/
│   │   ├── components/      # PlantCard.jsx, CareGuide.jsx
│   │   ├── pages/           # PlantProfilePage.jsx
│   │   ├── hooks/           # usePlant.js
│   │   ├── assets/
│   │   ├── services/        # plantApi.js
│   │   └── types/           # plant.d.ts
│   │
│   ├── gallery/
│   │   ├── components/      # GalleryGrid.jsx
│   │   ├── pages/           # GalleryPage.jsx
│   │   └── hooks/
│   │   ├── assets/
│   │
│   ├── user/                # future user dashboard
│   │   ├── components/      # UserSidebar.jsx
│   │   ├── pages/           # UserDashboard.jsx, MyPlants.jsx
│   │   ├── hooks/           # useUser.js
│   │   ├── assets/
│   │   ├── services/        # userApi.js
│   │   └── types/           # user.d.ts
│   │
│   ├── admin/               # future admin dashboard
│   │   ├── components/      # AdminSidebar.jsx
│   │   ├── pages/           # AdminDashboard.jsx, ManageUsers.jsx
│   │   ├── hooks/
│   │   ├── assets/
│   │   ├── services/        # adminApi.js
│   │   └── types/
│
├── common/
│   ├── components/          # Button.jsx, Input.jsx, Modal.jsx
│   ├── hooks/               # useFetch.js, useDebounce.js
│   └── utils/               # formatDate.js, validators.js
│
├── layouts/
│   ├── MainLayout.jsx
│   ├── UserLayout.jsx
│   └── AdminLayout.jsx
│
├── router/
│   └── index.jsx
│
├── context/
│   ├── AuthContext.jsx
│   └── ThemeContext.jsx
│
├── assets/
│   ├── images/
│   ├── icons/
│   └── fonts/
│
├── styles/
│   ├── global.css
│   └── variables.css
│
├── App.jsx
└── main.jsx
```
