Analysis
========

```
Size of ECMAP at end is 1 
{u'PULAUPASIRMANDI': ['470']}
Write to Shapefile!!
NEW/Unmatched DM! ==> 083/15/08
NEW/Unmatched DM! ==> 087/28/06
NEW/Unmatched DM! ==> 088/32/12
NEW/Unmatched DM! ==> 089/34/04
```

Logs:
=====

```
/Users/leow/PyOGR/bin/python /Users/leow/Desktop/PROJECTS/SINARPROJECT/playground-python/ogr/ogr.py
Sinar Project OGR Attribute Tables Processing!!!
{'geometry': 'Polygon',
 'properties': OrderedDict([(u'NAME', 'str:12'), (u'NAMA_DM', 'str:128'), (u'PAR_LAMA', 'str:5'), (u'DUN_LAMA', 'str:5'), (u'DM_LAMA', 'str:5'), (u'PENGUNDI', 'int:6'), (u'KODPAR', 'str:5'), (u'PAR_BARU', 'str:128'), (u'KODDUN', 'str:5'), (u'DUN_BARU', 'str:128'), (u'KODDM', 'str:5'), (u'DM_BARU', 'str:128'), (u'PENGUNDI_B', 'int:6')])}
in Extract Feature Map ...
in Extract Data ...
in Find DM Match of ED Data ...
Size of ECMAP at start is 506 
DM: KAMPUNG MELAYU has more than one possibilities!!
DM: TAMAN SENTOSA has more than one possibilities!!
DM: KAMPUNG BAHARU has more than one possibilities!!
DM: BUKIT DINDING has more than one possibilities!!
DM: CHENDERAWASIH has more than one possibilities!!
Found match in index 0 popping!
DM: KAMPUNG JAWA has more than one possibilities!!
DM is SUNGAI ISAP MURNI: 083/15/08
KeyError: SUNGAIISAPMURNI
DM: TANJUNG BATU has more than one possibilities!!
Found match in index 0 popping!
DM is BUKIT LADA: 087/28/06
IndexError: pop from empty list
DM: KAMPUNG BAHARU has more than one possibilities!!
DM is TANJUNG BELENGU: 088/32/12
KeyError: TANJUNGBELENGU
DM is SRI LAYANG: 089/34/04
IndexError: pop from empty list
Size of ECMAP at end is 1 
{u'PULAUPASIRMANDI': ['470']}
Write to Shapefile!!
NEW/Unmatched DM! ==> 083/15/08
NEW/Unmatched DM! ==> 087/28/06
NEW/Unmatched DM! ==> 088/32/12
NEW/Unmatched DM! ==> 089/34/04

Process finished with exit code 0

```

