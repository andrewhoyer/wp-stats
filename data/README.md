# WP Stats Data

This folder contains the data files in CSV format.

## Download file sizes

The data for the download size of WordPress releases is contained in the `wp-download-file-sizes.png` file. It contains the following columns, with all sizes noted in MB:

* **Version**. The version of WordPress.
* **File size**. The file size of the download (zip).
* **File size change**. The difference in size from the previous version.
* **Themes size**. The file size of the themes folder (zip).
* **File size without themes**. The file size without the themes folder (zip).

## Days between releases

The data for the number of days since the previous release is contained in the `wp-days-since-release.csv` file. It contains the following columns:

* **Version**. The version of WordPress.
* **Release Date**. The date the version was released.
* **Days since last release**. The number of days between this release and the previous one.

## Plugins in the review queue

The data for the number of plugins in the WordPress review queue is contained in the `wp-review-queue.csv` file. It contains the following columns:

* **Date**. The date the value was recorded on.
* **Plugins in Queue**. The number of plugins in the queue as reported on the [WordPress plugin developer page](https://wordpress.org/plugins/developers/add/).
* **Notes**. Specific notes that help identify or interpret important data points.

Historically, the estimated wait for review was displayed, but recently its availability is very inconsistent, and as a results is not recorded here.
