Rkt_JsCssforSb
================================

INTRODUCTION
------------
A Magento Extension that will allow to add javascript and css for static blocks. This extension makes static blocks somewhat "dynamic". For every static block, there will be provision to add javascript and CSS to that particular static block. Whenever static blocks with js and css are rendered in frontend, these properties will get applied  to that static blocks

COMPATIBILITY
---------------

Currently this extension supports Magento 1.8,1.9,1.8.1. Most probably this extension  will work with lower version too.


MORE INFO
--------

You can chekckout my blog for more details : http://rajeev-k-tomy.blogspot.in/2014/08/js-and-css-for-static-block-magento.html

HOW TO INSTALL
---------------
1. Download the zip file
2. Unzip it and go to the root directory of your Magneto Applicatioin
3. Merge unzipped file there.

Soon Magento Connect will be availble for this extension.

ADVANCED DETAILS
------------------

This extension has
<pre>
Rewrite - 1
Observers - 3
</pre>


NOTES
------

1. Don't put `<script>` or `<style>` tags inside the text areas. The extension will autogenerate this enclosure html tags.
2. You can put javascirpt and css directly inside text areas
3. Don't put html contents inside the text area
4. You can put jquery in text area. In this case, it is your job to make sure that, necessary jquery files are added.
5. By default, all the script and CSS that are related to static blocks are included in `head` part.
6. Extension can detect static blocks that are added via `layout-updates`, static blocks that are added via `block-directive` (eg: `{{block id="blockId"}}` or `{{block type="cms/block" block_id="blockId"}}`) in CMS Pages and static block that are added via `layout-directive` (eg: `{{layout handle="some_handle"}}`) in CMS Pages.
