# Nix Runtime Dependencies Reporter

This is the runtime report bundler
from [nix-how/nix-demos][]
with the static header removed.

Usage:

    nix bundle --bundler github:gmacon/nix-dependency-report#runtimeReport nixpkgs#hello
    
The output is a symlink `${hello.name}-report` with a simple report.
Check upstream for more explanation about how this works.

[nix-how/nix-demos]: https://github.com/nix-how/nix-demos/tree/2079f25135044df96f31ab265e05dfc9d570b4fc
