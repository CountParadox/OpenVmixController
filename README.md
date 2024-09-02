# OpenVmixController
Open Source Vmix Controller


Open source hardware and software for controlling vMix from a physical surface.

![vmix-controller](https://github.com/user-attachments/assets/68d7113e-0695-4a80-88d4-4fa6ff6a49ef)

KLE Link:

http://www.keyboard-layout-editor.com/#/gists/fcaade05215c99b7f5b90faef4c1ad29

<img width="870" alt="image" src="https://github.com/user-attachments/assets/6e4fca97-3814-44f7-822f-42d36bddf3da">



Parts:

3x 10k rotary potentiometer
1x rotary encover
1x 10k slide potentiometer
32x cherry compatible keyswitches
32x cherry compatible relegendable keycaps
1x microcontroller (TBC which type, prefer rp2040 but may have to be 32u4)


Software:

QMK Firmware Joystick support sounds the best! 
https://docs.qmk.fm/features/joystick


WIP Matrix Layout:

http://www.keyboard-layout-editor.com/##@_name=vMix%20Controller%20Matrix&author=CountParadox&notes=Kinda%20stole%20the%20layout%20from%20an%20aliexpress%20controller%20I%20dont%20want%20to%20pay%20for...%20%2F:)&background_name=Carbon%20fibre%204&style=background-image%2F:%20url('%2F%2Fbg%2F%2Fcarbonfibre%2F%2Fcarbon%2F_texture1873.png')%2F%3B%3B&switchMount=cherry&switchBrand=cherry&switchType=MX1A-G1Nx&plate:true%3B&@_y:0.25&x:0.5%3B&=A1%0A%0A%0A%0A%0A%0A%0A%0A%0APOT&_x:0.5%3B&=A2%0A%0A%0A%0A%0A%0A%0A%0A%0APOT&_x:0.5%3B&=A3%0A%0A%0A%0A%0A%0A%0A%0A%0APOT&_x:1%3B&=4,0%0A%0A4,2%0A%0A4,1%0A%0A%0A%0A%0AENC&_x:4&h:5.5%3B&=A0%0A%0A%0A%0A%0A%0A%0A%0A%0APOT&_x:0.5%3B&=0,4&_x:0.25%3B&=0,5&_x:0.25%3B&=0,6&_x:0.25%3B&=0,7%3B&@_y:-0.5&x:7.5%3B&=3,6&_x:0.25%3B&=3,7%3B&@_y:-0.25&x:12%3B&=1,4&_x:0.25%3B&=1,5&_x:0.25%3B&=1,6&_x:0.25%3B&=1,7%3B&@_y:0.5&x:13.25%3B&=2,4&_x:0.25%3B&=2,5%3B&@_y:-0.5%3B&=0,0&_x:0.25%3B&=0,1&_x:0.25%3B&=0,2&_x:0.25%3B&=0,3&_x:0.25%3B&=1,0&_x:0.25%3B&=1,1&_x:0.25%3B&=1,2&_x:0.25%3B&=1,3%3B&@_y:-0.25&x:13.25%3B&=2,6&_x:0.25%3B&=2,7%3B&@_y:-0.25%3B&=2,0&_x:0.25%3B&=2,1&_x:0.25%3B&=2,2&_x:0.25%3B&=2,3&_x:0.25%3B&=3,0&_x:0.25%3B&=3,1&_x:0.25%3B&=3,2&_x:0.25%3B&=3,3%3B&@_y:-0.75&x:12%3B&=3,4&_x:2.75%3B&=3,5




https://github.com/zykrah/firmware-scripts?tab=readme-ov-file
https://xelus.netlify.app/guides/kle_via_parser

switches only with matrix: 
[{y:0.25,x:5.5,a:1,f:2},"MI_G1\n\n\n\n0\n3",{x:5.5},"MI_E4\n\n\n\n0\n8",{x:0.25},"MI_F4\n\n\n\n0\n9",{x:0.25},"MI_G4\n\n\n\n0\n10",{x:0.25},"MI_A4\n\n\n\n0\n11"],
[{y:-0.5,x:7.5},"MI_E1\n\n\n\n0\n5",{x:0.25},"MI_F1\n\n\n\n0\n6"],
[{y:-0.5,x:5},"MI_A1\n\n\n\n0\n0\ne","MI_B1\n\n\n\n0\n1\ne"],
[{y:-0.75,x:12},"MI_B4\n\n\n\n1\n8",{x:0.25},"MI_C5\n\n\n\n1\n9",{x:0.25},"MI_D5\n\n\n\n1\n10",{x:0.25},"MI_E5\n\n\n\n1\n11"],
[{y:0.5,x:13.25},"MI_F5\n\n\n\n2\n9",{x:0.25},"MI_G5\n\n\n\n2\n10"],
[{y:-0.5},"MI_C2\n\n\n\n3\n0",{x:0.25},"MI_D2\n\n\n\n2\n1",{x:0.25},"MI_E2\n\n\n\n2\n2",{x:0.25},"MI_F2\n\n\n\n2\n3",{x:0.25},"MI_G2\n\n\n\n2\n4",{x:0.25},"MI_A2\n\n\n\n2\n5",{x:0.25},"MI_B2\n\n\n\n2\n6",{x:0.25},"MI_C3\n\n\n\n2\n7"],
[{y:-0.25,x:13.25},"MI_A5\n\n\n\n3\n9",{x:0.25},"MI_B5\n\n\n\n3\n10"],
[{y:-0.25},"MI_D3\n\n\n\n4\n0",{x:0.25},"MI_E3\n\n\n\n3\n1",{x:0.25},"MI_F3\n\n\n\n3\n2",{x:0.25},"MI_G3\n\n\n\n3\n3",{x:0.25},"MI_A3\n\n\n\n3\n4",{x:0.25},"MI_B3\n\n\n\n3\n5",{x:0.25},"MI_C4\n\n\n\n3\n6",{x:0.25},"MI_D4\n\n\n\n3\n7"],
[{y:-0.75,x:12,a:0},"\n\nu\n\n4\n8\n\n\nMI_C1",{x:2.75},"\n\nu\n\n4\n11\n\n\nMI_D1"]

