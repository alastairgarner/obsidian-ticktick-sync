# Obsidian TickTick Plugin

_Create tasks in Obsidian and sync them to TickTick._

> [!WARNING] **This plugin is still in development and not yet ready for use.**
> I don't initially plan on releasing this plugin to the community, but if it can get it to a point where it's stable and useful, I'll consider it.

---

## What this tries plugin tries to solve

My current personal management system involves Obsidian for documenting and managing work and personal projects, and TickTick for organising and scheduling general "life" tasks. In an ideal world I'd use a single application that allows you to both embed tasks directly into your project documentation, while keeping the task scheduling capabilities of TickTick.

While some Obsidian plugins purport to solve this scheduling requirement, I've not found one that is half a slick as TickTick.

However, if it were possible to create tasks in Obsidian and have them sync to TickTick, then I'd be able to schedule both my project tasks and general life tasks in TickTick's calendar view. Win!

With this in mind, these are the main requirements for this project:

-   AAU I can create and update tasks in Obsidian and have them sync to TickTick.
-   AAU, any changes I make to these tasks in TickTick should be reflected in Obsidian.
-   AAU I can trust this plugin not to mess up either my TickTick or Obsidian data. Both are sacred.

What this project does **not** plan to support:

-   Syncing _all_ tasks in TickTick to Obsidian. Only those tasks initially _created in Obsidian_ will sync to TickTick.

---

## Acknowledgements

This project borrows heavily from:

-   https://github.com/lucasvtiradentes/ticktick-api-lvt
-   https://github.com/thesamim/TickTickSync

A huge thanks to the developers of these projects for doing the hard work of figuring out the undocumented v2 of the TickTick API, and demonstrating how to build a TickTick integration into an Obsidian plugin, respectively. This has made it much easier for me to get this project going. I massively appreciate the work you've done.
