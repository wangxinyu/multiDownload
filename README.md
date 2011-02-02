Plugin allows you to start multiple parallel downloads from page. 

First point links you want to download:
$('.my_links').multiDownload();

Then set triggering element and event type on which you want to start:
$('.my_download_trigger').multiDownload('click');

On $('.my_download_trigger') click all marked with multiDownload() links will open on sepatare "Save As" windows.

Important: All $('.my_links') elements must have defined "href" attribute. "href" must point to documents that generate proper HTML headers ("Content-Disposition: attachment; filename=my_filename").
