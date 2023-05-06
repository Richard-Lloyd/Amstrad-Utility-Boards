# Amstrad-Utility-Boards
Various expansions for Amstrad CPC &amp; PCW computers
1. Amstrad CPC 50way PCB Edge to Pin/Socket Header Convertor

## 1. Amstrad CPC 50way PCB Edge to Pin/Socket Header Convertor
Work in progress.

Amstrad CPC expansion cards originally came with an edge connector to plug into the back of the computer. For a number of years now, backplane expanders have been available that accommodate pin/socket header connectors that are much more reliable. These are often known as 'Mother' or 'MX4' connectors. The PCB in this repository can be used to create adaptors to allow traditional cards with an edge connector to utilise one of the new backplane expanders. Also some cards, with an edge connector, don't allow through connections and prevent anything else being fitted. Adaptors made with this PCB can avoid these problems.

Please note.
1. The PCBs can be ordered (usually in batches of 10) from a number of manufacturers.
2. You will need to obtain suitable connectors and cable for the configurations you intend to build.
3. You will need soldering skills and the ability to 'crimp' IDC connectors for some of the configurations.
4. There are no electronic devices so these adaptors are easy to build.
5. The tracks that carry 5V and Ground are as wide as possible to allow for the currents involved.
6. Some cards may not work properly due to the extra resistance of the connectors and cable added by these adaptors. Because of this it is suggested that their use is limited to testing and temporary purposes.

![ACUB03 3 applications cropped 0300px](https://user-images.githubusercontent.com/68661647/236644518-c4704707-1bbb-412e-8b36-ce4ea67a2afd.jpg)

|Config No|Description|Notes|
|---|---|---|
| 1 | Direct MX4 | Used where the card edge connector is parallel to it's card and will sit vertically |
| 2 | Remote MX4 | Used where the card edge connector is at right angles to it's card or the card is bulky. A 50 way ribbon cable extension allows the card to be placed some distance from the MX4 connector. Can be used to connect the CPC464 Amstrad DDI-1 interface to an MX4 expansion backplane. |
| 3 | Remote to MX4 'through' | Uses the through connector on an expansion backplane as a card connector. Same user case as 2 but uses a female instead of a male connector. |

***Direct MX4.***

Top view, Bottom View, Installed with an M4 Card

![ACUB03-01 Direct - Top 0300px](https://user-images.githubusercontent.com/68661647/236644749-cc42edb5-dda6-46bd-81d9-f5679cd5622f.jpg)![ACUB03-02 Direct - Bottom 0300px](https://user-images.githubusercontent.com/68661647/236644757-02aa8e3f-3bca-4e5d-ab04-c9f020f8f763.jpg)![ACUB03-03 Direct - M4 0300px](https://user-images.githubusercontent.com/68661647/236644770-6ca4bd79-fa9c-4ea4-b6ea-f8b971fc4b91.jpg)

| Qty | Description of parts required|
|---|---|
| 1 | PCB |
| 1 |Boxed Connector Header, Through Hole, Right Angle 50 position 0.100" (2.54mm) such as Digikey 3M157291-ND [here](https://www.digikey.co.uk/en/products/detail/3m/30350-5002HB/1237406?s=N4IgTCBcDaIMwFkCMBWA7GAnEgtAOQBEQBdAXyA) |


