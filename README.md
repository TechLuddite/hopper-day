# Hopper Day

**August 14. Talk to your computer. Make something yours.**

An open-source project celebrating what people can make when they can talk to their computers. Grace Hopper helped make programming more accessible. Hopper Day is a chance to carry that work forward and give it your own meaning.

- [Live page](https://techluddite.github.io/hopper-day/)
- [MIT license](LICENSE): fork it, contribute, make it yours.
- [Research notes](research.md): sources, dates, definitions, and calculations.
- [Research audit](research-audit.md): what changed and which claims remain unresolved.

## Why August 14

[Omarchy 4.0 ("Quattro") shipped on August 14, 2026](https://github.com/omacom/omarchy/releases/tag/v4.0.0). We're choosing that anniversary as an occasion to celebrate working through ideas with a computer in plain language.

Hopper and her team helped develop early compilers and FLOW-MATIC, which influenced COBOL. For me, working with an agent on an old laptop feels like another step along that path. The connection is personal; this project doesn't speak for Hopper or the Omarchy team.

## Why old computers matter

PIRG estimated that up to 400 million PCs could not upgrade to Windows 11, representing up to 1.6 billion pounds of potential e-waste. That is an estimate of affected hardware, not a tally of discarded machines. [PIRG's report](https://pirg.org/edfund/resources/electronic-waste-graveyard/).

The Windows 10 deadline drove replacement demand before regular support ended in October 2025. Microsoft's later consumer extension buys more time, but doesn't undo fleet decisions already made. Business and education ESU programs have separate terms. The [research timeline](research.md#the-extension-came-after-replacement-pressure) records the sources and what we can establish about the refresh wave.

A useful computer deserves another job. Revisit some research, catalog a collection, organize family recipes, or build a tool you've wanted for years. Check hardware compatibility and the setup requirements of whichever Linux distribution and agent you choose.

## The investment question

Goldman Sachs forecasts about $1 trillion in global AI-related capital investment for 2026. We compare that with selected, traceable US public budgets, including animal welfare, ocean exploration, arts funding, and cancer research. Each figure has a year and a defined scope in the [research notes](research.md#us-comparisons).

These comparisons show scale. They don't establish a direct transfer of money from public programs into AI. I want to see people working on those problems have more access to useful computing tools, and more say in what gets built.

## Make your own Hopper Day

I enjoy the mechanics of making things work. I also love seeing the visuals other people come up with, with or without digital aids.

Fork this project and show us what Hopper Day means to you. Restyle it, translate it, tell your own story, or add something we haven't thought of. Your version can have its own point of view. [Share a link in an issue](https://github.com/TechLuddite/hopper-day/issues) so we can see it.

PRs are welcome too. Help improve this page, correct a source, add a translation, or contribute a personal example of what you'd like to do with your computer.

## Work on the page

This repo is small: one static HTML page with inline CSS and a little JavaScript to cycle through example requests. There are no build tools or package dependencies. Fonts load from Google Fonts, with system fonts as a fallback.

```bash
git clone https://github.com/TechLuddite/hopper-day.git
cd hopper-day
# Open index.html in your browser to preview your edits.
```

The examples change every eight seconds and have a pause button. With reduced motion enabled, they start paused. Without JavaScript, the first example remains readable.

Send a PR to contribute here, or publish your own fork with GitHub Pages. Keep it easy to read, easy to adapt, and honest about what the tools can do.
