# Things I have changed on the website from the out of the box template!

- Colour scheme
- Category hover
- Fonts
- Side Menu
- Favicon
- Search Widget
- Checkout
- A hell of a lot of CSS


### Colour Scheme
The original colour scheme featured white however I changed all the elements with ID’s and classes in the CSS to make it purple which matches the brand.

### Category hover
The hover elements helps distinguish the element when looking at all the other static images.

### Fonts
I had changed the fonts as there were other fonts in the template. Agreed by myself and Kevin, we had chosen a google font.

### Side Menu
The side menu wasn’t as clean as it is now, it featured over spacing and had no widgets to search through the products and didn’t have indication or link to the checkout.

### Favicon
As per branding,  I created a favicon with the ‘P’ since it was the most distinguishable letter.

### Search Widget
I added the search widget through the wordpress back-end panel. Woocommerce had installed the widget however it was inactive. Woocommerce also had their own styling for it which I changed in the CSS.

### Checkout
The checkout on the side had a lot of elements which wasn’t needed. There was an express checkout with Paypal but it didn’t match my design, and I do not have an SSL certificate or an API key for checkout. I had to make do with what I had.

### All CSS changes
Below is all my additional CSS I had changed in order to better the visual representation of the brand.

~~~~
.top_bar.hasbg {
background: rgba(255,255,255,0.8)
}

.top_bar.fullscreen_video #menu_wrapper div .nav > li > a, .top_bar.fullscreen_video i, .top_bar.fullscreen_video #searchform label, .top_bar.hasbg #menu_wrapper div .nav > li > a, .top_bar.hasbg i, .top_bar.hasbg .top_contact_info, .top_bar.hasbg .top_contact_info a, .top_bar.hasbg .top_contact_info a:hover, .top_bar.hasbg .top_contact_info a:active, .top_bar.dark.scroll #menu_wrapper div .nav > li > a {
color: #000 !important;
}

.top_bar.scroll.dark {
background: #fff;
border-color: #fff;
}

.top_bar.scroll.dark .header_cart_wrapper a, .top_bar.scroll.dark .post_share_wrapper a#page_share, .top_bar.scroll.dark .post_download_wrapper a#gallery_download, .top_bar.scroll.dark .social_wrapper ul li a, .top_bar.scroll.dark #menu_wrapper div .nav > li > a {
color: #000;
}

.top_bar.hasbg #mobile_nav_icon {
border-color: #000;
}

.top_bar.scroll.dark #mobile_nav_icon {
color: #000;
}

.search-field {
border: 1px solid #222;
padding: 10px;
position: relative;
text-align: center;
display: block;
font-family: 'Montserrat', 'Helvetica Neue', Arial,Verdana,sans-serif;
width: 12vw;
margin: auto;
padding-right: 20px;
float: left;
margin-bottom: 10px;
}

input[type=submit], input[type=button], a.button, .button, .pagination a:hover, .woocommerce .footer_bar .button, .woocommerce .footer_bar .button:hover, .woocommerce-page div.product form.cart .button, .woocommerce #respond input#submit.alt, .woocommerce a.button.alt, .woocommerce button.button.alt, .woocommerce input.button.alt
{
color: #FFF;
background-color: #441989;
border-color: #441989;
float:left;
padding-right: 20px;
width: 12vw;
padding-right: 20px;
}

.logo_container img {
margin: auto;
}

#page_caption.hasbg {
display: none;
}

.woocommerce .widget_shopping_cart .widget_shopping_cart_content a.button, .woocommerce table.cart td.actions .button.alt.checkout-button, .woocommerce #payment #place_order, .woocommerce-page #payment #place_order, .woocommerce table.cart td.actions .button.alt
{
margin: 10px auto;
color: #FFF;
background: #441989 !important;
border-color: #441989 !important;
}

.woocommerce #respond input#submit, .woocommerce a.button, .woocommerce button.button, .woocommerce input.button
{
padding: 1em;
}


#woo_pp_ec_button {
visibility: hidden;
}

#tagline-catchy {
font-size: 11px;
padding-top: 15px;
text-transform: none;
}

#social_share_wrapper, hr, #social_share_wrapper, .post.type-post, #page_content_wrapper .sidebar .content .sidebar_widget li h2.widgettitle, h2.widgettitle, h5.widgettitle, .comment .right, .widget_tag_cloud div a, .meta-tags a, .tag_cloud a, #footer, #post_more_wrapper, .woocommerce ul.products li.product, .woocommerce-page ul.products li.product, .woocommerce ul.products li.product .price, .woocommerce-page ul.products li.product .price, #page_content_wrapper .inner .sidebar_content, #page_content_wrapper .inner .sidebar_content.left_sidebar, .ajax_close, .ajax_next, .ajax_prev, .portfolio_next, .portfolio_prev, .portfolio_next_prev_wrapper.video .portfolio_prev, .portfolio_next_prev_wrapper.video .portfolio_next, .separated, .blog_next_prev_wrapper, #post_more_wrapper h5, #ajax_portfolio_wrapper.hidding, #ajax_portfolio_wrapper.visible, .tabs.vertical .ui-tabs-panel, .ui-tabs.vertical.right .ui-tabs-nav li, .woocommerce div.product .woocommerce-tabs ul.tabs li, .woocommerce #content div.product .woocommerce-tabs ul.tabs li, .woocommerce-page div.product .woocommerce-tabs ul.tabs li, .woocommerce-page #content div.product .woocommerce-tabs ul.tabs li, .woocommerce div.product .woocommerce-tabs .panel, .woocommerce-page div.product .woocommerce-tabs .panel, .woocommerce #content div.product .woocommerce-tabs .panel, .woocommerce-page #content div.product .woocommerce-tabs .panel, .woocommerce table.shop_table, .woocommerce-page table.shop_table, table tr td, .woocommerce .cart-collaterals .cart_totals, .woocommerce-page .cart-collaterals .cart_totals, .woocommerce .cart-collaterals .shipping_calculator, .woocommerce-page .cart-collaterals .shipping_calculator, .woocommerce .cart-collaterals .cart_totals tr td, .woocommerce .cart-collaterals .cart_totals tr th, .woocommerce-page .cart-collaterals .cart_totals tr td, .woocommerce-page .cart-collaterals .cart_totals tr th, table tr th, .woocommerce #payment, .woocommerce-page #payment, .woocommerce #payment ul.payment_methods li, .woocommerce-page #payment ul.payment_methods li, .woocommerce #payment div.form-row, .woocommerce-page #payment div.form-row, .ui-tabs li:first-child, .ui-tabs .ui-tabs-nav li, .ui-tabs.vertical .ui-tabs-nav li, .ui-tabs.vertical.right .ui-tabs-nav li.ui-state-active, .ui-tabs.vertical .ui-tabs-nav li:last-child, #page_content_wrapper .inner .sidebar_wrapper ul.sidebar_widget li.widget_nav_menu ul.menu li.current-menu-item a, .page_content_wrapper .inner .sidebar_wrapper ul.sidebar_widget li.widget_nav_menu ul.menu li.current-menu-item a, .pricing_wrapper, .pricing_wrapper li, .ui-accordion .ui-accordion-header, .ui-accordion .ui-accordion-content, #page_content_wrapper .sidebar .content .sidebar_widget li h2.widgettitle:before, h2.widgettitle:before, #autocomplete, .ppb_blog_minimal .one_third_bg, #page_content_wrapper .sidebar .content .sidebar_widget li h2.widgettitle, h2.widgettitle, h5.event_title, .tabs .ui-tabs-panel, .ui-tabs .ui-tabs-nav li, .ui-tabs li:first-child, .ui-tabs.vertical .ui-tabs-nav li:last-child, .woocommerce .woocommerce-ordering select, .woocommerce div.product .woocommerce-tabs ul.tabs li.active, .woocommerce-page div.product .woocommerce-tabs ul.tabs li.active, .woocommerce #content div.product .woocommerce-tabs ul.tabs li.active, .woocommerce-page #content div.product .woocommerce-tabs ul.tabs li.active, .woocommerce-page table.cart th, table.shop_table thead tr th, hr.title_break, .overlay_gallery_border, #page_content_wrapper.split #copyright, .page_content_wrapper.split #copyright, .post.type-post, .events.type-events, h5.event_title, .post_header h5.event_title, .client_archive_wrapper {
border-color: #FFF;
float: left;
padding: 0;
padding-bottom: 10px;
font-weight: 600;
}

.mobile_menu_wrapper .sidebar_wrapper .sidebar .content .sidebar_widget li {
margin-bottom: 0px;
margin-top: 0px;
}

.mobile_main_nav li a, #sub_menu li a {
text-transform: none;
}

#page_content_wrapper .sidebar .content .sidebar_widget li h2.widgettitle, h2.widgettitle, h5.widgettitle {
text-transform: none;
}

input[type=submit], input[type=button], a.button, .button
{
text-transform: none;
}

.woocommerce ul.products li.product h2.woocommerce-loop-product__title, .woocommerce-page ul.products li.product h2.woocommerce-loop-product__title {
text-transform: none;
}

.woocommerce .woocommerce-ordering select {
text-transform: none;
}

.woocommerce #page_content_wrapper a.button, .woocommerce.columns-4 ul.products li.product a.add_to_cart_button, .woocommerce.columns-4 ul.products li.product a.add_to_cart_button:hover {
text-transform: none !important;
}

.products {
float: left
}

#tab-title-description {
visibility: hidden !important;
}

#page_caption {
display: none;
}

.sidebar_content, .full_width {
margin-top: 50px !important;
}

.search-field {
float: left !important;
margin-top: 0px;
}

.woocommerce-pagination {
float: bottom;
}

body, #wrapper, #page_content_wrapper.fixed, #gallery_lightbox h2, .slider_wrapper .gallery_image_caption h2, #body_loading_screen, h3#reply-title span, .overlay_gallery_wrapper, .progress_bar_holder, .pricing_wrapper_border, .pagination a, .pagination span, #captcha-wrap .text-box input {
position: relative;
}

.woocommerce #content nav.woocommerce-pagination, .woocommerce nav.woocommerce-pagination, .woocommerce-page #content nav.woocommerce-pagination, .woocommerce-page nav.woocommerce-pagination {
position: absolute;
bottom: 0;
}

.mobile_main_nav li a:hover, .mobile_main_nav li a:active, #sub_menu li a:hover, #sub_menu li a:active, .mobile_menu_wrapper .sidebar_wrapper h2.widgettitle {
padding-top: 10px;
}

#page_content_wrapper .sidebar .content .sidebar_widget li select, .textwidget select, .page_content_wrapper .sidebar .content .sidebar_widget li select {
float: left;
}

#tab-description {
width: 50%;
}

.mobile_main_nav, #sub_menu {
margin-top: 10px;
margin-bottom: 0px;
}

#page_content_wrapper .sidebar .content .sidebar_widget li select, .textwidget select, .page_content_wrapper .sidebar .content .sidebar_widget li select {
margin: 0px 0px 20px 0px;
}

.form-wppp-select products-per-page{
display: none;
}

input[type=text], input[type=password], input[type=email], input[type=url], input[type=date], input[type=tel], input.wpcf7-text, .woocommerce table.cart td.actions .coupon .input-text, .woocommerce-page table.cart td.actions .coupon .input-text, .woocommerce #content table.cart td.actions .coupon .input-text, .woocommerce-page #content table.cart td.actions .coupon .input-text, select {
font-size: 11px;
}

#add_payment_method .wc-proceed-to-checkout a.checkout-button, .woocommerce-cart .wc-proceed-to-checkout a.checkout-button, .woocommerce-checkout .wc-proceed-to-checkout a.checkout-button {
font-size: 11px;}

.wcppec-checkout-buttons__separator {
display:none;
}

.dropdown_product_cat {
display: block;
position: relative;
cursor: pointer;
  -webkit-transition: all 0.15s linear;
  -moz-transition: all 0.15s linear;
  -ms-transition: all 0.15s linear;
  -o-transition: all 0.15s linear;
  transition: all 0.15s linear;
}

.dropdown_product_cat:hover {
display: block;
position: relative;
cursor: pointer;
  -webkit-transition: all 0.15s linear;
  -moz-transition: all 0.15s linear;
  -ms-transition: all 0.15s linear;
  -o-transition: all 0.15s linear;
  transition: all 0.15s linear;
background: #442087;
color: #fff;
padding: 10px;
}
~~~~
