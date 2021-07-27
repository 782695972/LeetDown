# LeetDown

[Official LeetDown Twitter account](https://twitter.com/LeetDownApp) for updates & support. 


an OTA Downgrade Tool for A7 devices.

Supported devices are iPhone 5s, iPad Air and iPad Mini 2. iPad Mini 3 will never be supported as apple doesn't sign 10.3.3 OTA for it.

Latest compiled version can be found [here](https://github.com/rA9stuff/LeetDown/releases).

![alt text](https://i.imgur.com/MkTCrWt.png)

# How to Use?

Mount the `LeetDown.dmg` and drag the `LeetDown.app` to your `/Applications` folder.

Follow the instructions shown in the app.

# F.A.Q.

* How to fix ***this app is damaged and can't be opened*** error?

- Drag and drop `LeetDown.app` to your `/Applications` folder then type the command below to terminal:

`xattr -cr /Applications/LeetDown.app`

# HEY! I HAVE PROBLEMS WITH LEETDOWN!

Problems are expected as LeetDown isn't perfect. But before opening an issue, please run leetdown with ``/Applications/LeetDown.app/Contents/MacOS/leetdown`` command to include the terminal log with your issue.

# Huge Thanks To:

* [@axi0mX](https://twitter.com/axi0mX) for the legendary checkm8 exploit.

* [@tihmstar](https://twitter.com/tihmstar) for futurerestore and igetnonce.

* [@dora2ios](https://twitter.com/dora2ios) for "pwnedDFU" which works ~100% on A7 :)

* [@mosk_i](https://twitter.com/mosk_i) for ibxx patch files and letting me know that DispatchQueue
and "pwnedDFU" is a thing :D

* [@pimskeks](https://twitter.com/pimskeks) for libimobiledevice.

* [@ConsoleLogLuke](https://twitter.com/ConsoleLogLuke) for helping with the dependencies and scripts :)

* [@s0uthwes](https://twitter.com/s0uthwes) (RIP) for updated igetnonce.
