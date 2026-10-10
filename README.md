# IzoMailer

A clean, fast email app for Linux and Android. Unread mail stands out, new
mail arrives within seconds, and nothing passes through anyone else's
servers: your email goes only between your device and your mail provider.

**Website:** https://izomailer.koli-bg.com ·
**Privacy policy:** https://izomailer.koli-bg.com/privacy/

This repository holds IzoMailer's **downloads** ([Releases](https://github.com/Izopi4a/izomailer/releases))
and its **issue tracker**. The source code is not public.

## Download

### Ubuntu, Debian, Linux Mint, Pop!_OS…: the APT repository (recommended)

Ubuntu 22.04 or newer, Debian 12 or newer, and distributions based on them.
Updates arrive with your normal system updates.

```sh
sudo curl -fsSLo /etc/apt/keyrings/koli-bg.gpg https://apt.koli-bg.com/KEY.gpg
echo "deb [signed-by=/etc/apt/keyrings/koli-bg.gpg] https://apt.koli-bg.com stable main" \
  | sudo tee /etc/apt/sources.list.d/koli-bg.list
sudo apt update && sudo apt install izomailer
```

### Fedora, openSUSE…: the .rpm

Download `izomailer-<version>-1.x86_64.rpm` from the
[latest release](https://github.com/Izopi4a/izomailer/releases/latest), then:

```sh
sudo dnf install ./izomailer-*.x86_64.rpm      # Fedora
sudo zypper install ./izomailer-*.x86_64.rpm   # openSUSE
```

### Any other distribution: the AppImage

Download `IzoMailer-<version>-x86_64.AppImage` from the
[latest release](https://github.com/Izopi4a/izomailer/releases/latest), make
it executable and run it:

```sh
chmod +x IzoMailer-*-x86_64.AppImage
./IzoMailer-*-x86_64.AppImage
```

The AppImage doesn't update itself: download the new one from Releases.

All Linux builds need a 64-bit PC (x86_64) and glibc 2.35 or newer (any
distribution from 2022 on).

### Android

Coming to Google Play.

## Gmail

On Linux, add a Gmail account with **Sign in with Google**. Google shows
**"Google hasn't verified this app"** once: IzoMailer is a small independent
app that hasn't been through Google's (paid, yearly) verification. Choose
**Advanced → Go to IzoMailer** to continue. Google allows unverified apps a
limited number of users; if sign-in is refused, use an
[app password](https://myaccount.google.com/apppasswords) instead (pick Gmail
in the sign-in dialog).

## Feedback

Found a bug or missing something? [Open an issue](https://github.com/Izopi4a/izomailer/issues).
Please don't post email contents or passwords in issues.

© 2026 Hristomir Kotzev
