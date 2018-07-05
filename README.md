# geturls

Extact all URLs from anchor and image tags within a html/xhtml page and its children.

Relative paths are prefixed with the root of the URL provided, i.e. full URLs are provided in all cases.

The URL provided must point to a file, so that this script can recursively obtain all the linked URLs.

## Usage
Simply provide the URL of the page you would like to get URLs from, e.g.:

`geturls https://www.openbookpublishers.com/htmlreader/978-1-78374-388-9/main.html`

The main purpose of this script at OBP is to obtain all URLs needed to display our html books properly so that these can be submitted to the [Wayback Machine](https://archive.org/web/web.php).
