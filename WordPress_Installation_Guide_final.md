**WordPress CMS Installation & Configuration Guide**

# **Instructions for Setting Up a Simple** **CMS**

### Systems for managing content (WordPress)

## **Overview**


More than 40% of websites on the internet are today powered by WordPress, an opensource content management system. This comprehensive user manual will help you set
up and configure a WordPress CMS-powered website.

## **Requirements**

1. Before installation starts, make sure the following conditions are satisfied:


2. central processing unit running Linux, macOS, or Windows


3. Internet access


4. Local server configuration (such as XAMPP or WAMP) or web hosting plan


5. If you plan to use hosting, a domain name


6. Only manual installations require an FTP client (FileZilla, Cute FTP, etc.).


**WordPress CMS Installation & Configuration Guide**

## **Phase 1: Setting Up the Server** **Option A: Using XAMPP to Install WordPress Locally**

The local Apache, MySQL, and PHP environment that XAMPP offers on your
computer is perfect for testing and development.
To download XAMPP, go to https://www.apachefriends.org/download.html.
2. Get XAMPP and set it up on your PC.
3. Open the XAMPP control panel and hit "Start" in opposition to MySQL and


_Figure 1: XAMPP Control Panel displaying services Apache and MySQL in_

_‘running’ mode._


4. Use your browser to explore your machine and visit http://localhost to see if the
server is operational.


**WordPress CMS Installation & Configuration Guide**

#### **Live Web Hosting is Option B.**

You would need a hosting account if you wanted others to be able to view your website
online.


5. Choose a hosting provider that supports MySQL and PHP 7.4+ (Bluehost,
SiteGround, or HostGator).


6. In the DNS management section, enter your domain name and connect it to your
hosting account.


7. Open your hosting control panel (cPanel) and log in.

## **Creating a MySQL Database in Phase Two**

For the WordPress website, which houses all the data and content, a MySQL
database needs to be created.

8. Launch phpMyAdmin. Go to http://localhost/phpmyadmin on XAMPP, and use
your cPanel to access PHP. MyAdmin on a live hosting server.
9. Click on the Databases tab.
10. Click the Create button after entering a database name under Create Database.


_Figure 2: Using phpMyAdmin, create a new database named "wordpress_db."_


**WordPress CMS Installation & Configuration Guide**


11. After selecting User Accounts, select "Add User Account."
12. Enter your password and username. In the area labeled "Database for user,"
choose the previously created database and provide all privileges.

#### _Figure 3: Configuring User Permissions to grant “All Permissions.”_


13. To save the configuration, click Go. Keep your password, username, and database
name safe.


**WordPress CMS Installation & Configuration Guide**

## **Phase 3: WordPress installation**

14. To obtain the most recent version of WordPress (a zip file), visit
https://wordpress.org/download.
15. Open the downloaded file by unzipping it. The WordPress folder will be
visible to you.


_Figure 4: WordPress 6.9.4 Configuration_


16. Transfer the files that were extracted to:

   - Local (XAMPP): C:\xampp\htdocs\your-site-name

    - Live Hosting: Use an FTP application or file manager to upload the files to the
public_html folder.

#### **Running the Installation Script for WordPress**

17. Open the web browser.
Visit http://yourdomain.com (live) or http://localhost/your-site-name (local).
18. Click Continue after selecting a language.
19. Select "Let us get started."
20. Enter the database host (localhost by default), username, password, and database
name. Press the "Submit" button.
21. Click Install WordPress once the connection has been established.
22. Enter your email address, password, admin username, and website name. Select
"Install WordPress."
23. To access the WordPress administration page, click Login once the procedure is
finished.


**WordPress CMS Installation & Configuration Guide**

## **Phase 4: Fundamental Setup**

#### **Step 1: General Preferences**

24. Use your administrator credentials to log in to http://yourdomain.com/wp-admin.
25. In the menu bar on the left, select Settings > General.
26. Configure your website title, slogan, time zone, and date format.
27. Click the "Save Changes" button.

#### **Step 2 — Permalinks**

28. Go to Settings > Permalinks.
29. Choose "Post name" for your website's permalink structure.
30. Save your modifications.

#### **Step 3: Setting Up a Theme**

31. From the sidebar menu, select Appearance > Themes.
32. Select "Add New" and look for a theme (such as Twenty Twenty-Four, OceanWP, or
Astra) using the search field.
33. After choosing a theme, mouse over it and select "Install" and "Activate."

#### **Step 4 — Setting Up Necessary Plugins**

34. Go to Plugins > Add New.
35. Look for and set up the following plugins:

- Yoast SEO Plugin: for search engine optimization of your website

- Wordfence Security Plugin: for malware and firewall checks

- The UpdraftPlus Plugin, which automatically backs up your website

- WP Super Cache Plugin: to enhance the functionality of your website
36. Select "Install Now" and then "Activate."

## **Phase 5: Creating Your First Website and Posting** **Your First Article**

#### **Constructing a Website**

37. Go to Pages > Add New in the Dashboard.
38. Enter the title of your page (such as "About Us") in the Title area.
39. Tap the + symbol to add material using the Gutenberg blocks editor.


**WordPress CMS Installation & Configuration Guide**


40. Click Publish once you are done.

#### **Making a Post**

41. Select Posts > Add New.
42. Add the title and body of your post.
43. From the panel on the right, select a category and add a few tags.
44. From the menu in the sidebar on the right, choose your feature image.
45. Press the "Publish" button.

## **Typical Mistakes & Solutions**

- Database connection establishment error: Please review the database details in the
wp-config.php file.

- White screen of death: Using the FTP manager, rename the /wp-content/plugins
directory to temporarily disable all plugins.

- 404 error on pages: Use the Settings > Permalinks menu to adjust your permalinks.

- Issues with media uploads: Verify the /wp-content/uploads folder's permission settings.

## **Conclusion**

A WordPress content management system has been successfully established. With
your theme chosen and the required plugins activated, your website is now completely
operational. You can now investigate additional areas like adding new plugins, making
menus, and altering your WordPress theme.


