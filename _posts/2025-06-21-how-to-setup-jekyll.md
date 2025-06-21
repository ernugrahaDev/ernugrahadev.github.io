---
title: "How to setup Jekyll"
layout: single
date: 2025-06-21
author: ernugraha
categories: [tutorial, linux, web]
tags: [debian, linux, software]
---

# This is how you setup Jekyll for making website.

Tested on Debian 12 (Bookworm Linux 6.1.0-37-amd64)

## Prerequisites

Before we begin, make sure you have the following installed:

-   Git

-   Ruby & RubyGems

-   Bundler (Ruby gem)

-   Jekyll (Ruby gem)

-  A GitHub account

```bash
sudo apt update
sudo apt install ruby-full build-essential zlib1g-dev git
echo '# Install Ruby Gems to ~/.gem' >> ~/.bashrc
echo 'export GEM_HOME="$HOME/gems"' >> ~/.bashrc
echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc
gem install bundler jekyll
```