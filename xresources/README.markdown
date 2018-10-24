sxiv-patch: Xresource Enabler
================================================================================
This patch lets one load their sxiv configurations from their `~/.Xresource`
file.

There are two options to apply this patch:
- **Only** apply the `sxiv-undocumented_xresources_all.diff`
    file
- Apply the base patch `sxiv-undocumented_xresources_base.diff`
    and then apply the supplemental patches **after** the base patch. The
    supplemental patches are:
    - `sxiv-undocumented_xresources_image_mode.diff`
    - `sxiv-undocumented_xresources_thumbnail_mode.diff`
    - `sxiv-undocumented_xresources_window.diff`
