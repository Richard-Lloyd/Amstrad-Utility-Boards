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

***Configuration 1 - Direct MX4.***

Top view, Bottom View, Installed with an M4 Card

![ACUB03-01 Direct - Top 0250px](https://user-images.githubusercontent.com/68661647/236645966-68d4789b-f4f9-4ccf-b1c6-4392ce2b5636.jpg)![ACUB03-02 Direct - Bottom 0250px](https://user-images.githubusercontent.com/68661647/236645976-0f68b3fe-ff6c-4017-af9f-2db338988cec.jpg)![ACUB03-03 Direct - M4 0250px](https://user-images.githubusercontent.com/68661647/236645982-0cf11acc-0293-4b94-8a06-b5337f82d0c7.jpg)

This configuration allows suitable cards to sit in the 'normal' orientation on a backplane expander such as revaldinho's self-build cards [here](https://github.com/revaldinho/cpc_ram_expansion/wiki/CPC-Expansion-Backplane). If your card has a PCB edge connector that is at right angles - see the next configuration. If you choose to use an 'unboxed' connector, you must ensure that it is connected to the backplane the correct way round!

| Qty | Description of parts required|
|---|---|
| 1 | PCB |
| 1 |Boxed Connector Header, Through Hole, Right Angle 50 position 0.100" (2.54mm) such as Digikey 3M157291-ND [here](https://www.digikey.co.uk/en/products/detail/3m/30350-5002HB/1237406?s=N4IgTCBcDaIMwFkCMBWA7GAnEgtAOQBEQBdAXyA) |

Build instructions. Place the box header connector on side 'A' of the PCB. Ensure that it is square with the board and solder on side 'B'. First solder the two end pins on one row and adjust the orientation of the connector (if necessary) before soldering the rest of the pins.


***Configuration 2 - Remote MX4.***

Top view, Bottom View, Installed with Amstrad CPC464 DDI-1 disc interface lying 'flat'.

![ACUB03-04 Remote - Top 0250px](https://user-images.githubusercontent.com/68661647/236801858-bf6a7499-16be-402d-bd9a-43dfbea2d7d7.jpg)![ACUB03-05 Remote - Bottom 0250px](https://user-images.githubusercontent.com/68661647/236801885-0dc35cd9-6af1-4590-b615-7658b8798d46.jpg)![ACUB03-06 Remote - DDI-1 0250px](https://user-images.githubusercontent.com/68661647/236801919-3eab38f5-8e79-4e69-8559-1dfed11ef897.jpg)

This configuration allows PCB Edge cards to connect to a backplane expander using a ribbon cable. It is advised to keep the ribbon cable as short as possible. In the photo above, it is shown connecting a DDI-1 disc interface to a backplane expander on a CPC464. This particular interface is bulky and does not have a through connector so connecting it to the rearmost MX4 connection allows it to lie flat on the desk and keep the ribbon cable short. The ribbon cable also provides some isolation from movement of the backplane expander. Trying to connect the DDI-1 to the through edge connector on the expansion card is problematic as the card and interface have to be securely supported.

