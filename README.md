# FureverFriends
This is a side project, there is a file located in "networking" called "DO NOT DELETE" Deleting it will cause the app to disable itself.

# Furever Friends (Flutter)

A minimal, aesthetic dog-walking request app.
- Payment: **Cash on Delivery** only
- Remote kill-switch: looks for the file `DO NOT DELETE` in this repo’s `main` branch.
  - If missing/404 → the app disables.

## Run (web)
```bash
flutter pub get
flutter run -d chrome

