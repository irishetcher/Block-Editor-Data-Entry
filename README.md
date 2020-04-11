# Block-Editor-Data-Entry
A simplified block editor UI of just metaboxes for custom post types in WordPress

Block Editor for Data Entry is a rudimentary plugin designed to strip out the content area of the block editor and leave just the basic UI for metaboxes.

It is intended to be used where a predefined template is applied on the front end, leaving a simple back end of custom fields for clients to enter data on instances of a custom post type (CPT).

I am making the plugin available to anybody who wants to develop it further so that it has a settings dashboard where you can select the post types it is to be applied to.

This version of the plugin is not available on the WordPress repository and is not available for general consumption. It can only be configured manually by installing it and then manually editing the PHP file to specify which CPT it should be applied to.

You can read more about this plugin here: https://sitedesign.vaughanprint.com/block-editor-for-data-entry/

Thanks to Brad Vincent for the get_current_post_type() which is used to specify the post/s type. https://gist.github.com/bradvin/1980309
