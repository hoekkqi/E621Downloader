## E621 Downloader
![Electron Builder](https://github.com/FurryBotCo/E621Downloader/workflows/Electron%20Builder/badge.svg)

A program to help with bulk downloading images from e621.

Head over to our [release page](https://github.com/FurryBotCo/E621Downloader/releases) to download it. You can report bugs, or ask for features in our [Discord server](https://discord.gg/gMK89SWjHm). You can also visit our website [here](https://e621downloader.furrybot.co)

### Supported Platforms:  
- [x] Windows (exe)
- [x] Debian (deb)
- [ ] Ubuntu (snap) (planned)
- [x] RedHat (rpm)
- [x] MacOS (dmg)

### TODO
- [x] switch to [e621downloader.js](https://npm.im/e621downloader.js)
- [ ] Reset "active" button
- [x] Specific message when zero posts are returned
- [ ] branch out to more services, like [FurAffinity](https://furaffinity.net) and [InkBunny](https://inkbunny.net)
- [x] Save the md5 of images to check for duplicates across different tag sets
- [ ] Incorporate a duplicate image checker that can be ran with a button
- [ ] Refresh previously downloaded tags button
- [x] Save cache frequently incase of network issues (every 10 posts or so)

### Known Bugs
- [x] [Fix Windows not working](https://github.com/FurryBotCo/E621Downloader/issues/3)
- [x] Fix download progress bar going in reverse (??) when you run a second run after one finished (it seems like it has some issues resetting the progress bar)
- [ ] Fix on-application progress bar (it apparently broke?)
- [x] [Fix cache parsing issue](https://github.com/FurryBotCo/E621Downloader/issues/4)
^ this is a pretty big issue but I have NO CLUE how it's happening or how to fix it
