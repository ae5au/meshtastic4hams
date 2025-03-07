# meshtastic4hams
Presentation on Meshtastic geared toward amateur radio operators

## What is Meshtastic? TODO:SCREENSHOT
An open source, off-grid, decentralized, mesh network built to run on affordable, low-power devices.

* Open source
    * Code is freely available
* Off grid, decentralized
    * Doesn't depend on the internet, a central server, registry, etc.
    * Can be stood up in the middle of nowhere with no connection to an existing network.
* Mesh network
    * Wikipedia: A mesh network is a network topology in which the nodes connect directly, dynamically and non-hierarchically to as many other nodes as possible and cooperate with one another to efficiently route data to and from clients.
    * Maybe a stretch, but basically the focus is that most nodes contribute to extending the network and it can function without much planning.
* Affordable devices TODO:IMAGE
    * Devices range from $20 ~ $100.
    * Many options for 3D printed cases and DIY builds.
    * Also options for hardware that is ready out-of-the-box.

## What else?
That's a good one-liner, but what does it not answer?

* Text-based communications - APRS-like
    * Direct & group messaging.
    * Position and telemetry reporting
    * Bots and some others
    * NOT voice, video, or browsing the web.
    * Different than APRS in that nodes by default repeat traffic like a digi
* Mostly unlicensed ISM bands - 900MHz in US
* LoRa - "long range"
    * CSS - Chirp Spread Spectrum  TODO:IMAGE
        * SS, but not really wide-banded.
    * Similar to FT8 in working below noise floor.
    * Focus on distance over speed

## Why Meshtastic?
* Keep in touch
* Comm plan for emergencies
* Fun

## Where?
* Neighborhood
* Outdoor activities
* Metro or larger area

## How? - Get Device
* Show various hardware options - TODO:IMAGES
* Discuss phone app and how app/node relationship works. - TODO:IMAGES
    * Phone app doesn't require internet or Wi-Fi
* Node options
    * nRF52840 Battery / solar
    * ESP32 - Wi-Fi
    * PA / LNA options

## How? - Setup Device
* Buy/build node
    * https://meshtastic.org/docs/hardware/devices/
* Flash firmware
    * Chrome - https://flasher.meshtastic.org/
* Tips
    * Use defaults first, customize later
    * Set long and short names. Leave channels alone at first.
    * Don't use licensed mode
    * Maybe info on what (not) to do, etc.
* Remote management
    * Can't upgrade firmware over network or LoRa
    * Consider how to maintain remote nodes
    * Setting management using admin keys

## Other
* LoRa-APRS and other similar things
