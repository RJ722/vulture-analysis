# Vulture report for Sharppy

[Sharppy - Sounding/Hodograph Analysis and Research Program in Python.](https://github.com/sharppy/SHARPpy)

We used vulture (https://github.com/jendrikseipp/vulture) to search
for unused code in your project. You can find the report below. It 
would be great if you could give us feedback about which items are 
actually used or unused. This would allow us to improve vulture and
ideally it also helps you to remove obsolete code or even find typos 
and bugs.

### Command

```
vulture .
```

### Raw Output:
```
datasources/available.py:112: unused variable 'nam' (60% confidence)
datasources/available.py:112: unused variable 'off' (60% confidence)
datasources/available.py:173: unused function '_available_nssl' (60% confidence)
datasources/available.py:173: unused variable 'ens' (60% confidence)
datasources/available.py:174: unused variable 'path_to_nssl_wrf' (60% confidence)
datasources/available.py:175: unused variable 'path_to_nssl_wrf_ens' (60% confidence)
datasources/data_source.py:233: unused function 'getFields' (60% confidence)
datasources/data_source.py:236: unused function 'isAvailable' (60% confidence)
datasources/data_source.py:289: unused function 'getDailyCycles' (60% confidence)
datasources/data_source.py:293: unused function 'getDelays' (60% confidence)
datasources/data_source.py:297: unused function 'getArchiveLens' (60% confidence)
datasources/data_source.py:342: unused function 'getName' (60% confidence)
datasources/data_source.py:348: unused function 'isObserved' (60% confidence)
runsharp/full_gui.py:37: unused import 'wraps' (90% confidence)
runsharp/full_gui.py:38: unused import 'cProfile' (90% confidence)
runsharp/full_gui.py:42: unused import 'wraps' (90% confidence)
runsharp/full_gui.py:482: unused variable 'decname' (60% confidence)
runsharp/full_gui.py:498: unused function 'hasConnection' (60% confidence)
runsharp/full_gui.py:639: unused function 'keyPressEvent' (60% confidence)
runsharp/full_gui.py:665: unused variable 'win' (60% confidence)
setup.py:2: unused import 'find_packages' (90% confidence)
sharppy/databases/inset_data.py:6: unused function 'sherbData' (60% confidence)
sharppy/databases/sars.py:319: unused variable 'avg_hail_size' (60% confidence)
sharppy/io/buf_decoder.py:23: unused variable 'num_members' (60% confidence)
sharppy/io/buf_decoder.py:58: unused variable 'wmo_id' (60% confidence)
sharppy/io/buf_decoder.py:62: unused variable 'wmo_id' (60% confidence)
sharppy/io/buf_decoder.py:66: unused variable 'slon' (60% confidence)
sharppy/io/buf_decoder.py:67: unused variable 'selv' (60% confidence)
sharppy/io/buf_decoder.py:68: unused variable 'stim' (60% confidence)
sharppy/io/decoder.py:108: unused variable 'bd' (60% confidence)
sharppy/io/qc_tools.py:63: unused function 'isPRESValid' (60% confidence)
sharppy/io/qc_tools.py:85: unused variable 'total' (60% confidence)
sharppy/io/qc_tools.py:111: unused variable 'total' (60% confidence)
sharppy/sharptab/constants.py:18: unused variable 'ORANGE' (60% confidence)
sharppy/sharptab/params.py:99: unused attribute 'desc' (60% confidence)
sharppy/sharptab/params.py:110: unused attribute 'desc' (60% confidence)
sharppy/sharptab/params.py:123: unused attribute 'desc' (60% confidence)
sharppy/sharptab/params.py:139: unused attribute 'desc' (60% confidence)
sharppy/sharptab/params.py:154: unused attribute 'desc' (60% confidence)
sharppy/sharptab/params.py:169: unused attribute 'desc' (60% confidence)
sharppy/sharptab/params.py:176: unused attribute 'desc' (60% confidence)
sharppy/sharptab/params.py:180: unused attribute 'pbot' (60% confidence)
sharppy/sharptab/params.py:181: unused attribute 'pbot' (60% confidence)
sharppy/sharptab/params.py:183: unused attribute 'pbot' (60% confidence)
sharppy/sharptab/params.py:210: unused attribute 'blayer' (60% confidence)
sharppy/sharptab/params.py:211: unused attribute 'tlayer' (60% confidence)
sharppy/sharptab/params.py:212: unused attribute 'entrain' (60% confidence)
sharppy/sharptab/params.py:220: unused attribute 'mplhght' (60% confidence)
sharppy/sharptab/params.py:226: unused attribute 'p0c' (60% confidence)
sharppy/sharptab/params.py:227: unused attribute 'pm10c' (60% confidence)
sharppy/sharptab/params.py:228: unused attribute 'pm20c' (60% confidence)
sharppy/sharptab/params.py:229: unused attribute 'pm30c' (60% confidence)
sharppy/sharptab/params.py:230: unused attribute 'hght0c' (60% confidence)
sharppy/sharptab/params.py:231: unused attribute 'hghtm10c' (60% confidence)
sharppy/sharptab/params.py:232: unused attribute 'hghtm20c' (60% confidence)
sharppy/sharptab/params.py:233: unused attribute 'hghtm30c' (60% confidence)
sharppy/sharptab/params.py:240: unused attribute 'brnu' (60% confidence)
sharppy/sharptab/params.py:241: unused attribute 'brnv' (60% confidence)
sharppy/sharptab/params.py:242: unused attribute 'brn' (60% confidence)
sharppy/sharptab/params.py:243: unused attribute 'limax' (60% confidence)
sharppy/sharptab/params.py:244: unused attribute 'limaxpres' (60% confidence)
sharppy/sharptab/params.py:245: unused attribute 'cap' (60% confidence)
sharppy/sharptab/params.py:246: unused attribute 'cappres' (60% confidence)
sharppy/sharptab/params.py:247: unused attribute 'bmin' (60% confidence)
sharppy/sharptab/params.py:248: unused attribute 'bminpres' (60% confidence)
sharppy/sharptab/params.py:771: unused variable 'mean_wdir' (60% confidence)
sharppy/sharptab/params.py:1354: unused variable 'cinh_old' (60% confidence)
sharppy/sharptab/params.py:1359: unused attribute 'blayer' (60% confidence)
sharppy/sharptab/params.py:1360: unused attribute 'pbot' (60% confidence)
sharppy/sharptab/params.py:1363: unused attribute 'tlayer' (60% confidence)
sharppy/sharptab/params.py:1369: unused attribute 'blayer' (60% confidence)
sharppy/sharptab/params.py:1389: unused variable 'bltheta' (60% confidence)
sharppy/sharptab/params.py:1412: unused attribute 'blayer' (60% confidence)
sharppy/sharptab/params.py:1538: unused variable 'cinh_old' (60% confidence)
sharppy/sharptab/params.py:1543: unused attribute 'blayer' (60% confidence)
sharppy/sharptab/params.py:1544: unused attribute 'pbot' (60% confidence)
sharppy/sharptab/params.py:1547: unused attribute 'tlayer' (60% confidence)
sharppy/sharptab/params.py:1552: unused attribute 'blayer' (60% confidence)
sharppy/sharptab/params.py:1579: unused variable 'bltheta' (60% confidence)
sharppy/sharptab/params.py:1603: unused attribute 'blayer' (60% confidence)
sharppy/sharptab/params.py:1614: unused attribute 'p0c' (60% confidence)
sharppy/sharptab/params.py:1615: unused attribute 'pm10c' (60% confidence)
sharppy/sharptab/params.py:1616: unused attribute 'pm20c' (60% confidence)
sharppy/sharptab/params.py:1617: unused attribute 'pm30c' (60% confidence)
sharppy/sharptab/params.py:1618: unused attribute 'hght0c' (60% confidence)
sharppy/sharptab/params.py:1619: unused attribute 'hghtm10c' (60% confidence)
sharppy/sharptab/params.py:1620: unused attribute 'hghtm20c' (60% confidence)
sharppy/sharptab/params.py:1621: unused attribute 'hghtm30c' (60% confidence)
sharppy/sharptab/params.py:1863: unused variable 'cinh_old' (60% confidence)
sharppy/sharptab/params.py:1867: unused attribute 'cap' (60% confidence)
sharppy/sharptab/params.py:1868: unused attribute 'cappres' (60% confidence)
sharppy/sharptab/params.py:1890: unused attribute 'limax' (60% confidence)
sharppy/sharptab/params.py:1891: unused attribute 'limaxpres' (60% confidence)
sharppy/sharptab/params.py:1916: unused attribute 'mplhght' (60% confidence)
sharppy/sharptab/params.py:1947: unused attribute 'bmin' (60% confidence)
sharppy/sharptab/params.py:1948: unused attribute 'bminpres' (60% confidence)
sharppy/sharptab/params.py:1987: unused attribute 'brn' (60% confidence)
sharppy/sharptab/params.py:1988: unused attribute 'brnu' (60% confidence)
sharppy/sharptab/params.py:1989: unused attribute 'brnv' (60% confidence)
sharppy/sharptab/params.py:2002: unused attribute 'brnu' (60% confidence)
sharppy/sharptab/params.py:2003: unused attribute 'brnv' (60% confidence)
sharppy/sharptab/params.py:2004: unused attribute 'brn' (60% confidence)
sharppy/sharptab/params.py:2010: unused attribute 'brnu' (60% confidence)
sharppy/sharptab/params.py:2011: unused attribute 'brnv' (60% confidence)
sharppy/sharptab/params.py:2014: unused attribute 'brn' (60% confidence)
sharppy/sharptab/params.py:2213: unused variable 'sfc_theta' (60% confidence)
sharppy/sharptab/params.py:2603: unused variable 'drtemp' (60% confidence)
sharppy/sharptab/params.py:2607: unused function 'precip_eff' (60% confidence)
sharppy/sharptab/prof_collection.py:42: unused attribute '_cancel_copy' (60% confidence)
sharppy/sharptab/prof_collection.py:231: unused function 'advanceHighlight' (60% confidence)
sharppy/sharptab/profile.py:99: unused attribute 'profile' (60% confidence)
sharppy/sharptab/profile.py:367: unused function 'get_theta_profile' (60% confidence)
sharppy/sharptab/profile.py:796: unused attribute 'left_scp' (60% confidence)
sharppy/sharptab/profile.py:800: unused attribute 'left_scp' (60% confidence)
sharppy/sharptab/utils.py:89: unused function 'MS2MPH' (60% confidence)
sharppy/sharptab/utils.py:106: unused function 'MPH2MS' (60% confidence)
sharppy/sharptab/utils.py:123: unused function 'MPH2KTS' (60% confidence)
sharppy/sharptab/utils.py:174: unused function 'FT2M' (60% confidence)
sharppy/sharptab/winds.py:177: unused function 'non_parcel_bunkers_motion_experimental' (60% confidence)
sharppy/sounding.py:44: unused variable 'obs24' (60% confidence)
sharppy/sounding.py:51: unused variable 'obstring2' (60% confidence)
sharppy/sounding.py:223: unused variable 'test' (60% confidence)
sharppy/viz/analogues.py:90: unused attribute 'divide' (60% confidence)
sharppy/viz/analogues.py:413: unused function 'mousePressEvent' (60% confidence)
sharppy/viz/barbs.py:62: unused function 'drawBarb_old' (60% confidence)
sharppy/viz/fire.py:37: unused attribute 'fosberg_metrics' (60% confidence)
sharppy/viz/fire.py:117: unused attribute 'fosberg_x' (60% confidence)
sharppy/viz/hodo.py:23: unused attribute 'first' (60% confidence)
sharppy/viz/hodo.py:241: unused function 'hodo_to_pix' (60% confidence)
sharppy/viz/hodo.py:337: unused attribute 'center_loc' (60% confidence)
sharppy/viz/hodo.py:519: unused attribute 'center_loc' (60% confidence)
sharppy/viz/hodo.py:531: unused attribute 'center_loc' (60% confidence)
sharppy/viz/hodo.py:541: unused attribute 'center_loc' (60% confidence)
sharppy/viz/hodo.py:571: unused function 'mousePressEvent' (60% confidence)
sharppy/viz/hodo.py:596: unused function 'mouseReleaseEvent' (60% confidence)
sharppy/viz/hodo.py:734: unused function 'calculateStormMode' (60% confidence)
sharppy/viz/hodo.py:785: unused function 'mouseMoveEvent' (60% confidence)
sharppy/viz/map.py:32: unused function 'getPhi0' (60% confidence)
sharppy/viz/map.py:207: unused variable 'south' (60% confidence)
sharppy/viz/map.py:208: unused variable 'north' (60% confidence)
sharppy/viz/map.py:213: unused variable 'typ' (60% confidence)
sharppy/viz/map.py:277: unused attribute 'map_rot' (60% confidence)
sharppy/viz/map.py:504: unused variable 'clicked_id' (60% confidence)
sharppy/viz/map.py:511: unused variable 'clicked_id' (60% confidence)
sharppy/viz/map.py:544: unused function 'mousePressEvent' (60% confidence)
sharppy/viz/map.py:547: unused function 'mouseMoveEvent' (60% confidence)
sharppy/viz/map.py:556: unused variable 'is_invertible' (60% confidence)
sharppy/viz/map.py:561: unused function 'mouseReleaseEvent' (60% confidence)
sharppy/viz/map.py:583: unused function 'mouseDoubleClickEvent' (60% confidence)
sharppy/viz/map.py:584: unused variable 'is_invertible' (60% confidence)
sharppy/viz/skew.py:156: unused function 'draw_moist_adiabat' (60% confidence)
sharppy/viz/skew.py:337: unused attribute 'dp' (60% confidence)
sharppy/viz/skew.py:560: unused function 'mouseReleaseEvent' (60% confidence)
sharppy/viz/skew.py:589: unused function 'mousePressEvent' (60% confidence)
sharppy/viz/skew.py:640: unused function 'mouseMoveEvent' (60% confidence)
sharppy/viz/skew.py:1078: unused variable 'text_offset' (60% confidence)
sharppy/viz/SPCWindow.py:59: unused attribute 'mode' (60% confidence)
sharppy/viz/SPCWindow.py:81: unused attribute 'swap_inset' (60% confidence)
sharppy/viz/SPCWindow.py:729: unused function 'keyPressEvent' (60% confidence)
sharppy/viz/thermo.py:148: unused function 'mouseDoubleClickEvent' (60% confidence)
sharppy/viz/thermo.py:593: unused function 'mousePressEvent' (60% confidence)
sharppy/viz/vrot.py:274: unused function 'mouseDoubleClickEvent' (60% confidence)
utils/async.py:81: unused variable 'prio' (60% confidence)
utils/frozenutils.py:15: unused function 'freezeSupport' (60% confidence)
```

#### True Positives

After inspecting the source code detected by Vulture as dead, we confirmed that
the following parts indeed aren't being used anywhere and can therefore be
deleted safely:

```
datasources/available.py:112: unused variable 'nam' (60% confidence)
datasources/available.py:112: unused variable 'off' (60% confidence)
datasources/available.py:173: unused function '_available_nssl' (60% confidence)
datasources/available.py:173: unused variable 'ens' (60% confidence)
datasources/available.py:174: unused variable 'path_to_nssl_wrf' (60% confidence)
datasources/available.py:175: unused variable 'path_to_nssl_wrf_ens' (60% confidence)
runsharp/full_gui.py:37: unused import 'wraps' (90% confidence)
runsharp/full_gui.py:38: unused import 'cProfile' (90% confidence)
runsharp/full_gui.py:42: unused import 'wraps' (90% confidence)
runsharp/full_gui.py:482: unused variable 'decname' (60% confidence)
runsharp/full_gui.py:665: unused variable 'win' (60% confidence)
setup.py:2: unused import 'find_packages' (90% confidence)
sharppy/databases/inset_data.py:6: unused function 'sherbData' (60% confidence)
sharppy/databases/sars.py:319: unused variable 'avg_hail_size' (60% confidence)
sharppy/io/buf_decoder.py:23: unused variable 'num_members' (60% confidence)
sharppy/io/buf_decoder.py:58: unused variable 'wmo_id' (60% confidence)
sharppy/io/buf_decoder.py:62: unused variable 'wmo_id' (60% confidence)
sharppy/io/buf_decoder.py:66: unused variable 'slon' (60% confidence)
sharppy/io/buf_decoder.py:67: unused variable 'selv' (60% confidence)
sharppy/io/buf_decoder.py:68: unused variable 'stim' (60% confidence)
sharppy/io/decoder.py:108: unused variable 'bd' (60% confidence)
sharppy/io/qc_tools.py:63: unused function 'isPRESValid' (60% confidence)
sharppy/io/qc_tools.py:85: unused variable 'total' (60% confidence)
sharppy/io/qc_tools.py:111: unused variable 'total' (60% confidence)
sharppy/sharptab/constants.py:18: unused variable 'ORANGE' (60% confidence)
sharppy/sharptab/prof_collection.py:42: unused attribute '_cancel_copy' (60% confidence)
sharppy/sharptab/prof_collection.py:231: unused function 'advanceHighlight' (60% confidence)
sharppy/sharptab/profile.py:99: unused attribute 'profile' (60% confidence)
sharppy/sharptab/profile.py:367: unused function 'get_theta_profile' (60% confidence)
sharppy/sharptab/profile.py:796: unused attribute 'left_scp' (60% confidence)
sharppy/sharptab/profile.py:800: unused attribute 'left_scp' (60% confidence)
sharppy/sharptab/utils.py:89: unused function 'MS2MPH' (60% confidence)
sharppy/sharptab/utils.py:106: unused function 'MPH2MS' (60% confidence)
sharppy/sharptab/utils.py:123: unused function 'MPH2KTS' (60% confidence)
sharppy/sharptab/utils.py:174: unused function 'FT2M' (60% confidence)
sharppy/sharptab/winds.py:177: unused function 'non_parcel_bunkers_motion_experimental' (60% confidence)
sharppy/sounding.py:44: unused variable 'obs24' (60% confidence)
sharppy/sounding.py:51: unused variable 'obstring2' (60% confidence)
sharppy/sounding.py:223: unused variable 'test' (60% confidence)
sharppy/viz/barbs.py:62: unused function 'drawBarb_old' (60% confidence)
sharppy/viz/fire.py:37: unused attribute 'fosberg_metrics' (60% confidence)
sharppy/viz/fire.py:117: unused attribute 'fosberg_x' (60% confidence)
sharppy/viz/hodo.py:23: unused attribute 'first' (60% confidence)
sharppy/viz/hodo.py:241: unused function 'hodo_to_pix' (60% confidence)
sharppy/viz/map.py:32: unused function 'getPhi0' (60% confidence)
sharppy/viz/map.py:207: unused variable 'south' (60% confidence)
sharppy/viz/map.py:208: unused variable 'north' (60% confidence)
sharppy/viz/map.py:213: unused variable 'typ' (60% confidence)
sharppy/viz/map.py:277: unused attribute 'map_rot' (60% confidence)
sharppy/viz/map.py:504: unused variable 'clicked_id' (60% confidence)
sharppy/viz/map.py:511: unused variable 'clicked_id' (60% confidence)
sharppy/viz/map.py:556: unused variable 'is_invertible' (60% confidence)
sharppy/viz/map.py:584: unused variable 'is_invertible' (60% confidence)
sharppy/viz/skew.py:1078: unused variable 'text_offset' (60% confidence)
sharppy/viz/SPCWindow.py:81: unused attribute 'swap_inset' (60% confidence)
utils/async.py:81: unused variable 'prio' (60% confidence)
utils/frozenutils.py:15: unused function 'freezeSupport' (60% confidence)
```

#### False Positives

Since the project uses PySide2 which internally overloads the methods defined
in C++ code, it is natural for Vulture to detect those methods as unused. All
the false positives reported by Vulture are listed here: (Nomenclature of these
functions gives some hint)

```
runsharp/full_gui.py:498: unused function 'hasConnection' (60% confidence)
runsharp/full_gui.py:639: unused function 'keyPressEvent' (60% confidence)
sharppy/viz/analogues.py:413: unused function 'mousePressEvent' (60% confidence)
sharppy/viz/hodo.py:571: unused function 'mousePressEvent' (60% confidence)
sharppy/viz/hodo.py:596: unused function 'mouseReleaseEvent' (60% confidence)
sharppy/viz/hodo.py:734: unused function 'calculateStormMode' (60% confidence)
sharppy/viz/hodo.py:785: unused function 'mouseMoveEvent' (60% confidence)
sharppy/viz/map.py:544: unused function 'mousePressEvent' (60% confidence)
sharppy/viz/map.py:547: unused function 'mouseMoveEvent' (60% confidence)
sharppy/viz/map.py:561: unused function 'mouseReleaseEvent' (60% confidence)
sharppy/viz/map.py:583: unused function 'mouseDoubleClickEvent' (60% confidence)
sharppy/viz/skew.py:337: unused attribute 'dp' (60% confidence)
sharppy/viz/skew.py:560: unused function 'mouseReleaseEvent' (60% confidence)
sharppy/viz/skew.py:589: unused function 'mousePressEvent' (60% confidence)
sharppy/viz/skew.py:640: unused function 'mouseMoveEvent' (60% confidence)
sharppy/viz/SPCWindow.py:729: unused function 'keyPressEvent' (60% confidence)
sharppy/viz/thermo.py:148: unused function 'mouseDoubleClickEvent' (60% confidence)
sharppy/viz/thermo.py:593: unused function 'mousePressEvent' (60% confidence)
sharppy/viz/vrot.py:274: unused function 'mouseDoubleClickEvent' (60% confidence)
``` 

### Unsure

I am unsure about the following results:

```
datasources/data_source.py:233: unused function 'getFields' (60% confidence)
datasources/data_source.py:236: unused function 'isAvailable' (60% confidence)
datasources/data_source.py:289: unused function 'getDailyCycles' (60% confidence)
datasources/data_source.py:293: unused function 'getDelays' (60% confidence)
datasources/data_source.py:297: unused function 'getArchiveLens' (60% confidence)
datasources/data_source.py:348: unused function 'isObserved' (60% confidence)
datasources/data_source.py:342: unused function 'getName' (60% confidence)
sharppy/viz/analogues.py:90: unused attribute 'divide' (60% confidence)
sharppy/viz/hodo.py:337: unused attribute 'center_loc' (60% confidence)
sharppy/viz/hodo.py:519: unused attribute 'center_loc' (60% confidence)
sharppy/viz/hodo.py:531: unused attribute 'center_loc' (60% confidence)
sharppy/viz/hodo.py:541: unused attribute 'center_loc' (60% confidence)
sharppy/viz/skew.py:156: unused function 'draw_moist_adiabat' (60% confidence)
sharppy/viz/SPCWindow.py:59: unused attribute 'mode' (60% confidence)
```

`sharppy/sharptab/params.py`: Parameters defined here seem to be dynamically
loaded somewhere else, but I'm not sure. Here are the results:

```
sharppy/sharptab/params.py:99: unused attribute 'desc' (60% confidence)
sharppy/sharptab/params.py:110: unused attribute 'desc' (60% confidence)
sharppy/sharptab/params.py:123: unused attribute 'desc' (60% confidence)
sharppy/sharptab/params.py:139: unused attribute 'desc' (60% confidence)
sharppy/sharptab/params.py:154: unused attribute 'desc' (60% confidence)
sharppy/sharptab/params.py:169: unused attribute 'desc' (60% confidence)
sharppy/sharptab/params.py:176: unused attribute 'desc' (60% confidence)
sharppy/sharptab/params.py:180: unused attribute 'pbot' (60% confidence)
sharppy/sharptab/params.py:181: unused attribute 'pbot' (60% confidence)
sharppy/sharptab/params.py:183: unused attribute 'pbot' (60% confidence)
sharppy/sharptab/params.py:210: unused attribute 'blayer' (60% confidence)
sharppy/sharptab/params.py:211: unused attribute 'tlayer' (60% confidence)
sharppy/sharptab/params.py:212: unused attribute 'entrain' (60% confidence)
sharppy/sharptab/params.py:220: unused attribute 'mplhght' (60% confidence)
sharppy/sharptab/params.py:226: unused attribute 'p0c' (60% confidence)
sharppy/sharptab/params.py:227: unused attribute 'pm10c' (60% confidence)
sharppy/sharptab/params.py:228: unused attribute 'pm20c' (60% confidence)
sharppy/sharptab/params.py:229: unused attribute 'pm30c' (60% confidence)
sharppy/sharptab/params.py:230: unused attribute 'hght0c' (60% confidence)
sharppy/sharptab/params.py:231: unused attribute 'hghtm10c' (60% confidence)
sharppy/sharptab/params.py:232: unused attribute 'hghtm20c' (60% confidence)
sharppy/sharptab/params.py:233: unused attribute 'hghtm30c' (60% confidence)
sharppy/sharptab/params.py:240: unused attribute 'brnu' (60% confidence)
sharppy/sharptab/params.py:241: unused attribute 'brnv' (60% confidence)
sharppy/sharptab/params.py:242: unused attribute 'brn' (60% confidence)
sharppy/sharptab/params.py:243: unused attribute 'limax' (60% confidence)
sharppy/sharptab/params.py:244: unused attribute 'limaxpres' (60% confidence)
sharppy/sharptab/params.py:245: unused attribute 'cap' (60% confidence)
sharppy/sharptab/params.py:246: unused attribute 'cappres' (60% confidence)
sharppy/sharptab/params.py:247: unused attribute 'bmin' (60% confidence)
sharppy/sharptab/params.py:248: unused attribute 'bminpres' (60% confidence)
sharppy/sharptab/params.py:771: unused variable 'mean_wdir' (60% confidence)
sharppy/sharptab/params.py:1354: unused variable 'cinh_old' (60% confidence)
sharppy/sharptab/params.py:1359: unused attribute 'blayer' (60% confidence)
sharppy/sharptab/params.py:1360: unused attribute 'pbot' (60% confidence)
sharppy/sharptab/params.py:1363: unused attribute 'tlayer' (60% confidence)
sharppy/sharptab/params.py:1369: unused attribute 'blayer' (60% confidence)
sharppy/sharptab/params.py:1389: unused variable 'bltheta' (60% confidence)
sharppy/sharptab/params.py:1412: unused attribute 'blayer' (60% confidence)
sharppy/sharptab/params.py:1538: unused variable 'cinh_old' (60% confidence)
sharppy/sharptab/params.py:1543: unused attribute 'blayer' (60% confidence)
sharppy/sharptab/params.py:1544: unused attribute 'pbot' (60% confidence)
sharppy/sharptab/params.py:1547: unused attribute 'tlayer' (60% confidence)
sharppy/sharptab/params.py:1552: unused attribute 'blayer' (60% confidence)
sharppy/sharptab/params.py:1579: unused variable 'bltheta' (60% confidence)
sharppy/sharptab/params.py:1603: unused attribute 'blayer' (60% confidence)
sharppy/sharptab/params.py:1614: unused attribute 'p0c' (60% confidence)
sharppy/sharptab/params.py:1615: unused attribute 'pm10c' (60% confidence)
sharppy/sharptab/params.py:1616: unused attribute 'pm20c' (60% confidence)
sharppy/sharptab/params.py:1617: unused attribute 'pm30c' (60% confidence)
sharppy/sharptab/params.py:1618: unused attribute 'hght0c' (60% confidence)
sharppy/sharptab/params.py:1619: unused attribute 'hghtm10c' (60% confidence)
sharppy/sharptab/params.py:1620: unused attribute 'hghtm20c' (60% confidence)
sharppy/sharptab/params.py:1621: unused attribute 'hghtm30c' (60% confidence)
sharppy/sharptab/params.py:1863: unused variable 'cinh_old' (60% confidence)
sharppy/sharptab/params.py:1867: unused attribute 'cap' (60% confidence)
sharppy/sharptab/params.py:1868: unused attribute 'cappres' (60% confidence)
sharppy/sharptab/params.py:1890: unused attribute 'limax' (60% confidence)
sharppy/sharptab/params.py:1891: unused attribute 'limaxpres' (60% confidence)
sharppy/sharptab/params.py:1916: unused attribute 'mplhght' (60% confidence)
sharppy/sharptab/params.py:1947: unused attribute 'bmin' (60% confidence)
sharppy/sharptab/params.py:1948: unused attribute 'bminpres' (60% confidence)
sharppy/sharptab/params.py:1987: unused attribute 'brn' (60% confidence)
sharppy/sharptab/params.py:1988: unused attribute 'brnu' (60% confidence)
sharppy/sharptab/params.py:1989: unused attribute 'brnv' (60% confidence)
sharppy/sharptab/params.py:2002: unused attribute 'brnu' (60% confidence)
sharppy/sharptab/params.py:2003: unused attribute 'brnv' (60% confidence)
sharppy/sharptab/params.py:2004: unused attribute 'brn' (60% confidence)
sharppy/sharptab/params.py:2010: unused attribute 'brnu' (60% confidence)
sharppy/sharptab/params.py:2011: unused attribute 'brnv' (60% confidence)
sharppy/sharptab/params.py:2014: unused attribute 'brn' (60% confidence)
sharppy/sharptab/params.py:2213: unused variable 'sfc_theta' (60% confidence)
sharppy/sharptab/params.py:2603: unused variable 'drtemp' (60% confidence)
sharppy/sharptab/params.py:2607: unused function 'precip_eff' (60% confidence)
```