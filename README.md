[![Netlify Status](https://api.netlify.com/api/v1/badges/93a0d9b8-f334-4371-8992-427dde652a5e/deploy-status)](https://app.netlify.com/sites/smirnov/deploys)
# CV Website

This repo is for personal CV.
Pure HTML, no fancy tech stack, just something that works for sure (and fast!).
I use Netlify for hosting purposes and it's continuous deployment features (by connecting with my Github repo).
The initial version which required a tiny style fix for my needs is bootstrapped with [jsonresume](https://jsonresume.org/) with the theme "Stackoverflow".

In order to generate a CV with same styles which I use you can define it with CLI:

```
resume export resume.html --theme stackoverflow
```
If you want to have your CV with same styling in pdf use: 

```
resume export resume.pdf --theme stackoverflow
```
If you don't want to memorize how the theme is called and you know exactly the one you want to stick with you can add this to your source resume.json file:
```
 "meta": { "theme": "stackoverflow" }
```
