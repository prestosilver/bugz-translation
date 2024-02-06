# Help Translate Bugz

## The file format

The overall progress of translation is stored in progress.txt.
Actual translations are stored in locale files.
If you would like to help translate, the official english translation is found in base.nim.
Lines are in the following format

``` nim
status "id", "translated"
```

If there is an r before the translated string, please remove it.
Once you complete a line change its status to done.

## Submitting translations

Translations can be submitted in a pull request. If you have any questions ask them in the issues.
