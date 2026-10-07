# LITTLE SHOP (little_shop_of_treasures)

One game of [megatouch-port](https://github.com/Merit-Megatouch/megatouch-port):
original Megatouch ION cabinet games running on Linux / WSL2.

This repo holds the port's configuration and notes — no cabinet code or assets. Use it from
the main repo, where it lives at `games/little_shop_of_treasures`:

```
git clone --recurse-submodules https://github.com/Merit-Megatouch/megatouch-port
cd megatouch-port && make setup && make new GAME=little_shop_of_treasures && make run GAME=little_shop_of_treasures
```

| File | What |
| --- | --- |
| [game.conf](game.conf) | GameId, library, asset folder, window size, language |
| [NOTES.md](NOTES.md) | Status, checklist, dated log |
| [notes/scaffold.md](notes/scaffold.md) | Facts found when scaffolding |
| [notes/unresolved.txt](notes/unresolved.txt) | Cabinet loader functions still needed |
