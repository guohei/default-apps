# Guohei's default-apps (a no so minimal setup guide)

## Todos

- Set up iCloud account.
- Install **[Bitwarden](https://bitwarden.com/download/)**. This is a self-deployed password management service.

- Install **[Warp](https://www.warp.dev/)**. The intelligent terminal.
- Install **[Homebrew](https://brew.sh/)**. THE package manager for macOS. `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
  - `asciinema`
  - `bat` <- `cat`
  - `btop` <- `htop` and `top`
  - **`emacs`**
  - `exiftool`
  - `eza` <- `ls` and `exa`
  - `fx`
  - `fzf`
  - `jq`
  - `neofetch`
  - `neovim` <- `vim`
  - `procs` <- `ps`
  - `scc`
  - `tldr`
  - `tre` (`brew install tre-command`) <- `tree`
  - `tmux`
  - **`uv`**
  - `vizdata`
  - `yt-dlp`
  - `axel`
  - `iperf3`
  - `axel`
  - `iperf3`
  - `mosh`
  - `mtr`
  - `scrcpy`
  - `speedtest`
  - `smartmontools`
  - `tmux`
  - `ffmpeg`  

- [Change computer and host name](https://apple.stackexchange.com/questions/66611/how-to-change-computer-name-so-terminal-displays-it-in-mac-os-x-mountain-lion):
  - `sudo scutil --set ComputerName "newname"`
  - `sudo scutil --set LocalHostName "newname"`
  - `sudo scutil --set HostName "newname"`
- Stop Time Machine local snapshots. `tmutil disablelocal` was deprecated since Mojave. Use  [TimeMachineEditor](https://tclementdev.com/timemachineeditor/) instead.
- Create a global `gitignore` file at `~/.gitignore`. See [this one](/config/.gitignore) as an example: `git config --global core.excludesfile ~/.gitignore`
- Generate and add SSH key to GitHub account.
- Turn off the Spotlight.
- Generate and add SSH key to My servers.
- In Safari, go to Preferences - Advanced, turn on "Show Develop menu in menu bar".

## Application list

### A

- [Acorn](https://flyingmeat.com/acorn/). 🎫
- [AirBattery](https://github.com/lihaoyun6/AirBattery). Get battery usage of all devices on Mac.🆓
- [Affinity Photo 2](https://affinity.serif.com/en-us/photo/). 🎫
- [Amphetamine](https://apps.apple.com/us/app/amphetamine/id937984704?mt=12). Keep the machine awake. `Cmd` + `Shift` + `A`: turn on/off 
- [Anki](https://apps.ankiweb.net/)🆓
- [Applite](https://github.com/milanvarady/Applite), user-friendly GUI macOS application for Homebrew Casks. `brew install --cask applite` 🍺🆓
- [App Cleaner & Uninstaller](https://nektony.com/mac-app-cleaner), Best uninstaller and cleaning assistant. 🎫
- [APTV](https://apps.apple.com/us/app/aptv/id1630403500), Live Stream Player. 🎫 

### B

- [BetterDisplay](https://github.com/waydabber/BetterDisplay#readme). Display customization tool. From the same developer of [Monitor Control](https://github.com/MonitorControl/MonitorControl). 🎫
- [BestTV](https://apps.apple.com/us/app/besttv-live-stream-player/id6443592543), Live Stream Player. 🎫 
- [Bob](https://bobtranslate.com/), 翻译 & OCR 软件.🎫
- [Bitwarden](https://bitwarden.com/download/), Self-deployed password management.🆓
- [Brave](https://bitwarden.com/download/), Desktop Browser.🆓

### C

- [calibre](https://calibre-ebook.com/). E-book management. `brew install --cask calibre` 🍺🆓
  - [calibre-douban](https://github.com/fugary/calibre-douban). 豆瓣插件.
  - [Fix Kindle Ebook Cover](https://github.com/bookfere/Fix-Kindle-Ebook-Cover). A tool to fix damaged cover for Kindle.
- [ChatGPT](https://openai.com/chatgpt/download/), ChatGPT on mobile or desktop.🆓
- [ChatWise](https://chatwise.app/), The second fastest AI chatbot™.🎫
- [Cherry Studio](https://github.com/CherryHQ/cherry-studio), AI chatbot.🆓
- [CleanShot X](https://cleanshot.com/), Screen capturing tool.🎫
- [Cursor](https://www.cursor.com/), The AI Code Editor🎫

### D

- [Dato](https://apps.apple.com/us/app/dato/id1470584107?mt=12). Menubar Calendar, World Clocks. 🎫 
- [DaisyDisk](https://daisydiskapp.com/). Disk usage in a wind rose diagram. 🎫
- [Dia](https://www.diabrowser.com/). AI Browser.🆓
- [Dropover](https://dropoverapp.com/) 🎫 
- [Discord](https://discord.com/). `brew install --cask discord` 🍺🆓
- [Downie](https://software.charliemonroe.net/downie/) 🎫
- **[Drafts](https://getdrafts.com/)**. For drafting. 🔁
  - `Cmd` + `Shift` + `1` = Drafts main window
  - `Cmd` + `Shift` + `2` = Drafts quick entry
- [Dropshare](https://dropshare.app/). File Sharing Tool. 🎫

### E

- [Eagle](https://eagle.cool/). Organize images. 🎫
- [Easydict](https://github.com/tisfeng/Easydict/). 开源的词典翻译 macOS App.🆓

### F

- [Final Cut Pro](https://www.apple.com/final-cut-pro/).🎫
  - [Motion](https://www.apple.com/final-cut-pro/motion/). 🎫
  - [Compressor](https://www.apple.com/final-cut-pro/compressor/). 🎫
- [ForkLift](https://binarynights.com/),Dual pane file manager. 🎫
- [Folo](https://apps.apple.com/us/app/folo-follow-everything/id6739802604), Follow everything in one place. 🆓

### G

- [GarageBand](https://apps.apple.com/us/app/garageband/id682658836).A recording studio on your Mac. 🆓
- [Google Drive](https://support.google.com/drive/answer/10838124), Cloud storage and backup.🆓
- [GitHub Desktop](https://desktop.github.com/). Easy-to-use Git GUI.🆓
- [Google Chrome](https://www.google.com/chrome/). 🆓
- [Google Earth Pro](https://www.google.com/earth/). 🆓

### H

- [Handbrake](https://handbrake.fr). Open source video transcoder. `brew install —cask handbrake` 🍺🆓
- [Hush](https://github.com/oblador/hush). Content blocker for Safari. 

### I

- [Ice](https://github.com/jordanbaird/Ice). Bartender alternative. `brew install --cask jordanbaird-ice` 🍺🆓
- [IINA](https://iina.io/). Media player. `brew install --cask iina` 🍺🆓
- [Immersive Translate](https://immersivetranslate.com/zh-Hans/), 沉浸式翻译.🆓
- [Input Source Pro](https://inputsource.pro/), Switch and track your input sources with ease ✨.🆓
- [Infuse](https://firecore.com/infuse),An elegant video player.🎫
- [IriunWebcam](https://iriun.com/), Webcam.
- [iStat Menus](https://bjango.com/mac/istatmenus/),The ultimate system monitor.🎫

### J

- [JPEGmini Pro](https://jpegmini.com/), Compress image.🎫
- [Jump Desktop](https://jumpdesktop.com/), Remote desktop app.🎫

### K

- [`kcc`](https://github.com/ciromattia/kcc), Kindle Comic Converter.🆓
- [Keka](https://www.keka.io/en/) `brew install --cask keka` 🍺🆓
- [KeyClu](https://sergii.tatarenkov.name/keyclu/support/). Cheatsheet alternative🆓
  - Double press cmd and hold to activate the cheatsheet.
  - Double press cmd and quick release to activate Siri.
  - `brew install —cask keyclu` 🍺

### L

- [Latest](https://github.com/mangerlahn/Latest). Checks applications' latest update on macOS.
 `brew install --cask latest` 🍺🆓
- [LocalSend](https://localsend.org/). Share files to nearby devices.🆓
- [Loop](https://github.com/MrKai77/Loop). Alternative to Moom.🆓
  - Left `Ctrl` to activate a selector ring.
  - `brew install --cask loop` 🍺
- [Logic Pro](https://www.apple.com/logic-pro/).🎫 
- [Loon](https://apps.apple.com/us/app/loon/id1373567447), Network tool. 🎫

### M

- [**mac-cleanup-py**](https://github.com/mac-cleanup/mac-cleanup-py) clean up script for macos. `brew tap mac-cleanup/mac-cleanup-py; brew install mac-cleanup-py` 🍺🆓
- [MarkEdit](https://github.com/MarkEdit-app/MarkEdit).🆓
- [MenubarX](https://apps.apple.com/us/app/menubarx-floating-browser/id1575588022?mt=12),Menu bar Browser.🎫 
- [Min Browser](https://github.com/minbrowser/min). `brew install --cask min` 🍺🆓
- [Mimestream](https://mimestream.com/).Gmail client.🎫
- [Movist Pro](https://movistprime.com/),Media player.🎫
- [MusicFree](https://github.com/maotoumao/MusicFree), 免费音乐播放器.🆓

### N

- [Navicat Premium Lite](https://www.navicat.com/en/products/navicat-premium-lite), a compact version of Navicat.🆓
- [Nova](https://nova.app/),Code editor.🎫

### O

- **[Obsidian](https://obsidian.md/)**. Second brain/digital garden/Zettelkasten. Go subscribe to [Obsidian Sync](https://obsidian.md/sync) to support the development!🆓
- [Obsidian Web Clipper](https://stephango.com/obsidian-web-clipper). 🆓
- [OBS Studio](https://github.com/obsproject/obs-studio/releases/), Live streaming and screen recording. 🆓
- [Ollama](https://github.com/jmorganca/ollama). LocalLLM.🆓
- [OrbStack](https://orbstack.dev/). A light-weight Docker and Linux runtime management. `brew install --cask orbstack` 🍺🆓
- [OpenCat](https://opencat.app). AI 聊天客户端.🎫

### P

- [Parallels Desktop](https://www.parallels.com/products/desktop/), Run Windows.🎫
- [PDF Expert](https://pdfexpert.com/) 🎫
- [Pearcleaner](https://github.com/alienator88/Pearcleaner). A free, source-available and fair-code licensed mac app cleaner. `brew install pearcleaner` 🍺
- [Permute 3](https://software.charliemonroe.net/permute/) 🎫
- [Pixelmator Pro](https://apps.apple.com/us/app/pixelmator-pro/id1289583905?mt=12). Image editing. 🎫
- [Planet](planetable.xyz). web3 publishing and following web content.🆓
- [PopClip](https://www.popclip.app/), Instant text actions. 🎫
- [ProNotes](https://www.pronotes.app/), Supercharged Apple Notes.
- [Plex](https://www.plex.tv/). `brew install --cask plex` 🍺

### Q

- [QLMarkdown](https://github.com/sbarex/QLMarkdown). macOS Quick Look extension for markdown files. `brew install --cask qlmarkdown` 🍺
- [Quantumult X](https://apps.apple.com/us/app/quantumult-x/id1443988620), A Powerful Network Tool.🎫

### R

- [Reeder](https://reeder.app) 🔁.
- [Raycast](https://www.raycast.com/). Extendable launcher substitute to Spotlight, with an extension store. `Cmd` + `Space`: Activate Raycast. (Disable this shortcut for Spotlight) `brew install --cask raycast` 🍺
- [Reminders Menubar](https://github.com/DamascenoRafael/reminders-menubar) `brew install --cask reminders-menubar` 🍺]

### S

- [Sequel](https://www.getsequel.app/). Keep track of the movies, shows, games, books and audiobooks. 
- [ServerCat](https://servercat.app/). Server Status
- [Shadowrocket](https://apps.apple.com/us/app/shadowrocket/id932747118), Rule based proxy utility 🎫
- [sing-box](https://github.com/SagerNet/sing-box), The universal proxy platform.🆓
- [SnippetsLab](https://www.renfei.org/snippets-lab/), Snippet manager.🎫
- [Steam](https://store.steampowered.com/)
  - [`balatro-mod-manager`](https://github.com/skyline69/balatro-mod-manager)
- [Speedtest](https://apps.apple.com/us/app/speedtest-by-ookla/id1153157709?mt=12)
- [Sublime Text](https://www.sublimetext.com/), Text editor.🎫
- [Surge](https://nssurge.com/), Network Toolbox.🎫

### T

- [Tailscale](https://tailscale.com/).🆓
- [Telegram](https://telegram.org/). `brew install --cask telegram` 🍺
- **[Things 3](https://culturedcode.com/things/)**. The best GTD. 
  - `Ctrl` + `Space`: quick entry.
  - `Hyper` + `T`: quick entry with autofill. This requires [Things Helper](https://culturedcode.com/things/help/things-sandboxing-helper-things3/).
- [TimeMachineEditor](https://tclementdev.com/timemachineeditor/). Manually control Time Machine backup schedule. `brew install --cask timemachineeditor` 🍺
- [Transmission](https://transmissionbt.com) `brew install --cask transmission` 🍺
- [Tiny Image](https://github.com/kyleduo/TinyPNG4Mac) Native client of TinyPNG.🆓
- [Tot](https://apps.apple.com/us/app/tot/id1491071483?mt=12), collect & edit text.🆓
- [Transmit](https://panic.com/transmit/), macOS file transfer apps.🎫

### U

- [UltraEdit](https://www.ultraedit.com/products/mac-text-editor/), Text editor.🎫
- [Ulysses](https://ulysses.app/), Writing App.🎫
- [uPic](https://github.com/gee1k/uPic). Image (and small file) upload tool for macOS. `brew install bigwig-club/brew/upic --cask` 🍺

### V

- [Visual Studio Code](https://code.visualstudio.com/docs/setup/mac).🆓
- [VMware Fusion](https://www.vmware.com/products/desktop-hypervisor/workstation-and-fusion),
Run Windows, Linux and other virtual machines.

### W

- [Warp](https://www.warp.dev/), The Intelligent Terminal.🆓
- [微信 WeChat](https://www.wechat.com/). `brew install --cask wechat` 🍺
- [Windsurf](https://windsurf.com/editor), Agentic IDE.🎫

### X

- [XDeck](https://github.com/morishin/XDeck).An 𝕏 client app.🆓
- [Xcode](https://developer.apple.com/xcode/). 
- [xld](https://tmkk.undo.jp/xld/index_e.html). Lossless audio decoder for macOS.

### Y

- [YACReader](https://www.yacreader.com/) `brew install --cask yacreader`. 🍺

### Z

- **[Zed](https://zed.dev/)**. Might be better than VSC. `brew install --cask zed` 🍺
- [Zen Browser](https://zen-browser.app). Might be better than Firefox. Plugins associated with Firefox should be synced.
- [ZeroTier](https://www.zerotier.com/) 🆓

## Font selections

- [Lexend](https://www.lexend.com/), sans-serif
- Roboto family
  - [Roboto](https://fonts.google.com/specimen/Roboto), sans-serif
  - [Roboto Condensed](https://fonts.google.com/specimen/Roboto+Condensed), sans-serif
  - [Roboto Serif](https://fonts.google.com/specimen/Roboto+Serif), serif
  - [Roboto Mono](https://fonts.google.com/specimen/Roboto+Mono), monospace
- [IBM 3270](https://github.com/rbanffy/3270font), monospace
- [JetBrains Mono](https://www.jetbrains.com/lp/mono/), monospace
- [Ubuntu Monospace](https://design.ubuntu.com/font/), monospace
- [Noto Mono for Powerline](https://github.com/powerline/fonts/), monospace
- Amazon Ember and Bookerly from [Amazon Complete Font Set](https://developer.amazon.com/en-US/alexa/branding/echo-guidelines/identity-guidelines/typography), sans serif, serif
- [LXGW WenKai / 霞鹜文楷](https://github.com/lxgw/LxgwWenKai), serif
- [LXGW Neo XiHei / 霞鹜新晰黑](https://github.com/lxgw/LxgwNeoXiHei), sans-serif
- [喜鹊宋体](https://xiquezaozi.taobao.com/), serif
- [Atkinson Hyperlegible](https://brailleinstitute.org/freefont), sans-serif
- [Charis SIL](https://software.sil.org/charis/), serif
- [Server Mono](https://servermono.com/), monospace