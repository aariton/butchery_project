# Butchery Management System

Cross-platform butchery management system built with Flutter and Firebase. Academic project, Bucharest University of Economic Studies (2024).

Two apps:
- **Customer** — browse catalogue, place delivery/pickup orders, manage addresses and payments.
- **Admin** — manage inventory (with expiry alerts), process orders, track suppliers, view sales reporting.

## Stack

| Technology | Purpose |
|------------|---------|
| Flutter / Dart | Cross-platform mobile apps |
| Firebase Firestore | Real-time NoSQL database |
| Firebase Authentication | User login |
| Google Cloud Console | Storage, notifications |
| Google Maps API | Address selection |

## Data model

- **Users** — profiles, addresses, orders
- **Products** — name, price, stock, expiry
- **Orders** — items, payment status, fulfilment
- **Suppliers** — supplier info, restocking

## Setup

```sh
git clone https://github.com/aariton/butchery_project.git
cd butchery_project
flutter pub get
flutter run
```

Requires Flutter SDK, Dart SDK, and a configured Firebase project (Firestore, Authentication, Storage) with `google-services.json` / `GoogleService-Info.plist`.

**Authors:** Alexandru Ariton, Cristian-Eugen Ciurea
