<div align="center">

<img src="https://degreesign.com/assets/images/Degree_Sign_Logo_2022.svg" alt="DegreeSign" width="96" height="96">

# DegreeSign

**Level Up Your Application**

[![Website](https://img.shields.io/badge/degreesign.com-visit-930988?style=flat-square)](https://degreesign.com)
[![npm](https://img.shields.io/badge/npm-%40degreesign-CB3837?style=flat-square&logo=npm&logoColor=white)](https://www.npmjs.com/search?q=%40degreesign)
[![Agent Skills](https://img.shields.io/badge/agent_skills-compatible-6E56CF?style=flat-square)](https://agentskills.io)
[![License](https://img.shields.io/badge/license-MIT-2ea44f?style=flat-square)](https://github.com/DegreeSign/ds_ui/blob/main/LICENSE)

</div>

## What we build

DegreeSign builds and runs [degreesign.com](https://degreesign.com): a GS1 Digital Link QR platform with free product info hosting, alongside manufacturing and design services. The site and its API are TypeScript end to end, from the DOM helpers and the build system to the server SDK and the mail archiver.

Every piece we needed and could not find as a small, dependency-free module is published here under the MIT license. No frameworks, no runtime lock-in, no account required.

## The product

- **GS1 QR generator** at [degreesign.com/qr](https://degreesign.com/qr): every supported application identifier, a downloadable GS1 Digital Link QR, and free hosted product info with no signup.
- **Product pages** at [degreesign.com/products](https://degreesign.com/products): the record a scanned GS1 QR resolves to, decoded and readable by any GS1 compatible reader.
- **Client portal** at [degreesign.com/account](https://degreesign.com/account): products, invoices and renewals, paid in sats over Lightning.
- **Manufacturing and design** at [degreesign.com/physical](https://degreesign.com/physical): product design, prototyping and production.

## Open source

All packages are on npm and MIT licensed. They are small on purpose: zero runtime dependencies where possible, typed APIs, and browser plus Node builds from one import.

| Package | What it does |
|---|---|
| [`@degreesign/ui`](https://github.com/DegreeSign/ds_ui) | DOM controls, instant hCaptcha, on-demand script loading |
| [`@degreesign/webapp`](https://github.com/DegreeSign/ds_webapp) | Webpack build standard: bundles, PWA, SEO meta tags |
| [`@degreesign/server`](https://github.com/DegreeSign/ds_server) | REST API server on `node:http`, no framework |
| [`@degreesign/analytics`](https://github.com/DegreeSign/ds_analytics) | Privacy-first, self-hosted web analytics |
| [`@degreesign/cache`](https://github.com/DegreeSign/ds_cache) | File, JSON and gzipped JSON cache for Node |
| [`@degreesign/utils`](https://github.com/DegreeSign/ds_utils) | Numbers, dates, statistics, forecasting, IDs, crypto |
| [`@degreesign/storage`](https://github.com/DegreeSign/ds_storage) | Typed local and IndexedDB storage, optionally encrypted |
| [`@degreesign/ai`](https://github.com/DegreeSign/ds_ai) | Typed SDK for any OpenAI compatible endpoint |
| [`@degreesign/chat`](https://github.com/DegreeSign/ds_chat) | Headless on-device AI chat, CPU and WebGPU engines |
| [`@degreesign/voice`](https://github.com/DegreeSign/ds_voice) | Speech to text and text to speech on the device |
| [`@degreesign/migrate`](https://github.com/DegreeSign/ds_migrate) | One command Ubuntu server migration over SSH |

```bash
npm install @degreesign/ui @degreesign/utils @degreesign/server
```

## Agent Skills

[`@degreesign/skills`](https://github.com/DegreeSign/skills) gives AI coding agents one entry point and seven reusable sub-skills: Material Symbols icons, npm releases and architecture maps, house coding conventions, high-performance web apps, Node backends, task backlogs and LLM discovery files. Plain Markdown, any skills compatible client.

```bash
npx @degreesign/skills
```

## How we build

- **TypeScript everywhere.** One language for the browser, the server and the tooling, with types shipped in every package.
- **Own the stack.** We publish the primitives we run on, so the product and the libraries stay in step.
- **Privacy first.** Cookieless analytics, on-device speech and chat, and no third-party trackers.
- **Docs for humans and agents.** Markdown pages, `llms.txt` and skill files sit next to the code.

## Contributing

Issues and pull requests are welcome on any repository above. For anything larger, mail [make@degreesign.com](mailto:make@degreesign.com) first so we can agree on the shape before you write code.

## Contact

- Website: [degreesign.com](https://degreesign.com)
- Packages: [degreesign.com/packages](https://degreesign.com/packages)
- Email: [make@degreesign.com](mailto:make@degreesign.com)

<div align="center"><sub>MIT licensed. Built by DegreeSign.</sub></div>
