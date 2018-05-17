Nothing here
===
Yet another creative usage of github pages?

### Updates
Check this out: https://www.netlify.com/ , which claims to offer modern automated web developing experience, already used by element-ui.

### Motivation

Occasionally, I need to write demos of patched element-ui on jsfiddle. The
problem is there is no convenient way to insert patched libraries:

* inline-script -> extremely inelegant (不清真)
* free js hosting -> no HTTPS, absolutely useless
* third-party cdn/s3/oss -> extra $$$

Previously, I hosted patched files on my own s3/oss servers, which worked well
for three months until the hosting company get DDoS-ed to death.

Then I came up with the github pages idea. It's free, git-managed and
**HTTPS friendly**. 

### How it works

1. set up a repository
2. enable github pages on master
3. commit & push
4. use approperiate url in jsfiddle
