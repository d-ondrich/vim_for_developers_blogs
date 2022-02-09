# Vim for Developers: Part 0 — Why Vim?
(originally appeared on [Medium](https://levelup.gitconnected.com/vim-for-developers-part-0-why-vim-95e68dc5d3a1))

---

<p align="center">
  <img src="https://miro.medium.com/max/1024/1*5xyiEYh7sxvjVcZkVJawGg.gif" />
</p>

>Note: I will be using NeoVim for this series. I address why below. But 99.99% of everything I cover will work exactly the same in Vim8. So, if you’d prefer to use Vim8 you can still learn a lot! From here on out I will use Vim and NeoVim interchangeably, unless noting differences.

## What is Vim?
Once I, a dog-lover, was talking to my friend, a cat-lover, about cats and their general disdain for humanity. That’s when he said something I’ll never forget. “The thing you don’t understand about cats is they’re not dogs”. Woah. Profound. What he meant was if you approach a cat the same way you would a dog, it’s just not going to work. With that in mind:
>The thing about Vim is it’s not an IDE

Vim isn’t an IDE, it’s a text editor. It’s a lightning-fast, feature-packed text-editor with more secrets than Hogwarts, and I’d argue that with a little tweaking it has the potential to be as good, if not better, than your current IDE.
I’ve been working as a software developer for circa ~2.5 years now, and for the last ~1 year I’ve been using Vim as my “daily driver”. About 80% of my time is spent with Javascript, and the other 20% in Python. Prior to using Vim I used VS Code and the IntelliJ IDEs (WebStorm and PyCharm in my case). All great tools, but all had their weaknesses and left me wondering “is there something better?”.
I started noticing some of the coding superheroes (you know the type) at my company were using Vim. At first I assumed it was something they used because they superheroes. But, soon I started to wonder if they were superheroes because they used Vim. Well the truth is Vim won’t make you a 10x developer by itself, but if you commit some time to learning its ways, it certainly can help (or can’t hurt). If you’re willing to take the plunge read on.

## What I Look For in an IDE?
There are some key features of IDEs that boost productivity so much that they’re non-negotiable for me in a dev environment.
- Code completion/Intellisense
- Go to definition of functions/variables/etc.
- Directory navigation and searching

By the end of this series we will use the power of Vim plugins to expand the functionality to encompass all these features.

## Why Use Vim?
There’s many reasons to use Vim as we’ll see in this series. It enhances productivity, it’s super cool (okay maybe only devs might think that), but I think most importantly it’s goddam ubiquitous. Seriously. Vim is everywhere. It’s shipped preloaded on almost every computer (for sure Mac and Linux and I’d be shocked if not Windows too). It’s on Linux servers that you’ll SSH into. It’s on the ancient, brick of a computer you may be asked by a random company to do some in-person coding on for an interview. If you have Vim at your disposal you’re efficient no matter your hardware setup.
This last point might seem like a stretch. I mean, hopefully you’re not SSH-ing into production servers and writing code directly on them very often (this does happen though and in those moments, trust me, you want to be fast). But it’s much more than that. To really be a super-powered-developer, you need to be a super-user of your dev environment. Sure the company you work at now provides the IntelliJ suite of products, and you know every nook and cranny of WebStorm. But your next company might not pay for IntelliJ, and then what? Or sure you’re a wizard at VS Code, and it’s free and open-source, so there’s no reason you can’t have it anywhere? Maybe your next role is for the Government, or some other large enterprise, you’d be surprised what it’s like to get the permission to download software at some of these places. Even if it’s free.
This is really the amazing thing about Vim’s reach. You can be certain anywhere you go, you can hit-the-ground-running right from the get-go.

## Vim vs. NeoVim
I know I just preached my heart out about Vim’s ubiquity being it’s secret weapon. But, I have a confession. I actually use NeoVim.
But why? NeoVim isn’t everywhere? What gives!?
It’s true NeoVim isn’t everywhere. And to be honest at this point in time. There really isn’t a difference between Vim8 and NeoVim. The reason I use NeoVim is more of a long-term and principled philosophy and also long-term mindset. NeoVim is maintained by a large community of developers and because of this is very community-driven. Vim on the other hand is maintained by a small core of developers (bus factor, jk). And seriously, at this moment they’re almost indistinguishable. In fact, I’ll be using NeoVim for this series but 99.99% of the tips and tricks I share will work exactly the same on Vim8.
The reason I choose NeoVim is because sure today they’re basically identical, but one day they may not be. I plan on being a dev for many years to come and I’d rather put my eggs in the community-driven wagon (not sure I nailed that metaphor).

## Why Did I Write This? Do We Need Another Vim Tutorial?
I’ve read every Vim blog post. I’ve watched every configuration video on YouTube. I’m in all the subreddits. Although there’s tons of great content out there, I’ve often found there’s a key detail glossed over, or a concept not fully explained. My goal is to teach you everything from scratch. Every command will be explained fully. Every line of the init.vim/.vimrc will be explained. You will know your Vim setup inside and out.

## What Can You Expect to Learn From This Series?
You can away with to come away from this series with:
- A working knowledge of vanilla Vim (commands, mnemonics, buffers, modes, and macros)
- Ability to customize your Vim using the config file (.vimrc/init.vim)
- Knowledge to enhance your Vim setup using the power of plugins.
- The confidence to begin using Vim in your day-to-day work.

## Take The Dive
Vim for Developers: Part 1 — The Basics
Vim for Developers: Part 2 — Advanced Basics