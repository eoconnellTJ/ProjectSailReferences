## BigCommerce Featured checklist 

When testing new features and branches, be sure to reference the items below making sure are functioning smoothly and as expected.

1.  MiniCart
    *   Can be found `global/tj-js/miniCart.js`
    *   User should be able to hover over cart icon and view their cart
    *   If user clicks on icon they should be redirected to cart.php page
    *   User should be able to add/remove and update items on cart from mini view
2.  Mobile Nav
    *   Can be found `js/common/collapsible.js` + `templates/components/tj/mobile-nav`
    *   Nav links should appear accordion style
    *   User should be able to view all links within viewport
    *   User should be able to scroll up and down on nav
3.  WhatsMySize
    *   Can be found `global/tj-js/whatsMySize.js` + `templates/components/products/options/set-rectangle`
    *   On category page, user can click `whats my size` which brings the user down to the table and chart sizing info.
4.  Shipping & Returns
    *   Can be found `global/tj-js/info-links.js`
    *   When link is clicked, a pop up modal with existing content
5.  Best Pair guarenteed
    *   Can be found `global/tj-js/info-links.js`
    *   When link is clicked, a pop up modal with existing content
6.  Currency Modal
    *   Can be found `ey-scripts`
    *   On page load currency modal should pop up and prompt user to select a currency
7.  Mobile Promo Banner
    *   Can be found `global/tj-js/promoBanner.js`
    *   On mobile and home page, user should see the promo at the top of screen
    *   When user scrolls down, the promo should disappear and header be fixed to top
8.  Filters accordion style on mobile
    *   Can be found `scss/tj/products/filter.scss`
    *   Filter options should appear similar to the nav links
9.  Search Removed on user scroll
    *   Can be found `global/tj-js/headerSizing.js`
    *   When user scrolls the search tab should be removed from view
    *   If user scrolls back to top the search option should appear
