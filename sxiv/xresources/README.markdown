sxiv-patch: Xresource Enabler
================================================================================
This patch lets one load their sxiv configurations from their `~/.Xresource`
file.

To apply this patch:
1. Apply the base patch `sxiv-undocumented_xresources_base.diff`
2. Apply the supplemental patches **after/on top of** the base patch. The
   supplemental patches are:
    - `sxiv-undocumented_xresources_image_mode.diff`
    - `sxiv-undocumented_xresources_thumbnail_mode.diff`
    - `sxiv-undocumented_xresources_window.diff`
