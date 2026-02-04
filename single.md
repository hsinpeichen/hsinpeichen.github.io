---
title: "Single Posts"
---

<!-- wp:template-part {"slug":"header","theme":"pub/fewer","tagName":"header"} /-->

<!-- wp:group {"lock":{"move":true,"remove":true},"layout":{"type":"default"}} -->
<div class="wp-block-group"><!-- wp:group {"style":{"border":{"top":{"width":"0px","style":"none"},"right":{"width":"0px","style":"none"},"bottom":{"color":"var:preset|color|primary","width":"1px"},"left":{"width":"0px","style":"none"}}},"layout":{"type":"constrained"}} -->
<div class="wp-block-group" style="border-top-style:none;border-top-width:0px;border-right-style:none;border-right-width:0px;border-bottom-color:var(--wp--preset--color--primary);border-bottom-width:1px;border-left-style:none;border-left-width:0px"><!-- wp:columns {"align":"full","style":{"spacing":{"padding":{"right":"var:preset|spacing|50","left":"var:preset|spacing|50","bottom":"var:preset|spacing|80","top":"0"}}}} -->
<div class="wp-block-columns alignfull" style="padding-top:0;padding-right:var(--wp--preset--spacing--50);padding-bottom:var(--wp--preset--spacing--80);padding-left:var(--wp--preset--spacing--50)"><!-- wp:column {"width":"35%"} -->
<div class="wp-block-column" style="flex-basis:35%"><!-- wp:group {"style":{"spacing":{"blockGap":"var:preset|spacing|40","padding":{"top":"var:preset|spacing|20"}}},"layout":{"type":"flex","orientation":"vertical"}} -->
<div class="wp-block-group" style="padding-top:var(--wp--preset--spacing--20)"><!-- wp:post-terms {"term":"category"} /-->

<!-- wp:template-part {"slug":"post-meta","theme":"pub/fewer","area":"uncategorized"} /--></div>
<!-- /wp:group --></div>
<!-- /wp:column -->

<!-- wp:column {"width":"55%"} -->
<div class="wp-block-column" style="flex-basis:55%"><!-- wp:post-title {"textAlign":"left"} /--></div>
<!-- /wp:column -->

<!-- wp:column {"width":"15%"} -->
<div class="wp-block-column" style="flex-basis:15%"></div>
<!-- /wp:column --></div>
<!-- /wp:columns --></div>
<!-- /wp:group -->

<!-- wp:group {"tagName":"main","lock":{"move":false,"remove":false},"style":{"dimensions":{"minHeight":"50vh"}}} -->
<main class="wp-block-group" style="min-height:50vh"><!-- wp:columns {"style":{"spacing":{"padding":{"top":"var:preset|spacing|50","right":"var:preset|spacing|50","bottom":"var:preset|spacing|50","left":"var:preset|spacing|50"}}}} -->
<div class="wp-block-columns" style="padding-top:var(--wp--preset--spacing--50);padding-right:var(--wp--preset--spacing--50);padding-bottom:var(--wp--preset--spacing--50);padding-left:var(--wp--preset--spacing--50)"><!-- wp:column {"width":"35%"} -->
<div class="wp-block-column" style="flex-basis:35%"></div>
<!-- /wp:column -->

<!-- wp:column {"width":"55%"} -->
<div class="wp-block-column" style="flex-basis:55%"><!-- wp:post-content {"lock":{"move":false,"remove":false},"layout":{"type":"default"}} /--></div>
<!-- /wp:column -->

<!-- wp:column {"width":"15%"} -->
<div class="wp-block-column" style="flex-basis:15%"></div>
<!-- /wp:column --></div>
<!-- /wp:columns --></main>
<!-- /wp:group -->

<!-- wp:columns {"style":{"spacing":{"padding":{"top":"var:preset|spacing|60","right":"var:preset|spacing|50","bottom":"0","left":"var:preset|spacing|50"}},"border":{"top":{"color":"var:preset|color|primary","width":"1px"},"right":{"width":"0px","style":"none"},"bottom":{"width":"0px","style":"none"},"left":{"width":"0px","style":"none"}}}} -->
<div class="wp-block-columns" style="border-top-color:var(--wp--preset--color--primary);border-top-width:1px;border-right-style:none;border-right-width:0px;border-bottom-style:none;border-bottom-width:0px;border-left-style:none;border-left-width:0px;padding-top:var(--wp--preset--spacing--60);padding-right:var(--wp--preset--spacing--50);padding-bottom:0;padding-left:var(--wp--preset--spacing--50)"><!-- wp:column {"width":"35%"} -->
<div class="wp-block-column" style="flex-basis:35%"><!-- wp:group {"style":{"spacing":{"blockGap":"var:preset|spacing|30"}},"layout":{"type":"flex","orientation":"vertical"}} -->
<div class="wp-block-group"><!-- wp:paragraph {"style":{"spacing":{"padding":{"top":"var:preset|spacing|50"}}},"textColor":"secondary","fontSize":"small"} -->
<p class="has-secondary-color has-text-color has-small-font-size" style="padding-top:var(--wp--preset--spacing--50)">Tags:</p>
<!-- /wp:paragraph -->

<!-- wp:post-terms {"term":"post_tag","style":{"elements":{"link":{"color":{"text":"var:preset|color|secondary"}}},"spacing":{"padding":{"top":"0"}}},"textColor":"secondary"} /--></div>
<!-- /wp:group --></div>
<!-- /wp:column --></div>
<!-- /wp:columns --></div>
<!-- /wp:group -->

<!-- wp:template-part {"slug":"footer","theme":"pub/fewer","tagName":"footer"} /-->