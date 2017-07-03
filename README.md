Nothing here
===
Yet another creative usage of github pages?


### Motivation

Occasionally, I need to write demos of patched element-ui on jsfiddle. The
problem is there is no convenient way to insert patched libraries into jsfiddle:

* inline-script -> extremely inelegant (不清真)
* free js hosting -> no HTTPS, useless in jsfiddle (and the future of Internet)
* third-party https cdn/s3/oss -> extra cost

Previously, I hosted patched files on my own s3/oss servers, which worked well
for three months until the hosting company went bust. (Though I perfer the term:
**got DDoS-ed to shut / forced to close**)

Then I came up with the idea of using github pages. It's free, git-managed and
**HTTPS friendly**. Since these files are used for collaboration on github, they
costs little storage and bandwidth. Hopefully it does not branch ToS.


### How it works

1. set up a repository
2. enable github pages on master
3. commit & push
4. use approperiate url in jsfiddle

