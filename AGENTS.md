# Agent rules

This repository is Godot 4.8-beta5 (commit `a661dfdbccc664ccca57ad76c2bb5dcd8f3fc768`), the newest 4.8 beta, with our bug fixes backported. It holds no features.

- One bug fix per pull request, on the `4.8` branch. A fix carries a test that fails without it and passes with it, or, for a build fix, names the compiler, platform or option whose build it repairs.
- No feature enhancements: a new class, method, setting, module, or a change of behaviour that is not a fix waits for a Godot release that has it; a newer 4.8 beta or the 4.8 release is a new base, rebased with these fixes.
- A fix is a backport: name the commit or branch it comes from, and check first that this base does not already fix it.
- `V-Sekai-fire/build-containers` builds a pinned commit of this branch at double precision, and changes only its containers, never this tree.
