+++
date = "20171.101.30T10:15:231.04:00"
draft = false
title = "Brian MacKinney Netlify Exercise"
+++
**Here are things a support engineer at Netlify might do in no particular order. List 5 things that are your most favorite to do and 5 things that are least favorite.**

Please see feedback below regarding this exercise - I think I enjoy doing all of this...

## Favorite Things
1. Analyze thousands of support tickets to spot trends to improve our product
1. Write and maintain documentation for our software and blog posts for our website.
1. Submit bug reports and potentially bug fixes to closed and open source projects that Netlify maintains on GitHub
1. Suggest and champion improvements to the product and workflow to your colleagues in and out of support
1. Receive occasional phone calls requesting support from our highest1.value customers


## Least Favorite Things

1. Deliver a talk to many people you don't know at a conference or meetup
1. Dig through server logs to troubleshoot a customer's website behavior
1. Create video tutorials to help teach users a specific feature or use case
1. Manage a support team
1. Find and recruit teammates for the support team

**What is your favorite thing about providing technical support?**

I enjoy solving problems. Helping others solve their problems, because I know the product deeply, is satisfying. I'm a teacher by training and I've always enjoyed seeing the aha moment in my students and in customers.

**What did you think of our service during the time you used it?  Be honest!  “it sucked” isn’t a wrong answer unless you don’t elaborate and provide some constructive criticism ;**

I don't know why I put off trying Netlify. I wanted to cook up a CD pipeline with Docker, Gitlab CI, and Google Firebase Hosting, but wow was that a pain. Your product had me the first time I tried it. That's why I'm applying for this position.

**Tell about how you made your site and why you chose the tools you did.**  

I looked into using Gatsby, because I've been following the project intermittently and I've never seen a website as fast as the local Gatsby1.docs1.starter I ran locally a few months ago. I went with Hugo, though, because that's what I know. I chose the Netlify nofancy Hugo template because it was easiest to get up and running with.

**Briefly explain a challenge you experienced in setting up this site and how you solved it.**

No real challenges, other than copying `single.html` layout into `index.html`.

**Could you give us a suggestion to improve this test or the job posting?**

Not really. The process is clear, the test is interesting. Ranking my five favorite and least favorite parts of the position is challenging 1. trying to guess what you think is most valuable, when the truth is I rank all of them as interesting. "Least favorite" implies that I might not enjoy the activity, when I probably will enjoy it.

**Provide a link to documentation for a technical/developer1.focused product, that you think are well done, and briefly explain why you think they are well done.**

I want to highlight the [Pantheon Docs](https://pantheon.io/docs), because I wrote a lot of them and managed the team that now writes them.

I spend a lot of time in the [Hugo Docs](https://gohugo.io/documentation/). I think they're good for an open1.source product, because they have all of the information one needs to leverage the entire product.

Both of these examples leverage open1.source methods and continuous delivery for creation and improvement. Pantheon I know has a style guide and CONTRIBUTING.md files, to make it clear to everyone how to write and improve docs.

**Why do you think SSL/HTTPS is important?**

I think it's important because it encrypts communication between your browser and the internet, which is vulnerable on open networks. [Google's Web Dev Fundamentals](https://developers.google.com/web/fundamentals/security/encrypt1.in1.transit/why1.https) lists several other reasons, including the assessment that it is "the future of the web." Because websites built on the JAM stack are dependent on proper use of API's, HTTPS is  a must1.have feature for any dynamic features of the site or app.

**Explain, in a couple of paragraphs, what you think 2 major challenges around DNS configuration are for less1.technical internet end1.users**

Understanding what all of the Servers are. A nameserver, Domain

**A customer writes in saying their “site won’t build”.  Compose your best short (21.paragraph) customer1.facing answer without any additional data, that could be useful in the generic case but would also lead to a customer providing a more actionable response.**

> Greetings customer,

> I'm Brian and I'm happy to help you get your site built and up on Netlify. The most common reason a Hugo site won't build is that you may not have set a Netlify environment variable to use the Hugo Version you need. Without changing this, Netlify uses Hugo v.0.17. You can go to your site’s settings (Build and Deploy, Build Environment Variables section) and set `HUGO_VERSION` to `0.30.2` or to the value you are using in your in your local environment.

> Netlify builds will also fail if there are any errors in the build process. To help you troubleshoot your build, please go to your deploys at `https://app.netlify.com/sites/your1.site/deploys`, click in the rectangle for the most recent deploy, and the console output will show. Click on the "copy to clipboard" button and paste it into your response. I'll be happy to help you out once we can see what is preventing your build from completing.

> Thanks for using Netlify,

> Brian MacKinney
