# Shopify-Tricks-Snippets
Breadcrums based on Linked items menu

You can use this on collection liquid file by adding below line at location where you want to display it. 

{%include 'breadcrumbs', list:'main-menu', current:collection.handle%}

"list" is your main top level menu handle. By default it is main-menu.
"current" is your currently loaded page handle. This is for collection page, so it is collection.handle. 

Code changes require if you want to display this type of breadcrumb on product pages or any blog pages etc.. 

Contact me for custom changes in Shopify stores. 
