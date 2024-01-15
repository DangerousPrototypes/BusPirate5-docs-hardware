---
sidebar_position: 10
sidebar_label: 'Molded Shell'
---

# Injection Molded Enclosure

## Components
### PP Shell

|**Reference**  |**Value  **|**Quantity  **|**Rating**  |**Note  **|
|-|-|-|-|-|
|Top shell  ||1  ||Clear PP|
|Bottom shell||1||Clear PP|

Top and bottom enclosure injection molded in clear/transparent PP plastic. 

### M3 brass insert nuts

|**Reference**|**Package**|**Value**|**Quantity**|**Rating**|**Note**|
|-|-|-|-|-|-|
|Nuts  |M3x3mmLx4.0mmD|M3 brass insert nut  |4  ||Should be 4mm height|

Brass insert nuts for injection molding. 

Nuts are placed into the tooling before each case is injection molded. This is labor intensive and future cases will probably have a cavity on the bottom for a typical M3 nut.

Ideally, the nut height would be 4mm so the case works with standard 8mm bolts. Due to circumstances (see below) the factory used 3mm insert nuts. 8mm bolts hit the injection molding gunk that creeps into the base of the 3mm nut, so the bolts don't always sit flush with the front of the case. The current solution is a 7mm bolt, which is a non-standard size.

### M3 7mm DIN7991 bolt
  
![](./img/din7991.png)

|**Reference**|**Package**|**Value**|**Quantity**|**Rating**|**Note**|
|-|-|-|-|-|-|
|Bolts|M3x**7mm** DIN7991|M3 **7mm** bolt DIN7991 silver|4||Silver color|

**7mm** bolts are a non-standard size. We're stuck with them because of clearance issues in this revision of the injection molded case. Bolts can usually be found at a couple factories that have remains from previous custom manufacturing runs. The next enclosure revision will address this issue.

:::danger
Bolts should be finger tight. Over tightening bolts may pull the insert nut out of the case, or crush the LCD.
:::

:::info
The 3D printable version of the enclosure work with standard 8mm DIN7991 bolts, but injection molded version specifies 7mm bolts. 8mm bolts will work, but some heads may sit 0.1-0.3mm from the front of the case. 
:::

### Hole cover

|**Reference**|**Package**|**Value**|**Quantity**|**Rating**|**Note**|
|-|-|-|-|-|-|
|Cover|-|Hole cover|1||White SLA|

Bus Pirate 5 REV0 to REV9 included an SD card socket. SD cards are slow in SPI mode, and slow down everything else on the internal shared SPI bus (LCD, IO expanders). We replaced it with a chunk of onboard NAND flash, but now there's a gaping hole in the enclosure and it's far too late to make changes.

In an act of despiration we modeled (link) a hole cover and SLA printed it. Despite being smaller than the allowed specs, our SLA supplier was happy to print batches of them. It turned out very well - super thin and a good color match to the case material. 

The SD card slot will be removed in a future revision of the case.

## Manufacturing Notes

We chose the case factory because they were cheap and the boss took the time to review the Bus Pirate and send photos of plastic materials/styles he thought would work well. It was off to such a great start.

We went the cheap route and paid dearly. This is our experience, and really shouldn't be your experience.

### Tooling fit test
ABS plastic test of inside fit. No surface treatment - check the tooling marks on the plastic.

No insert nuts, which we reported and tehy said no problem.

:::danger
Mold tooling is made to accommodate the properties of specific materials. One tooling should not be used for multiple materials like ABS, PP, PC etc. That didn't seem to matter to the factory we used, they did make it work. Did it work well though? It wasn't great...
:::

### Material test
Matte surface treatment applied. Molded in PP. A little too clear (lights not diffused).

Still no insert nuts. We panick and ask when we can test them. Soon, no worries.

### Polycarbinate for some reason

A second material test arrives in PC (polycarbonate), a much stronger material. It's a little more opaque and the LEDs look great. It's much more expensive though, and not the material we origionally ordered for the tooling.

Still no insert nuts. Next time for sure!

### Color & production test

Injection molding machine photo

A color test was scheduled for a Thursday. 

We asked that they add a little bit extra titanium dioxide (6g total) to make the PP more opaque. This set off a series of events that resulted in our full production batch being scheduled imediatly for the next sunday without a final color or insert nut test. It's months late, okay, we'll roll with it.

### The bad batch

Pics of bad cases, 

Thousands of bits of plastic descend on our office. All of them have serious defects:
- Part of the wall is missing on every case
- The two positioning pegs for the 9P auxillary conector are missing/deformed on every case
- Insert nuts are in the wrong place or burried on a third of the cases
- Enough plastic leaked into the base of the insert nut that 8mm bolts no longer consistently sit flush agains the front of the case

After months of delay this was a huge bummer. The factory asked us to "help them out" and use the cases anyways. Next, they wanted to charge us even more for a second batch using PC.

We talked to a contact at a factory that is far too high-end/high-volume for our project. He looked as some photos and gave us the techinal terms (in Mandarin) for the mold/process failures. We leveraged this bit of knowledge to get a second batch of cases manufactured without charge.

:::info
The sudden decision to run our cases on a Sunday without a final test seems to have caused all sorts of problems. The "nut master" with the most experince handing this type of tooling had the day off, so they used unqualified hourly labor instead. Our factory rep was supposed to do quality control, but they left after 20 minutes because "it's Sunday" and tried to put that on us. The whole thing was weird.

We hoped to come out of this experience with some definitive lesson about injection molding, but we haven't found it. The general rule applies though: go hang out at the factory if your production is critical/time sensitive.
:::

### Batch 2

PIC of good cases

The second batch is beautiful, even better than the intial samples. It seems they really slowed down the machine and took their time getting it done.

The insert nuts are still too short, they should have been 4mm to accomidate an 8mm bolt. We sourced 7mm bolts and they fit perfectly, though they are non-standard.

