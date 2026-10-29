# ZenDo 🧘

A **dark-themed productivity app** built with **Flutter** that helps you organize
your day — track tasks, build habits, run focus sessions, and watch your
progress grow in one clean, modern interface.

![Flutter](https://img.shields.io/badge/Flutter-3.x-02569B?logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-3.x-0175C2?logo=dart&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green)
![Platform](https://img.shields.io/badge/Platform-Android%20%7C%20iOS%20%7C%20Web%20%7C%20Desktop-lightgrey)

---

## ✨ Features

- 🔐 **Authentication UI** — Login & Signup with form validation, password
  strength meter, "remember me", and social-login buttons (UI only).
- 🏠 **Home Dashboard** — Greeting, date, daily progress ring, quick stats.
- ✅ **Task Management** — Add tasks via a bottom sheet, toggle completion,
  swipe-to-delete with **undo** support.
- 🔥 **Habit Tracker** — Horizontal habit cards with streaks and tap-to-complete.
- 🎯 **Focus Card** — Start a 25-minute focus session (UI placeholder).
- 📊 **Weekly Chart** — Bar chart of completed tasks per day of the week.
- 🎨 **Custom Dark Theme** — Centralized color palette (`AppColors`) with a
  deep-navy aesthetic and Material 3 styling.
- 📱 **Responsive Layout** — Works on mobile, web, and desktop.

---

## 📸 Screenshots

> Add your own screenshots here after running the app.
> Recommended: `docs/screenshots/login.png`, `home.png`, `signup.png`.

| Login | Home | Signup |
|-------|------|--------|
| _placeholder_ | _placeholder_ | _placeholder_ |

---

## 🚀 Getting Started

### Prerequisites
- [Flutter SDK](https://docs.flutter.dev/get-started/install) (3.x or newer)
- Dart 3.x
- Android Studio / VS Code with the Flutter plugin

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/<your-username>/zendo.git
cd zendo

# 2. Install dependencies
flutter pub get

# 3. Run the app
flutter run
```

### Run on a specific device

```bash
flutter devices              # list available devices
flutter run -d chrome        # run on web
flutter run -d <device-id>   # run on a specific device
```

---

## 🗂️ Project Structure

```
lib/
├── main.dart                     # App entry point + global theme
├── app_colors.dart               # Centralized color palette
├── models.dart                   # TaskItem, HabitItem, priority helpers
├── validators.dart               # Form validation helpers
├── login_page.dart               # Login screen
├── signup_page.dart              # Signup screen
├── home_page.dart                # Main dashboard
└── widgets/
    ├── add_task_sheet.dart       # Bottom sheet to create tasks
    ├── auth_text_field.dart      # Reusable auth input field
    ├── bottom_nav_bar.dart       # Custom bottom navigation
    ├── coming_soon.dart          # Placeholder for unbuilt screens
    ├── focus_card.dart           # Focus session card
    ├── habit_card.dart           # Habit tracker card
    ├── home_header.dart          # Greeting + user info header
    ├── password_strength_bar.dart
    ├── progress_card.dart        # Daily progress ring
    ├── section_title.dart        # Section header row
    ├── social_button.dart        # Google / Apple buttons
    ├── stat_card.dart            # Quick stats tiles
    ├── task_card.dart            # Individual task item
    └── weekly_chart.dart         # Weekly bar chart
```

---

## 🛠️ Built With

| Tool / Package | Purpose |
|---|---|
| [Flutter](https://flutter.dev) | UI framework |
| [Dart](https://dart.dev) | Programming language |
| Material 3 | Design system |
| `withValues(alpha:)` | Modern color opacity API (Flutter 3.27+) |

> No third-party packages are used — this project relies solely on the Flutter SDK.

---

## 🎨 Theme

All colors are defined in `lib/app_colors.dart`:

| Name | Hex | Usage |
|---|---|---|
| `navy` | `#0A1929` | Scaffold background |
| `navyLight` | `#112240` | Surfaces / nav bar |
| `navyCard` | `#132F4C` | Cards |
| `accent` | `#3B82F6` | Primary buttons / highlights |
| `accentLight` | `#60A5FA` | Secondary accent |
| `textPrimary` | `#E6F1FF` | Primary text |
| `textSecondary` | `#8892B0` | Muted text |
| `error` | `#FF6B6B` | Errors / delete |
| `border` | `#233554` | Card borders |

---

## 🗺️ Roadmap

- [ ] Real authentication (Firebase / Supabase)
- [ ] Persistent storage (SQLite / Hive / SharedPreferences)
- [ ] Priority selector in the add-task sheet
- [ ] Working focus timer (countdown + notifications)
- [ ] Tasks / Calendar / Focus / Dashboard tabs
- [ ] Dark & light theme toggle
- [ ] Unit & widget tests

---

## 🤝 Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

## 👤 Author

**Your Name**
- GitHub: [Taymid](https://github.com/Taymid)
- LinkedIn: [linkedin.com/in/Taymid](https://linkedin.com/in/taymid-ahmed-sarker)

---

## ⭐ Support

If you like this project, please give it a ⭐ on GitHub — it really helps!
