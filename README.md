# Amazon eCommerce

## Description
ecommerce platform with Stripe, Inventory, and Emails


## Objectives

### Learning Objectives

After completing this assignment, you should…

* Understand the technical challenges in accepting moneys online
* Integrate with external APIs



### Performance Objectives

After completing this assignment, you be able to effectively use

* Stripe
* Emailing on Heroku with Mandrill
* Payola engine
* Rails Admin
* Friendly SEO Ids and Page Titles



## Details

### Deliverables

* A repo containing at least:
  * Seeded Products
  * Rails Admin
  * Stripe purchasing with Stripe Checkout
* Stripe should be in test mode

### Requirements

* a Rails app, live on Heroku
* a layout that looks "not-embarassing"



## Normal Mode

Your products are listing on the homepage, and can be viewed and then purchased.

Your checkout process should be secure, and use Stripe Checkout -- the payola checkout is recommended.

Use Rails Admin for administration of your app.

## Hard Mode

Everything in Normal mode, plus:

1. Add a search engine (`pg_search gem`) that will let you search for items.

2. When you add an item to the cart (`https://github.com/crowdint/acts_as_shopping_cart`) , stay on that page and give visual feedback to the user by a) the cart icon in the header b) change the "Add to cart" button to be text with "Added to Cart [View Cart](#)"

3. Create a "receipt" page that you can email to them securely, viewable without sign in

4. Email the user a receipt, with a link to the receipt page, upon successful purchase.

## Nightmare Mode

1. Enhance the search engine to auto-complete results. Include a custom template on results that shows a thumbnail of the image as well as

2. On results of the search engine, allow them to query by price "< $50" and ">= $50"

3. Allow users to see their previous purchases

5. Use a custom domain name

6. Secure Rails Admin with custom authentication (or devise for an Admin User)


## Notes

Passwords and Credit Cards should never be logged or stored in plain text.

You do not have to use the Payola gem, but it sure is nice.

Mandrill is my go-to emailing service on Heroku.

## Additional Resources

* [Payola Payments](https://github.com/peterkeen/payola)
* [Mandrill Addon](https://addons.heroku.com/mandrill)
