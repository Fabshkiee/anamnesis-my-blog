---
title: Anamnesis - A Reminder
date: 2026-06-21T19:49:00.000+08:00
description: I never thought I’d actually set up *a* blog, but here we are. This
  is how I brought a completely different SSG theme over to Hugo—and the moments
  I almost gave up entirely.
draft: false
tags:
  - Summer
  - College
  - Development
  - Life
---
## What made me build this

Lately, I've been feeling pretty dispassionate on life. IDK lang talaga if it's just a really boring staycation sa bahay but I remember I would spend **hours and hours** of my time to game instead of finishing my *Xiao Kai* (Homework from HuaSiong)<span style="font-size: 10px;"><sup> i dont miss you  TnT<sup></span>

I barely spend 30 mins playing these days and just press the exit button. I think i'm just growing up if ganon, hard to believe **AND** accept it tho especially when I think my mental capacity is that of my 18 year old self.

Kaya siguro napa-isip ako this early morning to build up a blog. Not just to pass time or get experience but rather exercise my brain and my soul. I've always been a forgetful person as well. I was always astonished by the events from what I used to do and the things that were happening around me nung highschool when the people who I used to be friends with reminded me TnT. I barely remember anything past-pandemic nor where my fave socks were recently placed<span style="font-size: 10px;"><sup> i swear my just sister lost it<sup></span>

- - -

## My approach on blogs

I thought I would never program a blog myself if there were plenty of platforms where it's easy to setup and most importantly of all free. I began searching muna for existing platforms or see the ones my senior shared on his post if they were sufficient enough for me. I could've written this down hours ago if it weren't for my weakness for **lack of features.**

Some free blogs I found insteresting were:

1. [Bear Blog](https://bearblog.dev)
2. [Write.as](https://write.as)
3. [Pika](https://pika.page)

I would've wrote on Pika if it weren't for the 50 blog limit on the free plan TnT. Regardless, the others really didn't connect to me—and that's when I realized I wanted to customize my own blog. I really didn't wanna look at an interface na hindi ko bet especially if I'm gonna commit a long time of doing this. With that on my mind, I started my research earlier this morning.

- - -

## Tech Stack

One of my favourite parts of being in this industry is system design, system architecture, and discovering new frameworks. I always love that each language and framework has their ups and downs on their fields especially when you've been experiencing so many downs on one thing so when you finally have the opportunity to try the new thing it feels like heaven to not experience those.

After a bit of research this is what I was going to choose:

| **SSGs** | **Language**         |
| -------- | -------------------- |
| 11ty     | Node.js              |
| Astro    | Node.js / TypeScript |
| Hugo     | Go                   |
| Zola     | Rust                 |
| Jekyll   | Ruby                 |

\
I really wanted to go to **Jekyll** due to their longevity and community support but idk shi about ruby and I don't really see myself coding **ruby** in anytime of the future. It felt like no choice between **Eleventy (11ty)** and **Astro** because I had most experience in these languages. I really wanted to try **Zola** because of rust but because of the amazing speeds I heard about **Go**, I went building this site with **Hugo**.\
\
I mean **LOOK** at this:<span style="font-size: 10px;"><sup> Next.js could never<sup></span>

![Hugo_IMG](/images/Hugo_IMG.png "19ms build speed.")

I also chose to go with a CMS (Content Management System) called **Decap**<span style="font-size: 10px;"><sup> i wish I hadn't<sup></span>, Basically a free software that allows you to do CRUD Operations without prior programming skills (Hence why no backend) It allows me to push, edit, and remove markdown files as long as the service is connected with my Github's Personal Access Token. I mean it's good as I learn to navigate it, I just wish more customizations TnT.

- - -

## Choosing a theme (Nightmare Fuel)

This is where the process took the longest. In order to speed up development time and setup. These **SSGs** comes with a lot of free [themes made by the community.](https://themes.gohugo.io) Usually they're built for making blogs such as mine but there are also themes made for portfolio websites with blogs integrated (Useful if you don't wanna design a portfolio site).

I eventually stumbled upon a reddit comment a year ago from a dev called *merox.* Now I really liked the theme of his site.\
\
For reference:

![merox_IMG](/images/merox_IMG.png "merox's blog site")

For me that was the perfect balance of darkness and light with the perfect design of UI/UX for me personally. So naturally I tried to find what he had so I could copy it. The comment I mentioned earlier stated that he used Hugo + a theme called Blowfish (which ofc doesn't look like the theme he had). It's understandable given the comment was a year ago, maybe he changed.\
\
I found that he replied to a comment that he had switched to Jellky + Chirpy Theme. Ah linto, abi ko amo na to. Colors and UI placement were similar so I had thought na he had to heavily customized the theme to tailor to his current web design. I was happy pa kay I found there was a Chirpy theme built for Hugo, I could just customize my shi to look like his shi.\
\
But I didn't wanna do allat. So i thought na maybe may kaparehos man nga theme, same placements, colors, simplicity....WALA. I then saw on another thread that he decided to go with another SSGs which is **Astro...** (≖_≖ )\
\
The theme he used [astro-erudite](https://astro-erudite.vercel.app/) by jktrn was the one I was looking for tho. It was incompatible with my SSGs, but because I really liked the theme...

- - -

## Mission: Import to Hugo

I wanted to import it to Hugo! I really thought na importing a theme by myself was impossible, especially when these theme repos get a lot of contribution per day. It didn't help to think about importing a theme from another SSG because I figured if a theme was popular enough, someone would have already made a copy of it for other SSGs anyway. \
\
Looking back I was stupid to overthinks things when I should've read the documentation and code structure first...SSGs Themes are nothing but are just reusable templates built from semantic HTML, stylesheets (CSS), and Markdown content...٩(ˋᗣˊ*)و

So I made sure to copy the structure and css style of the theme I wanted and by I, I mean **Antigravity** and Me. There's just no way I would read thousands of tailwind css just to convert them back to semantic css. So he took care of that and I just added the little things that I wanted. When everything was working correctly (Responsiveness and such) I edited the homepage a little different because I wanted my profile to be the center of the website rather than on the side.

- - -

## Current Status

As I'm writing this, I genuinely enjoyed through this process...**Decap** is still annoying me but I'm getting used to it (Might change CSM soon tho). The only thing I have left to do to really publish my blog is to deploy it into **Cloudflare Pages** (Underrated tbh,  I don't see much talk about it dito). Maybe my passion for gaming has gone or not...but one thing I'm sure though is that we mustn't be disarmed by the things we used to love. Sometimes the spark doesn't die, it just needs to be set aside for a while. We shouldn't feel guilty for outgrowing a phase or simply needing a break. Hell, I always thought people who wrote blogs were just bots (fr), yet here I am on my 4th hour writing this. There's still a lot of things I need to learn down my career, but I'm thankful to God for letting me go through with this. I really thought I would give up at the first paragraph. \
\
To me, **Anamnesis** represents a profound chapter. It serves as much more than a simple log to document my life's journey; it is a vital, grounding tool designed to help me navigate the pieces of my mind that slip away. Well that or my rant library. I might post more here of my past experiences whether it'd be hackathons, life, or college. \
\
I'll end this blog for now, baka akig na ung boss ko sakin sa game dev namin. („• ֊ •„)੭


<div style="text-align: right;">
Sincerely,
<br>
<br>
Me
</div>
