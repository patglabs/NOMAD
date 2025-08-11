# NOMAD
A laptop designed to be customisable, portable and open source

if you're in the hc slack make sure to join #pats-basement

## In brief:
Nomad is a laptop ive designed and am designing that features a lattepanda mu n100 at its center which handles all the compute. It uses a custom mainboard pcb that I designed to have 2 usb 3 type A ports exposed to the outside,
1 usb c 2.0 and 1 internal usb 2.0 which will go into an internal usb hub so that i can put an rtl sdr inside the laptop so i have an sdr everywhere i go. It uses a 14 inch hd display. A thinkpad keyboard. 3-4 5000mah lithium ion batteries in the standard
7mm thickness. Its passively cooled using an anodized aluminum sheet that will cover most of the bottom with the rest being 3d printed ideally in petg and assuming all goes to plan around it will be around 1.7cm thick. I estimate that it can acheive at least 6 hours of battery life with 4 5000mah battery while doing lite tasks. It also has m.2 slots. M key for nvme and e key for a wireless adapter.

## The vision:

A while ago i remember seeing a youtube short that really stuck with me, it was about a "hacker laptop and the short explained how it used a raspberry pi inside and had 18650 batteries and all and while it was a cool project i was blown away by the price, it costed over 1k usd and it was not very powerfull nor portable it felt like more of a cool gimmick than a tool. So I said one day I want to make something like that but ill make it the way i want. Itl have the things i want in a laptop: being compact and sturdy, easily fixable if something breaks, cheap, i can put custom stuff in it (like an rtl-sdr) and i wanted it to have decent battery life so that i can bring it anywhere and if i'm stuck somewhere with no power for 3 hours i can still work on stuff on it. Basically something that can be daily drivable when I dont have access to my desktop.

### pcb
<img width="791" height="853" alt="image" src="https://github.com/user-attachments/assets/eb38c365-057b-4eb3-b05d-9d72353b8282" />
Its pretty crowded, I recomend you open up the pcb in kicad you'll be able to zoom into stuff

<img width="896" height="635" alt="image" src="https://github.com/user-attachments/assets/9359cf34-b557-42c1-8045-e7cb2073b700" />

(missing the 2 usb3 ports and the ddr4 so-dimm connector

note: pcb V2 is the latest pcb, but production wise they are the same its just a redraw of the schematic

### cad
<img width="731" height="548" alt="image" src="https://github.com/user-attachments/assets/3b908616-347f-4ec7-8787-8387c1257f1a" />





![image](https://github.com/user-attachments/assets/a43cceae-174c-48a3-99e0-9f248a05b672)




### Bom

| Item | Price | Link |
|------|-------|------|
| Lattepanda MU + Lite Dev Carrier Board | 180 USD | [DFRobot](https://www.dfrobot.com/kit-004.html) |
| Display Controller | 22 USD | [AliExpress](https://www.aliexpress.com/item/1005008432586523.html?spm=a2g0o.productlist.main.12.6c4bwR7lwR7l8y&algo_pvid=8593971f-0f25-4dac-ac2b-4313578de187&algo_exp_id=8593971f-0f25-4dac-ac2b-4313578de187-11&pdp_ext_f=%7B%22order%22%3A%22-1%22%2C%22eval%22%3A%221%22%7D&pdp_npi=4%40dis%21CAD%2131.75%2126.99%21%21%21162.57%21138.20%21%402103247417527988213296838e3ecd%2112000045073927194%21sea%21CA%216086132031%21X&curPageLogUid=1h1893jWQeCE&utparam-url=scene%3Asearch%7Cquery_from%3A) |
| Display 14 inch | 42 USD | [AliExpress](https://www.aliexpress.com/item/1005003386237483.html?spm=a2g0o.productlist.main.20.787a5f1dEl49la&algo_pvid=1de636ed-d35d-4aee-a0d8-9a6b0865f511&algo_exp_id=1de636ed-d35d-4aee-a0d8-9a6b0865f511-19&pdp_ext_f=%7B%22order%22%3A%2223%22%2C%22eval%22%3A%221%22%7D&pdp_npi=4%40dis%21CAD%2168.99%2168.99%21%21%2149.21%2149.21%21%40210318ec17527987558765212ed2de%2112000025538273862%21sea%21CA%216086132031%21X&curPageLogUid=DP21csvKEzq9&utparam-url=scene%3Asearch%7Cquery_from%3A) |
| Reinforcement Sheet for Display | 4.50 USD | [AliExpress](https://www.aliexpress.com/item/1005005966208898.html?spm=a2g0o.productlist.main.4.46b44b90s4itPe&algo_pvid=2cadd10b-1e23-4d8a-baaa-58015ebbfa84&algo_exp_id=2cadd10b-1e23-4d8a-baaa-58015ebbfa84-3&pdp_ext_f=%7B%22order%22%3A%22911%22%2C%22eval%22%3A%221%22%7D&pdp_npi=4%40dis%21CAD%215.69%215.69%21%21%2129.16%2129.16%21%402103244417534139299131566ef5c8%2112000035086418949%21sea%21CA%216086132031%21X&curPageLogUid=P45FPnknGnQg&utparam-url=scene%3Asearch%7Cquery_from%3A) |
| SODIMM DDR4 Connector (C2979963) | - | [JLCPCB](https://jlcpcb.com/partdetail/FOXCONN-ASAA823_EARB07H/C2979963) |
| 5000 mAh Battery | 30 CAD × 3–4 | [Amazon](https://www.amazon.ca/5000mAh-755590-Lithium-Replacement-Electronic/dp/B0BG85CMFL/ref=sr_1_1_sspa?crid=1VN50572QX28K&dib=eyJ2IjoiMSJ9.UH2iT11CrxzaQwfjEOyYPhK1U5jypSDZNWR4AsOAj6AqUhiNM-AfuSVTdCHuEgDrhX1ioglR6OQ_EnFGpm1RMRGhI8XFnnH-OlCwdBPSY1DBLp_jPFmBZIQ1OtFXrNlPgc_Z7XODRqUUBo6_nUXE3vagri2b7yDxdF9CqiwkFz52h7MugKFeGZKHuOtqFd3e4pfhVFPoPNogyl6p7YN8Cja68egJHFHi3pZRJOaOmkVI7mTkMwltDyW_U-2lOJuCL-ofAm3b0rf8hjlGPR3D_fCmjXyqCv1V4x5C1jTn2eI.CyqpkaqJzNKz6gdU7nku_drLzpFhmbIbea_bnupkH2w&dib_tag=se&keywords=lithium+battery+5000mah&qid=1753592235&sprefix=lithium+battery+5000mah%2Caps%2C94&sr=8-1-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&psc=1) |
| Mainboard PCB | ~90 USD (estimate) | x |
| ThinkPad Keyboard | ~30–40 USD | - |

Note that I already have the thinkpad keyboard and the 3d printing filament but its pla so ill have to test petg in the future.
