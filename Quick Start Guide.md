# Quickstart guide

# Context

A month ago, I bought a WordPress.org theme from Etsy. My purchase came with a comprehensive installation guide, which was a bit difficult to follow and too detailed for my needs.

At the time, I only needed a quick guide that would help me get started with my blog in no time. Despite being elaborate, the installation guide skipped many prerequisite steps, 
so I had to look for external resources. The writer of the theme documentation probably assumed that the user was already familiar with WordPress. 
In my case, I had only started working on my website.

The issues I encountered prompted me to create this document.

In this quickstart guide, I aim to:

1. Cover the pre-installation procedures,

2. Make the instructions easy to follow even for non-tech savvy users, and

3. Opt for the most straightforward method, particularly for steps that can be done in multiple ways.

## Target Audience

The target audience of this quickstart guide is non-technical people installing a WordPress.org theme for the first time. 
The users are unfamiliar with WordPress and only need the bare minimum from the theme.

# 📝 Quickstart Guide for the Ethereal Glow WordPress.org Theme

The Ethereal Glow WordPress Theme provides the ultimate blogging and design solution for your needs. This theme is beautiful, professional, easily customizable, and packed 
with several features. It's also available in multiple languages, compatible with different plugins, and SEO-optimizable.

Before getting started, you must first install WordPress.org on your computer.

After installing WordPress, you must complete the steps below.

1. Download the theme from Etsy.
2. Update your site's .htaccess file.
3. Upload the theme to WordPress.

## Step 1: Download the Theme from Etsy.

**Procedure**

1. Log in to your Etsy account.
2. Click your profile picture in the upper right corner of the page. Select **Purchases and reviews** from the dropdown box.
3. Locate the Ethereal Glow WordPress theme. Select **Download Files** on the right side of your order. 
   This opens a new page.
4. Navigate to the bottom of the Download page. 
5. Click **Download** to download all available files.

## Step 2: Update your Site's .htaccess File
The WordPress .htaccess file is a powerful configuration file. 
It contains commands that control and configure how the server runs your website.

###Procedure

1. Log in to your WordPress **cPanel**.
2. Scroll down the page and locate the **Files** section.
3. Under the Files section, select File Manager.
   This opens a new page.
4. In the File Manager, find the search bar in the upper right corner of the page. 
5. Type **.htaccess** in the search bar. 
6. Press **Enter** to initiate the search.
   The search results pop-up screen should appear on the page. 
6. Double-click /public_html/.access. 
   It returns you to the File Manager or the previous page.
7. Right-click on the **.htaccess** file, and choose **Edit**. 
   A pop-up screen will appear. 
8. Click **Edit** to proceed.
7. Add the following code to the end of the file.
  
  ```
  php_value post_max_size 64M  
  php_value upload_max_filesize 128M  
  php_value max_file_uploads 128M  
  php_value max_input_vars 5000
  ```

8. Click **Save Changes**.

## Step 3: Upload the Theme to WordPress.

You can upload the Ethereal Glow theme via WordPress or FTP. 
For this guide, you'll be uploading the theme via the WordPress admin panel.

### Procedure
1. Log in to your WordPress.org account.
2. On the left sidebar, select **Appearance > Themes**.
3. Choose **Add New**.
4. Choose **Upload Theme**.
   This displays a new page section.
5. Click **Choose file**.
6. Navigate to the folder where you downloaded your Ethereal Glow theme and select the **ethereal-glow.zip** file.
7. After choosing the file, click **Install Now**.
8. Once the theme has been successfully installed, click **Activate**.

[!CAUTION]
Make sure you choose the theme archive–ethereal-glow.zip–and not the other .zip files you downloaded.

**Next Steps
Once you are done with the prerequisite steps, you can start setting up and customizing your new theme, which includes:

* Adding plugins
* Setting up WooCommerce
* Uploading demo content
* Customizing the appearance of the theme
* Updating the header, footer, logo, and favicon
* Setting up the menu
* Adding widgets
* Adding pages and blog posts