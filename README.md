# [libidn-podspec](https://github.com/chrisballinger/libidn-podspec)

[![CI Status](http://img.shields.io/travis/chrisballinger/libidn-podspec.svg?style=flat)](https://travis-ci.org/chrisballinger/libidn-podspec)
[![Version](https://img.shields.io/cocoapods/v/libidn.svg?style=flat)](http://cocoapods.org/pods/libidn)
[![License](https://img.shields.io/cocoapods/l/libidn.svg?style=flat)](http://cocoapods.org/pods/libidn)
[![Platform](https://img.shields.io/cocoapods/p/libidn.svg?style=flat)](http://cocoapods.org/pods/libidn)

From [GNU IDN Library - Libidn](http://www.gnu.org/software/libidn/)

> GNU Libidn is a fully documented implementation of the Stringprep, Punycode and IDNA specifications. Libidn's purpose is to encode and decode internationalized domain names. The native C, C# and Java libraries are available under the GNU Lesser General Public License version 2.1 or later.

> The library contains a generic Stringprep implementation. Profiles for Nameprep, iSCSI, SASL, XMPP and Kerberos V5 are included. Punycode and ASCII Compatible Encoding (ACE) via IDNA are supported. A mechanism to define Top-Level Domain (TLD) specific validation tables, and to compare strings against those tables, is included. Default tables for some TLDs are also included.

This podspec uses a [fork of libidn](https://github.com/chrisballinger/libidn/compare/1.32-podspec) to fix a few minor issues related to CocoaPods integration.

## Usage

To run the example project, clone the repo, and run `pod install` from the Example directory first.

## Installation

libidn is available through [CocoaPods](http://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
pod "libidn"
```

## Authors

* [Chris Ballinger](https://github.com/chrisballinger) - Podspec maintainer
* Simon Josefsson <simon@josefsson.org> - Designed and implemented libidn.
* For more see `AUTHORS` in libidn source code.

## License

libidn is available under the LGPL license, but the podspec and example code in this repo is MIT. See `LICENSE` for more details.