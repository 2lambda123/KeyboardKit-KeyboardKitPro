# KeyboardKit Pro

<p align="center">
    <img src ="Resources/Logo.png" width=600 />
</p>

<p align="center">
    <img src="https://img.shields.io/github/v/release/KeyboardKit/KeyboardKit?color=%2300550&sort=semver" alt="Version" />
    <img src="https://img.shields.io/cocoapods/p/KeyboardKit.svg?style=flat" alt="Platform" />
    <img src="https://img.shields.io/badge/Swift-5.3-orange.svg" alt="Swift 5.3" />
    <img src="https://img.shields.io/github/license/KeyboardKit/KeyboardKit" alt="MIT License" />
    <a href="https://twitter.com/danielsaidi">
        <img src="https://img.shields.io/badge/contact-@danielsaidi-blue.svg?style=flat" alt="Twitter: @danielsaidi" />
    </a>
</p>


## About KeyboardKit Pro

[KeyboardKit][KeyboardKit] is a Swift library that helps you create custom keyboard extensions for `iOS` and `ipadOS`.  KeyboardKit Pro is a license-based extensions that unlocks pro features, such as additional locales. 

Going pro is also a way to support this project.


## Getting a license

KeyboardKit Pro licenses are currently handled via [e-mail][Email]. Pricing depends on project, team size and the number of bundles you register for. 

[Contact us][Email] for more information.


## Getting started

KeyboardKit Pro can be setup with a single line of code after it has been installed into the library:

* Install and setup KeyboardKit as described [in the main repo][KeyboardKit].
* Obtain a KeyboardKit Pro license key (for now via [e-mail][Email]).
* Install and `import KeyboardKitPro` alongside KeyboardKit as described [Installation].
* Instead of `setup(with:)`, call `setupPro(withLicenseKey:view:)` to setup Pro features. 
* You can also call `setupPro(withLicenseKey:)` to setup KeyboardKit Pro without a view.

`IMPORTANT` Failure to call `setupPro` before accessing pro features, or setting it up with an invalid license, will cause the extension to show a warning and crash.


## Features

### 🏳️‍🌈 More Locales

KeyboardKit pro adds support for more locales:

* 🇺🇸 English (US)
* 🇩🇪 German
* 🇮🇹 Italian
* 🇸🇪 Swedish 

If you use a `SystemKeyboard` these locales will be supported right away.

New locales are added by demand. One new locale is offered free of charge for each new pro license.

### 🔤 More Input Sets

KeyboardKit Pro adds input set providers for the above locales.

### 🗯 Improved Callouts

KeyboardKit Pro adds secondary callout action providers for the above locales.


## Contact me

Feel free to reach out if you have questions or if you want to contribute in any way:

* E-mail: [daniel.saidi@gmail.com][Email]
* Twitter: [@danielsaidi][Twitter]
* Web site: [danielsaidi.com][Website]


## License

KeyboardKit Pro is closed source. See the `LICENSE` file for more info.

[KeyboardKit]: https://github.com/KeyboardKit/KeyboardKit

[Installation]: https://github.com/KeyboardKit/KeyboardKit/blob/master/readmes/Installation.md
[Troubleshooting]: https://github.com/KeyboardKit/KeyboardKit/blob/master/readmes/Troubleshooting.md

[Email]: mailto:daniel.saidi@gmail.com
[Twitter]: http://www.twitter.com/danielsaidi
[Website]: http://www.danielsaidi.com
