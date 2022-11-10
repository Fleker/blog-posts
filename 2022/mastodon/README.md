# Why I think Mastodon will never replace Twitter

A week ago I went to [Join Mastodon](https://joinmastodon.org/) and signed up for an account, [@fleker@mastodon.world](https://mastodon.world/@fleker), and have been using it.

While there has been a sudden uptick in growth, most of the people I've followed on Twitter have not migrated. My timeline is fairly empty. I used a tool called [Debirdify](https://pruvisto.org/debirdify/) to help find my followers, but the number is still just a few dozen.

I wil continue to use Mastodon when something interesting comes up, but I don't think it'll ever replace Twitter. The main reason is that it seems incapable of scaling, perhaps intentionally, and that is going to hold it back in becoming a "global public square".

## Scaling servers

I visited the Mastodon homepage and joined the first server that the recommended for me, that being [mastodon.world](mastodon.world). Since that time, the number of linked servers have grown a lot. That's probably a good thing because a few hours after I created my account the server become overwhelmed.

https://mastodon.world/@fleker/109293923488149179

7000 users is not a whole lot, certainly many orders of magnitude to the [~200M daily active users](https://www.statista.com/statistics/970920/monetizable-daily-active-twitter-users-worldwide/) on Twitter. The admin on the server is trying their best to meet capacity, but they don't have the resources of a large corporation to handle large flows of traffic.

### Fediverse

Some critics would say this isn't fair, since Mastodon isn't a single instance. It's designed to be federated. Rather than Twitter managing everything, anyone can spin up and host a Mastodon network. Even Trump is using the open-source platform as [the basis for his Truth Social](https://www.theverge.com/2021/10/29/22752850/mastodon-trump-truth-social-network-open-source-gab-legal-notice).

But that's one exception. Many servers operate in a broader network called the Fediverse which includes sites like [mastodon.social](mastodon.social). It's easy for me to follow accounts and boost posts between servers.

### Onboarding

![](https://github.com/Fleker/blog-posts/blob/db1a98bb82d02c3417666e671634fa7589721d4d/2022/mastodon/Screen%20Shot%202022-11-04%20at%2012.29.17%20PM.png)

Except maybe it's not that simple. Right away you run into a limitation of this approach. I opened up someone's account, which is on mastodon.social, and saw a post I wanted to boost. I need to do one of these two things. But I don't have an account on mastodon.social. So now I need to copy this link and open a new tab and use the search bar and this adds a bit of friction to something that is a core use-case.

![](https://github.com/Fleker/blog-posts/blob/db1a98bb82d02c3417666e671634fa7589721d4d/2022/mastodon/Screen%20Shot%202022-11-04%20at%2012.32.53%20PM.png)

Even following accounts requires opening a bunch of windows and tabs. When I see someone on Twitter linking their Mastodon account page, the process to actually completing my task is cumbersome. The onboarding documentation could use a lot of work to make interactions more clear.

After a week I understand how to do these tasks, but it doesn't make it any less cumbersome. Even the first step, picking a server to join, creates more questions. Does it matter which I join? Yes, but no. Since it affects my "Local" timeline but not the "Federated" timeline and has no effect on my "Home" timeline, I guess it's irrelevant.

https://twitter.com/GernotWagner/status/1590256992916238336

But there are lots of servers that are popping up for all kinds of topics. mastodon.world is sort of broad, but there are [a number of servers](https://joinmastodon.org/servers) on topics like art, gaming, and other themes. There are even more that aren't listed, since anyone can create their own.

https://twitter.com/ashtonpittman/status/1588626168391127040

Picking just one server might present an existential question to some, since people may want to have one account and interact with a number of topics and interests. You can still engage with these communities, but it can affect the way you present yourself to the world.

There are some cool communities [like one for science academics](https://fediscience.org/about) that I'm not able to join. Each server admin can make it public to join or require manual review of each application. This means that something like `fleker@fediscience.org` does wind up becoming impossible since I'm not in that community. Yet, as part of the Fediverse, I can still follow those public accounts.

This leads to a sort of status symbol not unlike Twitter's verified symbol, which has rightly been criticized for [being applied arbitrarily and infrequently](https://www.theverge.com/2021/8/13/22623714/twitter-verification-program-pause-fake-accounts-review). Musk's effort to make the verified symbol available to more people is good in theory, though in practice it hasn't been thought through.

### Can't scale servers

![](https://github.com/Fleker/blog-posts/blob/db1a98bb82d02c3417666e671634fa7589721d4d/2022/mastodon/Screenshot%20from%202022-11-10%2011-34-25.png)

Even on small instances I've experienced a lot of server lag. Trying to do simple tasks like following accounts can take up to half a minute and then fail. It's frustrating and will lead to users leaving. There's a [direct correlation between page load times and bounce rates](https://www.section.io/blog/page-load-time-bounce-rate/). That is, the longer it takes to complete common tasks, the less users will do it. They'll just get frustrated and leave.

https://twitter.com/JoeMerrick/status/1589986161870921729

This is a problem every web service faces as it scales. Twitter famously had the [fail whale](https://business.time.com/2013/11/06/how-twitter-slayed-the-fail-whale/) for years until their hired enough engineers to develop a reliable and sustainable service. Now that [Twitter engineering may be understaffed](https://www.technologyreview.com/2022/11/08/1062886/heres-how-a-twitter-engineer-says-it-will-break-in-the-coming-weeks/), its reliability seems likely to unravel. Can Mastodon do better?

Unfortunately, Mastodon cannot scale to millions of users while being as reliable as Twitter. Being decentralized, every server is dependent on themselves to continue running reliably. Server costs can get massive. Twitter recently reported about [$1.7 billion](https://s22.q4cdn.com/826641620/files/doc_financials/2021/ar/FiscalYR2021_Twitter_Annual_-Report.pdf#page=50&zoom=auto,-158,734) in annual infrastructure costs. mastodon.world gets funding from [a Patreon page](https://www.patreon.com/mastodonworld) where it raises $262 per month.

That's not enough money to hire even a single reliability engineer. Perhaps it can pay to run a single server, but it cannot scale. Pretty soon people will have to go to second-tier servers and people like me will gain some status as being one of the few that got in early with a cool server.

So the server is run by the grace of a few volunteers, which is not sustainable. Depending on volunteers to do the work of full-time employees [is a bad idea](https://fleker.medium.com/dont-trust-open-source-software-it-s-inherently-insecure-f2d87cdb76d4).

Twitter gets around these costs largely by selling advertising. With access to a large audience, Twitter is able to target ads to individual customers and take a payment. At scale they can get billions in revenue.

Mastodon has no ads, and is not beholden to [creating a safe environment for advertiers](https://www.nytimes.com/2022/11/04/technology/twitter-advertisers.html).

Critics might say that if I don't trust mastodon.world to be reliable, I can just spin up my own server. But I think this misses the point.

https://twitter.com/AlecStapp/status/1588900946548965376

https://twitter.com/RippleStream/status/1589369551728562176

Mastodon can be compared to email: a decentralized network with many different servers that all talk to one another. But nobody manages their own email server. Nobody wants to do that. They just want email to work. Even if my printer was open-source and highly repairable, I actually never want to fix my printer. I just want it to work. That's why I write blog posts on Medium rather than constantly tinkering on my own blog toolchain.

There are [highly-managed Mastodon servers](https://masto.host/) which take out most of the work, but I still would rather not have to pay and manage something. As a software engineer I don't want to do it, and I can expect most people to be even more reluctant. And that's why companies like Microsoft and Google have created their own email products, maintaining services, ejecting spam, and [moderating repugnant content](https://www.theverge.com/2019/2/25/18229714/cognizant-facebook-content-moderator-interviews-trauma-working-conditions-arizona).

## Scaling audiences

Right now Mastodon in general has relatively few users, and Twitter's value largely comes from the [network effect](https://en.wikipedia.org/wiki/Network_effect) of already have many users. It requires a lot of marketing to get enough growth to create this value, and we've already seen that Mastodon cannot fund much marketing. If they could, individual servers would have trouble managing that growth. So instead it might have slow and middling growth that will never reach a hundred million daily active users.

This makes it hard to convince big names to join, since they won't get nearly as many followers. As an example, one person has 300K followers on Twitter and hardly over 1000 on Mastodon. If one platform gives less engagement, you'll engage with it less. Even if you cross-posted everything, fewer replies lead to less time spent.

https://mstdn.social/@robinsonmeyer/109315263261066312

https://twitter.com/AustingrahamZ1/status/1029385497213366279

As a global social network, high-profile Twitter accounts have developed a certain style of writing. They tend to use language that hedges a lot, already anticipating angry replies and quote tweets from strangers. I've noticed that Mastodon lets you boost posts, retweets, but you can't add your own opinion.

Quote tweets [are absolutely toxic](https://onezero.medium.com/quote-tweets-have-turned-us-all-into-jerks-d5776c807942). It enables you to not only harass a particular account with your own dunk, but broadcasts your dunk to your entire audience to enable a greater pile-on. Not allowing that, Mastodon might lead to less hostility. At the same time, a good dunk has become a way to gain visibility and social clout. That's why people do it.

https://mstdn.social/@joncollinsdev/109304833282324452

A healthy community does not mean a large one. People enjoy status and gravitate toward things that raise their status. In one particular example that has led to influencers who get paid to promote products. In another example that's led high-profile Twitter accounts to create paid Substack newsletters. In both examples their social media brand becomes part of their business, a way to market themselves.

Mastodon doesn't promote that kind of interaction. There's no algorithmic sorting or promoted toot function. As such, prominent creators aren't going to get very much out of it. Even things like boost and favorite numbers are hidden from the main timeline, making it hard for passersby to see who is "winning".

But then why use Mastodon if not for boosting your status? For good conversation and learning new things? Sure. But that definitely will limit usage. Open source development involves people doing tons of work without getting paid, which [isn't a good thing](https://fleker.medium.com/dont-trust-open-source-software-it-s-inherently-insecure-f2d87cdb76d4). On social media, the individuals on the network are creating the content. If they don't get much out of it, they won't put much into it.

A healthy community is fine, but I also need to eat.

## A global square with non-global rules

https://mastodon.social/@Alon/109308912093409357

Mastodon, being decentralized, means there is no one standard for how you're allowed to interact on the platform. Individual admins own each server and they're just volunteers. Beyond that there's no real oversight. There's no paid full-time security team monitoring network intrusions or preventing phishing. Even that's not necessarily a panacea, but giving over all your conversations to a handful of unpaid volunteers doesn't give confidence they'll be too reliable.

Mastodon's federated nature is also controlled by the server admins, who can [turn off entire domains from your timeline](https://docs.joinmastodon.org/admin/moderation/#server-wide-moderation). That's probably not bad in the abstract, as there are porn and Nazi Mastodon servers that I don't want to see. But that does present potential inter-admin political fights that might create problems due to a lack of central leadership.

https://twitter.com/HandNF/status/1589370404040478720

It's true that the admins of mastodon.world [can read my DMs](https://github.com/mastodon/mastodon/issues/18079). That's not a problem if I trust the admins to act in good faith. But I certainly don't trust them to keep the server secure. Even Twitter has had [major infiltrations to tools](https://blog.twitter.com/en_us/topics/company/2020/an-update-on-our-security-incident) which gave hackers access to far too much. They used this to shill cryptocurrency and accessed DMs from certain accounts.

Twitter's access control was too broad, but it doesn't seem like Mastodon does this any better. A similar spear phishing attack would only affect users of a single server, but would still have a big impact. If dissidents were using a Mastodon instance, what's to prevent the admin becoming [a spy](https://www.theguardian.com/us-news/2022/aug/09/twitter-saudi-arabia-dissident-spying)? Saudi Arabia paid one Twitter employee $300K to identify dissident Twitter accounts.

Do I really trust a voluntary admin with something too sensitive? Are they less willing to take a bribe? I don't know. Given the decentralized nature, it would be much harder for them to get caught. Central leadership has a number of problems too, but can be more accountable. As a public company, Twitter would see an immediate effect during scandals and could be steered toward something that kept people using it.

https://twitter.com/elonmusk/status/1590755506112823296

The global square often means a global zeitgeist, and [people enjoy belonging to something](https://www.mayoclinichealthsystem.org/hometown-health/speaking-of-health/is-having-a-sense-of-belonging-important). Elon Musk has been the topic of conversation for weeks and everyone joins together to dunk on him. It's toxic, but addictive. It makes us sad, but gives us [a sense of purpose](https://xkcd.com/386/).

![https://xkcd.com/386/](https://imgs.xkcd.com/comics/duty_calls.png)

If Mastodon is broken apart into small, niche servers where I can't grow an audience by quote-tweeting and dunking on people, it doesn't generate outrage. But people use Twitter to be outraged.

## Conclusion

Mastodon and the underlying [ActivityPub spec](https://www.w3.org/TR/activitypub/) are actually neat technology, and I will continue to keep a tab open to Mastodon. Even better, it's [a PWA](https://web.dev/progressive-web-apps/) so I can keep it open in a separate window.

Having a number of dedicated servers for journalists and art can allow you to join and talk with niche communities, and that's a good way to make meaningful connections.

Niche communities are good, but that's the opposite of a single global community of people who can tweet and reply to each other.  And that's why Mastodon can never become a single global square.

Maybe it shouldn't.
