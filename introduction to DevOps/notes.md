1. # intro to devops

# week 1 overview of devops

### **course intro**

DevOps is the practice of development and operations engineers working together through the entire software development lifecycle, following Lean and Agile principles that allow them to deliver software in a rapid and continuous manner.

### **business case for DevOps**

disrution is inevitable. its not always about new technologies, but often about combinations of technologies into new business models.

but the message here is that technology is the enabler of innovation. It is not the driver of innovation. You must have a great business model idea and a great model and then leverage that technology.

### **devops adoption (cultural change)**

its also about a cultural change.

limit the blast impact when rolling into production. testing live with the market, and do live AB testing. microservices focused architecture .

[Velocity 09: John Allspaw and Paul Hammond, "10+ Deploys Pe](https://www.youtube.com/watch?v=LdOe18KhtT4)

[The Phoenix Project: A Novel About IT, DevOps, and Helping Your Business Win](https://www.amazon.de/-/en/Gene-Kim/dp/0988262592)

DevOps because DevOps is not about tools.

It's about trust, transparency, communication, coordination, and discipline.

[DevOps: Making the Middle Great Again - Hearst](https://www.youtube.com/watch?v=zMsi5zQ9wp8&list=PLvk9Yh_MWYuzyTmTgM36jF4E8SjzJrmRL)

### Definition of DevOps

new team culture

application design (move away from monolith)

automation to handle our microservices

dynamic continously deploying environment

devops is also applying agile to the operations team and having the developers and operations  working together and not in silos anymore. devops is not just about ops automations

dev is the developers. they develop software. then there are the operations side. they do all things that are necessary for the developed code to operate.   This is not DevOps. The Devs are still doing the same thing. This is not just Ops automation. That’s all it is, automating Ops. DevOps is not just Dev and it is not just Ops. It is DevOps. One word, one team, one set of measurements.

### Essential Characteristics of DevOps

After watching this video, you will be able to: Describe how applications evolved to give rise to DevOps, list the three dimensions of DevOps, and describe some essential characteristics of DevOps. Let's not lose sight of the goal. What is the goal? Agility is the goal.

**There are three pillars for agility.**

One of the pillars is DevOps. This includes cultural change, automated pipelines, infrastructure as code, and immutable infrastructure. speed and agility.

The second pillar is microservices and includes a loosely coupled application design using microservices that communicate via REST APIs. Microservices are designed to resist failure and are tested by breaking them and failing fast.

The third pillar is containers. Containers are developer-centric environments that give us portability and fast startup. They also enable an ecosystem that allows quick deploys with immutable infrastructure.

![Image.png](/assets/images/Image.png)

DevOps has three dimensions: culture, method, and tools.

And the essential characteristics of DevOps include cultural change, automated pipelines,

infrastructure as code, microservices, containers, and immutable infrastructure.

You must change your measurement system and measure differently because you always get

![Image.png](/assets/images/Image%20(2).png)

### Leading Up to DevOps

![Image.png](/assets/images/Image%20(3).png)

Well, there's no provision for change

### XP, Agile, and Beyond

extreme programming is all about iteration kent beck

![Image.png](/assets/images/Image%20(4).png)

pair programming 🙂

the agile manifesto from snowbird utah

the agile manifesto What they came up with is called the Agile Manifesto. The Agile Manifesto emphasized valuing individuals and interactions over process and tools; working software over comprehensive documentation; customer collaboration over contract negotiation; and responding to change over following a plan.

![Image.png](/assets/images/Image%20(5).png)

Work is done in increments called sprints. Planning is adaptive. We plan for the next two weeks, and then the two weeks after that, and then two weeks after that. Agile includes continuous improvement, that is asking what you learned, and what you are going to do to change.

**but what about ops**

2 speeds IT does not work (when devs and ops work at different speeds)

shadow IT (is when devs goes directly to outside to get stuff done)

**Agile development**

Agile emphasizes valuing individuals, collaboration, responding to change, adaptive planning, early delivery, and continuous improvement

### Brief History of DevOps

2007 to 2019

2007 patrick debois - figured out that dev and ops werent working well together

2008 Patrick Debois attended the Agile Infrastructure “Birds of a Feather” meeting, organized by Andrew Clay Shafer, in 2008 at the Agile Conference. Debois also started DevOpsDays in 2009.

2009 velocity conference dev and ops coop 10+ deploys a day also the bdevops days in belgium

2010, Jez Humble and David Farley wrote a groundbreaking book called Continuous Delivery

[Continuous Delivery: Reliable Software Releases Through Build, Test, and Deployment Automation (Addison-Wesley Signature Series)](https://www.amazon.de/-/en/Jez-Humble/dp/0321601912)

2013 the phoenix project book (listed earlier

2015, Dr. Nicole Forsgren, Gene Kim, and Jez Humble founded a startup called DORA (DevOps

Research and Assessment) that produced what are now the largest DevOps studies to date

called the State of DevOps Report.

2016 the devops handbook

[The Devops Handbook: How to Create World-Class Agility, Reliability, & Security in Technology Organizations](https://www.amazon.de/-/en/Gene-Kim/dp/1942788002)

Arrested DevOps podcast

[Arrested DevOps](https://www.arresteddevops.com/)

# **people in devops**

Patrick Debois,

Andrew Clay Shaffer,

John Allspaw,

Jez Humble,

Gene Kim,

John Willis,

Bridget Kromhout,

Nicole Forsgren,

# Summary and Highlights

Congratulations! You have completed this lesson. At this point in the course, you know:

- Technology is the enabler of innovation, rather than the driver of innovation. You must have an innovative business idea to leverage technology.
- In 2009, John Allspaw described an innovative approach to managing development and operations that enabled Flickr to complete over ten deploys per day, when many companies were completing fewer than one deploy every six months. This was a key moment in the growth of DevOps.
- DevOps is the practice of development and operation engineers working together during the entire development lifecycle, following Lean and Agile principles that allow them to deliver software in a rapid and continuous manner.
- DevOps is not it is not just Dev and Ops working together. It is a cultural change and a different way to work. DevOps has three dimensions: culture, methods, and tools. Of these, culture is the most important.
- The essential characteristics of DevOps include cultural change, automated pipelines, infrastructure as code, immutable infrastructure, cloud native application design, the ecosystem of containers, and how to deploy with immutable infrastructure.
- DevOps started in 2007 when Patrick Debois and Andrew Clay Shafer began to gather like-minded people together at conferences to talk about common experiences.
- In 2009, Allspaw delivered his now famous “10+ Deploys Per Day – Dev and Ops Cooperation at Flickr” presentation and the idea gained ground. Also in 2009, Patrick Debois started a conference called DevOpsDays that helped spread the DevOps message.
- Books such as *Continuous Delivery* in 2011, *The Phoenix Project* in 2015, and *The DevOps Handbook* in 2016, helped practitioners understand how DevOps worked.
- The major influential people of the early DevOps movement: Patrick Debois, Andrew Clay Shafer, John Allspaw, Jez Humble, Gene Kim, John Willis, Bridget Kromhout, and Nicole Forsgren, went out and made a difference, showing the results that could be achieved with DevOps.
- The message spread from practitioner to practitioner until they began to realize what was possible with DevOps and that it was a better way to work.

# week 2 thinking devops

### social coding principles

social coding - coding as a community

**new feature** You open up a GitHub Issue and you assign it to yourself so that everyone knows you’re working on it. Then you fork the repo, create a branch, and make your changes. When you’re all done and have something to contribute back, then you issue a pull request signaling that you are ready for a review and the repo owner can decide whether to merge your code back into the main project.

**pair programming** is 2 coders at a single workstation, swapping every so often.

Social coding is done communally with public repositories and all team members are encouraged to contribute. Pair programming results in higher quality code because defects are found earlier, costs are lowered, and there is a broader understanding of the codebase.

### Git Repository Guidelines

each microservice should have their own repository dont do monorepoes (not even if it is easier to demonstrate) you want people to just seee the code that they do care about 🙂

create a new branch for each issue you are working on. master branch and feture branches.

use pull requests to merge to master (always wanna have 4 hours, dont merge yourself)

**git feature branch workflow**

![Image.png](/assets/images/Image%20(6).png)

### Working in Small Batches

from lean manufacturing, gives fast feedback, doesnt waste too many resources

more experiments more feedback. keeping with devops workflow and cross functional teams.

**working in large vs small batches**

big batch 1000

large flow 50

single piece flow 1 : inspect

**HOW TO SIZE FEATURES**

Working in small batches helps you implement other DevOps practices like Continuous Integration and Continuous Delivery. So how do you know if your batches are small enough? I would start with the size of your stories in your backlog. Are your application features decomposed in such a way as to support frequent releases? You have to ask yourself, how often are releases possible? Are there delays in the release because the features are too large? Can features be completed in a sprint? If you have features that take several sprints, then your batches are too large. Optimally a feature should be small enough to be completed in a week or less. The features you build are one step toward a goal. Many people feel that only a completed goal is worth shipping. Instead of thinking of useful subsets that can be delivered in increments to gain feedback toward the ultimate goal.

## Minimum Viable Product

A minimum viable product is the minimal thing that you can do to test a value hypothesis and gain learning and understanding. You might say it is the cheapest thing you can do to prove a hypothesis.

at the end of the learning do i pivot or persevere .

![Image.png](/assets/images/Image%20(7).png)

what they wanted vs what they desired.

failure leads to understanding

# Test Driven Development tdd

“If it's worth building, it's worth testing. If it's not worth testing, why are you wasting your time working on it?” - scott ambler

writing test cases is critical to making sure your code works as intended.

you describe how you want the code to be and then you write the code that does that hhahahaha

super important when thinnking about api design. code is of no use if no one can call it 🙂

![Image.png](/assets/images/Image%20(8).png)

why is this a part of dev ops

So why is TDD important to DevOps? First and foremost, it saves time when developing. As you add new features to the code or changes to existing features (right?), the test cases will quickly let you know if something broke. It allows you to code faster because you are more confident. You don't have to worry if a change you just made broke something. When you refactor code, you can move much faster because you know the test cases will catch any changes in behavior. TDD ensures that the code is working as you expected. If you write the test cases first to define the behavior you want, you will know that you have achieved that behavior when the tests pass. It also means that future changes don’t break the code. Failing test cases will instantly alert you that someone has introduced something that broke the code. Finally, and most importantly, in order to create a DevOps pipeline (a CI/CD pipeline), all tests must be automated unless you want to push bugs to production faster.

# Behavior Driven Development bdd

focus on behaviour of the system as seen from outside in.

thinking outside in… only build what has business value

tdd is inside out - bdd is outside in (high level)

bdd is ensuring the right thing, explore the prblem domain. document the behaviour that the team wants

Gherkin (language) the original name was cucumber

   given   context

   when.   some event happens

   then.     some testable outcome

   and.     is used for continuation

u**ser stories.**

Notice that it uses the "As a," "I need," "So that" syntax; we use this in writing our **user stories.**

![Image.png](/assets/images/Image%20(9).png)

![Image.png](/assets/images/Image%20(10).png)

[Gherkin Reference - Cucumber Documentation](https://cucumber.io/docs/gherkin/reference/)

```other
Feature: Guess the word

  # The first example has two steps
  Scenario: Maker starts a game
    When the Maker starts a game
    Then the Maker waits for a Breaker to join

  # The second example has three steps
  Scenario: Breaker joins a game
    Given the Maker has started a game with the word "silky"
    When the Breaker joins the Maker's game
    Then the Breaker must guess a word with 5 characters
```

# Cloud Native Microservices

the twelve factor app

stateless microservices

each service maintains its own state

resilliance throughhorizontal scaling

instances scaled as needed.

continuous delivery.

"…the microservice architectural style is an approach to developing a single application as a suite of small services, each running in its own process..." These are not just threads. These are full processes running independently, "...and communicating with lightweight mechanisms, often an HTTP resource." We now use REST APIs as these lightweight mechanisms. "These services are built around business capabilities and independently deployable by fully automated deployment machinery."  - - - - Martin Fowler and James Lewis

![Richardson-microservices-part1-2_microservices-architecture.png](/assets/images/Richardson-microservices-part1-2_microservices-architecture.png)

[Introduction to Microservices | NGINX](https://www.nginx.com/blog/introduction-to-microservices/)

![Image.png](/assets/images/Image%20(11).png)

In this video, you learned Cloud native architecture is a collection of independently deployable microservices. Stateless microservices each maintain their own state in a separate database or persistent object-store. Microservices are loosely coupled services, designed for scalability and communicate with APIs.

# Designing for Failure

mean time to recovery is the most important metric

retry patter. try, fail wait 1 sec. try fail wait 2 sec try fail wait 4 sec etc etc untill you give up 🙂

circuit breaked pattern - used to avoid cascading failres.. have alternate paths.

![Image.png](/assets/images/Image%20(12).png)

bulkhead pattern

![Image.png](/assets/images/Image%20(13).png)

chaos engineering( monkey testing)

deliberately kill services and see what happens lol. netflix has a tool for this.

Developers need to build in resilience to be able to recover quickly

# Summary and Highlights

Congratulations! You have completed this lesson. At this point in the course, you know:

- Social coding is coding as a community and public repositories and pair programming result in higher code quality.
- Working in small batches reduces waste and means quickly delivering something useful to the customer.
- Minimum viable product is as much about delivery as it is about building what the customer really desires.
- Test driven development is writing the test for the code you wish you had, then writing the code to make the test pass. It allows you to develop faster and with more confidence.
- Behavior driven development focuses on the behavior of the system from the outside in. It looks at the system as a consumer of it.
- Behavior driven development improves communication by using an approachable syntax that developers and stakeholders can understand.
- Microservices are built around business capabilities and are independently deployable by fully automated deployment machinery.
- Cloud native architecture enables independently deployable microservices that take advantage of horizontal scaling and result in more resilient services.
- Failure is inevitable, so we design for failure rather than trying to avoid failure.
- It is important to embrace failure and quickly recover when failures happen.

# week 3 working devops

# Taylorism and Working in Silos

culture of teaming and collaboration

agile development

automate relentlessly

push smaller releases

taylorism (fred winslow taylor) - large scale manufacturing (c and c management) (siloism)

working in dev ops you must move awa from command and control

# Software Engineering vs. Civil Engineering

project management is not really for software engineering.

project to be completed and then move on.. but software is a continuously developing thing. software stack changes, packages updated, new features,

the project model is flawed when it comes to software denelopmemnt.. rather treat it as product developement

key here is **end to end ownership**

# Required DevOps Behaviors

traditional ops vs devops

![Image.png](/assets/images/Image%20(14).png)

leverage IaC

Devs want innovation, ops want stability this is known as

the wall of confusion

![worked-in-dev.jpeg](/assets/images/worked-in-dev.jpeg)

![Image.png](/assets/images/Image%20(15).png)

# Infrastructure as Code

**configuration management systems:** These are tools like Ansible, Puppet, and Chef

**iac:** docker kubernetes Vagrant Terraform

The reason this is so important is because server drift is a major source of failure. Over time, servers get updated for various reasons, and not always by the same people. This causes them to drift from their original configuration.

parallel infrastructure is a product of iac

never make changes to a running container

Ephemeral infrastructure can be used and then discarded. Servers are built on demand, via automation. Rather than patching a running container, immutable delivery is making changes to thecontainer image, then redeploying a new container.

# Continuous Integration

Continuous Integration (CI) is the process of continuously building, testing, and integrating every developer change into the master branch after a set of tests have passed. The result is potentially deployable code. Continuous Delivery (CD) is a series of practices designed to ensure that code can be rapidly and safely deployed to production by delivering every change to a production-like environment. Notice that I said “production-like.” It doesn’t have to be deployed into production and, in fact, many people reserve the term “Continuous Deployment” for when you are deploying continuously to production.

![Image.png](/assets/images/Image%20(16).png)

Speaking of pull requests, every pull request should be built and tested.

master branch should always be deployable

# Continuous Delivery

5 key principles

master branch should always be deployable - - - build and test every change (CI)

CD is more about the piperline and the automation.

**deliver every change to the production like environment!!! - - - its all about a produiction llike env and not necessarily the production environment**

![Image.png](/assets/images/Image%20(17).png)

![Image.png](/assets/images/Image%20(18).png)

![Image.png](/assets/images/Image%20(19).png)

continuousl deplopyment should be called continuous release (CR)

how do yo reducde the risk of all this automation . . . . deploy more and not less.

feature flag (decouple deployment and activation)

canary testing aka zero downtime deployment

# Summary and Highlights

Congratulations! You have completed this lesson. At this point in the course, you know:

- Taylorism was designed for factory work and software development is bespoke, that is, more like craftwork, and that working in silos leads to mistakes and bottlenecks.
- Team ownership and stable teams make software development more like product development rather than project management.
- Developers want innovation, while Operations want stability.
- Required DevOps behaviors include shared ownership, collaboration, embracing change, and data-driven responses.
- Infrastructure as Code is describing infrastructure in a textual executable format.
- Ephemeral infrastructure can be used and then discarded because servers are built on demand, via automation, using Infrastructure as Code techniques.
- Continuous Integration is building, testing, and integrating every developer change into the master branch after tests have passed.
- The benefits of Continuous Integration include faster reaction time, moving faster, and reducing the risk in integrating code.
- Continuous Delivery ensures that code can be rapidly and safely deployed to production by delivering every change to a production-like environment.
- The five principles of Continuous Delivery have to do with quality, working in small batches, automation, continuous improvement, and shared responsibility.

# week 4 Organizational Impact of DevOps

# Organizational Impact of DevOps

first become agile:

1. small teams
2. dedicated teams
3. cross functional
4. self organizing teams

Conways law: orgs follow their communication structure

![Image.png](/assets/images/Image%20(20).png)

devops teams examples

![Image.png](/assets/images/Image%20(21).png)

aloign your teams with the business, give them autonomy 5 to 7 engineers and no more than 10

give end to end responsibility

give teams long term missions.

# There is No DevOps Team

![Image.png](/assets/images/Image%20(22).png)

first 4 are shitty

last one is good.. devops works against silos.

just as no one forms an agile team

following lean and agile principles

# Everyone is Responsible for Success

bad behaviour arises when you abstract people away from their consequences

make developers responsible for their code

deal with team mates instead of ticket que

“you build it you run it”

In this video, you learned that actions without consequences can lead to apathy. Allowing teams to feel the effect of their actions fosters empathy, resulting in higher-quality work. Your organizational DevOps objective should be to attain a shared mindset and empower everyone to deliver customer value.

# Summary and Highlights

Congratulations! You have completed this lesson. At this point in the course, you know:

- Organizations need to have small, dedicated, cross-functional, self-organizing teams to successfully implement DevOps.
- Conway’s Law implies that a company’s design results are a direct reflection of the company’s communication structure.
- Instead of the traditional structure organized around technology, successful DevOps teams should be organized around business domains. Each team should have its own mission that aligns with a business domain.
- DevOps is a mindset that the whole organization adopts.
- DevOps solves problems caused by siloed teams.
- DevOps is the practice of development and operations engineers working together during the entire software lifecycle, following lean and Agile principles that allow them to deliver high-quality results.
- Actions without consequences can lead to apathy.
- Allowing teams to feel the effect of their actions fosters empathy, resulting in higher-quality work.
- The organizational objective of DevOps is to attain a shared mindset and empower everyone to deliver customer value

jez humble continuous delivery

# measuring devops

## Rewarding for “A” while hoping for “B”

you cannot get b if you are measuring b

breh, you get what you measure

**Measure what matters**

social - who is using your code, and whos code are you using

1. get a baseline
2. choose a goal and work towards it.#

mean time to failure to mean time to recovery 🙂 mttf → mttr

new way of thinking about availibility 🙂

# Vanity metrics vs. actionable metrics

good example of vanity metrics is “website hits per day”

actionable metrics tell us about the users

   ab split testing -

![Image.png](/assets/images/Image%20(23).png)

now you have a cause and effect:

reduce time to market for new feutures - eric ries lean startup

increase overall availability

reduce time to deployment

defects detected before production

performance feedback -

nicole forgren - actionable metrics 2017 tools wont fix your broken devops

1. mean lead time - from ask for feature to feature in hands
2. release frequency
3. change failure rate
4. mean time to recovery

# How to Measure Your Culture

measuring team culture would be hard

dr. nicole forsgren

![Image.png](/assets/images/Image%20(24).png)

# Comparison of DevOps to Site Reliability Engineering

SRE is not DEVOPS but they can be used together

SRE are there to also automate.. but SRE teams are working in SILOS

main thing is really that SRES have silos

![Image.png](/assets/images/Image%20(25).png)

both seek to make operations visible

both require a blameless culture 🙂

the objective of both are the same deploy faster and more reliable

SRE maintains the infrastructure deploy the cloud

devops uses the infrastructures  consume the cloud

[How to make your days better with DevOps | Nicole Forsgren | The DEVOPS Conference 2022](https://www.youtube.com/watch?v=Ki7F6vg0KkE)

# Summary and Highlights

Congratulations! You have completed this lesson. At this point in the course, you know:

- Measure and reward what you want to improve.
- People seek information on what is rewarded and then seek to do that.
- Measuring social metrics leads to improved teamwork and measuring DevOps metrics allows you to see the progression toward your goals.
- If you want people to be social, then measure them being social.
- DevOps changes the objective of problem resolution from failure prevention to failure recovery.
- Vanity metrics may be appealing at first but offer limited actionable insights.
- Actionable metrics provide meaningful ways to measure your processes and take action toward goals.
- DevOps actionable metrics include mean lead time, release frequency, change failure rate, and mean time to recovery.
- You can rate statements developed by Dr. Nicole Forsgren to measure your team’s culture, including statements about information, failures, collaboration, and new ideas.
- Mean lead time is the measure of how long it takes for an idea to get to production.
- Change failure rate is the rate of failure from pushing new releases out.
- Mean time to recovery is how long it takes to recover from a failure.
- Failures are learning opportunities that should not be punished.
- Dr. Nicole Forsgren developed cultural statements for measuring team culture.