# Gender reveal puzzle website

## Introduction

This website was meant to share the gender of our expected baby with friends and family, with a nod to American gender reveal parties. 



## Inspiration

We wanted to reveal the gender of our baby in a funny/puzzly way, while remaining non-programmer friendly.

This project is a fork from [this more complex baby reveal puzzle](https://github.com/evilbotnet/babyreveal), go and check there if you're looking for something more challenging or if your friends and family read hex-encoded ;)


## SPOILER

Below is a list of steps to get to the gender. 

1. The page starts with a 'coming soon' message and confetti in a random color (pink or blue)
2. 5 seconds in, a refresh button appears. Clicking it switches the color.
3. After 5 times clicking the refresh button, a 'And now for real'-button appear.
4. this redirects you to the gender.html page, where a wheel reveals text that. We configured it to display "It's a [X]" where X is a morse encoded word.
5. The morse encoded word was 'strakur', which is (at least according to Google Translate) Icelandic for 'boy'.


## How to run

Simply serve all files statically (we used an S3 bucket + cloudfront).