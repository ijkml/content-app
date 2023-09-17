# Nuxt Content

This page corresponds to the `/` route of your website. You can delete it or create another file in the `content/` directory.

Try to navigate to [/about](/about). These 2 pages are rendered by the `pages/[...slug].vue` component.

## Testing inline code highlighting...

This should work... or not yet. `const codeInline: string = 'code inline'`{lang="ts"}

### Code block with syntax highlighting...

```typescript [filename]{1,3-5}meta
import { parseMarkdown } from '@nuxtjs/mdc/runtime';

async function main(mdc: string) {
  const ast = await parseMarkdown(mdc)

  // Do your magic with parsed AST tree

  return ast
}
```

```

---

Look at the [Content documentation](https://content.nuxtjs.org/) to learn more.
```
