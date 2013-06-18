Gallery Module
----------------------------------------------------------------

How to Install:

(1) Upload /app/modules/gallery/ to your /app/modules/ folder.

(2) Upload all /themes/orchard/* template files to your current theme folder (e.g., /themes/yourtheme/)

(3) Access your control panel.  You will now have a Publish > Manage Galleries navigation item.

(4) Use {content type="galleries"} to load in your galleries into a template.

(5) Use {gallery_feature_image id=$gallery_id} (where $gallery_id is the ID of a gallery) to return the path to a feature image for any
	gallery.