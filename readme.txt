=== Groups for MemberMouse ===
Contributors: mintunmedia,roymckenzie
Tags: membermouse, member management, membership site, groups, mm groups, groups for membermouse, membermouse groups
Requires at least: 4.8
Tested up to: 5.7
Requires PHP: 5.6
Stable tag: trunk
License: GPLv3
License URI: https://www.gnu.org/licenses/gpl.html

Groups for MemberMouse allows you to sell "seats" of membership to a Group Leader or Business.

== Description ==
*Groups for MemberMouse* is one of the most sought after add-ons for MemberMouse, allowing you to offer memberships to businesses, schools, sports teams, and other users who need the ability to give access to your membership site to their team members.

Groups allows you to extend MemberMouse's premium Member Management tool with the ability to sell "seats of membership" to your members. This gives your members the capability to add their own users to their own account. The beauty is that you can increase your profit by allowing your members to purchase membership with any varying amount of seats:

3 seats: $100/mo
5 seats: $120/mo
10 seats: $200/mo

This is the perfect solution for many different business models wanting to offer seats of membership:

- B2B
- Coaches
- Churches
- Sales Teams
- and many more!

Groups for MemberMouse REQUIRES MemberMouse in order to run.

**Some features include**

- Sell seats of membership to your products and memberships.
- Offers support for the same subscriptions/pricing plans that MemberMouse does.
- Integrates directly with MemberMouse
- Dedicated Leader Management Screen - Leaders are able to manage their groups easily from a dedicated mangement screen.
- Easy to Manage for Admins - Easily create or remove groups, add any kind of payment plan to your group products, and add and remove members from specific groups.

**Upcoming Changes**

- Improved leader management screen that takes the dashboard out of /wp-admin/
- Add group import feature

**Thanks to the Github Community**
Thank you to the Github community for contributing to the [plugin's codebase](https://github.com/mintunmedia/groups-for-membermouse) and for bringing it to the state is in today. Mintun Media decided to take ownership of the codebase and has enhanced its security, stability, and WordPress compatibility. We look forward to working with the Github and WordPress communities to add new features all while adhering to WordPress coding standards. We also encourage you to make a pull request if you see any issues or have ideas to enhance the plugin.

**Shortcodes and URLs**
You'll need to add a special shortcode to your checkout page in between the `[MM_Form type="checkout"]` and `[/MM_Form]` tags. This shortcode may have a different ID than the one displayed here: `[MM_Form_Field type="custom-hidden" id="1"]`

You'll want to place a shortcode on the Group Leader's payment confirmation page, this shows them their member signup link (which they'll use to send to the people they want to invite to your membership): `[MM_Group_SignUp_Link]`

Important: You can add the `[MM_Group_SignUp_Link]` shortcode anywhere. The Payment Confirmation page may not be the most ideal place to put this shortcode.

__Group Leader Management Page__
The URL you'll want to send your Group Leader to manage their Groups (adding and deleting people, etc) is located here:
`https://[domain]/wp-admin/admin.php?page=membermousemanagegroup`

*We understand that running this dashboard in your WP admin area is not ideal. We're working on building a new Group Leader Dashboard that is embedded on a regular WordPress page using a simple shortcode in the very near future (Q4 2018).*

== Installation ==
1. Install this marvelous plugin
2. Activate it
3. Navigate to MemberMouse > Groups to set it up!
4. Be sure to add the shortcodes necessary to make it work properly (you'll see these show up as alerts in your WP admin area)
5. Start selling group memberships and increase your ROI ten-fold! (hopefully!)

== Screenshots ==
1. The Groups Dashboard

== Changelog ==
2.0.5 Improved Group Leader status change handler to include Expired status. Now if a group leader expires, all their group members under them will also expire.

2.0.4 Improved member upgrade/downgrade functionality. Improved logging. Improved Group Leader cancellation automation - cancels all members and cancels group. Fixed misc PHP warnings.

2.0.3 Added group member upgrade/downgrade functionality.

2.0.2 Fixed pagination issues on Admin Group Dashboard and Group Leader Dashboard.

2.0.1 Added ability for Group Leader to delete members on Group Leader Dashboard - only if that member does not have a paid subscription. Updated Docs.

2.0.0
- Added Admin groups management dashboard
- Added ability for admin to remove member's from groups
- Added ability for Admin's to see who is in each group
- Added ability for Admin's to navigate to member's profile from Admin Dashboard
- Improved remove Member functionality - to also remove Group Custom Field in MM
- Gave admin ability to remove a member from group when member doesn't have any active subscriptions. Before it'd only allow it if the member's status = cancelled
- Added Getting Started tab with light documentation
- General Housekeeping and cleanup

1.0.4 Fixed Notices - Now notices will be dismissable.

1.0.3 Fixed bugs. - Removed Description Field from Create Group. Not used. Fixed issue with Pagination in plugin and number of results to display. Updated loading gif to fontawesome.

1.0.2 Initial release on WordPress Plugin Repository. Fixed a lot of dependency issues within the plugin. Plugin taken over by Mintun Media from MemberMouse and maintaining it for good.

1.0.1 Update to release on Github

1.0.0 Initial Release on Github
