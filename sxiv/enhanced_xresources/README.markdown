sxiv-patch: Enhanced Xresource Enabler
================================================================================
This patch lets one load their sxiv configurations from their `~/.Xresource`
file. This version is (in my opinion) a better implementation of the current
implementation due to the following reasons:
1. There is 1 and only 1 necessary call to `XrmInitialize()`.
2. There is 1 and only 1 instance of the Xrm databse being constructed.
3. Creates the framework to modify strings, integers, booleans, and doubles
   from xresources.

To apply this patch:
1. Apply the base patch `sxiv-enhanced_xresources_base-20191218-0bf3265.diff`
2. Apply the supplemental patches **after/on top of** the base patch. The
   supplemental patches are:
    - `sxiv-enhanced_xresources_image_mode.diff`
    - `sxiv-enhanced_xresources_thumbnail_mode.diff`
    - `sxiv-enhanced_xresources_window.diff`

TODO: Update to master branch of [muennich/sxiv]
[muennich/sxiv]: https://github.com/muennich/sxiv
