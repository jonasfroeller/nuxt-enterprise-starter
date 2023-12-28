# Nuxt Enterprise Starter

```bash
# initialized using nuxi
npx nuxi init -t ui nuxt-enterprise-starter
```

## [Why](https://nuxt.com/docs/getting-started/introduction)?

Why not :)  
I like to learn frameworks by building a poc project with them, to see if they fit my needs and how they behave.  
I really like **SvelteKit**, but I tried Nuxt and it does so many things right as well.  
Nuxt also feels a lot more mature and suiting for bigger projects.  
**\+** The vuejs and nuxt community is awesome!

**Docs**: [nuxt.com/docs](https://nuxt.com/docs/getting-started/introduction)  
Other **starters**: [nuxt.new](https://nuxt.new)  
And **templates**: [nuxt.templates](https://nuxt.com/templates)  
More of nuxt: [nuxt.resources](https://github.com/nuxt/awesome)

## Features

- [x] [Nuxt](https://nuxt.com)
- **UI**
  - [x] [Nuxt UI](https://ui.nuxt.com)
  - [x] [TailwindCSS](https://nuxt.com/modules/tailwindcss)
    - [ ] [Typography](https://tailwindcss.com/docs/typography-plugin)
  - [ ] [Google Fonts](https://nuxt.com/modules/google-fonts)
- **Content**
  - [x] [Nuxt Content](https://nuxt.com/modules/content)
  - [ ] [Strapi CMS](https://strapi.io)
    - [nuxt-module](https://nuxt.com/modules/strapi)
    - [image](https://hub.docker.com/r/strapi/strapi)
  - [ ] [SEO](https://nuxt.com/modules/seo-kit)
- **Assets/Images**
  - [ ] [Nuxt Image](https://nuxt.com/modules/image)
  - [ ] [Image Lazy Loading](https://nuxt.com/modules/unlazy)
  - [ ] [PWA](https://nuxt.com/modules/vite-pwa-nuxt)
- **Testing**
  - [ ] [Unlighthouse](https://unlighthouse.dev/integrations/nuxt)
- **Database**
  - [ ] [MongoDB](https://nuxt.com/modules/nuxt-mongoose)
  - [ ] [Authentication](https://nuxt.com/modules/authjs)
- **Legal**
  - [ ] [Cookies](https://nuxt.com/modules/cookie-control)
- **Monitoring/Analytics**
  - [ ] [Analytics](https://nuxt.com/modules/umami)
- **Payments**
  - [ ] [Payments](https://nuxt.com/modules/stripe-next)
- **Emails**
  - [ ] [Vue Email](https://nuxt.com/modules/vue-email)
- **Other**
  - [ ] [SwiperJS](https://nuxt.com/modules/swiper)
  - [ ] [Algolia Search](https://nuxt.com/modules/algolia)
  - [ ] [DDos Protection](https://nuxt.com/modules/turnstile)

---

- **more [modules](https://nuxt.com/modules) you could add**  
  - [ChatGPT](https://nuxt.com/modules/nuxt-chatgpt)

## Setup

### Install Dependencies:

```bash
pnpm install
```

### Add Dependencies:

#### Development Scope

```bash
pnpm add -D <dependency>
```

#### Production Scope

```bash
pnpm add <dependency>
```

### Remove Dependencies:

```bash
pnpm remove <dependency>
```

### Other Commands

```bash
# update dependencies
pnpm update

# list dependencies
pnpm list

# list outdated dependencies
pnpm outdated

# run script
pnpm [run] <script>

# npx equivalent
pnpm dlx <command>

# exec command
pnpm exec <command>

# initialize project
pnpm create <template> <name>
```

## Development

```bash
pnpm run dev -o
```

## Production

### Build

```bash
pnpm run build
```

### Serve Build

Locally preview production build:

```bash
pnpm run preview
```

Check out the [deployment documentation](https://nuxt.com/docs/getting-started/deployment) for more information.
