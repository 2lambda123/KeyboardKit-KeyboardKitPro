<p align="center">
    <img src ="Resources/Logo.png" width=600 />
</p>

<p align="center">
    <img src="https://img.shields.io/github/v/release/KeyboardKit/KeyboardKit?color=%2300550&sort=semver" alt="Version" />
    <img src="https://img.shields.io/cocoapods/p/KeyboardKit.svg?style=flat" alt="Platform" />
    <img src="https://img.shields.io/badge/Swift-5.5-orange.svg" alt="Swift 5.5" />
    <img src="https://img.shields.io/github/license/KeyboardKit/KeyboardKit" alt="Closed-Source License" />
    <a href="https://twitter.com/getkeyboardkit">
        <img src="https://img.shields.io/badge/contact-@getkeyboardkit-blue.svg?style=flat" alt="Twitter: @getkeyboardkit" />
    </a>
</p>



## About KeyboardKit Pro

[KeyboardKit][KeyboardKit] is a Swift library that helps you build custom keyboards with Swift and SwiftUI. It extends the native keyboard APIs and provides you with a lot more functionality than is otherwise available.

The end result can look something like this...or entirely different:

<p align="center">
    <img src ="https://github.com/KeyboardKit/KeyboardKit/blob/master/Resources/Demo.gif?raw=true" width="300" />
</p> 

KeyboardKit Pro extends KeyboardKit with pro features, such as additional locales, autocomplete engines, more extensions, additional views etc. It lets you create fully localized system keyboards with a single line of code. 
 

KeyboardKit Pro requires a [commercial license][Licenses] to be used. Licenses can be purchased from the [website][Website] or from [Gumroad][Gumroad].



## Supported Platforms

KeyboardKit Pro supports `iOS 13`, `macOS 11`, `tvOS 13` and `watchOS 6`.

Although KeyboardKit Pro builds on all platform, some features are unavailable on some platforms. 



## Installation

KeyboardKit Pro can be installed with the Swift Package Manager:

```
https://github.com/KeyboardKit/KeyboardKitPro.git
```

Since KeyboardKit Pro installs as a binary, it only has to be added to the main app target.



## Getting started

The online documentation has a [getting-started guide][Getting-Started] that will help you get started with the library.



## Documentation

The [online documentation][Documentation] has articles, code examples etc. that let you overview the various parts of the library and understand how they all connect to each other.

The online documentation is currently iOS-specific.

Note that extensions to native types are not included in this documentation. Future versions of this library will refactor the extensions in a way that makes them appear in the documentation.



## ✨ Features

KeyboardKit is localized in 50+ keyboard-specific locales ([Read more in the main repo][KeyboardKit]):

🇺🇸 🇦🇱 🇦🇪 🇧🇾 🇧🇬 🇦🇩 🇭🇷 🇨🇿 🇩🇰 🇳🇱 <br />
🇧🇪 🇬🇧 🇺🇸 🇪🇪 🇫🇴 🇵🇭 🇫🇮 🇫🇷 🇨🇭 🇬🇪 <br />
🇩🇪 🇦🇹 🇬🇷 🇭🇺 🇮🇸 🇮🇪 🇮🇹 🇹🇯 🇱🇻 🇱🇹 <br />
🇲🇰 🇲🇹 🇲🇳 🇳🇴 🇮🇷 🇵🇱 🇵🇹 🇧🇷 🇷🇴 🇷🇺 <br />
🇷🇸 🇸🇰 🇸🇮 🇪🇸 🇰🇪 🇸🇪 🇹🇷 🇺🇦 🇺🇸 🇧🇪 <br />

Besides the core features, KeyboardKit Pro extends KeyboardKit with a bunch of pro features:

* 💡 Autocomplete - KeyboardKit Pro adds an autocomplete engine that supports all locales above, as well as an engine that fetches suggestions from a remote api.
* 🗯 Callouts - KeyboardKit Pro adds locale-specific callout actions for all locales above. 
* 🔤 Input Sets - KeyboardKit Pro adds locale-specific input sets for all locales above.
* ➡️ [Proxy][Proxy] - KeyboardKit Pro adds `UITextDocumentProxy` extensions for getting all text from the proxy.
* 🖼 Views - KeyboardKit Pro adds additonal views that simplify building great keyboards.



## Contact

Feel free to reach out if you have questions or if you want to contribute in any way:

* E-mail: [info@getkeyboardkit.com][Email]
* Twitter: [@getkeyboardkit][Twitter]
* Website: [getkeyboardkit.com][Website]


## Sponsors and Clients

This project is proudly sponsored by the following companies:

<a href="https://www.oribi.se/en">
    <img src="Resources/sponsors/oribi.png" alt="Oribi Icon" title="Oribi" width=120 />
</a>
<a href="https://www.phonetoroam.com">
    <img src="Resources/sponsors/phonetoroam.png" alt="phonetoroam Icon" title="phonetoroam" width=120 />
</a>
<a href="https://vitalisapps.com">
    <img src="Resources/sponsors/vitalis.png" alt="Vitalis Icon" title="Vitalis" width=120 />
</a>
<a href="https://letterkey.eu">
    <img src="Resources/sponsors/letterkey.png" alt="LetterKey Icon" title="LetterKey" width=120 />
</a>
<a href="http://anomaly.net.au">
    <img src="Resources/sponsors/anomaly.png" alt="Anomaly Software Icon" title="Anomaly Software" width=120 />
</a>
<a href="https://www.milocreative.com">
    <img src="Resources/sponsors/milo.png" alt="Milo Creative Icon" title="Milo Creative" width=120 />
</a>

KeyboardKit is free, but please consider sponsoring the project if you find it useful. You can support KeyboardKit through [GitHub Sponsors][Sponsors], by signing up for a Pro license, paying for support, donations etc.



## Demo Applications

The [main repo][KeyboardKit] contains a `Demo` folder with two demo apps that lets you try out KeyboardKit and KeyboardKit Pro:

* `Demo` has a system keyboard that mimics an English keyboard, as well as a unicode-based keyboard.
* `Demo - Pro` shows you how to use KeyboardKit Pro and has one keyboard for LTR locales, and one for RTL locales. 

To run the demo apps, open and run the projects, then enable the keyboards you want to try under System Settings. 

Note that you need to enable full access to try some features, like audio and haptic feedback.



## Contact

Feel free to reach out if you have questions or if you want to contribute in any way:

* E-mail: [info@getkeyboardkit.com][Email]
* Twitter: [@getkeyboardkit][Twitter]
* Web site: [getkeyboardkit.com][Website]



## Support

You can sponsor this project on [GitHub Sponsors][Sponsors] or get in touch for paid support. 

KeyboardKit is proudly sponsored by the following companies:

<a href="https://www.oribi.se/en">
    <img src="Resources/sponsors/oribi.png" alt="Oribi Icon" title="Oribi" width=120 />
</a>
<a href="https://www.phonetoroam.com">
    <img src="Resources/sponsors/phonetoroam.png" alt="phonetoroam Icon" title="phonetoroam" width=120 />
</a>
<a href="https://vitalisapps.com">
    <img src="Resources/sponsors/vitalis.png" alt="Vitalis Icon" title="Vitalis" width=120 />
</a>
<a href="https://letterkey.eu">
    <img src="Resources/sponsors/letterkey.png" alt="LetterKey Icon" title="LetterKey" width=120 />
</a>
<a href="http://anomaly.net.au">
    <img src="Resources/sponsors/anomaly.png" alt="Anomaly Software Icon" title="Anomaly Software" width=120 />
</a>
<a href="https://www.milocreative.com">
    <img src="Resources/sponsors/milo.png" alt="Milo Creative Icon" title="Milo Creative" width=120 />
</a>

KeyboardKit is free, but please consider sponsoring the project or upgrading to KeyboardKit Pro if you find it useful.



## License

KeyboardKit Pro is closed source. See the [LICENSE][License] file for more info.



[Email]: mailto:info@getkeyboardkit.com
[Twitter]: http://www.twitter.com/getkeyboardkit
[Website]: https://getkeyboardkit.com
[Licenses]: https://getkeyboardkit.com/pro
[Sponsors]: https://github.com/sponsors/danielsaidi
[KeyboardKit]: https://github.com/KeyboardKit/KeyboardKit
[Gumroad]: https://danielsaidi.gumroad.com

[Documentation]: https://keyboardkit.github.io/KeyboardKitPro/documentation/keyboardkitpro/
[Getting-Started]: https://keyboardkit.github.io/KeyboardKitPro/documentation/keyboardkitpro/pro-getting-started
[Proxy]: https://keyboardkit.github.io/KeyboardKitPro/documentation/keyboardkitpro/pro-uitextdocumentproxy-extensions

[License]: https://github.com/KeyboardKit/KeyboardKitPro/blob/master/LICENSE
