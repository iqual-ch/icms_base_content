# ICMS Recipe: Base Content

This recipe is only used as dependency by other content recipes.

It ships the `test` user (role `content_editor`), the author of the default content, without a
password: no login is possible until one is set. Set one if the account is used:

```bash
drush user:password test '<password>'
```
