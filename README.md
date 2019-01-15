# VkProductSynchronizerInstruction
Instruction about what need do, that setting products synchronization between site and the social network «vk»

**Steps**
1. Create new application in VK;
1. Configure site and «vk» application;


## Create new application in VK
1. Authorize in social network;
1. Go here: https://vk.com/apps?act=manage;
1. Click on button with text «Create application» (text on button may differ, see [screenshot](screenshots/create-app-button.png));
1. In opened page enter some name for the application;
1. In field «Platform» choose option «Website»;
1. Click on button in bottom;
1. Finish, application was created.

## Configure site and «vk» application
1. Open main page of content management system (CMS) (simple append to domain name of site next string: `/-cms-/`);
1. Find in sidebar link «Synchronize products with VK» and click on it ([screenshot](screenshots/sync-products-button.png));
1. On top of page click on green button with text «Add»;
1. Open in other window page with successfully created application in social network «vk»;
1. In vk sidebar click on link «Settings»;
1. Copy from vk page value from field «Application ID» and insert it to field «Application identifier» of your site (this field in russian have name «Идентификатор приложения»);
1. Copy from vk page value from field «Secret key» and insert it to same name field of your site (this field in russian have name «Защищённый ключ»);
1. In the field «Community ID» of your site enter identifier you community in network «vk» (this field in russian have name «ID сообщества»);
1. Copy value from the field «Trusted redirect URI» of your site and instert it to same name field in vk (in russian: «Доверенный redirect URI»);
1. In «vk» set next fields:
1. Open API: enable;
  1. Site address («Open API» section): `your site address with protocol`;
  1. Base domain: `your domain name`;
  1. Site theme: `your theme`
1. In your site in field «Set category» («Установить категорию» in russain) enter the product category name from network «vk» (see hint of this field);
1. Click on button (in bottom of page) «Save and exit»;
1. Finish.
