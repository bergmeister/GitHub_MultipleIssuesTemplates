---
name: Bug report 🐛
about: Report errors or unexpected behavior 🤔

---

Steps to reproduce
------------------

```PowerShell

```

Expected behavior
-----------------

```none

```

Actual behavior
---------------

```none

```

If an unexpected error was thrown then please report the full error details using e.g. `$error[0] | Select-Object *`

Environment data
----------------

<!-- Provide the output of the following 2 commands -->

```PowerShell
> $PSVersionTable

> (Get-Module -ListAvailable PSScriptAnalyzer).Version | ForEach-Object { $_.ToString() }

```
