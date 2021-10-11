# Release Notes

These release notes only include functional changes. They do
not cover license changes.


## 5.0

### ✨ New features

* `StandardAutocompleteProvider` can now be enrichened with a custom lexicon.  

### 💡 Behavior changes

* License errors no longer cause a crash, but are instead throwing.
* All pro feature initializers are now throwing and no longer cause any hidden license validation errors.

### 🐛 Bug fixes

* The autocomplete provider is now created with the correct locale.

### 💥 Breaking changes

* All previously deprecated functionality has been removed.
* All pro feature initializers are now throwing and must be called using `try`.



## 4.9.3

### 🐛 Bug fixes

* This patch fixes a min text length but in the `ExternalAutocompleteProvider`.



## 4.9.2

This version removes `ExternalAutocompleteProvider`s `AutocompleteProvider` implementation.

Something is causing app extensions to link KeyboardKit and KeyboardKit Pro differently, in a way that makes the protocol implementation not work in app extensions.

Until this is fixed, subclass `ExternalAutocompleteProvider` and just implement `AutocompleteProvider` as well.



## 4.9.1

This version syncs KeyboardKit Pro with new features in the core library.

Make sure to update both dependencies, otherwise KeyboardKit Pro will crash. 



## 4.9

This version adds support for fetching autocomplete suggestions from an external datasource. 

### ✨ New features

* `ExternalAutocompleteProvider` is a new autocomplete provider that can be used to fetch autocomplete suggestions from an external datasource. 

### 🗑 Deprecations

* `StandardAutocompleteSuggestionProvider` has been renamed to `StandardAutocompleteProvider`.



## 4.8

KeyboardKit Pro 4.8 has no functional changes.



## 4.7

This release makes it easier to inspect errors that occur when registering or validating licenses.

### ✨ New features

* `setupPro` and `KeyboardKitLicense.register` are now throwing, which means that you can inspect any errors that occur. 

### 💡 Behavior changes

* License registration and validation are now throwing instead of returning.
* Failing a license registration or validation no longer causes assertion failures, since they are now throwing.
* Failing a license registration or validation no longer displays the error view. This is now handled by `setupPro` instead.

### 💥 Breaking changes

* `setupPro` and `KeyboardKitLicense.register` are now throwing, which means that you must call them with `try` (or `try?` to ignore the result). 



## 4.6

This release makes the binaries work with the main library.



## 4.5

This release adds support for new new locales.

### 🌐 New locales

* 🇫🇷 French
* 🇪🇸 Spanish



## 4.4

This release adds support for new locales.

### 🌐 New locales

* 🇬🇧 English U.K. (GB)
* 🇺🇸 English U.S. (same keyboard as base English but different region)

### 💡 Behavior changes

* All locales now return secondary callout actions for `%`, since `‰` now renders correctly. 



## 4.3.2

This release adds new license registration functions, to make it possibe to register pro licenses when not in a keyboard extension.

### ✨ New features

* `License` has a new, static `current` property.
* `License` has a new, static `register(licenseKey:)` function.



## 4.3

This release makes the binaries work with the main library.



## 4.1

[Milestone](https://github.com/KeyboardKit/KeyboardKit/milestone/30).

### ✨ New features

* `KeyboardLocale` has a new `keyboardInputSetProvider` property.
* `KeyboardLocale` has a new `secondaryCalloutActionProvider` property.
* `KeyboardInputViewController` now auto-registers a `StandardAutocompleteSuggestionProvider` when going pro.
* `StandardAutocompleteSuggestionProvider` is a new autosuggestion provider that can be used to get real suggestions.

### 🌐 New locales

* 🇩🇰 Danish
* 🇳🇱 Dutch
* 🇫🇮 Finnish
* 🇳🇴 Norwegian



## 4.0.1

### 🐛 Bug fixes

* This patch fixes a double quote bug for Swedish, German and Italian providers.



## 4.0

This is the first release of KeyboardKit Pro. 

New versions will sync with the major and minor version of the main library, but the patch number may differ.

### ✨ New features:

* There is a new `KeyboardInputViewController` `.setupPro(with:)` setup function.
* There is a new `StandardKeyboardInputSetProvider.pro(with:)` function.
* There is a new `GermanKeyboardInputSetProvider`
* There is a new `ItalianKeyboardInputSetProvider`
* There is a new `SwedishKeyboardInputSetProvider`
* There is a new `GermanSecondaryCalloutActionProvider`
* There is a new `ItalianSecondaryCalloutActionProvider`
* There is a new `SwedishSecondaryCalloutActionProvider`
