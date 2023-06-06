## Using Zola

Build the site with `zola build`

Preview the site with `zola serve`.
If you want to preview *all* pages,
use `zola serve --drafts`.
This also applies to builds ---
ensure you don't deploy with draft builds.

### New Post

Use `./new <post-title>` to create a new one automatically.
It copies the template from `templates/page.md`
and fills it in.

## Update Date

Remember to update the "updated" date in the frontmatter,
when you update a post.

## Wrap Tables

Wrap tables inside a div.tablewrapper:

```
<div class="tablewrapper">

| table | table |
| ----- | ----- |
| item  | item  |

</div>
```

Remember to add the spacing before and after the table syntax.

This is important to make them overflow properly,
otherwise tables mess up the size of the page and other elements.
