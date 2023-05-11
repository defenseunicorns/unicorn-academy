# 2. Initial architecture for Unicorn Academy

Date: 2023-05-09

## Status

Accepted

## Context

Unicorn Academy currently exists only in a few people's heads.  This repo is the start of making it come to life.  Step 0 in enabling that is deciding where Unicorn Academy is going to live.

## Decision

Unicorn Academy will be hosted at https://academy.defenseunicorns.com and will be free to consume.  Unicorn Academy will leverage:

- [Netlify](https://www.netlify.com/) for hosting
- [Docusaurus](https://docusaurus.io/) to author content 

These are both already used in various other projects at Defense Unicorns including the company website.

## Consequences 

Making progress developing Unicorn Academy should not be hindered by fighting with the hosting or authoring tools as there is in house knowledge about how these tools work.

Migrating away from these tools in the future may be difficult if they are eventually deemed unsuitable for any reason.  If that choice is made, it is likely being made across multiple Defense Unicorns products which means there will be multiple brains attacking the same problem. 