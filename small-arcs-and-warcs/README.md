Small ARCs and WARCs
====================

These test files, generated from [these larger samples][1] using [JWATTools v0.5.6][2].

1. jwatools decompress to make them easier to edit.
2. edit in vim, manually truncating after the seventh record.
3. renamed (adding '-truncated')
4. jwattools compress to create the compressed varients.

Note that as these were H3 WARCs, and indeed have been recompressed with JWAT tools, they may vary from the originals and not cover the same aspects of the specs as other test files.

In particular, these were not generated by wget and so cannot display the compatibility problems observed when using WARCs built using that tool. Therefore, I extracted the URLs and used wget to make a new compressed WARC file containing those resources. However, of course, this was taken some time later, and so the contents may have changed.

[1]: https://webarchive.jira.com/wiki/pages/viewpage.action?pageId=4817
[2]: https://sbforge.org/display/JWAT/JWAT-Tools
