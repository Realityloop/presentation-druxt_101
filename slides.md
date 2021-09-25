---
background: https://source.unsplash.com/collection/94734566/1920x1080
class: text-center
highlighter: shiki
info: |
  ## Druxt 101
  Fully Decoupled Drupal with JSON:API and Nuxt.js

  Learn more at [DruxtJS.org](https://druxtjs.org)
theme: ./theme
---

# Druxt 101

Fully Decoupled Drupal  
with JSON:API and Nuxt.js

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 p-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Press Space for next page <carbon:arrow-right class="inline"/>
  </span>
</div>

---
layout: image-right
image: https://s.gravatar.com/avatar/499831a65f45885a7e1b70ea47c06a58?s=800
---

# Stuart Clark

<div class="my-10 grid grid-cols-[40px,1fr] w-min gap-y-4">
  <mdi-briefcase class="opacity-50" />
  <div><a href="https://www.realityloop.com" target="_blank">Realityloop.com</a></div>
  <mdi-drupal class="opacity-50" />
  <div><a href="https://www.drupal.org/u/Deciphered" target="_blank">Deciphered</a></div>
  <mdi-github class="opacity-50" />
  <div><a href="https://github.com/decipher" target="_blank">Decipher</a></div>
  <mdi-nuxt class="opacity-50" />
  <div><a href="https://druxtjs.org" target="_blank">DruxtJS.org</a></div>
  <mdi-youtube class="opacity-50" />
  <div><a href="https://www.youtube.com/channel/UCHp-BhAv8T5AHM8K4y_Mzlw" target="_blank">Mixed&nbsp;Stack&nbsp;Gaming</a></div>
  <mdi-earth class="opacity-50"/>
  <div>Australia</div>
</div>

<!--
Hello

I'm Stuart Clark:
* Decoupled Developer @ Realityloop in Australia
* Drupal developer of 15 years
* Vue developer for 3+ years with focus on decoupled, leading to the creation of Druxt

With me today is ...
-->

---
layout: image-left
image: https://secure.gravatar.com/avatar/dd0e29f8a76a2481b2bfec40e69f749f?s=800
---

# Brian Gilbert

<div class="my-10 grid grid-cols-[40px,1fr] w-min gap-y-4">
  <mdi-briefcase class="opacity-50" />
  <div><a href="https://www.realityloop.com" target="_blank">Realityloop.com</a></div>
  <mdi-drupal class="opacity-50" />
  <div><a href="https://www.drupal.org/u/realityloop" target="_blank">realityloop</a></div>
  <mdi-github class="opacity-50" />
  <div><a href="https://github.com/BrianGilbert" target="_blank">BrianGilbert</a></div>
  <mdi-youtube class="opacity-50" />
  <div><a href="https://youtube.com/konstruukt" target="_blank">Konstruukt</a></div>
  <mdi-earth class="opacity-50"/>
  <div>Australia</div>
</div>

<!--
Brian Gilbert:
- Founder of Realityloop
- Fellow Tech enthusiast and VR streamer

Today will be acting as a:
- Chat bot
- and time manager

Say Hi Brian
-->

---
layout: module
---

<div class="grid grid-cols-[2fr,2fr] gap-4">
  <div class="text-center pb-4">
    <img class="h-50 inline-block" src="/images/logo-druxt.svg">
    <div class="mb-2 text-sm">
      <h1>Druxt</h1>
      <a href="https://druxtjs.org" target="_blank">druxtjs.org</a><br />
      <a href="https://www.youtube.com/channel/UC3rybROe6cP9Uly_qQEW-4w" class="no-underline" target="_blank">
        <mdi-youtube class="inline-block no-underline opacity-50" />
      </a>
      <a href="https://twitter.com/druxtjs" class="no-underline" target="_blank">
        <mdi-twitter class="inline-block no-underline opacity-50" />
      </a>
    </div>
    <div class="opacity-50 mb-2 text-sm">
      An open source framework for building<br />
      Fully Decoupled Drupal integrations with Nuxt.js.
    </div>
    <div class="text-center">
      <a class="!border-none" href="https://www.npmjs.com/package/druxt" target="__blank"><img class="h-4 inline mx-0.5" src="https://img.shields.io/npm/v/druxt?label=druxt" alt="NPM version"></a>
    </div>
  </div>
  <div class="!all:leading-12 !all:list-none my-auto">

  - Drupal and Node module(s)
  - Drupal JSON:API client
  - Modular Vue.js component library
  - Vuex resource and collection cache
  - SPA / SSG / SSR
  - Fully Decoupled first

  </div>
</div>

<!--
Let's talk about about Druxt: What is Druxt?

Druxt is An open source framework for building Fully Decoupled Drupal integrations with Nuxt

- It is Drupal and Node Modules.
- it's aDrupal JSON:API Client
- a Modular Vue component library system with a Vuex store based caching system
  - Partial resources
  - Dehydration of both collection and included resources
- It can be used for Single Page Applications, Static Site Generation, Server Side Rendering and a combination of the lot.
- Fully decoupled first.
-->

---
layout: section
---

<div class="grid grid-cols-[2fr,2fr] gap-4">
  <div class="text-center pb-4">
    <img class="h-40 mb-4 inline-block" src="https://www.drupal.org/files/cta/graphic/drupal%208%20logo%20isolated%20CMYK%2072_1.png">
    <div class="mb-2 text-sm">
      <h1>Drupal 8</h1>
      <a href="https://drupal.org/8" target="_blank">drupal.org/8</a>
    </div>
    <div class="opacity-50 mb-2 text-xl">
      Build something amazing
    </div>
    <div class="text-center">
    </div>
  </div>

  <div class="my-auto text-center pb-4 pl-8">
    <img class="h-40 mb-4 inline-block" src="https://www.drupal.org/files/EL_blue_RGB%281%29.png">
    <div class="mb-2 text-sm">
      <h1>Drupal 9</h1>
      <a href="https://drupal.org/9" target="_blank">drupal.org/9</a>
    </div>
    <div class="opacity-50 mb-2 text-xl">
      Build the best of the web
    </div>
    <div class="text-center">
    </div>
  </div>
</div>

<!--
Druxt works with both Drupal 8 and 9, and can work on existing sites and distributions, including but not limited to ContentaCMS and Tide.
-->

---
layout: module
---

<div class="grid grid-cols-[2fr,2fr] gap-4">
  <div class="text-center pb-4">
    <img class="h-50 inline-block" src="/images/logo-druxt.svg">
    <div class="mb-2 text-sm">
      <h1>Druxt<small class="text-sm text-gray-400">.module</small></h1>
      <a href="https://drupal.org/project/druxt" target="_blank">drupal.org/project/druxt</a>
    </div>
  </div>
  <div class="pl-8 my-auto">

  ### Requires:

  <div class="text-sm py-4 !all:leading-6 !all:list-none">

  - Decoupled Router
  - JSON:API Menu Items
  - JSON:API Views

  </div>

  ### Provides:

  <div class="text-sm py-4 !all:leading-6 !all:list-none">

  - Read-only permission for required resources
  - Block condition plugin bypass
  - Enables Cross-Origin Resource Sharing (CORS)

  </div>
  </div>
</div>

<!--
The Druxt module for Drupal handles all third party requirements, and provides a read-only permission to enable the Nuxxt modules to consume the required data.

The intent is to remove the requirement on this module in favour of a Drupal native solution.
-->

---
layout: section
---

<div class="grid grid-cols-[2fr,2fr] gap-4">
  <div class="text-center pb-4">
    <img class="h-40 mb-4 inline-block" src="/images/logo-vue.svg">
    <div class="mb-2 text-sm">
      <h1>Vue.js</h1>
      <a href="https://vuejs.org" target="_blank">vuejs.org</a>
    </div>
    <div class="opacity-50 mb-2 text-xl">
      The Progressive JavaScript Framework
    </div>
    <div class="text-center">
      <a class="!border-none" href="https://www.npmjs.com/package/vue" target="__blank"><img class="h-4 inline mx-0.5" src="https://img.shields.io/npm/v/vue?label=vue" alt="NPM version"></a>
    </div>
  </div>

  <div class="my-auto text-center pb-4 pl-8">
    <img class="h-40 mb-4 inline-block" src="/images/logo-nuxt.svg">
    <div class="mb-2 text-sm">
      <h1>Nuxt.js</h1>
      <a href="https://nuxtjs.org" target="_blank">nuxtjs.org</a>
    </div>
    <div class="opacity-50 mb-2 text-xl">
      The Intuitive Vue Framework
    </div>
    <div class="text-center">
      <a class="!border-none" href="https://www.npmjs.com/package/nuxt" target="__blank"><img class="h-4 inline mx-0.5" src="https://img.shields.io/npm/v/nuxt?label=nuxt" alt="NPM version"></a>
    </div>
  </div>
</div>

<!--
Druxt is Vue.js 2 and Nuxt.js 2, and support will be added for Vue 3 and Nuxt 3 in the future.
-->

---
layout: section
---

<div class="grid grid-cols-[2fr,2fr] gap-4">
  <div>
    <h2>DruxtBlocks</h2>
    <div class="pb-2 text-sm">Blocks and regions</div>
    <a class="!border-none" href="https://www.npmjs.com/package/druxt-blocks" target="__blank"><img class="h-4 inline mx-0.5" src="https://img.shields.io/npm/v/druxt-blocks?label=druxt-blocks" alt="NPM version"></a>
  </div>

  <div>
    <h2>DruxtBreadcrumb</h2>
    <div class="pb-2 text-sm">Route based breadcrumbs</div>
    <a class="!border-none" href="https://www.npmjs.com/package/druxt-breadcrumb" target="__blank"><img class="h-4 inline mx-0.5" src="https://img.shields.io/npm/v/druxt-breadcrumb?label=druxt-breadcrumb" alt="NPM version"></a>
  </div>

  <div>
    <h2>DruxtEntity</h2>
    <div class="pb-2 text-sm">Entities, forms and fields</div>
    <a class="!border-none" href="https://www.npmjs.com/package/druxt-entity" target="__blank"><img class="h-4 inline mx-0.5" src="https://img.shields.io/npm/v/druxt-entity?label=druxt-entity" alt="NPM version"></a>
  </div>

  <div>
    <h2>DruxtMenu</h2>
    <div class="pb-2 text-sm">Menus and menu items</div>
    <a class="!border-none" href="https://www.npmjs.com/package/druxt-menu" target="__blank"><img class="h-4 inline mx-0.5" src="https://img.shields.io/npm/v/druxt-menu?label=druxt-menu" alt="NPM version"></a>
  </div>

  <div>
    <h2>DruxtRouter</h2>
    <div class="pb-2 text-sm">Wildcard router</div>
    <a class="!border-none" href="https://www.npmjs.com/package/druxt-router" target="__blank"><img class="h-4 inline mx-0.5" src="https://img.shields.io/npm/v/druxt-router?label=druxt-router" alt="NPM version"></a>
  </div>

  <div>
    <h2>DruxtSchema</h2>
    <div class="pb-2 text-sm">Entity display modes and field formatters</div>
    <a class="!border-none" href="https://www.npmjs.com/package/druxt-schema" target="__blank"><img class="h-4 inline mx-0.5" src="https://img.shields.io/npm/v/druxt-schema?label=druxt-schema" alt="NPM version"></a>
  </div>

  <div>
    <h2>DruxtSite</h2>
    <div class="pb-2 text-sm">Out-of-the-box Decoupled Drupal</div>
    <a class="!border-none" href="https://www.npmjs.com/package/druxt-site" target="__blank"><img class="h-4 inline mx-0.5" src="https://img.shields.io/npm/v/druxt-site?label=druxt-site" alt="NPM version"></a>
  </div>

  <div>
    <h2>DruxtViews</h2>
    <div class="pb-2 text-sm">Drupal Views pages and blocks</div>
    <a class="!border-none" href="https://www.npmjs.com/package/druxt-views" target="__blank"><img class="h-4 inline mx-0.5" src="https://img.shields.io/npm/v/druxt-views?label=druxt-views" alt="NPM version"></a>
  </div>
</div>

<!--
And Druxt comprises of 8 notable core modules, with several in the pipeline, including DruxtAuth and DruxtWordpress.

You can also create your own custom modules by extending the DruxtModule component.
-->

---
class: text-center
layout: fact
---

# TL;DR

## Druxt = DRUpal + nUXT

<!--
To put it simply, Druxt is Drupal plus Nuxt.
-->

---
layout: section
---

# Table of Contents

0. Introduction
1. DruxtSite - Umami Parity project
2. Getting started with DruxtSite
3. Theming (DruxtWrapper)
4. Blocks & Regions
5. Storybook
6. Reactivity and v-model
7. Static Site Generation
8. Q & A

<!--
Druxt is a big project, and there is a lot to talk about.

In case we are unable to cover everything today, checkout the slides in your own time.

Any topics you wish to prioritise, please let Brian know in the chat or via the poll.
-->

---
background: /images/modules-druxt-site.png
class: text-center
layout: cover
---

# DruxtSite

## Umami Parity project

<!--
Let's get started with DruxtSite and the Umami Parity project.
-->

---
background: /images/modules-druxt-site.png
layout: module
---

<div class="grid grid-cols-[2fr,2fr] gap-4">
  <div class="text-center pb-4">
    <img class="h-50 inline-block" src="/images/logo-druxt.svg">
    <div class="mb-2 text-sm">
      <h1>DruxtSite</h1>
      <a href="https://site.druxtjs.org" target="_blank">site.druxtjs.org</a>
    </div>
    <div class="opacity-50 mb-2 text-sm">
      Out of the box, Decoupled Drupal site experience.
    </div>
    <div class="text-center">
      <a class="!border-none" href="https://www.npmjs.com/package/druxt-site" target="__blank"><img class="h-4 inline mx-0.5" src="https://img.shields.io/npm/v/druxt-site?label=druxt-site" alt="NPM version"></a>
    </div>
  </div>

  <div>
  <div class="content-card !all:leading-12 mb-2 !all:list-none">

  - Decoupled router
  - Drupal powered Entity, Fields and Forms
  - Blocks and Regions
  - ~~Vuews~~ Views
  - Menus, Breadcrumbs, etc
  - Reactive content editing
  </div>
    
  ```vue
  // DruxtSite component
  <template>
    <DruxtSite :theme="theme" />
  </template>
  ```
  </div>
</div>

<!--
Druxt is not necessarily for out of the box Drupal sites but the DruxtSite module is.

It provides all the necessary modules to get setup for Decoupled Drupal development in under 5 minutes.

And as Druxt is Reactive by default, it supports inline content editing via the `v-model` directive.
-->

---
class: text-sm
id: R6eM3JQ_pv8
layout: youtube-right
---

# Umami Parity project

<div class="mb-10" />

<div class="my-10 grid grid-cols-[40px,260px] w-min gap-y-4">
  <ri-cloud-line class="opacity-50"/>
  <div><a href="https://demo.druxtjs.org" target="_blank">demo.druxtjs.org</a></div>
  <ri-cloud-line class="opacity-50"/>
  <div><a href="https://druxt-umami.netlify.app" target="_blank">druxt-umami.netlify.app</a></div>
  <ri-artboard-line class="opacity-50"/>
  <div><a href="http://umami-storybook.druxtjs.org" target="_blank">umami-storybook.druxtjs.org</a></div>
  <ri-github-line class="opacity-50"/>
  <div><a href="https://github.com/druxt/demo.druxtjs.org" target="_blank">github.com/druxt/demo.druxtjs.org</a></div>
  <ri-github-line class="opacity-50"/>
  <div><a href="https://github.com/druxt/demo-api.druxtjs.org" target="_blank">github.com/druxt/demo-api.druxtjs.org</a></div>
</div>

<!--
@todo Add Umami logo on slide and improve layout / style

[Click play]

This is the Umami Parity project, it's my testing ground and goal posts for the Druxt 1.0 release.

Let's take a quick walk through of the site __ BRIAN:
(BRIAN TO SHARE)
- It's serving Full Statically generated HTML, which Nuxt hydrates to provide client-side navigation.
- This also allows for Layout components, which provide modern User experience, like the SearchBar.
- The Frontend is hosted on Amazee's Lagoon, however, being Full static allows it to run on services like Netlify and Vercel.

The source code is all available on github, so be sure to check it out.
-->

---
background: https://source.unsplash.com/collection/94734566/1920x1080
class: text-center
layout: cover
---

# Getting Started

## with DruxtSite

<!--
Now, let's talk about how to get started using DruxtSite yourself.

Being Fully decoupled, Druxt requires both a Drupal and a Nuxt codebase.
-->

---
layout: youtube-left
id: PQcTyIpdHsk
---

<img class="h-15 absolute right-15" src="https://www.drupal.org/files/EL_blue_RGB%281%29.png">

# Getting Started

## Drupal

1. Download Drupal
```sh
composer create-project -s dev drupal/recommended-project [DESTINATION]
```

2. Download Druxt module
```sh
composer require drupal/druxt
```

3. Quickstart
```sh
php ./web/core/scripts/drupal quick-start
```

4. Install Druxt module: [/admin/modules](http://127.0.0.1:8888/admin/modules#edit-modules-other)

5. Configure permissions: [/admin/people/permissions](http://127.0.0.1:8888/admin/people/permissions#module-druxt)

<!--
Druxt/Decoupled Drupal needs a Drupal backend.

Drupal 8 and 9 are both supported, and the Druxt module should work with existing sites or distributions, like Contenta.

A permission is provided for READ ONLY access to JSON:API endpoints required by the Druxt fontend modules.

## Timing

- 0:35 - Drupal downloaded
- 0:47 - Druxt module downloaded
- 1:07 - Drupal installed
- 1:37 - Druxt Setup
-->

---
layout: youtube-right
id: aWoQRb4F3FY
---

<img class="h-15 absolute left-90" src="https://nuxtjs.org/logos/nuxt.svg">

# Getting Started

## Nuxt

1. Download Nuxt
```sh
npx create-nuxt-app [DESTINATION]
```

2. Download DruxtSite module
```sh
npm i druxt-site
```

3. Configure `nuxt.config.js`
```js
modules: [
  ...
  'druxt-site',
],

druxt: {
  baseUrl: 'https://example.com',
}
```

4. `npm run dev`

<!--
@TODO - Druxt is a Functional Framework, not a Design library.

## Timing

- 1:00 - Nuxt downloaded
- 1:19 - DruxtSite downloaded
- 1:51 - Setup
-->

---
background: /images/nuxt-welcome.png
class: text-center
layout: cover
---

# Welcome to ~~Nuxt~~ Druxt

## (Round 1)

<div class="mb-50" />

```
rm pages/index.vue
```

<!--
Druxt extends Nuxt, and in the case of the DruxtSite module we can see that by the presence of the DruxtRouter wildcard route.

Nuxt has a Page based routing system, which allows frontend driven campaign pages and single page apps, among other things, but in our case we want Drupal to serve the homepage, so I'll go ahead and delete this page.

1. Show Page
2. Open VueDevTools > Routes
3. Delete `pages/index.vue`
4. Reveal no content.
5. Add content
6. Show content.
7. Recap
-->

---
background: /images/druxt-welcome.png
layout: module
---

<div class="pb-4 text-center">
  <img class="h-50 inline-block" src="/images/logo-druxt.svg">
  <div class="mb-2 text-sm">
    <h1>DruxtRouter</h1>
    <a href="https://router.druxtjs.org" target="_blank">router.druxtjs.org</a>
  </div>
  <div class="opacity-50 mb-2 text-sm">
    Simple decoupled Drupal routing for Nuxt.
  </div>
  <div class="text-center">
    <a class="!border-none" href="https://www.npmjs.com/package/druxt-router" target="__blank"><img class="h-4 inline mx-0.5" src="https://img.shields.io/npm/v/druxt-router?label=druxt-router" alt="NPM version"></a>
  </div>
</div>

<!--
Once we delete the default Nuxt page, we see the No Result text for the Frontpage View, as per a standard Drupal installation.
-->

---
layout: full
---

```mermaid { theme: 'base' }
sequenceDiagram
  Browser->>+VueRouter: Request route
  alt Wildcard route
    rect rgba(65, 184, 131, 1)
      VueRouter->>+DruxtRouter: Fallback to DruxtRouter
      DruxtRouter->>+druxtRouterStore: getRoute()
      alt MISS
        rect rgba(6, 120, 190, 1)
          druxtRouterStore->>+Decoupled Router: /router/translate-path?path=
          Decoupled Router->>-druxtRouterStore: Resolved route
        end
      end
      druxtRouterStore->>-DruxtRouter: Resolved route
      DruxtRouter->>-VueRouter: Resolved component
    end
    VueRouter->>-Browser: Return page
  end
```

<!--
This is provided via the DruxtRouter module, which uses Drupals Deocupled Router module to determine the JSON:API resource and Druxt component to render.

The route data is cached in the druxtRouter vuex store, reducing queries to the Drupal backend.
-->

---
background: /images/druxt-views-page.png
layout: module
---

<div class="grid grid-cols-[2fr,2fr] gap-4">
  <div class="pb-4 text-center">
    <img class="h-50 inline-block" src="/images/logo-druxt.svg">
    <div class="mb-2 text-sm">
      <h1>DruxtViews</h1>
      <a href="https://views.druxtjs.org" target="_blank">views.druxtjs.org</a>
    </div>
    <div class="opacity-50 mb-2 text-sm">
      Drupal Views Vue.js components for Nuxt.js
    </div>
    <div class="text-center">
      <a class="!border-none" href="https://www.npmjs.com/package/druxt-views" target="__blank"><img class="h-4 inline mx-0.5" src="https://img.shields.io/npm/v/druxt-views?label=druxt-views" alt="NPM version"></a>
    </div>
  </div>
  <div class="pb-4 pl-8">

```vue
// DruxtView component
<template>
  <DruxtView :display-id="displayId" :view-id="viewId" />
</template>
```

```vue
// Default template
<template>
  <DruxtView v-bind="{ displayId, viewId }">
    <template #default="{ results, view }">
      <DruxtEntity v-for="result of results" v-bind="result" />
    </template>
  </DruxtView>
</template>
```

```vue
// Wrapper & slots
<template>
  <div>
    <slot name="filters" />
    <slot name="results" />
    <slot name="pager" />
  </div>
</template>
```

  </div>
</div>

<!--
In this case, the route is the Drupal Frontpage View, so the DruxtView module is used to render the page.

The DruxtView component can also be used in a standard Nuxt page or Vue component.

It requires a View ID or UUID, and an optional Display ID.

All configuration is managed in the Drupal backend, but the Frontend developer has access to the configuration, pagination, filters, sorts and more via the DruxtWrapper slots system.
-->

---
background: /images/drupal-cms.png
class: text-center
layout: cover
---

# Content & Configuration

<!--
1. Open Drupal backend: http://127.0.0.1:8888
2. Add content: Decopled Days 2021 * 2
3. Show Frontend.
4. Walkthrough Entity Components data
5. Recap
-->

---
background: /images/schemas.png
layout: module
---

<div class="pb-4 text-center">
  <img class="h-50 inline-block" src="/images/logo-druxt.svg">
  <div class="mb-2 text-sm">
    <h1>DruxtSchema</h1>
    <a href="https://schema.druxtjs.org" target="_blank">schema.druxtjs.org</a>
  </div>
  <div class="opacity-50 mb-2 text-sm">
    Entity Form and View mode schemas for Drupal driven frontends.
  </div>
  <div class="text-center">
    <a class="!border-none" href="https://www.npmjs.com/package/druxt-schema" target="__blank"><img class="h-4 inline mx-0.5" src="https://img.shields.io/npm/v/druxt-schema?label=druxt-schema" alt="NPM version"></a>
  </div>
</div>

<!--
The DruxtSchema module generates a schema file for each Content Entity Resource type per View and Form Display modes.

The files are currently only generated during the Druxt build cycle, but live regeneration will be added in a future release.
-->

---
background: /images/druxt-entity.png
layout: module
---

<div class="grid grid-cols-[2fr,2fr] gap-4">
  <div class="pb-4 text-center">
    <img class="h-50 inline-block" src="/images/logo-druxt.svg">
    <div class="mb-2 text-sm">
      <h1>DruxtEntity</h1>
      <a href="https://entity.druxtjs.org" target="_blank">entity.druxtjs.org</a>
    </div>
    <div class="opacity-50 mb-2 text-sm">
      Drupal Display Mode powered Entity, Form and Field Vue.js component system.
    </div>
    <div class="text-center">
      <a class="!border-none" href="https://www.npmjs.com/package/druxt-entity" target="__blank"><img class="h-4 inline mx-0.5" src="https://img.shields.io/npm/v/druxt-entity?label=druxt-entity" alt="NPM version"></a>
    </div>
  </div>
  <div class="pb-4 pl-8">

```vue
// DruxtEntity component
<template>
  <DruxtEntity :mode="displayMode" :type="resourceType" :uuid="uuid" />
</template>
```

```vue
// Default template
<template>
  <DruxtEntity v-bind="{ mode, type, uuid }">
    <template #default="{ entity, schema }">
      <h1>{{ entity.attributes.title }}</h1>
    </template>
  </DruxtEntity>
</template>
```

```vue
// Wrapper & slots
<template>
  <div>
    <h1>{{ $attrs.entity.attributes.title }}</h1>
    <slot name="field_media_image" />
    <slot name="body" />
  </div>
</template>
```

  </div>
</div>

<!--
The DruxtEntity module displays a Drupal content entity using Drupal's Display modes and field configuration.

The DruxtEntity component requires the Entity UUID, resource type and an optional display mode.

It also supports Form schemas for content editing via the schemaType property, as well as the DruxtEntityForm component
-->

---
background: /images/components.png
class: text-center
layout: cover
---

# Theming

## DruxtWrapper

---
layout: full-left
---

# Theming

### Wrappers & slots

```vue {all|1-7|9-15|17-21}
<template>
  <BCard>
    <h2>{{ entity.attributes.title }}</h2>
    <slot name="body" />
    <BButton :to="link" variant="success">Read more</BButton>
  </BCard>
</template>

<script>
export default {
  computed: {
    link: ({ entity }) => entity.attributes.path.alias || `/node/${entity.attributes.drupal_internal__nid}`,
  },
}
</script>

<style scoped>
h2 {
  color: #007bff;
}
</style>
```

<!--
Druxt provides Wrapper components for theming the modules.

A wrapper is just a Vue component:
- Template: `.tpl.php/.twig` HTML + Components, Slots and Mustache templates.
- Script: `.js` Vue & Nuxt data, props, methods, etc
- Style: `.css` Multi-lingual, scope, PostCSS processing
-->

---
layout: full-left
---

# Theming

### $attrs, props & mixins

<div class="grid grid-cols-[2fr,2fr] gap-4 mt-4 text-sm">
  <div>

```jsx
<template>
  <div>{{ $attrs.entity.attributes.title }}</div>
</template>
```

All unregistered props data is provided as `$attrs`.

It is recommended to register your `props`, or use the `mixin` provided by the module.

  </div>
  <div>

```jsx
<template>
  <div>{{ entity.attributes.title }}</div>
</template>

<script>
import { DruxtEntityMixin } from 'druxt-entity'

export default {
  mixins: [DruxtEntityMixin],
}
</script>
```

  </div>
</div>

<!--
Each module provides slots and $attrs as well as a mixin to register props.
-->

---
image: /images/components.png
layout: image-right
position: left
---

# Theming

### Wrapper component options + discovery

![DruxtEntity Component options](/images/devtools-entity-component-options.png)

<!--
- Druxt modules provide options for the Wrapper component.  
- Nuxt (>= v2.13) auto imports components.  
- First available option is used.  
- Most modules provide a default if no Wrapper component found.  
-->

---
background: https://source.unsplash.com/collection/94734566/1920x1080
class: text-center
layout: cover
---

# Prettification

## (Round 2)

<!--
1. Inspect DruxtEntity with VueDevTools
2. Show data > component > options.
3. Create `druxt/entity/node/article/Teaser.vue`
4. Navigate to node
5. Explain missing fields and DruxtWrapper
6. Create `druxt/entity/node/article/Default.vue`
7. Add `<DruxtView view-id="frontpage" />`
8. Goto Blocks demo
-->

---
background: /images/druxt-block-region.png
class: text-center
layout: cover
---

# Blocks & Regions

## (Round 3)

<!--
1. Create new `layouts/default.vue`
2. Add `<DruxtSite theme="bartik" />`
3. Add customised version of layout
4. Explain DruxtWrapper / Block decoupling
5. Add `components/druxt/block/SystemBrandingBlock.vue`
6. [BACKEND] Show blocks, remove title, tabs, help, actions, etc
7. Recap
-->


---
background: /images/druxt-block-region.png
layout: module
---

<div class="grid grid-cols-[2fr,2fr] gap-4">
  <div class="pb-4 text-center">
    <img class="h-50 inline-block" src="/images/logo-druxt.svg">
    <div class="mb-2 text-sm">
      <h1>DruxtBlocks</h1>
      <a href="https://blocks.druxtjs.org" target="_blank">blocks.druxtjs.org</a>
    </div>
    <div class="opacity-50 mb-2 text-sm">
      Provides Drupal blocks and region components.
    </div>
    <div class="text-center">
      <a class="!border-none" href="https://www.npmjs.com/package/druxt-blocks" target="__blank"><img class="h-4 inline mx-0.5" src="https://img.shields.io/npm/v/druxt-blocks?label=druxt-blocks" alt="NPM version"></a>
    </div>
  </div>
  <div class="pb-4 pl-8">

```vue
// DruxtBlock component
<template>
  <DruxtBlock :id="drupal_internal__id" />
</template>
```

```vue
// DruxtBlockRegion component
<template>
  <DruxtBlockRegion :name="name" :theme="theme" />
</template>
```

  </div>
</div>

---
background: /images/umami-storybook.png
class: text-center
layout: cover
---

# Storybook

---
id: ek8BlCghwkE
layout: youtube-right
---

<img class="h-15 absolute left-95" src="https://raw.githubusercontent.com/storybookjs/brand/master/icon/icon-storybook-default.svg">

# @nuxtjs/storybook

[storybook.nuxtjs.org](https://storybook.nuxtjs.org/)

<div class="mb-8" />

### + Druxt =

Zero-config, auto-generated Storybook integration with Druxt modules.

<div class="mb-16" />

## Getting started

<div class="mb-4" />

1. Download @nuxtjs/storybook module
```sh
npm i -D @nuxtjs/storybook
```

2. `npx nuxt storybook`

<!--
[MAKE SURE TO START STORYBOOK AFTER CONTENT WAS CREATED]

Druxt provides zero-config, auto-generated Storybook integration.

## Timing

- 0:31 - Installed
- 1:05 - Running

### Blocks

1. Bartik > Secondary Menu >> DruxtBlock (initial)
2. Docs tab
3. Expand "Content" region

### Entity

- 1:30

1. Node > Article > View displays > Default
2. Canvas tab
3. Mode > teaser
4. Change UUID (needs 2xArticles)

### Views

- 1:50

1. Frontpage > Master
2. Open in new tab
3. Vue developer tools
-->

---
background: /images/umami-storybook.png
class: text-center
layout: cover
---

# Story time

## (Round 4)

<!--
1. Open Storybook > Entity > Node > Article > View displays > Docs
2. Brief walkthrough
3. Open Default in new tab
4. Open Vue dev tools
5. Add template
    ```vue
    <template>
    </template>
    ```
-->

---
background: https://source.unsplash.com/collection/94734566/1920x1080
class: text-center
layout: cover
---

# Reactivity & v-model

---
class: text-sm
id: OL_bRANN6oA
layout: youtube-right
---

# v-model

<div class="my-10 grid grid-cols-[40px,260px] w-min gap-y-4">
  <ri-cloud-line class="opacity-50"/>
  <div><a href="https://nginx.feature-239-editbar.demo-druxtjs-org.au2.amazee.io/en/recipes/vegan-chocolate-and-nut-brownies" target="_blank">nginx.feature-239-editbar.demo-druxtjs-org.au2.amazee.io</a></div>
  <mdi-github class="opacity-50" />
  <div><a href="https://github.com/druxt/demo.druxtjs.org/pull/261" target="_blank">druxt/demo.druxtjs.org/pull/261</a></div>
</div>

```vue
<template>
  <div>
    <DruxtEntity v-bind="props" v-model="model">
    <DruxtEntityForm v-bind="props" v-model="model">
  </div>
</template>

<script>
export default {
  data: () => ({
    model: null,
    props: { type: 'node--article', uuid: '...' }
  }),
}
</script>
```

<!--
[Click play]

The EditBar is a User Experience experiment to demonstrate one of the many ways to bring editing to the frontend in a Fully Decoupled Drupal site.

Let's take a quick walk through of the site __ BRIAN:
(BRIAN TO SHARE)
- This is the first time I've seen a content preview out of Drupal that actually works

The source code is all available on github, so be sure to check it out.
-->

---
background: https://source.unsplash.com/collection/94734566/1920x1080
class: text-center
layout: cover
---

# It's time to react

## (Round 5)

---
id: SoWU5PfE7SI
layout: youtube-right
---

# Static Site Generation

1. Configure `nuxt.config.js`
```js
target: 'static',
ssr: true,

// optional.
generate: {
  routes: ['/', '/en', '/es'],
}
```

2. `npm run generate`

3. (optional) `npm start`

<!--
Static Site generation works out of the box, as long as you have `target: 'static'` set.

Nuxt will crawl all accessible links and generate HTML pages for Drupals content.

If
-->

---
class: text-center
layout: cover
---

# Sponsors

<div class="grid grid-cols-[2fr,2fr] gap-4">
  <div class="text-center pb-4 mt-8">
    <a href="https://www.realityloop.com" target="_blank"><img class="mb-4 ml-8 w-100" src="/images/realityloop-logo-transparent.png"></a>
    <div class="mb-2 text-sm mt-14">
      <h2>Development</h2>
    </div>
  </div>

  <div class="my-auto text-center pb-4 pl-8">
    <a href="https://amazee.io" target="_blank"><img class="h-30 mb-4 ml-12" src="/images/amazeeio-logo-transparent.webp"></a>
    <div class="mb-2 text-sm">
      <h2>Hosting</h2>
    </div>
  </div>
</div>

<!--
A big thanks to Realityloop for sponsored development on the project.

And to lagoon for providing community hosting for the website.
-->

---
class: text-center
layout: cover
---

# Q & A

### [Your question goes here]

<div class="mb-10" />

# Find out more

<div class="grid grid-cols-[2fr,2fr] gap-4 !all:border-0 mt-5 !all:mb-5">
  <a href="https://druxtjs.org">druxtjs.org</a>
  <a href="https://github.org/druxt">github.org/druxt</a>
  <a href="https://discord.druxtjs.org">discord.druxtjs.org</a>
  <a href="https://druxt-101.slides.realityloop.com">druxt-101.slides.realityloop.com</a>
</div>
