## Gallery of Datasets from Self-Driving Vehicles

This repository contains Docker-encapsulated datasets and OpenDLV-powered
replay/visualization environments for replay in modern web-browsers.

List of available datasets:

* [comma.ai/2016-06-08 11:46:01](https://archive.org/details/comma-dataset) - [docker-compose.yml](https://raw.githubusercontent.com/chalmers-revere/opendlv-gallery/master/comma.ai-2016-06-08_114601.yml) - online replay with [Play-with-Docker](https://labs.play-with-docker.com/#):
    1. Start [Play-with-Docker](https://labs.play-with-docker.com/#) instance.
    2. Create a new node.
    3. Download the correspondig [docker-compose.yml](https://raw.githubusercontent.com/chalmers-revere/opendlv-gallery/master/comma.ai-2016-06-08_114601.yml): wget https://raw.githubusercontent.com/chalmers-revere/opendlv-gallery/master/comma.ai-2016-06-08_114601.yml
    4. Start replay: docker-compose -f comma.ai-2016-06-08_114601.yml up
    5. Click on the new button :8080 appearing in the upper part of Play-with-Docker.
