---
weight: 100
date: "2023-05-03T22:37:22+01:00"
draft: false
author: "Pedro Martins"
title: "About Page Implementation"
icon: "rocket_launch"
toc: true
description: "A guide to implement the about page"
publishdate: "2023-05-03T22:37:22+01:00"
tags: ["Beginners"]
---


## Introduction
   In this page it is possible to follow a step by step guide that aims to educate the reader on how to make the color picker page in this website.

## Set up
   1. Install Hugo and Go
       
       If you haven’t installed Hugo and Go, you can go see the installation guidelines provided in [Hugo Installation](https://gohugo.io/installation/). If you do already have them installed you can skip this step and go directly to the next one. 
       
       Do not forget the prerequisites. You should need the following command or similar: `choco install hugo-extended` (windows) or `brew install hugo` (mac), for instance. 

       Check the version using: `hugo version`. 

       Check how to install Go ([Go Installation](https://go.dev/dl/)) and proceed with the installation, check that everything is fine at the end: `go version`.

   2. Download Lotus Docs theme
       
       Use the Lotus Docs example project as a template. Start by cloning the repository from [Lotus Docs GitHub Repository](https://github.com/colinwilson/lotusdocs) and changing to the exampleSite folder. There, execute the following command: `hugo server`. You should now see something like Figure 1.

  ```shell
                   | EN  | FR  | DE
-------------------+-----+-----+------
  Pages            |  19 |  14 |  14
  Paginator pages  |   0 |   0 |   0
  Non-page files   |   1 |   1 |   1
  Static files     | 367 | 367 | 367
  Processed images |  18 |   0 |   0
  Aliases          |   1 |   0 |   0
  Cleaned          |   0 |   0 |   0

```
  Your website should be available at http://localhost:1313/

## Implementing the About Page/Your MD Code

```shell
weight: 100
date: "2023-05-03T22:37:22+01:00"
draft: false
author: "Pedro Martins"
title: "About"
icon: "rocket_launch"
toc: true
description: "Discover how we create a user-focused guide to building technical documentation websites."
publishdate: "2023-05-03T22:37:22+01:00"
tags: ["Beginners"]
---

# Welcome to Our Technical Documentation Project

This project is part of our Informatics Engineering course. It gives you practical help to build and manage websites for technical documentation. We use modern web technologies and follow industry best practices to help you learn technical documentation well.

## What We Aim to Do

We are here to help both new and seasoned developers understand how to create documentation websites. Our project includes everything from managing content and designing, to following accessibility standards and working with backend technologies.

## Meet the Team

- **Pedro Martins** from Felgueiras leads the storytelling on this page with clear communication.
- **Ricardo Mascarenhas** handles the "Color-Picking Page" and commutes from Porto on his electric scooter, making sure our site looks great.
- **João Martins** runs our "Deployment Page," using his HTML skills to make our website work well across different platforms.
- **Pedro Simões**, a fan of anime and skilled in backend technologies from Porto, takes care of the "Setup Page" with his strong Java skills.

## How We Build

Using the Hugo framework because it's fast and efficient, our website is designed to be quick, easy to use, and responsive. This makes sure you have a smooth experience using it.

## Our Commitment to Accessibility

We follow the Web Content Accessibility Guidelines (WCAG) to make sure our site is accessible to everyone, no matter their ability. You can see our commitment in every choice we make, from choosing colors to adding interactive elements.

## Accessibility Statement

### Introduction
Our commitment goes beyond just following rules. We want to make a welcoming place online for everyone, especially those with disabilities. We keep working to make access and use better for everyone by using the latest standards and technologies.

### Our Commitment to Accessibility
**Objective:**  
Our main goal is to follow the Web Content Accessibility Guidelines (WCAG) 2.2 Level AA. This makes sure our website is usable by people with all types of abilities and disabilities.

**Accessibility Features:**  
We have added features to make sure everyone can use the site easily:
- **Keyboard Navigation**: You can use our website with a keyboard alone, allowing you to interact without a mouse.
- **Screen Reader Compatibility**: We make sure our content works with screen readers, which help read out text.
- **Adjustable Text Size and Contrast**: You can change text sizes and contrast to make things easier to read.

### Usage Guidance
**Optimal Experience Recommendations:**  
For the best experience, we suggest using the latest tools for accessibility and browsers that support these technologies. If you have any trouble using our site, please contact our support team directly.

### Feedback and Contact
**We Value Your Input:**  
Your feedback is very important to help us make our website better for everyone. Please let us know about any problems you have or suggest improvements:
- **Email**: [1230204@isep.ipp.pt](mailto:1230204@isep.ipp.pt)

- **Phone**: [+351912206445]

### Commitment to Continuous Improvement
We see accessibility as an ongoing goal and always look for new ways to make the site better. Your feedback helps us keep improving and making sure our site meets various needs.

### Legal and Regulatory Compliance
**Legal Adherence:**  
Our website meets all accessibility laws and rules to make sure we go beyond what is required.

### Updates and Modifications
**Regular Updates:**  
We often update our accessibility features and methods to keep up with laws, technology changes, and feedback from users.

## Keeping Performance in Check

We don’t just build; we make sure our site works well. We keep checking and improving it to meet the highest performance standards, making sure it works fast and smoothly for every user.

```