## Climate change

### Onboarding with actionable items for climate change

#### Motivation

It can be daunting to learn about climate change and figure what's the best way one can contribute with the skills one has.

New user experience to the entire movement is very unclear and overwhelming. Most of the information is either scary info dump or skeptic pieces. 

Given there is nothing actionable for quite a while and realising what actions one can take is cumbersome, partly-hidden and heavily-debated, most people would drop off before they can figure how they can help.

#### Solution

Ask people about themselves and give them a semi-personalised, 1 step at a time, actionable onboarding.

Make the initial few weeks of their journey into reversing climate change guided, keep giving progressively difficult things to do.

[Sample user bot flow](https://landbot.io/u/H-427314-S9BKE7V242FKEWXP/index.html)

Note: I used a bot builder because it gets the point across quicker, the UI definitely should not be a bot.

Originally thought for: [https://protect.earth](https://protect.earth)

### Social credits to bridge social and economic incentives short term

#### Motivation

Most people can't / aren't going to give a shit about something that will happen 5-10 years from now. We need to bridge rewards for them short term to do the right thing.

#### Solution

Make a social credits system to give short term incentives to people to reduce their environmental footprint.
Use this to create social and economic pressure on govt and industry to improve their impact on climate.

- People earn points based on how far below the national average per capita emission they are.
- Company A sells coffee, it wants to be seen as caring about the environment. They have a marketing budget.
- Company A offers a 10% discount on their coffee for people in exchange of 100 points.


TK: This needs to be fleshed out more.

## Open source

### Pledge instead of upvotes for feature requests
TK

## Dev tools

### Prototyping tool + IDE for designers that generates/manipulates your UI code, integrates with your source control (A visual IDE, Unity for web pages, so to speak)

#### Motivation

During my time at verloop, I'd noticed a few recurring themes in the design process:
- Transition from low fidelity to high fidelity designs would keep presenting previously unidentified usability issues.
- The UI developers shipped would drift from the designer's intent. Even components of the designer and developers would have differences because the fundamental limits of the universe of a prototyping tool and that of a UI framework are different.
- The engineer working on the UI would keep running into constraints of the framework and this would lead to a lot of back and forth between the dev and the desiger.

These problems weren't specific to verloop and even larger companies that have much better efficiency struggle with these issues to some extent.

In an ideal world, the designer should get to make the entire user experience flow and the frontend developer should only need to work on the data + API layer. Right now, the designer works with the contstraints of the tool they are using instead of the UI framework the developer has access to and the developer spends time on manually codifying UI information from a prototyping/design site into the framework.


The export from all famous prototyping tools I've encountered are utterly useless to be actually usable by the frontend engineer directly.

There are also lesser known tools that try to work with a few UI frameworks, but those necessitate starting with a new project and sometimes also have a limit on the components you can use.

There have been attempts in making websites completely code independent, like CMSes and SaaS cmses, but these haven't been flexible enough to penetrate any "serious" use cases.

#### Solution

Make an open source UI prototyping editor based on popular frameworks. Alternatively, add a view tab + UI drag and drop capability in existing editors like VSCode.

Minimum:
- Render real frontend code, no canvas, no images, no gimmicks.
- Must work with as many existing code bases as possible. i.e. Integration with top 5 UI frameworks and top 5 css frameworks.
- Minimum changes to existing projects to get started.
- 2 edit modes. 1 to edit the grid and another for component dropping within the grid.
- Avoid bad UI code. Eg: Minimal `position:absolute` elements and minimal inline styles.
- Save changes back to the UI template code file. Use project's pre-conigured linter.
- Ability to bind events of components with existing JS/TS methods / other html attributes like a regular editor.

Good to have:
- Integration with gitlab, github and bitbucket to raise PRs.
- Ability to make ghost JS/TS methods with notes as comments for developers to implement necessary functionality.

Side benefit: More developers will want to work with the UI. Right now, translating UI from designer prototype to code is sometimes seen as tedious work that most developers do not want to do. Dragging and dropping is much easier than figuring out UI developer code.


### Working variant of telepresence
TK
