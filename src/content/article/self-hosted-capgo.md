---
slug: "self-hosted-capgo"
title: open-source licensing and why we're changing capacitor-updater to the LGPL license
description: I'm changing my license as I’ve become aware that there are risks associated with not enougth permissive open-source licenses that corporations that can't use.
author: Martin Donadieu
author_url: https://x.com/martindonadieu
created_at: 2022-04-08
updated_at: 2022-04-08
head_image: "/appflow_alt.webp"
head_image_alt: Appflow alternative illustration
tag: Alternatives
published: false
next_blog: ""

---
<!-- markdown-link-check-disable -->
Capgo is a 100% open-source web tool. My goal is to allow more maker to enjoy app live update by making a useful tool that doesn’t serve only big corporates.

The site owner gets some actionable to help improve they app, while the users keeps having a nice and experience. All with a fair cost

The easiest way to get started with Capgo is with my [official managed service in the cloud](https://capgo.app/), but if you’re happy to manage your own, you can also self-host Capgo on your server.

My managed hosting can save a substantial amount of time and. For most apps, this ends up being the best value option and goes to funding the maintenance and further development of Capgo. You’ll be supporting open-source and getting a great service!

![Capgo: Self-hosted Appflow alternative](https://capgo.app/assets/images/privacy-focused-web-analytics.webp "Capgo: Self-hosted Appflow alternative")

## What’s the difference between Capgo Cloud and Capgo Self-Hosted?

There is only one version of Capgo. Both my Cloud and my Self-Hosted products are completely equal. There’s no premium and exclusive commercial version with a better or more complete feature set.

You get the same dashboard, same actionable metrics and same commitment to [respecting the privacy of your visitors](https://capgo.app/privacy-focused-web-analytics) with both.

I started developing Capgo in December 2018, and I launched the SaaS subscription business in May 2019. The project is very much alive, actively developed and fast-growing. It is robust and battle-tested too.

Here are the differences between Capgo Cloud and Capgo Self-Hosted:

|   | Cloud | Self-hosted |
| --- | --- | --- |
| **Hosting** | Easy and convenient. It takes 2 minutes to start sending your first update, high availability, backups, security, and maintenance all done for you by me. I manage everything for you so you don’t have to worry about anything. | You do it all yourself. You need to get a server, and you need to manage your infrastructure. You are responsible for installation, maintenance, upgrades, server capacity, uptime, backup, security, stability, consistency, loading time and so on. |
| **Storage** | All visitor data is exclusively processed on EU-owned cloud infrastructure. I keep your site data on a secure, encrypted and server in Germany. This ensures that your site data is protected by the strict European Union data privacy laws and ensures compliance with GDPR. Your website data never leaves the EU. | You have full control and can host your Capgo on any server in any country that you wish. Host it on a server in your basement or host it with any cloud provider wherever you want, even those that are not GDPR compliant. |
| **Raw data** | You see all your site stats and metrics on my modern-looking, simple to use and fast loading dashboard. You can only see the stats aggregated in the dashboard. | Are you an analyst and want access to the raw data? Hosting Capgo yourself gives you that option. Take the data directly from the database and import it to a data analysis tool of your choice. |
| **Costs** | There’s a cost associated with providing an updater service, so I charge a subscription fee. | You only need to pay for your server and whatever cost there is associated with running a server. You never have to pay any fees to me, only to your cloud provider. |
| **Premium Support** | Real support delivered by real human beings who build and maintain Capgo. | Premium support is not included. Self-hosted release is community supported only. |
| **Releases** | Continuously developed and improved with new features and updates multiple times per week. | [It’s a long term release](https://capgo.app/blog/building-open-source) published twice per year, so the latest features won’t be immediately available as they’re battled-tested in the cloud first. |

## How can you be sustainable if you’re giving your software for free?

Funding is a big topic in the world of open-source software. Many open-source projects are terribly under-resourced and under-funded. Some people even have to sacrifice their financial security to work on their passion.

I believe that no financial sacrifice should be required to work on open-source. Making open-source sustainable is something we’re passionate about. To build competitive and open-source alternatives to popular proprietary tools, I need more people to be able to commit to open-source full time.

While Capgo is an open-source software that you can self-host for free, I also sell a hosted, plug and play solution as a SaaS. This is my only source of funding. I'm growing a sustainable open-source project, funded solely by the fees that my subscribers pay.

[My business model](https://capgo.app/about) has nothing to do with collecting and analyzing huge amounts of personal information from your users. I don’t make money by selling or sharing your data, or abusing your users privacy.

I am not interested in raising funds or taking investment either. Capgo is completely independent and bootstrapped. Revenue from paid subscriptions is used to pay my rent, further develop Capgo and allow me to commit to open-source full time.

If you choose to self-host Capgo you can [become a sponsor](https://github.com/sponsors/capgo) which is a great way to give back to the community and to contribute to the long-term sustainability of the project. Thank you to all of my GitHub sponsors. I appreciate your support.

For more views on the topic of open-source funding, see [how to pay your rent with your open-source project](https://capgo.app/blog/open-source-funding).

## Transparency as a key value of privacy-focused software

One aspect that makes Capgo different from many of the other web analytics providers such as Google is the fact that Capgo is [a fully open-source updater software](https://capgo.app/open-source-updater).

I am not a black box. There’s nothing proprietary or closed source about Capgo. Everything is in the open. My source code is available and accessible [on GitHub](https://github.com/cap-go/capgo).

Anyone can view, review and inspect the code i'm running to understand how it works and to verify whether my actions match with my words. This gives you, and everyone else, full transparency on how I handle users traffic data.

This is essential to me. Corporations and proprietary software cannot always be trusted when personal data is in question. This is one of the main reasons [why you should stop using close source software](https://capgo.app/blog/switch-open-source).

The only way to prove your trust is to allow the public and the experts to look into your code and verify that you practice what you preach. It is this transparency and openness that means that open-source products can be more trustworthy than proprietary products.

Many open-source projects offer a do-it-yourself, self-hosted deployment. Some people prefer that approach and want to host, run and maintain the software themselves on their server. And this is what you can do with Capgo too. Anyone can download my software, install it and run it on their server. Open-source enables this.

## What license is Capgo released under?

Capgo is open-source under the GNU Affero General Public License Version 3 (AGPLv3) or any later version. You can [find it here](https://github.com/cap-go/capgo/blob/master/LICENSE.md).

## How do I self-host Capgo?

This is the free as in beer and free as in speech version of Capgo. Here’s [how you can install Capgo Self-Hosted on your server](/docs/self-hosted/getting-started).
