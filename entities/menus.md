# Menus

In Drupal, menus are more than just simple links to other pages, they drive the site's content hierarchy as well as URLs and Breadcrumbs within pages.

### Managing menus

Menus can be managed in several ways in Drupal, you can manage them directly in the Menus page, or you can manage them as you create content.

1. From the Admin toolbar, click **Structure** then **Menus**. Here you will see several menus which make up each of the sections of our site
2. Click the **Edit** link next to the menu you wish to edit. You should see all the links that are part of that particular menu. One thing you can do is change the order in which they display within that menu by dragging links to the order you wish to display them.
3. If you click **Edit** next to any given link, you can change the label for the link as well as the url of the page the link is pointing to
4. Within the Menu edit page you can also disable individual links by clearing the **Enabled** checkbox
5. Save your changes after all changes are made



{% hint style="info" %}
When linking to an internal page, ensure you only include the page's slug rather than the entire site's URL.  For example:

**Use:** _/link-to-my-page_

**Avoid:** _https://www.uscourts.gov/link-to-my-page_
{% endhint %}
