# Awesome Chaos Engineering [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)


A curated list of awesome [Chaos Engineering](http://principlesofchaos.org/) resources.

#### What is Chaos Engineering?
> Chaos Engineering is the discipline of experimenting on a distributed system in order to build confidence in the system’s capability to withstand turbulent conditions in production. - [Principles Of Chaos Engineering](http://principlesofchaos.org/) website.

## Contributing

Please take a look at the [contribution guidelines](CONTRIBUTING.md) first. Contributions are always welcome!

## Contents
- [Culture](#culture)
- [Books](#books)
- [Education](#education)
- [Notable Tools](#notable-tools)
- [Papers](#papers)
- [Blogs & Newsletters](#blogs--newsletters)
- [Conferences & Meetups](#conferences--meetups)
- [Forums](#forums)
- [Twitter](#twitter)

## Culture
* [Principles Of Chaos Engineering](http://principlesofchaos.org/)
* [Chaos Community](http://chaos.community/)
* [Chaos Engineering](https://www.infoq.com/articles/chaos-engineering)
* [O'Reilly Velocity San Jose 2017: Precision Chaos](https://www.youtube.com/watch?v=C11LNUEaHuo)
* [The Discipline of Chaos Engineering](https://blog.gremlininc.com/the-discipline-of-chaos-engineering-e39d2383c459)
* [Chaos Monkey for Fun and Profit](https://medium.com/production-ready/chaos-monkey-for-fun-and-profit-87e2f343db31)
* [Fault Injection in Production: Making the case for resilience testing](https://queue.acm.org/detail.cfm?id=2353017)
* [Lord of Chaos - Becoming a Chaos Engineer](https://vimeo.com/groups/jz2016/videos/181925286)
* [Chaos testing - Preventing failure by instigation](http://www.cakesolutions.net/teamblogs/chaos-testing-preventing-failure-by-instiga)
* [Orchestrated Chaos](https://docs.google.com/presentation/d/1zzHS3qoPGzwsSna5-uk3Xt7LW_3Fr6ag8JDkeyrKwL4/edit#slide=id.p)
* Choose your own adventure: Chaos Engineering - [Video](https://www.infoq.com/presentations/adopt-chaos-engineering) & [Slides](https://www.slideshare.net/NoraJones1/choose-your-own-adventure-qcon-2017-1)
* [AMA Chaos Engineering + DiRT](http://pages.catchpoint.com/AMA-Chaos-DiRT.html)
* [SRECON17: Principles of Chaos Engineering](https://www.usenix.org/conference/srecon17americas/program/presentation/rosenthal)
* [Chaos & Intuition Engineering at Netflix](https://www.youtube.com/watch?v=Q4nniyAarbs)
* [Mastering Chaos - A Netflix Guide to Microservices](https://www.youtube.com/watch?v=CZ3wIuvmHeM)
* [Too big to test: Breaking a production brokerage platform without causing financial devastation](https://conferences.oreilly.com/velocity/devops-web-performance-ny-2015/public/schedule/detail/45012)
* [Inside Azure Search: Chaos Engineering](https://azure.microsoft.com/en-us/blog/inside-azure-search-chaos-engineering/)
* [Netflix, the Simian Army, and the culture of freedom and responsibility](https://devops.com/netflix-the-simian-army-and-the-culture-of-freedom-and-responsibility/)
* [FIT: Failure Injection Testing](https://medium.com/netflix-techblog/fit-failure-injection-testing-35d8e2a9bb2)
* [The Netflix Simian Army](https://medium.com/netflix-techblog/the-netflix-simian-army-16e57fbab116)
* [Automated Failure Testing](https://medium.com/netflix-techblog/automated-failure-testing-86c1b8bc841f)
* [The Verification of a Distributed System by Caitie McCaffrey](http://queue.acm.org/detail.cfm?ref=rss&id=2889274)
* [The Journey to Chaos Engineering begins with a single step - Bruce Wong and James Burns (Twilio)](https://www.youtube.com/watch?v=rKAo2wANiHM)
* [Chaos Engineering by Lorin Hochstein](https://www.youtube.com/watch?v=vq4QZ4_YDok)
* [Aaron Rinehart - ChaoSlingr: Introducing Security based Chaos Testing](https://www.youtube.com/watch?v=BLRb-E0G5zk)
* [Chaos Engineering - Casey Rosenthal](https://www.youtube.com/watch?v=6OIOpx_dVFY)
* The Road to Chaos - Velocity 2017- [video](https://www.youtube.com/watch?v=FCZVAZaXIjs) & [slides](https://github.com/norajones/Presentations/blob/master/The%20Road%20To%20Chaos%20-%20Velocity%202017.pdf)
* [How Netflix DDoS’d Itself To Help Protect the Entire Internet](https://www.wired.com/story/netflix-ddos-attack)
* [10 Years of Crashing Google](https://www.usenix.org/conference/lisa15/conference-program/presentation/krishnan)
* [Weathering the Unexpected](http://queue.acm.org/detail.cfm?id=2371516)
* [SRECON17: Breaking Things on Purpose](https://youtu.be/h_-shm0SL08)
* [PuppetConf 2016: Chaos Patterns - Architecting for Failure in Distributed Systems](https://youtu.be/V3P35N_HXNQ)
* [Ship More, Sink Less - Changing Chaos Engineering and Distributed Tracing](https://youtu.be/nr2KWbyWAmA)
* [Cloudcast - Discipline of Chaos Engineering](http://www.thecloudcast.net/2017/05/the-cloudcast-299-discipline-of-chaos.html)
* [Software Engineering Daily - Failure Injection with Kolton Andrus podcast](https://softwareengineeringdaily.com/2017/03/29/failure-injection-with-kolton-andrus/)
* [Responding to Failures in Playback Features with Haley Tucker podcast](https://www.infoq.com/podcasts/netflix-haley-tucker?utm_campaign=infoq_content&utm_source=twitter&utm_medium=feed&utm_term=architecture-design)
* [Distributed Chaos Operations](https://www.youtube.com/watch?v=8xIeu4S-Cro)
* ["Antics, drift, and chaos" by Lorin Hochstein](https://youtu.be/SM2uXpmyJmA)
* [re:invent 2017: Nora Jones Describes Why We Need More Chaos - Chaos Engineering, That Is](https://youtu.be/rgfww8tLM0A)
* [Failure Friday: Four Years On](https://www.pagerduty.com/blog/failure-fridays-four-years/)
* [Monkeys & Lemurs and Locusts, Oh my!](https://www.slideshare.net/zgrinch/monkeys-lemurs-and-locusts-oh-my)

## Books
* [Chaos Engineering: Building Confidence in System Behavior through Experiment](http://www.oreilly.com/webops-perf/free/chaos-engineering.csp)
* [Site Reliability Engineering: How Google Runs Production Systems](https://landing.google.com/sre/book.html)
* [The Practice Of Cloud System Administration: Designing and Operating Large Distributed Systems](http://the-cloud-book.com/)
* [Antifragile Systems and Teams](http://www.oreilly.com/webops-perf/free/antifragile-systems-and-teams.csp)

## Education
* A Chaos Engineering Bootcamp for O'Reilly Velocity 2017 - [Slides](https://speakerdeck.com/tammybutow/chaos-engineering-bootcamp) & [Source code](https://github.com/tammybutow/chaos_engineering_bootcamp)
* [Your First Chaos Experiment](https://blog.gremlininc.com/your-first-chaos-experiment-321ec4468bce)
* [Chaos Engineering 101](https://medium.com/production-ready/chaos-engineering-101-1103059fae44)
* [A Primer on Automating Chaos](https://blog.gremlininc.com/a-primer-on-automating-chaos-84ff4b053be0)

## Notable Tools
* [Chaos Monkey](https://github.com/Netflix/chaosmonkey) - A resiliency tool that helps applications tolerate random instance failures.
* [The Simian Army](https://github.com/Netflix/SimianArmy) - A suite of tools for keeping your cloud operating in top form
* [orchestrator](https://github.com/github/orchestrator) - MySQL replication topology management and HA
* [kube-monkey](https://github.com/asobti/kube-monkey) - An implementation of Netflix's Chaos Monkey for Kubernetes clusters
* [Gremlin Inc.](https://www.gremlininc.com/) - Failure as a Service
* [Pumba](https://github.com/gaia-adm/pumba) - Chaos testing and network emulation for Docker containers (and clusters)
* [Chaos Toolkit](https://github.com/chaostoolkit/chaostoolkit) - A chaos engineering toolkit to help you build confidence in your software system.
* [ChaoSlingr](https://github.com/Optum/ChaoSlingr) - Introducing Security Chaos Engineering. ChaoSlingr focuses primarily on the experimentation on AWS Infrastructure to proactively instrument system security failure through experimentation.
* [PowerfulSeal](https://github.com/bloomberg/powerfulseal) - adds chaos to your Kubernetes clusters, so that you can detect problems in your systems as early as possible. It kills targeted pods and takes VMs up and down.
* [drax](https://github.com/dcos-labs/drax) -  DC/OS Resilience Automated Xenodiagnosis tool. It helps to test DC/OS deployments by applying a Chaos Monkey-inspired, proactive and invasive testing approach.
* [Wiremock](http://wiremock.org/) - API mocking (Service Virtualization) which enables modeling real world faults and delays
* [MockLab](http://get.mocklab.io/) - API mocking (Service Virtualization) as a service which enables modeling real world faults and delays
* [Pod-Reaper](https://github.com/target/pod-reaper) - A rules based pod killing container. Pod-Reaper was designed to kill pods that meet specific conditions that can be used for Chaos testing in Kubernetes.
* [Muxy](https://github.com/mefellows/muxy/) - A chaos testing tool for simulating a real-world distributed system failures.

## Papers
* [Simple Testing Can Prevent Most Critical Failures: An Analysis of Production Failures in Distributed Data-Intensive Systems](https://www.usenix.org/system/files/conference/osdi14/osdi14-paper-yuan.pdf)
* [Lineage-driven Fault Injection](https://people.eecs.berkeley.edu/~palvaro/molly.pdf)
* [Automating Failure Testing Research at Internet Scale ](https://people.ucsc.edu/~palvaro/fit-ldfi.pdf)
* [Principles of Antifragile Software](https://arxiv.org/abs/1404.3056)

## Blogs & Newsletters
* [Netflix Technology Blog](https://medium.com/@NetflixTechBlog) - Learn more about how Netflix designs, builds, and operates our systems and engineering organizations
* [Production Ready](https://tinyletter.com/production-ready) - A mailing list about building resilient infrastructure and tools.
* [SRE Weekly](https://sreweekly.com/) - Weekly Site Reliability Newsletter.
* [Site Reliability Engineering resources](https://github.com/dastergon/awesome-sre) - A curated list of awesome Site Reliability and Production Engineering resources.
* [SysAdvent](https://sysadvent.blogspot.com) - One article for each day of December, ending on the 25th article.
* [Gremlin Blog](https://blog.gremlininc.com) - Blogs on Chaos Engineering from Gremlin Inc.
* [O’Reilly Systems Engineering and Operations Newsletter](http://www.oreilly.com/webops-perf/newsletter.html) - Weekly systems engineering and operations news and insights from industry insiders.

## Conferences & Meetups
* [SRECon Conferences](https://www.usenix.org/conferences/byname/925) - The Official SRE Conference.
* [LISA Conferences](https://www.usenix.org/conferences/byname/5) - Prominent Conference About SysAdmin/DevOps/SRE.
* [O'Reilly Velocity Conference](https://conferences.oreilly.com/velocity/)
* [Chaos Engineering Community Meetup Group](https://www.meetup.com/Chaos-Engineering-Community/) - Bay Area Meetup group for Chaos Engineers
* [London Chaos Engineering Community](https://www.meetup.com/London-Chaos-Engineering-Community/)
* [Chaos Engineering Community](https://www.meetup.com/pro/chaos/)

## Forums
* [Chaos Community Google Group](https://groups.google.com/forum/#!forum/chaos-community)
* [Chaos Engineering LinkedIn Group](https://www.linkedin.com/groups/7057761)
* [Chaos Engineering Slack Community](gremlin.com/community)

## Twitter
* [Aaron Blohowiak](https://twitter.com/aaronblohowiak)
* [Casey Rosenthal](https://twitter.com/caseyrosenthal)
* [Mathias Lafeldt](https://twitter.com/mlafeldt)
* [Nora Jones](https://twitter.com/nora_js)
* [Tammy Bütow](https://twitter.com/tammybutow)
* [Bruce Wong](https://twitter.com/bruce_m_wong)
* [Kolton Andrus](https://twitter.com/koltonandrus)
* [Lorin Hochstein](https://twitter.com/lhochstein)
* [Peter Alvaro](https://twitter.com/palvaro)
* [John Allspaw](https://twitter.com/allspaw)
* [Charles Torre](https://twitter.com/carmine007)
* [Russ Miles](https://twitter.com/russmiles)
* [Aaron Rinehart](https://twitter.com/aaronrinehart)
* [Mikolaj Pawlikowski](https://twitter.com/mikopawlikowski)
