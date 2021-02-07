![CodeGen](https://i.picasion.com/pic90/be11ad50e54277263090f6cc568de530.gif)
![Generator](https://github.com/merlinofcha0s/generator-jhipster-flutter/workflows/Generator/badge.svg?branch=master&event=push)
![npm version](https://img.shields.io/badge/Flutter-passing-green)
![npm](https://img.shields.io/badge/npm-passing-green)

Generate your Flutter mobile App (Android / iOS) for JHipster

This is a [JHipster](https://www.jhipster.tech/) module.

Get started and (Full not yet) documentation

# What's inside

- Screen
  - Main
  - Register
  - Login
  - User preferences
- Theming
  - All styles in one place
  - Light theme for now
- Full I18n support
  - EN, FR for now
  - Automatic generation with [IntelliJ plugin](https://plugins.jetbrains.com/plugin/13666-flutter-intl) or [VS code plugin](https://marketplace.visualstudio.com/items?itemName=localizely.flutter-intl)
  - Detecting device locale
  - Change language in user preferences UI
  - Apply the preferred locale instead of the device one
- BLoC Architecture [More informations](https://pub.dev/packages/flutter_bloc)
- JSON serializer / deserializer Java Jackson like [More informations](https://pub.dev/packages/dart_json_mapper)
- Language choice
  - Java / Kotlin for Android 
  - Objective C / Swift for iOS
- Profiles / Environments
  - Dev
  - Prod
- IntelliJ Config file for dev and prod profile

## Entity generator

Generate your entity from your jhipster project
- One by one
- All your entities


# Prerequisites

As this is a [JHipster](https://www.jhipster.tech/) module, we expect you have JHipster and its related tools already installed:

- [Installing JHipster (6.x.x)](https://www.jhipster.tech/installation/)
- [Installing Flutter SDK (1.22.x)](https://flutter.dev/docs/get-started/install)
- Generating your app with 

```bash
jhipster
```

# Installation

## With NPM

To install this blueprint:

```bash
npm install -g generator-jhipster-flutter-jdlc
```

To update this blueprint:

```bash
npm update -g generator-jhipster-flutter-jdlc
```

## With Yarn

To install this blueprint:

```bash
yarn global add generator-jhipster-flutter-jdlc
```

To update this blueprint:

```bash
yarn global upgrade generator-jhipster-flutter-jdlc
```

# Usage

To use this blueprint, run 

```bash
yo jhipster-flutter-jdlc
```
#Usage create entity from JHipster
To create a single entity

```bash
yo jhipster-flutter-jdlc:entity Employee
```

All entities
```bash
yo jhipster-flutter-jdlc:entities
```

# Help and contribution to the project

Feel free to help, the project is open to PR

# License

Apache-2.0 © Cyril Casaucau

# Creditos
Cyril Casaucau
https://github.com/merlinofcha0s
