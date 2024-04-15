# TemplateOncePerParent
ProcessWire module - Allow pages of a template only once per parent

Adds an option "Once per parent" to each template's family settings. If checked, users are only allowed to create one page of this type under each parent page. This restriction is additive to other restrictions set in a template's family settings.

### Compatibility

Compatible with ProcessWire 3.0

### Status
Beta

### Changes

0.2.0:

- Use $parent->children->count() instead of $parent->count() to determine if template was already used in a parent.
- Add namespace declaration (removing support for ProcessWire < 3.0).

### License
Released under Mozilla Public License v2
