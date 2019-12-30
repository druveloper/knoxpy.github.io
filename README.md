# KnoxPy website :computer: :snake:

This repository contains the KnoxPy website. KnoxPy is a Python users group in Knoxville, TN. Visit the website at [https://knoxpy.org](). The site is built with [Jekyll](https://jekyllrb.com) and hosted with [GitHub Pages](https://pages.github.com).

## Installation and usage

The site is built with Jekyll using the GitHub Pages gem. Bundler is used for the Ruby environment.

Install Bundler per the instructions at [bundler.io](https://bundler.io) such as:

```bash
$ gem install bundler
```

Next, create a GitHub Pages Gemfile by following the instructions at [github.com/github/pages-gem](https://github.com/github/pages-gem):

```bash
source 'https://rubygems.org'
gem 'github-pages', group: :jekyll_plugins
```

Create the Ruby environment for the project:

```bash
$ bundle install
```

Run the Jekyll server as follows:

```bash
$ bundle exec jekyll serve
```

To update Bundler and the GitHub Pages gem:

```bash
# Update the Ruby Bundler gem
$ gem update bundler

# Update the GitHub Pages gem
$ bundle update github-pages
```

## Submit a talk

Anyone from beginners to experienced Python programmers are welcome to give a presentation, lead a discussion, or demo some code. Presentations are very informal and typically last anywhere from 15 minutes to an hour. However, we have the space reserved for two hours if you need more time.

Upcoming events and past events are posted to the website as Markdown files located in the `_posts` folder. The name of the Markdown file must begin with the date of the event and two to three words describing the event. For example, a post describing an upcoming presentation would have a file name such as `2020-05-07-awesome-python.md`. The date format is year-month-day.

An example of the contents of the Markdown file is given below. Or see the existing files in the `_posts` folder for more examples. Notice that the front matter of the file must contain the title, time, and address of the event followed by a description of the event.

```markdown
---
title: My KnoxPy presentation
time: 6:30-8:30pm
address: Technology Cooperative, 127 West Jackson Ave, Unit 103, Knoxville, TN
---

This is a description of my awesome talk, discussion, or demo for KnoxPy.
Since this is Markdown, all the typical Markdown syntax is supported. Can't
wait to give a presentation!
```

If you would like to give a presentation or lead a discussion/demo for an upcoming meeting, follow the instructions given below to submit your talk.

1. Clone this repository
2. Add a Markdown file to the `_posts` directory which contains the title, time, address, and description of your talk
3. Use the template shown above for your Markdown file
4. Commit and push your changes to GitHub
5. Create a Pull Request to submit your talk to the KnoxPy website

## Follow us

:bird: **[Twitter](https://twitter.com/knoxpytn)**

:email: **[Newsletter](https://tinyletter.com/knoxpy)**
