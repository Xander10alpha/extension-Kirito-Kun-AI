# Easier discovery in GUI 1.0.17

Proposed patch versions: Kirito-Kun 1.0.1.

- Find these extensions using translated topics in the search box and tag filter.
- Existing saved setups and activation rules keep their package identities and settings.

## Maintainer notes

Stable tag IDs use the GUI’s shared translations in all nine supported languages. Capability facts describe this package’s files, parsed configuration demands and options, not its family’s combined behavior. Existing dependencies, required/suggested settings and load-order conflict controls still apply. Family membership does not make members exclusive or install them automatically.

The published Store identity is `Kirito-Kun`; source main changed it to `Kirito-Kun-AI` without changing version 1.0.0. This patch retains the published identity so existing dependents still select the same package. The display name remains independent.

Validation: definitions parse; unrelated manifest fields and configuration are preserved, apart from the explicit identity/path corrections above. Shared family roots and tag translations are checked against GUI 1.0.17. No game testing or release publication is claimed.
