=== Obi LearnDash Redirect ===
Contributors: obijuandev
Tags: Redirection, LearnDash, WooCommerce
Requires at least: 5.2
Tested up to: 6.2
Stable tag: 1.0.0
Requires PHP: 7.0
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

== Description ==

Redirect any non-enrolled users from the course page to the indicated sales page in the Button URL field when the course access mode is set as closed.
This takes into consideration non-authenticated users. Also, logged-in users that have not purchased the course yet, thus not enrolled in the course.


Let's say you have a **closed course**, and payments controlled by WooCommerce.   
Let's also say that you have a **beautiful sales page** in place for your course with all the benefits your students get, and that **you don't want** unerolled users accessing the Single Course Page.   
Instead, you want them to easily reach your sales page.   
Obi LearnDash Redirect plugin helps you with that. 

== Requirements ==
* PHP 8.0
* LearnDash 4.5.3

== Changelog ==

= 1.0 =
* Initial release.
* Reditect users on closed courses.

== Road Map ==
* Add support for external URLs.
* Add support for Groups (Coming in version 1.2).
* Add an admin settings page to enable disable the redirect options.
* WooCommerce > Add the inverse feature. If a user is already enrolled in a course, and they click the WooCommerce product link, get redirected to the Single Course Page respectively.
* Add the inverse feature for internal pages (not WooCommerce).
* Add proper notices in the admin area.