# Xpounder Pages compatibility

Compatibility redirects for the moved RadioDesk, paper and Hormuz websites, with
unchanged paper and Hormuz assets to preserve direct download links. The original asset
hashes and source revision are recorded in `compatibility-manifest.json`.

The site publishes `site/` using GitHub Pages. It has no custom domain and does
not change DNS. Hormuz's 17 old routes retain their existing fixed destinations
on `usehormuz.github.io`; query strings stay private. JavaScript redirects preserve
fragments; the no-script refresh opens the fixed destination without a fragment.
Its 76 public assets retain the immutable website snapshot's bytes.
The root `404.html` offers a Hormuz link for unlisted legacy URLs without
automatically navigating visitors or forwarding their URL contents.
Do not recreate any moved repository slug,
because that would replace GitHub repository redirects.
