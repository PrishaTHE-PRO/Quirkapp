🚧🚧🚧

**What is the Quirk app and how does it work?**
Quirk is a companion and self-help app for one of the most common formats of CBT. You may have heard it called "the three column technique" or "catch it, check it, change it." Your brain is really good at making you feel exactly what you're thinking.

**How did Quirk start?**
Quirk started as a little thing I made for myself as I started doing CBT. As I got better, I needed Quirk less. But at the same time, lots of other people had discovered Quirk and started picking it up. That meant more bug fixes, more features, and just more work to be done. I really couldn't keep it up well, especially with my main focus at the time (my day job). 

So in order to work on it full time, my brother and I tried to turn it into a company. That way we could continue to develop Quirk as a primary focus, even if we didn't need it anymore. 

**What is CBT (Cognitive Behavioral Therapy0) ?**
Cognitive Behavioral Therapy (CBT) is the "gold standard" of psychotherapy and is widely considered to be one of the most effective, evidence backed treatments for depression, anxiety, and panic. If you go into just about any therapist or psychiatrist, CBT will likely be one of the first treatments they try.

**What are the experiences of people who have been through CBT (Cognitive Behavioral Therapy) ?**
**1**
(Young Adult, Social Anxiety)

When I first came here I didn’t want to talk or do anything until it was time to let it out. They taught me the skills of how I should be around others including Emotional Intelligence which is a good thing. Then there’s Fact, Feel and Goal which is very important to use. Dr. Julian taught me the tools or skills of what I should use whenever I’m feeling upset or mad. He taught FFG and then there’s Emotional Intelligence which is very interesting. So now...

I know what to do whenever it comes to a bad day.

the future.
Young Adult

 
**2**
(Adult, Anxiety & Depression)

Treatment at ACBT is not like other mental health places. I went to other therapists, and they would listen and not say much. Here it's much different. When something was going on, we would just plug the problem into the NECBT treatment for the day. It was amazing! I feel so much better.

Builder, Adult Male - West Hartford

🚧🚧🚧


---

<p align="center">
<h1 align="center">✨🐙 quirk. </h1>
</p>
<p align="center">
  <a href="https://itunes.apple.com/us/app/quirk-cbt/id1447026451?mt=8">Download iOS</a> • <a href="https://play.google.com/store/apps/details?id=tech.econn.quirk">Download Android</a> • <a href="mailto:humans+github@quirk.fyi">Contact</a> • <a href="https://tinyletter.com/quirk">Newsletter</a>
<br><br>
</p>

Quirk is a crossplatform, GPL-licensed, [Cognitive Behavioral Therapy (CBT)](https://en.wikipedia.org/wiki/Cognitive_behavioral_therapy)
app built in React Native / Expo.

Unlike many CBT apps, it's fairly unbiased in what you use it for; it doesn't ask about you
to do depression-specific CBT exercises. That makes it fairly quick and discreet to use, especially in a public
setting.

![screenshot](https://i.imgur.com/64Cpmpm.png)

## How Quirk Supports Itself

In order for Quirk to support itself, **it charges a small subscription fee.** Currently it's $5.99 / month in the US, which is roughly the cost of a cup of coffee. This helps pay for a full-time developer to make Quirk not-dead and generally good. 

### The Survival Law of Product Design

To understand _why_ we do a subscription, we can look to the Survival Law of Product Design, a fancy term I just made up. When you make a product, whatever keeps that product alive becomes the primary force of design. 

For example, facebook.com is not Facebook's product, facebook.com/business/ads is Facebook's product. Because 0 dollars are made from facebook accounts, only from advertisers that pay to get access to those facebook accounts. The way you keep the lights on ultimately shapes the product you make. 

So if you want to make a good product that helps folks, you should pick a model of sustainability where the financial incentives of the organization are aligned with the individual interests of the users.

After a lot of tries with other models, that ended up being a subscription. In a subscription, the primary metric is retention: are people still using this thing? If retention drops, people cancel their subscription and you no longer get to exist.

The _only_ solid way to have good retention is to create something that is actively useful and good. Similarly, the only way to get any value from CBT is to consistently do it. 

## Contributors

Some amazing folks have helped build the Quirk you see today.

- [@devinroche](https://github.com/devinroche) for setting up translation and stepping up as a core maintainer 🔥
- [@devilcius](https://github.com/devilcius) for the amazing Spanish translation 🇪🇸
- [@idnovic](https://github.com/idnovic) for the amazing German translation 🇩🇪 (and the iPad support!)
- [@kwierbol](https://github.com/kwierbol) for the amazing Polish translation 🇵🇱
- [@Walther](https://github.com/Walther) for the amazing Finnish translation 🇫🇮
- [@Jos512](https://github.com/Jos512) for the amazing Dutch translation 🇳🇱
- [@jinto](https://github.com/jinto) for the amazing Korean translation 🇰🇷
- [@briankung](https://github.com/briankung) for the Chinese 🇨🇳 localization, internationalization support and helping guide the entire translation effort. 🎉
- [@akinariobi](https://github.com/akinariobi) for the Russian translation 🇷🇺 
- [@miguelmf](https://github.com/miguelmf) for the Portugese translation 🇵🇹
- [@comradekingu](https://github.com/comradekingu) for the Norweigan Bokmål translation 🇳🇴
- [@micheleriva](https://github.com/micheleriva) for the Italian translation 🇮🇹
- [@Jolg42](https://github.com/jolg42) for the French translation 🇫🇷
- [@Buricescu](https://github.com/Buricescu) for the Romanian translation 🇷🇴

## Running Locally

Quirk is built on React Native and therefore assumes you have [node](https://nodejs.org/en/) installed.
[Yarn](https://yarnpkg.com/en/) is preferred over NPM as a package manager.

```sh
# clone the project and cd into it
git clone git@github.com:Flaque/quirk.git; cd ./quirk

# copy the sample .env (edit as required)
cp .env.sample .env

# install dependencies
yarn

# start development environment
yarn start
```

You'll then be in the [expo development environment](https://docs.expo.io/versions/latest/).
If you already have XCode installed with a simulator, you can just press `i` to start it.

# Can I help?

Of course!

**If you like the app,** go give it 5 stars! It helps more people find the app.

**If you're a mental health professional,** audit [the descriptions](https://github.com/Flaque/quirk/blob/master/src/locals/en.json) of the cognitive distortions. If you have suggestions, let me know and we'll change stuff!

**If you can draw** and can make digital illustrations of the little blobs, let me know and I'll find a place to stick them in the app!

**If you know a language other than English,** help [us translate the app!](/TRANSLATIONS.md)

# Design

Quirk's goal is to be both inviting and focused. It should be _really_ easy to enter in a thought; people frequently enter these in public settings and need to do it fairly quickly. It also should not cause any increased frustration.

## Design Logic

Quirk is built with two main goals in mind:

- Don't be bloated
- Don't be evil

### Don't be bloated

**Don't include features for one particular condition at the expense of other conditions.** For example, don't couple mood tracking to thought tracking. If a user _has_ to enter a mood in order to track a thought, then the entire app is ruined for people who use it for panic, OCD or another condition where mood isn't the primary focus.

**Don't include non-CBT related treatments without good reason.** No relaxation audio tracks or meditation guides. It's a CBT app, keep it focused on CBT.

**Don't include things that could be better accomplished by another app.** No one needs an in-app diary when a diary works just fine. No one needs an in-app heart rate tracker when a heart rate tracker works just fine.

**Be quick and efficient.** Thoughts shouldn't take 5 minutes to enter and you should be able to skip fields if it's reasonable. Don't let the perfect be the enemy of the good.

### Don't be Evil

**Thoughts are more valuable than passwords, treat them that way.** Most people would rather give over their passwords than their CBT thoughts. They're incredibly private, occasionally involve other people, and frequently are embarrassing.

**Don't have \$200 dollar in app purchases.** I'm looking at you CBT Thought Diary. I get it, developers need to make money. It costs a lot to just keep the app on the app store. But you're preying on vulnerable people. Very few people of rational mind will purposely spend \$200s for a dark mode.

**Don't have dumb notifications.** Scheduling is fine, abusing push notifications so your app has better traffic is scummy and gross.

**Be open.** Not every app has to be open source; it's a hard choice to make. But be clear and obvious within the app about what's going on with the user's data. Don't be sending it to some server without making that clear within the app, especially if it's not providing any extra utility to the user.

**Don't push people to be unhappy.** Do not purposefully or accidentally force people to be unhappy to use their app. Don't force people to state their unhappy in order to access a feature. It's easy for this to sneak up in the design, if a user has to rate their happiness below average in order to access the CBT features, you're asking them to be unhappy to use your app.

**Be extremely cautious about making engagement your core metric.** User engagement is fine to be concerned about. We all want people who need help to be actually engaging in the help. But holy moly becareful about this. You _do not_ want to drive something that is for many people a treatment into a self-perpetuating engagement loop. A ruthless focus on engagement has caused many a product to become skinner boxes. _No one should ever be addicted to your mental health app._

# Engineering Logic

Quirk _must not_ lose user data. The entire point of the app is to record your thoughts, so if you lost them it would be pretty bad. As stated in [one study](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6010839/):

> While an app failure in general can be inconvenient and annoying, it can have serious consequences in the context of mental health apps—someone who has come to rely on an app for emotional support can find a failure “devastating.”

Therefore, data management should be given a higher priority than any other part of the app.

## Taxonomy and Order of Data Failure Cases

The following is a list of extremely _bad_ behaviors and states that could happen in order of severity.

### 1 - Large Scale Data Corruption

All thoughts have been corrupted somehow. For example, the JSON format of every item is wrong. This is put at the top because not only can a user not access the data, but it may spiral out can cause continuing errors forcing the app to be "bricked."

### 2 - Large Scale Data Loss

All thoughts have been deleted without any hope of recovery.

### 3 - Small Scale Data Loss

A small amount of data has been deleted without any hope of recovery.

### 4 - Small Scale Data Corruption

A small amount of data has been corrupted in a recoverable way. The user still has lost data, but the app does not crash, and this is potentially fixable via an update.

# License

Quirk is licensed under the [GPL](https://en.wikipedia.org/wiki/GNU_General_Public_License), which guarantees end users the freedom to study, share, and modify the software.

Note that this license **does not** give free reign to redistribute the name and branding of quirk. So if you'd like to publish your own version, please rename it to avoid end-user confusion.
