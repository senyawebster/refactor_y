# README

E-commerce site. Uses `bcrypt` and `materialize`. There's a seed file. Set up your own admin. If you have questions, I'll be in Bali with no email. Ask someone else.

To set up:

* `rake db:setup`

* Sorry, didn't get around to tests. It mostly works. There might be a few bugs.

**Changes Made:
1) add qty validation to order_item model so site doesn't break when product of qty 0 is added. Instead nothing happens, <b>should still add a flash</b>

2)
