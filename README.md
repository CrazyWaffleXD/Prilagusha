# Prilagusha

Структура репозитория данного приложения: 

app/
├── src/main/
│   ├── java/com/example/prilagusha/
│   │   ├── PrilagushaApp.kt
│   │   ├── MainActivity.kt
│   │   ├── ui/
│   │   │   ├── home/
│   │   │   │   └── HomeFragment.kt
│   │   │   ├── announcements/
│   │   │   │   ├── AnnouncementsFragment.kt
│   │   │   │   ├── AnnouncementAdapter.kt
│   │   │   │   ├── EditAnnouncementFragment.kt
│   │   │   │   └── AnnouncementsViewModel.kt
│   │   │   ├── schedule/
│   │   │   │   ├── ScheduleFragment.kt
│   │   │   │   └── ScheduleAdapter.kt
│   │   │   ├── chat/
│   │   │   │   ├── ChatFragment.kt
│   │   │   │   ├── ChatAdapter.kt
│   │   │   │   └── ChatViewModel.kt
│   │   │   └── news/
│   │   │       ├── NewsFragment.kt
│   │   │       └── NewsAdapter.kt
│   │   ├── data/
│   │   │   ├── model/
│   │   │   │   ├── Announcement.kt
│   │   │   │   ├── ScheduleItem.kt
│   │   │   │   ├── ChatMessage.kt
│   │   │   │   └── NewsItem.kt
│   │   │   └── repository/
│   │   │       ├── AnnouncementRepository.kt
│   │   │       └── AppRepository.kt
│   │   ├── util/
│   │   │   └── SharedPrefsManager.kt
│   │   └── di/
│   │       └── ViewModelFactory.kt
│   ├── res/
│   │   ├── layout/
│   │   │   ├── activity_main.xml
│   │   │   ├── fragment_home.xml
│   │   │   ├── fragment_announcements.xml
│   │   │   ├── fragment_schedule.xml
│   │   │   ├── fragment_chat.xml
│   │   │   ├── fragment_news.xml
│   │   │   └── fragment_edit_announcement.xml
│   │   ├── menu/
│   │   │   └── bottom_nav_menu.xml
│   │   ├── drawable/
│   │   │   ├── ic_launcher_background.xml
│   │   │   ├── ic_launcher_foreground.xml
│   │   │   ├── ic_news.xml
│   │   │   ├── ic_announcements.xml
│   │   │   ├── ic_schedule.xml
│   │   │   ├── ic_chat.xml
│   │   │   ├── ic_edit.xml
│   │   │   ├── ic_delete.xml
│   │   │   ├── ic_filter.xml
│   │   │   ├── ic_priority_high.xml
│   │   │   └── ic_phone.xml
│   │   ├── values/
│   │   │   ├── colors.xml
│   │   │   ├── strings.xml
│   │   │   ├── themes.xml
│   │   │   └── arrays.xml
│   │   ├── values-night/
│   │   │   └── colors.xml
│   │   └── xml/
│   │       └── backup_rules.xml
│   └── AndroidManifest.xml
└── build.gradle (module)

скоро :)
