---
title: "Overview of Modern Frontend Technologies and Tooling"
date: 2021-02-10T20:47:16+06:00
draft: true
---

The internet is a network of computers that transfer data between each other
using various protocols such as HTTP and HTTPS for websites, POP/IMAP for
emails, FTP for files and many others. A protocol, without diving into details,
is a set of rules as to how data is to be tranferred.
<!--more-->

## The internet

The internet is a network of computers that transfer data between each other
using various protocols such as HTTP and HTTPS for websites, POP/IMAP for
emails, FTP for files and many others. A protocol, without diving into details,
is a set of rules as to how data is to be tranferred.

A website is an HTML document that your browser (also sometimes called the
client) fetches from a remote computer, usually called the server via the HTTP
or HTTPS protocols. Then your browser interprets the document and displays it in
a human-friendly format.

## HTML

HTML stands for Hyper-Text Markup Language as it is used to express the
structure of a webpage. The basic block of an HTML page is an element or also
called a tag. Each element has a specific meaning and behaviour and should be
used accordingly. Every HTML document has a `<head>` and a `<body>` . The
`<head>` contains all the technical information that is necessary for the
browser to load the page properly and none of it is shown to the user, except
the page title. The actual content of the webpage goes into the `<body>`
element.

The latest universally supported version of the HTML language is HTML5 that came
out in 2008. It introduced such useful tags as `<video>`, `<audio>` and
`<canvas>`. It also includes a bunch of semantic<sup>2</sup> tags, such as
`section`, `article`, `header` and `footer` to name a few. Each tag has a number
of attributes that can and sometimes must be specified in order for them to work
properly.

## CSS

CSS stands for Cascading Style Sheets. CSS is what gives webpages style and
makes UI more pleasant and intuitive. CSS code is written inside a `<style>`
HTML tag but more often the code is extracted into a separate file with the
`.css` extension and referenced in the `<head>`.

There are two basic terms in CSS: a selector and a rule. A selector is a way to
target an HTML element and rules specify the style of the target element.
