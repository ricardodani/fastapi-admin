=========
ChangeLog
=========

0.2
===

0.3.1
-----
- Auto register permission.

0.3.0
-----
- Search_fields not required.
- Bug fix.
- Add `_rowVariant` and `_cellVariants`.
- Add update password.
- Fix user create password hash.
- Make `Role`,`Permission` abstract.

0.2.9
-----
- Rename `fastapi_admin.models.User` to `fastapi_admin.models.AbstractUser`.
- Move `is_superuser` and `is_active` to base `AbstractUser`.
- Fix `createsuperuser` error.

0.2.8
-----
- Add password auto hash.
- `Field` description as help text for form.
- Make `uvloop` dependency optional.

0.2.7
-----
- Add custom login_view.

0.2.6
-----
- Fix createsuperuser error.
- Update cli.

0.2.5
-----
- Now there has builtin menus.
- Fix field type.
