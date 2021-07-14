# DroidApps for Linux

Run android application in GNU/Linux without installing emulator like they were a part of the native OS.<br>
droidapps is inspired by [winapps for linux](https://github.com/Fmstrat/winapps)

# Instalation

required by droidapps

> - scrcpy
> - awk
> - rofi

for archlinux user with paru as package manager

```
$ paru -S droidapps
```

another distributions

```
$ curl -o ~/.local/bin https://github.com/mnabila/droidapps/raw/main/droidapps && chmod +x ~/.local/bin/droidapps
```

# Todo

- [x] multiple device support
- [ ] show app name not package name
- [ ] automatically enable simulate secondary display
- [ ] another todo comingsoon

# limitation

- limited number of apps based on mDisplayId
- no icon (idk how to get icons from android apps LOL)

# License

Source is available under the [Mit License](./LICENSE)
