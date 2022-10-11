# Automated Ship Detection using ArcGIS.learn and Copernicus Hub Sentinel-1

This notebook automates the process of downloading Sentinel-1 imagery from Copernicus hub and running Ship Detection against the images.

The notebook uses an ArcGIS feature service with collection targets to query Copernicus daily and then applies the ArcGIS Living Atlas ship detection FasterRCNN model against the images (https://www.arcgis.com/home/item.html?id=705f4c04ac3043be806529047b79abfd). The detections are then stored in a feature service.

This notebook also includes the logic to upload the downloaded images to a S3 bucket, update a mosaic dataset stored in a SDE for an Image Service, and updates a layer of the footprints of collections.

![alt text](https://github.com/phornstein/ArcGIS-Notebooks-Samples/blob/main/(Analysis)%20Automated%20Ship%20Detection/dashboard.JPG?raw=true)
