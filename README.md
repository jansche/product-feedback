> **This document is work in progress. Feel free to contribute. More ideas and different opinions are always appreciated.**
> 
> _This document has been developed during my job search for a DevRel role in 2021. It may be useful as an inspiration for future DevRel programs. Use it at your own discretion. It's published under the [MIT license](LICENSE). Please let me know if you use it._
> 

# Product Feedback through Developer Relations – A Program Framework


## Executive Summary
This program suggets a framework for organising product feedback programmatically. Honest and quality-assured handling of user feedback paves a road to success in these ways: 
    **Product:**
    Improving and aligning development of a product to the requirements of its users is essential. The earlier usage trends, design flaws and security issues are discovered, the easier it is to implement the fix into the product. Developer Relations has access to qualitative feedback from the most experienced users. These users are not only influential, but also have a wide network and a great understanding of real life application of the product.
    **Brand:**
    A reliable and transparent process in product feedback will eventually pay towards brand trust. Authentic realtionships with developers support positive word of mouth, overall favorability and individual willingness to pay for services. A trusted brand is a competitive advance.
    **Relationships:** 
    All managed and unmanaged relationships from developer advocates include conversation about the product at some point. Be it positive or negative. Providing a way to capture this feedback (subject to consent) and track it throughout its lifecycle will benefit both sides of the relationship. The advocate has a talking point with the community member, and may reconnect from time to time just to give a status update. The feedback provider feels empowered and taken seriously. The more if their feedback makes it to a product improvement or feature. 

Managing product feedback in a reliable durable process secures success in all of the above areas. This framework focuses on setting up inclusive processes to provide transparency, authenticity, a stable flow of feedback and trusted relationships between stakeholders. It seeks diversity and quality, and helps product and developer relations through a neutral unbiased approach.


> **Feedback and content/documentation are the two key assets that Developer Relations contribute to a product.**


## Description
From the three pillars of Developer Relations (relationship management, content and product feedback) product feedback is for sure the most underrated. Yet it is also the most powerful one. External feedback to a product discloses hidden flaws in design, unexpected use cases and security issues. It provides a fresh perspective and helps evaluate assumptions. 
This document on gathering and processing product feedback through and with Developer Relations is meant as a starting point for implementing a process at [company name] for improving how external and internal product feedback has the opportunity to contribute to product development. It’s written with a corporate structure in mind, where Developer Relations is a separate organization in Engineering or Marketing, but many of the key aspects may also apply to organizations where Developer Relations is fragmented over various product groups or product marketing. 

Focus of this document is the operational details to streamline feedback from internal and external sources.


## Opportunity and Value Prop 
-	With a diverse community you get:
-   Diverse feedback
-   Diverse (and new) use cases
-	Honesty
-	Pay back to a beloved product (also risk: bashing "because I hate it")
-	Pride moment
-   Share of Voice



## Situation Analysis

## What a Product Feedback Program can do (besides the obvious, e.g. identify security flaws)
-	Contribute to customer and partner success
-	Pay back to the community
-	Build brand trust 
-	Nurture a fan community
-	Contribute to other programs (see https://github.com/jansche/oss-advisors)



## What a Product Feedback Program can’t do
-	Take responsibility for business decisions
-	Access a pool of unpaid product testers
-	Replace quality assurance processes
-	Substitute bounty bug hunts
-	Amplify content or marketing campaigns

## What is Product Feedback
tbd

## Program Objectives and Key Results
-	Building a network of responsive experts that are committed to providing high-quality product feedback from themselves and their communities
-	Organically nurture external voices for [company’s name]’s products
-	Provide clear structure and framework for managing feedback end-to-end
-	Setup a toolset for product feedback management
-	Setup an interaction scheme

### Projected impact (not all apply to all OSS Advisors evenly), Key Results
- tbd


### What is Success (tools of measurements in brackets)
-	The product team loves the feedback and is able to improve quality and develop features with the input from this program. (engineering NPS, eNPS)
-	A vivid exchange between external feeback providers, advocates and product group representatives, the group is well interconnected. (Vitality or workgroup health index of the program)
-	Feedback turns into product development or feature.
-	Feedback-induced feature get publicity on social media. (Original content mentioning [company’s name]’s efforts, Share of Voice) 
-	Product becomes more accessible and inclusive through this program. (accessibility features added, removal of bias from product experience)

## Stakeholders
-	Developer Advocates for ongoing interaction and lead in product feedback and content alignment
-	Product teams, TPMs for product feedback
-	Engineering Leads for commitment in product teams
-	VP as sponsor of the program

## Scenarios (names and companies are made up)
### Scenario A: 
Developer Advocate Janice Mokambu (they/them) is speaking on a tech conference online. They finish their talk and hop on an AMA (ask me anything) session right after. They hear back from session attendee Lin Da Lee (she/her) that Janice’s product API is returning invalid results when used consequently during the change of hour while not re-authenticating. They fixed this by force re-authentication before each request, which results in a performance loss. Janice asks the attendee to pass them their contact details via Twitter IM or email, notes down the case and gets into touch with the product team.  They can’t reproduce, but after a quick chat with Lin Da, it turns out the problem only occurs over a UTC date change. Since the engineering team is based in Europe, they never experienced this flaw themselves. Lin Da’s team is located in China, and they repeatedly came across this issue during their regular working hours.
Engineering is fixing the issue with input from the product team, who had a call with the product manager from Lin Da’s company that helped narrow down the issue. Janice was involved in every step, but they didn’t have to have much interaction in this case. The product team informed them when the update would go live, so Janice could chat with Lin Da and let them know that their feedback was deeply appreciated and how to plan for the update, so they could improve their experience and performance accordingly.
After the update got live, Janice and the product team work together to feature Lin Da on their social channels and award her a certificate, that got designed for product feedback through community.

### Scenario B:
Data Scientist Jules Ng (he/him) - while working on a machine learning model – finds an outdated piece of documentation for [company name]’s machine learning product online. They can’t fiddle out how to use the description for the newer version and turns to Reddit for help. Jules gets a few comments, two of them pointing him to an also outdated blog post by [company name]’s technical writer Emma Schoemaker (she/her). Jules decides to leave a comment on the blog to vent his anger. He’s about to switch to AutoML, [company name]’s competitor, when Emma replies to his comment, pointing them to a newer article on dev.to, which is still in draft mode. Jules is able to finish implementation and also gets asked by Emma if he wants to be their guest on the podcast [company name]’s developer advocate Janice Mokambu (they/them) is producing. She also updates the official documentation to the newest release, and informs the product group of the breaking changes in their last version.  On the podcast, Janice, Jules and Emma talk about the need for up to date documentation, but also on technical requirements, competitors and the future of Machine Learning.

### Scenario C: 
Yoha Mitchell (she/her) is a professional power user and hobby developer for [company name]'s cloud service. Yoha loves to automate things, and tends to overshare on social media. She'd like to see an extension to [company name]'s product API, so she could build a template that might be helpful to a bunch of people. She's unsure about her developer skills, and asks Twitter for advice. Several people jump the train and urge [company name] on social networks to implement the feature or at least provide a workaround. Developer Advocate Janice Mokambu (they/them) gets aware of the issue through their social monitoring tool, and answers the thread while communicating with the product group. They also inform [company name]'s Public Relations about whats going on on social. (They decide it's too small of an issue to need handling.)
The use case Yoha described was new to the product group, but could eventuall result in broader usage of the cloud service through hobbyists. Janice provides additional input, but a workaround is not available, while extending the product through an additional feature is not feasible short term ("hobbyists don't consume the paid version of the service"). Janice stays in contact with Yoha and collects more data over the next few weeks. They are crunching numbers with the product group and marketing to finally show a feature extension would be worth the effort.  During the time, Janice stays connected with Yoha, who became a friendly voice for [company name] on social thanks to Janice's ongoing communications. They finally succeed in a feature extension for the next version of [company name]'s cloud service and is allowed to let Yoha know she's been the reason for implementation. The news gets reteeted and shared on social, riding a trending topic #lowcodedevs #changetheworld hashtag combo.

## Collaborational details
-	Per product cadence meetings between product team, and developer advocates and an optional representative from engineering (suggested monthly)
-   Per case in-promptu asynchronous communication via company-approved chat tool
-   Tools usage consistency throughout all involved internal parties (don't add another tool, if the DevOps / bug tracking tool is able to cover feedback)
-   Dedicated external Slack/Discord/forum for product feedback or section/channel in company's developer outreach channels, monitored and nurtured by Community Program Manager (Advocates and product groups are at least reactively available.)
-   Third-party platform (e.g. UserVoice) for anonymous feedback
-   Beta program participation open to previous feedback providers
-   Availability of social media monitoring tool (e.g. HootSuite, TalkWalker, Onalytica, Radarly, EchoBot or other)
- Developer Advocacy with CRU(D)* access to DevOps / bug tracking system.

## Operational details

A structured approach to putting product feedback on the records is essential to managing and growing product feedback. For ease of consumption, I'll only focus on one of many toolsets, but please interpret the toolset as replaceable by any other toolset with similar capacities. It should be chosen with status quo in mind. Another tool adds another level of complexity, adds friction and raises the barrier for internal adoption of this program.

This example suggests **Azure DevOps** and uses "**on system**" whenever referring to the DevOps environment / bug tracking system.

### Decision making on how to record
[[Formal recording of feedback or informal mentioning during cadence meeting]]

### Ideal flow of feedback
    1) Product feedback is gathered, anonymized to avoid bias, pre-filtered, recorded, grouped, tagged and then handed over to product the group, with flags for high urgency items - all on system.
    2) Product group filters with business justification on system.
    3) Feedback gets prioritized through both, product group and Developer Advocacy on system. 
    4) If priority is marked as "very high" from one party, a chat or meeting between parties will be set up to define next steps within a matter of three days (one week if priority is "high"). Next steps include:
        -   interaction with feedback provider
        -   feasibility of a quick solution/fix
        -   availability of a quick solution/fix
        -   triage
        -   
        -   communication with feedback provider
        -   
### Example process 


### Filtering
tbd

### Building for diversity, equity and inclusion
tbd

### Feedback for feedback
tbd

### Standard communication templates
tbd

## Risks
tbd

## Appendix
Social Media Monitoring Tools:
- [HootSuite](https://www.hootsuite.com/)
- [TalkWalker](https://www.talkwalker.com/)
- [Onalytica](https://onalytica.com/)
- [Radarly / linkfluenc](https://www.linkfluence.com/)
- [EchoBot](https://www.echobot.io/)

CRU(D)
    Create, Read, Update, (Delete) - Deveoper Advocacy should have the ability to manage feedback entries in DevOps. Using DevOps in a collaborational cross-team spirit helps build trust between Product, Engineering and Advocacy.

