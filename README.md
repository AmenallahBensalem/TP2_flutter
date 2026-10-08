# Waiting Room App – Flutter Workshop 3

Une application Flutter de salle d'attente refactorisée dans le cadre du **Workshop 3** (Provider & Scalable State Management with TDD).

## 📄 Documentation

| Document | Description |
|----------|-------------|
| [`Compte_rendu_Workshop2.pdf`](docs/Compte_rendu_Workshop2.pdf) | Compte rendu du Workshop 2 (setState) |
| [`Compte_rendu_Workshop3.pdf`](docs/Compte_rendu_Workshop3.pdf) | Compte rendu du Workshop 3 – **Trace d'exécution** (Provider & TDD) |
| [`Workshop3_AI_Summary.md`](docs/Workshop3_AI_Summary.md) | Résumé de la session AI (Claude Sonnet) |

## 🚀 Démarrage rapide

### Prérequis

- Flutter SDK installé ([flutter.dev](https://flutter.dev))
- Un émulateur Android/iOS ou un appareil physique

### Installation

```bash
# Cloner le repository
git clone https://github.com/AmenallahBensalem/TP3_flutter.git
cd TP3_flutter

# Installer les dépendances
flutter pub get

# Lancer l'application
flutter run
```

## 🛠️ Technologies utilisées

- **Flutter** – Framework UI multiplateforme
- **Dart** – Langage de programmation
- **Provider** – Gestion d'état scalable (`ChangeNotifier`)
- **TDD** – Test-Driven Development (tests unitaires & widget tests)

## 📁 Structure du projet

```
waiting_room_app/
├── docs/                              # Documentation du projet
│   ├── Compte_rendu_Workshop2.pdf
│   ├── Compte_rendu_Workshop3.pdf     ← Trace d'exécution Workshop 3
│   └── Workshop3_AI_Summary.md
├── lib/                               # Code source Dart
│   ├── main.dart                      # UI avec Provider (StatelessWidget)
│   └── queue_provider.dart            # QueueProvider (ChangeNotifier)
├── test/                              # Tests
│   ├── waiting_room_manager_test.dart # Tests unitaires
│   └── waiting_room_widget_test.dart  # Tests widget
├── android/                           # Configuration Android
├── ios/                               # Configuration iOS
├── web/                               # Configuration Web
├── pubspec.yaml                       # Dépendances Flutter
└── README.md                          # Ce fichier
```

## 🧪 Lancer les tests

```bash
# Tests unitaires uniquement
flutter test test/waiting_room_manager_test.dart

# Tous les tests
flutter test
```

## 📚 Ressources Flutter

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)
- [Documentation officielle Flutter](https://docs.flutter.dev/)
- [Package Provider](https://pub.dev/packages/provider)

## 👤 Auteur

**Amenallah Bensalem** – [GitHub](https://github.com/AmenallahBensalem)
