SingleViewAppStarter
===

iOS/Swift single view application template project

- Package Manager
  - CocoaPods
  - Carthage

## Setup

1. `git clone git@github.com:53ningen/SingleViewAppStarter.git`
1. `brew install rbenv`
1. `brew install carthage`
1. `cd SingleViewAppStarter`
1. `rbenv install`
1. `rbenv exec gem install bundler`
1. `rbenv exec bundle install`
1. `rbenv exec bundle exec pod install`
1. `open SingleViewAppStarter.xcworkspace`

or Run `./start`

## Adding Libs
### CocoaPods

1. `vi Podfile`
1. `rbenv exec bundle exec pod install`

### Carthage

1. `vi Cartfile`
1. `carthage update`

## Using another Xcode

If you wish to use another Xcode such as beta version, download it and put it into Application directory, then run: `sudo xcode-select --switch  path/to/Xcode.app`

