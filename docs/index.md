Evelution is a Next Gen Skin for MediaWiki. Designed to improve reading has four different thems that you can use them on a page-basis. With the inclusion of a Dark Mode, you can read pages with fewer eye stress.

With the inclusion of Sticky sidebars and Sticky Community Header, you can have many of the known tools MediaWiki following you.

Evelution Desktop Skin in three different main Breakpoint Sizes, 705px, 1280px & 1500px. It is maintained by Qora Qore Telecommunities, A Techno Services and all other CPE Evelution Developers

You can read more about the skin [here](Overview.md)

# Requirements
To Run Evelution on your wiki, you must have MediaWiki 1.36 or greater. Older versions are not supported

# Installation
To Install Evelution, you must download the reposistory first. Make a folder called **Evelution** in **Skins** diractory where you have installed MediaWiki and extract the zipped file contents in **Evelution** folder.  Lastly, put this in **LocalSettings.php**:
```php
wfLoadSkin( 'Evelution' );
```

# Translating Evelution
Fork this repo, add a new language code to the i18n folder (Such as fr.php). Copy all contents from en.php to xxx.php (Such as fr.php) and then translate them to the corresponding language (For fr.php should be in French). Then send up a PR and I will be happy to merge it.