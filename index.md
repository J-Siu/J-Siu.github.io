# J-Siu Project Page

- [Blog](#blog)
- [Golang](#golang)
- [Hugo SK Themes](#hugo-sk-themes)
- [Docker](#docker)
- [Dart/Flutter](#dartflutter)
  - [Pin2Me](#pin2me)
  - [Lazy Library](#lazy-library)
- [Angular](#angular)
- [Others](#others)

### Blog

- [JSiu.Dev](//JSiu.dev/)

### Golang

Project|Version|Blog|GitHub|Description
---|---|---|---|---
go-chktag|v0.0.2||[go-chktag](//github.com/J-Siu/go-chktag)|command line tool checking `version.go`, `CHANGELOG.md` and git tag before tagging.
go-crypto|v1.1.1|[go-crypto](//johnsiu.com/blog/go-crypto)|[go-crypto](//github.com/J-Siu/go-crypto)|module and command line for crypto function: anonymous box seal.
go-dotfile|v1.1.7||[go-dotfile](//github.com/J-Siu/go-dotfile)|simple dotfile command line management tool.
go-dtquery|v1.1.0||[go-dtquery](//github.com/J-Siu/go-dtquery)|module and command line tool to get devtools version and tab information.
go-gitapi|v2.1.1|[go-gitapi](//johnsiu.com/blog/go-gitapi)|[go-gitapi](//github.com/J-Siu/go-gitapi)|API library supporting github/gitea.
go-gitcmd|v1.0.0||[go-gitcmd](//github.com/J-Siu/go-gitcmd)|provide git command using exec.Cmd wrapper [go-helper/v2/cmd](https://github.com/J-Siu/go-helper)
go-helper|v2.5.5|[go-helper](//johnsiu.com/blog/go-helper)|[go-helper](//github.com/J-Siu/go-helper)|helper library for string, file, error queueing, cmd.exec wrapper, etc.
go-hugo-lc|v1.0.5|[go-hugo-lc](//johnsiu.com/blog/go-hugo-lc)|[go-hugo-lc](//github.com/J-Siu/go-hugo-lc)|Hugo site link checker.
go-is|v1.1.8||[go-is](//github.com/J-Siu/go-is)|infinite scroll webpage processing package.
go-mygit|v2.8.1|[go-mygit](//johnsiu.com/blog/go-mygit)|[go-mygit](//github.com/J-Siu/go-mygit)|Git, Github repository command line tool supporting group action and mass directory processing with parallel push.
go-png2ico|v2.0.2|[go-png2ico](//johnsiu.com/blog/go-png2ico)|[go-png2ico](//github.com/J-Siu/go-png2ico)|module and command line for PNG to ICO. ICO use PNG format for storage.
go-readme2blog|v1.0.3|[go-readme2blog](//johnsiu.com/blog/go-readme2blog)|[go-readme2blog](//github.com/J-Siu/go-readme2blog)|Mass processing of README.md to markdown blog post synchronization.
go-restapi|v1.0.1||[go-restapi](//github.com/J-Siu/go-restapi)|simple Golang REST api library.
id3go|v1.4.0|[id3go](//johnsiu.com/blog/id3go)|[id3go](//github.com/J-Siu/id3go)|id3v2 command line tool.
yt-toolbox|v0.7.0||[yt-toolbox](//github.com/J-Siu/yt-toolbox)|command line tool to extract youtube subscriptions, playlist and history.

### Hugo SK Themes

Theme|GitHub|Hugo|Demo|Description
---|---|---|---|---
SK1|[hugo-theme-sk1](//github.com/J-Siu/hugo-theme-sk1)|[SK1](//themes.gohugo.io/hugo-theme-sk1/)|[sk1.jsiu.dev](//sk1.jsiu.dev/)|Fully functional basic Hugo theme with no css, no javascript.
SK2|[hugo-theme-sk2](//github.com/J-Siu/hugo-theme-sk2)|[SK2](//themes.gohugo.io/hugo-theme-sk2/)|[sk2.jsiu.dev](//sk2.jsiu.dev/)|Fully functional basic Hugo theme with minimum css.
SK3|[hugo-theme-sk3](//github.com/J-Siu/hugo-theme-sk3)|[SK3](//themes.gohugo.io/hugo-theme-sk3/)|[sk3.jsiu.dev](//sk3.jsiu.dev/)|Full feature Hugo theme with Google AdSense support.

### Docker

Docker|Blog|GitHub|Description
---|---|---|---
auto_docker|[auto_docker](//johnsiu.com/blog/auto_docker/)|[auto_docker](//github.com/J-Siu/auto_docker)|Mass Dockerfile auto update script.
docker_compose|-|[docker_compose](//github.com/J-Siu/docker_compose)|Compose and env files for 3rd party docker images.
amule|-|[docker_amule](//github.com/J-Siu/docker_amule)|Amule Daemon
dnsmasq|[Linux IPv6 Router How To](//johnsiu.com/blog/linux-router/)|[docker_dnsmasq](//github.com/J-Siu/docker_dnsmasq)|Dnsmasq Daemon
hostapd|[Linux IPv6 Router How To](//johnsiu.com/blog/linux-router/)|[docker_hostapd](//github.com/J-Siu/docker_hostapd)|Wifi Daemon
hugo|[Jenkins Blog Automation](//johnsiu.com/blog/jenkins-blog-automation/)|[docker_hugo](//github.com/J-Siu/docker_hugo)|Hugo generator for CI/CD
mldonkey|-|[docker_mldonkey](//github.com/J-Siu/docker_mldonkey)|MLdonkey
mpd|[docker_mpd](//johnsiu.com/blog/docker-mpd/)|[docker_mpd](//github.com/J-Siu/docker_mpd)|Music Player Daemon
mpd_lite|[docker_mpd_lite](//johnsiu.com/blog/docker-mpd-lite/)|[docker_mpd_lite](//github.com/J-Siu/docker_mpd_lite)|Music Player Daemon
postfix|[Tiny VPS Postfix with Docker](//johnsiu.com/blog/tiny-vps-postfix-docker/)|[docker_postfix](//github.com/J-Siu/docker_postfix)|Postfix Email Daemon
tor|-|[docker_tor](//github.com/J-Siu/docker_tor)|Tor Client
transmission|-|[docker_transmission](//github.com/J-Siu/docker_transmission)|Transmission Client
unbound|-|[docker_unbound](//github.com/J-Siu/docker_unbound)|Unbound DNS

### Dart/Flutter

#### Pin2Me

Repo: [GitHub](https://github.com/J-Siu/pin2me)

Platform|Link
---|---
Demo|[demo.pin2me.dev](https://demo.pin2me.dev/)
Prod|[pin2me.dev](https://pin2me.dev/)
Chrome|[Chrome Web Store](https://chrome.google.com/webstore/detail/pin2me/hclokpdkmfceobbckckjkdohdgeljlld)
Firefox|[Firefox Add-On](https://addons.mozilla.org/en-US/firefox/addon/pin2me/)

#### Lazy Library
A collection of packages intended to save time, especially from things that are very repetitive across projects.

Repo: [Github](https://github.com/j-siu/flutter_lazy)

Pub.dev|Version|Description
---|---|---
[json_preferences](https://pub.dev/packages/json_preferences)|2.0.0|Combine json object with [SharedPreferences]. And an extended version with notifier.
[lazy_cache](https://pub.dev/packages/lazy_cache)|2.0.0|Provides an indexed local storage on top of the shared_preferences package.
[lazy_download](https://pub.dev/packages/lazy_download)|0.0.2|Dart package for downloading web content
[lazy_extensions](https://pub.dev/packages/lazy_extensions)|2.0.0|Provide extensions and functions for various types to save time and efforts.
[lazy_g_drive](https://pub.dev/packages/lazy_g_drive)|2.0.0|A simple Google Drive Api package mainly design for [AppData] scope operation.
[lazy_g_sync](https://pub.dev/packages/lazy_g_sync)|2.1.0|Single file sync using Google Drive `appData` space. A bridge between [lazy.GDrive], [lazy.GSignIn] and local data/content.
[lazy_http_client](https://pub.dev/packages/lazy_http_client)|2.0.0|Simple http client class that will auto apply specified headers on all requests.
[lazy_log](https://pub.dev/packages/lazy_log)|2.0.0|Simple [log] with global [enableLog] to turn on and off and [forced] to override individually.
[lazy_sign_in](https://pub.dev/packages/lazy_sign_in)|2.1.0|Base package for [lazy_sign_in_extension] and [lazy_sign_in_google].
[lazy_sign_in_extension](https://pub.dev/packages/lazy_sign_in_extension)|2.1.0|Chrome/Firefox extension Google sign-in library base on [LazySignIn]
[lazy_sign_in_google](https://pub.dev/packages/lazy_sign_in_google)|2.1.0|'[google_sign_in] wrapper using [lazy_sign_in] interface. Support web and app Google sign in.'
[lazy_ui_utils](https://pub.dev/packages/lazy_ui_utils)|0.0.2|Collection of flutter UI utilities and widgets

### Angular

Lib(NPM)|GitHub|Description
---|---|---
ng2-simple-global|[ng2-simple-global-lib](//github.com/J-Siu/ng2-simple-global-lib)|Global variable service for Angular.
ng2-simple-mq|[ng2-simple-mq](//github.com/J-Siu/ng2-simple-mq-lib)|Message queue for Angular inter-component communication base on RxJS.
ng2-simple-timer|[ng2-simple-timer-lib](//github.com/J-Siu/ng2-simple-timer-lib)|Timer service for Angular base on RxJS.
simple-api-client-ng2|[ng2-simple-api-lib](//github.com/J-Siu/ng2-simple-api-lib)|Api service work with simple-api-express.
simple-api-express|[simple-api-express](//github.com/J-Siu/simple-api-express)|Api handler that work with simple-api-client-ng2.

### Others

Docker|Blog|GitHub|Description
---|---|---|---
itpl|[itpl](//johnsiu.com/blog/itpl/)|[itpl](//github.com/J-Siu/itpl)|iTunes Playlist command line tool.
tiny_ca|[Tiny CA - OpenSSL-CA](//johnsiu.com/blog/tiny-ca/)|[tiny_ca](//github.com/J-Siu/tiny_ca)|Bash script to create root CA for local network.
