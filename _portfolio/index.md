---
classes: wide
header:
  image: /assets/images/niubanner2.png
permalink: /portfolio/index.html
---

# Blog Posts

<details markdown="1"><summary>1. Discovering Open Source</summary>

### What is open source?
Open source refers to a product, usually software, where the source code is made publically available for inspection, modification, and redistribution.

Platforms like GitHub make it possible for people all over the world, regardless of location or timezone, to work on the same software project. 

### What surprised me?
As a computer science major, I was already familiar with open source software prior to this class-- its definition, community-driven development,
and tools such as Git and Markdown. When I explored more deeply into the topic, I learned more about the strategic
reasoning behind big tech companies using open source.

React is an open source JavaScript library for building user interfaces. By releasing React as open source, Facebook was able to secure React's place
as the standard for front-end applications. As React got more and more popular, developers began to learn it at an increased pace.
This meant that Facebook could hire new developers already familiar with React, so the company did not have to spend money on training
these new hires.

### Which well-known companies and projects use open source?
1. Google
   - TensorFlow - a widely used open-source machine learning library.
   - Chromium – the foundation for Google Chrome.

2. Microsoft
   - Visual Studio Code - a free, open source code editor
   - TypeScript - another open source prohramming language

3. Meta (formerly Facebook)
   - React - part of the example above
   - Also contributes to PyTorch, a popular deep learning framework

### Why does that matter?
It matters which companies use open source for multiple reasons.
1. Innovation Ability
   - Making a project open source opens it to contributions from a large population of developers worldwide. Collaboration on this scale drives much quicker innovation and problem-solving. 
2. Transparency
   - Since the source code is public, users are able to easily inspect it for data privacy practices and security flaws.
3. Sustainability
   - Having open source code creates a community around the company by encouraging good relationships with developers. Because of this community, the software is kept alive and relevant, even without input from the original maintainers.
</details>

<details markdown="1"><summary>2. GitHub and Markdown</summary>

### What I learned about Markdown and Git and how they help me contribute to open source and improve professionally:
This week, I explored the "Intro to Git" and "Intro to GitHub" units of Microsoft's Learning Labs. While I was already familiar with both of these topics, revisiting the basics helped remind me of best practices. I also refreshed my knowledge on branching, committing, and creating and merging pull requests.

These topics will help me improve professionally by allowing me to: 
- collaborate with people around the world, regardless of timezone
- showcase GitHub activity to potential employers

### Have you used them before?
Yes, I have used both GitHub and Markdown extensively in the past. My internship at [Ticomix](https://www.ticomix.com/) used Markdown wikis to track the technical specifications of each project, alongside other things.

### What surprised you about Markdown or Git?
I was surprised by the "rebasing" feature I learned about in the [GitGud](https://www.gitmastery.me/) activity. I had never encountered this feature before and it was interesting to learn the differences between merging and rebasing. 

| Rebasing          | Merging           |
|-------------------|-------------------|
| Commits by merging each commit into the main brain one by one    | Commits by combining all changes into one commit and then merging   |
| Merge conflicts may crop up for each individual commit    | Merge conflicts are presented and resolved at the same time     |
| Effective when concerning private projects to help organize history    | Helpful in collaborative projects so that the many commits do not disturb others  |

</details>

<details markdown="1">
  <summary>3. Exploring a Repository</summary>

## Selected Repository: Calendarium

### How I Selected the Repository: 

I chose to explore the Calendarium repository because it is an open source resource that I already utilize. Getting a peek behind the scenes of such a utility is 
an opportunity I couldn't pass up.

Obsidian is a powerful knowledge management tool that allows users to create, link, and organize notes in a flexible, non-linear way. It operates on a local 
markdown-based vault system, enabling users to build a network of interconnected notes.

<img width="267" height="257" alt="Obsidian Logo" src="https://github.com/user-attachments/assets/d3a904d5-0559-413b-b7bd-62ac3dd55290" />

[Calendarium](https://github.com/javalent/calendarium) is a calendar and scheduling tool designed to help Obsidian users manage time, track events, and organize 
schedules. It provides features like customizable views, event creation, reminders, and recurring tasks.

### Structure: 

The Calendarium repository is structured under the assumption that you are already familiar with the Git flow. With a minimal README and Contributing Guide, but an 
extensive Code of Conduct, it seems to be a close-knit group of maintainers who deal with a lot of bug reports. They expect to deal with a lot of users, but do not
make it easy on first-timers who would want to contribute.

Within their README, they do have a link to a documentation site that helps non-technical users set up the Calendarium extension on their local machines. 

### Community: 

The community on the Calendarium repository is one of their best traits. While most of the contributions are done by the same 3 people, they articulate 
themselves well and still document enough that an outsider could follow their decision making process. There is a healthy amount of recent activity and a 
friendly overall tone to any responses to Issues, whether they are from maintainers or from other users.

### Contribution Process: 

In order to contribute to Calendarium, one must follow three simple steps:
1. Fork the repository
2. Make any necessary changes
3. Submit a Pull Request

</details>

<details markdown="1">
  <summary>4. Reveal.js</summary>
  
### After exploring Reveal.js, describe:

#### 1. How it's Structured
The Reveal.js repository is organized into clear folders, making it easy to navigate. It holds the key files
such as a README.md, a contributing guide, and a license file.

It keeps the plugins, the CSS, and the code well-organized in separate folders, making it easy for 
contributors to work on specific parts of the project.

#### 2. What it's For
Reveal.js is an open source framework targeted towards creating HTML-based presentations that are both functional and aesthetically pleasing.

#### 3. What I Found Interesting About the Way the Project is Documented and Maintained
One thing I found interesting about the way the project is documented is how they implement community
boundaries -- they expect all issues to be bug reports and bug reports only. The Discussions board should
be reserved for questions on how to use the software.

### Could you imagine yourself contributing to this? Why or why not?
Reveal.js represents the kind of project that I would love to contribute to -- eventually. The repository
is well-documented, has an active community, and has plenty of range in the existing issues.

However, the challenge I anticipate with working on a project such as Reveal.js is the time I must spend
to familiarize myself with the project's architecture. While I am quite familiar with JavaScipt as a language,
I would need to know a lot more than I currently do about the existing codebase.

</details>

<details markdown="1">
  <summary>5. Ownership, Access, and Innovation: What I Learned About Licensing</summary>

### Reflect on something you learned about open source licenses (e.g., MIT vs GPL, what’s allowed, what’s restricted).
While pursuing my minor of Business Administration at Northern Illinois University, I took the class MGMT 217 (The Legal Environments of Business).
This means that I went into this activity already well-versed in licensing as a concept, but was able to understand more about how it works in practice.

There are three widely used open-source licenses that stand out for comparison: the MIT License, the GNU General Public License (GPL), and the 
Berkeley Software Distribution (BSD) License.

| MIT               | GPL               | BSD               |
|-------------------|-------------------|-------------------|
| Very permissive   | Least permissive   | Permissive    |
| Compatible with other licenses  | Not usually compatible with permissive licenses   |  Compatible with other licenses   |
| Copyright license  | Copyleft license   |  Copyright license   |

### How did the Tetris movie shape your understanding of software ownership and distribution?
The *Tetris* movie showed me a different view on the conversation about open source licensing. It helped highlight
that having ownership over source code isn't enough when it comes to licensing software. It also showed just how
much the entire world is involved in these types of negotiations.

### What surprised or intrigued you about NIU’s approach to IP, patents, and tech transfer?
Mark Hankins mentioned that NIU has an Office of General Counsel, where you can find NIU-specific rules available about the "fair use" clause of 
copyright law.

He also stated that in general, "traditional academic works" are considered the intellectual property of the Professor overseeing the research, whereas 
the software product itself is considered property of the University.

### How do you think licensing empowers or complicates open innovation?
Licensing is a double-edged sword when it comes to innovation. Many licenses, such as the MIT and BSD licenses, help streamline innovation by
removing typical legal barriers. These licenses allow individuals and organizations to use, modify, and redistribute code freely, often without needing to open-source 
their own contributions. This opens the door to projects such as Python, Java, and Angular.

However, more restrictive licenses, such as the GPL license, may discourage companies from open source innovation. These licenses require that open source

</details>

<details markdown="1">
  <summary>6. MLH Global Hack Week</summary>

## My experience participating in MLH Global Hack Week: what I learned, what I contributed, and who I connected with

### What I learned from participating in MLH Global Hack Week
I attended the `Supercharge Your Github Profile` session this week. Here, I learned more about developing
my online portfolio and putting my best digital forward when it comes to first impressions with employers.

I also was able to see the speaker do a pull request in real time and view other coders' GitHub profiles,
which helped give me a standard to hold my profile to.

### What contribution (or challenge) you made
The challenge I completed was the `Star an Open Source Repository` challenge. While many other challenges caught my
eye, such as activating various accounts now available to me, I wanted to wait until I could dedicate the
appropriate amount of time and energy into the available walkthroughs before

### Who you connected with or learned from
I learned from Kari from MLH, who led the aforementioned session I attended. She was passionate and 
helpful and I intend to reach out through LinkedIn in hopes of connecting with her more.

### How this experience shaped your view of open source collaboration
Participating in GHW helped reinforce certain ideas I held about open source collaboration:
 - The Importance of Community
    - The time I spent over the past week meeting new people and seeing them engage in projects really
      cemented how much open source is about connecting with people and collaboration, not just code.
 - Continuous Learning
   - Every livestream I either attended or watched later drove home how people will never be *done*
     learning and how open source innovation helps support this continuous welcome.
 - All are Welcome
   - The speakers all made it very clear: It didn't matter how much or how little experience you have,
     everyone is welcome to contribute when it comes to open source.

</details>

<details markdown="1">
  <summary>7. Non-Code Contributions</summary>

## What Counts as Contribution in Open-Source?

Contributions are any meaningful addition to an open-source repository. This can include:
1. Opening an Issue
2. Completing an Issue
3. Opening, or participating, in a discussion
4. Submitting a Pull Request
5. Adding documentation
6. Testing existing features

## My Thoughts on the Value of of Code and Non-code Contributions:

Code contributions are important to the creation and upkeep of software features. Without code 
contributions, an open-source project would likely not exist. Code contributions keep the project
functional and, hopefully, efficient. 

Non-code contributions are essential to open-source projects reaching a more diverse and larger
population of users. These contributions often help make a project more accessible -- for example,
adding things such as image descriptions for those who might be using screen readers. They also help
maintain a projects community by giving key documentation and translating portions of the documentation
for a more widespread audience.

## How Diagrams Help Clarify Workflows:

Diagrams help clarify workflows by offering a detailed visual alternative to an otherwise occasionally 
confusing text description. 

## Communication and Collaboration:

Maintaining a welcoming environment helps encourage communication and collaboration in open-source 
projects, which is usually the whole reason behind making a community open-source. Reaching a 
greater circle of contributors, coders and non-coders alike, is a great perk -- one that is easy
to lose if you become harsh or otherwise difficult to work with.

## Non-Code Contributions I Found:

Many of the non-code contributions I've found involve testing features and improving the accessibility of 
the project. As I often use a screen reader myself, to help limit my eye's exposure to screen time as much
as possible, I'll be the first to tell you that many projects don't even bother considering those who may 
not be as able to see as the maintainer themselves.

</details>

<details markdown="1">
  <summary>8. Retrospective</summary>
  To Be Completed
</details>
