#### Introduction

Experimenting with LDA on the bible, to see what I could come up with.

#### Getting Started

First run:

```
make build
```

Then run:

```
make nlp
```

You can experiment with k (the number of topics), 
i (the number of iterations), and alpha + beta (tuning parameters).

#### Example Output

```
-- topic: 0 (8769 words)
shall: 0.005613 (87)
people: 0.004394 (68)
unto: 0.004330 (67)
stranger: 0.003175 (49)
two: 0.003175 (49)
stood: 0.002854 (44)
i: 0.002790 (43)
thy: 0.002790 (43)
work: 0.002662 (41)
the: 0.002598 (40)
coming: 0.002405 (37)
iniquity: 0.002085 (32)
brother: 0.002085 (32)
said: 0.002021 (31)
dwell: 0.001892 (29)
according: 0.001892 (29)
hath: 0.001892 (29)
rest: 0.001828 (28)
wife: 0.001828 (28)
also: 0.001636 (25)
turned: 0.001636 (25)
thought: 0.001572 (24)
away: 0.001572 (24)
thou: 0.001572 (24)
deep: 0.001572 (24)
commanded: 0.001572 (24)
israel: 0.001507 (23)
consider: 0.001443 (22)
heal: 0.001443 (22)
remain: 0.001443 (22)
sword: 0.001379 (21)
kept: 0.001379 (21)
spake: 0.001379 (21)
for: 0.001315 (20)
men: 0.001315 (20)
father: 0.001315 (20)
land: 0.001251 (19)
beside: 0.001251 (19)
driven: 0.001251 (19)
eat: 0.001251 (19)
wisdom: 0.001251 (19)
shewed: 0.001251 (19)
lord: 0.001251 (19)
still: 0.001251 (19)
hear: 0.001187 (18)
call: 0.001187 (18)
running: 0.001187 (18)
condemned: 0.001123 (17)
lame: 0.001123 (17)
thing: 0.001123 (17)

-- topic: 1 (68434 words)
i: 0.023567 (1773)
shall: 0.022450 (1689)
unto: 0.017082 (1285)
lord: 0.016976 (1277)
god: 0.012750 (959)
thy: 0.011009 (828)
upon: 0.009920 (746)
hath: 0.008764 (659)
thee: 0.008484 (638)
said: 0.007262 (546)
land: 0.006784 (510)
son: 0.006598 (496)
thou: 0.006292 (473)
people: 0.006186 (465)
house: 0.006013 (452)
it: 0.005694 (428)
ye: 0.005588 (420)
men: 0.005269 (396)
day: 0.005229 (393)
and: 0.005149 (387)
israel: 0.005030 (378)
moses: 0.005030 (378)
away: 0.004990 (375)
brother: 0.004923 (370)
saying: 0.004724 (355)
set: 0.004671 (351)
hast: 0.004405 (331)
thing: 0.004285 (322)
even: 0.004206 (316)
take: 0.004086 (307)
him: 0.004086 (307)
make: 0.004033 (303)
also: 0.004006 (301)
say: 0.004006 (301)
king: 0.003940 (296)
me: 0.003873 (291)
way: 0.003860 (290)
judgment: 0.003847 (289)
the: 0.003807 (286)
given: 0.003754 (282)
come: 0.003741 (281)
david: 0.003674 (276)
may: 0.003661 (275)
every: 0.003634 (273)
child: 0.003608 (271)
wisdom: 0.003555 (267)
came: 0.003515 (264)
brought: 0.003422 (257)
gold: 0.003329 (250)
mine: 0.003236 (243)

-- topic: 2 (119252 words)
lord: 0.028813 (3632)
unto: 0.026037 (3282)
shall: 0.022554 (2843)
i: 0.021063 (2655)
god: 0.016090 (2028)
thou: 0.014860 (1873)
son: 0.014535 (1832)
thy: 0.014392 (1814)
ye: 0.012933 (1630)
said: 0.012719 (1603)
thee: 0.012552 (1582)
king: 0.012544 (1581)
man: 0.010363 (1306)
come: 0.009205 (1160)
one: 0.008777 (1106)
israel: 0.008221 (1036)
shalt: 0.007048 (888)
thing: 0.006770 (853)
upon: 0.006587 (830)
came: 0.006421 (809)
people: 0.005763 (726)
city: 0.005723 (721)
land: 0.005667 (714)
hand: 0.005429 (684)
you: 0.005390 (679)
day: 0.005310 (669)
father: 0.004906 (618)
him: 0.004882 (615)
thereof: 0.004842 (610)
year: 0.004708 (593)
great: 0.004589 (578)
saith: 0.004557 (574)
go: 0.004501 (567)
child: 0.004192 (528)
earth: 0.004129 (520)
hast: 0.004065 (512)
heart: 0.004033 (508)
pas: 0.003946 (497)
word: 0.003906 (492)
o: 0.003906 (492)
away: 0.003883 (489)
them: 0.003676 (463)
according: 0.003676 (463)
therefore: 0.003676 (463)
chapter: 0.003534 (445)
also: 0.003470 (437)
servant: 0.003407 (429)
art: 0.003312 (417)
house: 0.003248 (409)
it: 0.003240 (408)

-- topic: 3 (5660 words)
thou: 0.003565 (44)
unto: 0.002604 (32)
lord: 0.002444 (30)
thee: 0.002203 (27)
them: 0.002043 (25)
i: 0.001803 (22)
dew: 0.001803 (22)
people: 0.001723 (21)
water: 0.001642 (20)
house: 0.001482 (18)
man: 0.001482 (18)
israel: 0.001482 (18)
come: 0.001482 (18)
anger: 0.001482 (18)
thy: 0.001402 (17)
work: 0.001402 (17)
when: 0.001322 (16)
offering: 0.001242 (15)
depart: 0.001242 (15)
pit: 0.001162 (14)
toward: 0.001162 (14)
smite: 0.001162 (14)
offer: 0.001162 (14)
noise: 0.001082 (13)
city: 0.001082 (13)
speak: 0.001002 (12)
said: 0.001002 (12)
king: 0.001002 (12)
shall: 0.001002 (12)
him: 0.001002 (12)
nothing: 0.000921 (11)
openeth: 0.000921 (11)
ask: 0.000921 (11)
bethel: 0.000921 (11)
worshipped: 0.000921 (11)
departed: 0.000921 (11)
high: 0.000921 (11)
down: 0.000921 (11)
according: 0.000921 (11)
cloud: 0.000841 (10)
porch: 0.000841 (10)
and: 0.000841 (10)
ye: 0.000841 (10)
day: 0.000841 (10)
took: 0.000841 (10)
prevailed: 0.000841 (10)
many: 0.000841 (10)
god: 0.000841 (10)
naked: 0.000761 (9)
honey: 0.000761 (9)

-- topic: 4 (84483 words)
shall: 0.023619 (2156)
unto: 0.020695 (1889)
i: 0.018581 (1696)
thou: 0.017978 (1641)
him: 0.013477 (1230)
me: 0.010586 (966)
them: 0.010038 (916)
upon: 0.009457 (863)
thy: 0.009403 (858)
thee: 0.008746 (798)
lord: 0.008614 (786)
hath: 0.008494 (775)
son: 0.008329 (760)
thine: 0.007913 (722)
said: 0.007322 (668)
and: 0.006884 (628)
day: 0.006752 (616)
place: 0.006654 (607)
king: 0.006555 (598)
people: 0.006391 (583)
word: 0.005953 (543)
god: 0.005723 (522)
also: 0.005679 (518)
one: 0.005493 (501)
saying: 0.005449 (497)
thing: 0.005306 (484)
forth: 0.005285 (482)
know: 0.005208 (475)
father: 0.005109 (466)
let: 0.005022 (458)
go: 0.004868 (444)
ye: 0.004638 (423)
hand: 0.004463 (407)
made: 0.004354 (397)
thousand: 0.004321 (394)
u: 0.004310 (393)
priest: 0.004189 (382)
man: 0.004135 (377)
make: 0.003981 (363)
hundred: 0.003926 (358)
came: 0.003905 (356)
jerusalem: 0.003872 (353)
enemy: 0.003828 (349)
brought: 0.003740 (341)
house: 0.003620 (330)
may: 0.003598 (328)
men: 0.003423 (312)
year: 0.003401 (310)
israel: 0.003401 (310)
put: 0.003357 (306)

-- topic: 5 (42151 words)
shall: 0.015346 (751)
i: 0.013508 (661)
lord: 0.012385 (606)
israel: 0.010281 (503)
said: 0.009648 (472)
thy: 0.009505 (465)
unto: 0.008913 (436)
god: 0.005871 (287)
work: 0.005850 (286)
thee: 0.005279 (258)
men: 0.004952 (242)
brother: 0.004462 (218)
hand: 0.004237 (207)
them: 0.004237 (207)
house: 0.003972 (194)
heaven: 0.003931 (192)
priest: 0.003849 (188)
give: 0.003829 (187)
good: 0.003767 (184)
heart: 0.003727 (182)
name: 0.003727 (182)
little: 0.003706 (181)
earth: 0.003604 (176)
heard: 0.003441 (168)
right: 0.003379 (165)
me: 0.003339 (163)
shalt: 0.003318 (162)
upon: 0.003237 (158)
chapter: 0.003237 (158)
whose: 0.003196 (156)
man: 0.003114 (152)
city: 0.002992 (146)
go: 0.002971 (145)
see: 0.002971 (145)
say: 0.002910 (142)
thought: 0.002910 (142)
every: 0.002869 (140)
reigned: 0.002869 (140)
king: 0.002828 (138)
hath: 0.002787 (136)
came: 0.002726 (133)
now: 0.002706 (132)
him: 0.002644 (129)
day: 0.002624 (128)
help: 0.002624 (128)
o: 0.002583 (126)
glory: 0.002583 (126)
come: 0.002522 (123)
prophet: 0.002522 (123)
land: 0.002501 (122)

-- topic: 6 (34136 words)
shall: 0.017177 (703)
i: 0.017054 (698)
unto: 0.011170 (457)
lord: 0.009608 (393)
god: 0.009510 (389)
him: 0.008289 (339)
work: 0.007728 (316)
child: 0.007435 (304)
ye: 0.006873 (281)
house: 0.006702 (274)
me: 0.006434 (263)
every: 0.005799 (237)
thou: 0.005774 (236)
thee: 0.005555 (227)
sin: 0.005262 (215)
head: 0.004724 (193)
made: 0.004651 (190)
life: 0.004529 (185)
them: 0.004358 (178)
way: 0.004285 (175)
you: 0.004016 (164)
hath: 0.003919 (160)
man: 0.003845 (157)
face: 0.003675 (150)
thy: 0.003601 (147)
said: 0.003382 (138)
speak: 0.003357 (137)
heard: 0.003333 (136)
time: 0.003308 (135)
saying: 0.003308 (135)
her: 0.003284 (134)
came: 0.003186 (130)
there: 0.003137 (128)
side: 0.003113 (127)
philistine: 0.003089 (126)
mine: 0.003064 (125)
even: 0.003040 (124)
laid: 0.003015 (123)
earth: 0.002918 (119)
certain: 0.002844 (116)
heart: 0.002820 (115)
moses: 0.002796 (114)
day: 0.002747 (112)
land: 0.002747 (112)
water: 0.002747 (112)
priest: 0.002649 (108)
great: 0.002551 (104)
not: 0.002551 (104)
judah: 0.002527 (103)
also: 0.002478 (101)

-- topic: 7 (15372 words)
shall: 0.012594 (279)
i: 0.009710 (215)
lord: 0.008899 (197)
city: 0.006736 (149)
unto: 0.006511 (144)
thee: 0.006151 (136)
like: 0.004483 (99)
day: 0.004438 (98)
thou: 0.004348 (96)
man: 0.003898 (86)
me: 0.003898 (86)
made: 0.003808 (84)
child: 0.003762 (83)
silver: 0.003267 (72)
called: 0.002906 (64)
thing: 0.002861 (63)
live: 0.002771 (61)
them: 0.002771 (61)
work: 0.002681 (59)
said: 0.002591 (57)
it: 0.002591 (57)
saith: 0.002501 (55)
brought: 0.002456 (54)
ye: 0.002366 (52)
letter: 0.002366 (52)
come: 0.002321 (51)
part: 0.002321 (51)
father: 0.002275 (50)
away: 0.002185 (48)
and: 0.002185 (48)
even: 0.002050 (45)
thine: 0.002050 (45)
samaria: 0.002050 (45)
upon: 0.002005 (44)
able: 0.001960 (43)
make: 0.001960 (43)
hath: 0.001960 (43)
die: 0.001915 (42)
thy: 0.001915 (42)
they: 0.001870 (41)
slain: 0.001870 (41)
gold: 0.001780 (39)
fear: 0.001780 (39)
name: 0.001780 (39)
came: 0.001735 (38)
house: 0.001690 (37)
god: 0.001645 (36)
heed: 0.001600 (35)
son: 0.001600 (35)
might: 0.001600 (35)

-- topic: 8 (99122 words)
unto: 0.023574 (2497)
shall: 0.022564 (2390)
lord: 0.016155 (1711)
thou: 0.014616 (1548)
them: 0.013257 (1404)
i: 0.012813 (1357)
him: 0.012247 (1297)
ye: 0.011794 (1249)
thy: 0.009878 (1046)
god: 0.009142 (968)
day: 0.009076 (961)
u: 0.008679 (919)
said: 0.008245 (873)
man: 0.007178 (760)
went: 0.007169 (759)
hand: 0.006980 (739)
hath: 0.006678 (707)
thee: 0.006527 (691)
child: 0.006433 (681)
men: 0.006348 (672)
came: 0.006272 (664)
son: 0.006234 (660)
and: 0.006159 (652)
upon: 0.005763 (610)
it: 0.005612 (594)
house: 0.005583 (591)
let: 0.005536 (586)
name: 0.005300 (561)
made: 0.005177 (548)
also: 0.005140 (544)
behold: 0.004885 (517)
people: 0.004611 (488)
every: 0.004573 (484)
jerusalem: 0.004535 (480)
thing: 0.004243 (449)
time: 0.004205 (445)
thus: 0.004167 (441)
offering: 0.004064 (430)
shalt: 0.003903 (413)
eye: 0.003856 (408)
israel: 0.003837 (406)
me: 0.003809 (403)
good: 0.003686 (390)
king: 0.003620 (383)
one: 0.003592 (380)
servant: 0.003469 (367)
law: 0.003431 (363)
go: 0.003374 (357)
answered: 0.003327 (352)
jesus: 0.003318 (351)

-- topic: 9 (1499 words)
son: 0.000781 (6)
tach: 0.000661 (5)
law: 0.000661 (5)
won: 0.000661 (5)
robbed: 0.000541 (4)
profit: 0.000541 (4)
meaning: 0.000541 (4)
nahor: 0.000541 (4)
gold: 0.000541 (4)
told: 0.000541 (4)
barefoot: 0.000421 (3)
thing: 0.000421 (3)
openeth: 0.000421 (3)
gibeon: 0.000421 (3)
thy: 0.000421 (3)
husband: 0.000421 (3)
desolate: 0.000421 (3)
besiege: 0.000421 (3)
thousand: 0.000421 (3)
ahikam: 0.000421 (3)
smitten: 0.000421 (3)
themselves: 0.000421 (3)
flesh: 0.000421 (3)
fir: 0.000421 (3)
uprightly: 0.000421 (3)
unto: 0.000421 (3)
shew: 0.000421 (3)
maidservant: 0.000421 (3)
order: 0.000421 (3)
pomegranate: 0.000421 (3)
victual: 0.000421 (3)
redemption: 0.000421 (3)
zimri: 0.000421 (3)
lad: 0.000421 (3)
hoshea: 0.000421 (3)
ninth: 0.000421 (3)
heave: 0.000421 (3)
increase: 0.000421 (3)
waved: 0.000421 (3)
needlework: 0.000421 (3)
softly: 0.000421 (3)
twenty: 0.000421 (3)
row: 0.000421 (3)
thereof: 0.000421 (3)
favoured: 0.000421 (3)
king: 0.000421 (3)
twined: 0.000421 (3)
sink: 0.000421 (3)
flour: 0.000421 (3)
begotten: 0.000421 (3)
```