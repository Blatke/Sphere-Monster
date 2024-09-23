# Sphere Monster
A HS2 / AIS Studio Item for monster.

## How to Use
Download the .zipmod file for the latest version on the [Release](https://github.com/Blatke/Sphere-Monster/releases) page, and drag and drop it into your ***/mods/*** folder or use KKManager to install this mod.

In Studio, search for "sphere monster" in QuickAccessBox and add it in the scene.

Enable the adv.mode of HS2PE / AIPE, on the tab of Bones, there are two categories of bones to manipulate:
1. The bones prefixed by "C", which mainly control the rotation (as well as position) for the monster's poses. Each bone is linked with one another, so when a parent such as "C1" is transforming (moving, rotating or scaling), its children C2, C3, C4 and C5 will follow it.

![image](https://github.com/user-attachments/assets/39c74fcb-d38b-4e4e-a782-bf7d679a0832)

2. The bones prefixed by "D", which are mainly the deformers for the monster's mesh. The bones prefixed by "DN_", such as D1_01, are separated from each other, so the transforms in one of them will not affect the rests. 

![image](https://github.com/user-attachments/assets/17ab9fec-da15-4ef1-8497-bb08c3a47ec8)

Their parents, D1, D2, D3, D4 and D5, can batch affect them when the former ones are transforming, and are parented respectively to C1, C2, C3, C4 and C5.

![image](https://github.com/user-attachments/assets/e895b44e-d605-4afb-a1c9-d2bc463fd8eb)

On the tab, you can search for "C" or "D" to get the corresponding bones and make them transform.

Of course you can also enable FK function to directly rotate the FK nodes of the monster.
