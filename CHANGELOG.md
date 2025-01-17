## [0.6.1](https://github.com/growupanand/ConvoForm/compare/0.6.0...0.6.1) (2024-04-07)

### Improvements

- ⚡️ Added empty string validation in answer input form
  ([ad3acec](https://github.com/growupanand/ConvoForm/commit/ad3acec7e27b6d61f550a651cb6e97efcfd745fb))
- 💄 Added illustration for endscreen in Form Submission pa
  ([50ae285](https://github.com/growupanand/ConvoForm/commit/50ae285d1b7704ed7ebcf6c95fc380bfdcf1625b))
- 💄 UI improvement in Form submission page
  ([d3b0332](https://github.com/growupanand/ConvoForm/commit/d3b033251f374170b044c3f159547284db8e7a91))

## [0.6.0](https://github.com/growupanand/ConvoForm/compare/0.5.0...0.6.0) (2024-04-03)

### Features

- 🚀 Added custom end screen message setting
  ([aa84182](https://github.com/growupanand/ConvoForm/commit/aa841829a19a3af2380f0dd5269cfae28774d816))
- 🚀 As form creator, I can add my company logo to the form
  ([#219](https://github.com/growupanand/ConvoForm/issues/219))
  ([9781e48](https://github.com/growupanand/ConvoForm/commit/9781e485be1f0805503060f909b7fabe817fd9be))
- 🚀 As form creator, I can add my company name to the form
  ([#216](https://github.com/growupanand/ConvoForm/issues/216))
  ([9b0cbf6](https://github.com/growupanand/ConvoForm/commit/9b0cbf6e0079de7872f51700925d86a4eea71212))

### Bug Fixes

- 🐛 Sometimes form editor page not loading
  ([c46eab4](https://github.com/growupanand/ConvoForm/commit/c46eab40a7283d25764078785f857ec2fa6f9be6)),
  closes [#206](https://github.com/growupanand/ConvoForm/issues/206)
- 🐛 tanstack mutate query raise false uncaught error
  ([7828ac4](https://github.com/growupanand/ConvoForm/commit/7828ac49b86724516eb0c2ab8f8b684312a01444)),
  closes [#208](https://github.com/growupanand/ConvoForm/issues/208)

### Improvements

- ⚡️ added ratelimit - create workspaces, forms
  ([aa70d75](https://github.com/growupanand/ConvoForm/commit/aa70d75ef06cd5ce637fd512a08a7dcb870e806b)),
  closes [#199](https://github.com/growupanand/ConvoForm/issues/199)
- ⚡️ added ratelimit - edit workspace, form
  ([6ac8f8d](https://github.com/growupanand/ConvoForm/commit/6ac8f8d48f39f703f5ec20d6efec79c00fa02d50)),
  closes [#200](https://github.com/growupanand/ConvoForm/issues/200)
- ⚡️ added ratelimit for OpenAI calls
  ([8376550](https://github.com/growupanand/ConvoForm/commit/8376550caae63620f5db51f7cf71e2e92e68c91d)),
  closes [#201](https://github.com/growupanand/ConvoForm/issues/201)
- 💄 Added request feature card in landing page
  ([c72e516](https://github.com/growupanand/ConvoForm/commit/c72e51680e3f7e399f08ad5490b1b7c2d9b5c0b0))
- 💄 added stagger animation for list items
  ([1961d0f](https://github.com/growupanand/ConvoForm/commit/1961d0f6256399573887575a1aee8d3b6d9ce37c)),
  closes [#210](https://github.com/growupanand/ConvoForm/issues/210)
- 💄 UI improvements in landing page
  ([6df1fcb](https://github.com/growupanand/ConvoForm/commit/6df1fcbaaff49660b408daa7dd4598a4a65c4756))
- 💡 changes related to form submission page
  ([f658846](https://github.com/growupanand/ConvoForm/commit/f6588465ab4155393b83253074d183a179d411b1))
- 💡 custom end screen message related changes
  ([f6a3ce4](https://github.com/growupanand/ConvoForm/commit/f6a3ce4c014fe036db034c9cd4e3e0d87149644a))
- 💡 fixed ratelimit error message toast
  ([e887a1b](https://github.com/growupanand/ConvoForm/commit/e887a1b57d10a0338308a46b9dfa8a6351735e8f))

## [0.5.0](https://github.com/growupanand/ConvoForm/compare/0.4.0...0.5.0) (2024-02-27)

### Features

- 🚀 added recent responses and usage card in dashboard page
  ([0adb281](https://github.com/growupanand/ConvoForm/commit/0adb28109b3255dbadec52b74638b1ef6227a5b4))
- 🚀 As a User, I Can Generate a New Form with AI
  ([70182c7](https://github.com/growupanand/ConvoForm/commit/70182c7241ad46b825785ee84d26d5bb4e1d15c2)),
  closes [#192](https://github.com/growupanand/ConvoForm/issues/192)

### Bug Fixes

- 🐛 Anyone can edit any form using the form link even it is
  ([37f4203](https://github.com/growupanand/ConvoForm/commit/37f42033e35269bcc6137a88e71c9e4def43561d)),
  closes [#194](https://github.com/growupanand/ConvoForm/issues/194)
- 🐛 edge case where collected data value is not string
  ([7989c2b](https://github.com/growupanand/ConvoForm/commit/7989c2bfca42ee72f36f9f29776a37ad7a370a3e))
- 🐛 form editor page break sometime
  ([bf718b7](https://github.com/growupanand/ConvoForm/commit/bf718b7a2a20cd6c1009064486d7d2f01b64992a))
- 🐛 handled uncaught error while chaning form name
  ([386b28a](https://github.com/growupanand/ConvoForm/commit/386b28ac3a6afbb41ab332de13e5ec30c206fdd1))
- 🐛 progress circle label position fixed while scroll window
  ([faafcbf](https://github.com/growupanand/ConvoForm/commit/faafcbf18dc6341071f6e14e819f6ebc7d8ca13f))
- 🐛 tremor chart library styling was not working with shadcn
  ([2b21f28](https://github.com/growupanand/ConvoForm/commit/2b21f280a0a5a19853571a5a6518955227424809))

### Improvements

- ⚡️ While using Auto form generate using AI, we will genera
  ([24e899c](https://github.com/growupanand/ConvoForm/commit/24e899c0bc66518605e35108c984d10c5cf1dde1))
- 💄 fixed percentage in response usage progress circle
  ([129477a](https://github.com/growupanand/ConvoForm/commit/129477a004b74165e5429cbb097899d37a27cd02))
- 💄 make generate AI form dialog responsive
  ([db04ffc](https://github.com/growupanand/ConvoForm/commit/db04ffcefdc9729e7b01ea7080aef38518b8a8b2))
- 💄 minor UI changes and removed harcoded value
  ([c183e64](https://github.com/growupanand/ConvoForm/commit/c183e64ad11dbec679d1a1f5ada3bc87aee2aad1))
- 💄 UI changes in landing page for new feature lanuch
  ([4c4e066](https://github.com/growupanand/ConvoForm/commit/4c4e066267cc0f613d794df7ab59fe81abc35024))
- 💄 UI improvements in auto generate form
  ([f03894e](https://github.com/growupanand/ConvoForm/commit/f03894e7c0ea5901fd2f55ee651f47d18e9d28b7))
- 💡 clerk webhook db calls from nextjs app to api
  ([0c3a265](https://github.com/growupanand/ConvoForm/commit/0c3a265ea7ee6bc92131f58a545c2245a560d1ad))

## [0.4.0](https://github.com/growupanand/ConvoForm/compare/0.3.0...0.4.0) (2024-02-13)

### Features

- 🚀 added form responses overview page
  ([fade9a1](https://github.com/growupanand/ConvoForm/commit/fade9a1539031afc9ed879be7c2c9c045c1d9da6)),
  closes [#162](https://github.com/growupanand/ConvoForm/issues/162)
- 🚀 now you can export and download responses table data
  ([105e241](https://github.com/growupanand/ConvoForm/commit/105e24103017b52339bba2894cbf93cdb0590e49)),
  closes [#186](https://github.com/growupanand/ConvoForm/issues/186)

### Bug Fixes

- 🐛 meta images not showing
  ([b19cfa1](https://github.com/growupanand/ConvoForm/commit/b19cfa19e70d8cd10d01462ec3e4cda7e482da8e))

### Improvements

- ⚡️ added drizzle and used it in whole project
  ([b50d53e](https://github.com/growupanand/ConvoForm/commit/b50d53ed080300652dd086353ab2aec415a72dfe))
- ⚡️ converted tRPC api route into edge runtime
  ([b41bc5d](https://github.com/growupanand/ConvoForm/commit/b41bc5d23d012681108de17aa172c4e58ef38886)),
  closes [#182](https://github.com/growupanand/ConvoForm/issues/182)
- ⚡️ removed prisma
  ([8e99984](https://github.com/growupanand/ConvoForm/commit/8e9998450faeb745b713d707e16327c24e13f14c))
- ⚡️ upgraded version of tRPC and @tanstack/react-query
  ([131c0a7](https://github.com/growupanand/ConvoForm/commit/131c0a7d7c9448da06906c7560488d47317a549d))
- 💄 added screenshots Carousel in landing page hero secito
  ([f8b5e1e](https://github.com/growupanand/ConvoForm/commit/f8b5e1ee6431644cd9c9bcf7430a4563ab67fbb8))
- 💄 Display confirm box before deleting workspace or form
  ([60c1dda](https://github.com/growupanand/ConvoForm/commit/60c1dda58a26d084ff7de7c8e811495e6a809e6f)),
  closes [#116](https://github.com/growupanand/ConvoForm/issues/116)
- 💡 fixed default value for updatedAt field in database
  ([97fd638](https://github.com/growupanand/ConvoForm/commit/97fd638d58a0b8f7abb46e6c5b388ae3460c7c73))

## 0.3.0 (2024-02-02)

### Features

- [#153](https://github.com/growupanand/ConvoForm/issues/153) while going to
  previous question, previous answer should also auto-filled in input
  ([f8c2b15](https://github.com/growupanand/ConvoForm/commit/f8c2b15bb54867c890e45658dec1f76b8cbea04e))
- 🚀 Added changelog page
  ([5677e81](https://github.com/growupanand/ConvoForm/commit/5677e81398afe79da99384e08c2ce8f378e47e6d)),
  closes [#143](https://github.com/growupanand/ConvoForm/issues/143)
- 🚀 Added charts in dashbard page
  ([c61739c](https://github.com/growupanand/ConvoForm/commit/c61739c30bab0d660fa60759bf74294a946480e0)),
  closes [#147](https://github.com/growupanand/ConvoForm/issues/147)

### Bug Fixes

- 🐛 auth pages were not working
  ([59688a3](https://github.com/growupanand/ConvoForm/commit/59688a3e2b8ea0e4b03acf453937519293e1f2bf))
- 🐛 Prisma client not working on production
  ([59fb06a](https://github.com/growupanand/ConvoForm/commit/59fb06a98b43cf908adaf6e242142404a7ec140b)),
  closes [#173](https://github.com/growupanand/ConvoForm/issues/173)
- 🐛 Unauthorized getOrganizationId(src/lib/getOrganizationId
  ([f7f404d](https://github.com/growupanand/ConvoForm/commit/f7f404d00ee0211c17c6c2959850193d8b77ac40)),
  closes [#166](https://github.com/growupanand/ConvoForm/issues/166)
- 🐛 wrong domain name on production doployment
  ([f738b62](https://github.com/growupanand/ConvoForm/commit/f738b6220b36f775a7a187322d75cb84305b9fa0)),
  closes [#159](https://github.com/growupanand/ConvoForm/issues/159)

### Improvements

- ⚡️ added meta image
  ([3ad6a63](https://github.com/growupanand/ConvoForm/commit/3ad6a63bfb0fddc050081a7e43320c02b6393ef8))
- ⚡️ added sperate organization selection page
  ([40941cb](https://github.com/growupanand/ConvoForm/commit/40941cb99281e39b4e150b9ca9e4cec3c05bdd53)),
  closes [#169](https://github.com/growupanand/ConvoForm/issues/169)
- ⚡️ Added trpc
  ([ef2dd15](https://github.com/growupanand/ConvoForm/commit/ef2dd156c37407a106e6b44c578c6b9856eec864)),
  closes [#145](https://github.com/growupanand/ConvoForm/issues/145)
- ⚡️ made root page static
  ([61ebf26](https://github.com/growupanand/ConvoForm/commit/61ebf265cc4ce791c79862214a95ca99eb1be009))
- 💄 Addded Progress Indicator while navigating pages
  ([4876b35](https://github.com/growupanand/ConvoForm/commit/4876b35914f4839039de36c36f908b13863ad3c8)),
  closes [#163](https://github.com/growupanand/ConvoForm/issues/163)

## [0.2.1](https://github.com/growupanand/ConvoForm/compare/0.2.0...0.2.1) (2024-01-23)

### Bug Fixes

- 🐛 wrong domain name on production doployment
  ([d5dcbd6](https://github.com/growupanand/ConvoForm/commit/d5dcbd687b0a242d9ece628b00ba5de7952f7c0a)),
  closes [#159](https://github.com/growupanand/ConvoForm/issues/159)

## 0.2.0 (2024-01-22)

### Features

- [#153](https://github.com/growupanand/ConvoForm/issues/153) while going to
  previous question, previous answer should also auto-filled in input
  ([2ac600d](https://github.com/growupanand/ConvoForm/commit/2ac600d7cab948b2a59050f5ffdb752e271f8d82))
- 🚀 Added changelog page
  ([8ff20ea](https://github.com/growupanand/ConvoForm/commit/8ff20ea58bf1b829553244d1b5fb2298e4d9fb55)),
  closes [#143](https://github.com/growupanand/ConvoForm/issues/143)

## 0.1.1 (2024-01-21)

### Reverts

- Revert "Added DIRECT_URL in db schema to make prisma work with pool
  connection"
  ([c8a60f5](https://github.com/growupanand/ConvoForm/commit/c8a60f5e57e3ff4767c4dee8ede2fa77f0b7837e))
- Revert "Added email provider to login using magic links"
  ([4306a0e](https://github.com/growupanand/ConvoForm/commit/4306a0ed3df74c8188343e2ce6db9c44445d44cd))
- Revert "Added custom email template for login magic link"
  ([0a97289](https://github.com/growupanand/ConvoForm/commit/0a972892716f47982356d4d07df71228c73bc654))
