# Unused L10n

A simple tool to find unused l10n keys in a Flutter project.

It checks arb files in the `lib/l10n` directory and dart files in the `lib` directory. Then it prints out the keys that are not used in the dart files.

Originally posted [here](https://github.com/localizely/flutter-intl-intellij/issues/13#issuecomment-1204931707).

# Usage

```sh
dart run bin/unused_l10n.dart -p /Users/path/to/the/project
```
