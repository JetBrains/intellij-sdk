---
title: Notable Changes in IntelliJ Platform and Plugins API 2019.*
---

<style>
  table {
    width:100%;
  }
  th, tr, td {
    width:50%;
  }
</style>

## Notable Changes in IntelliJ Platform 2019.1

| Change | Description |
|--------|-------------|
| `@org.jetbrains.annotations.ApiStatus.AvailableSince` | External annotations for IntelliJ Platform are generated and attached to plugin projects automatically (replacing `@since` Javadoc) |
| `PsiReferenceProvider`: assert underlying element | Assert references are created for the given underlying `PsiElement` [Issue](https://youtrack.jetbrains.com/issue/IDEA-203954) |
