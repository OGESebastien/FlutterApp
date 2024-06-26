# T-DEV-600-STG_14

## SSMOversight - Gestion de projet avec Flutter et API Trello

SSMOversight est une application de gestion de projet mobile qui intègre l'API Trello pour fournir une expérience utilisateur fluide et synchronisée sur plusieurs appareils. Ce projet est développé avec le framework Flutter et le langage Dart.

### Fonctionnalités

- Création et gestion de tableaux, listes et cartes Trello.
- Synchronisation en temps réel avec le compte Trello de l'utilisateur.
- Notifications push pour les mises à jour importantes.
- Interface utilisateur intuitive et réactive.

### Technologies utilisées

#### Construit avec

- [Flutter](https://flutter.dev) - Le framework UI pour développer des applications mobiles multiplateformes.
- [Dart](https://dart.dev) - Langage de programmation optimisé pour les applications multiplateformes.
- [Trello API](https://developer.atlassian.com/cloud/trello) - Pour la synchronisation et la gestion des projets.

### Comment démarrer

Ces instructions vous permettront de copier le projet et de le faire fonctionner sur votre machine locale à des fins de développement et de test.

#### Prérequis

1. Installation de Flutter: [Flutter Documentation](https://docs.flutter.dev/get-started/install/windows/mobile)
3. Editeur de code: Android Studio ou VS Code avec les plugins Flutter
4. [Générer clé API et token](https://developer.atlassian.com/cloud/trello/guides/rest-api/authorization/) de son compte personnel [Trello](https://trello.com/)
5. Windows configs:
    - Adding the **Flutter** and **Dart** in the system path:
        - *System -> Advanced system settings -> Environment Variables -> System variables -> Path -> New*
        - write your own path: e.g. `C:\Users\massoud\Documents\Epitech\projets_perso\flutter_codelab\flutter\bin`
        - Click "OK" in all windows.
    - Set JAVA_HOME:
        - *System -> Advanced system settings -> Environment Variables -> System variables -> New*
        - write the name **JAVA_HOME** and the path: `C:\Program Files\Android\Android Studio\jbr`
        - Click “OK” in all windows.
    - add JAVA_HOME to PATH :
        - *System -> Advanced system settings -> Environment Variables -> System variables -> edit -> Path -> New*
        - write: `%JAVA_HOME%\bin`
        - write another:`C:\Program Files\Android\Android Studio\jbr\bin`
        - Click “OK” in all windows.
        - **restart your terminal**
        - check the setup: `java -version`
    - Install [Android Command-Line Tools](https://developer.android.com/studio#cmdline-tools)
        - Extract it in your own user path: e.g.
        `C:\Users\massoud\AppData\Local\Android\sdk`
        - Commande to install (use your own path) : `C:\Users\massoud\AppData\Local\Android\sdk\cmdline-tools\bin\sdkmanager --sdk_root=C:\Users\massoud\AppData\Local\Android\sdk --install "cmdline-tools;latest"`
    - Accepte the licence: `flutter doctor --android-licenses`

### Installation

1. Clonez le dépôt sur votre machine locale:

```sh
git clone https://github.com/EpitechMscProPromo2026/T-DEV-600-STG_14.git
```
2. Créer un fichier `.env` dans la racine du projet puis copier-coller ceci et mettre les valeurs appropriées:

```sh
API_KEY=your_public_key
SECRET_TOKEN=your_private_token
ACCOUNT_ID=your_trello_account_id
```

3. Créer un émulateur android avec [android studio](https://youtu.be/TSIhiZ5jRB0?si=XwCSKK7J1pCbLGXl&t=20) ou [windows11 terminal](https://www.wrike.com/blog/how-to-create-an-android-emulator-terminal/)

4. Dans votre terminal accédez au répertoir du projet puis:

- installer les dépendances:
```sh
flutter pub get
```
- lancer l'émulateur:
```sh
flutter emulators --launch name_of_your_emulator

```
- démarrer l'application:
```sh
flutter run -v

```

### Tests
Pour exécuter les tests unitaires et d'intégration, utilisez la commande suivante :
```sh
flutter test
```


### Licence

Distribué sous la Licence MIT. Voir [LICENSE](https://fr.wikipedia.org/wiki/Licence_MIT) pour plus d'informations.

### Contact

- setayesh.ghamat@epitech.eu
- massoudud.shams@epitech.eu
- sebastien.oge@epitech.eu

### Reconnaissance

Chapeau aux contributeurs du projet!
- Remerciements spéciaux à tous ceux qui ont donné des retours et des suggestions.
- Inspiré par les nombreux tutoriels et ressources en ligne sur Flutter et l'API Trello.