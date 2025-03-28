---
موضوع: Vite 6.0 منتشر شد!
نویسنده:
  نام: تیم Vite
تاریخ: 2024-11-26
نوار کناری: نادرست
سر:
  - - متا
    - ویژگی: og:type
      محتوا: وب‌سایت
  - - متا
    - ویژگی: og:title
      محتوا: معرفی Vite 6
  - - متا
    - ویژگی: og:image
      محتوا: https://vite.dev/og-image-announcing-vite6.png
  - - متا
    - ویژگی: og:url
      محتوا: https://vite.dev/blog/announcing-vite6
  - - متا
    - ویژگی: og:description
      محتوا: Vite 6 Release Announcement
  - - متا
    - نام: twitter:card
      محتوا: summary_large_image
---

# ‌‌نسخه Vite 6.0 منتشر شد!

_۲۶ نوامبر ۲۰۲۴_

![تصویری از بنر معرفی نسخه 6.0 Vite](/og-image-announcing-vite6.png)

امروزه، ما درحال برداشتن قدم بزرگ دیگری در داستان Vite هستیم. [تیم](/team) Vite، [همکاران آن](https://github.com/vitejs/vite/graphs/contributors) و شرکای اکوسیستم برای انتشار نسخه 6.0 Vite هیجان‌زده هستند.

امسال سرشار از رویداد بوده است. مقبولیت Vite رشد خود را با افزایش آمار دانلود هفنگی از ۷.۵ میلیون به ۱۷ میلیون، از زمان انتشار نسخه 5 Vite در سال پیش، ادامه داده‌ است. [Vitest](https://vitest.dev) نه‌ تنها مورد علاقه کاربران است، بلکه درحال شروع فرم‌دهی به یک اکوسیستم برای خودش نیز می‌باشد. برای مثال، [کتاب داستان](https://storybook.js.org) دارای قابلیت‌های تست جدیدی‌ست که توسط Vitest طراحی شده‌است.

کتابخانه‌های جدید دیگری نیز به اکوسیستم Vite پیوسه‌اند. مانند [TanStack Start](https://tanstack.com/start)، [One](https://onestack.dev/)، [Ember](https://emberjs.com/) و سایر . کتابخانه‌های وب درحال نوآوری با سرعتی بیشتر و افزایشی هستند. پیشرفت‌های درحال انجام توسط گروه‌ها را در [Astro](https://astro.build/)، [Nuxt](https://nuxt.com/)، [SvelteKit](https://kit.svelte.dev/)، [Solid Start](https://www.solidjs.com/blog/introducing-solidstart)، [Qwik City](https://qwik.builder.io/qwikcity/overview/)، [RedwoodJS](https://redwoodjs.com/)، [React Router](https://reactrouter.com/) مشاهده کنید. لیست ادامه‌دار می‌باشد.



در ادامه، Vite توسط OpenAI ,Google ,Apple ,Microsoft ,NASA ,Shopify ,Cloudflare ,GitLab ,Reddit ,Linear استفاده شده و در میان بسیار شرکت‌های دیگری نیز می‌باشد. ما لیستی از [شزکت‌هایی که درحال حاضر از Vite استفاده می‌کنند](https://github.com/vitejs/companies-using-vite) درست کرده‌ایم. خرسندیم که PR بسیاری از توسعه‌دهندگان را برای اضافه کردن شرکت‌شان به لیست می‌بینیم. باورش سخت است که چقدر اکوسیستمی که ما با یکدیگر ساخته‌ایم از زمانی که اولین قدم را برای آن برداشته‌ایم پیشرفت کرده است. 



![دانلود هفتگی npm Vite](/vite6-npm-weekly-downloads.png)

## افزایش سرعت اکوسیستم Vite


ماه گذشته، کامیونیتی برای ویرایش سوم [ViteConf](https://viteconf.org/24/replay) دور هم جمع شد، یکبار دیگر توسط [StackBlitz](https://stackblitz.com) میزبانی شد. این بزرگترین کنفرانس Vite، با نمایندگی گسترده‌ای از سازندگان اکوسیستم بود. بین سایر معرفی‌ها [VoidZero](https://staging.voidzero.dev/posts/announcing-voidzero-inc) توسط Evan You معرفی شد؛ شرکتی که به ساخت یک زنجیره ابزار توسعه منبع باز، با کارایی بالا و یکپارچه برای اکوسیستم جاوا اسکریپت اختصاص داده شده است. VoidZero پشت [Rolldown](https://rolldown.rs) و [Oxc](https://oxc.rs) است، و تیم آنها گام های مهمی برمی دارد و آنها را به سرعت برای پذیرش توسط Vite آماده می کند. با تماشای سخنرانی اصلی ایوان، در مورد مراحل بعدی آینده مبتی بر Rust برای Vite بیشتر بدانید.


<YouTubeideo videoId="EKvvptbTx6k?si=EZ-rFJn4pDW3tUvp" />

[Stackblitz](https://stackblitz.com) unveiled [bolt.new](https://bolt.new), a Remix app that combines Claude and WebContainers and lets you prompt, edit, run, and deploy full-stack apps. Nate Weiner announced [One](https://onestack.dev/), a new Vite-powered React framework for web and native. Storybook showcased their latest Vitest-powered [testing features](https://youtu.be/8t5wxrFpCQY?si=PYZoWKf-45goQYDt). And so much more. We encourage you to watch [all 43 talks](https://www.youtube.com/playlist?list=PLqGQbXn_GDmnObDzgjUF4Krsfl6OUKxtp). The speakers made a significant effort to share with us what each project has been up to.

Vite also got a refreshed landing page and a clean domain. You should update your URLs to point to the new [vite.dev](https://vite.dev) domain moving forward. The new design and implementation was done by VoidZero, by the same folks that made their website. Shoutout to [Vicente Rodriguez](https://bento.me/rmoon) and [Simon Le Marchant](https://marchantweb.com/).

## The next Vite major is here

Vite 6 is the most significant major release since Vite 2. We're eager to partner with the ecosystem to keep expanding our shared commons through new APIs and, as usual, a more polished base upon which to build.

Quick links:

- [Docs](/)
- Translations: [简体中文](https://cn.vite.dev/), [日本語](https://ja.vite.dev/), [Español](https://es.vite.dev/), [Português](https://pt.vite.dev/), [한국어](https://ko.vite.dev/), [Deutsch](https://de.vite.dev/)
- [Migration Guide](/guide/migration)
- [GitHub Changelog](https://github.com/vitejs/vite/blob/main/packages/vite/CHANGELOG.md#600-2024-11-26)

If you're new to Vite, we suggest reading the [Getting Started](/guide/) and [Features](/guide/features) guides first.

We want to thank the more than [1K contributors to Vite Core](https://github.com/vitejs/vite/graphs/contributors) and the maintainers and contributors of Vite plugins, integrations, tools, and translations that have helped us craft this new major. We invite you to get involved and help us improve Vite for the whole ecosystem. Learn more at our [Contributing Guide](https://github.com/vitejs/vite/blob/main/CONTRIBUTING.md).

To get started, we suggest helping [triage issues](https://github.com/vitejs/vite/issues), [review PRs](https://github.com/vitejs/vite/pulls), send failing tests PRs based on open issues, and support others in [Discussions](https://github.com/vitejs/vite/discussions) and Vite Land's [help forum](https://discord.com/channels/804011606160703521/1019670660856942652). If you'd like to talk to us, join our [Discord community](http://chat.vite.dev/) and say hi on the [#contributing channel](https://discord.com/channels/804011606160703521/804439875226173480).

For the latest news about the Vite ecosystem and Vite core, follow us on [Bluesky](https://bsky.app/profile/vite.dev), [X](https://twitter.com/vite_js), or [Mastodon](https://webtoo.ls/@vite).

## Getting started with Vite 6

You can use `pnpm create vite` to quickly scaffold a Vite app with your preferred framework or play online with Vite 6 using [vite.new](https://vite.new). You can also run `pnpm create vite-extra` to get access to templates from other frameworks and runtimes (Solid, Deno, SSR, and library starters). `create vite-extra` templates are also available when you run `create vite` under the `Others` option.

The Vite starter templates are intended to be used as a playground to test Vite with different frameworks. When building your next project, you should reach out to the starter recommended by each framework. `create vite` also provides a shortcut to setup proper starters by some frameworks, like `create-vue`, `Nuxt 3`, `SvelteKit`, `Remix`, `Analog`, and `Angular`.

## Node.js Support

Vite 6 supports Node.js 18, 20, and 22+, similar to Vite 5. Node.js 21 support has been dropped. Vite drops Node.js support for older versions after their [EOL](https://endoflife.date/nodejs). The Node.js 18 EOL is at the end of April 2025, after which we may release a new major to bump the required Node.js version.

## Experimental Environment API

Vite is getting more flexible with the new Environment API. These new APIs will allow framework authors to offer a dev experience closer to production and for the Ecosystem to share new building blocks. Nothing changes if you're building a SPA; when you use Vite with a single client environment, everything works as before. And even for custom SSR apps, Vite 6 is backward compatible. The primary target audience for Environment API is framework authors.

For end users who are curious, [Sapphi](https://github.com/sapphi-red) wrote a great [Introduction to Environment API](https://green.sapphi.red/blog/increasing-vites-potential-with-the-environment-api) guide. It is a great place to start and understand why we're trying to make Vite even more flexible.

If you are a framework author or Vite plugin maintainer and would like to leverage the new APIs, you can learn more at the [Environment API Guides](https://main.vite.dev/guide/api-environment).

We want to thank everyone involved in defining and implementing the new APIs. The story begins with Vite 2 adopting the unbundled SSR dev scheme pioneered by [Rich Harris](https://github.com/Rich-Harris) and the [SvelteKit](https://svelte.dev/docs/kit) team. Vite's SSR transform then unlocked [Anthony Fu](https://github.com/antfu/) and [Pooya Parsa](https://github.com/pi0) to create vite-node and improve [Nuxt's Dev SSR story](https://antfu.me/posts/dev-ssr-on-nuxt). Anthony went to use vite-node to power [Vitest](https://vitest.dev), and [Vladimir Sheremet](https://github.com/sheremet-va) kept improving it as part of his work maintaining Vitest. At the beginning of 2023, Vladimir started working to upstream vite-node to Vite Core, and we released it as Runtime API in Vite 5.1 a year later. Feedback from ecosystem partners (special shout-out to the Cloudflare team) pushed us to do a more ambitious rework of Vite's environments. You can learn more about the story at [Patak's ViteConf 24 talk](https://www.youtube.com/watch?v=WImor3HDyqU?si=EZ-rFJn4pDW3tUvp).

Everyone on the Vite team participated in defining the new API, which was co-designed with feedback from many projects in the Ecosystem. Thanks to everyone involved! We encourage you to get involved if you're building a framework, plugin, or tool on top of Vite. The new APIs are experimental. We will work with the Ecosystem to review how the new APIs will be used and stabilize them for the next major. If you'd like to ask questions or give feedback, there is an [open GitHub discussion here](https://github.com/vitejs/vite/discussions/16358).

## Main Changes

- [Default value for `resolve.conditions`](/guide/migration#default-value-for-resolve-conditions)
- [JSON stringify](/guide/migration#json-stringify)
- [Extended support of asset references in HTML elements](/guide/migration#extended-support-of-asset-references-in-html-elements)
- [postcss-load-config](/guide/migration#postcss-load-config)
- [Sass now uses modern API by default](/guide/migration#sass-now-uses-modern-api-by-default)
- [Customize CSS output file name in library mode](/guide/migration#customize-css-output-file-name-in-library-mode)
- [And more changes that should only affect a few users](/guide/migration#advanced)

There is also a new [Breaking Changes](/changes/) page that lists all planned, considering, and past changes in Vite.

## Migrating to Vite 6

For most projects, the update to Vite 6 should be straightforward, but we advise reviewing the [detailed Migration Guide](/guide/migration) before upgrading.

The complete list of changes is at the [Vite 6 Changelog](https://github.com/vitejs/vite/blob/main/packages/vite/CHANGELOG.md#500-2024-11-26).

## Acknowledgments

Vite 6 results from long work hours by our community of contributors, downstream maintainers, plugin authors, and the [Vite Team](/team). We appreciate the individuals and companies sponsoring Vite development. Vite is brought to you by [VoidZero](https://voidzero.dev), in partnership with [StackBlitz](https://stackblitz.com/), [Nuxt Labs](https://nuxtlabs.com/), and [Astro](https://astro.build). A shout-out to sponsors on [Vite's GitHub Sponsors](https://github.com/sponsors/vitejs) and [Vite's Open Collective](https://opencollective.com/vite).
