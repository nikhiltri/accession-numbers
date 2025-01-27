# Data sources

_This file was generated by robots at 2021-11-21 17:42:04.129037 -0800 PST m=+0.001899648_

## Art Institute of Chicago

* [https://www.artic.edu](https://www.artic.edu)

### Patterns

#### common

```
((?:Obj: \d+)|(?:[RXTNof\d]{3,}(?:\.|\/)?[\d\.\-,a-z]*))
```

For example:

```
0158 (0096TS)
19.148.1966
1900.678 - 685
1902.167a
1925.2687, 1930.385, 1934.250-252
1926.224
1926.417
1962.743a-c
1964.336
1978.1098
1988.157.88
1994.36
2015.255
2020.316.1-13
Obj: 96681
R1689/20.2
RX16751/1844.a
RX23664/75.1-3,216
RX23664/89.1-151
RX23664/89.115
RX23931
RX5669/3
RofO3998/2
TN11
This is an object\nGift of Important Donor\nX78\n\nThis is another object\nAnonymouts Gift\nRX16751/1844.a\n1962.743a-c\nBronze
X78
```

## Baltimore Museum of Art

* [https://artbma.org](https://artbma.org)

### Patterns

#### common

```
((?:\d{4})\.(?:\d+)(?:(?:\.[0-9\.]*)*)?)
```

For example:

```
1938.304
1980.441.28
2009.42
```

## Cooper Hewitt Smithsonian National Design Museum

* [https://cooperhewitt.org/](https://cooperhewitt.org/)

### Patterns

#### common

```
((?:[a-z0-9]+)-(?:[a-z0-9]+)-(?:[a-z0-9]+))
```

For example:

```
2007-27-30
```

## Denver Museum of Nature & Science

* [https://www.dmns.org](https://www.dmns.org)

### Patterns

#### common

```
((?:\w+)(?:[\.\-]+)(?:\d+[A-Z\&\-\d]*))
```

For example:

```
A1290.6
A1396.24A&B
BA21-849
EGM.19492
HS.2010-103-2
HS.2014-236-102
OS-239-1
ZE.35094
ZM.6700
```

## Georgia O'Keeffe Museum

* [https://www.okeeffemuseum.org](https://www.okeeffemuseum.org)

### Patterns

#### common

```
((?:(?:\d{4})|(?:[A-Z]*))\.(?:\d+)(?:(?:\.[0-9a-z]*)*))?
```

For example:

```
2000.5.815v
2006.6.1311
2006.6.1412
2007.4.42
MS.37
MS.6
```

## Getty Center

* [https://www.getty.edu](https://www.getty.edu)

### Patterns

#### common

```
((?:\d+)\.(?:\d{2}|\D{2})(?:\.\d+){0,3})
```

For example:

```
2004.60.17
2014.32
2016.66
70.AA.109
84.XA.757.4.13
```

## Metropolitan Museum of Art

* [https://www.metmuseum.org](https://www.metmuseum.org)

### Patterns

#### common

```
((?:\d+)(?:\.(?:\d+\w*-*–*\w*)){0,2})
```

For example:

```
03.14.13a–g
04.1a–c
2018.873
2019.456.13
53.87a-i
66.173
66.221.1
88.3.1
```

## Milwaukee Art Museum

* [http://mam.org](http://mam.org)

### Patterns

#### common

```
((?:M\d{4})\.(?:\d+)(?:\.[0-9a-z\,–\.]*)*)
```

For example:

```
M2019.117.1a,b–.5
M2019.120.1a,b–4a,b
M2019.66
M2020.39
M2021.371
```

## Minneapolis Art Museum

* [https://new.artsmia.org](https://new.artsmia.org)

### Patterns

#### common

```
((?:[A-Z]?\d{2,4})\.(?:\d+)(?:\.\d+[A-Z\,]*)*)
```

For example:

```
14.120
2003.236.236
2015.79.456
98.75.2A,B
98.78.3.2
```

## Museo del Prado

* [https://www.museodelprado.es](https://www.museodelprado.es)

### Patterns

#### common

```
([A-Z]\d+)
```

For example:

```
D003874
E000028
P000299
P002132
P002179
```

## Museum of Fine Arts Boston

* [https://www.mfa.org](https://www.mfa.org)

### Patterns

#### common

```
((?:\d{2,4})\.(?:\d+[A-Z]*))
```

For example:

```
11.24732B
17.2230
2007.600
99.101
```

## Museum of Modern Art

* [https://www.moma.org](https://www.moma.org)

### Patterns

#### common

```
((?:[A-Z]{0,2}\d+)\.(?:\d{4})\.*(?:\w*\d*-*)*)
```

For example:

```
146.2020
203.2020
284.2020.1
302.2021.x1-x2
PG731.2019
This is an object\nGift of Important Donor\n302.2021.x1-x2\n\nThis is another object\nAnonymouts Gift\nPG731.2019 146.2020
```

## Museum of New Zealand Te Papa Tongarewa

* [https://www.tepapa.govt.nz](https://www.tepapa.govt.nz)

### Patterns

#### common

```
((?:[A-Z]+[0-9]+[/A-Z])|(?:(?:\d+)-(?:\d+)-(?:\d+)(?:/[A-z\ -]+)))
```

For example:

```
2008-0006-1/A-L to L-L
2014-0031-1
GH004839
ME001533
OL000491
SP082549/A
```

## Musée d'Orsay

* [https://www.musee-orsay.fr](https://www.musee-orsay.fr)

### Patterns

#### common

```
((?:[A-Z]+\ )(?:\d+)+(?:(?:\ [0-9]+)|(?:,\ [A-z0-9\ ,]*)|(?:-[0-9]+)))
```

For example:

```
RF 1949 17
RF 1980-195
RF 37305, Recto, RF 37305
RF 676, LUX 91
```

## National Air and Space Museum

* [https://airandspace.si.edu/](https://airandspace.si.edu/)

### Patterns

#### common

```
((?:\D)(?:\d{4})(?:\d)+)
```

For example:

```
A19610048000
A19670093000
A19670176000
A19920072000
```

## National Gallery Singapore

* [https://www.nationalgallery.sg](https://www.nationalgallery.sg)

### Patterns

#### common

```
((?:(?:\d+)|(?:[A-Z]+))-(?:[A-Z0-9]+)(?:-[A-Z0-9.]+)*)
```

For example:

```
2001-03415
2003-03691
2010-04133
ASB-0036
RC-S2-CCS2.6
```

## National Gallery of Art

* [https://www.nga.gov/](https://www.nga.gov/)

### Patterns

#### common

```
((?:\d+)\.(?:\d+)\.(?:\d+))
```

For example:

```
1942.9.8
1992.101.1
1999.26.1
2000.39.2
2001.72.1
2005.52.4
```

## National Museum of African American History and Culture

* [https://nmaahc.si.edu/](https://nmaahc.si.edu/)

### Patterns

#### common

```
((?:\d{4})\.(?:\d+)(?:\.\d+){0,2})
```

For example:

```
2012.110
2013.68.19
2014.270.2
2016.5.2.11
```

## National Museum of American History

* [https://americanhistory.si.edu/](https://americanhistory.si.edu/)

### Patterns

#### common

```
((?:[A-Z]*\d*)\.(?:\d+)\.(?:\d+)\.*(?:\w+)*)
```

For example:

```
1980.0771.03
CE.62.1061
PL.227739.1801.I1
PL.227739.1829.X01
PL.315264.3833
```

## National Museum of Anthropology

* [https://museu.ms/museum/details/16762](https://museu.ms/museum/details/16762)

### Patterns

#### common

```
((?:\d+)\.(?:\d-\d+))
```

For example:

```
06.0-03266
07.0-04968
09.0-06366
```

## National Museum of Korea

* [https://www.museum.go.kr](https://www.museum.go.kr)

### Patterns

#### common

```
((?:[A-z]+)\ (?:\d+)(?:~[0-9]+)*)
```

For example:

```
Buyeo 5333
Deoksu 2327
Hwangbuk 45
Sinsu 2578~2583
```

## SFO Museum

* [https://sfomuseum.org/](https://sfomuseum.org/)

### Patterns

#### common

```
((?:L|R)?(?:\d+)\.(?:\d+)\.(?:\d+)(?:\.(?:\d+))?(?:(?:\s?[sa-z])+)?)
```

For example:

```
1994.18.175
1994.18.199a
2000.058.1185 a c
2001.106.041 a
2002.135.017.042
2014.120.001
L2021.0501.033 a
R2021.0501.030
This is an object\nGift of Important Donor\n1994.18.175\n\nThis is another object\nAnonymouts Gift\n1994.18.165 1994.18.199a\n2000.058.1185 a c\nOil on canvas
```

## Saint Louis Art Museum

* [https://www.slam.org](https://www.slam.org)

### Patterns

#### common

```
((?:\d+)\:(?:\d{4})(?:[0-9a-z\,\.]*)*)
```

For example:

```
111:2010a,b
138:1947
23:1992
7:1946
9:2016.6
```

## San Francisco Museum of Modern Art

* [https://www.sfmoma.org](https://www.sfmoma.org)

### Patterns

#### common

```
((?:\d{2})\.(?:\d+)(?:\.[A-Z\-]*)*)
```

For example:

```
54.3536
86.6
91.161
98.193.A-E
98.513.A-PP
```

## Seattle Art Museum

* [https://seattleartmuseum.org](https://seattleartmuseum.org)

### Patterns

#### common

```
((?:\d{2,4})\.(?:\d+)(?:\.[0-9\.]*)*)
```

For example:

```
2006.123
2012.14.2
2020.15.12
2020.15.25
69.177
97.44.1.2
```

## Smithsonian National Museum of Natural History

* [http://naturalhistory.si.edu/](http://naturalhistory.si.edu/)

### Patterns

#### common

```
(USNM\ (?:\d+))
```

For example:

```
USNM 139604
USNM 364282
```

## The Chrysler Museum of Art

* [https://chrysler.org](https://chrysler.org)

### Patterns

#### common

```
((?:[A-Z]?\d{2,4})\.(?:\d+)(?:\.\d+)*)
```

For example:

```
2012.14
66.34.4
71.1079
L2005.10.159
```

## Virginia Museum of Fine Arts

* [https://www.vmfa.museum](https://www.vmfa.museum)

### Patterns

#### common

```
((?:\d{2,4})\.(?:\d+)(?:(?:\.[0-9\-]*)*)?)
```

For example:

```
2014.369
2017.166
47.20.117
97.89.1-8
```

## Walker Art Center

* [https://walkerart.org](https://walkerart.org)

### Patterns

#### common

```
((?:\d{4})\.(?:\d+)(?:(?:\.[0-9\.\-]*)*)?)
```

For example:

```
1988.163.1
1993.194.2
2011.229
2019.139.1-.4
```

