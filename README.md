# Unity Ads iOS Release Repository

Welcome to the Unity Ads iOS release repository.

## Supported Integration Configurations

Always use the pre-built release framework when integrating Unity Ads into your project. Integration using the source-code is not supported.

## Building
### Download Ruby
Ruby can be installed using rbenv or homebrew.
To install Ruby by rbenv:
-`brew install rbenv`
-`rbenv install 2.3.1`
Setup Ruby by rbenv:
-`eval "$(rbenv init -)"`
-`rbenv shell 2.3.1`
OR
To install Ruby by brew using terminal:
-`brew install ruby`
### Install dependencies:
-`bundle install`
### Generate .xcodeproj
From the terminal, go to the project directory and use:
-`./generate-project.rb -c dev`

## Binaries

Binaries can be found from the [releases tab](https://github.com/Unity-Technologies/unity-ads-ios/releases).

## Integration Guide

Integration guide can be found [here](https://github.com/Unity-Technologies/unity-ads-ios/wiki/sdk_ios_integration_guide). There are integration tutorial videos for [Objective-C](https://www.youtube.com/watch?v=T6VIC5E_Wt0) and [Swift](https://www.youtube.com/watch?v=Dhxivc9wWZ8).

## API Reference

API Reference can be found [here](https://github.com/Unity-Technologies/unity-ads-ios/wiki/sdk_ios_api_reference)

## Transition guide from Unity Ads 1.5

Transition guide from Unity Ads 1.5 can be found [here](https://github.com/Unity-Technologies/unity-ads-ios/wiki/sdk_ios_transition_guide)
