# The Samurai Programmer

Have you ever wondered how software is made? Have you ever wanted something to change in a program, or mod a game?

Here's how I would learn programming if I was getting started. It follows the path I took starting in 2008, with modern tools and resources.

This is an opinionated learning path. This is just how I did it.

Even if you never intend to become a professional software engineer, learning programming is a valuable skill and a creative outlet. It's a way to express yourself and create things that you can share with the world.

It's also mostly free!!

The amount of stuff to learn might be a bit daunting. Don't worry though - you can go as slow or as fast as you like. It took me around a decade. Slow and steady wins the race 🐢

## Basics

[Scratch](https://scratch.mit.edu/projects/editor/?tutorial=getStarted) is my favourite website. It's a visual programming language that's great for beginners. It's fun and easy to use, and you can make games, animations, and more.

- [ ] Make a few projects on Scratch
- [ ] [See the skill ceiling](https://scratch.mit.edu/projects/113321949/)
- [ ] Feel limited by the limitations of Scratch

Remember: limitation breeds creativity!

## HTML

HTML is the markup language of webpages. It's the foundation of the web, and it's easy to learn. You can start building web pages with just a text editor and a web browser.

Learn: https://web.dev/learn/html

Share: https://glitch.com/

If you learn accessible HTML you'll be better than 90% of people who build websites because most people don't know how to make websites that work for everyone (e.g. people who use screenreaders). Look for "a11y" (a + eleven letters + y = accessibility) resources.

- [ ] Make a few webpages with HTML
- [ ] Send your HTML files to your friends for them to open in their web browser
- [ ] Make a website on Glitch

## CSS

## JavaScript

Read [You Don't Know JS](https://github.com/getify/You-Dont-Know-JS/blob/2nd-ed/preface.md).

## 5. Scratch derivatives

- [ ] Try [tosh](https://tosh.blob.codes/app/) (text-based Scratch)
- [ ] Try [_Snap!_](https://snap.berkeley.edu/snap/snap.html) (Scratch with data structures and functions)

If you like these, you can [extend Scratch with JavaScript](https://github.com/scratchfoundation/scratch-vm/blob/develop/docs/extensions.md). You could make an extension, for example, that adds a `fetch [url]` block.

## Git

Git is a version control system that allows you to track changes to your code and collaborate with others. It's an essential tool and you might even want to use it for non-programming projects.

- [ ] If you don't use a password manager already, get [Bitwarden](https://bitwarden.com/)
- [ ] Make a GitHub account
- [ ] Download [GitKraken](https://www.gitkraken.com/)
- [ ] Create GitHub repos for your projects and push them there

If you made anything particularly cool, post it on HackerNews.

## Build a personal website

A great thing to do is build a personal website. Make it as silly as you like :)

- [ ] Create a GitHub repo
- [ ] Sign up to Cloudflare
- [ ] Buy a domain name from Cloudflare (~£10/yr)
- [ ] Use Cloudflare Pages to deploy the repo
- [ ] Share the website with your friends

You might also want to set up email forwarding so that you can use `yourname@yourwebsite.fun` as your email address!

## Invest in you and your tools

Just as the samurai cares for their body, mind, katana, and armour, the software engineer must care for their body, mind, computer, and equipment.

Consider the amount of time you spend with your tools. Let's assume you work and play at your computer for 40 hours per week. A good mechanical keyboard can set you back around £300. That's 300/40/52 = **14 pence per hour** for a year and then you've paid it off!

Investing in the right equipment will make you happier, healthier, and more productive.

### Body

- [ ] Learn (at least) hand and wrist exercises.
- [ ] Take regular breaks.
- [ ] Use a standing desk.

### Mind

- [ ] Consider [brain and gut supplements](https://refer.yourheights.com/cam8nas3)
- [ ] Learn to meditate. [Practical Zen](https://www.amazon.co.uk/Practical-Skinner-Foreword-Shinzan-Miyamae/dp/1848193637) is a great book for this.

### Computer

The goal here is a computer with a decent CPU and a 

- [ ] Buy or build a good personal computer
- [ ] Install Linux (Ubuntu first because it's the most popular; later, explore [NixOS](https://github.com/bates64/nixfiles))

If you're unable to do this, [dual boot Linux on your existing machine](https://www.tomshardware.com/how-to/dual-boot-linux-and-windows-11) or [use GitHub Codespaces](https://github.com/features/codespaces) (free for students).

### Equipment

- [ ] [Get a programmable mechanical keyboard](https://www.zsa.io/) (cheaper: build one yourself)
- [ ] [Get a vertical mouse](https://www.aliexpress.com/item/1005006243693677.html) ($$: Logitech MX Vertical)
- [ ] Get a good screen or two (I recommend 4K panels if possible)

I recommend a vertical mouse and a split mechanical keyboard because it will prevent muscle pain, repetitive strain injury, and [carpal tunnel](https://www.nhs.uk/conditions/carpal-tunnel-syndrome/). These issues can force you to retire early! Also using a vertical mouse and split keyboard makes you feel like a wizard.

## Python

Python is a scripting language. Good for writing.... scripts. That is, quick and dirty work that you don't expect to maintain.

https://learnxinyminutes.com/docs/python/

IMO if you catch yourself writing anything complicated in Python you'll regret not rewriting it in a faster, statically typed language like Rust or Java later. About the only thing slower than Python is Ruby, but Ruby makes up for it because it's a lovely language.

You might hear that machine learning (ML/AI) is all Python. That's not really true:

- All the good "Python libraries" are originally written in C, C++, or Rust. They have Python _bindings_.
- 

## C

C is the ubiquitous programming language. Even if you hate it, it's important to know about what's going on under the hood when you work with higher level languages. Some people really enjoy working at a low level!

Read [The C Programming Language (2nd ed)](https://www.amazon.co.uk/C-Programming-Language-2nd/dp/0131103628). This classic was written by Kernighan & Ritchie in 1998, and they're the guys who made the bloody language so they know what they're on about.

If you learn C, some data structures and algorithms, and build some stuff, you can pretty much skip a computer science degree.

## Paper Mario modding with C

Retro games were written in assembly or C. Nowadays they're mostly written in C++ (originally C with classes, i.e. object-oriented C).

Paper Mario (2000) is a Nintendo 64 game that's very close to my heart. I recommend mucking about with it.

https://docs.starhaven.dev

## Java

Java has no real relationship to JavaScript. JavaScript's authors thought it'd make it more popular if they called their language (most popular language of the day) + "Script" so we got JS.

Java is an object oriented programming language and you will smell its influence everywhere you go.

https://learnxinyminutes.com/docs/java/

If you like both Java and C, start learning C++. Be warned: C++ is _massive_.

## Minecraft modding with Java

https://fabricmc.net/wiki/tutorial:introduction

## Rust

https://doc.rust-lang.org/stable/book/

## The best bit

By now, you probably have an idea of what you enjoy, what you want to make, and how to build it. **Go build it!**
