---
layout: page
status: publish
published: true
title: Development
author:
date: '2010-01-08 21:25:14 +1100'
categories:
---
# Contributing to Vienna

## Debugging

dSYM files containing the debug symbols can be found at [GitHub]({{ site.app_github_url }}/releases) under "Assets".

## Writing code

The current version of Vienna requires Xcode 10 and the macOS 10.14 SDK. Most of Vienna is made with Objective-C, but some newer code is being created in Swift 4. We welcome both Objective-C and Swift contributions.

You should have a basic knowledge of Git and read this [suggested workflow]({{ site.app_github_url }}/wiki/Good-manners-with-Git).

As a starting point, search for any [issues with the *help-wanted* label]({{ site.app_github_url }}/labels/%22help%20wanted%20%3Asos%3A%22).

Please let us know what you are working on by posting an issue on Vienna's github and assigning it to yourself.

## Code style guidelines

Try to respect the code style of the code you modify. 

For new Objective-C code or significant refactoring, it is advised to adopt the [Spotify Objective-C Coding Style](https://github.com/spotify/ios-style).

For Swift code, please try to follow the [GitHub Swift Style Guide](https://github.com/github/swift-style-guide).

## Commit messages

1. Separate subject line from body with a blank line.

2. Use present-tense, imperative-style for the subject line (as if you are giving orders to the codebase to change its behavior). This is shorter and consistent with commit texts automatically generated by Git.

3. Try to limit the subject line to 50 characters : consistent commit histories are easier to read. Avoid at all costs subject lines with more than 72 characters : Github will truncate them with an ellipsis.

4. Capitalize the subject line.

5. Do not end the subject line with a period.

6. Use the body to explain _what_ and _why_ (and not on the _how_). Focus on the reasons which required the change - the way things worked before the change (and what was wrong with that), the way they work now, and why you decided to solve it the way you did.  
You may reference issues/discussions raised at Github, but avoid relying heavily on them: a reviewer should be able to make an analysis based solely on code and commit messages.

7. It is recommended to hard wrap the body text at 72 characters (except for quoted material that is non-prose, like compiler error messages).

