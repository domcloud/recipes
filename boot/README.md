[deploy]: https://img.shields.io/badge/Deploy%20now%20-blue?style=flat-square
[recipe]: https://img.shields.io/badge/See%20recipe%20-darkviolet?style=flat-square
[website]: https://img.shields.io/badge/See%20website-darkgreen?style=flat-square
[source]: https://img.shields.io/badge/See%20source-dimgrey?style=flat-square
[php]: https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white
[node]: https://img.shields.io/badge/Node.js-43853D?style=flat-square&logo=node.js&logoColor=white
[python]: https://img.shields.io/badge/Python-14354C?style=flat-square&logo=python&logoColor=white
[ruby]: https://img.shields.io/badge/Ruby-CC342D?style=flat-square&logo=ruby&logoColor=white
[untested]: https://img.shields.io/badge/Untested-red?style=flat-square&logoColor=white
[lite_plan]: https://img.shields.io/badge/require%20plan-LITE-gold?style=flat-square&logoColor=white

# List of Boot-From-Stratch Recipes

These are lists of recipes that proven to work on DOM Cloud, in no particular order. 

These recipes includes framework or open-source software that can be self-hosted. If an authentication / admin user is created automatically within the recipe, it defaults to `admin@` + domain name with password equal to host password.

## General Framework / Static Site Generators

| Name  | Runtime | Deploy Now | See Recipe |
|---|---|---|---|
| CodeIgniter 4 | ![php] | [↗️](https://my.domcloud.co/start?from=https://raw.githubusercontent.com/domcloud/dom-templates/master/boot/codeigniter.yml) | [📜](./codeigniter.yml)
| CodeIgniter 3 | ![php] | [↗️](https://my.domcloud.co/start?from=https://raw.githubusercontent.com/domcloud/dom-templates/master/boot/codeigniter3.yml) | [📜](./codeigniter3.yml)
| CakePHP | ![php] | [↗️](https://my.domcloud.co/start?from=https://raw.githubusercontent.com/domcloud/dom-templates/master/boot/cakephp.yml) | [📜](./cakephp.yml)
| Laravel | ![php] | [↗️](https://my.domcloud.co/start?from=https://raw.githubusercontent.com/domcloud/dom-templates/master/boot/laravel.yml) | [📜](./laravel.yml)
| Create React App | ![node] | [↗️](https://my.domcloud.co/start?from=https://raw.githubusercontent.com/domcloud/dom-templates/master/boot/cra.yml) | [📜](./cra.yml)
| Express | ![node] | [↗️](https://my.domcloud.co/start?from=https://raw.githubusercontent.com/domcloud/dom-templates/master/boot/express.yml) | [📜](./express.yml)
| Nest.js | ![node] | [↗️](https://my.domcloud.co/start?from=https://raw.githubusercontent.com/domcloud/dom-templates/master/boot/nestjs.yml) | [📜](./nestjs.yml)
| Next.js | ![node] | [↗️](https://my.domcloud.co/start?from=https://raw.githubusercontent.com/domcloud/dom-templates/master/boot/nextjs.yml) | [📜](./nextjs.yml)
| Nuxt.js | ![node] | [↗️](https://my.domcloud.co/start?from=https://raw.githubusercontent.com/domcloud/dom-templates/master/boot/nuxtjs.yml) | [📜](./nuxts.yml)
| SvelteKit | ![node] | [↗️](https://my.domcloud.co/start?from=https://raw.githubusercontent.com/domcloud/dom-templates/master/boot/sveltekit.yml) | [📜](./sveltekit.yml)
| Flask | ![python] | [↗️](https://my.domcloud.co/start?from=https://raw.githubusercontent.com/domcloud/dom-templates/master/boot/flask.yml) | [📜](./flask.yml)
| Django | ![python] | [↗️](https://my.domcloud.co/start?from=https://raw.githubusercontent.com/domcloud/dom-templates/master/boot/django.yml) | [📜](./django.yml)
| Ruby on Rails | ![ruby] | [↗️](https://my.domcloud.co/start?from=https://raw.githubusercontent.com/domcloud/dom-templates/master/boot/rails.yml) | [📜](./rails.yml)
| Jekyll | ![ruby] | [↗️](https://my.domcloud.co/start?from=https://raw.githubusercontent.com/domcloud/dom-templates/master/boot/jekyl.yml) | [📜](./jekyll.yml)

## CMS / CMF / Blogging / Ecommerce

+ **WordPress**  
  World’s most-used blogging and CMS engine.

  ![php] [![deploy]](https://my.domcloud.co/start?from=https://raw.githubusercontent.com/domcloud/dom-templates/master/boot/wordpress.yml) [![recipe]](./wordpress.yml) [![website]](https://wordpress.org) [![source]](https://github.com/WordPress/wordpress-develop)

+ **WooCommerce**  
  WordPress based e-commerce solution.

  ![php] [![deploy]](https://my.domcloud.co/start?from=https://raw.githubusercontent.com/domcloud/dom-templates/master/boot/woocommerce.yml) [![recipe]](./wordpress.yml) [![website]](https://woo.com) [![source]](https://github.com/woocommerce/woocommerce)

+ **Drupal**  
  Advanced open source content management platform.

  ![php] [![deploy]](https://my.domcloud.co/start?from=https://raw.githubusercontent.com/domcloud/dom-templates/master/boot/drupal.yml) [![recipe]](./drupal.yml) [![website]](https://drupal.org/) [![source]](https://git.drupalcode.org/project/drupal)

+ **Magento**  
  Leading provider of open omnichannel innovation.

  ![php] [![deploy]](https://my.domcloud.co/start?from=https://raw.githubusercontent.com/domcloud/dom-templates/master/boot/magento.yml) [![recipe]](./magento.yml) [![website]](https://business.adobe.com/products/magento/open-source.html) [![source]](https://github.com/magento/magento2)

+ **Bagisto**  
  Leading Laravel open source e-commerce framework with multi-inventory sources, taxation, localization, dropshipping and more exciting features.

  ![php] [![deploy]](https://my.domcloud.co/start?from=https://raw.githubusercontent.com/domcloud/dom-templates/master/boot/bagisto.yml) [![recipe]](./bagisto.yml) [![website]](https://bagisto.com/) [![source]](https://github.com/bagisto/bagisto/)

+ **QloApps**  
  https://qloapps.com/

+ **Ghost**  
  Independent technology for modern publishing, memberships, subscriptions and newsletters.

  ![node] [![deploy]](https://my.domcloud.co/start?from=https://raw.githubusercontent.com/domcloud/dom-templates/master/boot/ghost.yml) [![recipe]](./ghost.yml) [![website]](https://ghost.org/) [![source]](https://github.com/TryGhost/Ghost)

+ **Strapi**  
  The most advanced open-source Content Management Framework (headless-CMS) to build powerful API with no effort.

  ![node] [![deploy]](https://my.domcloud.co/start?from=https://raw.githubusercontent.com/domcloud/dom-templates/master/boot/strapi.yml) [![recipe]](./strapi.yml) [![website]](https://strapi.io/) [![source]](https://github.com/strapi/strapi)

+ **Medusa.js** ![untested]  
  Open-source headless commerce engine that enables developers to create amazing digital commerce experiences.
  
  ![node] [![deploy]](https://my.domcloud.co/start?from=https://raw.githubusercontent.com/domcloud/dom-templates/master/boot/medusajs.yml) [![recipe]](./medusajs.yml) [![website]](https://medusajs.com/) [![source]](https://github.com/medusajs/medusa)

+ **Payload CMS**  
  https://payloadcms.com/

+ **Wagtail**  
  Django content management system focused on flexibility and user experience.

  ![python] [![deploy]](https://my.domcloud.co/start?from=https://raw.githubusercontent.com/domcloud/dom-templates/master/boot/wagtail.yml) [![recipe]](./wagtail.yml) [![website]](https://wagtail.io/) [![source]](https://github.com/wagtail/wagtail)

+ **Saleor**  
  https://saleor.io/

+ **Spree Commerce**  
  https://spreecommerce.org/

## Collaboration / Forum / Administration Software

+ **Flarum**  
  Simple forum software for building great communities.

  ![php] [![deploy]](https://my.domcloud.co/start?from=https://raw.githubusercontent.com/domcloud/dom-templates/master/boot/flarum.yml) [![recipe]](./flarum.yml) [![website]](https://flarum.org/) [![source]](https://github.com/flarum/flarum)

+ **Open Journal System**  
  Open source software to manage scholarly journals.

  ![php] [![deploy]](https://my.domcloud.co/start?from=https://raw.githubusercontent.com/domcloud/dom-templates/master/boot/ojs.yml) [![recipe]](./ojs.yml) [![website]](https://pkp.sfu.ca/software/ojs) [![source]](https://github.com/pkp/ojs)

+ **Cal.com** ![untested]  
  The open-source online appointment scheduling system.

  ![node] [![deploy]](https://my.domcloud.co/start?from=https://raw.githubusercontent.com/domcloud/dom-templates/master/boot/calcom.yml) [![recipe]](./calcom.yml) [![website]](https://cal.com/) [![source]]( https://github.com/calcom/cal.com)

+ **Linkwarden** ![untested] ![lite_plan]  
  A self-hosted bookmark + archive manager to store your useful links.
   
  ![node] [![deploy]](https://my.domcloud.co/start?from=https://raw.githubusercontent.com/domcloud/dom-templates/master/boot/linkwarden.yml) [![recipe]](./linkwarden.yml) [![website]](https://linkwarden.app/) [![source]](https://github.com/linkwarden/linkwarden)

+ **Chatwoot**  
  https://www.chatwoot.com/

+ **Mattermost**  
  https://mattermost.com/

+ **Rocket.Chat**  
  https://www.rocket.chat/

+ **Zulip**  
  https://zulip.com/

+ **Moodle**   
  Learning and courses platform with one of the largest open source communities worldwide.

  ![node] [![deploy]](https://my.domcloud.co/start?from=https://raw.githubusercontent.com/domcloud/dom-templates/master/boot/moodle.yml) [![recipe]](./moodle.yml) [![website]](https://moodle.org/) [![source]](https://git.in.moodle.com/moodle/moodle)

+ **Canvas**  
  https://www.instructure.com/canvas

+ **Fider**  
  https://fider.io/

+ **Limesurvey**  
  https://limesurvey.org/

## Office / Memo / Document Software

+ **InvoiceNinja**  
  https://www.instructure.com/canvas

+ **Paperless-Ngx**  
  https://docs.paperless-ngx.com/

+ **Joplin App**  
  https://joplinapp.org/

+ **UseMemos**  
  https://www.usememos.com/

+ **Grist**  
  https://getgrist.com/

+ **ERPNext**  
  https://erpnext.com/

## Developer Tools

+ **Directus**  
  An Instant App & API for your SQL Database.

  ![node] [![deploy]](https://my.domcloud.co/start?from=https://raw.githubusercontent.com/domcloud/dom-templates/master/boot/flarum.yml) [![recipe]](./flarum.yml) [![website]](https://directus.io/) [![source]](https://github.com/directus/directus)
  
+ **Jupyter Notebook**  
  The classic web-based interactive computing platform.

  ![python] [![deploy]](https://my.domcloud.co/start?from=https://raw.githubusercontent.com/domcloud/dom-templates/master/boot/jupyter.yml) [![recipe]](./jupyter.yml) [![website]](https://jupyter.org/) [![source]](https://github.com/jupyter/notebook)

+ **ArchiveBox**  
  https://archivebox.io/

+ **ChangeDetection.io**  
  https://changedetection.io/

+ **Novu**  
  https://novu.co/

+ **Ntfy.sh**  
  https://ntfy.sh/

+ **NocoDB**  
  https://www.nocodb.com/

+ **OpenSearch**  
  https://opensearch.org/

+ **Meilisearch**  
  https://meilisearch.com/

+ **PocketBase**  
  https://pocketbase.io/

+ **Appflowy**  
  https://appflowy.io/

+ **Focalboard**  
  https://focalboard.com/

+ **Yourls**  
  https://yourls.org/

+ **Weblate**  
  https://weblate.org/
