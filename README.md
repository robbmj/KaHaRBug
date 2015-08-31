**Step One:**

Low Level Check Box is Checked, use Wave function:

  Attack Force
  Unit  Start Quant.   End Quant.  Power Armour   Shield
  fighters              95029.00            ?        5.60       5.800        0.00

  defensive force
  unit start quant. end quant. power armourshield
  fighters           62848           ?               8.88            4.8             0              
  cruiser            2108            ?               95.46           57.6            4              
  carrier            770             ?               36.63           57.6            4              
  dreadnought        2               ?               2237.76         1228.8          40             
  planetaryshield    25              ?               6.2             4915.2          40             
  planetaryring      30              ?               3276.8          2457.6          24      


**Step Two:**

Replace attacker's start quantity with 1.4M fighters and then Wave again:

Attack Force
Unit               Start Quant.   End Quant.       Power      Armour      Shield
fighters                  1400000            ?        5.60       5.800        0.00

Defensive Force
Unit               Start Quant.   End Quant.       Power      Armour      Shield
fighters                  0.00            ?        8.88       4.800        0.00
cruiser                1567.97            ?       95.46      57.600        4.00
carrier                 229.97            ?       36.63      57.600        4.00
dreadnought               1.95            ?     2237.76    1228.800       40.00
planetaryshield          24.98            ?        6.20    4915.200       40.00
planetaryring            29.98            ?     3276.80    2457.600       24.00

**Step Three:**

Wave Again, Note the start quantity for DN:

Attack Force
Unit               Start Quant.   End Quant.       Power      Armour      Shield
fighters            1355024.28            ?        5.60       5.800        0.00

Defensive Force
Unit               Start Quant.   End Quant.       Power      Armour      Shield
fighters                  0.00            ?        8.88       4.800        0.00
cruiser                   0.00            ?       95.46      57.600        4.00
carrier                   0.00            ?       36.63      57.600        4.00
dreadnought              -0.00            ?     2237.76    1228.800       40.00
planetaryshield          13.34            ?        6.20    4915.200       40.00
planetaryring            16.01            ?     3276.80    2457.600       24.00

**Step Four:**

Again Note the start quantity for DN:

Attack Force
Unit               Start Quant.   End Quant.       Power      Armour      Shield
fighters             482590.81            ?        5.60       5.800        0.00

Defensive Force
Unit               Start Quant.   End Quant.       Power      Armour      Shield
fighters                  0.00            ?        8.88       4.800        0.00
cruiser                   0.00            ?       95.46      57.600        4.00
carrier                   0.00            ?       36.63      57.600        4.00
dreadnought            2215.71        -0.00     2237.76    1228.800       40.00
planetaryshield           5.23            ?        6.20    4915.200       40.00
planetaryring             6.28            ?     3276.80    2457.600       24.00


**This Bug also manifests it's self When using the zero Fleet Option:**

**Step One:**

Low Level Check Box is Checked, use Wave function:

Attack Force
Unit  Start Quant.   End Quant.  Power Armour   Shield
fighters              95029.00            ?        5.60       5.800        0.00

defensive force
unit start quant. end quant. power armourshield
fighters           62848           ?               8.88            4.8             0              
cruiser            2108            ?               95.46           57.6            4              
carrier            770             ?               36.63           57.6            4              
dreadnought        2               ?               2237.76         1228.8          40             
planetaryshield    25              ?               6.2             4915.2          40             
planetaryring      30              ?               3276.8          2457.6          24

**Step Two:**

Replace attacker's start quantity with 1.4M fighters and then Zero Fleet:

Attack Force
Unit               Start Quant.   End Quant.       Power      Armour      Shield
fighters                  1400000            ?        5.60       5.800        0.00

Defensive Force
Unit               Start Quant.   End Quant.       Power      Armour      Shield
fighters                  0.00            ?        8.88       4.800        0.00
cruiser                1567.97            ?       95.46      57.600        4.00
carrier                 229.97            ?       36.63      57.600        4.00
dreadnought               1.95            ?     2237.76    1228.800       40.00
planetaryshield          24.98            ?        6.20    4915.200       40.00
planetaryring            29.98            ?     3276.80    2457.600       24.00

Result is:

[code]Number of waves: 1000[/code]

...

[code]Attacker lost [color=red]0 [/color][color=red][764,655][/color] credits and [color=red]0 [/color][color=red][0][/color] credits in repairs
Defender lost [color=red]0 [/color][color=red][1,063,840][/color] credits and [color=red]0 [/color][color=red][258][/color] credits in repairs
Debris generated [color=green]0 [/color][color=green][1,176,887][/color] credits
Attacker Ratio 0.00001:1 [0.71900:1]
Profit Rate: OVER NINE THOUSAAAAND% [53.9100%]
Profit: [color=green]0.00 [/color][color=green][412,232.00][/color][/code]

Funny thing is that this the correct ratio

