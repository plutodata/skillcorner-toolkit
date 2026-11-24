# Installable SkillCorner toolkit

This fork adds Python packaging metadata to the public SkillCorner toolkit.
Upstream: https://github.com/SkillCorner/skillcorner-toolkit
Upstream revision: `3389bf6cc9d472c347db17be6c104fcc90287b4a`.

All upstream Python source files are unchanged. The wheel includes the complete
`event_synchronization` package and declares its runtime dependencies. Notebook
and command-line examples are not packaged. Upstream licensing is unchanged;
see the upstream README.

Consumers should install this repository at an immutable Git commit. When
updating upstream, verify the source diff and run the consuming application's
synchronization tests.
