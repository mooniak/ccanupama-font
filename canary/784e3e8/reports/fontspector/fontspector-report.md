## FontSpector report

fontspector version: 1.9.0






## Check results




<details><summary>[9] fonts/ttf/CCAnupamaCANARY-Regular.ttf</summary>
<div>


<details>
    <summary>⚠️ <b>WARN</b> Check that OS/2 fsSelection WWS bit is set correctly. (opentype/fsselection_wws)</summary>
    <div>








- ⚠️ **WARN** OS/2 fsSelection WWS bit is not set, and the font does not have name IDs 21/22 (WWS Family/Subfamily). If the font's naming is WWS-conformant, the WWS bit should be set. [code: no-wws-without-wws-names]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. (contour_count)</summary>
    <div>








- ⚠️ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are
     inferred from the typical amounts of contours observed in a
     large collection of reference font families. The divergences
     listed below may simply indicate a significantly different
     design on some of your glyphs. On the other hand, some of these
     may flag actual bugs in the font such as glyphs mapped to an
     incorrect codepoint. Please consider reviewing the design and
     codepoint assignment of these to make sure they are correct.


    The following glyphs do not have the recommended number of contours:
* uni0D85 (U+0D85): found 1, expected one of: [2, 3, 4]
* uni0D86 (U+0D86): found 2, expected one of: [3, 4, 5]
* uni0D87 (U+0D87): found 2, expected one of: [3, 4, 5]
* uni0D88 (U+0D88): found 2, expected one of: [3, 4, 5]
* uni0D89 (U+0D89): found 1, expected one of: [2, 3, 4]
* uni0D8D (U+0D8D): found 2, expected one of: [3, 4, 6]
* uni0D8E (U+0D8E): found 3, expected one of: [5, 6, 8]
* uni0D95 (U+0D95): found 1, expected one of: [3, 4]
* uni0D9E (U+0D9E): found 1, expected one of: [2, 3, 4]
* uni0DA1 (U+0DA1): found 1, expected one of: [3, 4, 5]
* uni0DA5 (U+0DA5): found 1, expected one of: [2, 3, 5]
* uni0DB5 (U+0DB5): found 1, expected one of: [2, 3]
* uni0DC1 (U+0DC1): found 1, expected one of: [2, 3, 4]
* semicolon (U+003B): found 1, expected one of: [2, 6]
* equal (U+003D): found 1, expected one of: [2, 6] [code: contour-count]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Does GPOS table have kerning information? (gpos_kerning_info)</summary>
    <div>








- ⚠️ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure indic fonts have the Indian Rupee Sign glyph. (rupee)</summary>
    <div>








- ⚠️ **WARN** Font is missing the Indian Rupee Sign glyph. Please add a glyph for Indian Rupee Sign (₹) at codepoint U+20B9. (Overriden: Sinhala fonts: U+20B9 is optional (Sri Lanka writes රු / Rs)) [code: missing-rupee]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs (unreachable_glyphs)</summary>
    <div>








- ⚠️ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

* nngasinh.alt1
* kSsasinh.alt1
* viramasinh.alt1 [code: unreachable-glyphs]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure font has overlaps bit set correctly. (overlaps_bit)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have overlaps but the overlaps bit is not set:
* uni0D8D (U+0D8D)
* uni0D8E (U+0D8E)
* uniE001 (U+E001)
* uni0DD1 (U+0DD1)
* rUusinh
* uni0D92 (U+0D92)
* uni0D88 (U+0D88)
* uni0DDD (U+0DDD)
* uni0DF2 (U+0DF2)
* uni0DD8 (U+0DD8)
* uni0DDA (U+0DDA) [code: no-overlaps-bit]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (googlefonts/meta/script_lang_tags)</summary>
    <div>








- ⚠️ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? (outline_colinear_vectors)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have colinear vectors:

* nnddsinh: from (326.0, 296.0) to (322.0, 296.0) is colinear with segment from (322.0, 296.0) to (320.0, 296.0) [code: found-colinear-vectors]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? (outline_jaggy_segments)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have jaggy segments:

* uni0D88 (U+0D88): Quad(QuadBez { p0: (627.5, 184.5), p1: (644.0, 201.0), p2: (657.0, 208.0) })/Quad(QuadBez { p0: (657.0, 208.0), p1: (647.0, 202.0), p2: (638.0, 202.0) }) = 2.663000766067174 degrees
* uni0DAD (U+0DAD): Quad(QuadBez { p0: (78.0, 165.0), p1: (78.0, 176.0), p2: (85.0, 180.0) })/Quad(QuadBez { p0: (85.0, 180.0), p1: (73.0, 174.0), p2: (62.0, 174.0) }) = 3.1798301198641643 degrees
* uni0DBB (U+0DBB): Quad(QuadBez { p0: (135.5, 239.0), p1: (121.0, 250.0), p2: (118.0, 267.0) })/Quad(QuadBez { p0: (118.0, 267.0), p1: (117.0, 252.0), p2: (116.0, 236.5) }) = 13.822054635731691 degrees
* uni0DD1 (U+0DD1): Quad(QuadBez { p0: (34.5, 184.5), p1: (51.0, 201.0), p2: (64.0, 208.0) })/Quad(QuadBez { p0: (64.0, 208.0), p1: (54.0, 202.0), p2: (45.0, 202.0) }) = 2.663000766067174 degrees
* uniE000 (U+E000): Quad(QuadBez { p0: (78.0, 171.0), p1: (78.0, 182.0), p2: (84.0, 186.0) })/Quad(QuadBez { p0: (84.0, 186.0), p1: (72.0, 180.0), p2: (60.0, 180.0) }) = 7.125016348901757 degrees
* tthIsinh: Quad(QuadBez { p0: (581.0, 403.0), p1: (568.0, 403.0), p2: (557.0, 413.0) })/Quad(QuadBez { p0: (557.0, 413.0), p1: (588.0, 375.0), p2: (607.5, 327.0) }) = 8.519107488938461 degrees
* tthIsinh: Quad(QuadBez { p0: (494.0, 476.0), p1: (525.0, 451.0), p2: (550.0, 422.0) })/Quad(QuadBez { p0: (550.0, 422.0), p1: (543.0, 434.0), p2: (543.0, 447.0) }) = 10.507168037411839 degrees
* khIisinh: Quad(QuadBez { p0: (642.0, 578.5), p1: (623.0, 581.0), p2: (605.0, 583.0) })/Quad(QuadBez { p0: (605.0, 583.0), p1: (616.0, 579.0), p2: (621.0, 567.5) }) = 13.642914775990079 degrees
* ttIisinh: Quad(QuadBez { p0: (433.0, 611.0), p1: (447.0, 601.0), p2: (450.0, 581.0) })/Quad(QuadBez { p0: (450.0, 581.0), p1: (450.0, 582.0), p2: (450.0, 583.0) }) = 8.530765609948139 degrees
* dhIisinh: Quad(QuadBez { p0: (561.0, 579.5), p1: (573.0, 589.0), p2: (589.0, 589.0) })/Quad(QuadBez { p0: (589.0, 589.0), p1: (537.0, 595.0), p2: (487.0, 595.0) }) = 6.581944655178027 degrees
* dhIisinh: Quad(QuadBez { p0: (644.0, 571.5), p1: (627.0, 582.0), p2: (609.0, 586.0) })/Quad(QuadBez { p0: (609.0, 586.0), p1: (624.0, 581.0), p2: (630.0, 568.5) }) = 5.906141113770435 degrees
* rUsinh: Quad(QuadBez { p0: (135.5, 239.0), p1: (121.0, 250.0), p2: (118.0, 267.0) })/Quad(QuadBez { p0: (118.0, 267.0), p1: (117.0, 252.0), p2: (116.0, 236.5) }) = 13.822054635731691 degrees
* rUusinh: Quad(QuadBez { p0: (135.5, 239.0), p1: (121.0, 250.0), p2: (118.0, 267.0) })/Quad(QuadBez { p0: (118.0, 267.0), p1: (117.0, 252.0), p2: (116.0, 236.5) }) = 13.822054635731691 degrees
* rUusinh: Quad(QuadBez { p0: (535.5, 184.5), p1: (552.0, 201.0), p2: (565.0, 208.0) })/Quad(QuadBez { p0: (565.0, 208.0), p1: (555.0, 202.0), p2: (546.0, 202.0) }) = 2.663000766067174 degrees
* six (U+0036): Quad(QuadBez { p0: (161.5, 481.0), p1: (127.0, 432.0), p2: (106.0, 354.0) })/Quad(QuadBez { p0: (106.0, 354.0), p1: (111.0, 369.0), p2: (128.0, 379.0) }) = 3.3664606634297236 degrees
* six (U+0036): Quad(QuadBez { p0: (116.5, 313.0), p1: (103.0, 328.0), p2: (104.0, 345.0) })/Quad(QuadBez { p0: (104.0, 345.0), p1: (101.0, 330.0), p2: (100.0, 312.5) }) = 7.943471810590459 degrees
* nine (U+0039): Quad(QuadBez { p0: (307.5, 264.0), p1: (337.0, 314.0), p2: (347.0, 362.0) })/Quad(QuadBez { p0: (347.0, 362.0), p1: (343.0, 347.0), p2: (325.5, 337.0) }) = 3.163128246116971 degrees
* nine (U+0039): Quad(QuadBez { p0: (336.0, 403.5), p1: (349.0, 389.0), p2: (349.0, 373.0) })/Quad(QuadBez { p0: (349.0, 373.0), p1: (354.0, 402.0), p2: (354.0, 438.0) }) = 9.782407031807285 degrees
* uniE004 (U+E004): Quad(QuadBez { p0: (143.0, 119.0), p1: (143.0, 126.0), p2: (150.0, 133.0) })/Quad(QuadBez { p0: (150.0, 133.0), p1: (135.0, 121.0), p2: (119.0, 121.0) }) = 6.340191745909908 degrees [code: found-jaggy-segments]
  
  

</div>
</details>


</div>
</details>


<details><summary>[1] fonts/ttf</summary>
<div>


<details>
    <summary>⚠️ <b>WARN</b> Ensure Fonts have 'ital' STAT axis. (opentype/STAT/ital_axis)</summary>
    <div>








- ⚠️ **WARN** Static font is missing the 'STAT' table. [code: no-stat-table]
  
  

</div>
</details>


</div>
</details>






### Summary

| ⚠️ WARN | ℹ️ INFO | ✅ PASS | ⏩ SKIP | 
| ---|---|---|---|
| 10 | 9 | 85 | 51 | 
| 6% | 6% | 55% | 33% | 



