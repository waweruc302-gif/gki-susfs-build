# ⚠️ Superseded

This repo was an early, unsuccessful attempt — the build failed at the final
link step due to undefined symbols in the SUSFS/KernelSU-Next patch.

The working, tested build is here instead:

👉 **[gki-susfs-build2](https://github.com/waweruc302-gif/gki-susfs-build2)**

That repo has the complete patches (kernel, prctl dispatch, setuid flag fix),
a working GitHub Actions pipeline, and is verified working on a Tecno Spark
10C (KI5K, Unisoc T606).
