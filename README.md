# Xcode8HungUpTestWithCoreData

This repo is intended to reproduce hung-ups when executing `xcodebuild -showBuildSettings`

## Steps to reproduce hung-ups

1. Clone this repo (or create by yourself) :octocat:
2. Run `xcodebuild -showBuildSettings` :computer:
3. Hung up sometimes :cry:

If you'd like to reproduce much more easily, run
```bash
$ for i in {1..10}; do xcodebuild -showBuildSettings; done
```

## Steps to create this project

1. Create new project
2. Check *Use Core Data* option
3. That's it!
