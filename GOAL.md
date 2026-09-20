# CLAUDE.md

## Project Goal

This is a personal portfolio website designed to show who I am, what I can build, and how I think.

The site should feel personal, technically competent, memorable, and polished.

It should not feel like:

* A generic SaaS landing page
* A corporate template
* A resume converted directly into HTML
* A portfolio generated from a common starter theme
* A page filled with meaningless cards and buzzwords

The website should make a visitor understand my personality and technical ability quickly.

## Core Priorities

When making design decisions, prioritize:

1. Personality
2. Technical credibility
3. Readability
4. Strong visual identity
5. Simplicity
6. Performance

The site should feel like it belongs to one specific person, not like it could belong to any software engineer.

## Tech Stack

* Use plain HTML and CSS only.
* Do not introduce a framework.
* Do not introduce a build step.
* Do not add JavaScript unless I explicitly ask for it.
* Ask before adding any dependency, package, external library, or new file type.

## File Structure

Keep the core website simple.

```text
/
├── index.html
└── style.css
```

* Keep `index.html` at the project root.
* Keep `style.css` at the project root.
* Use correct relative paths.
* Do not create unnecessary nested folders.
* Do not rename or relocate existing files unless I ask.

Use:

```html
<link rel="stylesheet" href="style.css">
```

Do not invent paths such as:

```text
styles/style.css
src/style.css
never/style.css
```

unless that structure already exists or I explicitly request it.

## Design Philosophy

The website should feel handcrafted.

Prefer strong composition over decoration.

Use:

* Strong typography
* Distinctive spacing
* Clear hierarchy
* Interesting section composition
* Purposeful asymmetry where appropriate
* Subtle borders
* Restrained shadows
* Selective accent colors
* Good whitespace
* Small CSS-only hover and focus interactions

Avoid:

* Generic card grids everywhere
* Excessive gradients
* Glassmorphism
* Giant pill-shaped UI elements
* Floating blobs
* Random glow effects
* Overused startup aesthetics
* Excessive rounded corners
* Fake terminal interfaces unless they genuinely fit the content
* Decorative code snippets that communicate nothing
* Tech buzzwords used as visual filler

The site should look modern without chasing every current design trend.

## Personal Identity

The site should communicate that I am a computer scientist and builder, not just someone listing technologies.

Projects should be presented around:

* What I built
* Why I built it
* What problem it solved
* What was technically difficult
* What I personally contributed
* What I learned
* The technologies involved

Prioritize evidence over claims.

For example:

Bad:

```text
Experienced software engineer passionate about innovation.
```

Better:

```text
Built autonomous drone navigation software using ROS 2 and PX4.
```

Whenever possible, show capability through concrete work rather than adjectives.

## Homepage

The top of the site should quickly establish:

* My name
* What I do
* What kind of problems I like working on
* A strong visual or textual identity
* A direct path to my best projects

The hero section should not contain a giant paragraph.

Keep the introduction short and confident.

The page should encourage visitors to explore rather than immediately dumping my entire resume onto the screen.

## Projects

Projects are one of the most important parts of the website.

Treat them as case studies rather than simple cards.

For important projects, include information such as:

* Project name
* Short description
* Technologies
* My role
* Interesting technical challenge
* Result or outcome

Major projects should receive more visual space than minor projects.

Do not force every project into identical boxes.

Use layout hierarchy to communicate which work matters most.

## About Section

The About section should sound like a person.

It may include:

* What I enjoy building
* Areas of computer science I care about
* My approach to engineering
* Current interests
* A small amount of personality outside of programming

Avoid generic phrases such as:

```text
I am a passionate software developer who loves solving problems.
```

Prefer specific information.

The goal is for someone to finish the section feeling like they actually know something about me.

## Skills

Do not create enormous icon walls.

Skills should support the projects rather than replace them.

Prefer grouped categories such as:

```text
Languages
Python
C#
C++
Java
SQL

Systems / Tools
ROS 2
PX4
Unity
Git

Machine Learning
scikit-learn
XGBoost
OpenCV
```

Keep skill lists readable and selective.

Do not use fake proficiency bars or percentages.

## Resume

The website may summarize relevant experience, education, and technical background.

Do not recreate the entire resume visually unless requested.

The website should complement the resume rather than duplicate it.

## Visual Personality

The site may have a slightly technical or experimental visual identity, but it should remain professional.

Good inspiration may come from:

* Developer tools
* Engineering documentation
* Technical diagrams
* IDE interfaces
* Minimalist editorial design
* Game UI
* Research interfaces

Use these influences subtly.

Do not turn the entire website into a fake operating system, terminal, or IDE unless I specifically request that direction.

## Writing Style

Website copy should be concise, confident, and specific.

Avoid corporate language.

Avoid phrases such as:

* Innovative solutions
* Cutting-edge technology
* Passionate developer
* Results-driven
* Dynamic professional
* Leveraging technology
* Transforming ideas into reality

Prefer plain language describing actual work.

## Responsive Design

The website must work well on desktop and mobile.

* Avoid fixed widths that cause horizontal scrolling.
* Use responsive layouts.
* Keep text readable on narrow screens.
* Collapse complex layouts gracefully.
* Add media queries only when needed.
* Preserve hierarchy on mobile rather than simply stacking everything without thought.

## Accessibility

Use basic accessibility best practices by default.

* Use semantic HTML.
* Maintain good contrast.
* Preserve visible keyboard focus states.
* Use meaningful alt text.
* Maintain proper heading hierarchy.
* Associate labels with controls.
* Do not rely entirely on color to communicate information.

## Implementation Rules

Before editing:

1. Inspect the existing structure.
2. Understand the current design language.
3. Preserve working patterns unless the task requires changing them.
4. Make the smallest reasonable set of changes.

When editing:

* Keep HTML semantic.
* Keep CSS understandable.
* Prefer reusable classes.
* Avoid unnecessary abstraction.
* Avoid inline styles.
* Avoid `!important`.
* Do not rewrite working sections without a reason.
* Do not add filler content simply to make the page appear larger.

## Protected Files

Do not edit:

```text
DECISIONS.md
verification/
```

Everything inside `verification/` is mine to write and maintain.

Do not modify, regenerate, format, rename, or clean up those files unless I explicitly tell you to.

## Scope Control

Ask before:

* Adding JavaScript
* Adding a dependency
* Adding a framework
* Adding a build tool
* Adding a new file type
* Changing the directory structure
* Adding external UI libraries
* Adding analytics
* Adding external fonts
* Adding third-party embeds

If something can be accomplished cleanly using existing HTML and CSS, prefer that approach.

When uncertain, favor simplicity and personality over complexity.
