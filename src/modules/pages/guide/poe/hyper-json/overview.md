---
extends: ../../../../layouts/guide/index.jade
locals:
  title:
  description:
block: content
---

# Overview

[hyper+json](https://github.com/hypergroup/hyper-json) drives everything. It establishes the contract of how all pieces of the system communicate. This allows us to create generic clients that can be reused for any type of content and any type of client. hyper+json includes hypermedia controls, or [affordances](https://en.wikipedia.org/wiki/Affordance), to communicate the capibilities of the server at runtime. The clients then use this runtime information to make decisions for rendering and communicating back to the server.

hyper-json let's all components in the system evolve at a different pace. Features can be added to servers in a backwards-compatible way and clients don't break. Clients are written in a way that can adapt to different server implementations, where failures returned from servers isn't catastrophic.

Since hyper-json is at the heart of Poe, all of the decisions around technology are made with the idea that they will support hypermedia concepts. This makes choosing technologies relatively straightforward.

<hr/>

Dive into [Poe-UI](/guide/ui/introduction/overview) to start creating user interfaces in the browser.
