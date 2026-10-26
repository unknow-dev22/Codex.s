# Mise en route

1. `flutter create sujets_app` puis remplace `pubspec.yaml` et le dossier `lib/` par ceux de ce zip
   (ou copie ce dossier tel quel et lance `flutter create .` dedans pour générer android/ et ios/).
2. Dans `lib/services/subject_service.dart`, remplace VOTRE_UTILISATEUR / VOTRE_DEPOT / main.
3. Mets `exemple_github/subjects.json` à la RACINE de ton dépôt GitHub (dépôt public).
4. Android : ajoute dans android/app/src/main/AndroidManifest.xml, avant <application> :
   <uses-permission android:name="android.permission.INTERNET"/>
5. `flutter pub get` puis `flutter run`.
