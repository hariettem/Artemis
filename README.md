# Artemis Quiver - Issue Tracker for Artemis App

## Table of Contents
+ [About](#about)
+ [New to Beta Testing?](#new_beta)
+ [Getting Started](#getting_started)
+ [Known Issues](#known_issues)

## About <a name = "about"></a>
**Artemis** is a [/kbin](https://kbin.social/) focused [Threadiverse](https://fedidb.org/current-events/threadiverse) app in development for iOS and Android, currently in a state of limited **BETA** access. Support for Lemmy will be added at a later date.

Following the changes to [Reddit's API pricing](https://techcrunch.com/2023/06/09/reddit-ceo-doubles-down-on-attack-on-apollo-developer-in-drama-filled-ama/), the fediverse has had an influx of ex-Reddit users who previously made use of *Apollo*, a dedicated Reddit app for iOS. 

**Artemis** aims to provide these users with a comparable experience for the fediverse, tailored and enhanced for interaction with instances of /kbin and Lemmy.

## New to Beta Testing? <a name = "new_beta"></a>

We are happy to have you here. In order to make the app as good as can be, we need  a diverse group of beta testers, with different skills, experiences, and backgrounds. 

The first step is to use the app as you would normally use an app of this kind. Browse your magazines, upvote, downvote, boost, type an eloquent reply (or spam emojis, if you're *that* kind of person). 

This app is supposed to be your daily driver for interacting with kbin, so it better be able to handle regular use. What you might find an instinctual interaction as a user, might not have crossed our minds as developers. 

On the other hand - don't be scared to break things. Let out your inner rockstar. Smash that like button. Pull down to refresh a few times and swipe before the page can change. Rotate your phone while an image is loading. All that matters to us is - it's a bug, and we can only fix it if we're aware of its existence.

## Getting Started <a name = "getting_started"></a>
In order for you to effectively contribute to these cycles of Beta testing, we have prepared this environment to gather feedback. Your feedback is essential in improving the user experience. Explore the app, share your thoughts, and report any issues you find. Together, let's make this app the best it can be. Thank you for joining us on this journey!

**Official Communication Channels**

- Discord Server [[LINK]](https://discord.gg/mqcQuERsTW)
- Matrix Group [[LINK]](https://matrix.to/#/#artemis-app:matrix.org)
- kbin official magazine (ArtemisApp) [[LINK]](https://kbin.social/m/ArtemisApp)
- GitHub [[LINK]](https://github.com/hariettem/Artemis)

**Reporting of Bugs, Enhancement, and Accesibility Requests**

- GitHub: Bugs [[LINK](https://github.com/hariettem/Artemis/issues?q=label%3ABug+)
- GitHub: Enhancements [[LINK]](https://github.com/hariettem/Artemis/issues?q=label%3AEnhancement+)
- GitHub: Accesibility [[LINK]](https://github.com/hariettem/Artemis/issues?q=label%3AAccessibility+)

**App Testing**

- kbin beta magazine (ArtemisQuiver) [[LINK]](https://kbin.social/m/ArtemisQuiver)
- kbin testing magazine (ArtemisAppPlayground) [[LINK]](https://kbin.social/m/ArtemisAppPlayground)
- kbin testing instance [[LINK]](https://artemis.camp)

**Misc**

- We are aware of some [existing issues](#known_issues). These issues should not be reported here. 
- Similarly, do a quick search before reporting: there is a chance the bug/request might already be submitted, and you can confirm for us it's not a single occurence.
- When in doubt: It's a bug. We would rather encounter a duplicate post in the tracker, than run into that bug a month or six later down the line.

## Known Issues <a name = "known_issues"></a>

See reported in the [issue tracker](https://github.com/hariettem/Artemis/issues). Below are a number of issues we are aware of, and do not need bug reports for:

1. Voting/boosting child comments errors out (kbin.social instance). [[ISSUE]](https://github.com/hariettem/Artemis/issues/101)
2. Voting/boosting a post in the comment page doesn’t update when going back. [[ISSUE]](https://github.com/hariettem/Artemis/issues/37)
3. Image previewer interactions are not smooth. [[ISSUE]](https://github.com/hariettem/Artemis/issues/75)
4. Opening imgur thumbnail throws an error. [[ISSUE]](https://github.com/hariettem/Artemis/issues/60)
5. Following a community does not update the subscription list. [[ISSUE]](https://github.com/hariettem/Artemis/issues/63)

Bear in mind graphical and interaction tweaks will occur. To list a few:

- Swipe and default kbin interactions are being worked on.
- Many icons and labels are placeholders, their functionality is not.
- Positioning of menus, items, and layout of settings will change. Finding the right spots is a process.
- Color themes will be adjusted if we find them unfavorable, or inaccessible. Accessibility remains important, and if you experience issues with a graphical design or color choice in multiple places **do make note of this** in the issue tracker.

Unless choices in the UI design truly make the testing version of Artemis unusable, please disregard these as issues. There is a high probability we are aware of this, but have prioritized functionality over design.
