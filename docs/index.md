# Welcome

This documentation details the SmartGlass protocol, used by the **Xbox One** gaming console family.

## Introduction

SmartGlass is a remote control protocol developed by Microsoft for their Xbox gaming system.
It was originally developed for the Xbox 360, where it relied on an active Xbox Live connection for
communication with the console. With the Xbox One it directly communicates over the local network.

In this documentation only the Xbox One variant of SmartGlass is documented.

## Browse the wiki

- [Basics](basics.md)
- [Cryptography](cryptography.md)
- [Simple Message](simple_message.md)
- [Message](message.md)
- [Channels](channels.md)
- [Nano Protocol](nano.md)

## Capabilities

Here is a rough overview about the capabilities of the SmartGlass protocol.

- Start games / apps via TitleID
- Controller input ([Input Channel](channels.md#input-channel))
- Media player control ([Media Channel](channels.md#media-channel))
- Text input ([Text Channel](channels.md#text-channel))
- Live TV streaming ([Stump Channel](channels.md#input-tv-remote-channel))
- Gamestreaming ([Broadcast Channel](channels.md#broadcast-channel) / [NANO](nano.md))
- and more...

## Related specifications

The following specifications share similarities with the Xbox specific protocols.

### SmartGlass protocol

- [MS-CDP: Connected Devices Platform](https://msdn.microsoft.com/en-us/library/mt766144.aspx)

### Nano protocol

- [MS-RDPEUDP: RDP:UDP TransportExtension](https://msdn.microsoft.com/en-us/library/hh536846.aspx)

## Disclaimer

Xbox, Xbox One, Smartglass and Xbox Live are trademarks of Microsoft Corporation.
Team OpenXbox is in no way endorsed by or affiliated with Microsoft Corporation, or any associated subsidiaries, logos or trademarks.
