# vinzdg.github.io

Serves the Sparkle update feed for older Codenotch builds.

Codenotch 1.0.0 shipped asking `vinzdg.github.io/usage-notch/appcast.xml` for
its updates. That address never existed — the repo behind it is private, and
GitHub Pages does not serve private repositories — so those copies reported
"an error occurred in retrieving update information" and could never update.

A feed URL is compiled into the app, so it cannot be corrected in place. This
repository makes the address they already ask for resolve, pointing at the same
release the current feed on hivinz.com serves. No source lives here; only the
feed.
