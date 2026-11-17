# ignite3d-cad

Exact goBILDA part geometry used by [Ignite3D](https://fanaustinca.github.io/ignite3d/) for STEP export.

`parts/{SKU}.stp.gz` is goBILDA's own STEP B-rep for that SKU, rewritten into Ignite3D's part frame
(millimetres, Y-up), gzipped. `parts/step-index.json` holds the entity ids Ignite3D needs to splice each
fragment into an assembly. This is served as a static site (GitHub Pages) and fetched only when you export.

**Source and attribution:** all geometry comes from the STEP files goBILDA publishes on
[gobilda.com](https://www.gobilda.com/) product pages. goBILDA® and REX® are trademarks of their owner.
This repository is an unofficial community resource for FTC teams; if you are goBILDA and want anything
changed or removed, please open an issue.
