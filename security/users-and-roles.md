# WordPress Users and Roles

WordPress has five default types of users — or six if WordPress Multisite is enabled. They are:

*   __Super Administrator__ — A superuser with access to the special WordPress Multisite network administration features and all other default Administrator capabilities for all the sites within a Multisite network.
*   __Administrator__ — A superuser with access to all administration features and capabilities for a single site.
*   __Editor__ — A user who can create, edit, publish, and delete all pages and posts on a site, including pages and posts created by other users. An editor can moderate, edit, and delete comments as well.
*   __Author__ — A user who can create, edit, and publish their own posts.
*   __Contributor__ — A user who can write and edit their own posts but cannot publish them.
*   __Subscriber__ — A user who only has the ability to edit their own user profile.

When WordPress Multisite is first installed, a Super Administrator account is automatically created. All new single-site installs within or apart from a Multisite network automatically create an Administrator account. 

Super Administrators, Administrators, and Editors are all considered "trusted" users, meaning they have capabilities that could be abused to damage or compromise a WordPress site. However, Authors, Contributors, and even Subscribers have limited back-end access that can sometimes be abused in combination with an insecure plugin. 

When installing plugins and themes, keep in mind that they may modify existing WordPress functionality and add additional types of content, users, and user capabilities. 

When adding users or managing user privileges, always follow the principle of the least privilege: no user should have any more privileges than they need.
