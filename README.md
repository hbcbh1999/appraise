# Appraise -- Visual approval testing

This is a (research) project aimed at prototyping a tool for visual approval testing. The goals of the project are to build a tool that helps developers with the following tasks:

- Review and approve changes to browser components quickly through visual inspection 
- Automate acceptance/regression tests for visual look and feel in a visual language, rather than xUnit style code
- Speed up visual exploratory testing by making it easier to rebuild visual components from example data/configuration
- Build living documentation for API consumers/component users that is easy to maintain
- Publish developer docs with visual examples to github easily (markdown) or as a static site (html)
- Run visual tests quickly/in parallel using AWS Lambda

## Status

too early to use (pre-alpha)


### Tasks

- [x] Choose a markdown rendering system (https://github.com/markdown-it)
- [x] Choose a Node DOM manipulation system (https://github.com/cheeriojs/cheerio)
- [x] Build local screenshots (using Chrome Headless and https://github.com/cyrus-and/chrome-remote-interface)
- [ ] Choose an image comparison system (investigate https://github.com/mapbox/pixelmatch)
- [ ] in-browser fixture execution
- [ ] Retina screen sizing
- [ ] AWS Lambda screenshots 

