# Collecting Commissions Corrupts Product Coverage

###
<!-- To grasp the severity of the problem consider the analog of pharmaceuticals. -->
Would you trust newspapers that promoted pharmaceuticals with headlines like ‘*Why You Need an Antidepressant. Yes, You*’?

Would you be concerned if their articles only quoted sources working in the pharmaceutical industry?

What if their coverage included purchase links and that paid them a commission from each sale?

This is how much of the news media covers potentially-hazardous tech products today. The New York Times has, in fact, published an article with the headline [‘*Why You Need a Password Manager. Yes, You*’](https://www.nytimes.com/2019/08/27/smarter-living/wirecutter/why-you-need-a-password-manager-yes-you.html) in its Wirecutter section; CNET has implored [‘*Yes, You Need a Password Manager. Your Online Security Depends on It*’](https://www.cnet.com/tech/services-and-software/yes-you-need-a-password-manager-your-online-security-depends-on-it/); Engadget has urged [‘*You need a password manager -- right now*’](https://www.engadget.com/2019-08-26-the-best-password-managers-compared.html); and PCWorld has explained [‘*Why your browser’s password manager isn’t good enough*’](https://www.pcworld.com/article/393979/why-your-browsers-password-manager-isnt-good-enough.html).

All the above publications collect commissions when readers click on links to buy add-on password managers.[^nyt-affiliate-links-are-indirect] The free password manager built into your web browser, which some articles descrbe as not “good enough”, pays no commissions.[^in-favor-of-browser-managers]


[^nyt-affiliate-links-are-indirect]: The New York Times WireCutter's [‘Why You Need a Password Manager. Yes, You’](https://www.nytimes.com/2019/08/27/smarter-living/wirecutter/why-you-need-a-password-manager-yes-you.html) does not have direct affiliate links, but directs readers to another of their articles, [‘The Best Password Managers’](https://www.nytimes.com/wirecutter/reviews/best-password-managers/) which contains purchasing links. Similarly, CNET's [‘Yes, You Need a Password Manager. Your Online Security Depends on It’](https://www.cnet.com/tech/services-and-software/yes-you-need-a-password-manager-your-online-security-depends-on-it/) links to their [rankings of the password managers](https://www.cnet.com/tech/services-and-software/best-password-manager/) with purchasing links that pay commissions. Engadget and PCWorld embedded affiliate links directly into the articles promoting the product category.

Like pharmaceuticals, tech products can be hazardous and those persuaded to buy them can be harmed. The readers most clearly harmed by news articles about password managers may be those persuaded to buy LastPass. In 2022, attackers were able to steal LastPass's online databases of all their customers' data, including each user's database of stored passwords. That theft was particularly harmful because LastPass had failed to design their software to encrypt some of that data, and the encryption LastPass used to protect customers' passwords was woefully substandard. Both flaws had been exposed in 2018 by Wladimir Palant, a well-known security researcher.[^lastpass-iterations] LastPass's failure to fix these flaws may have led to the compromise of customers' passwords. Regardless, all customers needed to urgently change their passwords for every account they had stored in LastPass.

Many victims had purchased LastPass because the product had been widely recommended, despite its known security flaws and a prior breach in 2015. Among those that recommended it were The New York Times[^nyt-lastpass-rec]; PCWorld, which awarded it ‘*Best Overall*’ password manager in 2021; and CNET, which awarded it ‘*Best paid password manager*’ in 2021.[^wired-notes-security] Positive coverage helped LastPass accumulate one of the largest shares of the password manager market, if not *the* largest, despite the company's poor security track record.[^lastpass-market-share]

[^nyt-lastpass-rec]: The free edition of LastPass was recommended by The New York Times WireCutter prior its developer's acquisition by private equity in 2019, which completed in 2020. I could not isolate when The New York Times stopped recommending it because The New York Times only shows updated versions of articles and the 2019 and 2020 versions of the article could not be found via [archive.org](archive.org).



News organizations that collect commissions argue we can still trust them because they have editorial independence in choosing which product is best in its category.

> [We strive to be the most trusted product recommendation service around, and we work with total editorial independence. We won’t post a recommendation unless our writers and editors have deemed something the best through rigorous reporting and testing.](https://www.nytimes.com/wirecutter/about/)<br/> — The New York Times Wirecutter

But even if they do choose the best fairly, commissions can still bias the news media. They encourage more coverage of product categories that pay the most commissions and they encouraging more favorable coverage of those product categories as a whole.
<!-- It is surely not coincidence that lucrative products like password managers generate so much coverage, and so much of it positive, and with so little concern for potential hazards. -->

Commissions also discourage coverage of products' safety. Safety coverage reduces commissions because mention of one product's hazards can dampen readers' enthusiasm for the entire product category. Even before commissions, safety received insufficient coverage because it's expensive to investigate. 
<!-- It's no wonder coverage of lucrative product categories like password managers so often glosses over the products' hazards. -->

Commissions encourage organizations to hire editorial staff skilled and eager to cover lucrative product categories and discourage the hiring of staff skilled in scrutinizing product safety. They encourage workloads that don't afford time for scrutinize safety. Thus, commissions can corrupt even when editorial staff have total editorial independence.

Commissions can even corrupt the news media even if news organizations do not intentionally favor product categories with lucrative commissions. Organizations naturally inclined to provide more coverage of lucrative categories, and naturally inclined to make more of it positive, will be more profitable and out-survive others.

The extent to which industry has captured the media using commissions is evident from the sheer volume of articles promoting hazardous products without sufficient scrutiny of their risks. It is surely not coincidence that lucrative products like add-on password managers generate so much coverage, so much of it positive, and with so little concern for potential hazards.

To restore our trust, news organizations will need to give up their willful ignorance of the many ways commissions can bias product coverage and harm the public. Those organizations that continue collecting commissions should disclose every penny they receive from every affiliate link. Investigative journalists should follow the money that is not disclosed. A good place to start would be the tens of millions of dollars that may have been paid to the news organizations that recommended LastPass.[^money-flow]


---

#### Acknowledgements

Many thanks to Cormac Herley, Wladimir Palant, and Bruce Schneier for suggestions on earlier drafts.


[^editorial-independence]: For example, the second paragraph of [The New York Times Wirecutter about page](https://www.nytimes.com/wirecutter/about/) states “We strive to be the most trusted product recommendation service around, and we work with total editorial independence. We won’t post a recommendation unless our writers and editors have deemed something the best through rigorous reporting and testing.” Later they explain that “the decisions we make regarding the products we feature on our site are always driven by editorial and product testing standards, not by affiliate deals or advertising relationships.” PCWorld, a product of IDG Communications Inc., claims “editorial independence” because [“Our journalists are generally unaware of how much commission – if any – PCWorld receives from a purchase.”](https://www.pcworld.com/about/affiliate-link-policy) Even [Consumer Reports](https://www.consumerreports.org/), the gold standard in product coverage that insists on buying the products it reviews and touts being “ad-free”, influence-free”, and “powered by consumers”, collects affiliate commissions, including via their links to recommended password managers. While LastPass was not among their recommendations as of May 2023, their review of LastPass still rated it “Excellent in data security” despite all the evidence to the contrary.

[^in-favor-of-browser-managers]: For arguments why browser-based password managers may be safer, see a  [blog post by Tavis Ormandy](https://lock.cmpxchg8b.com/passmgrs.html), which I offer with the caveats that Ormandy wrote it while working for Google (maker of Chrome) and that it is fairly one-sided, eliding arguments that favor third-party password managers (e.g., zero knowledge architectures can be betrayed by sending clients malicious code as Ormandy argues, but since doing so risks exposing the betrayal, and so does not scale.)

[^lastpass-market-share]: In a 2021 [study](https://dash.harvard.edu/handle/1/37374029) co-authored with collaborators at UC Berkeley, LastPass had the largest market share among verified participants.

[^lastpass-iterations]: See Wladimir Palant's 2018 [Is your LastPass data really safe in the encrypted online vault?](https://palant.info/2018/07/09/is-your-lastpass-data-really-safe-in-the-encrypted-online-vault/) and post-breach article [LastPass breach: The significance of these password iterations](https://palant.info/2022/12/28/lastpass-breach-the-significance-of-these-password-iterations/),

[^lastpass-best]: Contact me for archival copies of both articles if necessary. At the time of writing, the [PCWorld article](https://www.pcworld.com/article/393979/why-your-browsers-password-manager-isnt-good-enough.html) was still online with the recommendation unchanged and the [CNET article was available via the Internet Archive](https://web.archive.org/web/20210707100536/https://www.cnet.com/tech/services-and-software/best-password-manager/).

[^wired-notes-security]: To the credit of Wired, author Lily Hay Newman did mention as early as [2018](https://web.archive.org/web/20200612063257/https://www.wired.com/story/password-manager-autofill-ad-tech-privacy/) that “The main drawback to LastPass is its mixed security track record—the product has had a number of high-profile, critical bugs and there have even been some data breaches. Overall, LastPass has weathered these storms, but it's worth noting.” (The act of “weathering the storms” does not appear to have included fixing the problems reported.)

[^money-flow]: The final [SEC Form 10-Q for the six months ending June 30, 2020 of LogMeIn](https://www.sec.gov/ix?doc=/Archives/edgar/data/0001420302/000156459020034298/logm-10q_20200630.htm), the developer of LastPass, reported sales and marketing expenses of \$235.5 million, of which \$92.2 million were bucketed as marketing expenses separate from the sales and marketing personnel, professional services, credit card transaction fees, and so on (the other \$147.7 million). The SEC report does not break down these expenses between LogMeIn's flagship LastPass and other products, and between affiliate commissions and direct advertising. Yet, even if LastPass commissions represented 10\% of that budget, it would mean that over ten million dollars of commissions were paid to those recommending LastPass in the year before the breach alone.