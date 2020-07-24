# Switch \ and \` keys on macOS

This is a fork of https://github.com/dchakarov/restore-tilde (more info in there) that remaps the key to right of the left shift (ISO UK keyboard) to the key to the left of 1 (and vice-versa), effectively switching the keys. 

This is due to the fact that the 2020 Macbook Pro with touchbar that I'm using has these keys switched on my external keyboard for some reason. (Original macbook layout: ISO PT-PT; external keyboard layout: ISO UK)

Note: This also switches these keys when using the actual keyboard on the machine on the original ISO PT-PT layout (and they were working correctly). I don't really mind, so I haven't yet searched for a better solution.

# How to run

## Run once (restart undoes this)

Run `switchBackslashAndGraveAccent.sh` script

## Automatically on every startup

Add `SwitchBackslashAndGraveAccent.app` to `System Preferences - Users & Group - Login Items`
