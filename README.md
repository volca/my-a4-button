# a4 button #

This repo serves as a template for creating a new ESPHome project.

It includes a GitHub workflow that will automatically build the configuration(s) and then deploys a simple 
website via GitHub pages that utilises [ESP Web Tools](https://esphome.github.io/esp-web-tools/) for users to 
easily install your project onto their device.

## Instructions

1. Use this repo template to [generate](https://github.com/esphome/esphome-project-template/generate) your own repository.
1. Browser to the file `secrets.yaml`, click `Edit this file`
   * Modify `wifi_ssid` and `wifi_pass`
   * Modify `mqtt_broker`
   * Click `Commit changes...`
1. Click `Actions` and wait the build finish
1. Click the latest workflow and browse to the bottom of the page, it should show `Artifacts` which contains the compi
led firmware files. Download the file and unzip the file. It should contains the `ota.bin` file.

