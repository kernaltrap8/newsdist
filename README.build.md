# Building NewsDist

NewsDist currently supports these platforms:
 - NetBSD             (Checked working on amd64 10.0)

   Note: You can pass `Config/netbsd-10` to `./config` to build for this platform.
 - SCO OpenServer     (Checked working on 5.0.7)

   Note: You can pass `Config/sco_sv-3` to `./config` to build for this platform.

   Note: You will have to build Berkeley Yacc and recent Flex to get it working.
 - Debian GNU/Linux   (Checked working on x86_64 12)

   Note: You can pass `Config/linux-6` to `./config` to build for this platform.
 - Windows x86/x86_64

   Note: You can pass `Config/win32` or `Config/win64` to `./config` to build for this platform.

And it might build on other *nix platforms, but I haven`t tested on other platforms.

To build, simply run:
```
  ./config
```
If it succeeds, run:
```
  make
```
You should use BSD make or GNU make to build NewsDist. Do not use SCO`s make, it seems to be broken on that.