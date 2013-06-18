hero-gallery
============

Create and manage image galleries in your control panel more flexibly than with the standard content type manager.  You can upload ZIP archives of images and single images and re-arrange them into a gallery.  The frontend is easily customized through standard templates, also included in this download.

## Installation

* Upload `/app/modules/gallery/` to your `/app/modules/` folder.

* Upload all `/themes/orchard/*` template files to your current theme folder (e.g., `/themes/yourtheme/`).

* Access your control panel.  You will now have a `Publish > Manage Galleries` navigation item.

* Use `{content type="galleries"}` to load in your galleries into a template.

* Use `{gallery_feature_image id=$gallery_id}` (where `$gallery_id` is the ID of a gallery) to return the path to a feature image for any gallery.
