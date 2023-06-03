# A very opinionated Collection of Linter Rules for Flutter and Dart (based on `flutter_lints` and `lints`)

## Getting started

Add this package as a `devDependency`.

```sh
flutter pub add dev:extended_dart_lints
```

or

```sh
dart pub add dev:extended_dart_lints
```

Alternatively, you can directly add it to the `devDependencies` section in your `pubspec.yaml`:

```yaml
dev_dependencies:
  extended_dart_lints: ^0.0.1
```

> Note: While this package is unpublished, use:

```yaml
dev_dependencies:
  extended_dart_lints:
    git:
      url: git@github.com:bjoernahrens/extended_dart_lints.git
      ref: main
```

## Usage

Add the following line to your `analysis_options.yaml`:

```yaml
include: package:extended_dart_lints/lints.yaml
```

Following that, you can still easily enable or disable rules as you please.

```yaml
linter:
  rules:
    prefer_single_quotes: false
```

## Additional information

Checkout the packages [`flutter_lints`](https://pub.dev/packages/flutter_lints) and [`lints`](https://pub.dev/packages/lints).
