# Contributing

### Ways to contribute

Want to help with the app? Here are some ways to contribute:

- [create new languages](https://github.com/Tulis12/ReadBear/issues) in translation (select "New language" template)
- update and review translations [here](https://translate.tulis.dev/engage/readbear/) [![translated percent badge](https://translate.tulis.dev/widget/readbear/svg-badge.svg)](https://translate.tulis.dev/engage/readbear/)
- create feature submissions
- submit issues if found
- create prs with bug fixes

## Running tests

Before commiting or making a PR make sure to run tests:

```sh
./gradlew lint assembleRelease --build-cache
python3 .github/scripts/check_permissions.py
python3 .github/scripts/check_lint.py
```

If something returns code different than 0, you need to check your changes before pushing.
