---
title: 'previewHead'
---

Parent: [main.js|ts configuration](./Overview.md)

Type: `(head: string) => string`

Programmatically adjust the [preview head](../configure/story-rendering.md#adding-to-head) of your Storybook.

<div class="aside">

💡 If you don't need to programmatically adjust the preview head, you can add scripts and styles to [`preview-head.html`](../configure/story-rendering.md#adding-to-head) instead.

</div>

For example, you can conditionally add scripts or styles, depending on the environment:

<!-- prettier-ignore-start -->

<CodeSnippets
  paths={[
    'common/main-config-preview-head.js.mdx',
    'common/main-config-preview-head.ts.mdx',
  ]}
/>

<!-- prettier-ignore-end -->