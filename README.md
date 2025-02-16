The Multiplier Structure include the 3 stages, they are 

1.𝐏𝐚𝐫𝐭𝐢𝐚𝐥 𝐩𝐫𝐨𝐝𝐮𝐜𝐭 𝐆𝐞𝐧𝐞𝐫𝐚𝐭𝐢𝐨𝐧 : Each bit of the multiplier is ANDed with the multiplicand, forming multiple rows of partial products.

2.𝐑𝐞𝐝𝐮𝐜𝐭𝐢𝐨𝐧 𝐔𝐬𝐢𝐧𝐠 𝐇𝐚𝐥𝐟 𝐚𝐧𝐝 𝐅𝐮𝐥𝐥 𝐀𝐝𝐝𝐞𝐫𝐬 : The partial products are reduced layer by layer using half adders and full adders in a tree-like structure, significantly reducing the carry propagation delay.

3.𝐅𝐢𝐧𝐚𝐥 𝐒𝐮𝐦𝐦𝐚𝐭𝐢𝐨𝐧 : The remaining bits are summed using a fast carry-propagate adder (such as a Carry Skip Adder).



𝔸𝕕𝕧𝕒𝕟𝕥𝕒𝕘𝕖𝕤 :

𝐇𝐢𝐠𝐡-𝐒𝐩𝐞𝐞𝐝 𝐂𝐨𝐦𝐩𝐮𝐭𝐚𝐭𝐢𝐨𝐧 : Parallel reduction minimizes the delay, making it faster than conventional array multipliers.

𝐎𝐩𝐭𝐢𝐦𝐢𝐳𝐞𝐝 𝐟𝐨𝐫 𝐕𝐋𝐒𝐈 𝐃𝐞𝐬𝐢𝐠𝐧 : Requires fewer logic gates and interconnects, leading to lower power consumption.

𝐒𝐜𝐚𝐥𝐚𝐛𝐢𝐥𝐢𝐭𝐲 : Can efficiently handle larger bit-width multiplications with minimal increase in delay.



𝔻𝕚𝕤𝕒𝕕𝕧𝕒𝕟𝕥𝕒𝕘𝕖𝕤 :

𝐂𝐨𝐦𝐩𝐥𝐞𝐱 𝐖𝐢𝐫𝐢𝐧𝐠 : The tree-like structure introduces routing complexity in hardware implementations.

𝐇𝐢𝐠𝐡 𝐏𝐨𝐰𝐞𝐫 𝐃𝐢𝐬𝐬𝐢𝐩𝐚𝐭𝐢𝐨𝐧 : Due to the increased number of logic gates and switching activities, the Wallace Tree Multiplier consumes more power compared to simpler multipliers.

𝐇𝐢𝐠𝐡𝐞𝐫 𝐀𝐫𝐞𝐚 𝐑𝐞𝐪𝐮𝐢𝐫𝐞𝐦𝐞𝐧𝐭 : More adders and interconnects lead to increased hardware resource utilization.
