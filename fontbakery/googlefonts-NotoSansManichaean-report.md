## Fontbakery report

Fontbakery version: 0.8.9

<details><summary><b>[11] NotoSansManichaean-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2018-2022 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansManichaean/googlefonts/ttf/NotoSansManichaean-Regular.ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 995, but got 790 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Check that texts shape as per expectation (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/shaping/regression">com.google.fonts/check/shaping/regression</a>)</summary><div>


* 🔥 **FAIL** qa/shaping_tests/manichaean.json: Expected and actual shaping not matching
<div class="shaping">


<style type="text/css">
    @font-face {font-family: "TestFont"; src: url(../../fonts/NotoSansManichaean/googlefonts/ttf/NotoSansManichaean-Regular.ttf);}
    .tf { font-family: "TestFont"; }
    .shaping pre { font-size: 1.2rem; }
    .shaping li {
        font-size: 1.2rem;
        border-top: 1px solid #ddd;
        padding: 12px;
        margin-top: 12px;
    }
    .shaping-svg {
        height: 100px;
        margin: 10px;
        transform: matrix(1, 0, 0, -1, 0, 0);
    }
</style>

<h4>qa/shaping_tests/manichaean.json: Expected and actual shaping not matching</h4>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐫋𐫥𐫝𐫏𐫛𐫦𐫁𐫦</span> (Added by SIESTA)</li>


<pre>Expected: u10AE6=6@691,0+0|u10AC1.fina=6+999|u10AE6=4@447,0+0|u10ADB.init=4+487|u10ACF=3+507|u10ADD=2+901|u10AE5=0@466,59+0|u10ACB=0+538</pre>



<pre>Got     : u10AE6=6@691,0+0|u10AC1.fina=6+999|u10AE6=4@447,0+0|u10ADB.init=4+487|u10ADD10ACF=2+1104|u10AE5=0@466,59+0|u10ACB=0+538</pre>



<pre>                                                                                    ^^^^^^^^^^   ^^   ++
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3128 2130" transform="matrix(1 0 0 -1 0 0)">
<path d="M-69.0,-219.0Q-91.0,-219.0 -112.0,-208.0Q-133.0,-197.0 -146.5,-179.0Q-160.0,-161.0 -160.0,-139.0Q-160.0,-106.0 -142.0,-82.5Q-124.0,-59.0 -91.0,-59.0Q-69.0,-59.0 -48.0,-70.0Q-27.0,-81.0 -13.5,-99.0Q0.0,-117.0 0.0,-139.0Q0.0,-172.0 -18.0,-195.5Q-36.0,-219.0 -69.0,-219.0ZM-313.0,-219.0Q-335.0,-219.0 -356.0,-208.0Q-377.0,-197.0 -390.5,-179.0Q-404.0,-161.0 -404.0,-139.0Q-404.0,-106.0 -386.0,-82.5Q-368.0,-59.0 -335.0,-59.0Q-313.0,-59.0 -292.0,-70.0Q-271.0,-81.0 -257.5,-99.0Q-244.0,-117.0 -244.0,-139.0Q-244.0,-172.0 -262.5,-195.5Q-281.0,-219.0 -313.0,-219.0Z"  transform="translate(691, 840)"/>
<path d="M146.0,0.0Q97.0,0.0 70.5,19.0Q44.0,38.0 44.0,72.0Q44.0,98.0 58.5,113.5Q73.0,129.0 98.0,129.0Q118.0,129.0 131.0,122.0Q144.0,115.0 157.0,105.0Q170.0,95.0 189.0,88.0Q208.0,81.0 244.0,81.0L811.0,81.0Q834.0,81.0 842.0,91.0Q850.0,101.0 850.0,116.0Q850.0,130.0 842.5,161.5Q835.0,193.0 824.5,228.5Q814.0,264.0 804.0,290.0Q772.0,258.0 723.5,238.0Q675.0,218.0 587.0,218.0Q495.0,218.0 430.0,248.5Q365.0,279.0 331.0,325.0Q322.0,337.0 317.0,349.0Q312.0,361.0 312.0,377.0Q312.0,396.0 324.0,410.5Q336.0,425.0 364.0,425.0Q392.0,425.0 408.5,410.5Q425.0,396.0 438.0,376.0Q450.0,359.0 466.0,341.0Q482.0,323.0 512.0,311.5Q542.0,300.0 594.0,300.0Q657.0,300.0 692.0,316.0Q727.0,332.0 745.0,355.5Q763.0,379.0 774.0,399.0Q783.0,416.0 792.5,427.5Q802.0,439.0 821.0,439.0Q844.0,439.0 853.5,425.5Q863.0,412.0 871.0,385.0Q878.0,364.0 889.5,325.0Q901.0,286.0 914.5,240.0Q928.0,194.0 938.5,151.5Q949.0,109.0 953.0,81.0L1038.0,81.0L1038.0,0.0L146.0,0.0Z"  transform="translate(0, 840)"/>
<path d="M-69.0,-219.0Q-91.0,-219.0 -112.0,-208.0Q-133.0,-197.0 -146.5,-179.0Q-160.0,-161.0 -160.0,-139.0Q-160.0,-106.0 -142.0,-82.5Q-124.0,-59.0 -91.0,-59.0Q-69.0,-59.0 -48.0,-70.0Q-27.0,-81.0 -13.5,-99.0Q0.0,-117.0 0.0,-139.0Q0.0,-172.0 -18.0,-195.5Q-36.0,-219.0 -69.0,-219.0ZM-313.0,-219.0Q-335.0,-219.0 -356.0,-208.0Q-377.0,-197.0 -390.5,-179.0Q-404.0,-161.0 -404.0,-139.0Q-404.0,-106.0 -386.0,-82.5Q-368.0,-59.0 -335.0,-59.0Q-313.0,-59.0 -292.0,-70.0Q-271.0,-81.0 -257.5,-99.0Q-244.0,-117.0 -244.0,-139.0Q-244.0,-172.0 -262.5,-195.5Q-281.0,-219.0 -313.0,-219.0Z"  transform="translate(1446, 840)"/>
<path d="M-39.0,0.0L-39.0,81.0L118.0,81.0Q84.0,107.0 65.5,142.0Q47.0,177.0 47.0,216.0Q47.0,248.0 61.5,276.0Q76.0,304.0 106.0,322.0Q136.0,340.0 180.0,340.0Q229.0,340.0 267.5,317.5Q306.0,295.0 336.0,257.5Q366.0,220.0 389.0,174.0Q412.0,128.0 429.0,81.0Q435.0,64.0 438.5,51.5Q442.0,39.0 442.0,29.0Q442.0,0.0 403.0,0.0L-39.0,0.0ZM328.0,81.0Q328.0,104.0 314.5,133.5Q301.0,163.0 279.5,190.5Q258.0,218.0 232.5,235.5Q207.0,253.0 183.0,253.0Q138.0,253.0 138.0,206.0Q138.0,175.0 166.0,146.0Q194.0,117.0 237.5,99.0Q281.0,81.0 328.0,81.0Z"  transform="translate(999, 840)"/>
<path d="M440.0,-225.0Q352.0,-225.0 279.5,-197.0Q207.0,-169.0 154.0,-120.0Q101.0,-71.0 72.5,-7.5Q44.0,56.0 44.0,127.0Q44.0,197.0 74.0,244.0Q104.0,291.0 151.0,314.5Q198.0,338.0 249.0,338.0Q283.0,338.0 311.5,326.0Q340.0,314.0 357.5,285.0Q375.0,256.0 375.0,204.0Q375.0,178.0 368.0,152.0Q361.0,126.0 344.5,108.5Q328.0,91.0 297.0,91.0Q252.0,91.0 228.0,124.0Q204.0,157.0 204.0,199.0Q204.0,206.0 204.0,215.5Q204.0,225.0 205.0,237.0Q167.0,230.0 150.5,200.0Q134.0,170.0 134.0,121.0Q134.0,81.0 152.5,35.5Q171.0,-10.0 209.0,-50.5Q247.0,-91.0 304.5,-116.5Q362.0,-142.0 440.0,-142.0Q511.0,-142.0 552.0,-118.5Q593.0,-95.0 610.5,-55.0Q628.0,-15.0 628.0,33.0Q628.0,104.0 601.5,164.5Q575.0,225.0 528.0,257.0Q472.0,278.0 436.5,309.0Q401.0,340.0 401.0,389.0Q401.0,415.0 416.5,426.5Q432.0,438.0 458.0,438.0Q483.0,438.0 499.5,426.0Q516.0,414.0 535.0,395.0Q558.0,372.0 592.0,346.0Q626.0,320.0 683.0,300.5Q740.0,281.0 831.0,276.0Q829.0,290.0 827.5,310.0Q826.0,330.0 826.0,343.0Q826.0,387.0 842.0,413.0Q858.0,439.0 891.0,439.0Q913.0,439.0 931.5,426.5Q950.0,414.0 950.0,386.0Q950.0,376.0 947.5,364.5Q945.0,353.0 940.0,342.0Q934.0,327.0 928.5,308.5Q923.0,290.0 923.0,264.0Q923.0,225.0 936.0,198.5Q949.0,172.0 968.5,153.5Q988.0,135.0 1006.0,121.0Q1030.0,103.0 1046.0,85.5Q1062.0,68.0 1062.0,42.0Q1062.0,20.0 1051.0,9.0Q1040.0,-2.0 1026.5,-6.0Q1013.0,-10.0 1003.0,-10.0Q957.0,-10.0 917.0,42.5Q877.0,95.0 850.0,184.0Q802.0,185.0 756.5,188.0Q711.0,191.0 665.0,200.0Q693.0,160.0 706.0,122.0Q719.0,84.0 719.0,31.0Q719.0,-16.0 705.0,-61.5Q691.0,-107.0 658.5,-144.0Q626.0,-181.0 572.5,-203.0Q519.0,-225.0 440.0,-225.0Z"  transform="translate(1486, 840)"/>
<path d="M-69.0,625.0Q-91.0,625.0 -112.0,636.0Q-133.0,647.0 -146.5,665.0Q-160.0,683.0 -160.0,705.0Q-160.0,738.0 -142.0,761.5Q-124.0,785.0 -91.0,785.0Q-69.0,785.0 -48.0,774.0Q-27.0,763.0 -13.5,745.0Q0.0,727.0 0.0,705.0Q0.0,672.0 -18.0,648.5Q-36.0,625.0 -69.0,625.0ZM-313.0,625.0Q-335.0,625.0 -356.0,636.0Q-377.0,647.0 -390.5,665.0Q-404.0,683.0 -404.0,705.0Q-404.0,738.0 -386.0,761.5Q-368.0,785.0 -335.0,785.0Q-313.0,785.0 -292.0,774.0Q-271.0,763.0 -257.5,745.0Q-244.0,727.0 -244.0,705.0Q-244.0,672.0 -262.5,648.5Q-281.0,625.0 -313.0,625.0Z"  transform="translate(3056, 899)"/>
<path d="M266.0,-10.0Q203.0,-10.0 162.5,5.5Q122.0,21.0 99.5,45.5Q77.0,70.0 68.0,98.5Q59.0,127.0 59.0,153.0Q59.0,199.0 74.5,242.5Q90.0,286.0 112.0,314.0Q134.0,342.0 153.0,342.0Q166.0,342.0 182.0,336.5Q198.0,331.0 209.5,321.5Q221.0,312.0 221.0,298.0Q221.0,286.0 213.0,275.5Q205.0,265.0 194.0,253.0Q177.0,235.0 163.0,213.5Q149.0,192.0 149.0,164.0Q149.0,126.0 176.5,101.0Q204.0,76.0 270.0,76.0Q320.0,76.0 345.0,84.0Q370.0,92.0 378.0,106.5Q386.0,121.0 386.0,143.0Q386.0,157.0 376.5,185.5Q367.0,214.0 354.0,246.0Q341.0,278.0 330.0,300.0Q313.0,337.0 293.5,381.0Q274.0,425.0 256.5,467.5Q239.0,510.0 228.0,544.5Q217.0,579.0 217.0,597.0Q217.0,611.0 225.5,618.0Q234.0,625.0 256.0,625.0Q307.0,625.0 332.0,615.0Q357.0,605.0 365.5,593.0Q374.0,581.0 374.0,573.0Q374.0,566.0 370.0,560.0Q366.0,554.0 361.0,548.0Q356.0,541.0 351.5,533.0Q347.0,525.0 347.0,515.0Q347.0,505.0 356.0,476.5Q365.0,448.0 381.0,408.5Q397.0,369.0 417.0,325.0Q427.0,303.0 441.5,267.5Q456.0,232.0 467.5,196.5Q479.0,161.0 479.0,138.0Q479.0,120.0 472.0,95.0Q465.0,70.0 444.0,46.0Q423.0,22.0 380.5,6.0Q338.0,-10.0 266.0,-10.0Z"  transform="translate(2590, 840)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3432 2130" transform="matrix(1 0 0 -1 0 0)">
<path d="M-69.0,-219.0Q-91.0,-219.0 -112.0,-208.0Q-133.0,-197.0 -146.5,-179.0Q-160.0,-161.0 -160.0,-139.0Q-160.0,-106.0 -142.0,-82.5Q-124.0,-59.0 -91.0,-59.0Q-69.0,-59.0 -48.0,-70.0Q-27.0,-81.0 -13.5,-99.0Q0.0,-117.0 0.0,-139.0Q0.0,-172.0 -18.0,-195.5Q-36.0,-219.0 -69.0,-219.0ZM-313.0,-219.0Q-335.0,-219.0 -356.0,-208.0Q-377.0,-197.0 -390.5,-179.0Q-404.0,-161.0 -404.0,-139.0Q-404.0,-106.0 -386.0,-82.5Q-368.0,-59.0 -335.0,-59.0Q-313.0,-59.0 -292.0,-70.0Q-271.0,-81.0 -257.5,-99.0Q-244.0,-117.0 -244.0,-139.0Q-244.0,-172.0 -262.5,-195.5Q-281.0,-219.0 -313.0,-219.0Z"  transform="translate(691, 840)"/>
<path d="M146.0,0.0Q97.0,0.0 70.5,19.0Q44.0,38.0 44.0,72.0Q44.0,98.0 58.5,113.5Q73.0,129.0 98.0,129.0Q118.0,129.0 131.0,122.0Q144.0,115.0 157.0,105.0Q170.0,95.0 189.0,88.0Q208.0,81.0 244.0,81.0L811.0,81.0Q834.0,81.0 842.0,91.0Q850.0,101.0 850.0,116.0Q850.0,130.0 842.5,161.5Q835.0,193.0 824.5,228.5Q814.0,264.0 804.0,290.0Q772.0,258.0 723.5,238.0Q675.0,218.0 587.0,218.0Q495.0,218.0 430.0,248.5Q365.0,279.0 331.0,325.0Q322.0,337.0 317.0,349.0Q312.0,361.0 312.0,377.0Q312.0,396.0 324.0,410.5Q336.0,425.0 364.0,425.0Q392.0,425.0 408.5,410.5Q425.0,396.0 438.0,376.0Q450.0,359.0 466.0,341.0Q482.0,323.0 512.0,311.5Q542.0,300.0 594.0,300.0Q657.0,300.0 692.0,316.0Q727.0,332.0 745.0,355.5Q763.0,379.0 774.0,399.0Q783.0,416.0 792.5,427.5Q802.0,439.0 821.0,439.0Q844.0,439.0 853.5,425.5Q863.0,412.0 871.0,385.0Q878.0,364.0 889.5,325.0Q901.0,286.0 914.5,240.0Q928.0,194.0 938.5,151.5Q949.0,109.0 953.0,81.0L1038.0,81.0L1038.0,0.0L146.0,0.0Z"  transform="translate(0, 840)"/>
<path d="M-69.0,-219.0Q-91.0,-219.0 -112.0,-208.0Q-133.0,-197.0 -146.5,-179.0Q-160.0,-161.0 -160.0,-139.0Q-160.0,-106.0 -142.0,-82.5Q-124.0,-59.0 -91.0,-59.0Q-69.0,-59.0 -48.0,-70.0Q-27.0,-81.0 -13.5,-99.0Q0.0,-117.0 0.0,-139.0Q0.0,-172.0 -18.0,-195.5Q-36.0,-219.0 -69.0,-219.0ZM-313.0,-219.0Q-335.0,-219.0 -356.0,-208.0Q-377.0,-197.0 -390.5,-179.0Q-404.0,-161.0 -404.0,-139.0Q-404.0,-106.0 -386.0,-82.5Q-368.0,-59.0 -335.0,-59.0Q-313.0,-59.0 -292.0,-70.0Q-271.0,-81.0 -257.5,-99.0Q-244.0,-117.0 -244.0,-139.0Q-244.0,-172.0 -262.5,-195.5Q-281.0,-219.0 -313.0,-219.0Z"  transform="translate(1446, 840)"/>
<path d="M-39.0,0.0L-39.0,81.0L118.0,81.0Q84.0,107.0 65.5,142.0Q47.0,177.0 47.0,216.0Q47.0,248.0 61.5,276.0Q76.0,304.0 106.0,322.0Q136.0,340.0 180.0,340.0Q229.0,340.0 267.5,317.5Q306.0,295.0 336.0,257.5Q366.0,220.0 389.0,174.0Q412.0,128.0 429.0,81.0Q435.0,64.0 438.5,51.5Q442.0,39.0 442.0,29.0Q442.0,0.0 403.0,0.0L-39.0,0.0ZM328.0,81.0Q328.0,104.0 314.5,133.5Q301.0,163.0 279.5,190.5Q258.0,218.0 232.5,235.5Q207.0,253.0 183.0,253.0Q138.0,253.0 138.0,206.0Q138.0,175.0 166.0,146.0Q194.0,117.0 237.5,99.0Q281.0,81.0 328.0,81.0Z"  transform="translate(999, 840)"/>
<path d="M247.0,-10.0Q156.0,-10.0 107.5,-1.5Q59.0,7.0 59.0,42.0Q59.0,79.0 113.0,79.0Q140.0,79.0 176.0,75.0Q195.0,73.0 216.0,72.0Q237.0,71.0 262.0,71.0Q301.0,71.0 329.0,87.0Q357.0,103.0 357.0,132.0Q357.0,162.0 339.0,193.0Q321.0,224.0 293.0,244.5Q265.0,265.0 235.0,265.0Q200.0,265.0 185.5,239.5Q171.0,214.0 157.0,169.0Q150.0,147.0 140.5,132.0Q131.0,117.0 109.0,117.0Q87.0,117.0 79.0,130.0Q71.0,143.0 71.0,160.0Q71.0,191.0 84.5,223.5Q98.0,256.0 114.0,280.0Q135.0,312.0 163.5,331.5Q192.0,351.0 239.0,351.0Q278.0,351.0 315.0,331.0Q352.0,311.0 382.0,277.0Q412.0,243.0 430.0,201.5Q448.0,160.0 448.0,118.0Q448.0,51.0 395.0,20.5Q342.0,-10.0 247.0,-10.0Z"  transform="translate(1486, 840)"/>
<path d="M271.0,-225.0Q206.0,-225.0 162.5,-205.0Q119.0,-185.0 93.0,-152.5Q67.0,-120.0 55.5,-81.0Q44.0,-42.0 44.0,-4.0Q44.0,43.0 59.0,69.5Q74.0,96.0 104.0,96.0Q125.0,96.0 138.5,85.0Q152.0,74.0 159.0,59.5Q166.0,45.0 166.0,33.0Q166.0,23.0 162.0,17.5Q158.0,12.0 152.0,7.0Q147.0,3.0 140.5,-6.0Q134.0,-15.0 134.0,-34.0Q134.0,-76.0 171.0,-108.0Q208.0,-140.0 275.0,-140.0Q331.0,-140.0 363.0,-118.5Q395.0,-97.0 409.0,-64.0Q423.0,-31.0 423.0,4.0Q423.0,34.0 414.0,70.5Q405.0,107.0 388.0,142.5Q371.0,178.0 347.5,207.0Q324.0,236.0 296.0,252.0Q233.0,277.0 194.0,308.0Q155.0,339.0 155.0,380.0Q155.0,410.0 174.0,424.0Q193.0,438.0 218.0,438.0Q244.0,438.0 261.0,426.0Q278.0,414.0 295.0,395.0Q311.0,378.0 333.0,359.0Q355.0,340.0 391.0,322.5Q427.0,305.0 484.0,292.5Q541.0,280.0 626.0,276.0Q624.0,290.0 622.5,310.0Q621.0,330.0 621.0,343.0Q621.0,387.0 637.0,413.0Q653.0,439.0 686.0,439.0Q708.0,439.0 726.5,426.5Q745.0,414.0 745.0,386.0Q745.0,376.0 742.5,364.5Q740.0,353.0 735.0,342.0Q729.0,327.0 723.5,308.5Q718.0,290.0 718.0,264.0Q718.0,225.0 731.0,198.0Q744.0,171.0 763.5,153.0Q783.0,135.0 801.0,121.0Q824.0,105.0 840.5,87.0Q857.0,69.0 857.0,42.0Q857.0,20.0 846.0,9.0Q835.0,-2.0 821.5,-6.0Q808.0,-10.0 798.0,-10.0Q752.0,-10.0 712.0,44.0Q672.0,98.0 645.0,189.0Q596.0,190.0 551.0,193.0Q506.0,196.0 459.0,205.0Q489.0,159.0 501.5,105.5Q514.0,52.0 514.0,10.0Q514.0,-29.0 501.5,-70.5Q489.0,-112.0 461.5,-147.0Q434.0,-182.0 387.0,-203.5Q340.0,-225.0 271.0,-225.0Z"  transform="translate(1993, 840)"/>
<path d="M-69.0,625.0Q-91.0,625.0 -112.0,636.0Q-133.0,647.0 -146.5,665.0Q-160.0,683.0 -160.0,705.0Q-160.0,738.0 -142.0,761.5Q-124.0,785.0 -91.0,785.0Q-69.0,785.0 -48.0,774.0Q-27.0,763.0 -13.5,745.0Q0.0,727.0 0.0,705.0Q0.0,672.0 -18.0,648.5Q-36.0,625.0 -69.0,625.0ZM-313.0,625.0Q-335.0,625.0 -356.0,636.0Q-377.0,647.0 -390.5,665.0Q-404.0,683.0 -404.0,705.0Q-404.0,738.0 -386.0,761.5Q-368.0,785.0 -335.0,785.0Q-313.0,785.0 -292.0,774.0Q-271.0,763.0 -257.5,745.0Q-244.0,727.0 -244.0,705.0Q-244.0,672.0 -262.5,648.5Q-281.0,625.0 -313.0,625.0Z"  transform="translate(3360, 899)"/>
<path d="M266.0,-10.0Q203.0,-10.0 162.5,5.5Q122.0,21.0 99.5,45.5Q77.0,70.0 68.0,98.5Q59.0,127.0 59.0,153.0Q59.0,199.0 74.5,242.5Q90.0,286.0 112.0,314.0Q134.0,342.0 153.0,342.0Q166.0,342.0 182.0,336.5Q198.0,331.0 209.5,321.5Q221.0,312.0 221.0,298.0Q221.0,286.0 213.0,275.5Q205.0,265.0 194.0,253.0Q177.0,235.0 163.0,213.5Q149.0,192.0 149.0,164.0Q149.0,126.0 176.5,101.0Q204.0,76.0 270.0,76.0Q320.0,76.0 345.0,84.0Q370.0,92.0 378.0,106.5Q386.0,121.0 386.0,143.0Q386.0,157.0 376.5,185.5Q367.0,214.0 354.0,246.0Q341.0,278.0 330.0,300.0Q313.0,337.0 293.5,381.0Q274.0,425.0 256.5,467.5Q239.0,510.0 228.0,544.5Q217.0,579.0 217.0,597.0Q217.0,611.0 225.5,618.0Q234.0,625.0 256.0,625.0Q307.0,625.0 332.0,615.0Q357.0,605.0 365.5,593.0Q374.0,581.0 374.0,573.0Q374.0,566.0 370.0,560.0Q366.0,554.0 361.0,548.0Q356.0,541.0 351.5,533.0Q347.0,525.0 347.0,515.0Q347.0,505.0 356.0,476.5Q365.0,448.0 381.0,408.5Q397.0,369.0 417.0,325.0Q427.0,303.0 441.5,267.5Q456.0,232.0 467.5,196.5Q479.0,161.0 479.0,138.0Q479.0,120.0 472.0,95.0Q465.0,70.0 444.0,46.0Q423.0,22.0 380.5,6.0Q338.0,-10.0 266.0,-10.0Z"  transform="translate(2894, 840)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐫖𐫤𐫞𐫅𐫖𐫗𐫀‬ ‫𐫖𐫓𐫇𐫀𐫀 1‬ ‫𐫐𐫓 𐫁𐫡𐫗𐫢𐫀 𐫁𐫡𐫏𐫓𐫆 𐫍𐫀𐫡𐫀 𐫇𐫁𐫡𐫁𐫡 𐫃𐫇 𐫀𐫏𐫞𐫡𐫀 𐫇𐫉𐫅𐫞𐫀 𐫇𐫛𐫏𐫢𐫏‬ ‫𐫓𐫆 𐫏𐫆𐫁𐫀</span></li>


<pre>Expected: u10AC0.fina=75+633|u10AC1.init=74+706|u10AC6=73+950|u10ACF=72+507|space=71+260|u10AC6=70+950|u10AD3=69+792|space=68+0|space=67+260|space=66+0|u10ACF=65+507|u10AE2=64+973|u10ACF.fina=63+507|u10ADB.init=62+487|u10AC7=61+451|space=60+260|u10AC0.fina=59+633|u10ADE.init=58+834|u10AC5=57+419|u10AC9=56+493|u10AC7=55+451|space=54+260|u10AC0=53+633|u10AE1.fina=52+385|u10ADE.init=51+834|u10ACF.fina=50+507|u10AC0.init=49+633|space=48+260|u10AC7.fina=47+429|u10AC3.init=46+427|space=45+260|u10AE1.fina=44+385|u10AC1.init=43+706|u10AE1.fina=42+385|u10AC1.init=41+706|u10AC7=40+451|space=39+260|u10AC0=38+633|u10AE1.fina=37+385|u10AC0.medi=36+633|u10ACD.init=35+624|space=34+260|u10AC6=33+950|u10AD3=32+792|u10ACF=31+507|u10AE1.fina=30+385|u10AC1.init=29+706|space=28+260|u10AC0=27+633|u10AE2=26+973|u10AD7=25+380|u10AE1.fina=24+385|u10AC1.init=23+706|space=22+260|u10AD3=21+792|u10AD0=20+1047|space=19+0|space=18+260|space=17+0|.notdef=16+600|space=15+260|u10AC0.fina=14+633|u10AC0.init=13+633|u10AC7.fina=12+429|u10AD3.medi=11+660|u10AD6.init=10+665|space=9+0|space=8+260|space=7+0|u10AC0.fina=6+633|u10AD7.init=5+380|u10AD6=4+994|u10AC5.fina=3+385|u10ADE.init=2+834|u10AE4.fina=1+632|u10AD6.init=0+665</pre>



<pre>Got     : u10AC0.fina=75+633|u10AC1.init=74+706|u10AC6=73+950|u10ACF=72+507|space=71+260|u10AC6=70+950|u10AD3=69+792|space=68+0|space=67+260|space=66+0|u10ACF=65+507|u10AE2=64+973|u10ACF.fina=63+507|u10ADB.init=62+487|u10AC7=61+451|space=60+260|u10AC0.fina=59+633|u10ADE.init=58+834|u10AC5=57+419|u10AC9=56+493|u10AC7=55+451|space=54+260|u10AC0=53+633|u10AE1.fina=52+385|u10ADE.init=51+834|u10ACF.fina=50+507|u10AC0.init=49+633|space=48+260|u10AC7.fina=47+429|u10AC3.init=46+427|space=45+260|u10AE1.fina=44+385|u10AC1.init=43+706|u10AE1.fina=42+385|u10AC1.init=41+706|u10AC7=40+451|space=39+260|u10AC0=38+633|u10AE1.fina=37+385|u10AC0.medi=36+633|u10ACD.init=35+624|space=34+260|u10AC6=33+950|u10AD3=32+792|u10ACF=31+507|u10AE1.fina=30+385|u10AC1.init=29+706|space=28+260|u10AC0=27+633|u10AE2=26+973|u10AD7=25+380|u10AE1.fina=24+385|u10AC1.init=23+706|space=22+260|u10AD3=21+792|u10AD0=20+1047|space=19+0|space=18+260|space=17+0|one=16+572|space=15+260|u10AC0.fina=14+633|u10AC0.init=13+633|u10AC7.fina=12+429|u10AD3.medi=11+660|u10AD6.init=10+665|space=9+0|space=8+260|space=7+0|u10AC0.fina=6+633|u10AD7.init=5+380|u10AD6=4+994|u10AC5.fina=3+385|u10ADE.init=2+834|u10AE4.fina=1+632|u10AD6.init=0+665</pre>



<pre>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 ++ ^^^^^^^^^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 38800 2130" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 840)"/>
<path d=""  transform="translate(633, 840)"/>
<path d=""  transform="translate(1339, 840)"/>
<path d=""  transform="translate(2289, 840)"/>
<path d=""  transform="translate(2796, 840)"/>
<path d=""  transform="translate(3056, 840)"/>
<path d=""  transform="translate(4006, 840)"/>
<path d=""  transform="translate(4798, 840)"/>
<path d=""  transform="translate(4798, 840)"/>
<path d=""  transform="translate(5058, 840)"/>
<path d=""  transform="translate(5058, 840)"/>
<path d=""  transform="translate(5565, 840)"/>
<path d=""  transform="translate(6538, 840)"/>
<path d=""  transform="translate(7045, 840)"/>
<path d=""  transform="translate(7532, 840)"/>
<path d=""  transform="translate(7983, 840)"/>
<path d=""  transform="translate(8243, 840)"/>
<path d=""  transform="translate(8876, 840)"/>
<path d=""  transform="translate(9710, 840)"/>
<path d=""  transform="translate(10129, 840)"/>
<path d=""  transform="translate(10622, 840)"/>
<path d=""  transform="translate(11073, 840)"/>
<path d=""  transform="translate(11333, 840)"/>
<path d=""  transform="translate(11966, 840)"/>
<path d=""  transform="translate(12351, 840)"/>
<path d=""  transform="translate(13185, 840)"/>
<path d=""  transform="translate(13692, 840)"/>
<path d=""  transform="translate(14325, 840)"/>
<path d=""  transform="translate(14585, 840)"/>
<path d=""  transform="translate(15014, 840)"/>
<path d=""  transform="translate(15441, 840)"/>
<path d=""  transform="translate(15701, 840)"/>
<path d=""  transform="translate(16086, 840)"/>
<path d=""  transform="translate(16792, 840)"/>
<path d=""  transform="translate(17177, 840)"/>
<path d=""  transform="translate(17883, 840)"/>
<path d=""  transform="translate(18334, 840)"/>
<path d=""  transform="translate(18594, 840)"/>
<path d=""  transform="translate(19227, 840)"/>
<path d=""  transform="translate(19612, 840)"/>
<path d=""  transform="translate(20245, 840)"/>
<path d=""  transform="translate(20869, 840)"/>
<path d=""  transform="translate(21129, 840)"/>
<path d=""  transform="translate(22079, 840)"/>
<path d=""  transform="translate(22871, 840)"/>
<path d=""  transform="translate(23378, 840)"/>
<path d=""  transform="translate(23763, 840)"/>
<path d=""  transform="translate(24469, 840)"/>
<path d=""  transform="translate(24729, 840)"/>
<path d=""  transform="translate(25362, 840)"/>
<path d=""  transform="translate(26335, 840)"/>
<path d=""  transform="translate(26715, 840)"/>
<path d=""  transform="translate(27100, 840)"/>
<path d=""  transform="translate(27806, 840)"/>
<path d=""  transform="translate(28066, 840)"/>
<path d=""  transform="translate(28858, 840)"/>
<path d=""  transform="translate(29905, 840)"/>
<path d=""  transform="translate(29905, 840)"/>
<path d=""  transform="translate(30165, 840)"/>
<path d=""  transform="translate(30165, 840)"/>
<path d=""  transform="translate(30737, 840)"/>
<path d=""  transform="translate(30997, 840)"/>
<path d=""  transform="translate(31630, 840)"/>
<path d=""  transform="translate(32263, 840)"/>
<path d=""  transform="translate(32692, 840)"/>
<path d=""  transform="translate(33352, 840)"/>
<path d=""  transform="translate(34017, 840)"/>
<path d=""  transform="translate(34017, 840)"/>
<path d=""  transform="translate(34277, 840)"/>
<path d=""  transform="translate(34277, 840)"/>
<path d=""  transform="translate(34910, 840)"/>
<path d=""  transform="translate(35290, 840)"/>
<path d=""  transform="translate(36284, 840)"/>
<path d=""  transform="translate(36669, 840)"/>
<path d=""  transform="translate(37503, 840)"/>
<path d=""  transform="translate(38135, 840)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 38828 2130" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 840)"/>
<path d=""  transform="translate(633, 840)"/>
<path d=""  transform="translate(1339, 840)"/>
<path d=""  transform="translate(2289, 840)"/>
<path d=""  transform="translate(2796, 840)"/>
<path d=""  transform="translate(3056, 840)"/>
<path d=""  transform="translate(4006, 840)"/>
<path d=""  transform="translate(4798, 840)"/>
<path d=""  transform="translate(4798, 840)"/>
<path d=""  transform="translate(5058, 840)"/>
<path d=""  transform="translate(5058, 840)"/>
<path d=""  transform="translate(5565, 840)"/>
<path d=""  transform="translate(6538, 840)"/>
<path d=""  transform="translate(7045, 840)"/>
<path d=""  transform="translate(7532, 840)"/>
<path d=""  transform="translate(7983, 840)"/>
<path d=""  transform="translate(8243, 840)"/>
<path d=""  transform="translate(8876, 840)"/>
<path d=""  transform="translate(9710, 840)"/>
<path d=""  transform="translate(10129, 840)"/>
<path d=""  transform="translate(10622, 840)"/>
<path d=""  transform="translate(11073, 840)"/>
<path d=""  transform="translate(11333, 840)"/>
<path d=""  transform="translate(11966, 840)"/>
<path d=""  transform="translate(12351, 840)"/>
<path d=""  transform="translate(13185, 840)"/>
<path d=""  transform="translate(13692, 840)"/>
<path d=""  transform="translate(14325, 840)"/>
<path d=""  transform="translate(14585, 840)"/>
<path d=""  transform="translate(15014, 840)"/>
<path d=""  transform="translate(15441, 840)"/>
<path d=""  transform="translate(15701, 840)"/>
<path d=""  transform="translate(16086, 840)"/>
<path d=""  transform="translate(16792, 840)"/>
<path d=""  transform="translate(17177, 840)"/>
<path d=""  transform="translate(17883, 840)"/>
<path d=""  transform="translate(18334, 840)"/>
<path d=""  transform="translate(18594, 840)"/>
<path d=""  transform="translate(19227, 840)"/>
<path d=""  transform="translate(19612, 840)"/>
<path d=""  transform="translate(20245, 840)"/>
<path d=""  transform="translate(20869, 840)"/>
<path d=""  transform="translate(21129, 840)"/>
<path d=""  transform="translate(22079, 840)"/>
<path d=""  transform="translate(22871, 840)"/>
<path d=""  transform="translate(23378, 840)"/>
<path d=""  transform="translate(23763, 840)"/>
<path d=""  transform="translate(24469, 840)"/>
<path d=""  transform="translate(24729, 840)"/>
<path d=""  transform="translate(25362, 840)"/>
<path d=""  transform="translate(26335, 840)"/>
<path d=""  transform="translate(26715, 840)"/>
<path d=""  transform="translate(27100, 840)"/>
<path d=""  transform="translate(27806, 840)"/>
<path d=""  transform="translate(28066, 840)"/>
<path d=""  transform="translate(28858, 840)"/>
<path d=""  transform="translate(29905, 840)"/>
<path d=""  transform="translate(29905, 840)"/>
<path d=""  transform="translate(30165, 840)"/>
<path d=""  transform="translate(30165, 840)"/>
<path d=""  transform="translate(30765, 840)"/>
<path d=""  transform="translate(31025, 840)"/>
<path d=""  transform="translate(31658, 840)"/>
<path d=""  transform="translate(32291, 840)"/>
<path d=""  transform="translate(32720, 840)"/>
<path d=""  transform="translate(33380, 840)"/>
<path d=""  transform="translate(34045, 840)"/>
<path d=""  transform="translate(34045, 840)"/>
<path d=""  transform="translate(34305, 840)"/>
<path d=""  transform="translate(34305, 840)"/>
<path d=""  transform="translate(34938, 840)"/>
<path d=""  transform="translate(35318, 840)"/>
<path d=""  transform="translate(36312, 840)"/>
<path d=""  transform="translate(36697, 840)"/>
<path d=""  transform="translate(37531, 840)"/>
<path d=""  transform="translate(38163, 840)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐫆𐫇𐫗𐫀 𐫇𐫀𐫗𐫏𐫤 𐫁𐫇𐫅 𐫅𐫀𐫆𐫀 𐫃𐫢𐫞𐫤𐫏 𐫙𐫓 𐫀𐫍𐫡𐫗𐫀 𐫃𐫡𐫃 𐫆𐫇𐫏‬ ‫𐫀 𐫁𐫍𐫅 𐫡𐫇𐫍𐫀 𐫅𐫀𐫍𐫗𐫇𐫤𐫀‬ ‫𐫖𐫓𐫇𐫀𐫀 2‬ ‫𐫐𐫓</span></li>


<pre>Expected: u10AD3=77+792|u10AD0=76+1047|space=75+0|space=74+260|space=73+0|.notdef=72+600|space=71+260|u10AC0.fina=70+633|u10AC0.init=69+633|u10AC7.fina=68+429|u10AD3.medi=67+660|u10AD6.init=66+665|space=65+0|space=64+260|space=63+0|u10AC0=62+633|u10AE4=61+677|u10AC7.fina=60+429|u10AD7.init=59+380|u10ACD=58+686|u10AC0=57+633|u10AC5=56+419|space=55+260|u10AC0.fina=54+633|u10ACD.init=53+624|u10AC7=52+451|u10AE1=51+419|space=50+260|u10AC5.fina=49+385|u10ACD.init=48+624|u10AC1=47+999|space=46+260|u10AC0=45+633|space=44+0|space=43+260|space=42+0|u10ACF=41+507|u10AC7=40+451|u10AC6=39+950|space=38+260|u10AC3=37+529|u10AE1.fina=36+385|u10AC3.init=35+427|space=34+260|u10AC0.fina=33+633|u10AD7.init=32+380|u10AE1.fina=31+385|u10ACD.init=30+624|u10AC0=29+633|space=28+260|u10AD3.fina=27+792|u10AD9.init=26+607|space=25+260|u10ACF=24+507|u10AE4.fina=23+632|u10ADE.init=22+834|u10AE2=21+973|u10AC3=20+529|space=19+260|u10AC0=18+633|u10AC6=17+950|u10AC0=16+633|u10AC5=15+419|space=14+260|u10AC5=13+419|u10AC7.fina=12+429|u10AC1.init=11+706|space=10+260|u10AE4=9+677|u10ACF.fina=8+507|u10AD7.init=7+380|u10AC0=6+633|u10AC7=5+451|space=4+260|u10AC0.fina=3+633|u10AD7.init=2+380|u10AC7=1+451|u10AC6=0+950</pre>



<pre>Got     : u10AD3=77+792|u10AD0=76+1047|space=75+0|space=74+260|space=73+0|two=72+572|space=71+260|u10AC0.fina=70+633|u10AC0.init=69+633|u10AC7.fina=68+429|u10AD3.medi=67+660|u10AD6.init=66+665|space=65+0|space=64+260|space=63+0|u10AC0=62+633|u10AE4=61+677|u10AC7.fina=60+429|u10AD7.init=59+380|u10ACD=58+686|u10AC0=57+633|u10AC5=56+419|space=55+260|u10AC0.fina=54+633|u10ACD.init=53+624|u10AC7=52+451|u10AE1=51+419|space=50+260|u10AC5.fina=49+385|u10ACD.init=48+624|u10AC1=47+999|space=46+260|u10AC0=45+633|space=44+0|space=43+260|space=42+0|u10ACF=41+507|u10AC7=40+451|u10AC6=39+950|space=38+260|u10AC3=37+529|u10AE1.fina=36+385|u10AC3.init=35+427|space=34+260|u10AC0.fina=33+633|u10AD7.init=32+380|u10AE1.fina=31+385|u10ACD.init=30+624|u10AC0=29+633|space=28+260|u10AD3.fina=27+792|u10AD9.init=26+607|space=25+260|u10ACF=24+507|u10AE4.fina=23+632|u10ADE.init=22+834|u10AE2=21+973|u10AC3=20+529|space=19+260|u10AC0=18+633|u10AC6=17+950|u10AC0=16+633|u10AC5=15+419|space=14+260|u10AC5=13+419|u10AC7.fina=12+429|u10AC1.init=11+706|space=10+260|u10AE4=9+677|u10ACF.fina=8+507|u10AD7.init=7+380|u10AC0=6+633|u10AC7=5+451|space=4+260|u10AC0.fina=3+633|u10AD7.init=2+380|u10AC7=1+451|u10AC6=0+950</pre>



<pre>                                                                          ^^ ^^^^^^^^^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 37985 2130" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 840)"/>
<path d=""  transform="translate(792, 840)"/>
<path d=""  transform="translate(1839, 840)"/>
<path d=""  transform="translate(1839, 840)"/>
<path d=""  transform="translate(2099, 840)"/>
<path d=""  transform="translate(2099, 840)"/>
<path d=""  transform="translate(2671, 840)"/>
<path d=""  transform="translate(2931, 840)"/>
<path d=""  transform="translate(3564, 840)"/>
<path d=""  transform="translate(4197, 840)"/>
<path d=""  transform="translate(4626, 840)"/>
<path d=""  transform="translate(5286, 840)"/>
<path d=""  transform="translate(5951, 840)"/>
<path d=""  transform="translate(5951, 840)"/>
<path d=""  transform="translate(6211, 840)"/>
<path d=""  transform="translate(6211, 840)"/>
<path d=""  transform="translate(6844, 840)"/>
<path d=""  transform="translate(7521, 840)"/>
<path d=""  transform="translate(7950, 840)"/>
<path d=""  transform="translate(8330, 840)"/>
<path d=""  transform="translate(9016, 840)"/>
<path d=""  transform="translate(9649, 840)"/>
<path d=""  transform="translate(10068, 840)"/>
<path d=""  transform="translate(10328, 840)"/>
<path d=""  transform="translate(10961, 840)"/>
<path d=""  transform="translate(11585, 840)"/>
<path d=""  transform="translate(12036, 840)"/>
<path d=""  transform="translate(12455, 840)"/>
<path d=""  transform="translate(12715, 840)"/>
<path d=""  transform="translate(13100, 840)"/>
<path d=""  transform="translate(13724, 840)"/>
<path d=""  transform="translate(14723, 840)"/>
<path d=""  transform="translate(14983, 840)"/>
<path d=""  transform="translate(15616, 840)"/>
<path d=""  transform="translate(15616, 840)"/>
<path d=""  transform="translate(15876, 840)"/>
<path d=""  transform="translate(15876, 840)"/>
<path d=""  transform="translate(16383, 840)"/>
<path d=""  transform="translate(16834, 840)"/>
<path d=""  transform="translate(17784, 840)"/>
<path d=""  transform="translate(18044, 840)"/>
<path d=""  transform="translate(18573, 840)"/>
<path d=""  transform="translate(18958, 840)"/>
<path d=""  transform="translate(19385, 840)"/>
<path d=""  transform="translate(19645, 840)"/>
<path d=""  transform="translate(20278, 840)"/>
<path d=""  transform="translate(20658, 840)"/>
<path d=""  transform="translate(21043, 840)"/>
<path d=""  transform="translate(21667, 840)"/>
<path d=""  transform="translate(22300, 840)"/>
<path d=""  transform="translate(22560, 840)"/>
<path d=""  transform="translate(23352, 840)"/>
<path d=""  transform="translate(23959, 840)"/>
<path d=""  transform="translate(24219, 840)"/>
<path d=""  transform="translate(24726, 840)"/>
<path d=""  transform="translate(25358, 840)"/>
<path d=""  transform="translate(26192, 840)"/>
<path d=""  transform="translate(27165, 840)"/>
<path d=""  transform="translate(27694, 840)"/>
<path d=""  transform="translate(27954, 840)"/>
<path d=""  transform="translate(28587, 840)"/>
<path d=""  transform="translate(29537, 840)"/>
<path d=""  transform="translate(30170, 840)"/>
<path d=""  transform="translate(30589, 840)"/>
<path d=""  transform="translate(30849, 840)"/>
<path d=""  transform="translate(31268, 840)"/>
<path d=""  transform="translate(31697, 840)"/>
<path d=""  transform="translate(32403, 840)"/>
<path d=""  transform="translate(32663, 840)"/>
<path d=""  transform="translate(33340, 840)"/>
<path d=""  transform="translate(33847, 840)"/>
<path d=""  transform="translate(34227, 840)"/>
<path d=""  transform="translate(34860, 840)"/>
<path d=""  transform="translate(35311, 840)"/>
<path d=""  transform="translate(35571, 840)"/>
<path d=""  transform="translate(36204, 840)"/>
<path d=""  transform="translate(36584, 840)"/>
<path d=""  transform="translate(37035, 840)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 38013 2130" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 840)"/>
<path d=""  transform="translate(792, 840)"/>
<path d=""  transform="translate(1839, 840)"/>
<path d=""  transform="translate(1839, 840)"/>
<path d=""  transform="translate(2099, 840)"/>
<path d=""  transform="translate(2099, 840)"/>
<path d=""  transform="translate(2699, 840)"/>
<path d=""  transform="translate(2959, 840)"/>
<path d=""  transform="translate(3592, 840)"/>
<path d=""  transform="translate(4225, 840)"/>
<path d=""  transform="translate(4654, 840)"/>
<path d=""  transform="translate(5314, 840)"/>
<path d=""  transform="translate(5979, 840)"/>
<path d=""  transform="translate(5979, 840)"/>
<path d=""  transform="translate(6239, 840)"/>
<path d=""  transform="translate(6239, 840)"/>
<path d=""  transform="translate(6872, 840)"/>
<path d=""  transform="translate(7549, 840)"/>
<path d=""  transform="translate(7978, 840)"/>
<path d=""  transform="translate(8358, 840)"/>
<path d=""  transform="translate(9044, 840)"/>
<path d=""  transform="translate(9677, 840)"/>
<path d=""  transform="translate(10096, 840)"/>
<path d=""  transform="translate(10356, 840)"/>
<path d=""  transform="translate(10989, 840)"/>
<path d=""  transform="translate(11613, 840)"/>
<path d=""  transform="translate(12064, 840)"/>
<path d=""  transform="translate(12483, 840)"/>
<path d=""  transform="translate(12743, 840)"/>
<path d=""  transform="translate(13128, 840)"/>
<path d=""  transform="translate(13752, 840)"/>
<path d=""  transform="translate(14751, 840)"/>
<path d=""  transform="translate(15011, 840)"/>
<path d=""  transform="translate(15644, 840)"/>
<path d=""  transform="translate(15644, 840)"/>
<path d=""  transform="translate(15904, 840)"/>
<path d=""  transform="translate(15904, 840)"/>
<path d=""  transform="translate(16411, 840)"/>
<path d=""  transform="translate(16862, 840)"/>
<path d=""  transform="translate(17812, 840)"/>
<path d=""  transform="translate(18072, 840)"/>
<path d=""  transform="translate(18601, 840)"/>
<path d=""  transform="translate(18986, 840)"/>
<path d=""  transform="translate(19413, 840)"/>
<path d=""  transform="translate(19673, 840)"/>
<path d=""  transform="translate(20306, 840)"/>
<path d=""  transform="translate(20686, 840)"/>
<path d=""  transform="translate(21071, 840)"/>
<path d=""  transform="translate(21695, 840)"/>
<path d=""  transform="translate(22328, 840)"/>
<path d=""  transform="translate(22588, 840)"/>
<path d=""  transform="translate(23380, 840)"/>
<path d=""  transform="translate(23987, 840)"/>
<path d=""  transform="translate(24247, 840)"/>
<path d=""  transform="translate(24754, 840)"/>
<path d=""  transform="translate(25386, 840)"/>
<path d=""  transform="translate(26220, 840)"/>
<path d=""  transform="translate(27193, 840)"/>
<path d=""  transform="translate(27722, 840)"/>
<path d=""  transform="translate(27982, 840)"/>
<path d=""  transform="translate(28615, 840)"/>
<path d=""  transform="translate(29565, 840)"/>
<path d=""  transform="translate(30198, 840)"/>
<path d=""  transform="translate(30617, 840)"/>
<path d=""  transform="translate(30877, 840)"/>
<path d=""  transform="translate(31296, 840)"/>
<path d=""  transform="translate(31725, 840)"/>
<path d=""  transform="translate(32431, 840)"/>
<path d=""  transform="translate(32691, 840)"/>
<path d=""  transform="translate(33368, 840)"/>
<path d=""  transform="translate(33875, 840)"/>
<path d=""  transform="translate(34255, 840)"/>
<path d=""  transform="translate(34888, 840)"/>
<path d=""  transform="translate(35339, 840)"/>
<path d=""  transform="translate(35599, 840)"/>
<path d=""  transform="translate(36232, 840)"/>
<path d=""  transform="translate(36612, 840)"/>
<path d=""  transform="translate(37063, 840)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐫅𐫍𐫅 𐫛𐫡𐫘𐫇𐫛𐫀‬ ‫ 𐫅𐫘𐫏𐫡𐫏𐫓𐫆 𐫁𐫏𐫆‬ ‫𐫖𐫓𐫇𐫀𐫀 3‬ ‫𐫐𐫓 𐫍𐫅 𐫀𐫏𐫤𐫓𐫆 𐫆𐫞𐫇𐫤𐫀 𐫓𐫍𐫏𐫀 𐫇𐫍𐫀𐫡𐫇𐫤𐫀 𐫇𐫢𐫏𐫗𐫀</span></li>


<pre>Expected: u10AC0.fina=73+633|u10AD7.init=72+380|u10ACF=71+507|u10AE2=70+973|u10AC7=69+451|space=68+260|u10AC0=67+633|u10AE4=66+677|u10AC7=65+451|u10AE1.fina=64+385|u10AC0.medi=63+633|u10ACD.init=62+624|u10AC7=61+451|space=60+260|u10AC0=59+633|u10ACF.fina=58+507|u10ACD.init=57+624|u10AD3=56+792|space=55+260|u10AC0=54+633|u10AE4=53+677|u10AC7.fina=52+429|u10ADE.init=51+834|u10AC6=50+950|space=49+260|u10AC6=48+950|u10AD3=47+792|u10AE4=46+677|u10ACF.fina=45+507|u10AC0.init=44+633|space=43+260|u10AC5.fina=42+385|u10ACD.init=41+624|space=40+260|u10AD3=39+792|u10AD0=38+1047|space=37+0|space=36+260|space=35+0|.notdef=34+600|space=33+260|u10AC0.fina=32+633|u10AC0.init=31+633|u10AC7.fina=30+429|u10AD3.medi=29+660|u10AD6.init=28+665|space=27+0|space=26+260|space=25+0|u10AC6=24+950|u10ACF.fina=23+507|u10AC1.init=22+706|space=21+260|u10AC6=20+950|u10AD3=19+792|u10ACF=18+507|u10AE1=17+419|u10ACF.fina=16+507|u10AD8.init=15+766|u10AC5=14+419|space=13+260|space=12+0|space=11+260|space=10+0|u10AC0.fina=9+633|u10ADB.init=8+487|u10AC7.fina=7+429|u10AD8.init=6+766|u10AE1.fina=5+385|u10ADB.init=4+487|space=3+260|u10AC5.fina=2+385|u10ACD.init=1+624|u10AC5=0+419</pre>



<pre>Got     : u10AC0.fina=73+633|u10AD7.init=72+380|u10ACF=71+507|u10AE2=70+973|u10AC7=69+451|space=68+260|u10AC0=67+633|u10AE4=66+677|u10AC7=65+451|u10AE1.fina=64+385|u10AC0.medi=63+633|u10ACD.init=62+624|u10AC7=61+451|space=60+260|u10AC0=59+633|u10ACF.fina=58+507|u10ACD.init=57+624|u10AD3=56+792|space=55+260|u10AC0=54+633|u10AE4=53+677|u10AC7.fina=52+429|u10ADE.init=51+834|u10AC6=50+950|space=49+260|u10AC6=48+950|u10AD3=47+792|u10AE4=46+677|u10ACF.fina=45+507|u10AC0.init=44+633|space=43+260|u10AC5.fina=42+385|u10ACD.init=41+624|space=40+260|u10AD3=39+792|u10AD0=38+1047|space=37+0|space=36+260|space=35+0|three=34+572|space=33+260|u10AC0.fina=32+633|u10AC0.init=31+633|u10AC7.fina=30+429|u10AD3.medi=29+660|u10AD6.init=28+665|space=27+0|space=26+260|space=25+0|u10AC6=24+950|u10ACF.fina=23+507|u10AC1.init=22+706|space=21+260|u10AC6=20+950|u10AD3=19+792|u10ACF=18+507|u10AE1=17+419|u10ACF.fina=16+507|u10AD8.init=15+766|u10AC5=14+419|space=13+260|space=12+0|space=11+260|space=10+0|u10AC0.fina=9+633|u10ADB.init=8+487|u10AC7.fina=7+429|u10AD8.init=6+766|u10AE1.fina=5+385|u10ADB.init=4+487|space=3+260|u10AC5.fina=2+385|u10ACD.init=1+624|u10AC5=0+419</pre>



<pre>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 ^^^^^^^^^^^^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 37394 2130" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 840)"/>
<path d=""  transform="translate(633, 840)"/>
<path d=""  transform="translate(1013, 840)"/>
<path d=""  transform="translate(1520, 840)"/>
<path d=""  transform="translate(2493, 840)"/>
<path d=""  transform="translate(2944, 840)"/>
<path d=""  transform="translate(3204, 840)"/>
<path d=""  transform="translate(3837, 840)"/>
<path d=""  transform="translate(4514, 840)"/>
<path d=""  transform="translate(4965, 840)"/>
<path d=""  transform="translate(5350, 840)"/>
<path d=""  transform="translate(5983, 840)"/>
<path d=""  transform="translate(6607, 840)"/>
<path d=""  transform="translate(7058, 840)"/>
<path d=""  transform="translate(7318, 840)"/>
<path d=""  transform="translate(7951, 840)"/>
<path d=""  transform="translate(8458, 840)"/>
<path d=""  transform="translate(9082, 840)"/>
<path d=""  transform="translate(9874, 840)"/>
<path d=""  transform="translate(10134, 840)"/>
<path d=""  transform="translate(10767, 840)"/>
<path d=""  transform="translate(11444, 840)"/>
<path d=""  transform="translate(11873, 840)"/>
<path d=""  transform="translate(12707, 840)"/>
<path d=""  transform="translate(13657, 840)"/>
<path d=""  transform="translate(13917, 840)"/>
<path d=""  transform="translate(14867, 840)"/>
<path d=""  transform="translate(15659, 840)"/>
<path d=""  transform="translate(16336, 840)"/>
<path d=""  transform="translate(16843, 840)"/>
<path d=""  transform="translate(17476, 840)"/>
<path d=""  transform="translate(17736, 840)"/>
<path d=""  transform="translate(18121, 840)"/>
<path d=""  transform="translate(18745, 840)"/>
<path d=""  transform="translate(19005, 840)"/>
<path d=""  transform="translate(19797, 840)"/>
<path d=""  transform="translate(20844, 840)"/>
<path d=""  transform="translate(20844, 840)"/>
<path d=""  transform="translate(21104, 840)"/>
<path d=""  transform="translate(21104, 840)"/>
<path d=""  transform="translate(21676, 840)"/>
<path d=""  transform="translate(21936, 840)"/>
<path d=""  transform="translate(22569, 840)"/>
<path d=""  transform="translate(23202, 840)"/>
<path d=""  transform="translate(23631, 840)"/>
<path d=""  transform="translate(24291, 840)"/>
<path d=""  transform="translate(24956, 840)"/>
<path d=""  transform="translate(24956, 840)"/>
<path d=""  transform="translate(25216, 840)"/>
<path d=""  transform="translate(25216, 840)"/>
<path d=""  transform="translate(26166, 840)"/>
<path d=""  transform="translate(26673, 840)"/>
<path d=""  transform="translate(27379, 840)"/>
<path d=""  transform="translate(27639, 840)"/>
<path d=""  transform="translate(28589, 840)"/>
<path d=""  transform="translate(29381, 840)"/>
<path d=""  transform="translate(29888, 840)"/>
<path d=""  transform="translate(30307, 840)"/>
<path d=""  transform="translate(30814, 840)"/>
<path d=""  transform="translate(31580, 840)"/>
<path d=""  transform="translate(31999, 840)"/>
<path d=""  transform="translate(32259, 840)"/>
<path d=""  transform="translate(32259, 840)"/>
<path d=""  transform="translate(32519, 840)"/>
<path d=""  transform="translate(32519, 840)"/>
<path d=""  transform="translate(33152, 840)"/>
<path d=""  transform="translate(33639, 840)"/>
<path d=""  transform="translate(34068, 840)"/>
<path d=""  transform="translate(34834, 840)"/>
<path d=""  transform="translate(35219, 840)"/>
<path d=""  transform="translate(35706, 840)"/>
<path d=""  transform="translate(35966, 840)"/>
<path d=""  transform="translate(36351, 840)"/>
<path d=""  transform="translate(36975, 840)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 37422 2130" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 840)"/>
<path d=""  transform="translate(633, 840)"/>
<path d=""  transform="translate(1013, 840)"/>
<path d=""  transform="translate(1520, 840)"/>
<path d=""  transform="translate(2493, 840)"/>
<path d=""  transform="translate(2944, 840)"/>
<path d=""  transform="translate(3204, 840)"/>
<path d=""  transform="translate(3837, 840)"/>
<path d=""  transform="translate(4514, 840)"/>
<path d=""  transform="translate(4965, 840)"/>
<path d=""  transform="translate(5350, 840)"/>
<path d=""  transform="translate(5983, 840)"/>
<path d=""  transform="translate(6607, 840)"/>
<path d=""  transform="translate(7058, 840)"/>
<path d=""  transform="translate(7318, 840)"/>
<path d=""  transform="translate(7951, 840)"/>
<path d=""  transform="translate(8458, 840)"/>
<path d=""  transform="translate(9082, 840)"/>
<path d=""  transform="translate(9874, 840)"/>
<path d=""  transform="translate(10134, 840)"/>
<path d=""  transform="translate(10767, 840)"/>
<path d=""  transform="translate(11444, 840)"/>
<path d=""  transform="translate(11873, 840)"/>
<path d=""  transform="translate(12707, 840)"/>
<path d=""  transform="translate(13657, 840)"/>
<path d=""  transform="translate(13917, 840)"/>
<path d=""  transform="translate(14867, 840)"/>
<path d=""  transform="translate(15659, 840)"/>
<path d=""  transform="translate(16336, 840)"/>
<path d=""  transform="translate(16843, 840)"/>
<path d=""  transform="translate(17476, 840)"/>
<path d=""  transform="translate(17736, 840)"/>
<path d=""  transform="translate(18121, 840)"/>
<path d=""  transform="translate(18745, 840)"/>
<path d=""  transform="translate(19005, 840)"/>
<path d=""  transform="translate(19797, 840)"/>
<path d=""  transform="translate(20844, 840)"/>
<path d=""  transform="translate(20844, 840)"/>
<path d=""  transform="translate(21104, 840)"/>
<path d=""  transform="translate(21104, 840)"/>
<path d=""  transform="translate(21704, 840)"/>
<path d=""  transform="translate(21964, 840)"/>
<path d=""  transform="translate(22597, 840)"/>
<path d=""  transform="translate(23230, 840)"/>
<path d=""  transform="translate(23659, 840)"/>
<path d=""  transform="translate(24319, 840)"/>
<path d=""  transform="translate(24984, 840)"/>
<path d=""  transform="translate(24984, 840)"/>
<path d=""  transform="translate(25244, 840)"/>
<path d=""  transform="translate(25244, 840)"/>
<path d=""  transform="translate(26194, 840)"/>
<path d=""  transform="translate(26701, 840)"/>
<path d=""  transform="translate(27407, 840)"/>
<path d=""  transform="translate(27667, 840)"/>
<path d=""  transform="translate(28617, 840)"/>
<path d=""  transform="translate(29409, 840)"/>
<path d=""  transform="translate(29916, 840)"/>
<path d=""  transform="translate(30335, 840)"/>
<path d=""  transform="translate(30842, 840)"/>
<path d=""  transform="translate(31608, 840)"/>
<path d=""  transform="translate(32027, 840)"/>
<path d=""  transform="translate(32287, 840)"/>
<path d=""  transform="translate(32287, 840)"/>
<path d=""  transform="translate(32547, 840)"/>
<path d=""  transform="translate(32547, 840)"/>
<path d=""  transform="translate(33180, 840)"/>
<path d=""  transform="translate(33667, 840)"/>
<path d=""  transform="translate(34096, 840)"/>
<path d=""  transform="translate(34862, 840)"/>
<path d=""  transform="translate(35247, 840)"/>
<path d=""  transform="translate(35734, 840)"/>
<path d=""  transform="translate(35994, 840)"/>
<path d=""  transform="translate(36379, 840)"/>
<path d=""  transform="translate(37003, 840)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐫛𐫡𐫘𐫇𐫛𐫏𐫀‬ ‫𐫖𐫓𐫇𐫀𐫀 4‬ ‫𐫆𐫐 𐫍𐫅 𐫃𐫡𐫃 𐫓𐫀 𐫛𐫀𐫢 𐫅𐫁𐫏𐫞𐫅𐫀 𐫃𐫇 𐫞𐫇𐫓𐫇𐫤𐫀 𐫏𐫗 𐫍𐫓𐫖𐫤𐫇𐫤𐫀 𐫏‬ ‫𐫗 𐫤𐫇𐫃𐫡𐫇𐫤𐫀</span></li>


<pre>Expected: u10AC0=77+633|u10AE4=76+677|u10AC7=75+451|u10AE1.fina=74+385|u10AC3.init=73+427|u10AC7=72+451|u10AE4=71+677|space=70+260|u10AD7=69+380|space=68+0|space=67+260|space=66+0|u10ACF=65+507|space=64+260|u10AC0=63+633|u10AE4=62+677|u10AC7=61+451|u10AE4.fina=60+632|u10AD6.medi=59+665|u10AD3.medi=58+660|u10ACD.init=57+624|space=56+260|u10AD7=55+380|u10ACF=54+507|space=53+260|u10AC0=52+633|u10AE4=51+677|u10AC7.fina=50+429|u10AD3.init=49+660|u10AC7.fina=48+429|u10ADE.init=47+834|space=46+260|u10AC7.fina=45+429|u10AC3.init=44+427|space=43+260|u10AC0=42+633|u10AC5.fina=41+385|u10ADE.init=40+834|u10ACF.fina=39+507|u10AC1.init=38+706|u10AC5=37+419|space=36+260|u10AE2=35+973|u10AC0.fina=34+633|u10ADB.init=33+487|space=32+260|u10AC0.fina=31+633|u10AD3.init=30+660|space=29+260|u10AC3=28+529|u10AE1.fina=27+385|u10AC3.init=26+427|space=25+260|u10AC5.fina=24+385|u10ACD.init=23+624|space=22+260|u10AD0=21+1047|u10AC6=20+950|space=19+0|space=18+260|space=17+0|.notdef=16+600|space=15+260|u10AC0.fina=14+633|u10AC0.init=13+633|u10AC7.fina=12+429|u10AD3.medi=11+660|u10AD6.init=10+665|space=9+0|space=8+260|space=7+0|u10AC0=6+633|u10ACF.fina=5+507|u10ADB.init=4+487|u10AC7.fina=3+429|u10AD8.init=2+766|u10AE1.fina=1+385|u10ADB.init=0+487</pre>



<pre>Got     : u10AC0=77+633|u10AE4=76+677|u10AC7=75+451|u10AE1.fina=74+385|u10AC3.init=73+427|u10AC7=72+451|u10AE4=71+677|space=70+260|u10AD7=69+380|space=68+0|space=67+260|space=66+0|u10ACF=65+507|space=64+260|u10AC0=63+633|u10AE4=62+677|u10AC7=61+451|u10AE4.fina=60+632|u10AD6.medi=59+665|u10AD3.medi=58+660|u10ACD.init=57+624|space=56+260|u10AD7=55+380|u10ACF=54+507|space=53+260|u10AC0=52+633|u10AE4=51+677|u10AC7.fina=50+429|u10AD3.init=49+660|u10AC7.fina=48+429|u10ADE.init=47+834|space=46+260|u10AC7.fina=45+429|u10AC3.init=44+427|space=43+260|u10AC0=42+633|u10AC5.fina=41+385|u10ADE.init=40+834|u10ACF.fina=39+507|u10AC1.init=38+706|u10AC5=37+419|space=36+260|u10AE2=35+973|u10AC0.fina=34+633|u10ADB.init=33+487|space=32+260|u10AC0.fina=31+633|u10AD3.init=30+660|space=29+260|u10AC3=28+529|u10AE1.fina=27+385|u10AC3.init=26+427|space=25+260|u10AC5.fina=24+385|u10ACD.init=23+624|space=22+260|u10AD0=21+1047|u10AC6=20+950|space=19+0|space=18+260|space=17+0|four=16+572|space=15+260|u10AC0.fina=14+633|u10AC0.init=13+633|u10AC7.fina=12+429|u10AD3.medi=11+660|u10AD6.init=10+665|space=9+0|space=8+260|space=7+0|u10AC0=6+633|u10ACF.fina=5+507|u10ADB.init=4+487|u10AC7.fina=3+429|u10AD8.init=2+766|u10AE1.fina=1+385|u10ADB.init=0+487</pre>



<pre>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                ^^ ^^^^^^^^^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 36738 2130" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 840)"/>
<path d=""  transform="translate(633, 840)"/>
<path d=""  transform="translate(1310, 840)"/>
<path d=""  transform="translate(1761, 840)"/>
<path d=""  transform="translate(2146, 840)"/>
<path d=""  transform="translate(2573, 840)"/>
<path d=""  transform="translate(3024, 840)"/>
<path d=""  transform="translate(3701, 840)"/>
<path d=""  transform="translate(3961, 840)"/>
<path d=""  transform="translate(4341, 840)"/>
<path d=""  transform="translate(4341, 840)"/>
<path d=""  transform="translate(4601, 840)"/>
<path d=""  transform="translate(4601, 840)"/>
<path d=""  transform="translate(5108, 840)"/>
<path d=""  transform="translate(5368, 840)"/>
<path d=""  transform="translate(6001, 840)"/>
<path d=""  transform="translate(6678, 840)"/>
<path d=""  transform="translate(7129, 840)"/>
<path d=""  transform="translate(7761, 840)"/>
<path d=""  transform="translate(8426, 840)"/>
<path d=""  transform="translate(9086, 840)"/>
<path d=""  transform="translate(9710, 840)"/>
<path d=""  transform="translate(9970, 840)"/>
<path d=""  transform="translate(10350, 840)"/>
<path d=""  transform="translate(10857, 840)"/>
<path d=""  transform="translate(11117, 840)"/>
<path d=""  transform="translate(11750, 840)"/>
<path d=""  transform="translate(12427, 840)"/>
<path d=""  transform="translate(12856, 840)"/>
<path d=""  transform="translate(13516, 840)"/>
<path d=""  transform="translate(13945, 840)"/>
<path d=""  transform="translate(14779, 840)"/>
<path d=""  transform="translate(15039, 840)"/>
<path d=""  transform="translate(15468, 840)"/>
<path d=""  transform="translate(15895, 840)"/>
<path d=""  transform="translate(16155, 840)"/>
<path d=""  transform="translate(16788, 840)"/>
<path d=""  transform="translate(17173, 840)"/>
<path d=""  transform="translate(18007, 840)"/>
<path d=""  transform="translate(18514, 840)"/>
<path d=""  transform="translate(19220, 840)"/>
<path d=""  transform="translate(19639, 840)"/>
<path d=""  transform="translate(19899, 840)"/>
<path d=""  transform="translate(20872, 840)"/>
<path d=""  transform="translate(21505, 840)"/>
<path d=""  transform="translate(21992, 840)"/>
<path d=""  transform="translate(22252, 840)"/>
<path d=""  transform="translate(22885, 840)"/>
<path d=""  transform="translate(23545, 840)"/>
<path d=""  transform="translate(23805, 840)"/>
<path d=""  transform="translate(24334, 840)"/>
<path d=""  transform="translate(24719, 840)"/>
<path d=""  transform="translate(25146, 840)"/>
<path d=""  transform="translate(25406, 840)"/>
<path d=""  transform="translate(25791, 840)"/>
<path d=""  transform="translate(26415, 840)"/>
<path d=""  transform="translate(26675, 840)"/>
<path d=""  transform="translate(27722, 840)"/>
<path d=""  transform="translate(28672, 840)"/>
<path d=""  transform="translate(28672, 840)"/>
<path d=""  transform="translate(28932, 840)"/>
<path d=""  transform="translate(28932, 840)"/>
<path d=""  transform="translate(29504, 840)"/>
<path d=""  transform="translate(29764, 840)"/>
<path d=""  transform="translate(30397, 840)"/>
<path d=""  transform="translate(31030, 840)"/>
<path d=""  transform="translate(31459, 840)"/>
<path d=""  transform="translate(32119, 840)"/>
<path d=""  transform="translate(32784, 840)"/>
<path d=""  transform="translate(32784, 840)"/>
<path d=""  transform="translate(33044, 840)"/>
<path d=""  transform="translate(33044, 840)"/>
<path d=""  transform="translate(33677, 840)"/>
<path d=""  transform="translate(34184, 840)"/>
<path d=""  transform="translate(34671, 840)"/>
<path d=""  transform="translate(35100, 840)"/>
<path d=""  transform="translate(35866, 840)"/>
<path d=""  transform="translate(36251, 840)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 36766 2130" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 840)"/>
<path d=""  transform="translate(633, 840)"/>
<path d=""  transform="translate(1310, 840)"/>
<path d=""  transform="translate(1761, 840)"/>
<path d=""  transform="translate(2146, 840)"/>
<path d=""  transform="translate(2573, 840)"/>
<path d=""  transform="translate(3024, 840)"/>
<path d=""  transform="translate(3701, 840)"/>
<path d=""  transform="translate(3961, 840)"/>
<path d=""  transform="translate(4341, 840)"/>
<path d=""  transform="translate(4341, 840)"/>
<path d=""  transform="translate(4601, 840)"/>
<path d=""  transform="translate(4601, 840)"/>
<path d=""  transform="translate(5108, 840)"/>
<path d=""  transform="translate(5368, 840)"/>
<path d=""  transform="translate(6001, 840)"/>
<path d=""  transform="translate(6678, 840)"/>
<path d=""  transform="translate(7129, 840)"/>
<path d=""  transform="translate(7761, 840)"/>
<path d=""  transform="translate(8426, 840)"/>
<path d=""  transform="translate(9086, 840)"/>
<path d=""  transform="translate(9710, 840)"/>
<path d=""  transform="translate(9970, 840)"/>
<path d=""  transform="translate(10350, 840)"/>
<path d=""  transform="translate(10857, 840)"/>
<path d=""  transform="translate(11117, 840)"/>
<path d=""  transform="translate(11750, 840)"/>
<path d=""  transform="translate(12427, 840)"/>
<path d=""  transform="translate(12856, 840)"/>
<path d=""  transform="translate(13516, 840)"/>
<path d=""  transform="translate(13945, 840)"/>
<path d=""  transform="translate(14779, 840)"/>
<path d=""  transform="translate(15039, 840)"/>
<path d=""  transform="translate(15468, 840)"/>
<path d=""  transform="translate(15895, 840)"/>
<path d=""  transform="translate(16155, 840)"/>
<path d=""  transform="translate(16788, 840)"/>
<path d=""  transform="translate(17173, 840)"/>
<path d=""  transform="translate(18007, 840)"/>
<path d=""  transform="translate(18514, 840)"/>
<path d=""  transform="translate(19220, 840)"/>
<path d=""  transform="translate(19639, 840)"/>
<path d=""  transform="translate(19899, 840)"/>
<path d=""  transform="translate(20872, 840)"/>
<path d=""  transform="translate(21505, 840)"/>
<path d=""  transform="translate(21992, 840)"/>
<path d=""  transform="translate(22252, 840)"/>
<path d=""  transform="translate(22885, 840)"/>
<path d=""  transform="translate(23545, 840)"/>
<path d=""  transform="translate(23805, 840)"/>
<path d=""  transform="translate(24334, 840)"/>
<path d=""  transform="translate(24719, 840)"/>
<path d=""  transform="translate(25146, 840)"/>
<path d=""  transform="translate(25406, 840)"/>
<path d=""  transform="translate(25791, 840)"/>
<path d=""  transform="translate(26415, 840)"/>
<path d=""  transform="translate(26675, 840)"/>
<path d=""  transform="translate(27722, 840)"/>
<path d=""  transform="translate(28672, 840)"/>
<path d=""  transform="translate(28672, 840)"/>
<path d=""  transform="translate(28932, 840)"/>
<path d=""  transform="translate(28932, 840)"/>
<path d=""  transform="translate(29532, 840)"/>
<path d=""  transform="translate(29792, 840)"/>
<path d=""  transform="translate(30425, 840)"/>
<path d=""  transform="translate(31058, 840)"/>
<path d=""  transform="translate(31487, 840)"/>
<path d=""  transform="translate(32147, 840)"/>
<path d=""  transform="translate(32812, 840)"/>
<path d=""  transform="translate(32812, 840)"/>
<path d=""  transform="translate(33072, 840)"/>
<path d=""  transform="translate(33072, 840)"/>
<path d=""  transform="translate(33705, 840)"/>
<path d=""  transform="translate(34212, 840)"/>
<path d=""  transform="translate(34699, 840)"/>
<path d=""  transform="translate(35128, 840)"/>
<path d=""  transform="translate(35894, 840)"/>
<path d=""  transform="translate(36279, 840)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐫅𐫞𐫓𐫇𐫤𐫀 𐫇𐫍𐫓𐫖𐫤𐫇𐫤𐫀‬ ‫𐫖𐫓𐫇𐫀𐫀 5‬ ‫𐫆𐫐 𐫍𐫅 𐫛𐫡𐫘𐫇𐫛𐫀 𐫃𐫡𐫃 𐫓𐫀 𐫛𐫀𐫢 𐫙𐫇𐫃𐫉𐫀 𐫏𐫗 𐫀𐫏𐫞𐫡𐫀 𐫢𐫞𐫏𐫓𐫀 𐫏𐫗‬ ‫</span></li>


<pre>Expected: space=77+0|space=76+260|space=75+0|u10AD7=74+380|u10ACF=73+507|space=72+260|u10AC0.fina=71+633|u10AD3.init=70+660|u10ACF.fina=69+507|u10ADE.init=68+834|u10AE2=67+973|space=66+260|u10AC0=65+633|u10AE1.fina=64+385|u10ADE.init=63+834|u10ACF.fina=62+507|u10AC0.init=61+633|space=60+260|u10AD7=59+380|u10ACF=58+507|space=57+260|u10AC0=56+633|u10AC9.fina=55+424|u10AC3.init=54+427|u10AC7.fina=53+429|u10AD9.init=52+607|space=51+260|u10AE2=50+973|u10AC0.fina=49+633|u10ADB.init=48+487|space=47+260|u10AC0.fina=46+633|u10AD3.init=45+660|space=44+260|u10AC3=43+529|u10AE1.fina=42+385|u10AC3.init=41+427|space=40+260|u10AC0.fina=39+633|u10ADB.init=38+487|u10AC7.fina=37+429|u10AD8.init=36+766|u10AE1.fina=35+385|u10ADB.init=34+487|space=33+260|u10AC5.fina=32+385|u10ACD.init=31+624|space=30+260|u10AD0=29+1047|u10AC6=28+950|space=27+0|space=26+260|space=25+0|.notdef=24+600|space=23+260|u10AC0.fina=22+633|u10AC0.init=21+633|u10AC7.fina=20+429|u10AD3.medi=19+660|u10AD6.init=18+665|space=17+0|space=16+260|space=15+0|u10AC0=14+633|u10AE4=13+677|u10AC7=12+451|u10AE4.fina=11+632|u10AD6.medi=10+665|u10AD3.medi=9+660|u10ACD.init=8+624|u10AC7=7+451|space=6+260|u10AC0=5+633|u10AE4=4+677|u10AC7.fina=3+429|u10AD3.medi=2+660|u10ADE.init=1+834|u10AC5=0+419</pre>



<pre>Got     : space=77+0|space=76+260|space=75+0|u10AD7=74+380|u10ACF=73+507|space=72+260|u10AC0.fina=71+633|u10AD3.init=70+660|u10ACF.fina=69+507|u10ADE.init=68+834|u10AE2=67+973|space=66+260|u10AC0=65+633|u10AE1.fina=64+385|u10ADE.init=63+834|u10ACF.fina=62+507|u10AC0.init=61+633|space=60+260|u10AD7=59+380|u10ACF=58+507|space=57+260|u10AC0=56+633|u10AC9.fina=55+424|u10AC3.init=54+427|u10AC7.fina=53+429|u10AD9.init=52+607|space=51+260|u10AE2=50+973|u10AC0.fina=49+633|u10ADB.init=48+487|space=47+260|u10AC0.fina=46+633|u10AD3.init=45+660|space=44+260|u10AC3=43+529|u10AE1.fina=42+385|u10AC3.init=41+427|space=40+260|u10AC0.fina=39+633|u10ADB.init=38+487|u10AC7.fina=37+429|u10AD8.init=36+766|u10AE1.fina=35+385|u10ADB.init=34+487|space=33+260|u10AC5.fina=32+385|u10ACD.init=31+624|space=30+260|u10AD0=29+1047|u10AC6=28+950|space=27+0|space=26+260|space=25+0|five=24+572|space=23+260|u10AC0.fina=22+633|u10AC0.init=21+633|u10AC7.fina=20+429|u10AD3.medi=19+660|u10AD6.init=18+665|space=17+0|space=16+260|space=15+0|u10AC0=14+633|u10AE4=13+677|u10AC7=12+451|u10AE4.fina=11+632|u10AD6.medi=10+665|u10AD3.medi=9+660|u10ACD.init=8+624|u10AC7=7+451|space=6+260|u10AC0=5+633|u10AE4=4+677|u10AC7.fina=3+429|u10AD3.medi=2+660|u10ADE.init=1+834|u10AC5=0+419</pre>



<pre>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           ^^^^^^^^^^^^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 37750 2130" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 840)"/>
<path d=""  transform="translate(0, 840)"/>
<path d=""  transform="translate(260, 840)"/>
<path d=""  transform="translate(260, 840)"/>
<path d=""  transform="translate(640, 840)"/>
<path d=""  transform="translate(1147, 840)"/>
<path d=""  transform="translate(1407, 840)"/>
<path d=""  transform="translate(2040, 840)"/>
<path d=""  transform="translate(2700, 840)"/>
<path d=""  transform="translate(3207, 840)"/>
<path d=""  transform="translate(4041, 840)"/>
<path d=""  transform="translate(5014, 840)"/>
<path d=""  transform="translate(5274, 840)"/>
<path d=""  transform="translate(5907, 840)"/>
<path d=""  transform="translate(6292, 840)"/>
<path d=""  transform="translate(7126, 840)"/>
<path d=""  transform="translate(7633, 840)"/>
<path d=""  transform="translate(8266, 840)"/>
<path d=""  transform="translate(8526, 840)"/>
<path d=""  transform="translate(8906, 840)"/>
<path d=""  transform="translate(9413, 840)"/>
<path d=""  transform="translate(9673, 840)"/>
<path d=""  transform="translate(10306, 840)"/>
<path d=""  transform="translate(10730, 840)"/>
<path d=""  transform="translate(11157, 840)"/>
<path d=""  transform="translate(11586, 840)"/>
<path d=""  transform="translate(12193, 840)"/>
<path d=""  transform="translate(12453, 840)"/>
<path d=""  transform="translate(13426, 840)"/>
<path d=""  transform="translate(14059, 840)"/>
<path d=""  transform="translate(14546, 840)"/>
<path d=""  transform="translate(14806, 840)"/>
<path d=""  transform="translate(15439, 840)"/>
<path d=""  transform="translate(16099, 840)"/>
<path d=""  transform="translate(16359, 840)"/>
<path d=""  transform="translate(16888, 840)"/>
<path d=""  transform="translate(17273, 840)"/>
<path d=""  transform="translate(17700, 840)"/>
<path d=""  transform="translate(17960, 840)"/>
<path d=""  transform="translate(18593, 840)"/>
<path d=""  transform="translate(19080, 840)"/>
<path d=""  transform="translate(19509, 840)"/>
<path d=""  transform="translate(20275, 840)"/>
<path d=""  transform="translate(20660, 840)"/>
<path d=""  transform="translate(21147, 840)"/>
<path d=""  transform="translate(21407, 840)"/>
<path d=""  transform="translate(21792, 840)"/>
<path d=""  transform="translate(22416, 840)"/>
<path d=""  transform="translate(22676, 840)"/>
<path d=""  transform="translate(23723, 840)"/>
<path d=""  transform="translate(24673, 840)"/>
<path d=""  transform="translate(24673, 840)"/>
<path d=""  transform="translate(24933, 840)"/>
<path d=""  transform="translate(24933, 840)"/>
<path d=""  transform="translate(25505, 840)"/>
<path d=""  transform="translate(25765, 840)"/>
<path d=""  transform="translate(26398, 840)"/>
<path d=""  transform="translate(27031, 840)"/>
<path d=""  transform="translate(27460, 840)"/>
<path d=""  transform="translate(28120, 840)"/>
<path d=""  transform="translate(28785, 840)"/>
<path d=""  transform="translate(28785, 840)"/>
<path d=""  transform="translate(29045, 840)"/>
<path d=""  transform="translate(29045, 840)"/>
<path d=""  transform="translate(29678, 840)"/>
<path d=""  transform="translate(30355, 840)"/>
<path d=""  transform="translate(30806, 840)"/>
<path d=""  transform="translate(31438, 840)"/>
<path d=""  transform="translate(32103, 840)"/>
<path d=""  transform="translate(32763, 840)"/>
<path d=""  transform="translate(33387, 840)"/>
<path d=""  transform="translate(33838, 840)"/>
<path d=""  transform="translate(34098, 840)"/>
<path d=""  transform="translate(34731, 840)"/>
<path d=""  transform="translate(35408, 840)"/>
<path d=""  transform="translate(35837, 840)"/>
<path d=""  transform="translate(36497, 840)"/>
<path d=""  transform="translate(37331, 840)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 37778 2130" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 840)"/>
<path d=""  transform="translate(0, 840)"/>
<path d=""  transform="translate(260, 840)"/>
<path d=""  transform="translate(260, 840)"/>
<path d=""  transform="translate(640, 840)"/>
<path d=""  transform="translate(1147, 840)"/>
<path d=""  transform="translate(1407, 840)"/>
<path d=""  transform="translate(2040, 840)"/>
<path d=""  transform="translate(2700, 840)"/>
<path d=""  transform="translate(3207, 840)"/>
<path d=""  transform="translate(4041, 840)"/>
<path d=""  transform="translate(5014, 840)"/>
<path d=""  transform="translate(5274, 840)"/>
<path d=""  transform="translate(5907, 840)"/>
<path d=""  transform="translate(6292, 840)"/>
<path d=""  transform="translate(7126, 840)"/>
<path d=""  transform="translate(7633, 840)"/>
<path d=""  transform="translate(8266, 840)"/>
<path d=""  transform="translate(8526, 840)"/>
<path d=""  transform="translate(8906, 840)"/>
<path d=""  transform="translate(9413, 840)"/>
<path d=""  transform="translate(9673, 840)"/>
<path d=""  transform="translate(10306, 840)"/>
<path d=""  transform="translate(10730, 840)"/>
<path d=""  transform="translate(11157, 840)"/>
<path d=""  transform="translate(11586, 840)"/>
<path d=""  transform="translate(12193, 840)"/>
<path d=""  transform="translate(12453, 840)"/>
<path d=""  transform="translate(13426, 840)"/>
<path d=""  transform="translate(14059, 840)"/>
<path d=""  transform="translate(14546, 840)"/>
<path d=""  transform="translate(14806, 840)"/>
<path d=""  transform="translate(15439, 840)"/>
<path d=""  transform="translate(16099, 840)"/>
<path d=""  transform="translate(16359, 840)"/>
<path d=""  transform="translate(16888, 840)"/>
<path d=""  transform="translate(17273, 840)"/>
<path d=""  transform="translate(17700, 840)"/>
<path d=""  transform="translate(17960, 840)"/>
<path d=""  transform="translate(18593, 840)"/>
<path d=""  transform="translate(19080, 840)"/>
<path d=""  transform="translate(19509, 840)"/>
<path d=""  transform="translate(20275, 840)"/>
<path d=""  transform="translate(20660, 840)"/>
<path d=""  transform="translate(21147, 840)"/>
<path d=""  transform="translate(21407, 840)"/>
<path d=""  transform="translate(21792, 840)"/>
<path d=""  transform="translate(22416, 840)"/>
<path d=""  transform="translate(22676, 840)"/>
<path d=""  transform="translate(23723, 840)"/>
<path d=""  transform="translate(24673, 840)"/>
<path d=""  transform="translate(24673, 840)"/>
<path d=""  transform="translate(24933, 840)"/>
<path d=""  transform="translate(24933, 840)"/>
<path d=""  transform="translate(25533, 840)"/>
<path d=""  transform="translate(25793, 840)"/>
<path d=""  transform="translate(26426, 840)"/>
<path d=""  transform="translate(27059, 840)"/>
<path d=""  transform="translate(27488, 840)"/>
<path d=""  transform="translate(28148, 840)"/>
<path d=""  transform="translate(28813, 840)"/>
<path d=""  transform="translate(28813, 840)"/>
<path d=""  transform="translate(29073, 840)"/>
<path d=""  transform="translate(29073, 840)"/>
<path d=""  transform="translate(29706, 840)"/>
<path d=""  transform="translate(30383, 840)"/>
<path d=""  transform="translate(30834, 840)"/>
<path d=""  transform="translate(31466, 840)"/>
<path d=""  transform="translate(32131, 840)"/>
<path d=""  transform="translate(32791, 840)"/>
<path d=""  transform="translate(33415, 840)"/>
<path d=""  transform="translate(33866, 840)"/>
<path d=""  transform="translate(34126, 840)"/>
<path d=""  transform="translate(34759, 840)"/>
<path d=""  transform="translate(35436, 840)"/>
<path d=""  transform="translate(35865, 840)"/>
<path d=""  transform="translate(36525, 840)"/>
<path d=""  transform="translate(37359, 840)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐫉𐫓𐫏𐫖𐫀 𐫏𐫗 𐫤𐫗𐫁𐫀 𐫏𐫆𐫁𐫀‬ ‫𐫖𐫓𐫇𐫀𐫀 6‬ ‫𐫐𐫓 𐫍𐫅 𐫀𐫗𐫢𐫀 𐫃𐫡𐫃 𐫛𐫀𐫢 𐫖𐫇𐫅𐫏𐫀 𐫁𐫏𐫆 𐫀𐫏𐫐 𐫍𐫅 𐫛𐫡𐫘𐫇𐫛𐫀 𐫞𐫖 𐫞𐫀‬</span></li>


<pre>Expected: space=79+0|u10AC0.fina=78+633|u10ADE.init=77+834|space=76+260|u10AD6.fina=75+994|u10ADE.init=74+834|space=73+260|u10AC0.fina=72+633|u10ADB.init=71+487|u10AC7.fina=70+429|u10AD8.init=69+766|u10AE1.fina=68+385|u10ADB.init=67+487|space=66+260|u10AC5.fina=65+385|u10ACD.init=64+624|space=63+260|u10AD0=62+1047|u10ACF.fina=61+507|u10AC0.init=60+633|space=59+260|u10AC6=58+950|u10ACF.fina=57+507|u10AC1.init=56+706|space=55+260|u10AC0=54+633|u10ACF=53+507|u10AC5=52+419|u10AC7.fina=51+429|u10AD6.init=50+665|space=49+260|u10AE2=48+973|u10AC0.fina=47+633|u10ADB.init=46+487|space=45+260|u10AC3=44+529|u10AE1.fina=43+385|u10AC3.init=42+427|space=41+260|u10AC0=40+633|u10AE2=39+973|u10AD7=38+380|u10AC0=37+633|space=36+260|u10AC5.fina=35+385|u10ACD.init=34+624|space=33+260|u10AD3=32+792|u10AD0=31+1047|space=30+0|space=29+260|space=28+0|.notdef=27+600|space=26+260|u10AC0.fina=25+633|u10AC0.init=24+633|u10AC7.fina=23+429|u10AD3.medi=22+660|u10AD6.init=21+665|space=20+0|space=19+260|space=18+0|u10AC0.fina=17+633|u10AC1.init=16+706|u10AC6=15+950|u10ACF=14+507|space=13+260|u10AC0.fina=12+633|u10AC1.medi=11+706|u10AD7.init=10+380|u10AE4=9+677|space=8+260|u10AD7=7+380|u10ACF=6+507|space=5+260|u10AC0.fina=4+633|u10AD6.init=3+665|u10ACF.fina=2+507|u10AD3.init=1+660|u10AC9=0+493</pre>



<pre>Got     : space=79+0|u10AC0.fina=78+633|u10ADE.init=77+834|space=76+260|u10AD6.fina=75+994|u10ADE.init=74+834|space=73+260|u10AC0.fina=72+633|u10ADB.init=71+487|u10AC7.fina=70+429|u10AD8.init=69+766|u10AE1.fina=68+385|u10ADB.init=67+487|space=66+260|u10AC5.fina=65+385|u10ACD.init=64+624|space=63+260|u10AD0=62+1047|u10ACF.fina=61+507|u10AC0.init=60+633|space=59+260|u10AC6=58+950|u10ACF.fina=57+507|u10AC1.init=56+706|space=55+260|u10AC0=54+633|u10ACF=53+507|u10AC5=52+419|u10AC7.fina=51+429|u10AD6.init=50+665|space=49+260|u10AE2=48+973|u10AC0.fina=47+633|u10ADB.init=46+487|space=45+260|u10AC3=44+529|u10AE1.fina=43+385|u10AC3.init=42+427|space=41+260|u10AC0=40+633|u10AE2=39+973|u10AD7=38+380|u10AC0=37+633|space=36+260|u10AC5.fina=35+385|u10ACD.init=34+624|space=33+260|u10AD3=32+792|u10AD0=31+1047|space=30+0|space=29+260|space=28+0|six=27+572|space=26+260|u10AC0.fina=25+633|u10AC0.init=24+633|u10AC7.fina=23+429|u10AD3.medi=22+660|u10AD6.init=21+665|space=20+0|space=19+260|space=18+0|u10AC0.fina=17+633|u10AC1.init=16+706|u10AC6=15+950|u10ACF=14+507|space=13+260|u10AC0.fina=12+633|u10AC1.medi=11+706|u10AD7.init=10+380|u10AE4=9+677|space=8+260|u10AD7=7+380|u10ACF=6+507|space=5+260|u10AC0.fina=4+633|u10AD6.init=3+665|u10ACF.fina=2+507|u10AD3.init=1+660|u10AC9=0+493</pre>



<pre>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       ^^^^^^^^^^^^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 40444 2130" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 840)"/>
<path d=""  transform="translate(0, 840)"/>
<path d=""  transform="translate(633, 840)"/>
<path d=""  transform="translate(1467, 840)"/>
<path d=""  transform="translate(1727, 840)"/>
<path d=""  transform="translate(2721, 840)"/>
<path d=""  transform="translate(3555, 840)"/>
<path d=""  transform="translate(3815, 840)"/>
<path d=""  transform="translate(4448, 840)"/>
<path d=""  transform="translate(4935, 840)"/>
<path d=""  transform="translate(5364, 840)"/>
<path d=""  transform="translate(6130, 840)"/>
<path d=""  transform="translate(6515, 840)"/>
<path d=""  transform="translate(7002, 840)"/>
<path d=""  transform="translate(7262, 840)"/>
<path d=""  transform="translate(7647, 840)"/>
<path d=""  transform="translate(8271, 840)"/>
<path d=""  transform="translate(8531, 840)"/>
<path d=""  transform="translate(9578, 840)"/>
<path d=""  transform="translate(10085, 840)"/>
<path d=""  transform="translate(10718, 840)"/>
<path d=""  transform="translate(10978, 840)"/>
<path d=""  transform="translate(11928, 840)"/>
<path d=""  transform="translate(12435, 840)"/>
<path d=""  transform="translate(13141, 840)"/>
<path d=""  transform="translate(13401, 840)"/>
<path d=""  transform="translate(14034, 840)"/>
<path d=""  transform="translate(14541, 840)"/>
<path d=""  transform="translate(14960, 840)"/>
<path d=""  transform="translate(15389, 840)"/>
<path d=""  transform="translate(16054, 840)"/>
<path d=""  transform="translate(16314, 840)"/>
<path d=""  transform="translate(17287, 840)"/>
<path d=""  transform="translate(17920, 840)"/>
<path d=""  transform="translate(18407, 840)"/>
<path d=""  transform="translate(18667, 840)"/>
<path d=""  transform="translate(19196, 840)"/>
<path d=""  transform="translate(19581, 840)"/>
<path d=""  transform="translate(20008, 840)"/>
<path d=""  transform="translate(20268, 840)"/>
<path d=""  transform="translate(20901, 840)"/>
<path d=""  transform="translate(21874, 840)"/>
<path d=""  transform="translate(22254, 840)"/>
<path d=""  transform="translate(22887, 840)"/>
<path d=""  transform="translate(23147, 840)"/>
<path d=""  transform="translate(23532, 840)"/>
<path d=""  transform="translate(24156, 840)"/>
<path d=""  transform="translate(24416, 840)"/>
<path d=""  transform="translate(25208, 840)"/>
<path d=""  transform="translate(26255, 840)"/>
<path d=""  transform="translate(26255, 840)"/>
<path d=""  transform="translate(26515, 840)"/>
<path d=""  transform="translate(26515, 840)"/>
<path d=""  transform="translate(27087, 840)"/>
<path d=""  transform="translate(27347, 840)"/>
<path d=""  transform="translate(27980, 840)"/>
<path d=""  transform="translate(28613, 840)"/>
<path d=""  transform="translate(29042, 840)"/>
<path d=""  transform="translate(29702, 840)"/>
<path d=""  transform="translate(30367, 840)"/>
<path d=""  transform="translate(30367, 840)"/>
<path d=""  transform="translate(30627, 840)"/>
<path d=""  transform="translate(30627, 840)"/>
<path d=""  transform="translate(31260, 840)"/>
<path d=""  transform="translate(31966, 840)"/>
<path d=""  transform="translate(32916, 840)"/>
<path d=""  transform="translate(33423, 840)"/>
<path d=""  transform="translate(33683, 840)"/>
<path d=""  transform="translate(34316, 840)"/>
<path d=""  transform="translate(35022, 840)"/>
<path d=""  transform="translate(35402, 840)"/>
<path d=""  transform="translate(36079, 840)"/>
<path d=""  transform="translate(36339, 840)"/>
<path d=""  transform="translate(36719, 840)"/>
<path d=""  transform="translate(37226, 840)"/>
<path d=""  transform="translate(37486, 840)"/>
<path d=""  transform="translate(38119, 840)"/>
<path d=""  transform="translate(38784, 840)"/>
<path d=""  transform="translate(39291, 840)"/>
<path d=""  transform="translate(39951, 840)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 40472 2130" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 840)"/>
<path d=""  transform="translate(0, 840)"/>
<path d=""  transform="translate(633, 840)"/>
<path d=""  transform="translate(1467, 840)"/>
<path d=""  transform="translate(1727, 840)"/>
<path d=""  transform="translate(2721, 840)"/>
<path d=""  transform="translate(3555, 840)"/>
<path d=""  transform="translate(3815, 840)"/>
<path d=""  transform="translate(4448, 840)"/>
<path d=""  transform="translate(4935, 840)"/>
<path d=""  transform="translate(5364, 840)"/>
<path d=""  transform="translate(6130, 840)"/>
<path d=""  transform="translate(6515, 840)"/>
<path d=""  transform="translate(7002, 840)"/>
<path d=""  transform="translate(7262, 840)"/>
<path d=""  transform="translate(7647, 840)"/>
<path d=""  transform="translate(8271, 840)"/>
<path d=""  transform="translate(8531, 840)"/>
<path d=""  transform="translate(9578, 840)"/>
<path d=""  transform="translate(10085, 840)"/>
<path d=""  transform="translate(10718, 840)"/>
<path d=""  transform="translate(10978, 840)"/>
<path d=""  transform="translate(11928, 840)"/>
<path d=""  transform="translate(12435, 840)"/>
<path d=""  transform="translate(13141, 840)"/>
<path d=""  transform="translate(13401, 840)"/>
<path d=""  transform="translate(14034, 840)"/>
<path d=""  transform="translate(14541, 840)"/>
<path d=""  transform="translate(14960, 840)"/>
<path d=""  transform="translate(15389, 840)"/>
<path d=""  transform="translate(16054, 840)"/>
<path d=""  transform="translate(16314, 840)"/>
<path d=""  transform="translate(17287, 840)"/>
<path d=""  transform="translate(17920, 840)"/>
<path d=""  transform="translate(18407, 840)"/>
<path d=""  transform="translate(18667, 840)"/>
<path d=""  transform="translate(19196, 840)"/>
<path d=""  transform="translate(19581, 840)"/>
<path d=""  transform="translate(20008, 840)"/>
<path d=""  transform="translate(20268, 840)"/>
<path d=""  transform="translate(20901, 840)"/>
<path d=""  transform="translate(21874, 840)"/>
<path d=""  transform="translate(22254, 840)"/>
<path d=""  transform="translate(22887, 840)"/>
<path d=""  transform="translate(23147, 840)"/>
<path d=""  transform="translate(23532, 840)"/>
<path d=""  transform="translate(24156, 840)"/>
<path d=""  transform="translate(24416, 840)"/>
<path d=""  transform="translate(25208, 840)"/>
<path d=""  transform="translate(26255, 840)"/>
<path d=""  transform="translate(26255, 840)"/>
<path d=""  transform="translate(26515, 840)"/>
<path d=""  transform="translate(26515, 840)"/>
<path d=""  transform="translate(27115, 840)"/>
<path d=""  transform="translate(27375, 840)"/>
<path d=""  transform="translate(28008, 840)"/>
<path d=""  transform="translate(28641, 840)"/>
<path d=""  transform="translate(29070, 840)"/>
<path d=""  transform="translate(29730, 840)"/>
<path d=""  transform="translate(30395, 840)"/>
<path d=""  transform="translate(30395, 840)"/>
<path d=""  transform="translate(30655, 840)"/>
<path d=""  transform="translate(30655, 840)"/>
<path d=""  transform="translate(31288, 840)"/>
<path d=""  transform="translate(31994, 840)"/>
<path d=""  transform="translate(32944, 840)"/>
<path d=""  transform="translate(33451, 840)"/>
<path d=""  transform="translate(33711, 840)"/>
<path d=""  transform="translate(34344, 840)"/>
<path d=""  transform="translate(35050, 840)"/>
<path d=""  transform="translate(35430, 840)"/>
<path d=""  transform="translate(36107, 840)"/>
<path d=""  transform="translate(36367, 840)"/>
<path d=""  transform="translate(36747, 840)"/>
<path d=""  transform="translate(37254, 840)"/>
<path d=""  transform="translate(37514, 840)"/>
<path d=""  transform="translate(38147, 840)"/>
<path d=""  transform="translate(38812, 840)"/>
<path d=""  transform="translate(39319, 840)"/>
<path d=""  transform="translate(39979, 840)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">‫𐫗𐫇𐫗‬ ‫𐫖𐫓𐫇𐫀𐫀 7‬ ‫𐫐𐫓 𐫀𐫗𐫢𐫀 𐫏𐫓𐫆 𐫁𐫡𐫁𐫡 𐫞𐫖 𐫞𐫀𐫗𐫇𐫗 𐫇𐫃𐫡𐫃 𐫛𐫀𐫢 𐫗𐫎𐫏𐫡𐫀 𐫁𐫏𐫅 𐫞𐫀‬ ‫𐫗𐫇𐫗 𐫅𐫓𐫀 𐫖𐫤𐫇𐫤𐫀</span></li>


<pre>Expected: u10AC0=79+633|u10AE4=78+677|u10AC7=77+451|u10AE4.fina=76+632|u10AD6.init=75+665|space=74+260|u10AC0.fina=73+633|u10AD3.init=72+660|u10AC5=71+419|space=70+260|u10AD7=69+380|u10AC7.fina=68+429|u10AD7.init=67+380|space=66+0|space=65+260|space=64+0|u10AC0.fina=63+633|u10ADE.init=62+834|space=61+260|u10AC5=60+419|u10ACF.fina=59+507|u10AC1.init=58+706|space=57+260|u10AC0=56+633|u10AE1=55+419|u10ACF=54+507|u10ACE.fina=53+530|u10AD7.init=52+380|space=51+260|u10AE2=50+973|u10AC0.fina=49+633|u10ADB.init=48+487|space=47+260|u10AC3=46+529|u10AE1.fina=45+385|u10AC3.init=44+427|u10AC7=43+451|space=42+260|u10AD7=41+380|u10AC7.fina=40+429|u10AD7.init=39+380|u10AC0.fina=38+633|u10ADE.init=37+834|space=36+260|u10AD6.fina=35+994|u10ADE.init=34+834|space=33+260|u10AE1.fina=32+385|u10AC1.init=31+706|u10AE1.fina=30+385|u10AC1.init=29+706|space=28+260|u10AC6=27+950|u10AD3=26+792|u10ACF=25+507|space=24+260|u10AC0=23+633|u10AE2=22+973|u10AD7=21+380|u10AC0=20+633|space=19+260|u10AD3=18+792|u10AD0=17+1047|space=16+0|space=15+260|space=14+0|.notdef=13+600|space=12+260|u10AC0.fina=11+633|u10AC0.init=10+633|u10AC7.fina=9+429|u10AD3.medi=8+660|u10AD6.init=7+665|space=6+0|space=5+260|space=4+0|u10AD7=3+380|u10AC7.fina=2+429|u10AD7.init=1+380|space=0+0</pre>



<pre>Got     : u10AC0=79+633|u10AE4=78+677|u10AC7=77+451|u10AE4.fina=76+632|u10AD6.init=75+665|space=74+260|u10AC0.fina=73+633|u10AD3.init=72+660|u10AC5=71+419|space=70+260|u10AD7=69+380|u10AC7.fina=68+429|u10AD7.init=67+380|space=66+0|space=65+260|space=64+0|u10AC0.fina=63+633|u10ADE.init=62+834|space=61+260|u10AC5=60+419|u10ACF.fina=59+507|u10AC1.init=58+706|space=57+260|u10AC0=56+633|u10AE1=55+419|u10ACF=54+507|u10ACE.fina=53+530|u10AD7.init=52+380|space=51+260|u10AE2=50+973|u10AC0.fina=49+633|u10ADB.init=48+487|space=47+260|u10AC3=46+529|u10AE1.fina=45+385|u10AC3.init=44+427|u10AC7=43+451|space=42+260|u10AD7=41+380|u10AC7.fina=40+429|u10AD7.init=39+380|u10AC0.fina=38+633|u10ADE.init=37+834|space=36+260|u10AD6.fina=35+994|u10ADE.init=34+834|space=33+260|u10AE1.fina=32+385|u10AC1.init=31+706|u10AE1.fina=30+385|u10AC1.init=29+706|space=28+260|u10AC6=27+950|u10AD3=26+792|u10ACF=25+507|space=24+260|u10AC0=23+633|u10AE2=22+973|u10AD7=21+380|u10AC0=20+633|space=19+260|u10AD3=18+792|u10AD0=17+1047|space=16+0|space=15+260|space=14+0|seven=13+572|space=12+260|u10AC0.fina=11+633|u10AC0.init=10+633|u10AC7.fina=9+429|u10AD3.medi=8+660|u10AD6.init=7+665|space=6+0|space=5+260|space=4+0|u10AD7=3+380|u10AC7.fina=2+429|u10AD7.init=1+380|space=0+0</pre>



<pre>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               ^^^^^^^^^^^^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 37726 2130" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 840)"/>
<path d=""  transform="translate(633, 840)"/>
<path d=""  transform="translate(1310, 840)"/>
<path d=""  transform="translate(1761, 840)"/>
<path d=""  transform="translate(2393, 840)"/>
<path d=""  transform="translate(3058, 840)"/>
<path d=""  transform="translate(3318, 840)"/>
<path d=""  transform="translate(3951, 840)"/>
<path d=""  transform="translate(4611, 840)"/>
<path d=""  transform="translate(5030, 840)"/>
<path d=""  transform="translate(5290, 840)"/>
<path d=""  transform="translate(5670, 840)"/>
<path d=""  transform="translate(6099, 840)"/>
<path d=""  transform="translate(6479, 840)"/>
<path d=""  transform="translate(6479, 840)"/>
<path d=""  transform="translate(6739, 840)"/>
<path d=""  transform="translate(6739, 840)"/>
<path d=""  transform="translate(7372, 840)"/>
<path d=""  transform="translate(8206, 840)"/>
<path d=""  transform="translate(8466, 840)"/>
<path d=""  transform="translate(8885, 840)"/>
<path d=""  transform="translate(9392, 840)"/>
<path d=""  transform="translate(10098, 840)"/>
<path d=""  transform="translate(10358, 840)"/>
<path d=""  transform="translate(10991, 840)"/>
<path d=""  transform="translate(11410, 840)"/>
<path d=""  transform="translate(11917, 840)"/>
<path d=""  transform="translate(12447, 840)"/>
<path d=""  transform="translate(12827, 840)"/>
<path d=""  transform="translate(13087, 840)"/>
<path d=""  transform="translate(14060, 840)"/>
<path d=""  transform="translate(14693, 840)"/>
<path d=""  transform="translate(15180, 840)"/>
<path d=""  transform="translate(15440, 840)"/>
<path d=""  transform="translate(15969, 840)"/>
<path d=""  transform="translate(16354, 840)"/>
<path d=""  transform="translate(16781, 840)"/>
<path d=""  transform="translate(17232, 840)"/>
<path d=""  transform="translate(17492, 840)"/>
<path d=""  transform="translate(17872, 840)"/>
<path d=""  transform="translate(18301, 840)"/>
<path d=""  transform="translate(18681, 840)"/>
<path d=""  transform="translate(19314, 840)"/>
<path d=""  transform="translate(20148, 840)"/>
<path d=""  transform="translate(20408, 840)"/>
<path d=""  transform="translate(21402, 840)"/>
<path d=""  transform="translate(22236, 840)"/>
<path d=""  transform="translate(22496, 840)"/>
<path d=""  transform="translate(22881, 840)"/>
<path d=""  transform="translate(23587, 840)"/>
<path d=""  transform="translate(23972, 840)"/>
<path d=""  transform="translate(24678, 840)"/>
<path d=""  transform="translate(24938, 840)"/>
<path d=""  transform="translate(25888, 840)"/>
<path d=""  transform="translate(26680, 840)"/>
<path d=""  transform="translate(27187, 840)"/>
<path d=""  transform="translate(27447, 840)"/>
<path d=""  transform="translate(28080, 840)"/>
<path d=""  transform="translate(29053, 840)"/>
<path d=""  transform="translate(29433, 840)"/>
<path d=""  transform="translate(30066, 840)"/>
<path d=""  transform="translate(30326, 840)"/>
<path d=""  transform="translate(31118, 840)"/>
<path d=""  transform="translate(32165, 840)"/>
<path d=""  transform="translate(32165, 840)"/>
<path d=""  transform="translate(32425, 840)"/>
<path d=""  transform="translate(32425, 840)"/>
<path d=""  transform="translate(32997, 840)"/>
<path d=""  transform="translate(33257, 840)"/>
<path d=""  transform="translate(33890, 840)"/>
<path d=""  transform="translate(34523, 840)"/>
<path d=""  transform="translate(34952, 840)"/>
<path d=""  transform="translate(35612, 840)"/>
<path d=""  transform="translate(36277, 840)"/>
<path d=""  transform="translate(36277, 840)"/>
<path d=""  transform="translate(36537, 840)"/>
<path d=""  transform="translate(36537, 840)"/>
<path d=""  transform="translate(36917, 840)"/>
<path d=""  transform="translate(37346, 840)"/>
<path d=""  transform="translate(37726, 840)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 37754 2130" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 840)"/>
<path d=""  transform="translate(633, 840)"/>
<path d=""  transform="translate(1310, 840)"/>
<path d=""  transform="translate(1761, 840)"/>
<path d=""  transform="translate(2393, 840)"/>
<path d=""  transform="translate(3058, 840)"/>
<path d=""  transform="translate(3318, 840)"/>
<path d=""  transform="translate(3951, 840)"/>
<path d=""  transform="translate(4611, 840)"/>
<path d=""  transform="translate(5030, 840)"/>
<path d=""  transform="translate(5290, 840)"/>
<path d=""  transform="translate(5670, 840)"/>
<path d=""  transform="translate(6099, 840)"/>
<path d=""  transform="translate(6479, 840)"/>
<path d=""  transform="translate(6479, 840)"/>
<path d=""  transform="translate(6739, 840)"/>
<path d=""  transform="translate(6739, 840)"/>
<path d=""  transform="translate(7372, 840)"/>
<path d=""  transform="translate(8206, 840)"/>
<path d=""  transform="translate(8466, 840)"/>
<path d=""  transform="translate(8885, 840)"/>
<path d=""  transform="translate(9392, 840)"/>
<path d=""  transform="translate(10098, 840)"/>
<path d=""  transform="translate(10358, 840)"/>
<path d=""  transform="translate(10991, 840)"/>
<path d=""  transform="translate(11410, 840)"/>
<path d=""  transform="translate(11917, 840)"/>
<path d=""  transform="translate(12447, 840)"/>
<path d=""  transform="translate(12827, 840)"/>
<path d=""  transform="translate(13087, 840)"/>
<path d=""  transform="translate(14060, 840)"/>
<path d=""  transform="translate(14693, 840)"/>
<path d=""  transform="translate(15180, 840)"/>
<path d=""  transform="translate(15440, 840)"/>
<path d=""  transform="translate(15969, 840)"/>
<path d=""  transform="translate(16354, 840)"/>
<path d=""  transform="translate(16781, 840)"/>
<path d=""  transform="translate(17232, 840)"/>
<path d=""  transform="translate(17492, 840)"/>
<path d=""  transform="translate(17872, 840)"/>
<path d=""  transform="translate(18301, 840)"/>
<path d=""  transform="translate(18681, 840)"/>
<path d=""  transform="translate(19314, 840)"/>
<path d=""  transform="translate(20148, 840)"/>
<path d=""  transform="translate(20408, 840)"/>
<path d=""  transform="translate(21402, 840)"/>
<path d=""  transform="translate(22236, 840)"/>
<path d=""  transform="translate(22496, 840)"/>
<path d=""  transform="translate(22881, 840)"/>
<path d=""  transform="translate(23587, 840)"/>
<path d=""  transform="translate(23972, 840)"/>
<path d=""  transform="translate(24678, 840)"/>
<path d=""  transform="translate(24938, 840)"/>
<path d=""  transform="translate(25888, 840)"/>
<path d=""  transform="translate(26680, 840)"/>
<path d=""  transform="translate(27187, 840)"/>
<path d=""  transform="translate(27447, 840)"/>
<path d=""  transform="translate(28080, 840)"/>
<path d=""  transform="translate(29053, 840)"/>
<path d=""  transform="translate(29433, 840)"/>
<path d=""  transform="translate(30066, 840)"/>
<path d=""  transform="translate(30326, 840)"/>
<path d=""  transform="translate(31118, 840)"/>
<path d=""  transform="translate(32165, 840)"/>
<path d=""  transform="translate(32165, 840)"/>
<path d=""  transform="translate(32425, 840)"/>
<path d=""  transform="translate(32425, 840)"/>
<path d=""  transform="translate(33025, 840)"/>
<path d=""  transform="translate(33285, 840)"/>
<path d=""  transform="translate(33918, 840)"/>
<path d=""  transform="translate(34551, 840)"/>
<path d=""  transform="translate(34980, 840)"/>
<path d=""  transform="translate(35640, 840)"/>
<path d=""  transform="translate(36305, 840)"/>
<path d=""  transform="translate(36305, 840)"/>
<path d=""  transform="translate(36565, 840)"/>
<path d=""  transform="translate(36565, 840)"/>
<path d=""  transform="translate(36945, 840)"/>
<path d=""  transform="translate(37374, 840)"/>
<path d=""  transform="translate(37754, 840)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐫁𐫇𐫅𐫞𐫀‬ ‫𐫖𐫓𐫇𐫀𐫀 8‬ ‫𐫐𐫓 𐫍𐫅 𐫀𐫏𐫤𐫓𐫆 𐫆𐫞𐫇𐫤𐫀 𐫅𐫛𐫀𐫢 𐫛𐫇𐫡𐫙𐫏𐫀 𐫁𐫏𐫅 𐫍𐫅 𐫁𐫏𐫤 𐫅𐫏𐫗𐫀 𐫞‬ ‫𐫀 𐫙𐫁𐫅𐫇𐫏𐫤𐫀 𐫓𐫀</span></li>


<pre>Expected: u10AC0.fina=79+633|u10AD3.init=78+660|space=77+260|u10AC0=76+633|u10AE4=75+677|u10ACF=74+507|u10AC7=73+451|u10AC5.fina=72+385|u10AC1.medi=71+706|u10AD9.init=70+607|space=69+260|u10AC0=68+633|space=67+0|space=66+260|space=65+0|u10ADE=64+1169|space=63+260|u10AC0.fina=62+633|u10AD7.init=61+380|u10ACF=60+507|u10AC5=59+419|space=58+260|u10AE4=57+677|u10ACF.fina=56+507|u10AC1.init=55+706|space=54+260|u10AC5.fina=53+385|u10ACD.init=52+624|space=51+260|u10AC5=50+419|u10ACF.fina=49+507|u10AC1.init=48+706|space=47+260|u10AC0=46+633|u10ACF.fina=45+507|u10AD9.init=44+607|u10AE1=43+419|u10AC7.fina=42+429|u10ADB.init=41+487|space=40+260|u10AE2=39+973|u10AC0.fina=38+633|u10ADB.init=37+487|u10AC5=36+419|space=35+260|u10AC0=34+633|u10AE4=33+677|u10AC7.fina=32+429|u10ADE.init=31+834|u10AC6=30+950|space=29+260|u10AC6=28+950|u10AD3=27+792|u10AE4=26+677|u10ACF.fina=25+507|u10AC0.init=24+633|space=23+260|u10AC5.fina=22+385|u10ACD.init=21+624|space=20+260|u10AD3=19+792|u10AD0=18+1047|space=17+0|space=16+260|space=15+0|.notdef=14+600|space=13+260|u10AC0.fina=12+633|u10AC0.init=11+633|u10AC7.fina=10+429|u10AD3.medi=9+660|u10AD6.init=8+665|space=7+0|space=6+260|space=5+0|u10AC0.fina=4+633|u10ADE.init=3+834|u10AC5=2+419|u10AC7.fina=1+429|u10AC1.init=0+706</pre>



<pre>Got     : u10AC0.fina=79+633|u10AD3.init=78+660|space=77+260|u10AC0=76+633|u10AE4=75+677|u10ACF=74+507|u10AC7=73+451|u10AC5.fina=72+385|u10AC1.medi=71+706|u10AD9.init=70+607|space=69+260|u10AC0=68+633|space=67+0|space=66+260|space=65+0|u10ADE=64+1169|space=63+260|u10AC0.fina=62+633|u10AD7.init=61+380|u10ACF=60+507|u10AC5=59+419|space=58+260|u10AE4=57+677|u10ACF.fina=56+507|u10AC1.init=55+706|space=54+260|u10AC5.fina=53+385|u10ACD.init=52+624|space=51+260|u10AC5=50+419|u10ACF.fina=49+507|u10AC1.init=48+706|space=47+260|u10AC0=46+633|u10ACF.fina=45+507|u10AD9.init=44+607|u10AE1=43+419|u10AC7.fina=42+429|u10ADB.init=41+487|space=40+260|u10AE2=39+973|u10AC0.fina=38+633|u10ADB.init=37+487|u10AC5=36+419|space=35+260|u10AC0=34+633|u10AE4=33+677|u10AC7.fina=32+429|u10ADE.init=31+834|u10AC6=30+950|space=29+260|u10AC6=28+950|u10AD3=27+792|u10AE4=26+677|u10ACF.fina=25+507|u10AC0.init=24+633|space=23+260|u10AC5.fina=22+385|u10ACD.init=21+624|space=20+260|u10AD3=19+792|u10AD0=18+1047|space=17+0|space=16+260|space=15+0|eight=14+572|space=13+260|u10AC0.fina=12+633|u10AC0.init=11+633|u10AC7.fina=10+429|u10AD3.medi=9+660|u10AD6.init=8+665|space=7+0|space=6+260|space=5+0|u10AC0.fina=4+633|u10ADE.init=3+834|u10AC5=2+419|u10AC7.fina=1+429|u10AC1.init=0+706</pre>



<pre>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             ^^^^^^^^^^^^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 39828 2130" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 840)"/>
<path d=""  transform="translate(633, 840)"/>
<path d=""  transform="translate(1293, 840)"/>
<path d=""  transform="translate(1553, 840)"/>
<path d=""  transform="translate(2186, 840)"/>
<path d=""  transform="translate(2863, 840)"/>
<path d=""  transform="translate(3370, 840)"/>
<path d=""  transform="translate(3821, 840)"/>
<path d=""  transform="translate(4206, 840)"/>
<path d=""  transform="translate(4912, 840)"/>
<path d=""  transform="translate(5519, 840)"/>
<path d=""  transform="translate(5779, 840)"/>
<path d=""  transform="translate(6412, 840)"/>
<path d=""  transform="translate(6412, 840)"/>
<path d=""  transform="translate(6672, 840)"/>
<path d=""  transform="translate(6672, 840)"/>
<path d=""  transform="translate(7841, 840)"/>
<path d=""  transform="translate(8101, 840)"/>
<path d=""  transform="translate(8734, 840)"/>
<path d=""  transform="translate(9114, 840)"/>
<path d=""  transform="translate(9621, 840)"/>
<path d=""  transform="translate(10040, 840)"/>
<path d=""  transform="translate(10300, 840)"/>
<path d=""  transform="translate(10977, 840)"/>
<path d=""  transform="translate(11484, 840)"/>
<path d=""  transform="translate(12190, 840)"/>
<path d=""  transform="translate(12450, 840)"/>
<path d=""  transform="translate(12835, 840)"/>
<path d=""  transform="translate(13459, 840)"/>
<path d=""  transform="translate(13719, 840)"/>
<path d=""  transform="translate(14138, 840)"/>
<path d=""  transform="translate(14645, 840)"/>
<path d=""  transform="translate(15351, 840)"/>
<path d=""  transform="translate(15611, 840)"/>
<path d=""  transform="translate(16244, 840)"/>
<path d=""  transform="translate(16751, 840)"/>
<path d=""  transform="translate(17358, 840)"/>
<path d=""  transform="translate(17777, 840)"/>
<path d=""  transform="translate(18206, 840)"/>
<path d=""  transform="translate(18693, 840)"/>
<path d=""  transform="translate(18953, 840)"/>
<path d=""  transform="translate(19926, 840)"/>
<path d=""  transform="translate(20559, 840)"/>
<path d=""  transform="translate(21046, 840)"/>
<path d=""  transform="translate(21465, 840)"/>
<path d=""  transform="translate(21725, 840)"/>
<path d=""  transform="translate(22358, 840)"/>
<path d=""  transform="translate(23035, 840)"/>
<path d=""  transform="translate(23464, 840)"/>
<path d=""  transform="translate(24298, 840)"/>
<path d=""  transform="translate(25248, 840)"/>
<path d=""  transform="translate(25508, 840)"/>
<path d=""  transform="translate(26458, 840)"/>
<path d=""  transform="translate(27250, 840)"/>
<path d=""  transform="translate(27927, 840)"/>
<path d=""  transform="translate(28434, 840)"/>
<path d=""  transform="translate(29067, 840)"/>
<path d=""  transform="translate(29327, 840)"/>
<path d=""  transform="translate(29712, 840)"/>
<path d=""  transform="translate(30336, 840)"/>
<path d=""  transform="translate(30596, 840)"/>
<path d=""  transform="translate(31388, 840)"/>
<path d=""  transform="translate(32435, 840)"/>
<path d=""  transform="translate(32435, 840)"/>
<path d=""  transform="translate(32695, 840)"/>
<path d=""  transform="translate(32695, 840)"/>
<path d=""  transform="translate(33267, 840)"/>
<path d=""  transform="translate(33527, 840)"/>
<path d=""  transform="translate(34160, 840)"/>
<path d=""  transform="translate(34793, 840)"/>
<path d=""  transform="translate(35222, 840)"/>
<path d=""  transform="translate(35882, 840)"/>
<path d=""  transform="translate(36547, 840)"/>
<path d=""  transform="translate(36547, 840)"/>
<path d=""  transform="translate(36807, 840)"/>
<path d=""  transform="translate(36807, 840)"/>
<path d=""  transform="translate(37440, 840)"/>
<path d=""  transform="translate(38274, 840)"/>
<path d=""  transform="translate(38693, 840)"/>
<path d=""  transform="translate(39122, 840)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 39856 2130" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 840)"/>
<path d=""  transform="translate(633, 840)"/>
<path d=""  transform="translate(1293, 840)"/>
<path d=""  transform="translate(1553, 840)"/>
<path d=""  transform="translate(2186, 840)"/>
<path d=""  transform="translate(2863, 840)"/>
<path d=""  transform="translate(3370, 840)"/>
<path d=""  transform="translate(3821, 840)"/>
<path d=""  transform="translate(4206, 840)"/>
<path d=""  transform="translate(4912, 840)"/>
<path d=""  transform="translate(5519, 840)"/>
<path d=""  transform="translate(5779, 840)"/>
<path d=""  transform="translate(6412, 840)"/>
<path d=""  transform="translate(6412, 840)"/>
<path d=""  transform="translate(6672, 840)"/>
<path d=""  transform="translate(6672, 840)"/>
<path d=""  transform="translate(7841, 840)"/>
<path d=""  transform="translate(8101, 840)"/>
<path d=""  transform="translate(8734, 840)"/>
<path d=""  transform="translate(9114, 840)"/>
<path d=""  transform="translate(9621, 840)"/>
<path d=""  transform="translate(10040, 840)"/>
<path d=""  transform="translate(10300, 840)"/>
<path d=""  transform="translate(10977, 840)"/>
<path d=""  transform="translate(11484, 840)"/>
<path d=""  transform="translate(12190, 840)"/>
<path d=""  transform="translate(12450, 840)"/>
<path d=""  transform="translate(12835, 840)"/>
<path d=""  transform="translate(13459, 840)"/>
<path d=""  transform="translate(13719, 840)"/>
<path d=""  transform="translate(14138, 840)"/>
<path d=""  transform="translate(14645, 840)"/>
<path d=""  transform="translate(15351, 840)"/>
<path d=""  transform="translate(15611, 840)"/>
<path d=""  transform="translate(16244, 840)"/>
<path d=""  transform="translate(16751, 840)"/>
<path d=""  transform="translate(17358, 840)"/>
<path d=""  transform="translate(17777, 840)"/>
<path d=""  transform="translate(18206, 840)"/>
<path d=""  transform="translate(18693, 840)"/>
<path d=""  transform="translate(18953, 840)"/>
<path d=""  transform="translate(19926, 840)"/>
<path d=""  transform="translate(20559, 840)"/>
<path d=""  transform="translate(21046, 840)"/>
<path d=""  transform="translate(21465, 840)"/>
<path d=""  transform="translate(21725, 840)"/>
<path d=""  transform="translate(22358, 840)"/>
<path d=""  transform="translate(23035, 840)"/>
<path d=""  transform="translate(23464, 840)"/>
<path d=""  transform="translate(24298, 840)"/>
<path d=""  transform="translate(25248, 840)"/>
<path d=""  transform="translate(25508, 840)"/>
<path d=""  transform="translate(26458, 840)"/>
<path d=""  transform="translate(27250, 840)"/>
<path d=""  transform="translate(27927, 840)"/>
<path d=""  transform="translate(28434, 840)"/>
<path d=""  transform="translate(29067, 840)"/>
<path d=""  transform="translate(29327, 840)"/>
<path d=""  transform="translate(29712, 840)"/>
<path d=""  transform="translate(30336, 840)"/>
<path d=""  transform="translate(30596, 840)"/>
<path d=""  transform="translate(31388, 840)"/>
<path d=""  transform="translate(32435, 840)"/>
<path d=""  transform="translate(32435, 840)"/>
<path d=""  transform="translate(32695, 840)"/>
<path d=""  transform="translate(32695, 840)"/>
<path d=""  transform="translate(33295, 840)"/>
<path d=""  transform="translate(33555, 840)"/>
<path d=""  transform="translate(34188, 840)"/>
<path d=""  transform="translate(34821, 840)"/>
<path d=""  transform="translate(35250, 840)"/>
<path d=""  transform="translate(35910, 840)"/>
<path d=""  transform="translate(36575, 840)"/>
<path d=""  transform="translate(36575, 840)"/>
<path d=""  transform="translate(36835, 840)"/>
<path d=""  transform="translate(36835, 840)"/>
<path d=""  transform="translate(37468, 840)"/>
<path d=""  transform="translate(38302, 840)"/>
<path d=""  transform="translate(38721, 840)"/>
<path d=""  transform="translate(39150, 840)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">‫𐫖𐫓𐫇𐫀𐫀 9‬ ‫𐫃𐫡𐫃 𐫆𐫐 𐫍𐫅 𐫓𐫀 𐫛𐫀𐫢 𐫅𐫁𐫏𐫞𐫀 𐫏𐫗 𐫖𐫇𐫤𐫁𐫀 𐫃𐫇 𐫁𐫏𐫤 𐫀𐫘𐫏𐫡𐫀 𐫏𐫗‬ ‫ 𐫎𐫡𐫏𐫅𐫀 𐫖𐫗 𐫀𐫤𐫡𐫀 𐫅𐫓𐫀</span></li>


<pre>Expected: u10AC0.fina=78+633|u10AD3.init=77+660|u10AC5=76+419|space=75+260|u10AC0=74+633|u10AE1=73+419|u10AE4.fina=72+632|u10AC0.init=71+633|space=70+260|u10AD7=69+380|u10AD6=68+994|space=67+260|u10AC0=66+633|u10AC5=65+419|u10ACF=64+507|u10AE1=63+419|u10ACE=62+520|space=61+260|space=60+0|space=59+260|space=58+0|u10AD7=57+380|u10ACF=56+507|space=55+260|u10AC0=54+633|u10AE1=53+419|u10ACF.fina=52+507|u10AD8.medi=51+766|u10AC0.init=50+633|space=49+260|u10AE4=48+677|u10ACF.fina=47+507|u10AC1.init=46+706|space=45+260|u10AC7.fina=44+429|u10AC3.init=43+427|space=42+260|u10AC0.fina=41+633|u10AC1.init=40+706|u10AE4=39+677|u10AC7.fina=38+429|u10AD6.init=37+665|space=36+260|u10AD7=35+380|u10ACF=34+507|space=33+260|u10AC0.fina=32+633|u10ADE.init=31+834|u10ACF.fina=30+507|u10AC1.init=29+706|u10AC5=28+419|space=27+260|u10AE2=26+973|u10AC0.fina=25+633|u10ADB.init=24+487|space=23+260|u10AC0.fina=22+633|u10AD3.init=21+660|space=20+260|u10AC5.fina=19+385|u10ACD.init=18+624|space=17+260|u10AD0=16+1047|u10AC6=15+950|space=14+260|u10AC3=13+529|u10AE1.fina=12+385|u10AC3.init=11+427|space=10+0|space=9+260|space=8+0|.notdef=7+600|space=6+260|u10AC0.fina=5+633|u10AC0.init=4+633|u10AC7.fina=3+429|u10AD3.medi=2+660|u10AD6.init=1+665|space=0+0</pre>



<pre>Got     : u10AC0.fina=78+633|u10AD3.init=77+660|u10AC5=76+419|space=75+260|u10AC0=74+633|u10AE1=73+419|u10AE4.fina=72+632|u10AC0.init=71+633|space=70+260|u10AD7=69+380|u10AD6=68+994|space=67+260|u10AC0=66+633|u10AC5=65+419|u10ACF=64+507|u10AE1=63+419|u10ACE=62+520|space=61+260|space=60+0|space=59+260|space=58+0|u10AD7=57+380|u10ACF=56+507|space=55+260|u10AC0=54+633|u10AE1=53+419|u10ACF.fina=52+507|u10AD8.medi=51+766|u10AC0.init=50+633|space=49+260|u10AE4=48+677|u10ACF.fina=47+507|u10AC1.init=46+706|space=45+260|u10AC7.fina=44+429|u10AC3.init=43+427|space=42+260|u10AC0.fina=41+633|u10AC1.init=40+706|u10AE4=39+677|u10AC7.fina=38+429|u10AD6.init=37+665|space=36+260|u10AD7=35+380|u10ACF=34+507|space=33+260|u10AC0.fina=32+633|u10ADE.init=31+834|u10ACF.fina=30+507|u10AC1.init=29+706|u10AC5=28+419|space=27+260|u10AE2=26+973|u10AC0.fina=25+633|u10ADB.init=24+487|space=23+260|u10AC0.fina=22+633|u10AD3.init=21+660|space=20+260|u10AC5.fina=19+385|u10ACD.init=18+624|space=17+260|u10AD0=16+1047|u10AC6=15+950|space=14+260|u10AC3=13+529|u10AE1.fina=12+385|u10AC3.init=11+427|space=10+0|space=9+260|space=8+0|nine=7+572|space=6+260|u10AC0.fina=5+633|u10AC0.init=4+633|u10AC7.fina=3+429|u10AD3.medi=2+660|u10AD6.init=1+665|space=0+0</pre>



<pre>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     ^^^^^^^^^^^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 37593 2130" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 840)"/>
<path d=""  transform="translate(633, 840)"/>
<path d=""  transform="translate(1293, 840)"/>
<path d=""  transform="translate(1712, 840)"/>
<path d=""  transform="translate(1972, 840)"/>
<path d=""  transform="translate(2605, 840)"/>
<path d=""  transform="translate(3024, 840)"/>
<path d=""  transform="translate(3656, 840)"/>
<path d=""  transform="translate(4289, 840)"/>
<path d=""  transform="translate(4549, 840)"/>
<path d=""  transform="translate(4929, 840)"/>
<path d=""  transform="translate(5923, 840)"/>
<path d=""  transform="translate(6183, 840)"/>
<path d=""  transform="translate(6816, 840)"/>
<path d=""  transform="translate(7235, 840)"/>
<path d=""  transform="translate(7742, 840)"/>
<path d=""  transform="translate(8161, 840)"/>
<path d=""  transform="translate(8681, 840)"/>
<path d=""  transform="translate(8941, 840)"/>
<path d=""  transform="translate(8941, 840)"/>
<path d=""  transform="translate(9201, 840)"/>
<path d=""  transform="translate(9201, 840)"/>
<path d=""  transform="translate(9581, 840)"/>
<path d=""  transform="translate(10088, 840)"/>
<path d=""  transform="translate(10348, 840)"/>
<path d=""  transform="translate(10981, 840)"/>
<path d=""  transform="translate(11400, 840)"/>
<path d=""  transform="translate(11907, 840)"/>
<path d=""  transform="translate(12673, 840)"/>
<path d=""  transform="translate(13306, 840)"/>
<path d=""  transform="translate(13566, 840)"/>
<path d=""  transform="translate(14243, 840)"/>
<path d=""  transform="translate(14750, 840)"/>
<path d=""  transform="translate(15456, 840)"/>
<path d=""  transform="translate(15716, 840)"/>
<path d=""  transform="translate(16145, 840)"/>
<path d=""  transform="translate(16572, 840)"/>
<path d=""  transform="translate(16832, 840)"/>
<path d=""  transform="translate(17465, 840)"/>
<path d=""  transform="translate(18171, 840)"/>
<path d=""  transform="translate(18848, 840)"/>
<path d=""  transform="translate(19277, 840)"/>
<path d=""  transform="translate(19942, 840)"/>
<path d=""  transform="translate(20202, 840)"/>
<path d=""  transform="translate(20582, 840)"/>
<path d=""  transform="translate(21089, 840)"/>
<path d=""  transform="translate(21349, 840)"/>
<path d=""  transform="translate(21982, 840)"/>
<path d=""  transform="translate(22816, 840)"/>
<path d=""  transform="translate(23323, 840)"/>
<path d=""  transform="translate(24029, 840)"/>
<path d=""  transform="translate(24448, 840)"/>
<path d=""  transform="translate(24708, 840)"/>
<path d=""  transform="translate(25681, 840)"/>
<path d=""  transform="translate(26314, 840)"/>
<path d=""  transform="translate(26801, 840)"/>
<path d=""  transform="translate(27061, 840)"/>
<path d=""  transform="translate(27694, 840)"/>
<path d=""  transform="translate(28354, 840)"/>
<path d=""  transform="translate(28614, 840)"/>
<path d=""  transform="translate(28999, 840)"/>
<path d=""  transform="translate(29623, 840)"/>
<path d=""  transform="translate(29883, 840)"/>
<path d=""  transform="translate(30930, 840)"/>
<path d=""  transform="translate(31880, 840)"/>
<path d=""  transform="translate(32140, 840)"/>
<path d=""  transform="translate(32669, 840)"/>
<path d=""  transform="translate(33054, 840)"/>
<path d=""  transform="translate(33481, 840)"/>
<path d=""  transform="translate(33481, 840)"/>
<path d=""  transform="translate(33741, 840)"/>
<path d=""  transform="translate(33741, 840)"/>
<path d=""  transform="translate(34313, 840)"/>
<path d=""  transform="translate(34573, 840)"/>
<path d=""  transform="translate(35206, 840)"/>
<path d=""  transform="translate(35839, 840)"/>
<path d=""  transform="translate(36268, 840)"/>
<path d=""  transform="translate(36928, 840)"/>
<path d=""  transform="translate(37593, 840)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 37621 2130" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 840)"/>
<path d=""  transform="translate(633, 840)"/>
<path d=""  transform="translate(1293, 840)"/>
<path d=""  transform="translate(1712, 840)"/>
<path d=""  transform="translate(1972, 840)"/>
<path d=""  transform="translate(2605, 840)"/>
<path d=""  transform="translate(3024, 840)"/>
<path d=""  transform="translate(3656, 840)"/>
<path d=""  transform="translate(4289, 840)"/>
<path d=""  transform="translate(4549, 840)"/>
<path d=""  transform="translate(4929, 840)"/>
<path d=""  transform="translate(5923, 840)"/>
<path d=""  transform="translate(6183, 840)"/>
<path d=""  transform="translate(6816, 840)"/>
<path d=""  transform="translate(7235, 840)"/>
<path d=""  transform="translate(7742, 840)"/>
<path d=""  transform="translate(8161, 840)"/>
<path d=""  transform="translate(8681, 840)"/>
<path d=""  transform="translate(8941, 840)"/>
<path d=""  transform="translate(8941, 840)"/>
<path d=""  transform="translate(9201, 840)"/>
<path d=""  transform="translate(9201, 840)"/>
<path d=""  transform="translate(9581, 840)"/>
<path d=""  transform="translate(10088, 840)"/>
<path d=""  transform="translate(10348, 840)"/>
<path d=""  transform="translate(10981, 840)"/>
<path d=""  transform="translate(11400, 840)"/>
<path d=""  transform="translate(11907, 840)"/>
<path d=""  transform="translate(12673, 840)"/>
<path d=""  transform="translate(13306, 840)"/>
<path d=""  transform="translate(13566, 840)"/>
<path d=""  transform="translate(14243, 840)"/>
<path d=""  transform="translate(14750, 840)"/>
<path d=""  transform="translate(15456, 840)"/>
<path d=""  transform="translate(15716, 840)"/>
<path d=""  transform="translate(16145, 840)"/>
<path d=""  transform="translate(16572, 840)"/>
<path d=""  transform="translate(16832, 840)"/>
<path d=""  transform="translate(17465, 840)"/>
<path d=""  transform="translate(18171, 840)"/>
<path d=""  transform="translate(18848, 840)"/>
<path d=""  transform="translate(19277, 840)"/>
<path d=""  transform="translate(19942, 840)"/>
<path d=""  transform="translate(20202, 840)"/>
<path d=""  transform="translate(20582, 840)"/>
<path d=""  transform="translate(21089, 840)"/>
<path d=""  transform="translate(21349, 840)"/>
<path d=""  transform="translate(21982, 840)"/>
<path d=""  transform="translate(22816, 840)"/>
<path d=""  transform="translate(23323, 840)"/>
<path d=""  transform="translate(24029, 840)"/>
<path d=""  transform="translate(24448, 840)"/>
<path d=""  transform="translate(24708, 840)"/>
<path d=""  transform="translate(25681, 840)"/>
<path d=""  transform="translate(26314, 840)"/>
<path d=""  transform="translate(26801, 840)"/>
<path d=""  transform="translate(27061, 840)"/>
<path d=""  transform="translate(27694, 840)"/>
<path d=""  transform="translate(28354, 840)"/>
<path d=""  transform="translate(28614, 840)"/>
<path d=""  transform="translate(28999, 840)"/>
<path d=""  transform="translate(29623, 840)"/>
<path d=""  transform="translate(29883, 840)"/>
<path d=""  transform="translate(30930, 840)"/>
<path d=""  transform="translate(31880, 840)"/>
<path d=""  transform="translate(32140, 840)"/>
<path d=""  transform="translate(32669, 840)"/>
<path d=""  transform="translate(33054, 840)"/>
<path d=""  transform="translate(33481, 840)"/>
<path d=""  transform="translate(33481, 840)"/>
<path d=""  transform="translate(33741, 840)"/>
<path d=""  transform="translate(33741, 840)"/>
<path d=""  transform="translate(34341, 840)"/>
<path d=""  transform="translate(34601, 840)"/>
<path d=""  transform="translate(35234, 840)"/>
<path d=""  transform="translate(35867, 840)"/>
<path d=""  transform="translate(36296, 840)"/>
<path d=""  transform="translate(36956, 840)"/>
<path d=""  transform="translate(37621, 840)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐫞𐫀𐫗𐫇𐫗‬ ‫𐫖𐫓𐫇𐫀𐫀 10‬ ‫𐫐𐫓 𐫍𐫅 𐫀𐫏𐫓𐫆 𐫁𐫡𐫁𐫡 𐫞𐫖 𐫁𐫏𐫤 𐫅𐫏𐫗𐫀 𐫍𐫀𐫡𐫀 𐫇𐫓𐫀 𐫖𐫤𐫃𐫗𐫏𐫗𐫀 𐫃𐫇‬ ‫ 𐫞𐫎𐫏𐫤𐫀</span></li>


<pre>Expected: u10AC0=74+633|u10AE4=73+677|u10ACF=72+507|u10ACE.fina=71+530|u10ADE.init=70+834|space=69+260|space=68+0|space=67+260|space=66+0|u10AC7.fina=65+429|u10AC3.init=64+427|space=63+260|u10AC0.fina=62+633|u10AD7.init=61+380|u10ACF.fina=60+507|u10AD7.init=59+380|u10AC3=58+529|u10AE4.fina=57+632|u10AD6.init=56+665|space=55+260|u10AC0.fina=54+633|u10AD3.init=53+660|u10AC7=52+451|space=51+260|u10AC0=50+633|u10AE1.fina=49+385|u10AC0.medi=48+633|u10ACD.init=47+624|space=46+260|u10AC0.fina=45+633|u10AD7.init=44+380|u10ACF=43+507|u10AC5=42+419|space=41+260|u10AE4=40+677|u10ACF.fina=39+507|u10AC1.init=38+706|space=37+260|u10AD6.fina=36+994|u10ADE.init=35+834|space=34+260|u10AE1.fina=33+385|u10AC1.init=32+706|u10AE1.fina=31+385|u10AC1.init=30+706|space=29+260|u10AC6=28+950|u10AD3=27+792|u10ACF.fina=26+507|u10AC0.init=25+633|space=24+260|u10AC5.fina=23+385|u10ACD.init=22+624|space=21+260|u10AD3=20+792|u10AD0=19+1047|space=18+0|space=17+260|space=16+0|.notdef=15+600|.notdef=14+600|space=13+260|u10AC0.fina=12+633|u10AC0.init=11+633|u10AC7.fina=10+429|u10AD3.medi=9+660|u10AD6.init=8+665|space=7+0|space=6+260|space=5+0|u10AD7=4+380|u10AC7.fina=3+429|u10AD7.init=2+380|u10AC0.fina=1+633|u10ADE.init=0+834</pre>



<pre>Got     : u10AC0=74+633|u10AE4=73+677|u10ACF=72+507|u10ACE.fina=71+530|u10ADE.init=70+834|space=69+260|space=68+0|space=67+260|space=66+0|u10AC7.fina=65+429|u10AC3.init=64+427|space=63+260|u10AC0.fina=62+633|u10AD7.init=61+380|u10ACF.fina=60+507|u10AD7.init=59+380|u10AC3=58+529|u10AE4.fina=57+632|u10AD6.init=56+665|space=55+260|u10AC0.fina=54+633|u10AD3.init=53+660|u10AC7=52+451|space=51+260|u10AC0=50+633|u10AE1.fina=49+385|u10AC0.medi=48+633|u10ACD.init=47+624|space=46+260|u10AC0.fina=45+633|u10AD7.init=44+380|u10ACF=43+507|u10AC5=42+419|space=41+260|u10AE4=40+677|u10ACF.fina=39+507|u10AC1.init=38+706|space=37+260|u10AD6.fina=36+994|u10ADE.init=35+834|space=34+260|u10AE1.fina=33+385|u10AC1.init=32+706|u10AE1.fina=31+385|u10AC1.init=30+706|space=29+260|u10AC6=28+950|u10AD3=27+792|u10ACF.fina=26+507|u10AC0.init=25+633|space=24+260|u10AC5.fina=23+385|u10ACD.init=22+624|space=21+260|u10AD3=20+792|u10AD0=19+1047|space=18+0|space=17+260|space=16+0|zero=15+572|one=14+572|space=13+260|u10AC0.fina=12+633|u10AC0.init=11+633|u10AC7.fina=10+429|u10AD3.medi=9+660|u10AD6.init=8+665|space=7+0|space=6+260|space=5+0|u10AD7=4+380|u10AC7.fina=3+429|u10AD7.init=2+380|u10AC0.fina=1+633|u10ADE.init=0+834</pre>



<pre>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             ^^ ^^^^^^^^^^^^^^ ^^^^^^^^^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 36071 2130" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 840)"/>
<path d=""  transform="translate(633, 840)"/>
<path d=""  transform="translate(1310, 840)"/>
<path d=""  transform="translate(1817, 840)"/>
<path d=""  transform="translate(2347, 840)"/>
<path d=""  transform="translate(3181, 840)"/>
<path d=""  transform="translate(3441, 840)"/>
<path d=""  transform="translate(3441, 840)"/>
<path d=""  transform="translate(3701, 840)"/>
<path d=""  transform="translate(3701, 840)"/>
<path d=""  transform="translate(4130, 840)"/>
<path d=""  transform="translate(4557, 840)"/>
<path d=""  transform="translate(4817, 840)"/>
<path d=""  transform="translate(5450, 840)"/>
<path d=""  transform="translate(5830, 840)"/>
<path d=""  transform="translate(6337, 840)"/>
<path d=""  transform="translate(6717, 840)"/>
<path d=""  transform="translate(7246, 840)"/>
<path d=""  transform="translate(7878, 840)"/>
<path d=""  transform="translate(8543, 840)"/>
<path d=""  transform="translate(8803, 840)"/>
<path d=""  transform="translate(9436, 840)"/>
<path d=""  transform="translate(10096, 840)"/>
<path d=""  transform="translate(10547, 840)"/>
<path d=""  transform="translate(10807, 840)"/>
<path d=""  transform="translate(11440, 840)"/>
<path d=""  transform="translate(11825, 840)"/>
<path d=""  transform="translate(12458, 840)"/>
<path d=""  transform="translate(13082, 840)"/>
<path d=""  transform="translate(13342, 840)"/>
<path d=""  transform="translate(13975, 840)"/>
<path d=""  transform="translate(14355, 840)"/>
<path d=""  transform="translate(14862, 840)"/>
<path d=""  transform="translate(15281, 840)"/>
<path d=""  transform="translate(15541, 840)"/>
<path d=""  transform="translate(16218, 840)"/>
<path d=""  transform="translate(16725, 840)"/>
<path d=""  transform="translate(17431, 840)"/>
<path d=""  transform="translate(17691, 840)"/>
<path d=""  transform="translate(18685, 840)"/>
<path d=""  transform="translate(19519, 840)"/>
<path d=""  transform="translate(19779, 840)"/>
<path d=""  transform="translate(20164, 840)"/>
<path d=""  transform="translate(20870, 840)"/>
<path d=""  transform="translate(21255, 840)"/>
<path d=""  transform="translate(21961, 840)"/>
<path d=""  transform="translate(22221, 840)"/>
<path d=""  transform="translate(23171, 840)"/>
<path d=""  transform="translate(23963, 840)"/>
<path d=""  transform="translate(24470, 840)"/>
<path d=""  transform="translate(25103, 840)"/>
<path d=""  transform="translate(25363, 840)"/>
<path d=""  transform="translate(25748, 840)"/>
<path d=""  transform="translate(26372, 840)"/>
<path d=""  transform="translate(26632, 840)"/>
<path d=""  transform="translate(27424, 840)"/>
<path d=""  transform="translate(28471, 840)"/>
<path d=""  transform="translate(28471, 840)"/>
<path d=""  transform="translate(28731, 840)"/>
<path d=""  transform="translate(28731, 840)"/>
<path d=""  transform="translate(29303, 840)"/>
<path d=""  transform="translate(29875, 840)"/>
<path d=""  transform="translate(30135, 840)"/>
<path d=""  transform="translate(30768, 840)"/>
<path d=""  transform="translate(31401, 840)"/>
<path d=""  transform="translate(31830, 840)"/>
<path d=""  transform="translate(32490, 840)"/>
<path d=""  transform="translate(33155, 840)"/>
<path d=""  transform="translate(33155, 840)"/>
<path d=""  transform="translate(33415, 840)"/>
<path d=""  transform="translate(33415, 840)"/>
<path d=""  transform="translate(33795, 840)"/>
<path d=""  transform="translate(34224, 840)"/>
<path d=""  transform="translate(34604, 840)"/>
<path d=""  transform="translate(35237, 840)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 36127 2130" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 840)"/>
<path d=""  transform="translate(633, 840)"/>
<path d=""  transform="translate(1310, 840)"/>
<path d=""  transform="translate(1817, 840)"/>
<path d=""  transform="translate(2347, 840)"/>
<path d=""  transform="translate(3181, 840)"/>
<path d=""  transform="translate(3441, 840)"/>
<path d=""  transform="translate(3441, 840)"/>
<path d=""  transform="translate(3701, 840)"/>
<path d=""  transform="translate(3701, 840)"/>
<path d=""  transform="translate(4130, 840)"/>
<path d=""  transform="translate(4557, 840)"/>
<path d=""  transform="translate(4817, 840)"/>
<path d=""  transform="translate(5450, 840)"/>
<path d=""  transform="translate(5830, 840)"/>
<path d=""  transform="translate(6337, 840)"/>
<path d=""  transform="translate(6717, 840)"/>
<path d=""  transform="translate(7246, 840)"/>
<path d=""  transform="translate(7878, 840)"/>
<path d=""  transform="translate(8543, 840)"/>
<path d=""  transform="translate(8803, 840)"/>
<path d=""  transform="translate(9436, 840)"/>
<path d=""  transform="translate(10096, 840)"/>
<path d=""  transform="translate(10547, 840)"/>
<path d=""  transform="translate(10807, 840)"/>
<path d=""  transform="translate(11440, 840)"/>
<path d=""  transform="translate(11825, 840)"/>
<path d=""  transform="translate(12458, 840)"/>
<path d=""  transform="translate(13082, 840)"/>
<path d=""  transform="translate(13342, 840)"/>
<path d=""  transform="translate(13975, 840)"/>
<path d=""  transform="translate(14355, 840)"/>
<path d=""  transform="translate(14862, 840)"/>
<path d=""  transform="translate(15281, 840)"/>
<path d=""  transform="translate(15541, 840)"/>
<path d=""  transform="translate(16218, 840)"/>
<path d=""  transform="translate(16725, 840)"/>
<path d=""  transform="translate(17431, 840)"/>
<path d=""  transform="translate(17691, 840)"/>
<path d=""  transform="translate(18685, 840)"/>
<path d=""  transform="translate(19519, 840)"/>
<path d=""  transform="translate(19779, 840)"/>
<path d=""  transform="translate(20164, 840)"/>
<path d=""  transform="translate(20870, 840)"/>
<path d=""  transform="translate(21255, 840)"/>
<path d=""  transform="translate(21961, 840)"/>
<path d=""  transform="translate(22221, 840)"/>
<path d=""  transform="translate(23171, 840)"/>
<path d=""  transform="translate(23963, 840)"/>
<path d=""  transform="translate(24470, 840)"/>
<path d=""  transform="translate(25103, 840)"/>
<path d=""  transform="translate(25363, 840)"/>
<path d=""  transform="translate(25748, 840)"/>
<path d=""  transform="translate(26372, 840)"/>
<path d=""  transform="translate(26632, 840)"/>
<path d=""  transform="translate(27424, 840)"/>
<path d=""  transform="translate(28471, 840)"/>
<path d=""  transform="translate(28471, 840)"/>
<path d=""  transform="translate(28731, 840)"/>
<path d=""  transform="translate(28731, 840)"/>
<path d=""  transform="translate(29331, 840)"/>
<path d=""  transform="translate(29931, 840)"/>
<path d=""  transform="translate(30191, 840)"/>
<path d=""  transform="translate(30824, 840)"/>
<path d=""  transform="translate(31457, 840)"/>
<path d=""  transform="translate(31886, 840)"/>
<path d=""  transform="translate(32546, 840)"/>
<path d=""  transform="translate(33211, 840)"/>
<path d=""  transform="translate(33211, 840)"/>
<path d=""  transform="translate(33471, 840)"/>
<path d=""  transform="translate(33471, 840)"/>
<path d=""  transform="translate(33851, 840)"/>
<path d=""  transform="translate(34280, 840)"/>
<path d=""  transform="translate(34660, 840)"/>
<path d=""  transform="translate(35293, 840)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐫅𐫆𐫞𐫇𐫤𐫀 𐫇𐫃𐫁𐫇𐫏𐫤𐫀 𐫇𐫐𐫓 𐫃𐫇𐫗𐫍𐫀 𐫅𐫡𐫞𐫇𐫓𐫆‬ ‫𐫖𐫓𐫇𐫀𐫀 11‬ ‫𐫐𐫓 𐫍𐫅 𐫅𐫛𐫀𐫢 𐫖𐫤𐫆𐫖𐫀 𐫓𐫢𐫖𐫎𐫤𐫀 𐫅𐫞𐫀𐫗𐫇𐫗</span></li>


<pre>Expected: u10AD7=74+380|u10AC7.fina=73+429|u10AD7.init=72+380|u10AC0.fina=71+633|u10ADE.init=70+834|u10AC5=69+419|space=68+260|u10AC0=67+633|u10AE4=66+677|u10ACE.fina=65+530|u10AD6.init=64+665|u10AE2=63+973|u10AD3=62+792|space=61+260|u10AC0.fina=60+633|u10AD6.init=59+665|u10AC6=58+950|u10AE4.fina=57+632|u10AD6.init=56+665|space=55+260|u10AE2=54+973|u10AC0.fina=53+633|u10ADB.init=52+487|u10AC5=51+419|space=50+260|u10AC5.fina=49+385|u10ACD.init=48+624|space=47+260|u10AD3=46+792|u10AD0=45+1047|space=44+0|space=43+260|space=42+0|.notdef=41+600|.notdef=40+600|space=39+260|u10AC0.fina=38+633|u10AC0.init=37+633|u10AC7.fina=36+429|u10AD3.medi=35+660|u10AD6.init=34+665|space=33+0|space=32+260|space=31+0|u10AC6=30+950|u10AD3=29+792|u10AC7.fina=28+429|u10ADE.init=27+834|u10AE1=26+419|u10AC5=25+419|space=24+260|u10AC0.fina=23+633|u10ACD.init=22+624|u10AD7=21+380|u10AC7.fina=20+429|u10AC3.init=19+427|space=18+260|u10AD3=17+792|u10AD0=16+1047|u10AC7=15+451|space=14+260|u10AC0=13+633|u10AE4=12+677|u10ACF=11+507|u10AC7.fina=10+429|u10AC1.medi=9+706|u10AC3.init=8+427|u10AC7=7+451|space=6+260|u10AC0=5+633|u10AE4=4+677|u10AC7.fina=3+429|u10ADE.init=2+834|u10AC6=1+950|u10AC5=0+419</pre>



<pre>Got     : u10AD7=74+380|u10AC7.fina=73+429|u10AD7.init=72+380|u10AC0.fina=71+633|u10ADE.init=70+834|u10AC5=69+419|space=68+260|u10AC0=67+633|u10AE4=66+677|u10ACE.fina=65+530|u10AD6.init=64+665|u10AE2=63+973|u10AD3=62+792|space=61+260|u10AC0.fina=60+633|u10AD6.init=59+665|u10AC6=58+950|u10AE4.fina=57+632|u10AD6.init=56+665|space=55+260|u10AE2=54+973|u10AC0.fina=53+633|u10ADB.init=52+487|u10AC5=51+419|space=50+260|u10AC5.fina=49+385|u10ACD.init=48+624|space=47+260|u10AD3=46+792|u10AD0=45+1047|space=44+0|space=43+260|space=42+0|one=41+572|one=40+572|space=39+260|u10AC0.fina=38+633|u10AC0.init=37+633|u10AC7.fina=36+429|u10AD3.medi=35+660|u10AD6.init=34+665|space=33+0|space=32+260|space=31+0|u10AC6=30+950|u10AD3=29+792|u10AC7.fina=28+429|u10ADE.init=27+834|u10AE1=26+419|u10AC5=25+419|space=24+260|u10AC0.fina=23+633|u10ACD.init=22+624|u10AD7=21+380|u10AC7.fina=20+429|u10AC3.init=19+427|space=18+260|u10AD3=17+792|u10AD0=16+1047|u10AC7=15+451|space=14+260|u10AC0=13+633|u10AE4=12+677|u10ACF=11+507|u10AC7.fina=10+429|u10AC1.medi=9+706|u10AC3.init=8+427|u10AC7=7+451|space=6+260|u10AC0=5+633|u10AE4=4+677|u10AC7.fina=3+429|u10ADE.init=2+834|u10AC6=1+950|u10AC5=0+419</pre>



<pre>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   ++ ^^^^^^^^^^^^^^ ^^^^^^^^^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 39932 2130" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 840)"/>
<path d=""  transform="translate(380, 840)"/>
<path d=""  transform="translate(809, 840)"/>
<path d=""  transform="translate(1189, 840)"/>
<path d=""  transform="translate(1822, 840)"/>
<path d=""  transform="translate(2656, 840)"/>
<path d=""  transform="translate(3075, 840)"/>
<path d=""  transform="translate(3335, 840)"/>
<path d=""  transform="translate(3968, 840)"/>
<path d=""  transform="translate(4645, 840)"/>
<path d=""  transform="translate(5175, 840)"/>
<path d=""  transform="translate(5840, 840)"/>
<path d=""  transform="translate(6813, 840)"/>
<path d=""  transform="translate(7605, 840)"/>
<path d=""  transform="translate(7865, 840)"/>
<path d=""  transform="translate(8498, 840)"/>
<path d=""  transform="translate(9163, 840)"/>
<path d=""  transform="translate(10113, 840)"/>
<path d=""  transform="translate(10745, 840)"/>
<path d=""  transform="translate(11410, 840)"/>
<path d=""  transform="translate(11670, 840)"/>
<path d=""  transform="translate(12643, 840)"/>
<path d=""  transform="translate(13276, 840)"/>
<path d=""  transform="translate(13763, 840)"/>
<path d=""  transform="translate(14182, 840)"/>
<path d=""  transform="translate(14442, 840)"/>
<path d=""  transform="translate(14827, 840)"/>
<path d=""  transform="translate(15451, 840)"/>
<path d=""  transform="translate(15711, 840)"/>
<path d=""  transform="translate(16503, 840)"/>
<path d=""  transform="translate(17550, 840)"/>
<path d=""  transform="translate(17550, 840)"/>
<path d=""  transform="translate(17810, 840)"/>
<path d=""  transform="translate(17810, 840)"/>
<path d=""  transform="translate(18382, 840)"/>
<path d=""  transform="translate(18954, 840)"/>
<path d=""  transform="translate(19214, 840)"/>
<path d=""  transform="translate(19847, 840)"/>
<path d=""  transform="translate(20480, 840)"/>
<path d=""  transform="translate(20909, 840)"/>
<path d=""  transform="translate(21569, 840)"/>
<path d=""  transform="translate(22234, 840)"/>
<path d=""  transform="translate(22234, 840)"/>
<path d=""  transform="translate(22494, 840)"/>
<path d=""  transform="translate(22494, 840)"/>
<path d=""  transform="translate(23444, 840)"/>
<path d=""  transform="translate(24236, 840)"/>
<path d=""  transform="translate(24665, 840)"/>
<path d=""  transform="translate(25499, 840)"/>
<path d=""  transform="translate(25918, 840)"/>
<path d=""  transform="translate(26337, 840)"/>
<path d=""  transform="translate(26597, 840)"/>
<path d=""  transform="translate(27230, 840)"/>
<path d=""  transform="translate(27854, 840)"/>
<path d=""  transform="translate(28234, 840)"/>
<path d=""  transform="translate(28663, 840)"/>
<path d=""  transform="translate(29090, 840)"/>
<path d=""  transform="translate(29350, 840)"/>
<path d=""  transform="translate(30142, 840)"/>
<path d=""  transform="translate(31189, 840)"/>
<path d=""  transform="translate(31640, 840)"/>
<path d=""  transform="translate(31900, 840)"/>
<path d=""  transform="translate(32533, 840)"/>
<path d=""  transform="translate(33210, 840)"/>
<path d=""  transform="translate(33717, 840)"/>
<path d=""  transform="translate(34146, 840)"/>
<path d=""  transform="translate(34852, 840)"/>
<path d=""  transform="translate(35279, 840)"/>
<path d=""  transform="translate(35730, 840)"/>
<path d=""  transform="translate(35990, 840)"/>
<path d=""  transform="translate(36623, 840)"/>
<path d=""  transform="translate(37300, 840)"/>
<path d=""  transform="translate(37729, 840)"/>
<path d=""  transform="translate(38563, 840)"/>
<path d=""  transform="translate(39513, 840)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 39988 2130" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 840)"/>
<path d=""  transform="translate(380, 840)"/>
<path d=""  transform="translate(809, 840)"/>
<path d=""  transform="translate(1189, 840)"/>
<path d=""  transform="translate(1822, 840)"/>
<path d=""  transform="translate(2656, 840)"/>
<path d=""  transform="translate(3075, 840)"/>
<path d=""  transform="translate(3335, 840)"/>
<path d=""  transform="translate(3968, 840)"/>
<path d=""  transform="translate(4645, 840)"/>
<path d=""  transform="translate(5175, 840)"/>
<path d=""  transform="translate(5840, 840)"/>
<path d=""  transform="translate(6813, 840)"/>
<path d=""  transform="translate(7605, 840)"/>
<path d=""  transform="translate(7865, 840)"/>
<path d=""  transform="translate(8498, 840)"/>
<path d=""  transform="translate(9163, 840)"/>
<path d=""  transform="translate(10113, 840)"/>
<path d=""  transform="translate(10745, 840)"/>
<path d=""  transform="translate(11410, 840)"/>
<path d=""  transform="translate(11670, 840)"/>
<path d=""  transform="translate(12643, 840)"/>
<path d=""  transform="translate(13276, 840)"/>
<path d=""  transform="translate(13763, 840)"/>
<path d=""  transform="translate(14182, 840)"/>
<path d=""  transform="translate(14442, 840)"/>
<path d=""  transform="translate(14827, 840)"/>
<path d=""  transform="translate(15451, 840)"/>
<path d=""  transform="translate(15711, 840)"/>
<path d=""  transform="translate(16503, 840)"/>
<path d=""  transform="translate(17550, 840)"/>
<path d=""  transform="translate(17550, 840)"/>
<path d=""  transform="translate(17810, 840)"/>
<path d=""  transform="translate(17810, 840)"/>
<path d=""  transform="translate(18410, 840)"/>
<path d=""  transform="translate(19010, 840)"/>
<path d=""  transform="translate(19270, 840)"/>
<path d=""  transform="translate(19903, 840)"/>
<path d=""  transform="translate(20536, 840)"/>
<path d=""  transform="translate(20965, 840)"/>
<path d=""  transform="translate(21625, 840)"/>
<path d=""  transform="translate(22290, 840)"/>
<path d=""  transform="translate(22290, 840)"/>
<path d=""  transform="translate(22550, 840)"/>
<path d=""  transform="translate(22550, 840)"/>
<path d=""  transform="translate(23500, 840)"/>
<path d=""  transform="translate(24292, 840)"/>
<path d=""  transform="translate(24721, 840)"/>
<path d=""  transform="translate(25555, 840)"/>
<path d=""  transform="translate(25974, 840)"/>
<path d=""  transform="translate(26393, 840)"/>
<path d=""  transform="translate(26653, 840)"/>
<path d=""  transform="translate(27286, 840)"/>
<path d=""  transform="translate(27910, 840)"/>
<path d=""  transform="translate(28290, 840)"/>
<path d=""  transform="translate(28719, 840)"/>
<path d=""  transform="translate(29146, 840)"/>
<path d=""  transform="translate(29406, 840)"/>
<path d=""  transform="translate(30198, 840)"/>
<path d=""  transform="translate(31245, 840)"/>
<path d=""  transform="translate(31696, 840)"/>
<path d=""  transform="translate(31956, 840)"/>
<path d=""  transform="translate(32589, 840)"/>
<path d=""  transform="translate(33266, 840)"/>
<path d=""  transform="translate(33773, 840)"/>
<path d=""  transform="translate(34202, 840)"/>
<path d=""  transform="translate(34908, 840)"/>
<path d=""  transform="translate(35335, 840)"/>
<path d=""  transform="translate(35786, 840)"/>
<path d=""  transform="translate(36046, 840)"/>
<path d=""  transform="translate(36679, 840)"/>
<path d=""  transform="translate(37356, 840)"/>
<path d=""  transform="translate(37785, 840)"/>
<path d=""  transform="translate(38619, 840)"/>
<path d=""  transform="translate(39569, 840)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐫅𐫞𐫇𐫖𐫤𐫀 𐫅𐫆𐫅𐫍𐫀 𐫖𐫗𐫅‬ ‫𐫏‬ ‫ 𐫖𐫓𐫇𐫀𐫀 12‬ ‫ 𐫃𐫡𐫃 𐫓𐫀 𐫙𐫇𐫡𐫏 𐫃𐫇 𐫍𐫏𐫀 𐫅𐫏𐫓𐫗𐫏𐫀 𐫅𐫍𐫅 𐫛𐫡𐫘𐫇𐫛𐫀 𐫏𐫗 𐫁𐫏𐫤𐫀</span></li>


<pre>Expected: u10AC0=79+633|u10AE4=78+677|u10ACF.fina=77+507|u10AC1.init=76+706|space=75+260|u10AD7=74+380|u10ACF=73+507|space=72+260|u10AC0.fina=71+633|u10ADB.init=70+487|u10AC7.fina=69+429|u10AD8.init=68+766|u10AE1.fina=67+385|u10ADB.init=66+487|space=65+260|u10AC5.fina=64+385|u10ACD.init=63+624|u10AC5=62+419|space=61+260|u10AC0=60+633|u10ACF.fina=59+507|u10AD7.init=58+380|u10AD3=57+792|u10ACF=56+507|u10AC5=55+419|space=54+260|u10AC0=53+633|u10ACF.fina=52+507|u10ACD.init=51+624|space=50+260|u10AC7.fina=49+429|u10AC3.init=48+427|space=47+260|u10ACF=46+507|u10AE1=45+419|u10AC7.fina=44+429|u10AD9.init=43+607|space=42+260|u10AC0.fina=41+633|u10AD3.init=40+660|space=39+260|u10AC3=38+529|u10AE1.fina=37+385|u10AC3.init=36+427|space=35+260|space=34+0|space=33+260|space=32+0|.notdef=31+600|.notdef=30+600|space=29+260|u10AC0.fina=28+633|u10AC0.init=27+633|u10AC7.fina=26+429|u10AD3.medi=25+660|u10AD6.init=24+665|space=23+260|space=22+0|space=21+260|space=20+0|u10ACF=19+507|space=18+0|space=17+260|space=16+0|u10AC5.fina=15+385|u10AD7.init=14+380|u10AD6=13+994|space=12+260|u10AC0.fina=11+633|u10ACD.init=10+624|u10AC5=9+419|u10AC6=8+950|u10AC5=7+419|space=6+260|u10AC0=5+633|u10AE4.fina=4+632|u10AD6.init=3+665|u10AC7.fina=2+429|u10ADE.init=1+834|u10AC5=0+419</pre>



<pre>Got     : u10AC0=79+633|u10AE4=78+677|u10ACF.fina=77+507|u10AC1.init=76+706|space=75+260|u10AD7=74+380|u10ACF=73+507|space=72+260|u10AC0.fina=71+633|u10ADB.init=70+487|u10AC7.fina=69+429|u10AD8.init=68+766|u10AE1.fina=67+385|u10ADB.init=66+487|space=65+260|u10AC5.fina=64+385|u10ACD.init=63+624|u10AC5=62+419|space=61+260|u10AC0=60+633|u10ACF.fina=59+507|u10AD7.init=58+380|u10AD3=57+792|u10ACF=56+507|u10AC5=55+419|space=54+260|u10AC0=53+633|u10ACF.fina=52+507|u10ACD.init=51+624|space=50+260|u10AC7.fina=49+429|u10AC3.init=48+427|space=47+260|u10ACF=46+507|u10AE1=45+419|u10AC7.fina=44+429|u10AD9.init=43+607|space=42+260|u10AC0.fina=41+633|u10AD3.init=40+660|space=39+260|u10AC3=38+529|u10AE1.fina=37+385|u10AC3.init=36+427|space=35+260|space=34+0|space=33+260|space=32+0|two=31+572|one=30+572|space=29+260|u10AC0.fina=28+633|u10AC0.init=27+633|u10AC7.fina=26+429|u10AD3.medi=25+660|u10AD6.init=24+665|space=23+260|space=22+0|space=21+260|space=20+0|u10ACF=19+507|space=18+0|space=17+260|space=16+0|u10AC5.fina=15+385|u10AD7.init=14+380|u10AD6=13+994|space=12+260|u10AC0.fina=11+633|u10ACD.init=10+624|u10AC5=9+419|u10AC6=8+950|u10AC5=7+419|space=6+260|u10AC0=5+633|u10AE4.fina=4+632|u10AD6.init=3+665|u10AC7.fina=2+429|u10ADE.init=1+834|u10AC5=0+419</pre>



<pre>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       ^^ ^^^^^^^^^^^^^^ ^^^^^^^^^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 35986 2130" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 840)"/>
<path d=""  transform="translate(633, 840)"/>
<path d=""  transform="translate(1310, 840)"/>
<path d=""  transform="translate(1817, 840)"/>
<path d=""  transform="translate(2523, 840)"/>
<path d=""  transform="translate(2783, 840)"/>
<path d=""  transform="translate(3163, 840)"/>
<path d=""  transform="translate(3670, 840)"/>
<path d=""  transform="translate(3930, 840)"/>
<path d=""  transform="translate(4563, 840)"/>
<path d=""  transform="translate(5050, 840)"/>
<path d=""  transform="translate(5479, 840)"/>
<path d=""  transform="translate(6245, 840)"/>
<path d=""  transform="translate(6630, 840)"/>
<path d=""  transform="translate(7117, 840)"/>
<path d=""  transform="translate(7377, 840)"/>
<path d=""  transform="translate(7762, 840)"/>
<path d=""  transform="translate(8386, 840)"/>
<path d=""  transform="translate(8805, 840)"/>
<path d=""  transform="translate(9065, 840)"/>
<path d=""  transform="translate(9698, 840)"/>
<path d=""  transform="translate(10205, 840)"/>
<path d=""  transform="translate(10585, 840)"/>
<path d=""  transform="translate(11377, 840)"/>
<path d=""  transform="translate(11884, 840)"/>
<path d=""  transform="translate(12303, 840)"/>
<path d=""  transform="translate(12563, 840)"/>
<path d=""  transform="translate(13196, 840)"/>
<path d=""  transform="translate(13703, 840)"/>
<path d=""  transform="translate(14327, 840)"/>
<path d=""  transform="translate(14587, 840)"/>
<path d=""  transform="translate(15016, 840)"/>
<path d=""  transform="translate(15443, 840)"/>
<path d=""  transform="translate(15703, 840)"/>
<path d=""  transform="translate(16210, 840)"/>
<path d=""  transform="translate(16629, 840)"/>
<path d=""  transform="translate(17058, 840)"/>
<path d=""  transform="translate(17665, 840)"/>
<path d=""  transform="translate(17925, 840)"/>
<path d=""  transform="translate(18558, 840)"/>
<path d=""  transform="translate(19218, 840)"/>
<path d=""  transform="translate(19478, 840)"/>
<path d=""  transform="translate(20007, 840)"/>
<path d=""  transform="translate(20392, 840)"/>
<path d=""  transform="translate(20819, 840)"/>
<path d=""  transform="translate(21079, 840)"/>
<path d=""  transform="translate(21079, 840)"/>
<path d=""  transform="translate(21339, 840)"/>
<path d=""  transform="translate(21339, 840)"/>
<path d=""  transform="translate(21911, 840)"/>
<path d=""  transform="translate(22483, 840)"/>
<path d=""  transform="translate(22743, 840)"/>
<path d=""  transform="translate(23376, 840)"/>
<path d=""  transform="translate(24009, 840)"/>
<path d=""  transform="translate(24438, 840)"/>
<path d=""  transform="translate(25098, 840)"/>
<path d=""  transform="translate(25763, 840)"/>
<path d=""  transform="translate(26023, 840)"/>
<path d=""  transform="translate(26023, 840)"/>
<path d=""  transform="translate(26283, 840)"/>
<path d=""  transform="translate(26283, 840)"/>
<path d=""  transform="translate(26790, 840)"/>
<path d=""  transform="translate(26790, 840)"/>
<path d=""  transform="translate(27050, 840)"/>
<path d=""  transform="translate(27050, 840)"/>
<path d=""  transform="translate(27435, 840)"/>
<path d=""  transform="translate(27815, 840)"/>
<path d=""  transform="translate(28809, 840)"/>
<path d=""  transform="translate(29069, 840)"/>
<path d=""  transform="translate(29702, 840)"/>
<path d=""  transform="translate(30326, 840)"/>
<path d=""  transform="translate(30745, 840)"/>
<path d=""  transform="translate(31695, 840)"/>
<path d=""  transform="translate(32114, 840)"/>
<path d=""  transform="translate(32374, 840)"/>
<path d=""  transform="translate(33007, 840)"/>
<path d=""  transform="translate(33639, 840)"/>
<path d=""  transform="translate(34304, 840)"/>
<path d=""  transform="translate(34733, 840)"/>
<path d=""  transform="translate(35567, 840)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 36042 2130" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 840)"/>
<path d=""  transform="translate(633, 840)"/>
<path d=""  transform="translate(1310, 840)"/>
<path d=""  transform="translate(1817, 840)"/>
<path d=""  transform="translate(2523, 840)"/>
<path d=""  transform="translate(2783, 840)"/>
<path d=""  transform="translate(3163, 840)"/>
<path d=""  transform="translate(3670, 840)"/>
<path d=""  transform="translate(3930, 840)"/>
<path d=""  transform="translate(4563, 840)"/>
<path d=""  transform="translate(5050, 840)"/>
<path d=""  transform="translate(5479, 840)"/>
<path d=""  transform="translate(6245, 840)"/>
<path d=""  transform="translate(6630, 840)"/>
<path d=""  transform="translate(7117, 840)"/>
<path d=""  transform="translate(7377, 840)"/>
<path d=""  transform="translate(7762, 840)"/>
<path d=""  transform="translate(8386, 840)"/>
<path d=""  transform="translate(8805, 840)"/>
<path d=""  transform="translate(9065, 840)"/>
<path d=""  transform="translate(9698, 840)"/>
<path d=""  transform="translate(10205, 840)"/>
<path d=""  transform="translate(10585, 840)"/>
<path d=""  transform="translate(11377, 840)"/>
<path d=""  transform="translate(11884, 840)"/>
<path d=""  transform="translate(12303, 840)"/>
<path d=""  transform="translate(12563, 840)"/>
<path d=""  transform="translate(13196, 840)"/>
<path d=""  transform="translate(13703, 840)"/>
<path d=""  transform="translate(14327, 840)"/>
<path d=""  transform="translate(14587, 840)"/>
<path d=""  transform="translate(15016, 840)"/>
<path d=""  transform="translate(15443, 840)"/>
<path d=""  transform="translate(15703, 840)"/>
<path d=""  transform="translate(16210, 840)"/>
<path d=""  transform="translate(16629, 840)"/>
<path d=""  transform="translate(17058, 840)"/>
<path d=""  transform="translate(17665, 840)"/>
<path d=""  transform="translate(17925, 840)"/>
<path d=""  transform="translate(18558, 840)"/>
<path d=""  transform="translate(19218, 840)"/>
<path d=""  transform="translate(19478, 840)"/>
<path d=""  transform="translate(20007, 840)"/>
<path d=""  transform="translate(20392, 840)"/>
<path d=""  transform="translate(20819, 840)"/>
<path d=""  transform="translate(21079, 840)"/>
<path d=""  transform="translate(21079, 840)"/>
<path d=""  transform="translate(21339, 840)"/>
<path d=""  transform="translate(21339, 840)"/>
<path d=""  transform="translate(21939, 840)"/>
<path d=""  transform="translate(22539, 840)"/>
<path d=""  transform="translate(22799, 840)"/>
<path d=""  transform="translate(23432, 840)"/>
<path d=""  transform="translate(24065, 840)"/>
<path d=""  transform="translate(24494, 840)"/>
<path d=""  transform="translate(25154, 840)"/>
<path d=""  transform="translate(25819, 840)"/>
<path d=""  transform="translate(26079, 840)"/>
<path d=""  transform="translate(26079, 840)"/>
<path d=""  transform="translate(26339, 840)"/>
<path d=""  transform="translate(26339, 840)"/>
<path d=""  transform="translate(26846, 840)"/>
<path d=""  transform="translate(26846, 840)"/>
<path d=""  transform="translate(27106, 840)"/>
<path d=""  transform="translate(27106, 840)"/>
<path d=""  transform="translate(27491, 840)"/>
<path d=""  transform="translate(27871, 840)"/>
<path d=""  transform="translate(28865, 840)"/>
<path d=""  transform="translate(29125, 840)"/>
<path d=""  transform="translate(29758, 840)"/>
<path d=""  transform="translate(30382, 840)"/>
<path d=""  transform="translate(30801, 840)"/>
<path d=""  transform="translate(31751, 840)"/>
<path d=""  transform="translate(32170, 840)"/>
<path d=""  transform="translate(32430, 840)"/>
<path d=""  transform="translate(33063, 840)"/>
<path d=""  transform="translate(33695, 840)"/>
<path d=""  transform="translate(34360, 840)"/>
<path d=""  transform="translate(34789, 840)"/>
<path d=""  transform="translate(35623, 840)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐫁𐫏𐫅 𐫞𐫀𐫗𐫇𐫗 𐫅𐫡𐫞𐫇𐫁𐫓 𐫆𐫅𐫍𐫀 𐫝𐫛𐫍𐫏𐫤‬ ‫𐫀‬ ‫ 𐫖𐫓𐫇𐫀𐫀 13‬ ‫𐫐𐫓 𐫍𐫅 𐫀𐫏𐫤𐫓𐫆 𐫆𐫞𐫇𐫤𐫀 𐫓𐫍𐫀𐫡𐫇𐫤𐫀 𐫅𐫃𐫇𐫃𐫤𐫀</span></li>


<pre>Expected: u10AC0=77+633|u10AE4.fina=76+632|u10AC3.init=75+427|u10AC7.fina=74+429|u10AC3.init=73+427|u10AC5=72+419|space=71+260|u10AC0=70+633|u10AE4=69+677|u10AC7=68+451|u10AE1.fina=67+385|u10AC0.medi=66+633|u10ACD.init=65+624|u10AD3=64+792|space=63+260|u10AC0=62+633|u10AE4=61+677|u10AC7.fina=60+429|u10ADE.init=59+834|u10AC6=58+950|space=57+260|u10AC6=56+950|u10AD3=55+792|u10AE4=54+677|u10ACF.fina=53+507|u10AC0.init=52+633|space=51+260|u10AC5.fina=50+385|u10ACD.init=49+624|space=48+260|u10AD3=47+792|u10AD0=46+1047|space=45+0|space=44+260|space=43+0|.notdef=42+600|.notdef=41+600|space=40+260|u10AC0.fina=39+633|u10AC0.init=38+633|u10AC7.fina=37+429|u10AD3.medi=36+660|u10AD6.init=35+665|space=34+260|space=33+0|space=32+260|space=31+0|u10AC0=30+633|space=29+0|space=28+260|space=27+0|u10AE4=26+677|u10ACF.fina=25+507|u10ACD.init=24+624|u10ADB=23+922|u10ADD=22+901|space=21+260|u10AC0.fina=20+633|u10ACD.init=19+624|u10AC5=18+419|u10AC6=17+950|space=16+260|u10AD3.fina=15+792|u10AC1.init=14+706|u10AC7.fina=13+429|u10ADE.init=12+834|u10AE1=11+419|u10AC5=10+419|space=9+260|u10AD7=8+380|u10AC7.fina=7+429|u10AD7.init=6+380|u10AC0.fina=5+633|u10ADE.init=4+834|space=3+260|u10AC5=2+419|u10ACF.fina=1+507|u10AC1.init=0+706</pre>



<pre>Got     : u10AC0=77+633|u10AE4.fina=76+632|u10AC3.init=75+427|u10AC7.fina=74+429|u10AC3.init=73+427|u10AC5=72+419|space=71+260|u10AC0=70+633|u10AE4=69+677|u10AC7=68+451|u10AE1.fina=67+385|u10AC0.medi=66+633|u10ACD.init=65+624|u10AD3=64+792|space=63+260|u10AC0=62+633|u10AE4=61+677|u10AC7.fina=60+429|u10ADE.init=59+834|u10AC6=58+950|space=57+260|u10AC6=56+950|u10AD3=55+792|u10AE4=54+677|u10ACF.fina=53+507|u10AC0.init=52+633|space=51+260|u10AC5.fina=50+385|u10ACD.init=49+624|space=48+260|u10AD3=47+792|u10AD0=46+1047|space=45+0|space=44+260|space=43+0|three=42+572|one=41+572|space=40+260|u10AC0.fina=39+633|u10AC0.init=38+633|u10AC7.fina=37+429|u10AD3.medi=36+660|u10AD6.init=35+665|space=34+260|space=33+0|space=32+260|space=31+0|u10AC0=30+633|space=29+0|space=28+260|space=27+0|u10AE4=26+677|u10ACF.fina=25+507|u10ACD.init=24+624|u10ADB=23+922|u10ADD=22+901|space=21+260|u10AC0.fina=20+633|u10ACD.init=19+624|u10AC5=18+419|u10AC6=17+950|space=16+260|u10AD3.fina=15+792|u10AC1.init=14+706|u10AC7.fina=13+429|u10ADE.init=12+834|u10AE1=11+419|u10AC5=10+419|space=9+260|u10AD7=8+380|u10AC7.fina=7+429|u10AD7.init=6+380|u10AC0.fina=5+633|u10ADE.init=4+834|space=3+260|u10AC5=2+419|u10ACF.fina=1+507|u10AC1.init=0+706</pre>



<pre>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          ^^ ^^^^^^^^^^^^^^^^^^^^^^^^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 39673 2130" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 840)"/>
<path d=""  transform="translate(633, 840)"/>
<path d=""  transform="translate(1265, 840)"/>
<path d=""  transform="translate(1692, 840)"/>
<path d=""  transform="translate(2121, 840)"/>
<path d=""  transform="translate(2548, 840)"/>
<path d=""  transform="translate(2967, 840)"/>
<path d=""  transform="translate(3227, 840)"/>
<path d=""  transform="translate(3860, 840)"/>
<path d=""  transform="translate(4537, 840)"/>
<path d=""  transform="translate(4988, 840)"/>
<path d=""  transform="translate(5373, 840)"/>
<path d=""  transform="translate(6006, 840)"/>
<path d=""  transform="translate(6630, 840)"/>
<path d=""  transform="translate(7422, 840)"/>
<path d=""  transform="translate(7682, 840)"/>
<path d=""  transform="translate(8315, 840)"/>
<path d=""  transform="translate(8992, 840)"/>
<path d=""  transform="translate(9421, 840)"/>
<path d=""  transform="translate(10255, 840)"/>
<path d=""  transform="translate(11205, 840)"/>
<path d=""  transform="translate(11465, 840)"/>
<path d=""  transform="translate(12415, 840)"/>
<path d=""  transform="translate(13207, 840)"/>
<path d=""  transform="translate(13884, 840)"/>
<path d=""  transform="translate(14391, 840)"/>
<path d=""  transform="translate(15024, 840)"/>
<path d=""  transform="translate(15284, 840)"/>
<path d=""  transform="translate(15669, 840)"/>
<path d=""  transform="translate(16293, 840)"/>
<path d=""  transform="translate(16553, 840)"/>
<path d=""  transform="translate(17345, 840)"/>
<path d=""  transform="translate(18392, 840)"/>
<path d=""  transform="translate(18392, 840)"/>
<path d=""  transform="translate(18652, 840)"/>
<path d=""  transform="translate(18652, 840)"/>
<path d=""  transform="translate(19224, 840)"/>
<path d=""  transform="translate(19796, 840)"/>
<path d=""  transform="translate(20056, 840)"/>
<path d=""  transform="translate(20689, 840)"/>
<path d=""  transform="translate(21322, 840)"/>
<path d=""  transform="translate(21751, 840)"/>
<path d=""  transform="translate(22411, 840)"/>
<path d=""  transform="translate(23076, 840)"/>
<path d=""  transform="translate(23336, 840)"/>
<path d=""  transform="translate(23336, 840)"/>
<path d=""  transform="translate(23596, 840)"/>
<path d=""  transform="translate(23596, 840)"/>
<path d=""  transform="translate(24229, 840)"/>
<path d=""  transform="translate(24229, 840)"/>
<path d=""  transform="translate(24489, 840)"/>
<path d=""  transform="translate(24489, 840)"/>
<path d=""  transform="translate(25166, 840)"/>
<path d=""  transform="translate(25673, 840)"/>
<path d=""  transform="translate(26297, 840)"/>
<path d=""  transform="translate(27219, 840)"/>
<path d=""  transform="translate(28120, 840)"/>
<path d=""  transform="translate(28380, 840)"/>
<path d=""  transform="translate(29013, 840)"/>
<path d=""  transform="translate(29637, 840)"/>
<path d=""  transform="translate(30056, 840)"/>
<path d=""  transform="translate(31006, 840)"/>
<path d=""  transform="translate(31266, 840)"/>
<path d=""  transform="translate(32058, 840)"/>
<path d=""  transform="translate(32764, 840)"/>
<path d=""  transform="translate(33193, 840)"/>
<path d=""  transform="translate(34027, 840)"/>
<path d=""  transform="translate(34446, 840)"/>
<path d=""  transform="translate(34865, 840)"/>
<path d=""  transform="translate(35125, 840)"/>
<path d=""  transform="translate(35505, 840)"/>
<path d=""  transform="translate(35934, 840)"/>
<path d=""  transform="translate(36314, 840)"/>
<path d=""  transform="translate(36947, 840)"/>
<path d=""  transform="translate(37781, 840)"/>
<path d=""  transform="translate(38041, 840)"/>
<path d=""  transform="translate(38460, 840)"/>
<path d=""  transform="translate(38967, 840)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 39729 2130" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 840)"/>
<path d=""  transform="translate(633, 840)"/>
<path d=""  transform="translate(1265, 840)"/>
<path d=""  transform="translate(1692, 840)"/>
<path d=""  transform="translate(2121, 840)"/>
<path d=""  transform="translate(2548, 840)"/>
<path d=""  transform="translate(2967, 840)"/>
<path d=""  transform="translate(3227, 840)"/>
<path d=""  transform="translate(3860, 840)"/>
<path d=""  transform="translate(4537, 840)"/>
<path d=""  transform="translate(4988, 840)"/>
<path d=""  transform="translate(5373, 840)"/>
<path d=""  transform="translate(6006, 840)"/>
<path d=""  transform="translate(6630, 840)"/>
<path d=""  transform="translate(7422, 840)"/>
<path d=""  transform="translate(7682, 840)"/>
<path d=""  transform="translate(8315, 840)"/>
<path d=""  transform="translate(8992, 840)"/>
<path d=""  transform="translate(9421, 840)"/>
<path d=""  transform="translate(10255, 840)"/>
<path d=""  transform="translate(11205, 840)"/>
<path d=""  transform="translate(11465, 840)"/>
<path d=""  transform="translate(12415, 840)"/>
<path d=""  transform="translate(13207, 840)"/>
<path d=""  transform="translate(13884, 840)"/>
<path d=""  transform="translate(14391, 840)"/>
<path d=""  transform="translate(15024, 840)"/>
<path d=""  transform="translate(15284, 840)"/>
<path d=""  transform="translate(15669, 840)"/>
<path d=""  transform="translate(16293, 840)"/>
<path d=""  transform="translate(16553, 840)"/>
<path d=""  transform="translate(17345, 840)"/>
<path d=""  transform="translate(18392, 840)"/>
<path d=""  transform="translate(18392, 840)"/>
<path d=""  transform="translate(18652, 840)"/>
<path d=""  transform="translate(18652, 840)"/>
<path d=""  transform="translate(19252, 840)"/>
<path d=""  transform="translate(19852, 840)"/>
<path d=""  transform="translate(20112, 840)"/>
<path d=""  transform="translate(20745, 840)"/>
<path d=""  transform="translate(21378, 840)"/>
<path d=""  transform="translate(21807, 840)"/>
<path d=""  transform="translate(22467, 840)"/>
<path d=""  transform="translate(23132, 840)"/>
<path d=""  transform="translate(23392, 840)"/>
<path d=""  transform="translate(23392, 840)"/>
<path d=""  transform="translate(23652, 840)"/>
<path d=""  transform="translate(23652, 840)"/>
<path d=""  transform="translate(24285, 840)"/>
<path d=""  transform="translate(24285, 840)"/>
<path d=""  transform="translate(24545, 840)"/>
<path d=""  transform="translate(24545, 840)"/>
<path d=""  transform="translate(25222, 840)"/>
<path d=""  transform="translate(25729, 840)"/>
<path d=""  transform="translate(26353, 840)"/>
<path d=""  transform="translate(27275, 840)"/>
<path d=""  transform="translate(28176, 840)"/>
<path d=""  transform="translate(28436, 840)"/>
<path d=""  transform="translate(29069, 840)"/>
<path d=""  transform="translate(29693, 840)"/>
<path d=""  transform="translate(30112, 840)"/>
<path d=""  transform="translate(31062, 840)"/>
<path d=""  transform="translate(31322, 840)"/>
<path d=""  transform="translate(32114, 840)"/>
<path d=""  transform="translate(32820, 840)"/>
<path d=""  transform="translate(33249, 840)"/>
<path d=""  transform="translate(34083, 840)"/>
<path d=""  transform="translate(34502, 840)"/>
<path d=""  transform="translate(34921, 840)"/>
<path d=""  transform="translate(35181, 840)"/>
<path d=""  transform="translate(35561, 840)"/>
<path d=""  transform="translate(35990, 840)"/>
<path d=""  transform="translate(36370, 840)"/>
<path d=""  transform="translate(37003, 840)"/>
<path d=""  transform="translate(37837, 840)"/>
<path d=""  transform="translate(38097, 840)"/>
<path d=""  transform="translate(38516, 840)"/>
<path d=""  transform="translate(39023, 840)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐫁𐫍𐫁𐫢𐫀 𐫀𐫤𐫡𐫀 ‬ ‫𐫇𐫅𐫏𐫡𐫤𐫀 𐫙𐫓 𐫀𐫤𐫡𐫀‬ ‫ 𐫖𐫓𐫇𐫀𐫀 14‬ ‫𐫐𐫓 𐫍𐫅 𐫀𐫏𐫤𐫓𐫆 𐫆𐫞𐫇𐫤𐫀 𐫓𐫍𐫀𐫡𐫇𐫤𐫀 𐫅𐫎𐫓𐫁</span></li>


<pre>Expected: u10AC1.fina=72+999|u10AD3.init=71+660|u10ACE=70+520|u10AC5=69+419|space=68+260|u10AC0=67+633|u10AE4=66+677|u10AC7=65+451|u10AE1.fina=64+385|u10AC0.medi=63+633|u10ACD.init=62+624|u10AD3=61+792|space=60+260|u10AC0=59+633|u10AE4=58+677|u10AC7.fina=57+429|u10ADE.init=56+834|u10AC6=55+950|space=54+260|u10AC6=53+950|u10AD3=52+792|u10AE4=51+677|u10ACF.fina=50+507|u10AC0.init=49+633|space=48+260|u10AC5.fina=47+385|u10ACD.init=46+624|space=45+260|u10AD3=44+792|u10AD0=43+1047|space=42+0|space=41+260|space=40+0|.notdef=39+600|.notdef=38+600|space=37+260|u10AC0.fina=36+633|u10AC0.init=35+633|u10AC7.fina=34+429|u10AD3.medi=33+660|u10AD6.init=32+665|space=31+260|space=30+0|space=29+260|space=28+0|u10AC0=27+633|u10AE1=26+419|u10AE4.fina=25+632|u10AC0.init=24+633|space=23+260|u10AD3.fina=22+792|u10AD9.init=21+607|space=20+260|u10AC0=19+633|u10AE4=18+677|u10AE1=17+419|u10ACF=16+507|u10AC5=15+419|u10AC7=14+451|space=13+0|space=12+260|space=11+0|space=10+260|u10AC0=9+633|u10AE1=8+419|u10AE4.fina=7+632|u10AC0.init=6+633|space=5+260|u10AC0=4+633|u10AE2=3+973|u10AC1.fina=2+999|u10ACD.init=1+624|u10AC1=0+999</pre>



<pre>Got     : u10AC1.fina=72+999|u10AD3.init=71+660|u10ACE=70+520|u10AC5=69+419|space=68+260|u10AC0=67+633|u10AE4=66+677|u10AC7=65+451|u10AE1.fina=64+385|u10AC0.medi=63+633|u10ACD.init=62+624|u10AD3=61+792|space=60+260|u10AC0=59+633|u10AE4=58+677|u10AC7.fina=57+429|u10ADE.init=56+834|u10AC6=55+950|space=54+260|u10AC6=53+950|u10AD3=52+792|u10AE4=51+677|u10ACF.fina=50+507|u10AC0.init=49+633|space=48+260|u10AC5.fina=47+385|u10ACD.init=46+624|space=45+260|u10AD3=44+792|u10AD0=43+1047|space=42+0|space=41+260|space=40+0|four=39+572|one=38+572|space=37+260|u10AC0.fina=36+633|u10AC0.init=35+633|u10AC7.fina=34+429|u10AD3.medi=33+660|u10AD6.init=32+665|space=31+260|space=30+0|space=29+260|space=28+0|u10AC0=27+633|u10AE1=26+419|u10AE4.fina=25+632|u10AC0.init=24+633|space=23+260|u10AD3.fina=22+792|u10AD9.init=21+607|space=20+260|u10AC0=19+633|u10AE4=18+677|u10AE1=17+419|u10ACF=16+507|u10AC5=15+419|u10AC7=14+451|space=13+0|space=12+260|space=11+0|space=10+260|u10AC0=9+633|u10AE1=8+419|u10AE4.fina=7+632|u10AC0.init=6+633|space=5+260|u10AC0=4+633|u10AE2=3+973|u10AC1.fina=2+999|u10ACD.init=1+624|u10AC1=0+999</pre>



<pre>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    ^^ ^^^^^^^^^^^^^^ ^^^^    ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 37894 2130" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 840)"/>
<path d=""  transform="translate(999, 840)"/>
<path d=""  transform="translate(1659, 840)"/>
<path d=""  transform="translate(2179, 840)"/>
<path d=""  transform="translate(2598, 840)"/>
<path d=""  transform="translate(2858, 840)"/>
<path d=""  transform="translate(3491, 840)"/>
<path d=""  transform="translate(4168, 840)"/>
<path d=""  transform="translate(4619, 840)"/>
<path d=""  transform="translate(5004, 840)"/>
<path d=""  transform="translate(5637, 840)"/>
<path d=""  transform="translate(6261, 840)"/>
<path d=""  transform="translate(7053, 840)"/>
<path d=""  transform="translate(7313, 840)"/>
<path d=""  transform="translate(7946, 840)"/>
<path d=""  transform="translate(8623, 840)"/>
<path d=""  transform="translate(9052, 840)"/>
<path d=""  transform="translate(9886, 840)"/>
<path d=""  transform="translate(10836, 840)"/>
<path d=""  transform="translate(11096, 840)"/>
<path d=""  transform="translate(12046, 840)"/>
<path d=""  transform="translate(12838, 840)"/>
<path d=""  transform="translate(13515, 840)"/>
<path d=""  transform="translate(14022, 840)"/>
<path d=""  transform="translate(14655, 840)"/>
<path d=""  transform="translate(14915, 840)"/>
<path d=""  transform="translate(15300, 840)"/>
<path d=""  transform="translate(15924, 840)"/>
<path d=""  transform="translate(16184, 840)"/>
<path d=""  transform="translate(16976, 840)"/>
<path d=""  transform="translate(18023, 840)"/>
<path d=""  transform="translate(18023, 840)"/>
<path d=""  transform="translate(18283, 840)"/>
<path d=""  transform="translate(18283, 840)"/>
<path d=""  transform="translate(18855, 840)"/>
<path d=""  transform="translate(19427, 840)"/>
<path d=""  transform="translate(19687, 840)"/>
<path d=""  transform="translate(20320, 840)"/>
<path d=""  transform="translate(20953, 840)"/>
<path d=""  transform="translate(21382, 840)"/>
<path d=""  transform="translate(22042, 840)"/>
<path d=""  transform="translate(22707, 840)"/>
<path d=""  transform="translate(22967, 840)"/>
<path d=""  transform="translate(22967, 840)"/>
<path d=""  transform="translate(23227, 840)"/>
<path d=""  transform="translate(23227, 840)"/>
<path d=""  transform="translate(23860, 840)"/>
<path d=""  transform="translate(24279, 840)"/>
<path d=""  transform="translate(24911, 840)"/>
<path d=""  transform="translate(25544, 840)"/>
<path d=""  transform="translate(25804, 840)"/>
<path d=""  transform="translate(26596, 840)"/>
<path d=""  transform="translate(27203, 840)"/>
<path d=""  transform="translate(27463, 840)"/>
<path d=""  transform="translate(28096, 840)"/>
<path d=""  transform="translate(28773, 840)"/>
<path d=""  transform="translate(29192, 840)"/>
<path d=""  transform="translate(29699, 840)"/>
<path d=""  transform="translate(30118, 840)"/>
<path d=""  transform="translate(30569, 840)"/>
<path d=""  transform="translate(30569, 840)"/>
<path d=""  transform="translate(30829, 840)"/>
<path d=""  transform="translate(30829, 840)"/>
<path d=""  transform="translate(31089, 840)"/>
<path d=""  transform="translate(31722, 840)"/>
<path d=""  transform="translate(32141, 840)"/>
<path d=""  transform="translate(32773, 840)"/>
<path d=""  transform="translate(33406, 840)"/>
<path d=""  transform="translate(33666, 840)"/>
<path d=""  transform="translate(34299, 840)"/>
<path d=""  transform="translate(35272, 840)"/>
<path d=""  transform="translate(36271, 840)"/>
<path d=""  transform="translate(36895, 840)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 37950 2130" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 840)"/>
<path d=""  transform="translate(999, 840)"/>
<path d=""  transform="translate(1659, 840)"/>
<path d=""  transform="translate(2179, 840)"/>
<path d=""  transform="translate(2598, 840)"/>
<path d=""  transform="translate(2858, 840)"/>
<path d=""  transform="translate(3491, 840)"/>
<path d=""  transform="translate(4168, 840)"/>
<path d=""  transform="translate(4619, 840)"/>
<path d=""  transform="translate(5004, 840)"/>
<path d=""  transform="translate(5637, 840)"/>
<path d=""  transform="translate(6261, 840)"/>
<path d=""  transform="translate(7053, 840)"/>
<path d=""  transform="translate(7313, 840)"/>
<path d=""  transform="translate(7946, 840)"/>
<path d=""  transform="translate(8623, 840)"/>
<path d=""  transform="translate(9052, 840)"/>
<path d=""  transform="translate(9886, 840)"/>
<path d=""  transform="translate(10836, 840)"/>
<path d=""  transform="translate(11096, 840)"/>
<path d=""  transform="translate(12046, 840)"/>
<path d=""  transform="translate(12838, 840)"/>
<path d=""  transform="translate(13515, 840)"/>
<path d=""  transform="translate(14022, 840)"/>
<path d=""  transform="translate(14655, 840)"/>
<path d=""  transform="translate(14915, 840)"/>
<path d=""  transform="translate(15300, 840)"/>
<path d=""  transform="translate(15924, 840)"/>
<path d=""  transform="translate(16184, 840)"/>
<path d=""  transform="translate(16976, 840)"/>
<path d=""  transform="translate(18023, 840)"/>
<path d=""  transform="translate(18023, 840)"/>
<path d=""  transform="translate(18283, 840)"/>
<path d=""  transform="translate(18283, 840)"/>
<path d=""  transform="translate(18883, 840)"/>
<path d=""  transform="translate(19483, 840)"/>
<path d=""  transform="translate(19743, 840)"/>
<path d=""  transform="translate(20376, 840)"/>
<path d=""  transform="translate(21009, 840)"/>
<path d=""  transform="translate(21438, 840)"/>
<path d=""  transform="translate(22098, 840)"/>
<path d=""  transform="translate(22763, 840)"/>
<path d=""  transform="translate(23023, 840)"/>
<path d=""  transform="translate(23023, 840)"/>
<path d=""  transform="translate(23283, 840)"/>
<path d=""  transform="translate(23283, 840)"/>
<path d=""  transform="translate(23916, 840)"/>
<path d=""  transform="translate(24335, 840)"/>
<path d=""  transform="translate(24967, 840)"/>
<path d=""  transform="translate(25600, 840)"/>
<path d=""  transform="translate(25860, 840)"/>
<path d=""  transform="translate(26652, 840)"/>
<path d=""  transform="translate(27259, 840)"/>
<path d=""  transform="translate(27519, 840)"/>
<path d=""  transform="translate(28152, 840)"/>
<path d=""  transform="translate(28829, 840)"/>
<path d=""  transform="translate(29248, 840)"/>
<path d=""  transform="translate(29755, 840)"/>
<path d=""  transform="translate(30174, 840)"/>
<path d=""  transform="translate(30625, 840)"/>
<path d=""  transform="translate(30625, 840)"/>
<path d=""  transform="translate(30885, 840)"/>
<path d=""  transform="translate(30885, 840)"/>
<path d=""  transform="translate(31145, 840)"/>
<path d=""  transform="translate(31778, 840)"/>
<path d=""  transform="translate(32197, 840)"/>
<path d=""  transform="translate(32829, 840)"/>
<path d=""  transform="translate(33462, 840)"/>
<path d=""  transform="translate(33722, 840)"/>
<path d=""  transform="translate(34355, 840)"/>
<path d=""  transform="translate(35328, 840)"/>
<path d=""  transform="translate(36327, 840)"/>
<path d=""  transform="translate(36951, 840)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐫛𐫇𐫓𐫏𐫎𐫏𐫞𐫏𐫀 𐫏𐫗 𐫙𐫁𐫅𐫇𐫏𐫤𐫀𐫓𐫀 𐫅𐫁𐫏𐫞𐫀 𐫖𐫗 𐫗𐫏𐫢𐫀 𐫅𐫀𐫖‬ ‫𐫇𐫤𐫀 𐫖𐫍𐫏𐫅𐫀‬ ‫ 𐫖𐫓𐫇𐫀𐫀 15‬ ‫𐫐𐫓 𐫍𐫅 𐫀𐫏𐫤𐫓𐫆</span></li>


<pre>Expected: u10AC6=77+950|u10AD3=76+792|u10AE4=75+677|u10ACF.fina=74+507|u10AC0.init=73+633|space=72+260|u10AC5.fina=71+385|u10ACD.init=70+624|space=69+260|u10AD3=68+792|u10AD0=67+1047|space=66+0|space=65+260|space=64+0|.notdef=63+600|.notdef=62+600|space=61+260|u10AC0.fina=60+633|u10AC0.init=59+633|u10AC7.fina=58+429|u10AD3.medi=57+660|u10AD6.init=56+665|space=55+260|space=54+0|space=53+260|space=52+0|u10AC0=51+633|u10AC5=50+419|u10ACF.fina=49+507|u10ACD.init=48+624|u10AD6=47+994|space=46+260|u10AC0=45+633|u10AE4=44+677|u10AC7=43+451|space=42+0|space=41+260|space=40+0|u10AD6.fina=39+994|u10AC0.init=38+633|u10AC5=37+419|space=36+260|u10AC0=35+633|u10AE2=34+973|u10ACF.fina=33+507|u10AD7.init=32+380|space=31+260|u10AD7=30+380|u10AD6=29+994|space=28+260|u10AC0.fina=27+633|u10ADE.init=26+834|u10ACF.fina=25+507|u10AC1.init=24+706|u10AC5=23+419|space=22+260|u10AC0.fina=21+633|u10AD3.medi=20+660|u10AC0.init=19+633|u10AE4=18+677|u10ACF=17+507|u10AC7=16+451|u10AC5.fina=15+385|u10AC1.medi=14+706|u10AD9.init=13+607|space=12+260|u10AD7=11+380|u10ACF=10+507|space=9+260|u10AC0=8+633|u10ACF.fina=7+507|u10ADE.init=6+834|u10ACF=5+507|u10ACE=4+520|u10ACF.fina=3+507|u10AD3.init=2+660|u10AC7.fina=1+429|u10ADB.init=0+487</pre>



<pre>Got     : u10AC6=77+950|u10AD3=76+792|u10AE4=75+677|u10ACF.fina=74+507|u10AC0.init=73+633|space=72+260|u10AC5.fina=71+385|u10ACD.init=70+624|space=69+260|u10AD3=68+792|u10AD0=67+1047|space=66+0|space=65+260|space=64+0|five=63+572|one=62+572|space=61+260|u10AC0.fina=60+633|u10AC0.init=59+633|u10AC7.fina=58+429|u10AD3.medi=57+660|u10AD6.init=56+665|space=55+260|space=54+0|space=53+260|space=52+0|u10AC0=51+633|u10AC5=50+419|u10ACF.fina=49+507|u10ACD.init=48+624|u10AD6=47+994|space=46+260|u10AC0=45+633|u10AE4=44+677|u10AC7=43+451|space=42+0|space=41+260|space=40+0|u10AD6.fina=39+994|u10AC0.init=38+633|u10AC5=37+419|space=36+260|u10AC0=35+633|u10AE2=34+973|u10ACF.fina=33+507|u10AD7.init=32+380|space=31+260|u10AD7=30+380|u10AD6=29+994|space=28+260|u10AC0.fina=27+633|u10ADE.init=26+834|u10ACF.fina=25+507|u10AC1.init=24+706|u10AC5=23+419|space=22+260|u10AC0.fina=21+633|u10AD3.medi=20+660|u10AC0.init=19+633|u10AE4=18+677|u10ACF=17+507|u10AC7=16+451|u10AC5.fina=15+385|u10AC1.medi=14+706|u10AD9.init=13+607|space=12+260|u10AD7=11+380|u10ACF=10+507|space=9+260|u10AC0=8+633|u10ACF.fina=7+507|u10ADE.init=6+834|u10ACF=5+507|u10ACE=4+520|u10ACF.fina=3+507|u10AD3.init=2+660|u10AC7.fina=1+429|u10ADB.init=0+487</pre>



<pre>                                                                                                                                                                                                                          ^^ ^^^^^^^^^^^^^^^^^^^^^^^^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 39391 2130" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 840)"/>
<path d=""  transform="translate(950, 840)"/>
<path d=""  transform="translate(1742, 840)"/>
<path d=""  transform="translate(2419, 840)"/>
<path d=""  transform="translate(2926, 840)"/>
<path d=""  transform="translate(3559, 840)"/>
<path d=""  transform="translate(3819, 840)"/>
<path d=""  transform="translate(4204, 840)"/>
<path d=""  transform="translate(4828, 840)"/>
<path d=""  transform="translate(5088, 840)"/>
<path d=""  transform="translate(5880, 840)"/>
<path d=""  transform="translate(6927, 840)"/>
<path d=""  transform="translate(6927, 840)"/>
<path d=""  transform="translate(7187, 840)"/>
<path d=""  transform="translate(7187, 840)"/>
<path d=""  transform="translate(7759, 840)"/>
<path d=""  transform="translate(8331, 840)"/>
<path d=""  transform="translate(8591, 840)"/>
<path d=""  transform="translate(9224, 840)"/>
<path d=""  transform="translate(9857, 840)"/>
<path d=""  transform="translate(10286, 840)"/>
<path d=""  transform="translate(10946, 840)"/>
<path d=""  transform="translate(11611, 840)"/>
<path d=""  transform="translate(11871, 840)"/>
<path d=""  transform="translate(11871, 840)"/>
<path d=""  transform="translate(12131, 840)"/>
<path d=""  transform="translate(12131, 840)"/>
<path d=""  transform="translate(12764, 840)"/>
<path d=""  transform="translate(13183, 840)"/>
<path d=""  transform="translate(13690, 840)"/>
<path d=""  transform="translate(14314, 840)"/>
<path d=""  transform="translate(15308, 840)"/>
<path d=""  transform="translate(15568, 840)"/>
<path d=""  transform="translate(16201, 840)"/>
<path d=""  transform="translate(16878, 840)"/>
<path d=""  transform="translate(17329, 840)"/>
<path d=""  transform="translate(17329, 840)"/>
<path d=""  transform="translate(17589, 840)"/>
<path d=""  transform="translate(17589, 840)"/>
<path d=""  transform="translate(18583, 840)"/>
<path d=""  transform="translate(19216, 840)"/>
<path d=""  transform="translate(19635, 840)"/>
<path d=""  transform="translate(19895, 840)"/>
<path d=""  transform="translate(20528, 840)"/>
<path d=""  transform="translate(21501, 840)"/>
<path d=""  transform="translate(22008, 840)"/>
<path d=""  transform="translate(22388, 840)"/>
<path d=""  transform="translate(22648, 840)"/>
<path d=""  transform="translate(23028, 840)"/>
<path d=""  transform="translate(24022, 840)"/>
<path d=""  transform="translate(24282, 840)"/>
<path d=""  transform="translate(24915, 840)"/>
<path d=""  transform="translate(25749, 840)"/>
<path d=""  transform="translate(26256, 840)"/>
<path d=""  transform="translate(26962, 840)"/>
<path d=""  transform="translate(27381, 840)"/>
<path d=""  transform="translate(27641, 840)"/>
<path d=""  transform="translate(28274, 840)"/>
<path d=""  transform="translate(28934, 840)"/>
<path d=""  transform="translate(29567, 840)"/>
<path d=""  transform="translate(30244, 840)"/>
<path d=""  transform="translate(30751, 840)"/>
<path d=""  transform="translate(31202, 840)"/>
<path d=""  transform="translate(31587, 840)"/>
<path d=""  transform="translate(32293, 840)"/>
<path d=""  transform="translate(32900, 840)"/>
<path d=""  transform="translate(33160, 840)"/>
<path d=""  transform="translate(33540, 840)"/>
<path d=""  transform="translate(34047, 840)"/>
<path d=""  transform="translate(34307, 840)"/>
<path d=""  transform="translate(34940, 840)"/>
<path d=""  transform="translate(35447, 840)"/>
<path d=""  transform="translate(36281, 840)"/>
<path d=""  transform="translate(36788, 840)"/>
<path d=""  transform="translate(37308, 840)"/>
<path d=""  transform="translate(37815, 840)"/>
<path d=""  transform="translate(38475, 840)"/>
<path d=""  transform="translate(38904, 840)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 39447 2130" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 840)"/>
<path d=""  transform="translate(950, 840)"/>
<path d=""  transform="translate(1742, 840)"/>
<path d=""  transform="translate(2419, 840)"/>
<path d=""  transform="translate(2926, 840)"/>
<path d=""  transform="translate(3559, 840)"/>
<path d=""  transform="translate(3819, 840)"/>
<path d=""  transform="translate(4204, 840)"/>
<path d=""  transform="translate(4828, 840)"/>
<path d=""  transform="translate(5088, 840)"/>
<path d=""  transform="translate(5880, 840)"/>
<path d=""  transform="translate(6927, 840)"/>
<path d=""  transform="translate(6927, 840)"/>
<path d=""  transform="translate(7187, 840)"/>
<path d=""  transform="translate(7187, 840)"/>
<path d=""  transform="translate(7787, 840)"/>
<path d=""  transform="translate(8387, 840)"/>
<path d=""  transform="translate(8647, 840)"/>
<path d=""  transform="translate(9280, 840)"/>
<path d=""  transform="translate(9913, 840)"/>
<path d=""  transform="translate(10342, 840)"/>
<path d=""  transform="translate(11002, 840)"/>
<path d=""  transform="translate(11667, 840)"/>
<path d=""  transform="translate(11927, 840)"/>
<path d=""  transform="translate(11927, 840)"/>
<path d=""  transform="translate(12187, 840)"/>
<path d=""  transform="translate(12187, 840)"/>
<path d=""  transform="translate(12820, 840)"/>
<path d=""  transform="translate(13239, 840)"/>
<path d=""  transform="translate(13746, 840)"/>
<path d=""  transform="translate(14370, 840)"/>
<path d=""  transform="translate(15364, 840)"/>
<path d=""  transform="translate(15624, 840)"/>
<path d=""  transform="translate(16257, 840)"/>
<path d=""  transform="translate(16934, 840)"/>
<path d=""  transform="translate(17385, 840)"/>
<path d=""  transform="translate(17385, 840)"/>
<path d=""  transform="translate(17645, 840)"/>
<path d=""  transform="translate(17645, 840)"/>
<path d=""  transform="translate(18639, 840)"/>
<path d=""  transform="translate(19272, 840)"/>
<path d=""  transform="translate(19691, 840)"/>
<path d=""  transform="translate(19951, 840)"/>
<path d=""  transform="translate(20584, 840)"/>
<path d=""  transform="translate(21557, 840)"/>
<path d=""  transform="translate(22064, 840)"/>
<path d=""  transform="translate(22444, 840)"/>
<path d=""  transform="translate(22704, 840)"/>
<path d=""  transform="translate(23084, 840)"/>
<path d=""  transform="translate(24078, 840)"/>
<path d=""  transform="translate(24338, 840)"/>
<path d=""  transform="translate(24971, 840)"/>
<path d=""  transform="translate(25805, 840)"/>
<path d=""  transform="translate(26312, 840)"/>
<path d=""  transform="translate(27018, 840)"/>
<path d=""  transform="translate(27437, 840)"/>
<path d=""  transform="translate(27697, 840)"/>
<path d=""  transform="translate(28330, 840)"/>
<path d=""  transform="translate(28990, 840)"/>
<path d=""  transform="translate(29623, 840)"/>
<path d=""  transform="translate(30300, 840)"/>
<path d=""  transform="translate(30807, 840)"/>
<path d=""  transform="translate(31258, 840)"/>
<path d=""  transform="translate(31643, 840)"/>
<path d=""  transform="translate(32349, 840)"/>
<path d=""  transform="translate(32956, 840)"/>
<path d=""  transform="translate(33216, 840)"/>
<path d=""  transform="translate(33596, 840)"/>
<path d=""  transform="translate(34103, 840)"/>
<path d=""  transform="translate(34363, 840)"/>
<path d=""  transform="translate(34996, 840)"/>
<path d=""  transform="translate(35503, 840)"/>
<path d=""  transform="translate(36337, 840)"/>
<path d=""  transform="translate(36844, 840)"/>
<path d=""  transform="translate(37364, 840)"/>
<path d=""  transform="translate(37871, 840)"/>
<path d=""  transform="translate(38531, 840)"/>
<path d=""  transform="translate(38960, 840)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐫖𐫓𐫇𐫀𐫀 16‬ ‫𐫗𐫢𐫀 𐫙𐫖 𐫅𐫐𐫡𐫀 𐫀𐫏𐫤𐫓𐫆𐫇𐫗 𐫆𐫞𐫇𐫤𐫀 𐫓𐫃𐫁𐫡𐫀 𐫇𐫢𐫤𐫘𐫤𐫀 𐫅𐫐𐫇‬ ‫𐫓𐫤 𐫅𐫓𐫀 𐫆𐫐 𐫢𐫡𐫎 𐫃𐫗𐫘𐫏𐫀 𐫏𐫗</span></li>


<pre>Expected: u10AD7=77+380|u10ACF=76+507|space=75+260|u10AC0=74+633|u10ACF.fina=73+507|u10AD8.medi=72+766|u10AD7.init=71+380|u10AC3=70+529|space=69+260|u10ACE=68+520|u10AE1=67+419|u10AE2=66+973|space=65+260|u10AD0=64+1047|u10AC6=63+950|space=62+260|u10AC0.fina=61+633|u10AD3.init=60+660|u10AC5=59+419|space=58+260|u10AE4.fina=57+632|u10AD3.init=56+660|space=55+0|space=54+260|space=53+0|u10AC7=52+451|u10AD0=51+1047|u10AC5=50+419|space=49+260|u10AC0=48+633|u10AE4.fina=47+632|u10AD8.init=46+766|u10AE4=45+677|u10AE2=44+973|u10AC7=43+451|space=42+260|u10AC0=41+633|u10AE1.fina=40+385|u10AC1.medi=39+706|u10AC3.medi=38+407|u10AD3.init=37+660|space=36+260|u10AC0=35+633|u10AE4=34+677|u10AC7.fina=33+429|u10ADE.init=32+834|u10AC6=31+950|space=30+260|u10AD7=29+380|u10AC7=28+451|u10AC6=27+950|u10AD3=26+792|u10AE4=25+677|u10ACF.fina=24+507|u10AC0.init=23+633|space=22+260|u10AC0=21+633|u10AE1=20+419|u10AD0=19+1047|u10AC5=18+419|space=17+260|u10AD6.fina=16+994|u10AD9.init=15+607|space=14+260|u10AC0=13+633|u10AE2=12+973|u10AD7=11+380|space=10+0|space=9+260|space=8+0|.notdef=7+600|.notdef=6+600|space=5+260|u10AC0.fina=4+633|u10AC0.init=3+633|u10AC7.fina=2+429|u10AD3.medi=1+660|u10AD6.init=0+665</pre>



<pre>Got     : u10AD7=77+380|u10ACF=76+507|space=75+260|u10AC0=74+633|u10ACF.fina=73+507|u10AD8.medi=72+766|u10AD7.init=71+380|u10AC3=70+529|space=69+260|u10ACE=68+520|u10AE1=67+419|u10AE2=66+973|space=65+260|u10AD0=64+1047|u10AC6=63+950|space=62+260|u10AC0.fina=61+633|u10AD3.init=60+660|u10AC5=59+419|space=58+260|u10AE4.fina=57+632|u10AD3.init=56+660|space=55+0|space=54+260|space=53+0|u10AC7=52+451|u10AD0=51+1047|u10AC5=50+419|space=49+260|u10AC0=48+633|u10AE4.fina=47+632|u10AD8.init=46+766|u10AE4=45+677|u10AE2=44+973|u10AC7=43+451|space=42+260|u10AC0=41+633|u10AE1.fina=40+385|u10AC1.medi=39+706|u10AC3.medi=38+407|u10AD3.init=37+660|space=36+260|u10AC0=35+633|u10AE4=34+677|u10AC7.fina=33+429|u10ADE.init=32+834|u10AC6=31+950|space=30+260|u10AD7=29+380|u10AC7=28+451|u10AC6=27+950|u10AD3=26+792|u10AE4=25+677|u10ACF.fina=24+507|u10AC0.init=23+633|space=22+260|u10AC0=21+633|u10AE1=20+419|u10AD0=19+1047|u10AC5=18+419|space=17+260|u10AD6.fina=16+994|u10AD9.init=15+607|space=14+260|u10AC0=13+633|u10AE2=12+973|u10AD7=11+380|space=10+0|space=9+260|space=8+0|six=7+572|one=6+572|space=5+260|u10AC0.fina=4+633|u10AC0.init=3+633|u10AC7.fina=2+429|u10AD3.medi=1+660|u10AD6.init=0+665</pre>



<pre>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    ^^ ^^^ ^^^^^^^^^^ ^^ +++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 41537 2130" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 840)"/>
<path d=""  transform="translate(380, 840)"/>
<path d=""  transform="translate(887, 840)"/>
<path d=""  transform="translate(1147, 840)"/>
<path d=""  transform="translate(1780, 840)"/>
<path d=""  transform="translate(2287, 840)"/>
<path d=""  transform="translate(3053, 840)"/>
<path d=""  transform="translate(3433, 840)"/>
<path d=""  transform="translate(3962, 840)"/>
<path d=""  transform="translate(4222, 840)"/>
<path d=""  transform="translate(4742, 840)"/>
<path d=""  transform="translate(5161, 840)"/>
<path d=""  transform="translate(6134, 840)"/>
<path d=""  transform="translate(6394, 840)"/>
<path d=""  transform="translate(7441, 840)"/>
<path d=""  transform="translate(8391, 840)"/>
<path d=""  transform="translate(8651, 840)"/>
<path d=""  transform="translate(9284, 840)"/>
<path d=""  transform="translate(9944, 840)"/>
<path d=""  transform="translate(10363, 840)"/>
<path d=""  transform="translate(10623, 840)"/>
<path d=""  transform="translate(11255, 840)"/>
<path d=""  transform="translate(11915, 840)"/>
<path d=""  transform="translate(11915, 840)"/>
<path d=""  transform="translate(12175, 840)"/>
<path d=""  transform="translate(12175, 840)"/>
<path d=""  transform="translate(12626, 840)"/>
<path d=""  transform="translate(13673, 840)"/>
<path d=""  transform="translate(14092, 840)"/>
<path d=""  transform="translate(14352, 840)"/>
<path d=""  transform="translate(14985, 840)"/>
<path d=""  transform="translate(15617, 840)"/>
<path d=""  transform="translate(16383, 840)"/>
<path d=""  transform="translate(17060, 840)"/>
<path d=""  transform="translate(18033, 840)"/>
<path d=""  transform="translate(18484, 840)"/>
<path d=""  transform="translate(18744, 840)"/>
<path d=""  transform="translate(19377, 840)"/>
<path d=""  transform="translate(19762, 840)"/>
<path d=""  transform="translate(20468, 840)"/>
<path d=""  transform="translate(20875, 840)"/>
<path d=""  transform="translate(21535, 840)"/>
<path d=""  transform="translate(21795, 840)"/>
<path d=""  transform="translate(22428, 840)"/>
<path d=""  transform="translate(23105, 840)"/>
<path d=""  transform="translate(23534, 840)"/>
<path d=""  transform="translate(24368, 840)"/>
<path d=""  transform="translate(25318, 840)"/>
<path d=""  transform="translate(25578, 840)"/>
<path d=""  transform="translate(25958, 840)"/>
<path d=""  transform="translate(26409, 840)"/>
<path d=""  transform="translate(27359, 840)"/>
<path d=""  transform="translate(28151, 840)"/>
<path d=""  transform="translate(28828, 840)"/>
<path d=""  transform="translate(29335, 840)"/>
<path d=""  transform="translate(29968, 840)"/>
<path d=""  transform="translate(30228, 840)"/>
<path d=""  transform="translate(30861, 840)"/>
<path d=""  transform="translate(31280, 840)"/>
<path d=""  transform="translate(32327, 840)"/>
<path d=""  transform="translate(32746, 840)"/>
<path d=""  transform="translate(33006, 840)"/>
<path d=""  transform="translate(34000, 840)"/>
<path d=""  transform="translate(34607, 840)"/>
<path d=""  transform="translate(34867, 840)"/>
<path d=""  transform="translate(35500, 840)"/>
<path d=""  transform="translate(36473, 840)"/>
<path d=""  transform="translate(36853, 840)"/>
<path d=""  transform="translate(36853, 840)"/>
<path d=""  transform="translate(37113, 840)"/>
<path d=""  transform="translate(37113, 840)"/>
<path d=""  transform="translate(37685, 840)"/>
<path d=""  transform="translate(38257, 840)"/>
<path d=""  transform="translate(38517, 840)"/>
<path d=""  transform="translate(39150, 840)"/>
<path d=""  transform="translate(39783, 840)"/>
<path d=""  transform="translate(40212, 840)"/>
<path d=""  transform="translate(40872, 840)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 41593 2130" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 840)"/>
<path d=""  transform="translate(380, 840)"/>
<path d=""  transform="translate(887, 840)"/>
<path d=""  transform="translate(1147, 840)"/>
<path d=""  transform="translate(1780, 840)"/>
<path d=""  transform="translate(2287, 840)"/>
<path d=""  transform="translate(3053, 840)"/>
<path d=""  transform="translate(3433, 840)"/>
<path d=""  transform="translate(3962, 840)"/>
<path d=""  transform="translate(4222, 840)"/>
<path d=""  transform="translate(4742, 840)"/>
<path d=""  transform="translate(5161, 840)"/>
<path d=""  transform="translate(6134, 840)"/>
<path d=""  transform="translate(6394, 840)"/>
<path d=""  transform="translate(7441, 840)"/>
<path d=""  transform="translate(8391, 840)"/>
<path d=""  transform="translate(8651, 840)"/>
<path d=""  transform="translate(9284, 840)"/>
<path d=""  transform="translate(9944, 840)"/>
<path d=""  transform="translate(10363, 840)"/>
<path d=""  transform="translate(10623, 840)"/>
<path d=""  transform="translate(11255, 840)"/>
<path d=""  transform="translate(11915, 840)"/>
<path d=""  transform="translate(11915, 840)"/>
<path d=""  transform="translate(12175, 840)"/>
<path d=""  transform="translate(12175, 840)"/>
<path d=""  transform="translate(12626, 840)"/>
<path d=""  transform="translate(13673, 840)"/>
<path d=""  transform="translate(14092, 840)"/>
<path d=""  transform="translate(14352, 840)"/>
<path d=""  transform="translate(14985, 840)"/>
<path d=""  transform="translate(15617, 840)"/>
<path d=""  transform="translate(16383, 840)"/>
<path d=""  transform="translate(17060, 840)"/>
<path d=""  transform="translate(18033, 840)"/>
<path d=""  transform="translate(18484, 840)"/>
<path d=""  transform="translate(18744, 840)"/>
<path d=""  transform="translate(19377, 840)"/>
<path d=""  transform="translate(19762, 840)"/>
<path d=""  transform="translate(20468, 840)"/>
<path d=""  transform="translate(20875, 840)"/>
<path d=""  transform="translate(21535, 840)"/>
<path d=""  transform="translate(21795, 840)"/>
<path d=""  transform="translate(22428, 840)"/>
<path d=""  transform="translate(23105, 840)"/>
<path d=""  transform="translate(23534, 840)"/>
<path d=""  transform="translate(24368, 840)"/>
<path d=""  transform="translate(25318, 840)"/>
<path d=""  transform="translate(25578, 840)"/>
<path d=""  transform="translate(25958, 840)"/>
<path d=""  transform="translate(26409, 840)"/>
<path d=""  transform="translate(27359, 840)"/>
<path d=""  transform="translate(28151, 840)"/>
<path d=""  transform="translate(28828, 840)"/>
<path d=""  transform="translate(29335, 840)"/>
<path d=""  transform="translate(29968, 840)"/>
<path d=""  transform="translate(30228, 840)"/>
<path d=""  transform="translate(30861, 840)"/>
<path d=""  transform="translate(31280, 840)"/>
<path d=""  transform="translate(32327, 840)"/>
<path d=""  transform="translate(32746, 840)"/>
<path d=""  transform="translate(33006, 840)"/>
<path d=""  transform="translate(34000, 840)"/>
<path d=""  transform="translate(34607, 840)"/>
<path d=""  transform="translate(34867, 840)"/>
<path d=""  transform="translate(35500, 840)"/>
<path d=""  transform="translate(36473, 840)"/>
<path d=""  transform="translate(36853, 840)"/>
<path d=""  transform="translate(36853, 840)"/>
<path d=""  transform="translate(37113, 840)"/>
<path d=""  transform="translate(37113, 840)"/>
<path d=""  transform="translate(37713, 840)"/>
<path d=""  transform="translate(38313, 840)"/>
<path d=""  transform="translate(38573, 840)"/>
<path d=""  transform="translate(39206, 840)"/>
<path d=""  transform="translate(39839, 840)"/>
<path d=""  transform="translate(40268, 840)"/>
<path d=""  transform="translate(40928, 840)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐫀𐫗𐫢𐫀 𐫇𐫢𐫇𐫓𐫎𐫗𐫀‬ ‫ 𐫖𐫓𐫇𐫀𐫀 17‬ ‫𐫐𐫓 𐫍𐫅 𐫀𐫏𐫤𐫓𐫆 𐫆𐫞𐫇𐫤𐫀 𐫅𐫖𐫡𐫇𐫤𐫀 𐫇𐫅𐫏𐫡𐫤𐫇𐫤𐫀 𐫁𐫗𐫇𐫛𐫢𐫀 𐫏𐫗‬ ‫ 𐫙𐫖</span></li>


<pre>Expected: u10AD6.fina=75+994|u10AD9.init=74+607|space=73+260|space=72+0|space=71+260|space=70+0|u10AD7=69+380|u10ACF=68+507|space=67+260|u10AC0=66+633|u10AE2=65+973|u10ADB=64+922|u10AC7.fina=63+429|u10AD7.init=62+380|u10AC1=61+999|space=60+260|u10AC0=59+633|u10AE4=58+677|u10AC7=57+451|u10AE4=56+677|u10AE1=55+419|u10ACF=54+507|u10AC5=53+419|u10AC7=52+451|space=51+260|u10AC0=50+633|u10AE4=49+677|u10AC7=48+451|u10AE1.fina=47+385|u10AD6.init=46+665|u10AC5=45+419|space=44+260|u10AC0=43+633|u10AE4=42+677|u10AC7.fina=41+429|u10ADE.init=40+834|u10AC6=39+950|space=38+260|u10AC6=37+950|u10AD3=36+792|u10AE4=35+677|u10ACF.fina=34+507|u10AC0.init=33+633|space=32+260|u10AC5.fina=31+385|u10ACD.init=30+624|space=29+260|u10AD3=28+792|u10AD0=27+1047|space=26+0|space=25+260|space=24+0|.notdef=23+600|.notdef=22+600|space=21+260|u10AC0.fina=20+633|u10AC0.init=19+633|u10AC7.fina=18+429|u10AD3.medi=17+660|u10AD6.init=16+665|space=15+260|space=14+0|space=13+260|space=12+0|u10AC0.fina=11+633|u10AD7.init=10+380|u10ACE.fina=9+530|u10AD3.init=8+660|u10AC7=7+451|u10AE2=6+973|u10AC7=5+451|space=4+260|u10AC0=3+633|u10AE2=2+973|u10AD7=1+380|u10AC0=0+633</pre>



<pre>Got     : u10AD6.fina=75+994|u10AD9.init=74+607|space=73+260|space=72+0|space=71+260|space=70+0|u10AD7=69+380|u10ACF=68+507|space=67+260|u10AC0=66+633|u10AE2=65+973|u10ADB=64+922|u10AC7.fina=63+429|u10AD7.init=62+380|u10AC1=61+999|space=60+260|u10AC0=59+633|u10AE4=58+677|u10AC7=57+451|u10AE4=56+677|u10AE1=55+419|u10ACF=54+507|u10AC5=53+419|u10AC7=52+451|space=51+260|u10AC0=50+633|u10AE4=49+677|u10AC7=48+451|u10AE1.fina=47+385|u10AD6.init=46+665|u10AC5=45+419|space=44+260|u10AC0=43+633|u10AE4=42+677|u10AC7.fina=41+429|u10ADE.init=40+834|u10AC6=39+950|space=38+260|u10AC6=37+950|u10AD3=36+792|u10AE4=35+677|u10ACF.fina=34+507|u10AC0.init=33+633|space=32+260|u10AC5.fina=31+385|u10ACD.init=30+624|space=29+260|u10AD3=28+792|u10AD0=27+1047|space=26+0|space=25+260|space=24+0|seven=23+572|one=22+572|space=21+260|u10AC0.fina=20+633|u10AC0.init=19+633|u10AC7.fina=18+429|u10AD3.medi=17+660|u10AD6.init=16+665|space=15+260|space=14+0|space=13+260|space=12+0|u10AC0.fina=11+633|u10AD7.init=10+380|u10ACE.fina=9+530|u10AD3.init=8+660|u10AC7=7+451|u10AE2=6+973|u10AC7=5+451|space=4+260|u10AC0=3+633|u10AE2=2+973|u10AD7=1+380|u10AC0=0+633</pre>



<pre>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         ^^ ^^^ ^^^^^^^^^^^ ^^ +++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 38719 2130" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 840)"/>
<path d=""  transform="translate(994, 840)"/>
<path d=""  transform="translate(1601, 840)"/>
<path d=""  transform="translate(1861, 840)"/>
<path d=""  transform="translate(1861, 840)"/>
<path d=""  transform="translate(2121, 840)"/>
<path d=""  transform="translate(2121, 840)"/>
<path d=""  transform="translate(2501, 840)"/>
<path d=""  transform="translate(3008, 840)"/>
<path d=""  transform="translate(3268, 840)"/>
<path d=""  transform="translate(3901, 840)"/>
<path d=""  transform="translate(4874, 840)"/>
<path d=""  transform="translate(5796, 840)"/>
<path d=""  transform="translate(6225, 840)"/>
<path d=""  transform="translate(6605, 840)"/>
<path d=""  transform="translate(7604, 840)"/>
<path d=""  transform="translate(7864, 840)"/>
<path d=""  transform="translate(8497, 840)"/>
<path d=""  transform="translate(9174, 840)"/>
<path d=""  transform="translate(9625, 840)"/>
<path d=""  transform="translate(10302, 840)"/>
<path d=""  transform="translate(10721, 840)"/>
<path d=""  transform="translate(11228, 840)"/>
<path d=""  transform="translate(11647, 840)"/>
<path d=""  transform="translate(12098, 840)"/>
<path d=""  transform="translate(12358, 840)"/>
<path d=""  transform="translate(12991, 840)"/>
<path d=""  transform="translate(13668, 840)"/>
<path d=""  transform="translate(14119, 840)"/>
<path d=""  transform="translate(14504, 840)"/>
<path d=""  transform="translate(15169, 840)"/>
<path d=""  transform="translate(15588, 840)"/>
<path d=""  transform="translate(15848, 840)"/>
<path d=""  transform="translate(16481, 840)"/>
<path d=""  transform="translate(17158, 840)"/>
<path d=""  transform="translate(17587, 840)"/>
<path d=""  transform="translate(18421, 840)"/>
<path d=""  transform="translate(19371, 840)"/>
<path d=""  transform="translate(19631, 840)"/>
<path d=""  transform="translate(20581, 840)"/>
<path d=""  transform="translate(21373, 840)"/>
<path d=""  transform="translate(22050, 840)"/>
<path d=""  transform="translate(22557, 840)"/>
<path d=""  transform="translate(23190, 840)"/>
<path d=""  transform="translate(23450, 840)"/>
<path d=""  transform="translate(23835, 840)"/>
<path d=""  transform="translate(24459, 840)"/>
<path d=""  transform="translate(24719, 840)"/>
<path d=""  transform="translate(25511, 840)"/>
<path d=""  transform="translate(26558, 840)"/>
<path d=""  transform="translate(26558, 840)"/>
<path d=""  transform="translate(26818, 840)"/>
<path d=""  transform="translate(26818, 840)"/>
<path d=""  transform="translate(27390, 840)"/>
<path d=""  transform="translate(27962, 840)"/>
<path d=""  transform="translate(28222, 840)"/>
<path d=""  transform="translate(28855, 840)"/>
<path d=""  transform="translate(29488, 840)"/>
<path d=""  transform="translate(29917, 840)"/>
<path d=""  transform="translate(30577, 840)"/>
<path d=""  transform="translate(31242, 840)"/>
<path d=""  transform="translate(31502, 840)"/>
<path d=""  transform="translate(31502, 840)"/>
<path d=""  transform="translate(31762, 840)"/>
<path d=""  transform="translate(31762, 840)"/>
<path d=""  transform="translate(32395, 840)"/>
<path d=""  transform="translate(32775, 840)"/>
<path d=""  transform="translate(33305, 840)"/>
<path d=""  transform="translate(33965, 840)"/>
<path d=""  transform="translate(34416, 840)"/>
<path d=""  transform="translate(35389, 840)"/>
<path d=""  transform="translate(35840, 840)"/>
<path d=""  transform="translate(36100, 840)"/>
<path d=""  transform="translate(36733, 840)"/>
<path d=""  transform="translate(37706, 840)"/>
<path d=""  transform="translate(38086, 840)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 38775 2130" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 840)"/>
<path d=""  transform="translate(994, 840)"/>
<path d=""  transform="translate(1601, 840)"/>
<path d=""  transform="translate(1861, 840)"/>
<path d=""  transform="translate(1861, 840)"/>
<path d=""  transform="translate(2121, 840)"/>
<path d=""  transform="translate(2121, 840)"/>
<path d=""  transform="translate(2501, 840)"/>
<path d=""  transform="translate(3008, 840)"/>
<path d=""  transform="translate(3268, 840)"/>
<path d=""  transform="translate(3901, 840)"/>
<path d=""  transform="translate(4874, 840)"/>
<path d=""  transform="translate(5796, 840)"/>
<path d=""  transform="translate(6225, 840)"/>
<path d=""  transform="translate(6605, 840)"/>
<path d=""  transform="translate(7604, 840)"/>
<path d=""  transform="translate(7864, 840)"/>
<path d=""  transform="translate(8497, 840)"/>
<path d=""  transform="translate(9174, 840)"/>
<path d=""  transform="translate(9625, 840)"/>
<path d=""  transform="translate(10302, 840)"/>
<path d=""  transform="translate(10721, 840)"/>
<path d=""  transform="translate(11228, 840)"/>
<path d=""  transform="translate(11647, 840)"/>
<path d=""  transform="translate(12098, 840)"/>
<path d=""  transform="translate(12358, 840)"/>
<path d=""  transform="translate(12991, 840)"/>
<path d=""  transform="translate(13668, 840)"/>
<path d=""  transform="translate(14119, 840)"/>
<path d=""  transform="translate(14504, 840)"/>
<path d=""  transform="translate(15169, 840)"/>
<path d=""  transform="translate(15588, 840)"/>
<path d=""  transform="translate(15848, 840)"/>
<path d=""  transform="translate(16481, 840)"/>
<path d=""  transform="translate(17158, 840)"/>
<path d=""  transform="translate(17587, 840)"/>
<path d=""  transform="translate(18421, 840)"/>
<path d=""  transform="translate(19371, 840)"/>
<path d=""  transform="translate(19631, 840)"/>
<path d=""  transform="translate(20581, 840)"/>
<path d=""  transform="translate(21373, 840)"/>
<path d=""  transform="translate(22050, 840)"/>
<path d=""  transform="translate(22557, 840)"/>
<path d=""  transform="translate(23190, 840)"/>
<path d=""  transform="translate(23450, 840)"/>
<path d=""  transform="translate(23835, 840)"/>
<path d=""  transform="translate(24459, 840)"/>
<path d=""  transform="translate(24719, 840)"/>
<path d=""  transform="translate(25511, 840)"/>
<path d=""  transform="translate(26558, 840)"/>
<path d=""  transform="translate(26558, 840)"/>
<path d=""  transform="translate(26818, 840)"/>
<path d=""  transform="translate(26818, 840)"/>
<path d=""  transform="translate(27418, 840)"/>
<path d=""  transform="translate(28018, 840)"/>
<path d=""  transform="translate(28278, 840)"/>
<path d=""  transform="translate(28911, 840)"/>
<path d=""  transform="translate(29544, 840)"/>
<path d=""  transform="translate(29973, 840)"/>
<path d=""  transform="translate(30633, 840)"/>
<path d=""  transform="translate(31298, 840)"/>
<path d=""  transform="translate(31558, 840)"/>
<path d=""  transform="translate(31558, 840)"/>
<path d=""  transform="translate(31818, 840)"/>
<path d=""  transform="translate(31818, 840)"/>
<path d=""  transform="translate(32451, 840)"/>
<path d=""  transform="translate(32831, 840)"/>
<path d=""  transform="translate(33361, 840)"/>
<path d=""  transform="translate(34021, 840)"/>
<path d=""  transform="translate(34472, 840)"/>
<path d=""  transform="translate(35445, 840)"/>
<path d=""  transform="translate(35896, 840)"/>
<path d=""  transform="translate(36156, 840)"/>
<path d=""  transform="translate(36789, 840)"/>
<path d=""  transform="translate(37762, 840)"/>
<path d=""  transform="translate(38142, 840)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐫀𐫍𐫡𐫗𐫀‬ ‫𐫆𐫐 𐫍𐫅 𐫃𐫡𐫃 𐫓𐫀 𐫛𐫀𐫢 𐫍𐫘𐫏𐫐𐫀 𐫖𐫗 𐫏𐫡𐫤𐫇𐫤𐫀‬ ‫ 𐫖𐫓𐫇𐫀𐫀 18‬ ‫ 𐫐𐫓 𐫍𐫅 𐫀𐫏𐫤𐫓𐫆 𐫆𐫞𐫇𐫤𐫀</span></li>


<pre>Expected: u10AC0=72+633|u10AE4=71+677|u10AC7.fina=70+429|u10ADE.init=69+834|u10AC6=68+950|space=67+260|u10AC6=66+950|u10AD3=65+792|u10AE4=64+677|u10ACF.fina=63+507|u10AC0.init=62+633|space=61+260|u10AC5.fina=60+385|u10ACD.init=59+624|space=58+260|u10AD3=57+792|u10AD0=56+1047|space=55+260|space=54+0|space=53+260|space=52+0|.notdef=51+600|.notdef=50+600|space=49+260|u10AC0.fina=48+633|u10AC0.init=47+633|u10AC7.fina=46+429|u10AD3.medi=45+660|u10AD6.init=44+665|space=43+260|space=42+0|space=41+260|space=40+0|u10AC0=39+633|u10AE4=38+677|u10AC7=37+451|u10AE4=36+677|u10AE1=35+419|u10ACF=34+507|space=33+260|u10AD7=32+380|u10AD6=31+994|space=30+260|u10AC0=29+633|u10AD0=28+1047|u10ACF.fina=27+507|u10AD8.medi=26+766|u10ACD.init=25+624|space=24+260|u10AE2=23+973|u10AC0.fina=22+633|u10ADB.init=21+487|space=20+260|u10AC0.fina=19+633|u10AD3.init=18+660|space=17+260|u10AC3=16+529|u10AE1.fina=15+385|u10AC3.init=14+427|space=13+260|u10AC5.fina=12+385|u10ACD.init=11+624|space=10+260|u10AD0=9+1047|u10AC6=8+950|space=7+0|space=6+260|space=5+0|u10AC0.fina=4+633|u10AD7.init=3+380|u10AE1.fina=2+385|u10ACD.init=1+624|u10AC0=0+633</pre>



<pre>Got     : u10AC0=72+633|u10AE4=71+677|u10AC7.fina=70+429|u10ADE.init=69+834|u10AC6=68+950|space=67+260|u10AC6=66+950|u10AD3=65+792|u10AE4=64+677|u10ACF.fina=63+507|u10AC0.init=62+633|space=61+260|u10AC5.fina=60+385|u10ACD.init=59+624|space=58+260|u10AD3=57+792|u10AD0=56+1047|space=55+260|space=54+0|space=53+260|space=52+0|eight=51+572|one=50+572|space=49+260|u10AC0.fina=48+633|u10AC0.init=47+633|u10AC7.fina=46+429|u10AD3.medi=45+660|u10AD6.init=44+665|space=43+260|space=42+0|space=41+260|space=40+0|u10AC0=39+633|u10AE4=38+677|u10AC7=37+451|u10AE4=36+677|u10AE1=35+419|u10ACF=34+507|space=33+260|u10AD7=32+380|u10AD6=31+994|space=30+260|u10AC0=29+633|u10AD0=28+1047|u10ACF.fina=27+507|u10AD8.medi=26+766|u10ACD.init=25+624|space=24+260|u10AE2=23+973|u10AC0.fina=22+633|u10ADB.init=21+487|space=20+260|u10AC0.fina=19+633|u10AD3.init=18+660|space=17+260|u10AC3=16+529|u10AE1.fina=15+385|u10AC3.init=14+427|space=13+260|u10AC5.fina=12+385|u10ACD.init=11+624|space=10+260|u10AD0=9+1047|u10AC6=8+950|space=7+0|space=6+260|space=5+0|u10AC0.fina=4+633|u10AD7.init=3+380|u10AE1.fina=2+385|u10ACD.init=1+624|u10AC0=0+633</pre>



<pre>                                                                                                                                                                                                                                                                                                                                    ^^ ^^^^^^^^^^^^^^^^^^^^^^^^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 36957 2130" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 840)"/>
<path d=""  transform="translate(633, 840)"/>
<path d=""  transform="translate(1310, 840)"/>
<path d=""  transform="translate(1739, 840)"/>
<path d=""  transform="translate(2573, 840)"/>
<path d=""  transform="translate(3523, 840)"/>
<path d=""  transform="translate(3783, 840)"/>
<path d=""  transform="translate(4733, 840)"/>
<path d=""  transform="translate(5525, 840)"/>
<path d=""  transform="translate(6202, 840)"/>
<path d=""  transform="translate(6709, 840)"/>
<path d=""  transform="translate(7342, 840)"/>
<path d=""  transform="translate(7602, 840)"/>
<path d=""  transform="translate(7987, 840)"/>
<path d=""  transform="translate(8611, 840)"/>
<path d=""  transform="translate(8871, 840)"/>
<path d=""  transform="translate(9663, 840)"/>
<path d=""  transform="translate(10710, 840)"/>
<path d=""  transform="translate(10970, 840)"/>
<path d=""  transform="translate(10970, 840)"/>
<path d=""  transform="translate(11230, 840)"/>
<path d=""  transform="translate(11230, 840)"/>
<path d=""  transform="translate(11802, 840)"/>
<path d=""  transform="translate(12374, 840)"/>
<path d=""  transform="translate(12634, 840)"/>
<path d=""  transform="translate(13267, 840)"/>
<path d=""  transform="translate(13900, 840)"/>
<path d=""  transform="translate(14329, 840)"/>
<path d=""  transform="translate(14989, 840)"/>
<path d=""  transform="translate(15654, 840)"/>
<path d=""  transform="translate(15914, 840)"/>
<path d=""  transform="translate(15914, 840)"/>
<path d=""  transform="translate(16174, 840)"/>
<path d=""  transform="translate(16174, 840)"/>
<path d=""  transform="translate(16807, 840)"/>
<path d=""  transform="translate(17484, 840)"/>
<path d=""  transform="translate(17935, 840)"/>
<path d=""  transform="translate(18612, 840)"/>
<path d=""  transform="translate(19031, 840)"/>
<path d=""  transform="translate(19538, 840)"/>
<path d=""  transform="translate(19798, 840)"/>
<path d=""  transform="translate(20178, 840)"/>
<path d=""  transform="translate(21172, 840)"/>
<path d=""  transform="translate(21432, 840)"/>
<path d=""  transform="translate(22065, 840)"/>
<path d=""  transform="translate(23112, 840)"/>
<path d=""  transform="translate(23619, 840)"/>
<path d=""  transform="translate(24385, 840)"/>
<path d=""  transform="translate(25009, 840)"/>
<path d=""  transform="translate(25269, 840)"/>
<path d=""  transform="translate(26242, 840)"/>
<path d=""  transform="translate(26875, 840)"/>
<path d=""  transform="translate(27362, 840)"/>
<path d=""  transform="translate(27622, 840)"/>
<path d=""  transform="translate(28255, 840)"/>
<path d=""  transform="translate(28915, 840)"/>
<path d=""  transform="translate(29175, 840)"/>
<path d=""  transform="translate(29704, 840)"/>
<path d=""  transform="translate(30089, 840)"/>
<path d=""  transform="translate(30516, 840)"/>
<path d=""  transform="translate(30776, 840)"/>
<path d=""  transform="translate(31161, 840)"/>
<path d=""  transform="translate(31785, 840)"/>
<path d=""  transform="translate(32045, 840)"/>
<path d=""  transform="translate(33092, 840)"/>
<path d=""  transform="translate(34042, 840)"/>
<path d=""  transform="translate(34042, 840)"/>
<path d=""  transform="translate(34302, 840)"/>
<path d=""  transform="translate(34302, 840)"/>
<path d=""  transform="translate(34935, 840)"/>
<path d=""  transform="translate(35315, 840)"/>
<path d=""  transform="translate(35700, 840)"/>
<path d=""  transform="translate(36324, 840)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 37013 2130" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 840)"/>
<path d=""  transform="translate(633, 840)"/>
<path d=""  transform="translate(1310, 840)"/>
<path d=""  transform="translate(1739, 840)"/>
<path d=""  transform="translate(2573, 840)"/>
<path d=""  transform="translate(3523, 840)"/>
<path d=""  transform="translate(3783, 840)"/>
<path d=""  transform="translate(4733, 840)"/>
<path d=""  transform="translate(5525, 840)"/>
<path d=""  transform="translate(6202, 840)"/>
<path d=""  transform="translate(6709, 840)"/>
<path d=""  transform="translate(7342, 840)"/>
<path d=""  transform="translate(7602, 840)"/>
<path d=""  transform="translate(7987, 840)"/>
<path d=""  transform="translate(8611, 840)"/>
<path d=""  transform="translate(8871, 840)"/>
<path d=""  transform="translate(9663, 840)"/>
<path d=""  transform="translate(10710, 840)"/>
<path d=""  transform="translate(10970, 840)"/>
<path d=""  transform="translate(10970, 840)"/>
<path d=""  transform="translate(11230, 840)"/>
<path d=""  transform="translate(11230, 840)"/>
<path d=""  transform="translate(11830, 840)"/>
<path d=""  transform="translate(12430, 840)"/>
<path d=""  transform="translate(12690, 840)"/>
<path d=""  transform="translate(13323, 840)"/>
<path d=""  transform="translate(13956, 840)"/>
<path d=""  transform="translate(14385, 840)"/>
<path d=""  transform="translate(15045, 840)"/>
<path d=""  transform="translate(15710, 840)"/>
<path d=""  transform="translate(15970, 840)"/>
<path d=""  transform="translate(15970, 840)"/>
<path d=""  transform="translate(16230, 840)"/>
<path d=""  transform="translate(16230, 840)"/>
<path d=""  transform="translate(16863, 840)"/>
<path d=""  transform="translate(17540, 840)"/>
<path d=""  transform="translate(17991, 840)"/>
<path d=""  transform="translate(18668, 840)"/>
<path d=""  transform="translate(19087, 840)"/>
<path d=""  transform="translate(19594, 840)"/>
<path d=""  transform="translate(19854, 840)"/>
<path d=""  transform="translate(20234, 840)"/>
<path d=""  transform="translate(21228, 840)"/>
<path d=""  transform="translate(21488, 840)"/>
<path d=""  transform="translate(22121, 840)"/>
<path d=""  transform="translate(23168, 840)"/>
<path d=""  transform="translate(23675, 840)"/>
<path d=""  transform="translate(24441, 840)"/>
<path d=""  transform="translate(25065, 840)"/>
<path d=""  transform="translate(25325, 840)"/>
<path d=""  transform="translate(26298, 840)"/>
<path d=""  transform="translate(26931, 840)"/>
<path d=""  transform="translate(27418, 840)"/>
<path d=""  transform="translate(27678, 840)"/>
<path d=""  transform="translate(28311, 840)"/>
<path d=""  transform="translate(28971, 840)"/>
<path d=""  transform="translate(29231, 840)"/>
<path d=""  transform="translate(29760, 840)"/>
<path d=""  transform="translate(30145, 840)"/>
<path d=""  transform="translate(30572, 840)"/>
<path d=""  transform="translate(30832, 840)"/>
<path d=""  transform="translate(31217, 840)"/>
<path d=""  transform="translate(31841, 840)"/>
<path d=""  transform="translate(32101, 840)"/>
<path d=""  transform="translate(33148, 840)"/>
<path d=""  transform="translate(34098, 840)"/>
<path d=""  transform="translate(34098, 840)"/>
<path d=""  transform="translate(34358, 840)"/>
<path d=""  transform="translate(34358, 840)"/>
<path d=""  transform="translate(34991, 840)"/>
<path d=""  transform="translate(35371, 840)"/>
<path d=""  transform="translate(35756, 840)"/>
<path d=""  transform="translate(36380, 840)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">‫𐫀𐫡𐫇𐫤𐫀 𐫁𐫗𐫇𐫛𐫢𐫀 𐫏𐫗 𐫙𐫖 𐫃𐫇 𐫢𐫇𐫤𐫛𐫇𐫤𐫀 𐫙𐫖 𐫀𐫍𐫡𐫗𐫀‬ ‫ 𐫖𐫓𐫇𐫀𐫀 19‬ ‫ 𐫐𐫓 𐫍𐫅 𐫀𐫏𐫤𐫓𐫆 𐫆𐫞𐫇𐫤𐫀 𐫅𐫡𐫙𐫏𐫗𐫀</span></li>


<pre>Expected: u10AC0.fina=78+633|u10AD7.init=77+380|u10ACF.fina=76+507|u10AD9.init=75+607|u10AE1=74+419|u10AC5=73+419|space=72+260|u10AC0=71+633|u10AE4=70+677|u10AC7.fina=69+429|u10ADE.init=68+834|u10AC6=67+950|space=66+260|u10AC6=65+950|u10AD3=64+792|u10AE4=63+677|u10ACF.fina=62+507|u10AC0.init=61+633|space=60+260|u10AC5.fina=59+385|u10ACD.init=58+624|space=57+260|u10AD3=56+792|u10AD0=55+1047|space=54+260|space=53+0|space=52+260|space=51+0|.notdef=50+600|.notdef=49+600|space=48+260|u10AC0.fina=47+633|u10AC0.init=46+633|u10AC7.fina=45+429|u10AD3.medi=44+660|u10AD6.init=43+665|space=42+260|space=41+0|space=40+260|space=39+0|u10AC0.fina=38+633|u10AD7.init=37+380|u10AE1.fina=36+385|u10ACD.init=35+624|u10AC0=34+633|space=33+260|u10AD6.fina=32+994|u10AD9.init=31+607|space=30+260|u10AC0=29+633|u10AE4=28+677|u10AC7.fina=27+429|u10ADB.init=26+487|u10AE4=25+677|u10AC7=24+451|u10AE2=23+973|space=22+260|u10AC7.fina=21+429|u10AC3.init=20+427|space=19+260|u10AD6.fina=18+994|u10AD9.init=17+607|space=16+260|u10AD7=15+380|u10ACF=14+507|space=13+260|u10AC0=12+633|u10AE2=11+973|u10ADB=10+922|u10AC7.fina=9+429|u10AD7.init=8+380|u10AC1=7+999|space=6+260|u10AC0=5+633|u10AE4=4+677|u10AC7=3+451|u10AE1.fina=2+385|u10AC0.init=1+633|space=0+0</pre>



<pre>Got     : u10AC0.fina=78+633|u10AD7.init=77+380|u10ACF.fina=76+507|u10AD9.init=75+607|u10AE1=74+419|u10AC5=73+419|space=72+260|u10AC0=71+633|u10AE4=70+677|u10AC7.fina=69+429|u10ADE.init=68+834|u10AC6=67+950|space=66+260|u10AC6=65+950|u10AD3=64+792|u10AE4=63+677|u10ACF.fina=62+507|u10AC0.init=61+633|space=60+260|u10AC5.fina=59+385|u10ACD.init=58+624|space=57+260|u10AD3=56+792|u10AD0=55+1047|space=54+260|space=53+0|space=52+260|space=51+0|nine=50+572|one=49+572|space=48+260|u10AC0.fina=47+633|u10AC0.init=46+633|u10AC7.fina=45+429|u10AD3.medi=44+660|u10AD6.init=43+665|space=42+260|space=41+0|space=40+260|space=39+0|u10AC0.fina=38+633|u10AD7.init=37+380|u10AE1.fina=36+385|u10ACD.init=35+624|u10AC0=34+633|space=33+260|u10AD6.fina=32+994|u10AD9.init=31+607|space=30+260|u10AC0=29+633|u10AE4=28+677|u10AC7.fina=27+429|u10ADB.init=26+487|u10AE4=25+677|u10AC7=24+451|u10AE2=23+973|space=22+260|u10AC7.fina=21+429|u10AC3.init=20+427|space=19+260|u10AD6.fina=18+994|u10AD9.init=17+607|space=16+260|u10AD7=15+380|u10ACF=14+507|space=13+260|u10AC0=12+633|u10AE2=11+973|u10ADB=10+922|u10AC7.fina=9+429|u10AD7.init=8+380|u10AC1=7+999|space=6+260|u10AC0=5+633|u10AE4=4+677|u10AC7=3+451|u10AE1.fina=2+385|u10AC0.init=1+633|space=0+0</pre>



<pre>                                                                                                                                                                                                                                                                                                                                                                                                                                                         ^^ ^^^^^^^^^^^^^^^^^^^^^^^^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 40261 2130" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 840)"/>
<path d=""  transform="translate(633, 840)"/>
<path d=""  transform="translate(1013, 840)"/>
<path d=""  transform="translate(1520, 840)"/>
<path d=""  transform="translate(2127, 840)"/>
<path d=""  transform="translate(2546, 840)"/>
<path d=""  transform="translate(2965, 840)"/>
<path d=""  transform="translate(3225, 840)"/>
<path d=""  transform="translate(3858, 840)"/>
<path d=""  transform="translate(4535, 840)"/>
<path d=""  transform="translate(4964, 840)"/>
<path d=""  transform="translate(5798, 840)"/>
<path d=""  transform="translate(6748, 840)"/>
<path d=""  transform="translate(7008, 840)"/>
<path d=""  transform="translate(7958, 840)"/>
<path d=""  transform="translate(8750, 840)"/>
<path d=""  transform="translate(9427, 840)"/>
<path d=""  transform="translate(9934, 840)"/>
<path d=""  transform="translate(10567, 840)"/>
<path d=""  transform="translate(10827, 840)"/>
<path d=""  transform="translate(11212, 840)"/>
<path d=""  transform="translate(11836, 840)"/>
<path d=""  transform="translate(12096, 840)"/>
<path d=""  transform="translate(12888, 840)"/>
<path d=""  transform="translate(13935, 840)"/>
<path d=""  transform="translate(14195, 840)"/>
<path d=""  transform="translate(14195, 840)"/>
<path d=""  transform="translate(14455, 840)"/>
<path d=""  transform="translate(14455, 840)"/>
<path d=""  transform="translate(15027, 840)"/>
<path d=""  transform="translate(15599, 840)"/>
<path d=""  transform="translate(15859, 840)"/>
<path d=""  transform="translate(16492, 840)"/>
<path d=""  transform="translate(17125, 840)"/>
<path d=""  transform="translate(17554, 840)"/>
<path d=""  transform="translate(18214, 840)"/>
<path d=""  transform="translate(18879, 840)"/>
<path d=""  transform="translate(19139, 840)"/>
<path d=""  transform="translate(19139, 840)"/>
<path d=""  transform="translate(19399, 840)"/>
<path d=""  transform="translate(19399, 840)"/>
<path d=""  transform="translate(20032, 840)"/>
<path d=""  transform="translate(20412, 840)"/>
<path d=""  transform="translate(20797, 840)"/>
<path d=""  transform="translate(21421, 840)"/>
<path d=""  transform="translate(22054, 840)"/>
<path d=""  transform="translate(22314, 840)"/>
<path d=""  transform="translate(23308, 840)"/>
<path d=""  transform="translate(23915, 840)"/>
<path d=""  transform="translate(24175, 840)"/>
<path d=""  transform="translate(24808, 840)"/>
<path d=""  transform="translate(25485, 840)"/>
<path d=""  transform="translate(25914, 840)"/>
<path d=""  transform="translate(26401, 840)"/>
<path d=""  transform="translate(27078, 840)"/>
<path d=""  transform="translate(27529, 840)"/>
<path d=""  transform="translate(28502, 840)"/>
<path d=""  transform="translate(28762, 840)"/>
<path d=""  transform="translate(29191, 840)"/>
<path d=""  transform="translate(29618, 840)"/>
<path d=""  transform="translate(29878, 840)"/>
<path d=""  transform="translate(30872, 840)"/>
<path d=""  transform="translate(31479, 840)"/>
<path d=""  transform="translate(31739, 840)"/>
<path d=""  transform="translate(32119, 840)"/>
<path d=""  transform="translate(32626, 840)"/>
<path d=""  transform="translate(32886, 840)"/>
<path d=""  transform="translate(33519, 840)"/>
<path d=""  transform="translate(34492, 840)"/>
<path d=""  transform="translate(35414, 840)"/>
<path d=""  transform="translate(35843, 840)"/>
<path d=""  transform="translate(36223, 840)"/>
<path d=""  transform="translate(37222, 840)"/>
<path d=""  transform="translate(37482, 840)"/>
<path d=""  transform="translate(38115, 840)"/>
<path d=""  transform="translate(38792, 840)"/>
<path d=""  transform="translate(39243, 840)"/>
<path d=""  transform="translate(39628, 840)"/>
<path d=""  transform="translate(40261, 840)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 40317 2130" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 840)"/>
<path d=""  transform="translate(633, 840)"/>
<path d=""  transform="translate(1013, 840)"/>
<path d=""  transform="translate(1520, 840)"/>
<path d=""  transform="translate(2127, 840)"/>
<path d=""  transform="translate(2546, 840)"/>
<path d=""  transform="translate(2965, 840)"/>
<path d=""  transform="translate(3225, 840)"/>
<path d=""  transform="translate(3858, 840)"/>
<path d=""  transform="translate(4535, 840)"/>
<path d=""  transform="translate(4964, 840)"/>
<path d=""  transform="translate(5798, 840)"/>
<path d=""  transform="translate(6748, 840)"/>
<path d=""  transform="translate(7008, 840)"/>
<path d=""  transform="translate(7958, 840)"/>
<path d=""  transform="translate(8750, 840)"/>
<path d=""  transform="translate(9427, 840)"/>
<path d=""  transform="translate(9934, 840)"/>
<path d=""  transform="translate(10567, 840)"/>
<path d=""  transform="translate(10827, 840)"/>
<path d=""  transform="translate(11212, 840)"/>
<path d=""  transform="translate(11836, 840)"/>
<path d=""  transform="translate(12096, 840)"/>
<path d=""  transform="translate(12888, 840)"/>
<path d=""  transform="translate(13935, 840)"/>
<path d=""  transform="translate(14195, 840)"/>
<path d=""  transform="translate(14195, 840)"/>
<path d=""  transform="translate(14455, 840)"/>
<path d=""  transform="translate(14455, 840)"/>
<path d=""  transform="translate(15055, 840)"/>
<path d=""  transform="translate(15655, 840)"/>
<path d=""  transform="translate(15915, 840)"/>
<path d=""  transform="translate(16548, 840)"/>
<path d=""  transform="translate(17181, 840)"/>
<path d=""  transform="translate(17610, 840)"/>
<path d=""  transform="translate(18270, 840)"/>
<path d=""  transform="translate(18935, 840)"/>
<path d=""  transform="translate(19195, 840)"/>
<path d=""  transform="translate(19195, 840)"/>
<path d=""  transform="translate(19455, 840)"/>
<path d=""  transform="translate(19455, 840)"/>
<path d=""  transform="translate(20088, 840)"/>
<path d=""  transform="translate(20468, 840)"/>
<path d=""  transform="translate(20853, 840)"/>
<path d=""  transform="translate(21477, 840)"/>
<path d=""  transform="translate(22110, 840)"/>
<path d=""  transform="translate(22370, 840)"/>
<path d=""  transform="translate(23364, 840)"/>
<path d=""  transform="translate(23971, 840)"/>
<path d=""  transform="translate(24231, 840)"/>
<path d=""  transform="translate(24864, 840)"/>
<path d=""  transform="translate(25541, 840)"/>
<path d=""  transform="translate(25970, 840)"/>
<path d=""  transform="translate(26457, 840)"/>
<path d=""  transform="translate(27134, 840)"/>
<path d=""  transform="translate(27585, 840)"/>
<path d=""  transform="translate(28558, 840)"/>
<path d=""  transform="translate(28818, 840)"/>
<path d=""  transform="translate(29247, 840)"/>
<path d=""  transform="translate(29674, 840)"/>
<path d=""  transform="translate(29934, 840)"/>
<path d=""  transform="translate(30928, 840)"/>
<path d=""  transform="translate(31535, 840)"/>
<path d=""  transform="translate(31795, 840)"/>
<path d=""  transform="translate(32175, 840)"/>
<path d=""  transform="translate(32682, 840)"/>
<path d=""  transform="translate(32942, 840)"/>
<path d=""  transform="translate(33575, 840)"/>
<path d=""  transform="translate(34548, 840)"/>
<path d=""  transform="translate(35470, 840)"/>
<path d=""  transform="translate(35899, 840)"/>
<path d=""  transform="translate(36279, 840)"/>
<path d=""  transform="translate(37278, 840)"/>
<path d=""  transform="translate(37538, 840)"/>
<path d=""  transform="translate(38171, 840)"/>
<path d=""  transform="translate(38848, 840)"/>
<path d=""  transform="translate(39299, 840)"/>
<path d=""  transform="translate(39684, 840)"/>
<path d=""  transform="translate(40317, 840)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐫁𐫤𐫡 𐫇𐫞𐫁𐫓𐫤𐫀 𐫖𐫅𐫙𐫗𐫇𐫤𐫀 𐫁𐫐𐫓 𐫀𐫇𐫡𐫍𐫀 𐫅𐫆𐫇𐫏𐫀 𐫅𐫓𐫀 𐫞𐫏𐫅𐫀 𐫅𐫤𐫍‬ ‫𐫇𐫁𐫀‬ ‫ 𐫖𐫓𐫇𐫀𐫀 20‬ ‫𐫐𐫓 𐫍𐫅 𐫀𐫏𐫤𐫓𐫆</span></li>


<pre>Expected: u10AC6=78+950|u10AD3=77+792|u10AE4=76+677|u10ACF.fina=75+507|u10AC0.init=74+633|space=73+260|u10AC5.fina=72+385|u10ACD.init=71+624|space=70+260|u10AD3=69+792|u10AD0=68+1047|space=67+0|space=66+260|space=65+0|.notdef=64+600|.notdef=63+600|space=62+260|u10AC0.fina=61+633|u10AC0.init=60+633|u10AC7.fina=59+429|u10AD3.medi=58+660|u10AD6.init=57+665|space=56+260|space=55+0|space=54+260|space=53+0|u10AC0.fina=52+633|u10AC1.init=51+706|u10AC7=50+451|space=49+0|space=48+260|space=47+0|u10ACD=46+686|u10AE4=45+677|u10AC5=44+419|space=43+260|u10AC0=42+633|u10AC5=41+419|u10ACF.fina=40+507|u10ADE.init=39+834|space=38+260|u10AC0.fina=37+633|u10AD3.init=36+660|u10AC5=35+419|space=34+260|u10AC0=33+633|u10ACF=32+507|u10AC7=31+451|u10AC6=30+950|u10AC5=29+419|space=28+260|u10AC0.fina=27+633|u10ACD.init=26+624|u10AE1=25+419|u10AC7.fina=24+429|u10AC0.init=23+633|space=22+260|u10AD3=21+792|u10AD0.fina=20+1047|u10AC1.init=19+706|space=18+260|u10AC0=17+633|u10AE4=16+677|u10AC7.fina=15+429|u10AD7.init=14+380|u10AD9=13+964|u10AC5.fina=12+385|u10AD6.init=11+665|space=10+260|u10AC0=9+633|u10AE4.fina=8+632|u10AD3.medi=7+660|u10AC1.medi=6+706|u10ADE.init=5+834|u10AC7=4+451|space=3+260|u10AE1=2+419|u10AE4.fina=1+632|u10AC1.init=0+706</pre>



<pre>Got     : u10AC6=78+950|u10AD3=77+792|u10AE4=76+677|u10ACF.fina=75+507|u10AC0.init=74+633|space=73+260|u10AC5.fina=72+385|u10ACD.init=71+624|space=70+260|u10AD3=69+792|u10AD0=68+1047|space=67+0|space=66+260|space=65+0|zero=64+572|two=63+572|space=62+260|u10AC0.fina=61+633|u10AC0.init=60+633|u10AC7.fina=59+429|u10AD3.medi=58+660|u10AD6.init=57+665|space=56+260|space=55+0|space=54+260|space=53+0|u10AC0.fina=52+633|u10AC1.init=51+706|u10AC7=50+451|space=49+0|space=48+260|space=47+0|u10ACD=46+686|u10AE4=45+677|u10AC5=44+419|space=43+260|u10AC0=42+633|u10AC5=41+419|u10ACF.fina=40+507|u10ADE.init=39+834|space=38+260|u10AC0.fina=37+633|u10AD3.init=36+660|u10AC5=35+419|space=34+260|u10AC0=33+633|u10ACF=32+507|u10AC7=31+451|u10AC6=30+950|u10AC5=29+419|space=28+260|u10AC0.fina=27+633|u10ACD.init=26+624|u10AE1=25+419|u10AC7.fina=24+429|u10AC0.init=23+633|space=22+260|u10AD3=21+792|u10AD0.fina=20+1047|u10AC1.init=19+706|space=18+260|u10AC0=17+633|u10AE4=16+677|u10AC7.fina=15+429|u10AD7.init=14+380|u10AD9=13+964|u10AC5.fina=12+385|u10AD6.init=11+665|space=10+260|u10AC0=9+633|u10AE4.fina=8+632|u10AD3.medi=7+660|u10AC1.medi=6+706|u10ADE.init=5+834|u10AC7=4+451|space=3+260|u10AE1=2+419|u10AE4.fina=1+632|u10AC1.init=0+706</pre>



<pre>                                                                                                                                                                                                                          ^^ ^^^^^^^^^^^^^^ ^^^^^^^^^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 40197 2130" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 840)"/>
<path d=""  transform="translate(950, 840)"/>
<path d=""  transform="translate(1742, 840)"/>
<path d=""  transform="translate(2419, 840)"/>
<path d=""  transform="translate(2926, 840)"/>
<path d=""  transform="translate(3559, 840)"/>
<path d=""  transform="translate(3819, 840)"/>
<path d=""  transform="translate(4204, 840)"/>
<path d=""  transform="translate(4828, 840)"/>
<path d=""  transform="translate(5088, 840)"/>
<path d=""  transform="translate(5880, 840)"/>
<path d=""  transform="translate(6927, 840)"/>
<path d=""  transform="translate(6927, 840)"/>
<path d=""  transform="translate(7187, 840)"/>
<path d=""  transform="translate(7187, 840)"/>
<path d=""  transform="translate(7759, 840)"/>
<path d=""  transform="translate(8331, 840)"/>
<path d=""  transform="translate(8591, 840)"/>
<path d=""  transform="translate(9224, 840)"/>
<path d=""  transform="translate(9857, 840)"/>
<path d=""  transform="translate(10286, 840)"/>
<path d=""  transform="translate(10946, 840)"/>
<path d=""  transform="translate(11611, 840)"/>
<path d=""  transform="translate(11871, 840)"/>
<path d=""  transform="translate(11871, 840)"/>
<path d=""  transform="translate(12131, 840)"/>
<path d=""  transform="translate(12131, 840)"/>
<path d=""  transform="translate(12764, 840)"/>
<path d=""  transform="translate(13470, 840)"/>
<path d=""  transform="translate(13921, 840)"/>
<path d=""  transform="translate(13921, 840)"/>
<path d=""  transform="translate(14181, 840)"/>
<path d=""  transform="translate(14181, 840)"/>
<path d=""  transform="translate(14867, 840)"/>
<path d=""  transform="translate(15544, 840)"/>
<path d=""  transform="translate(15963, 840)"/>
<path d=""  transform="translate(16223, 840)"/>
<path d=""  transform="translate(16856, 840)"/>
<path d=""  transform="translate(17275, 840)"/>
<path d=""  transform="translate(17782, 840)"/>
<path d=""  transform="translate(18616, 840)"/>
<path d=""  transform="translate(18876, 840)"/>
<path d=""  transform="translate(19509, 840)"/>
<path d=""  transform="translate(20169, 840)"/>
<path d=""  transform="translate(20588, 840)"/>
<path d=""  transform="translate(20848, 840)"/>
<path d=""  transform="translate(21481, 840)"/>
<path d=""  transform="translate(21988, 840)"/>
<path d=""  transform="translate(22439, 840)"/>
<path d=""  transform="translate(23389, 840)"/>
<path d=""  transform="translate(23808, 840)"/>
<path d=""  transform="translate(24068, 840)"/>
<path d=""  transform="translate(24701, 840)"/>
<path d=""  transform="translate(25325, 840)"/>
<path d=""  transform="translate(25744, 840)"/>
<path d=""  transform="translate(26173, 840)"/>
<path d=""  transform="translate(26806, 840)"/>
<path d=""  transform="translate(27066, 840)"/>
<path d=""  transform="translate(27858, 840)"/>
<path d=""  transform="translate(28905, 840)"/>
<path d=""  transform="translate(29611, 840)"/>
<path d=""  transform="translate(29871, 840)"/>
<path d=""  transform="translate(30504, 840)"/>
<path d=""  transform="translate(31181, 840)"/>
<path d=""  transform="translate(31610, 840)"/>
<path d=""  transform="translate(31990, 840)"/>
<path d=""  transform="translate(32954, 840)"/>
<path d=""  transform="translate(33339, 840)"/>
<path d=""  transform="translate(34004, 840)"/>
<path d=""  transform="translate(34264, 840)"/>
<path d=""  transform="translate(34897, 840)"/>
<path d=""  transform="translate(35529, 840)"/>
<path d=""  transform="translate(36189, 840)"/>
<path d=""  transform="translate(36895, 840)"/>
<path d=""  transform="translate(37729, 840)"/>
<path d=""  transform="translate(38180, 840)"/>
<path d=""  transform="translate(38440, 840)"/>
<path d=""  transform="translate(38859, 840)"/>
<path d=""  transform="translate(39491, 840)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 40253 2130" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 840)"/>
<path d=""  transform="translate(950, 840)"/>
<path d=""  transform="translate(1742, 840)"/>
<path d=""  transform="translate(2419, 840)"/>
<path d=""  transform="translate(2926, 840)"/>
<path d=""  transform="translate(3559, 840)"/>
<path d=""  transform="translate(3819, 840)"/>
<path d=""  transform="translate(4204, 840)"/>
<path d=""  transform="translate(4828, 840)"/>
<path d=""  transform="translate(5088, 840)"/>
<path d=""  transform="translate(5880, 840)"/>
<path d=""  transform="translate(6927, 840)"/>
<path d=""  transform="translate(6927, 840)"/>
<path d=""  transform="translate(7187, 840)"/>
<path d=""  transform="translate(7187, 840)"/>
<path d=""  transform="translate(7787, 840)"/>
<path d=""  transform="translate(8387, 840)"/>
<path d=""  transform="translate(8647, 840)"/>
<path d=""  transform="translate(9280, 840)"/>
<path d=""  transform="translate(9913, 840)"/>
<path d=""  transform="translate(10342, 840)"/>
<path d=""  transform="translate(11002, 840)"/>
<path d=""  transform="translate(11667, 840)"/>
<path d=""  transform="translate(11927, 840)"/>
<path d=""  transform="translate(11927, 840)"/>
<path d=""  transform="translate(12187, 840)"/>
<path d=""  transform="translate(12187, 840)"/>
<path d=""  transform="translate(12820, 840)"/>
<path d=""  transform="translate(13526, 840)"/>
<path d=""  transform="translate(13977, 840)"/>
<path d=""  transform="translate(13977, 840)"/>
<path d=""  transform="translate(14237, 840)"/>
<path d=""  transform="translate(14237, 840)"/>
<path d=""  transform="translate(14923, 840)"/>
<path d=""  transform="translate(15600, 840)"/>
<path d=""  transform="translate(16019, 840)"/>
<path d=""  transform="translate(16279, 840)"/>
<path d=""  transform="translate(16912, 840)"/>
<path d=""  transform="translate(17331, 840)"/>
<path d=""  transform="translate(17838, 840)"/>
<path d=""  transform="translate(18672, 840)"/>
<path d=""  transform="translate(18932, 840)"/>
<path d=""  transform="translate(19565, 840)"/>
<path d=""  transform="translate(20225, 840)"/>
<path d=""  transform="translate(20644, 840)"/>
<path d=""  transform="translate(20904, 840)"/>
<path d=""  transform="translate(21537, 840)"/>
<path d=""  transform="translate(22044, 840)"/>
<path d=""  transform="translate(22495, 840)"/>
<path d=""  transform="translate(23445, 840)"/>
<path d=""  transform="translate(23864, 840)"/>
<path d=""  transform="translate(24124, 840)"/>
<path d=""  transform="translate(24757, 840)"/>
<path d=""  transform="translate(25381, 840)"/>
<path d=""  transform="translate(25800, 840)"/>
<path d=""  transform="translate(26229, 840)"/>
<path d=""  transform="translate(26862, 840)"/>
<path d=""  transform="translate(27122, 840)"/>
<path d=""  transform="translate(27914, 840)"/>
<path d=""  transform="translate(28961, 840)"/>
<path d=""  transform="translate(29667, 840)"/>
<path d=""  transform="translate(29927, 840)"/>
<path d=""  transform="translate(30560, 840)"/>
<path d=""  transform="translate(31237, 840)"/>
<path d=""  transform="translate(31666, 840)"/>
<path d=""  transform="translate(32046, 840)"/>
<path d=""  transform="translate(33010, 840)"/>
<path d=""  transform="translate(33395, 840)"/>
<path d=""  transform="translate(34060, 840)"/>
<path d=""  transform="translate(34320, 840)"/>
<path d=""  transform="translate(34953, 840)"/>
<path d=""  transform="translate(35585, 840)"/>
<path d=""  transform="translate(36245, 840)"/>
<path d=""  transform="translate(36951, 840)"/>
<path d=""  transform="translate(37785, 840)"/>
<path d=""  transform="translate(38236, 840)"/>
<path d=""  transform="translate(38496, 840)"/>
<path d=""  transform="translate(38915, 840)"/>
<path d=""  transform="translate(39547, 840)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐫐𐫗𐫇𐫢𐫗𐫀‬ ‫ 𐫖𐫓𐫇𐫀𐫀 21‬ ‫𐫐𐫓 𐫍𐫅 𐫀𐫏𐫤𐫓𐫆 𐫆𐫞𐫇𐫤𐫀 𐫓𐫖𐫢𐫤𐫇𐫛𐫀 𐫃𐫇 𐫢𐫇𐫓𐫎𐫗𐫀 𐫅𐫀𐫤𐫡𐫀 𐫅‬ ‫𐫇𐫉𐫀 𐫅𐫇𐫉 𐫏𐫗</span></li>


<pre>Expected: u10AD7=76+380|u10ACF=75+507|space=74+260|u10AC9=73+493|u10AC7=72+451|u10AC5=71+419|space=70+260|u10AC0=69+633|u10AC9=68+493|u10AC7=67+451|space=66+0|space=65+260|space=64+0|u10AC5=63+419|space=62+260|u10AC0=61+633|u10AE1=60+419|u10AE4.fina=59+632|u10AC0.init=58+633|u10AC5=57+419|space=56+260|u10AC0.fina=55+633|u10AD7.init=54+380|u10ACE.fina=53+530|u10AD3.init=52+660|u10AC7=51+451|u10AE2=50+973|space=49+260|u10AC7.fina=48+429|u10AC3.init=47+427|space=46+260|u10AC0.fina=45+633|u10ADB.init=44+487|u10AC7=43+451|u10AE4=42+677|u10AE2=41+973|u10AD6.fina=40+994|u10AD3.init=39+660|space=38+260|u10AC0=37+633|u10AE4=36+677|u10AC7.fina=35+429|u10ADE.init=34+834|u10AC6=33+950|space=32+260|u10AC6=31+950|u10AD3=30+792|u10AE4=29+677|u10ACF.fina=28+507|u10AC0.init=27+633|space=26+260|u10AC5.fina=25+385|u10ACD.init=24+624|space=23+260|u10AD3=22+792|u10AD0=21+1047|space=20+0|space=19+260|space=18+0|.notdef=17+600|.notdef=16+600|space=15+260|u10AC0.fina=14+633|u10AC0.init=13+633|u10AC7.fina=12+429|u10AD3.medi=11+660|u10AD6.init=10+665|space=9+260|space=8+0|space=7+260|space=6+0|u10AC0.fina=5+633|u10AD7.init=4+380|u10AE2=3+973|u10AC7.fina=2+429|u10AD7.init=1+380|u10AD0=0+1047</pre>



<pre>Got     : u10AD7=76+380|u10ACF=75+507|space=74+260|u10AC9=73+493|u10AC7=72+451|u10AC5=71+419|space=70+260|u10AC0=69+633|u10AC9=68+493|u10AC7=67+451|space=66+0|space=65+260|space=64+0|u10AC5=63+419|space=62+260|u10AC0=61+633|u10AE1=60+419|u10AE4.fina=59+632|u10AC0.init=58+633|u10AC5=57+419|space=56+260|u10AC0.fina=55+633|u10AD7.init=54+380|u10ACE.fina=53+530|u10AD3.init=52+660|u10AC7=51+451|u10AE2=50+973|space=49+260|u10AC7.fina=48+429|u10AC3.init=47+427|space=46+260|u10AC0.fina=45+633|u10ADB.init=44+487|u10AC7=43+451|u10AE4=42+677|u10AE2=41+973|u10AD6.fina=40+994|u10AD3.init=39+660|space=38+260|u10AC0=37+633|u10AE4=36+677|u10AC7.fina=35+429|u10ADE.init=34+834|u10AC6=33+950|space=32+260|u10AC6=31+950|u10AD3=30+792|u10AE4=29+677|u10ACF.fina=28+507|u10AC0.init=27+633|space=26+260|u10AC5.fina=25+385|u10ACD.init=24+624|space=23+260|u10AD3=22+792|u10AD0=21+1047|space=20+0|space=19+260|space=18+0|one=17+572|two=16+572|space=15+260|u10AC0.fina=14+633|u10AC0.init=13+633|u10AC7.fina=12+429|u10AD3.medi=11+660|u10AD6.init=10+665|space=9+260|space=8+0|space=7+260|space=6+0|u10AC0.fina=5+633|u10AD7.init=4+380|u10AE2=3+973|u10AC7.fina=2+429|u10AD7.init=1+380|u10AD0=0+1047</pre>



<pre>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       ++ ^^^^^^^^^^^^^^ ^^^^^^^^^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 38176 2130" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 840)"/>
<path d=""  transform="translate(380, 840)"/>
<path d=""  transform="translate(887, 840)"/>
<path d=""  transform="translate(1147, 840)"/>
<path d=""  transform="translate(1640, 840)"/>
<path d=""  transform="translate(2091, 840)"/>
<path d=""  transform="translate(2510, 840)"/>
<path d=""  transform="translate(2770, 840)"/>
<path d=""  transform="translate(3403, 840)"/>
<path d=""  transform="translate(3896, 840)"/>
<path d=""  transform="translate(4347, 840)"/>
<path d=""  transform="translate(4347, 840)"/>
<path d=""  transform="translate(4607, 840)"/>
<path d=""  transform="translate(4607, 840)"/>
<path d=""  transform="translate(5026, 840)"/>
<path d=""  transform="translate(5286, 840)"/>
<path d=""  transform="translate(5919, 840)"/>
<path d=""  transform="translate(6338, 840)"/>
<path d=""  transform="translate(6970, 840)"/>
<path d=""  transform="translate(7603, 840)"/>
<path d=""  transform="translate(8022, 840)"/>
<path d=""  transform="translate(8282, 840)"/>
<path d=""  transform="translate(8915, 840)"/>
<path d=""  transform="translate(9295, 840)"/>
<path d=""  transform="translate(9825, 840)"/>
<path d=""  transform="translate(10485, 840)"/>
<path d=""  transform="translate(10936, 840)"/>
<path d=""  transform="translate(11909, 840)"/>
<path d=""  transform="translate(12169, 840)"/>
<path d=""  transform="translate(12598, 840)"/>
<path d=""  transform="translate(13025, 840)"/>
<path d=""  transform="translate(13285, 840)"/>
<path d=""  transform="translate(13918, 840)"/>
<path d=""  transform="translate(14405, 840)"/>
<path d=""  transform="translate(14856, 840)"/>
<path d=""  transform="translate(15533, 840)"/>
<path d=""  transform="translate(16506, 840)"/>
<path d=""  transform="translate(17500, 840)"/>
<path d=""  transform="translate(18160, 840)"/>
<path d=""  transform="translate(18420, 840)"/>
<path d=""  transform="translate(19053, 840)"/>
<path d=""  transform="translate(19730, 840)"/>
<path d=""  transform="translate(20159, 840)"/>
<path d=""  transform="translate(20993, 840)"/>
<path d=""  transform="translate(21943, 840)"/>
<path d=""  transform="translate(22203, 840)"/>
<path d=""  transform="translate(23153, 840)"/>
<path d=""  transform="translate(23945, 840)"/>
<path d=""  transform="translate(24622, 840)"/>
<path d=""  transform="translate(25129, 840)"/>
<path d=""  transform="translate(25762, 840)"/>
<path d=""  transform="translate(26022, 840)"/>
<path d=""  transform="translate(26407, 840)"/>
<path d=""  transform="translate(27031, 840)"/>
<path d=""  transform="translate(27291, 840)"/>
<path d=""  transform="translate(28083, 840)"/>
<path d=""  transform="translate(29130, 840)"/>
<path d=""  transform="translate(29130, 840)"/>
<path d=""  transform="translate(29390, 840)"/>
<path d=""  transform="translate(29390, 840)"/>
<path d=""  transform="translate(29962, 840)"/>
<path d=""  transform="translate(30534, 840)"/>
<path d=""  transform="translate(30794, 840)"/>
<path d=""  transform="translate(31427, 840)"/>
<path d=""  transform="translate(32060, 840)"/>
<path d=""  transform="translate(32489, 840)"/>
<path d=""  transform="translate(33149, 840)"/>
<path d=""  transform="translate(33814, 840)"/>
<path d=""  transform="translate(34074, 840)"/>
<path d=""  transform="translate(34074, 840)"/>
<path d=""  transform="translate(34334, 840)"/>
<path d=""  transform="translate(34334, 840)"/>
<path d=""  transform="translate(34967, 840)"/>
<path d=""  transform="translate(35347, 840)"/>
<path d=""  transform="translate(36320, 840)"/>
<path d=""  transform="translate(36749, 840)"/>
<path d=""  transform="translate(37129, 840)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 38232 2130" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 840)"/>
<path d=""  transform="translate(380, 840)"/>
<path d=""  transform="translate(887, 840)"/>
<path d=""  transform="translate(1147, 840)"/>
<path d=""  transform="translate(1640, 840)"/>
<path d=""  transform="translate(2091, 840)"/>
<path d=""  transform="translate(2510, 840)"/>
<path d=""  transform="translate(2770, 840)"/>
<path d=""  transform="translate(3403, 840)"/>
<path d=""  transform="translate(3896, 840)"/>
<path d=""  transform="translate(4347, 840)"/>
<path d=""  transform="translate(4347, 840)"/>
<path d=""  transform="translate(4607, 840)"/>
<path d=""  transform="translate(4607, 840)"/>
<path d=""  transform="translate(5026, 840)"/>
<path d=""  transform="translate(5286, 840)"/>
<path d=""  transform="translate(5919, 840)"/>
<path d=""  transform="translate(6338, 840)"/>
<path d=""  transform="translate(6970, 840)"/>
<path d=""  transform="translate(7603, 840)"/>
<path d=""  transform="translate(8022, 840)"/>
<path d=""  transform="translate(8282, 840)"/>
<path d=""  transform="translate(8915, 840)"/>
<path d=""  transform="translate(9295, 840)"/>
<path d=""  transform="translate(9825, 840)"/>
<path d=""  transform="translate(10485, 840)"/>
<path d=""  transform="translate(10936, 840)"/>
<path d=""  transform="translate(11909, 840)"/>
<path d=""  transform="translate(12169, 840)"/>
<path d=""  transform="translate(12598, 840)"/>
<path d=""  transform="translate(13025, 840)"/>
<path d=""  transform="translate(13285, 840)"/>
<path d=""  transform="translate(13918, 840)"/>
<path d=""  transform="translate(14405, 840)"/>
<path d=""  transform="translate(14856, 840)"/>
<path d=""  transform="translate(15533, 840)"/>
<path d=""  transform="translate(16506, 840)"/>
<path d=""  transform="translate(17500, 840)"/>
<path d=""  transform="translate(18160, 840)"/>
<path d=""  transform="translate(18420, 840)"/>
<path d=""  transform="translate(19053, 840)"/>
<path d=""  transform="translate(19730, 840)"/>
<path d=""  transform="translate(20159, 840)"/>
<path d=""  transform="translate(20993, 840)"/>
<path d=""  transform="translate(21943, 840)"/>
<path d=""  transform="translate(22203, 840)"/>
<path d=""  transform="translate(23153, 840)"/>
<path d=""  transform="translate(23945, 840)"/>
<path d=""  transform="translate(24622, 840)"/>
<path d=""  transform="translate(25129, 840)"/>
<path d=""  transform="translate(25762, 840)"/>
<path d=""  transform="translate(26022, 840)"/>
<path d=""  transform="translate(26407, 840)"/>
<path d=""  transform="translate(27031, 840)"/>
<path d=""  transform="translate(27291, 840)"/>
<path d=""  transform="translate(28083, 840)"/>
<path d=""  transform="translate(29130, 840)"/>
<path d=""  transform="translate(29130, 840)"/>
<path d=""  transform="translate(29390, 840)"/>
<path d=""  transform="translate(29390, 840)"/>
<path d=""  transform="translate(29990, 840)"/>
<path d=""  transform="translate(30590, 840)"/>
<path d=""  transform="translate(30850, 840)"/>
<path d=""  transform="translate(31483, 840)"/>
<path d=""  transform="translate(32116, 840)"/>
<path d=""  transform="translate(32545, 840)"/>
<path d=""  transform="translate(33205, 840)"/>
<path d=""  transform="translate(33870, 840)"/>
<path d=""  transform="translate(34130, 840)"/>
<path d=""  transform="translate(34130, 840)"/>
<path d=""  transform="translate(34390, 840)"/>
<path d=""  transform="translate(34390, 840)"/>
<path d=""  transform="translate(35023, 840)"/>
<path d=""  transform="translate(35403, 840)"/>
<path d=""  transform="translate(36376, 840)"/>
<path d=""  transform="translate(36805, 840)"/>
<path d=""  transform="translate(37185, 840)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐫍𐫅 𐫀𐫇𐫡𐫍𐫀 𐫀‬ ‫𐫍𐫡𐫤𐫀 𐫀𐫏𐫐𐫀 𐫍𐫀𐫡𐫇𐫤𐫀 𐫅𐫃𐫁𐫏𐫗𐫀 𐫛𐫏𐫢𐫀 𐫗𐫎𐫡𐫤𐫀‬ ‫ 𐫖𐫓𐫇𐫀𐫀 22‬ ‫ 𐫐𐫓 𐫍𐫅 𐫛𐫡𐫘𐫇𐫛𐫀 𐫀𐫏𐫐</span></li>


<pre>Expected: u10AD0=78+1047|u10ACF.fina=77+507|u10AC0.init=76+633|space=75+260|u10AC0.fina=74+633|u10ADB.init=73+487|u10AC7.fina=72+429|u10AD8.init=71+766|u10AE1.fina=70+385|u10ADB.init=69+487|space=68+260|u10AC5.fina=67+385|u10ACD.init=66+624|space=65+260|u10AD3=64+792|u10AD0=63+1047|space=62+260|space=61+0|space=60+260|space=59+0|.notdef=58+600|.notdef=57+600|space=56+260|u10AC0.fina=55+633|u10AC0.init=54+633|u10AC7.fina=53+429|u10AD3.medi=52+660|u10AD6.init=51+665|space=50+260|space=49+0|space=48+260|space=47+0|u10AC0=46+633|u10AE4=45+677|u10AE1=44+419|u10ACE.fina=43+530|u10AD7.init=42+380|space=41+260|u10AC0=40+633|u10AE2=39+973|u10ACF.fina=38+507|u10ADB.init=37+487|space=36+260|u10AC0.fina=35+633|u10AD7.init=34+380|u10ACF.fina=33+507|u10AC1.medi=32+706|u10AC3.init=31+427|u10AC5=30+419|space=29+260|u10AC0=28+633|u10AE4=27+677|u10AC7=26+451|u10AE1.fina=25+385|u10AC0.medi=24+633|u10ACD.init=23+624|space=22+260|u10AC0=21+633|u10AD0=20+1047|u10ACF.fina=19+507|u10AC0.init=18+633|space=17+260|u10AC0=16+633|u10AE4=15+677|u10AE1.fina=14+385|u10ACD.init=13+624|space=12+0|space=11+260|space=10+0|u10AC0=9+633|space=8+260|u10AC0.fina=7+633|u10ACD.init=6+624|u10AE1=5+419|u10AC7.fina=4+429|u10AC0.init=3+633|space=2+260|u10AC5.fina=1+385|u10ACD.init=0+624</pre>



<pre>Got     : u10AD0=78+1047|u10ACF.fina=77+507|u10AC0.init=76+633|space=75+260|u10AC0.fina=74+633|u10ADB.init=73+487|u10AC7.fina=72+429|u10AD8.init=71+766|u10AE1.fina=70+385|u10ADB.init=69+487|space=68+260|u10AC5.fina=67+385|u10ACD.init=66+624|space=65+260|u10AD3=64+792|u10AD0=63+1047|space=62+260|space=61+0|space=60+260|space=59+0|two=58+572|two=57+572|space=56+260|u10AC0.fina=55+633|u10AC0.init=54+633|u10AC7.fina=53+429|u10AD3.medi=52+660|u10AD6.init=51+665|space=50+260|space=49+0|space=48+260|space=47+0|u10AC0=46+633|u10AE4=45+677|u10AE1=44+419|u10ACE.fina=43+530|u10AD7.init=42+380|space=41+260|u10AC0=40+633|u10AE2=39+973|u10ACF.fina=38+507|u10ADB.init=37+487|space=36+260|u10AC0.fina=35+633|u10AD7.init=34+380|u10ACF.fina=33+507|u10AC1.medi=32+706|u10AC3.init=31+427|u10AC5=30+419|space=29+260|u10AC0=28+633|u10AE4=27+677|u10AC7=26+451|u10AE1.fina=25+385|u10AC0.medi=24+633|u10ACD.init=23+624|space=22+260|u10AC0=21+633|u10AD0=20+1047|u10ACF.fina=19+507|u10AC0.init=18+633|space=17+260|u10AC0=16+633|u10AE4=15+677|u10AE1.fina=14+385|u10ACD.init=13+624|space=12+0|space=11+260|space=10+0|u10AC0=9+633|space=8+260|u10AC0.fina=7+633|u10ACD.init=6+624|u10AE1=5+419|u10AC7.fina=4+429|u10AC0.init=3+633|space=2+260|u10AC5.fina=1+385|u10ACD.init=0+624</pre>



<pre>                                                                                                                                                                                                                                                                                                                                           ^^ ^^^^^^^^^^^^^^ ^^^^^^^^^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 37779 2130" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 840)"/>
<path d=""  transform="translate(1047, 840)"/>
<path d=""  transform="translate(1554, 840)"/>
<path d=""  transform="translate(2187, 840)"/>
<path d=""  transform="translate(2447, 840)"/>
<path d=""  transform="translate(3080, 840)"/>
<path d=""  transform="translate(3567, 840)"/>
<path d=""  transform="translate(3996, 840)"/>
<path d=""  transform="translate(4762, 840)"/>
<path d=""  transform="translate(5147, 840)"/>
<path d=""  transform="translate(5634, 840)"/>
<path d=""  transform="translate(5894, 840)"/>
<path d=""  transform="translate(6279, 840)"/>
<path d=""  transform="translate(6903, 840)"/>
<path d=""  transform="translate(7163, 840)"/>
<path d=""  transform="translate(7955, 840)"/>
<path d=""  transform="translate(9002, 840)"/>
<path d=""  transform="translate(9262, 840)"/>
<path d=""  transform="translate(9262, 840)"/>
<path d=""  transform="translate(9522, 840)"/>
<path d=""  transform="translate(9522, 840)"/>
<path d=""  transform="translate(10094, 840)"/>
<path d=""  transform="translate(10666, 840)"/>
<path d=""  transform="translate(10926, 840)"/>
<path d=""  transform="translate(11559, 840)"/>
<path d=""  transform="translate(12192, 840)"/>
<path d=""  transform="translate(12621, 840)"/>
<path d=""  transform="translate(13281, 840)"/>
<path d=""  transform="translate(13946, 840)"/>
<path d=""  transform="translate(14206, 840)"/>
<path d=""  transform="translate(14206, 840)"/>
<path d=""  transform="translate(14466, 840)"/>
<path d=""  transform="translate(14466, 840)"/>
<path d=""  transform="translate(15099, 840)"/>
<path d=""  transform="translate(15776, 840)"/>
<path d=""  transform="translate(16195, 840)"/>
<path d=""  transform="translate(16725, 840)"/>
<path d=""  transform="translate(17105, 840)"/>
<path d=""  transform="translate(17365, 840)"/>
<path d=""  transform="translate(17998, 840)"/>
<path d=""  transform="translate(18971, 840)"/>
<path d=""  transform="translate(19478, 840)"/>
<path d=""  transform="translate(19965, 840)"/>
<path d=""  transform="translate(20225, 840)"/>
<path d=""  transform="translate(20858, 840)"/>
<path d=""  transform="translate(21238, 840)"/>
<path d=""  transform="translate(21745, 840)"/>
<path d=""  transform="translate(22451, 840)"/>
<path d=""  transform="translate(22878, 840)"/>
<path d=""  transform="translate(23297, 840)"/>
<path d=""  transform="translate(23557, 840)"/>
<path d=""  transform="translate(24190, 840)"/>
<path d=""  transform="translate(24867, 840)"/>
<path d=""  transform="translate(25318, 840)"/>
<path d=""  transform="translate(25703, 840)"/>
<path d=""  transform="translate(26336, 840)"/>
<path d=""  transform="translate(26960, 840)"/>
<path d=""  transform="translate(27220, 840)"/>
<path d=""  transform="translate(27853, 840)"/>
<path d=""  transform="translate(28900, 840)"/>
<path d=""  transform="translate(29407, 840)"/>
<path d=""  transform="translate(30040, 840)"/>
<path d=""  transform="translate(30300, 840)"/>
<path d=""  transform="translate(30933, 840)"/>
<path d=""  transform="translate(31610, 840)"/>
<path d=""  transform="translate(31995, 840)"/>
<path d=""  transform="translate(32619, 840)"/>
<path d=""  transform="translate(32619, 840)"/>
<path d=""  transform="translate(32879, 840)"/>
<path d=""  transform="translate(32879, 840)"/>
<path d=""  transform="translate(33512, 840)"/>
<path d=""  transform="translate(33772, 840)"/>
<path d=""  transform="translate(34405, 840)"/>
<path d=""  transform="translate(35029, 840)"/>
<path d=""  transform="translate(35448, 840)"/>
<path d=""  transform="translate(35877, 840)"/>
<path d=""  transform="translate(36510, 840)"/>
<path d=""  transform="translate(36770, 840)"/>
<path d=""  transform="translate(37155, 840)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 37835 2130" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 840)"/>
<path d=""  transform="translate(1047, 840)"/>
<path d=""  transform="translate(1554, 840)"/>
<path d=""  transform="translate(2187, 840)"/>
<path d=""  transform="translate(2447, 840)"/>
<path d=""  transform="translate(3080, 840)"/>
<path d=""  transform="translate(3567, 840)"/>
<path d=""  transform="translate(3996, 840)"/>
<path d=""  transform="translate(4762, 840)"/>
<path d=""  transform="translate(5147, 840)"/>
<path d=""  transform="translate(5634, 840)"/>
<path d=""  transform="translate(5894, 840)"/>
<path d=""  transform="translate(6279, 840)"/>
<path d=""  transform="translate(6903, 840)"/>
<path d=""  transform="translate(7163, 840)"/>
<path d=""  transform="translate(7955, 840)"/>
<path d=""  transform="translate(9002, 840)"/>
<path d=""  transform="translate(9262, 840)"/>
<path d=""  transform="translate(9262, 840)"/>
<path d=""  transform="translate(9522, 840)"/>
<path d=""  transform="translate(9522, 840)"/>
<path d=""  transform="translate(10122, 840)"/>
<path d=""  transform="translate(10722, 840)"/>
<path d=""  transform="translate(10982, 840)"/>
<path d=""  transform="translate(11615, 840)"/>
<path d=""  transform="translate(12248, 840)"/>
<path d=""  transform="translate(12677, 840)"/>
<path d=""  transform="translate(13337, 840)"/>
<path d=""  transform="translate(14002, 840)"/>
<path d=""  transform="translate(14262, 840)"/>
<path d=""  transform="translate(14262, 840)"/>
<path d=""  transform="translate(14522, 840)"/>
<path d=""  transform="translate(14522, 840)"/>
<path d=""  transform="translate(15155, 840)"/>
<path d=""  transform="translate(15832, 840)"/>
<path d=""  transform="translate(16251, 840)"/>
<path d=""  transform="translate(16781, 840)"/>
<path d=""  transform="translate(17161, 840)"/>
<path d=""  transform="translate(17421, 840)"/>
<path d=""  transform="translate(18054, 840)"/>
<path d=""  transform="translate(19027, 840)"/>
<path d=""  transform="translate(19534, 840)"/>
<path d=""  transform="translate(20021, 840)"/>
<path d=""  transform="translate(20281, 840)"/>
<path d=""  transform="translate(20914, 840)"/>
<path d=""  transform="translate(21294, 840)"/>
<path d=""  transform="translate(21801, 840)"/>
<path d=""  transform="translate(22507, 840)"/>
<path d=""  transform="translate(22934, 840)"/>
<path d=""  transform="translate(23353, 840)"/>
<path d=""  transform="translate(23613, 840)"/>
<path d=""  transform="translate(24246, 840)"/>
<path d=""  transform="translate(24923, 840)"/>
<path d=""  transform="translate(25374, 840)"/>
<path d=""  transform="translate(25759, 840)"/>
<path d=""  transform="translate(26392, 840)"/>
<path d=""  transform="translate(27016, 840)"/>
<path d=""  transform="translate(27276, 840)"/>
<path d=""  transform="translate(27909, 840)"/>
<path d=""  transform="translate(28956, 840)"/>
<path d=""  transform="translate(29463, 840)"/>
<path d=""  transform="translate(30096, 840)"/>
<path d=""  transform="translate(30356, 840)"/>
<path d=""  transform="translate(30989, 840)"/>
<path d=""  transform="translate(31666, 840)"/>
<path d=""  transform="translate(32051, 840)"/>
<path d=""  transform="translate(32675, 840)"/>
<path d=""  transform="translate(32675, 840)"/>
<path d=""  transform="translate(32935, 840)"/>
<path d=""  transform="translate(32935, 840)"/>
<path d=""  transform="translate(33568, 840)"/>
<path d=""  transform="translate(33828, 840)"/>
<path d=""  transform="translate(34461, 840)"/>
<path d=""  transform="translate(35085, 840)"/>
<path d=""  transform="translate(35504, 840)"/>
<path d=""  transform="translate(35933, 840)"/>
<path d=""  transform="translate(36566, 840)"/>
<path d=""  transform="translate(36826, 840)"/>
<path d=""  transform="translate(37211, 840)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐫇𐫢𐫇𐫤𐫛𐫏𐫤𐫀 𐫇𐫖𐫡𐫅𐫇𐫤𐫗𐫏𐫤𐫀 𐫅𐫇𐫞𐫀 𐫙𐫖 𐫀𐫏𐫞𐫡‬ ‫𐫀 𐫇𐫖𐫎𐫇𐫡𐫤𐫀 𐫛𐫡𐫘𐫇𐫛𐫏𐫤𐫀‬ ‫ 𐫖𐫓𐫇𐫀𐫀 23‬ ‫𐫐𐫓 𐫍𐫅 𐫀𐫗𐫢𐫀</span></li>


<pre>Expected: u10AC0=77+633|u10AE2=76+973|u10AD7=75+380|u10AC0=74+633|space=73+260|u10AC5.fina=72+385|u10ACD.init=71+624|space=70+260|u10AD3=69+792|u10AD0=68+1047|space=67+0|space=66+260|space=65+0|.notdef=64+600|.notdef=63+600|space=62+260|u10AC0.fina=61+633|u10AC0.init=60+633|u10AC7.fina=59+429|u10AD3.medi=58+660|u10AD6.init=57+665|space=56+260|space=55+0|space=54+260|space=53+0|u10AC0=52+633|u10AE4=51+677|u10ACF.fina=50+507|u10ADB.init=49+487|u10AC7.fina=48+429|u10AD8.init=47+766|u10AE1.fina=46+385|u10ADB.init=45+487|space=44+260|u10AC0=43+633|u10AE4=42+677|u10AE1=41+419|u10AC7=40+451|u10ACE.fina=39+530|u10AD6.init=38+665|u10AC7=37+451|space=36+260|u10AC0=35+633|space=34+0|space=33+260|space=32+0|u10AE1.fina=31+385|u10ADE.init=30+834|u10ACF.fina=29+507|u10AC0.init=28+633|space=27+260|u10AD6.fina=26+994|u10AD9.init=25+607|space=24+260|u10AC0.fina=23+633|u10ADE.init=22+834|u10AC7=21+451|u10AC5=20+419|space=19+260|u10AC0=18+633|u10AE4=17+677|u10ACF.fina=16+507|u10AD7.init=15+380|u10AE4=14+677|u10AC7=13+451|u10AC5=12+419|u10AE1.fina=11+385|u10AD6.init=10+665|u10AC7=9+451|space=8+260|u10AC0=7+633|u10AE4=6+677|u10ACF.fina=5+507|u10ADB.init=4+487|u10AE4=3+677|u10AC7=2+451|u10AE2=1+973|u10AC7=0+451</pre>



<pre>Got     : u10AC0=77+633|u10AE2=76+973|u10AD7=75+380|u10AC0=74+633|space=73+260|u10AC5.fina=72+385|u10ACD.init=71+624|space=70+260|u10AD3=69+792|u10AD0=68+1047|space=67+0|space=66+260|space=65+0|three=64+572|two=63+572|space=62+260|u10AC0.fina=61+633|u10AC0.init=60+633|u10AC7.fina=59+429|u10AD3.medi=58+660|u10AD6.init=57+665|space=56+260|space=55+0|space=54+260|space=53+0|u10AC0=52+633|u10AE4=51+677|u10ACF.fina=50+507|u10ADB.init=49+487|u10AC7.fina=48+429|u10AD8.init=47+766|u10AE1.fina=46+385|u10ADB.init=45+487|space=44+260|u10AC0=43+633|u10AE4=42+677|u10AE1=41+419|u10AC7=40+451|u10ACE.fina=39+530|u10AD6.init=38+665|u10AC7=37+451|space=36+260|u10AC0=35+633|space=34+0|space=33+260|space=32+0|u10AE1.fina=31+385|u10ADE.init=30+834|u10ACF.fina=29+507|u10AC0.init=28+633|space=27+260|u10AD6.fina=26+994|u10AD9.init=25+607|space=24+260|u10AC0.fina=23+633|u10ADE.init=22+834|u10AC7=21+451|u10AC5=20+419|space=19+260|u10AC0=18+633|u10AE4=17+677|u10ACF.fina=16+507|u10AD7.init=15+380|u10AE4=14+677|u10AC7=13+451|u10AC5=12+419|u10AE1.fina=11+385|u10AD6.init=10+665|u10AC7=9+451|space=8+260|u10AC0=7+633|u10AE4=6+677|u10ACF.fina=5+507|u10ADB.init=4+487|u10AE4=3+677|u10AC7=2+451|u10AE2=1+973|u10AC7=0+451</pre>



<pre>                                                                                                                                                                                                  ^^ ^^^^^^^^^^^^^^^^^^^^^^^^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 38239 2130" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 840)"/>
<path d=""  transform="translate(633, 840)"/>
<path d=""  transform="translate(1606, 840)"/>
<path d=""  transform="translate(1986, 840)"/>
<path d=""  transform="translate(2619, 840)"/>
<path d=""  transform="translate(2879, 840)"/>
<path d=""  transform="translate(3264, 840)"/>
<path d=""  transform="translate(3888, 840)"/>
<path d=""  transform="translate(4148, 840)"/>
<path d=""  transform="translate(4940, 840)"/>
<path d=""  transform="translate(5987, 840)"/>
<path d=""  transform="translate(5987, 840)"/>
<path d=""  transform="translate(6247, 840)"/>
<path d=""  transform="translate(6247, 840)"/>
<path d=""  transform="translate(6819, 840)"/>
<path d=""  transform="translate(7391, 840)"/>
<path d=""  transform="translate(7651, 840)"/>
<path d=""  transform="translate(8284, 840)"/>
<path d=""  transform="translate(8917, 840)"/>
<path d=""  transform="translate(9346, 840)"/>
<path d=""  transform="translate(10006, 840)"/>
<path d=""  transform="translate(10671, 840)"/>
<path d=""  transform="translate(10931, 840)"/>
<path d=""  transform="translate(10931, 840)"/>
<path d=""  transform="translate(11191, 840)"/>
<path d=""  transform="translate(11191, 840)"/>
<path d=""  transform="translate(11824, 840)"/>
<path d=""  transform="translate(12501, 840)"/>
<path d=""  transform="translate(13008, 840)"/>
<path d=""  transform="translate(13495, 840)"/>
<path d=""  transform="translate(13924, 840)"/>
<path d=""  transform="translate(14690, 840)"/>
<path d=""  transform="translate(15075, 840)"/>
<path d=""  transform="translate(15562, 840)"/>
<path d=""  transform="translate(15822, 840)"/>
<path d=""  transform="translate(16455, 840)"/>
<path d=""  transform="translate(17132, 840)"/>
<path d=""  transform="translate(17551, 840)"/>
<path d=""  transform="translate(18002, 840)"/>
<path d=""  transform="translate(18532, 840)"/>
<path d=""  transform="translate(19197, 840)"/>
<path d=""  transform="translate(19648, 840)"/>
<path d=""  transform="translate(19908, 840)"/>
<path d=""  transform="translate(20541, 840)"/>
<path d=""  transform="translate(20541, 840)"/>
<path d=""  transform="translate(20801, 840)"/>
<path d=""  transform="translate(20801, 840)"/>
<path d=""  transform="translate(21186, 840)"/>
<path d=""  transform="translate(22020, 840)"/>
<path d=""  transform="translate(22527, 840)"/>
<path d=""  transform="translate(23160, 840)"/>
<path d=""  transform="translate(23420, 840)"/>
<path d=""  transform="translate(24414, 840)"/>
<path d=""  transform="translate(25021, 840)"/>
<path d=""  transform="translate(25281, 840)"/>
<path d=""  transform="translate(25914, 840)"/>
<path d=""  transform="translate(26748, 840)"/>
<path d=""  transform="translate(27199, 840)"/>
<path d=""  transform="translate(27618, 840)"/>
<path d=""  transform="translate(27878, 840)"/>
<path d=""  transform="translate(28511, 840)"/>
<path d=""  transform="translate(29188, 840)"/>
<path d=""  transform="translate(29695, 840)"/>
<path d=""  transform="translate(30075, 840)"/>
<path d=""  transform="translate(30752, 840)"/>
<path d=""  transform="translate(31203, 840)"/>
<path d=""  transform="translate(31622, 840)"/>
<path d=""  transform="translate(32007, 840)"/>
<path d=""  transform="translate(32672, 840)"/>
<path d=""  transform="translate(33123, 840)"/>
<path d=""  transform="translate(33383, 840)"/>
<path d=""  transform="translate(34016, 840)"/>
<path d=""  transform="translate(34693, 840)"/>
<path d=""  transform="translate(35200, 840)"/>
<path d=""  transform="translate(35687, 840)"/>
<path d=""  transform="translate(36364, 840)"/>
<path d=""  transform="translate(36815, 840)"/>
<path d=""  transform="translate(37788, 840)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 38295 2130" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 840)"/>
<path d=""  transform="translate(633, 840)"/>
<path d=""  transform="translate(1606, 840)"/>
<path d=""  transform="translate(1986, 840)"/>
<path d=""  transform="translate(2619, 840)"/>
<path d=""  transform="translate(2879, 840)"/>
<path d=""  transform="translate(3264, 840)"/>
<path d=""  transform="translate(3888, 840)"/>
<path d=""  transform="translate(4148, 840)"/>
<path d=""  transform="translate(4940, 840)"/>
<path d=""  transform="translate(5987, 840)"/>
<path d=""  transform="translate(5987, 840)"/>
<path d=""  transform="translate(6247, 840)"/>
<path d=""  transform="translate(6247, 840)"/>
<path d=""  transform="translate(6847, 840)"/>
<path d=""  transform="translate(7447, 840)"/>
<path d=""  transform="translate(7707, 840)"/>
<path d=""  transform="translate(8340, 840)"/>
<path d=""  transform="translate(8973, 840)"/>
<path d=""  transform="translate(9402, 840)"/>
<path d=""  transform="translate(10062, 840)"/>
<path d=""  transform="translate(10727, 840)"/>
<path d=""  transform="translate(10987, 840)"/>
<path d=""  transform="translate(10987, 840)"/>
<path d=""  transform="translate(11247, 840)"/>
<path d=""  transform="translate(11247, 840)"/>
<path d=""  transform="translate(11880, 840)"/>
<path d=""  transform="translate(12557, 840)"/>
<path d=""  transform="translate(13064, 840)"/>
<path d=""  transform="translate(13551, 840)"/>
<path d=""  transform="translate(13980, 840)"/>
<path d=""  transform="translate(14746, 840)"/>
<path d=""  transform="translate(15131, 840)"/>
<path d=""  transform="translate(15618, 840)"/>
<path d=""  transform="translate(15878, 840)"/>
<path d=""  transform="translate(16511, 840)"/>
<path d=""  transform="translate(17188, 840)"/>
<path d=""  transform="translate(17607, 840)"/>
<path d=""  transform="translate(18058, 840)"/>
<path d=""  transform="translate(18588, 840)"/>
<path d=""  transform="translate(19253, 840)"/>
<path d=""  transform="translate(19704, 840)"/>
<path d=""  transform="translate(19964, 840)"/>
<path d=""  transform="translate(20597, 840)"/>
<path d=""  transform="translate(20597, 840)"/>
<path d=""  transform="translate(20857, 840)"/>
<path d=""  transform="translate(20857, 840)"/>
<path d=""  transform="translate(21242, 840)"/>
<path d=""  transform="translate(22076, 840)"/>
<path d=""  transform="translate(22583, 840)"/>
<path d=""  transform="translate(23216, 840)"/>
<path d=""  transform="translate(23476, 840)"/>
<path d=""  transform="translate(24470, 840)"/>
<path d=""  transform="translate(25077, 840)"/>
<path d=""  transform="translate(25337, 840)"/>
<path d=""  transform="translate(25970, 840)"/>
<path d=""  transform="translate(26804, 840)"/>
<path d=""  transform="translate(27255, 840)"/>
<path d=""  transform="translate(27674, 840)"/>
<path d=""  transform="translate(27934, 840)"/>
<path d=""  transform="translate(28567, 840)"/>
<path d=""  transform="translate(29244, 840)"/>
<path d=""  transform="translate(29751, 840)"/>
<path d=""  transform="translate(30131, 840)"/>
<path d=""  transform="translate(30808, 840)"/>
<path d=""  transform="translate(31259, 840)"/>
<path d=""  transform="translate(31678, 840)"/>
<path d=""  transform="translate(32063, 840)"/>
<path d=""  transform="translate(32728, 840)"/>
<path d=""  transform="translate(33179, 840)"/>
<path d=""  transform="translate(33439, 840)"/>
<path d=""  transform="translate(34072, 840)"/>
<path d=""  transform="translate(34749, 840)"/>
<path d=""  transform="translate(35256, 840)"/>
<path d=""  transform="translate(35743, 840)"/>
<path d=""  transform="translate(36420, 840)"/>
<path d=""  transform="translate(36871, 840)"/>
<path d=""  transform="translate(37844, 840)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐫆𐫞𐫇𐫤𐫀 𐫓𐫢𐫤𐫀𐫘𐫤𐫀 𐫇𐫉𐫁𐫃𐫤𐫀 𐫏𐫖 𐫍𐫇𐫏𐫅𐫀 𐫤‬ ‫𐫇𐫃𐫡𐫏𐫀 𐫓𐫍𐫖𐫏𐫤𐫀 𐫏𐫇𐫤𐫡𐫗𐫀‬ ‫ 𐫖𐫓𐫇𐫀𐫀 24‬ ‫ 𐫐𐫓 𐫍𐫅 𐫀𐫏𐫤𐫓𐫆</span></li>


<pre>Expected: u10AC6=79+950|u10AD3=78+792|u10AE4=77+677|u10ACF.fina=76+507|u10AC0.init=75+633|space=74+260|u10AC5.fina=73+385|u10ACD.init=72+624|space=71+260|u10AD3=70+792|u10AD0=69+1047|space=68+260|space=67+0|space=66+260|space=65+0|.notdef=64+600|.notdef=63+600|space=62+260|u10AC0.fina=61+633|u10AC0.init=60+633|u10AC7.fina=59+429|u10AD3.medi=58+660|u10AD6.init=57+665|space=56+260|space=55+0|space=54+260|space=53+0|u10AC0.fina=52+633|u10AD7.init=51+380|u10AE1=50+419|u10AE4=49+677|u10AC7=48+451|u10ACF=47+507|space=46+260|u10AC0=45+633|u10AE4=44+677|u10ACF.fina=43+507|u10AD6.medi=42+665|u10ACD.init=41+624|u10AD3=40+792|space=39+260|u10AC0=38+633|u10ACF=37+507|u10AE1.fina=36+385|u10AC3.init=35+427|u10AC7=34+451|space=33+0|space=32+260|space=31+0|u10AE4=30+677|space=29+260|u10AC0=28+633|u10AC5=27+419|u10ACF=26+507|u10AC7.fina=25+429|u10ACD.init=24+624|space=23+260|u10AD6=22+994|u10ACF=21+507|space=20+260|u10AC0=19+633|u10AE4.fina=18+632|u10AC3.medi=17+407|u10AC1.init=16+706|u10AC9=15+493|u10AC7=14+451|space=13+260|u10AC0=12+633|u10AE4.fina=11+632|u10AD8.medi=10+766|u10AC0.init=9+633|u10AE4=8+677|u10AE2=7+973|u10AD3=6+792|space=5+260|u10AC0=4+633|u10AE4=3+677|u10AC7.fina=2+429|u10ADE.init=1+834|u10AC6=0+950</pre>



<pre>Got     : u10AC6=79+950|u10AD3=78+792|u10AE4=77+677|u10ACF.fina=76+507|u10AC0.init=75+633|space=74+260|u10AC5.fina=73+385|u10ACD.init=72+624|space=71+260|u10AD3=70+792|u10AD0=69+1047|space=68+260|space=67+0|space=66+260|space=65+0|four=64+572|two=63+572|space=62+260|u10AC0.fina=61+633|u10AC0.init=60+633|u10AC7.fina=59+429|u10AD3.medi=58+660|u10AD6.init=57+665|space=56+260|space=55+0|space=54+260|space=53+0|u10AC0.fina=52+633|u10AD7.init=51+380|u10AE1=50+419|u10AE4=49+677|u10AC7=48+451|u10ACF=47+507|space=46+260|u10AC0=45+633|u10AE4=44+677|u10ACF.fina=43+507|u10AD6.medi=42+665|u10ACD.init=41+624|u10AD3=40+792|space=39+260|u10AC0=38+633|u10ACF=37+507|u10AE1.fina=36+385|u10AC3.init=35+427|u10AC7=34+451|space=33+0|space=32+260|space=31+0|u10AE4=30+677|space=29+260|u10AC0=28+633|u10AC5=27+419|u10ACF=26+507|u10AC7.fina=25+429|u10ACD.init=24+624|space=23+260|u10AD6=22+994|u10ACF=21+507|space=20+260|u10AC0=19+633|u10AE4.fina=18+632|u10AC3.medi=17+407|u10AC1.init=16+706|u10AC9=15+493|u10AC7=14+451|space=13+260|u10AC0=12+633|u10AE4.fina=11+632|u10AD8.medi=10+766|u10AC0.init=9+633|u10AE4=8+677|u10AE2=7+973|u10AD3=6+792|space=5+260|u10AC0=4+633|u10AE4=3+677|u10AC7.fina=2+429|u10ADE.init=1+834|u10AC6=0+950</pre>



<pre>                                                                                                                                                                                                                                       ++++++ ++++++++++  ^^ +++++++++++++++++++++++++++++
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 40580 2130" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 840)"/>
<path d=""  transform="translate(950, 840)"/>
<path d=""  transform="translate(1742, 840)"/>
<path d=""  transform="translate(2419, 840)"/>
<path d=""  transform="translate(2926, 840)"/>
<path d=""  transform="translate(3559, 840)"/>
<path d=""  transform="translate(3819, 840)"/>
<path d=""  transform="translate(4204, 840)"/>
<path d=""  transform="translate(4828, 840)"/>
<path d=""  transform="translate(5088, 840)"/>
<path d=""  transform="translate(5880, 840)"/>
<path d=""  transform="translate(6927, 840)"/>
<path d=""  transform="translate(7187, 840)"/>
<path d=""  transform="translate(7187, 840)"/>
<path d=""  transform="translate(7447, 840)"/>
<path d=""  transform="translate(7447, 840)"/>
<path d=""  transform="translate(8019, 840)"/>
<path d=""  transform="translate(8591, 840)"/>
<path d=""  transform="translate(8851, 840)"/>
<path d=""  transform="translate(9484, 840)"/>
<path d=""  transform="translate(10117, 840)"/>
<path d=""  transform="translate(10546, 840)"/>
<path d=""  transform="translate(11206, 840)"/>
<path d=""  transform="translate(11871, 840)"/>
<path d=""  transform="translate(12131, 840)"/>
<path d=""  transform="translate(12131, 840)"/>
<path d=""  transform="translate(12391, 840)"/>
<path d=""  transform="translate(12391, 840)"/>
<path d=""  transform="translate(13024, 840)"/>
<path d=""  transform="translate(13404, 840)"/>
<path d=""  transform="translate(13823, 840)"/>
<path d=""  transform="translate(14500, 840)"/>
<path d=""  transform="translate(14951, 840)"/>
<path d=""  transform="translate(15458, 840)"/>
<path d=""  transform="translate(15718, 840)"/>
<path d=""  transform="translate(16351, 840)"/>
<path d=""  transform="translate(17028, 840)"/>
<path d=""  transform="translate(17535, 840)"/>
<path d=""  transform="translate(18200, 840)"/>
<path d=""  transform="translate(18824, 840)"/>
<path d=""  transform="translate(19616, 840)"/>
<path d=""  transform="translate(19876, 840)"/>
<path d=""  transform="translate(20509, 840)"/>
<path d=""  transform="translate(21016, 840)"/>
<path d=""  transform="translate(21401, 840)"/>
<path d=""  transform="translate(21828, 840)"/>
<path d=""  transform="translate(22279, 840)"/>
<path d=""  transform="translate(22279, 840)"/>
<path d=""  transform="translate(22539, 840)"/>
<path d=""  transform="translate(22539, 840)"/>
<path d=""  transform="translate(23216, 840)"/>
<path d=""  transform="translate(23476, 840)"/>
<path d=""  transform="translate(24109, 840)"/>
<path d=""  transform="translate(24528, 840)"/>
<path d=""  transform="translate(25035, 840)"/>
<path d=""  transform="translate(25464, 840)"/>
<path d=""  transform="translate(26088, 840)"/>
<path d=""  transform="translate(26348, 840)"/>
<path d=""  transform="translate(27342, 840)"/>
<path d=""  transform="translate(27849, 840)"/>
<path d=""  transform="translate(28109, 840)"/>
<path d=""  transform="translate(28742, 840)"/>
<path d=""  transform="translate(29374, 840)"/>
<path d=""  transform="translate(29781, 840)"/>
<path d=""  transform="translate(30487, 840)"/>
<path d=""  transform="translate(30980, 840)"/>
<path d=""  transform="translate(31431, 840)"/>
<path d=""  transform="translate(31691, 840)"/>
<path d=""  transform="translate(32324, 840)"/>
<path d=""  transform="translate(32956, 840)"/>
<path d=""  transform="translate(33722, 840)"/>
<path d=""  transform="translate(34355, 840)"/>
<path d=""  transform="translate(35032, 840)"/>
<path d=""  transform="translate(36005, 840)"/>
<path d=""  transform="translate(36797, 840)"/>
<path d=""  transform="translate(37057, 840)"/>
<path d=""  transform="translate(37690, 840)"/>
<path d=""  transform="translate(38367, 840)"/>
<path d=""  transform="translate(38796, 840)"/>
<path d=""  transform="translate(39630, 840)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 40636 2130" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 840)"/>
<path d=""  transform="translate(950, 840)"/>
<path d=""  transform="translate(1742, 840)"/>
<path d=""  transform="translate(2419, 840)"/>
<path d=""  transform="translate(2926, 840)"/>
<path d=""  transform="translate(3559, 840)"/>
<path d=""  transform="translate(3819, 840)"/>
<path d=""  transform="translate(4204, 840)"/>
<path d=""  transform="translate(4828, 840)"/>
<path d=""  transform="translate(5088, 840)"/>
<path d=""  transform="translate(5880, 840)"/>
<path d=""  transform="translate(6927, 840)"/>
<path d=""  transform="translate(7187, 840)"/>
<path d=""  transform="translate(7187, 840)"/>
<path d=""  transform="translate(7447, 840)"/>
<path d=""  transform="translate(7447, 840)"/>
<path d=""  transform="translate(8047, 840)"/>
<path d=""  transform="translate(8647, 840)"/>
<path d=""  transform="translate(8907, 840)"/>
<path d=""  transform="translate(9540, 840)"/>
<path d=""  transform="translate(10173, 840)"/>
<path d=""  transform="translate(10602, 840)"/>
<path d=""  transform="translate(11262, 840)"/>
<path d=""  transform="translate(11927, 840)"/>
<path d=""  transform="translate(12187, 840)"/>
<path d=""  transform="translate(12187, 840)"/>
<path d=""  transform="translate(12447, 840)"/>
<path d=""  transform="translate(12447, 840)"/>
<path d=""  transform="translate(13080, 840)"/>
<path d=""  transform="translate(13460, 840)"/>
<path d=""  transform="translate(13879, 840)"/>
<path d=""  transform="translate(14556, 840)"/>
<path d=""  transform="translate(15007, 840)"/>
<path d=""  transform="translate(15514, 840)"/>
<path d=""  transform="translate(15774, 840)"/>
<path d=""  transform="translate(16407, 840)"/>
<path d=""  transform="translate(17084, 840)"/>
<path d=""  transform="translate(17591, 840)"/>
<path d=""  transform="translate(18256, 840)"/>
<path d=""  transform="translate(18880, 840)"/>
<path d=""  transform="translate(19672, 840)"/>
<path d=""  transform="translate(19932, 840)"/>
<path d=""  transform="translate(20565, 840)"/>
<path d=""  transform="translate(21072, 840)"/>
<path d=""  transform="translate(21457, 840)"/>
<path d=""  transform="translate(21884, 840)"/>
<path d=""  transform="translate(22335, 840)"/>
<path d=""  transform="translate(22335, 840)"/>
<path d=""  transform="translate(22595, 840)"/>
<path d=""  transform="translate(22595, 840)"/>
<path d=""  transform="translate(23272, 840)"/>
<path d=""  transform="translate(23532, 840)"/>
<path d=""  transform="translate(24165, 840)"/>
<path d=""  transform="translate(24584, 840)"/>
<path d=""  transform="translate(25091, 840)"/>
<path d=""  transform="translate(25520, 840)"/>
<path d=""  transform="translate(26144, 840)"/>
<path d=""  transform="translate(26404, 840)"/>
<path d=""  transform="translate(27398, 840)"/>
<path d=""  transform="translate(27905, 840)"/>
<path d=""  transform="translate(28165, 840)"/>
<path d=""  transform="translate(28798, 840)"/>
<path d=""  transform="translate(29430, 840)"/>
<path d=""  transform="translate(29837, 840)"/>
<path d=""  transform="translate(30543, 840)"/>
<path d=""  transform="translate(31036, 840)"/>
<path d=""  transform="translate(31487, 840)"/>
<path d=""  transform="translate(31747, 840)"/>
<path d=""  transform="translate(32380, 840)"/>
<path d=""  transform="translate(33012, 840)"/>
<path d=""  transform="translate(33778, 840)"/>
<path d=""  transform="translate(34411, 840)"/>
<path d=""  transform="translate(35088, 840)"/>
<path d=""  transform="translate(36061, 840)"/>
<path d=""  transform="translate(36853, 840)"/>
<path d=""  transform="translate(37113, 840)"/>
<path d=""  transform="translate(37746, 840)"/>
<path d=""  transform="translate(38423, 840)"/>
<path d=""  transform="translate(38852, 840)"/>
<path d=""  transform="translate(39686, 840)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐫖𐫓𐫇𐫀𐫀 25‬ ‫𐫐𐫓 𐫍𐫅 𐫀𐫏𐫤𐫓𐫆 𐫆𐫞𐫇𐫤𐫀 𐫓𐫍𐫅 𐫞𐫅𐫡𐫀 𐫝𐫛𐫏 𐫖𐫗 𐫍𐫇𐫓𐫖𐫗𐫀 𐫁𐫍𐫁‬ ‫𐫢𐫀 𐫖𐫐𐫇𐫓𐫤𐫀 𐫇𐫓𐫁𐫢𐫤𐫀 𐫇𐫁𐫏𐫤𐫀</span></li>


<pre>Expected: u10AC0=79+633|u10AE4=78+677|u10ACF.fina=77+507|u10AC1.init=76+706|u10AC7=75+451|space=74+260|u10AC0=73+633|u10AE4=72+677|u10AE2=71+973|u10AC1.fina=70+999|u10AD3.init=69+660|u10AC7=68+451|space=67+260|u10AC0=66+633|u10AE4.fina=65+632|u10AD3.init=64+660|u10AC7=63+451|u10AD0.fina=62+1047|u10AD6.init=61+665|space=60+260|u10AC0=59+633|u10AE2=58+973|space=57+0|space=56+260|space=55+0|u10AC1.fina=54+999|u10ACD.init=53+624|u10AC1=52+999|space=51+260|u10AC0.fina=50+633|u10AD7.init=49+380|u10AD6.fina=48+994|u10AD3.init=47+660|u10AC7.fina=46+429|u10ACD.init=45+624|space=44+260|u10AD7=43+380|u10AD6=42+994|space=41+260|u10ACF.fina=40+507|u10ADB.init=39+487|u10ADD=38+901|space=37+260|u10AC0=36+633|u10AE1=35+419|u10AC5.fina=34+385|u10ADE.init=33+834|space=32+260|u10AC5.fina=31+385|u10ACD.init=30+624|u10AD3=29+792|space=28+260|u10AC0=27+633|u10AE4=26+677|u10AC7.fina=25+429|u10ADE.init=24+834|u10AC6=23+950|space=22+260|u10AC6=21+950|u10AD3=20+792|u10AE4=19+677|u10ACF.fina=18+507|u10AC0.init=17+633|space=16+260|u10AC5.fina=15+385|u10ACD.init=14+624|space=13+260|u10AD3=12+792|u10AD0=11+1047|space=10+0|space=9+260|space=8+0|.notdef=7+600|.notdef=6+600|space=5+260|u10AC0.fina=4+633|u10AC0.init=3+633|u10AC7.fina=2+429|u10AD3.medi=1+660|u10AD6.init=0+665</pre>



<pre>Got     : u10AC0=79+633|u10AE4=78+677|u10ACF.fina=77+507|u10AC1.init=76+706|u10AC7=75+451|space=74+260|u10AC0=73+633|u10AE4=72+677|u10AE2=71+973|u10AC1.fina=70+999|u10AD3.init=69+660|u10AC7=68+451|space=67+260|u10AC0=66+633|u10AE4.fina=65+632|u10AD3.init=64+660|u10AC7=63+451|u10AD0.fina=62+1047|u10AD6.init=61+665|space=60+260|u10AC0=59+633|u10AE2=58+973|space=57+0|space=56+260|space=55+0|u10AC1.fina=54+999|u10ACD.init=53+624|u10AC1=52+999|space=51+260|u10AC0.fina=50+633|u10AD7.init=49+380|u10AD6.fina=48+994|u10AD3.init=47+660|u10AC7.fina=46+429|u10ACD.init=45+624|space=44+260|u10AD7=43+380|u10AD6=42+994|space=41+260|u10ACF.fina=40+507|u10ADB.init=39+487|u10ADD=38+901|space=37+260|u10AC0=36+633|u10AE1=35+419|u10AC5.fina=34+385|u10ADE.init=33+834|space=32+260|u10AC5.fina=31+385|u10ACD.init=30+624|u10AD3=29+792|space=28+260|u10AC0=27+633|u10AE4=26+677|u10AC7.fina=25+429|u10ADE.init=24+834|u10AC6=23+950|space=22+260|u10AC6=21+950|u10AD3=20+792|u10AE4=19+677|u10ACF.fina=18+507|u10AC0.init=17+633|space=16+260|u10AC5.fina=15+385|u10ACD.init=14+624|space=13+260|u10AD3=12+792|u10AD0=11+1047|space=10+0|space=9+260|space=8+0|five=7+572|two=6+572|space=5+260|u10AC0.fina=4+633|u10AC0.init=3+633|u10AC7.fina=2+429|u10AD3.medi=1+660|u10AD6.init=0+665</pre>



<pre>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            ^^ ^^^^^^^^^^^^^^^^^^^^^^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 44738 2130" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 840)"/>
<path d=""  transform="translate(633, 840)"/>
<path d=""  transform="translate(1310, 840)"/>
<path d=""  transform="translate(1817, 840)"/>
<path d=""  transform="translate(2523, 840)"/>
<path d=""  transform="translate(2974, 840)"/>
<path d=""  transform="translate(3234, 840)"/>
<path d=""  transform="translate(3867, 840)"/>
<path d=""  transform="translate(4544, 840)"/>
<path d=""  transform="translate(5517, 840)"/>
<path d=""  transform="translate(6516, 840)"/>
<path d=""  transform="translate(7176, 840)"/>
<path d=""  transform="translate(7627, 840)"/>
<path d=""  transform="translate(7887, 840)"/>
<path d=""  transform="translate(8520, 840)"/>
<path d=""  transform="translate(9152, 840)"/>
<path d=""  transform="translate(9812, 840)"/>
<path d=""  transform="translate(10263, 840)"/>
<path d=""  transform="translate(11310, 840)"/>
<path d=""  transform="translate(11975, 840)"/>
<path d=""  transform="translate(12235, 840)"/>
<path d=""  transform="translate(12868, 840)"/>
<path d=""  transform="translate(13841, 840)"/>
<path d=""  transform="translate(13841, 840)"/>
<path d=""  transform="translate(14101, 840)"/>
<path d=""  transform="translate(14101, 840)"/>
<path d=""  transform="translate(15100, 840)"/>
<path d=""  transform="translate(15724, 840)"/>
<path d=""  transform="translate(16723, 840)"/>
<path d=""  transform="translate(16983, 840)"/>
<path d=""  transform="translate(17616, 840)"/>
<path d=""  transform="translate(17996, 840)"/>
<path d=""  transform="translate(18990, 840)"/>
<path d=""  transform="translate(19650, 840)"/>
<path d=""  transform="translate(20079, 840)"/>
<path d=""  transform="translate(20703, 840)"/>
<path d=""  transform="translate(20963, 840)"/>
<path d=""  transform="translate(21343, 840)"/>
<path d=""  transform="translate(22337, 840)"/>
<path d=""  transform="translate(22597, 840)"/>
<path d=""  transform="translate(23104, 840)"/>
<path d=""  transform="translate(23591, 840)"/>
<path d=""  transform="translate(24492, 840)"/>
<path d=""  transform="translate(24752, 840)"/>
<path d=""  transform="translate(25385, 840)"/>
<path d=""  transform="translate(25804, 840)"/>
<path d=""  transform="translate(26189, 840)"/>
<path d=""  transform="translate(27023, 840)"/>
<path d=""  transform="translate(27283, 840)"/>
<path d=""  transform="translate(27668, 840)"/>
<path d=""  transform="translate(28292, 840)"/>
<path d=""  transform="translate(29084, 840)"/>
<path d=""  transform="translate(29344, 840)"/>
<path d=""  transform="translate(29977, 840)"/>
<path d=""  transform="translate(30654, 840)"/>
<path d=""  transform="translate(31083, 840)"/>
<path d=""  transform="translate(31917, 840)"/>
<path d=""  transform="translate(32867, 840)"/>
<path d=""  transform="translate(33127, 840)"/>
<path d=""  transform="translate(34077, 840)"/>
<path d=""  transform="translate(34869, 840)"/>
<path d=""  transform="translate(35546, 840)"/>
<path d=""  transform="translate(36053, 840)"/>
<path d=""  transform="translate(36686, 840)"/>
<path d=""  transform="translate(36946, 840)"/>
<path d=""  transform="translate(37331, 840)"/>
<path d=""  transform="translate(37955, 840)"/>
<path d=""  transform="translate(38215, 840)"/>
<path d=""  transform="translate(39007, 840)"/>
<path d=""  transform="translate(40054, 840)"/>
<path d=""  transform="translate(40054, 840)"/>
<path d=""  transform="translate(40314, 840)"/>
<path d=""  transform="translate(40314, 840)"/>
<path d=""  transform="translate(40886, 840)"/>
<path d=""  transform="translate(41458, 840)"/>
<path d=""  transform="translate(41718, 840)"/>
<path d=""  transform="translate(42351, 840)"/>
<path d=""  transform="translate(42984, 840)"/>
<path d=""  transform="translate(43413, 840)"/>
<path d=""  transform="translate(44073, 840)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 44794 2130" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 840)"/>
<path d=""  transform="translate(633, 840)"/>
<path d=""  transform="translate(1310, 840)"/>
<path d=""  transform="translate(1817, 840)"/>
<path d=""  transform="translate(2523, 840)"/>
<path d=""  transform="translate(2974, 840)"/>
<path d=""  transform="translate(3234, 840)"/>
<path d=""  transform="translate(3867, 840)"/>
<path d=""  transform="translate(4544, 840)"/>
<path d=""  transform="translate(5517, 840)"/>
<path d=""  transform="translate(6516, 840)"/>
<path d=""  transform="translate(7176, 840)"/>
<path d=""  transform="translate(7627, 840)"/>
<path d=""  transform="translate(7887, 840)"/>
<path d=""  transform="translate(8520, 840)"/>
<path d=""  transform="translate(9152, 840)"/>
<path d=""  transform="translate(9812, 840)"/>
<path d=""  transform="translate(10263, 840)"/>
<path d=""  transform="translate(11310, 840)"/>
<path d=""  transform="translate(11975, 840)"/>
<path d=""  transform="translate(12235, 840)"/>
<path d=""  transform="translate(12868, 840)"/>
<path d=""  transform="translate(13841, 840)"/>
<path d=""  transform="translate(13841, 840)"/>
<path d=""  transform="translate(14101, 840)"/>
<path d=""  transform="translate(14101, 840)"/>
<path d=""  transform="translate(15100, 840)"/>
<path d=""  transform="translate(15724, 840)"/>
<path d=""  transform="translate(16723, 840)"/>
<path d=""  transform="translate(16983, 840)"/>
<path d=""  transform="translate(17616, 840)"/>
<path d=""  transform="translate(17996, 840)"/>
<path d=""  transform="translate(18990, 840)"/>
<path d=""  transform="translate(19650, 840)"/>
<path d=""  transform="translate(20079, 840)"/>
<path d=""  transform="translate(20703, 840)"/>
<path d=""  transform="translate(20963, 840)"/>
<path d=""  transform="translate(21343, 840)"/>
<path d=""  transform="translate(22337, 840)"/>
<path d=""  transform="translate(22597, 840)"/>
<path d=""  transform="translate(23104, 840)"/>
<path d=""  transform="translate(23591, 840)"/>
<path d=""  transform="translate(24492, 840)"/>
<path d=""  transform="translate(24752, 840)"/>
<path d=""  transform="translate(25385, 840)"/>
<path d=""  transform="translate(25804, 840)"/>
<path d=""  transform="translate(26189, 840)"/>
<path d=""  transform="translate(27023, 840)"/>
<path d=""  transform="translate(27283, 840)"/>
<path d=""  transform="translate(27668, 840)"/>
<path d=""  transform="translate(28292, 840)"/>
<path d=""  transform="translate(29084, 840)"/>
<path d=""  transform="translate(29344, 840)"/>
<path d=""  transform="translate(29977, 840)"/>
<path d=""  transform="translate(30654, 840)"/>
<path d=""  transform="translate(31083, 840)"/>
<path d=""  transform="translate(31917, 840)"/>
<path d=""  transform="translate(32867, 840)"/>
<path d=""  transform="translate(33127, 840)"/>
<path d=""  transform="translate(34077, 840)"/>
<path d=""  transform="translate(34869, 840)"/>
<path d=""  transform="translate(35546, 840)"/>
<path d=""  transform="translate(36053, 840)"/>
<path d=""  transform="translate(36686, 840)"/>
<path d=""  transform="translate(36946, 840)"/>
<path d=""  transform="translate(37331, 840)"/>
<path d=""  transform="translate(37955, 840)"/>
<path d=""  transform="translate(38215, 840)"/>
<path d=""  transform="translate(39007, 840)"/>
<path d=""  transform="translate(40054, 840)"/>
<path d=""  transform="translate(40054, 840)"/>
<path d=""  transform="translate(40314, 840)"/>
<path d=""  transform="translate(40314, 840)"/>
<path d=""  transform="translate(40914, 840)"/>
<path d=""  transform="translate(41514, 840)"/>
<path d=""  transform="translate(41774, 840)"/>
<path d=""  transform="translate(42407, 840)"/>
<path d=""  transform="translate(43040, 840)"/>
<path d=""  transform="translate(43469, 840)"/>
<path d=""  transform="translate(44129, 840)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐫅𐫃𐫇𐫡𐫀 𐫏𐫗 𐫓𐫀 𐫀𐫏𐫤𐫓𐫆𐫇‬ ‫𐫗 𐫆𐫞𐫇𐫤𐫀 𐫀𐫏𐫐 𐫀𐫍𐫅𐫅𐫀‬ ‫ 𐫖𐫓𐫇𐫀𐫀 26‬ ‫𐫐𐫓 𐫍𐫅 𐫀𐫏𐫤𐫓𐫆 𐫆𐫞𐫇𐫤𐫀 𐫓𐫏𐫇𐫓𐫛𐫗𐫀</span></li>


<pre>Expected: u10AC0.fina=77+633|u10AD7.init=76+380|u10ADB.fina=75+922|u10AD3.init=74+660|u10AC7=73+451|u10ACF.fina=72+507|u10AD3.init=71+660|space=70+260|u10AC0=69+633|u10AE4=68+677|u10AC7.fina=67+429|u10ADE.init=66+834|u10AC6=65+950|space=64+260|u10AC6=63+950|u10AD3=62+792|u10AE4=61+677|u10ACF.fina=60+507|u10AC0.init=59+633|space=58+260|u10AC5.fina=57+385|u10ACD.init=56+624|space=55+260|u10AD3=54+792|u10AD0=53+1047|space=52+0|space=51+260|space=50+0|.notdef=49+600|.notdef=48+600|space=47+260|u10AC0.fina=46+633|u10AC0.init=45+633|u10AC7.fina=44+429|u10AD3.medi=43+660|u10AD6.init=42+665|space=41+260|space=40+0|space=39+260|space=38+0|u10AC0=37+633|u10AC5=36+419|u10AC5.fina=35+385|u10ACD.init=34+624|u10AC0=33+633|space=32+260|u10AD0=31+1047|u10ACF.fina=30+507|u10AC0.init=29+633|space=28+260|u10AC0=27+633|u10AE4=26+677|u10AC7.fina=25+429|u10ADE.init=24+834|u10AC6=23+950|space=22+260|u10AD7=21+380|space=20+0|space=19+260|space=18+0|u10AC7=17+451|u10AC6=16+950|u10AD3=15+792|u10AE4=14+677|u10ACF.fina=13+507|u10AC0.init=12+633|space=11+260|u10AC0.fina=10+633|u10AD3.init=9+660|space=8+260|u10AD7=7+380|u10ACF=6+507|space=5+260|u10AC0=4+633|u10AE1=3+419|u10AC7.fina=2+429|u10AC3.init=1+427|u10AC5=0+419</pre>



<pre>Got     : u10AC0.fina=77+633|u10AD7.init=76+380|u10ADB.fina=75+922|u10AD3.init=74+660|u10AC7=73+451|u10ACF.fina=72+507|u10AD3.init=71+660|space=70+260|u10AC0=69+633|u10AE4=68+677|u10AC7.fina=67+429|u10ADE.init=66+834|u10AC6=65+950|space=64+260|u10AC6=63+950|u10AD3=62+792|u10AE4=61+677|u10ACF.fina=60+507|u10AC0.init=59+633|space=58+260|u10AC5.fina=57+385|u10ACD.init=56+624|space=55+260|u10AD3=54+792|u10AD0=53+1047|space=52+0|space=51+260|space=50+0|six=49+572|two=48+572|space=47+260|u10AC0.fina=46+633|u10AC0.init=45+633|u10AC7.fina=44+429|u10AD3.medi=43+660|u10AD6.init=42+665|space=41+260|space=40+0|space=39+260|space=38+0|u10AC0=37+633|u10AC5=36+419|u10AC5.fina=35+385|u10ACD.init=34+624|u10AC0=33+633|space=32+260|u10AD0=31+1047|u10ACF.fina=30+507|u10AC0.init=29+633|space=28+260|u10AC0=27+633|u10AE4=26+677|u10AC7.fina=25+429|u10ADE.init=24+834|u10AC6=23+950|space=22+260|u10AD7=21+380|space=20+0|space=19+260|space=18+0|u10AC7=17+451|u10AC6=16+950|u10AD3=15+792|u10AE4=14+677|u10ACF.fina=13+507|u10AC0.init=12+633|space=11+260|u10AC0.fina=10+633|u10AD3.init=9+660|space=8+260|u10AD7=7+380|u10ACF=6+507|space=5+260|u10AC0=4+633|u10AE1=3+419|u10AC7.fina=2+429|u10AC3.init=1+427|u10AC5=0+419</pre>



<pre>                                                                                                                                                                                                                                                                                                                                                                                                                                                                    ^^ ^^^^^^^^^^^^^^^^^^^^^^^^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 39508 2130" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 840)"/>
<path d=""  transform="translate(633, 840)"/>
<path d=""  transform="translate(1013, 840)"/>
<path d=""  transform="translate(1935, 840)"/>
<path d=""  transform="translate(2595, 840)"/>
<path d=""  transform="translate(3046, 840)"/>
<path d=""  transform="translate(3553, 840)"/>
<path d=""  transform="translate(4213, 840)"/>
<path d=""  transform="translate(4473, 840)"/>
<path d=""  transform="translate(5106, 840)"/>
<path d=""  transform="translate(5783, 840)"/>
<path d=""  transform="translate(6212, 840)"/>
<path d=""  transform="translate(7046, 840)"/>
<path d=""  transform="translate(7996, 840)"/>
<path d=""  transform="translate(8256, 840)"/>
<path d=""  transform="translate(9206, 840)"/>
<path d=""  transform="translate(9998, 840)"/>
<path d=""  transform="translate(10675, 840)"/>
<path d=""  transform="translate(11182, 840)"/>
<path d=""  transform="translate(11815, 840)"/>
<path d=""  transform="translate(12075, 840)"/>
<path d=""  transform="translate(12460, 840)"/>
<path d=""  transform="translate(13084, 840)"/>
<path d=""  transform="translate(13344, 840)"/>
<path d=""  transform="translate(14136, 840)"/>
<path d=""  transform="translate(15183, 840)"/>
<path d=""  transform="translate(15183, 840)"/>
<path d=""  transform="translate(15443, 840)"/>
<path d=""  transform="translate(15443, 840)"/>
<path d=""  transform="translate(16015, 840)"/>
<path d=""  transform="translate(16587, 840)"/>
<path d=""  transform="translate(16847, 840)"/>
<path d=""  transform="translate(17480, 840)"/>
<path d=""  transform="translate(18113, 840)"/>
<path d=""  transform="translate(18542, 840)"/>
<path d=""  transform="translate(19202, 840)"/>
<path d=""  transform="translate(19867, 840)"/>
<path d=""  transform="translate(20127, 840)"/>
<path d=""  transform="translate(20127, 840)"/>
<path d=""  transform="translate(20387, 840)"/>
<path d=""  transform="translate(20387, 840)"/>
<path d=""  transform="translate(21020, 840)"/>
<path d=""  transform="translate(21439, 840)"/>
<path d=""  transform="translate(21824, 840)"/>
<path d=""  transform="translate(22448, 840)"/>
<path d=""  transform="translate(23081, 840)"/>
<path d=""  transform="translate(23341, 840)"/>
<path d=""  transform="translate(24388, 840)"/>
<path d=""  transform="translate(24895, 840)"/>
<path d=""  transform="translate(25528, 840)"/>
<path d=""  transform="translate(25788, 840)"/>
<path d=""  transform="translate(26421, 840)"/>
<path d=""  transform="translate(27098, 840)"/>
<path d=""  transform="translate(27527, 840)"/>
<path d=""  transform="translate(28361, 840)"/>
<path d=""  transform="translate(29311, 840)"/>
<path d=""  transform="translate(29571, 840)"/>
<path d=""  transform="translate(29951, 840)"/>
<path d=""  transform="translate(29951, 840)"/>
<path d=""  transform="translate(30211, 840)"/>
<path d=""  transform="translate(30211, 840)"/>
<path d=""  transform="translate(30662, 840)"/>
<path d=""  transform="translate(31612, 840)"/>
<path d=""  transform="translate(32404, 840)"/>
<path d=""  transform="translate(33081, 840)"/>
<path d=""  transform="translate(33588, 840)"/>
<path d=""  transform="translate(34221, 840)"/>
<path d=""  transform="translate(34481, 840)"/>
<path d=""  transform="translate(35114, 840)"/>
<path d=""  transform="translate(35774, 840)"/>
<path d=""  transform="translate(36034, 840)"/>
<path d=""  transform="translate(36414, 840)"/>
<path d=""  transform="translate(36921, 840)"/>
<path d=""  transform="translate(37181, 840)"/>
<path d=""  transform="translate(37814, 840)"/>
<path d=""  transform="translate(38233, 840)"/>
<path d=""  transform="translate(38662, 840)"/>
<path d=""  transform="translate(39089, 840)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 39564 2130" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 840)"/>
<path d=""  transform="translate(633, 840)"/>
<path d=""  transform="translate(1013, 840)"/>
<path d=""  transform="translate(1935, 840)"/>
<path d=""  transform="translate(2595, 840)"/>
<path d=""  transform="translate(3046, 840)"/>
<path d=""  transform="translate(3553, 840)"/>
<path d=""  transform="translate(4213, 840)"/>
<path d=""  transform="translate(4473, 840)"/>
<path d=""  transform="translate(5106, 840)"/>
<path d=""  transform="translate(5783, 840)"/>
<path d=""  transform="translate(6212, 840)"/>
<path d=""  transform="translate(7046, 840)"/>
<path d=""  transform="translate(7996, 840)"/>
<path d=""  transform="translate(8256, 840)"/>
<path d=""  transform="translate(9206, 840)"/>
<path d=""  transform="translate(9998, 840)"/>
<path d=""  transform="translate(10675, 840)"/>
<path d=""  transform="translate(11182, 840)"/>
<path d=""  transform="translate(11815, 840)"/>
<path d=""  transform="translate(12075, 840)"/>
<path d=""  transform="translate(12460, 840)"/>
<path d=""  transform="translate(13084, 840)"/>
<path d=""  transform="translate(13344, 840)"/>
<path d=""  transform="translate(14136, 840)"/>
<path d=""  transform="translate(15183, 840)"/>
<path d=""  transform="translate(15183, 840)"/>
<path d=""  transform="translate(15443, 840)"/>
<path d=""  transform="translate(15443, 840)"/>
<path d=""  transform="translate(16043, 840)"/>
<path d=""  transform="translate(16643, 840)"/>
<path d=""  transform="translate(16903, 840)"/>
<path d=""  transform="translate(17536, 840)"/>
<path d=""  transform="translate(18169, 840)"/>
<path d=""  transform="translate(18598, 840)"/>
<path d=""  transform="translate(19258, 840)"/>
<path d=""  transform="translate(19923, 840)"/>
<path d=""  transform="translate(20183, 840)"/>
<path d=""  transform="translate(20183, 840)"/>
<path d=""  transform="translate(20443, 840)"/>
<path d=""  transform="translate(20443, 840)"/>
<path d=""  transform="translate(21076, 840)"/>
<path d=""  transform="translate(21495, 840)"/>
<path d=""  transform="translate(21880, 840)"/>
<path d=""  transform="translate(22504, 840)"/>
<path d=""  transform="translate(23137, 840)"/>
<path d=""  transform="translate(23397, 840)"/>
<path d=""  transform="translate(24444, 840)"/>
<path d=""  transform="translate(24951, 840)"/>
<path d=""  transform="translate(25584, 840)"/>
<path d=""  transform="translate(25844, 840)"/>
<path d=""  transform="translate(26477, 840)"/>
<path d=""  transform="translate(27154, 840)"/>
<path d=""  transform="translate(27583, 840)"/>
<path d=""  transform="translate(28417, 840)"/>
<path d=""  transform="translate(29367, 840)"/>
<path d=""  transform="translate(29627, 840)"/>
<path d=""  transform="translate(30007, 840)"/>
<path d=""  transform="translate(30007, 840)"/>
<path d=""  transform="translate(30267, 840)"/>
<path d=""  transform="translate(30267, 840)"/>
<path d=""  transform="translate(30718, 840)"/>
<path d=""  transform="translate(31668, 840)"/>
<path d=""  transform="translate(32460, 840)"/>
<path d=""  transform="translate(33137, 840)"/>
<path d=""  transform="translate(33644, 840)"/>
<path d=""  transform="translate(34277, 840)"/>
<path d=""  transform="translate(34537, 840)"/>
<path d=""  transform="translate(35170, 840)"/>
<path d=""  transform="translate(35830, 840)"/>
<path d=""  transform="translate(36090, 840)"/>
<path d=""  transform="translate(36470, 840)"/>
<path d=""  transform="translate(36977, 840)"/>
<path d=""  transform="translate(37237, 840)"/>
<path d=""  transform="translate(37870, 840)"/>
<path d=""  transform="translate(38289, 840)"/>
<path d=""  transform="translate(38718, 840)"/>
<path d=""  transform="translate(39145, 840)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐫆𐫞𐫇𐫤𐫀 𐫓𐫃𐫁𐫏𐫤𐫀 𐫏𐫇𐫓𐫛𐫗𐫀 𐫞𐫀 𐫏𐫆𐫓𐫏𐫆𐫏‬ ‫ 𐫖𐫓𐫇𐫀𐫀 27‬ ‫𐫐𐫓 𐫍𐫅 𐫀𐫏𐫤𐫓𐫆 𐫆𐫞𐫇𐫤𐫀 𐫞𐫀 𐫢𐫡𐫐𐫤𐫀 𐫃𐫇 𐫍𐫏𐫀</span></li>


<pre>Expected: u10AC0=76+633|u10ACF.fina=75+507|u10ACD.init=74+624|space=73+260|u10AC7.fina=72+429|u10AC3.init=71+427|space=70+260|u10AC0=69+633|u10AE4=68+677|u10AD0=67+1047|u10AE1=66+419|u10AE2=65+973|space=64+260|u10AC0.fina=63+633|u10ADE.init=62+834|space=61+260|u10AC0=60+633|u10AE4=59+677|u10AC7.fina=58+429|u10ADE.init=57+834|u10AC6=56+950|space=55+260|u10AC6=54+950|u10AD3=53+792|u10AE4=52+677|u10ACF.fina=51+507|u10AC0.init=50+633|space=49+260|u10AC5.fina=48+385|u10ACD.init=47+624|space=46+260|u10AD3=45+792|u10AD0=44+1047|space=43+0|space=42+260|space=41+0|.notdef=40+600|.notdef=39+600|space=38+260|u10AC0.fina=37+633|u10AC0.init=36+633|u10AC7.fina=35+429|u10AD3.medi=34+660|u10AD6.init=33+665|space=32+260|space=31+0|space=30+260|space=29+0|u10ACF=28+507|u10AC6=27+950|u10ACF.fina=26+507|u10AD3.init=25+660|u10AC6=24+950|u10ACF=23+507|space=22+260|u10AC0.fina=21+633|u10ADE.init=20+834|space=19+260|u10AC0.fina=18+633|u10AD7.init=17+380|u10ADB.fina=16+922|u10AD3.init=15+660|u10AC7=14+451|u10ACF=13+507|space=12+260|u10AC0=11+633|u10AE4=10+677|u10ACF.fina=9+507|u10AC1.medi=8+706|u10AC3.medi=7+407|u10AD3.init=6+660|space=5+260|u10AC0=4+633|u10AE4=3+677|u10AC7.fina=2+429|u10ADE.init=1+834|u10AC6=0+950</pre>



<pre>Got     : u10AC0=76+633|u10ACF.fina=75+507|u10ACD.init=74+624|space=73+260|u10AC7.fina=72+429|u10AC3.init=71+427|space=70+260|u10AC0=69+633|u10AE4=68+677|u10AD0=67+1047|u10AE1=66+419|u10AE2=65+973|space=64+260|u10AC0.fina=63+633|u10ADE.init=62+834|space=61+260|u10AC0=60+633|u10AE4=59+677|u10AC7.fina=58+429|u10ADE.init=57+834|u10AC6=56+950|space=55+260|u10AC6=54+950|u10AD3=53+792|u10AE4=52+677|u10ACF.fina=51+507|u10AC0.init=50+633|space=49+260|u10AC5.fina=48+385|u10ACD.init=47+624|space=46+260|u10AD3=45+792|u10AD0=44+1047|space=43+0|space=42+260|space=41+0|seven=40+572|two=39+572|space=38+260|u10AC0.fina=37+633|u10AC0.init=36+633|u10AC7.fina=35+429|u10AD3.medi=34+660|u10AD6.init=33+665|space=32+260|space=31+0|space=30+260|space=29+0|u10ACF=28+507|u10AC6=27+950|u10ACF.fina=26+507|u10AD3.init=25+660|u10AC6=24+950|u10ACF=23+507|space=22+260|u10AC0.fina=21+633|u10ADE.init=20+834|space=19+260|u10AC0.fina=18+633|u10AD7.init=17+380|u10ADB.fina=16+922|u10AD3.init=15+660|u10AC7=14+451|u10ACF=13+507|space=12+260|u10AC0=11+633|u10AE4=10+677|u10ACF.fina=9+507|u10AC1.medi=8+706|u10AC3.medi=7+407|u10AD3.init=6+660|space=5+260|u10AC0=4+633|u10AE4=3+677|u10AC7.fina=2+429|u10ADE.init=1+834|u10AC6=0+950</pre>



<pre>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  ^^ ^^^^^^^^^^^^^^^^^^^^^^^^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 42044 2130" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 840)"/>
<path d=""  transform="translate(633, 840)"/>
<path d=""  transform="translate(1140, 840)"/>
<path d=""  transform="translate(1764, 840)"/>
<path d=""  transform="translate(2024, 840)"/>
<path d=""  transform="translate(2453, 840)"/>
<path d=""  transform="translate(2880, 840)"/>
<path d=""  transform="translate(3140, 840)"/>
<path d=""  transform="translate(3773, 840)"/>
<path d=""  transform="translate(4450, 840)"/>
<path d=""  transform="translate(5497, 840)"/>
<path d=""  transform="translate(5916, 840)"/>
<path d=""  transform="translate(6889, 840)"/>
<path d=""  transform="translate(7149, 840)"/>
<path d=""  transform="translate(7782, 840)"/>
<path d=""  transform="translate(8616, 840)"/>
<path d=""  transform="translate(8876, 840)"/>
<path d=""  transform="translate(9509, 840)"/>
<path d=""  transform="translate(10186, 840)"/>
<path d=""  transform="translate(10615, 840)"/>
<path d=""  transform="translate(11449, 840)"/>
<path d=""  transform="translate(12399, 840)"/>
<path d=""  transform="translate(12659, 840)"/>
<path d=""  transform="translate(13609, 840)"/>
<path d=""  transform="translate(14401, 840)"/>
<path d=""  transform="translate(15078, 840)"/>
<path d=""  transform="translate(15585, 840)"/>
<path d=""  transform="translate(16218, 840)"/>
<path d=""  transform="translate(16478, 840)"/>
<path d=""  transform="translate(16863, 840)"/>
<path d=""  transform="translate(17487, 840)"/>
<path d=""  transform="translate(17747, 840)"/>
<path d=""  transform="translate(18539, 840)"/>
<path d=""  transform="translate(19586, 840)"/>
<path d=""  transform="translate(19586, 840)"/>
<path d=""  transform="translate(19846, 840)"/>
<path d=""  transform="translate(19846, 840)"/>
<path d=""  transform="translate(20418, 840)"/>
<path d=""  transform="translate(20990, 840)"/>
<path d=""  transform="translate(21250, 840)"/>
<path d=""  transform="translate(21883, 840)"/>
<path d=""  transform="translate(22516, 840)"/>
<path d=""  transform="translate(22945, 840)"/>
<path d=""  transform="translate(23605, 840)"/>
<path d=""  transform="translate(24270, 840)"/>
<path d=""  transform="translate(24530, 840)"/>
<path d=""  transform="translate(24530, 840)"/>
<path d=""  transform="translate(24790, 840)"/>
<path d=""  transform="translate(24790, 840)"/>
<path d=""  transform="translate(25297, 840)"/>
<path d=""  transform="translate(26247, 840)"/>
<path d=""  transform="translate(26754, 840)"/>
<path d=""  transform="translate(27414, 840)"/>
<path d=""  transform="translate(28364, 840)"/>
<path d=""  transform="translate(28871, 840)"/>
<path d=""  transform="translate(29131, 840)"/>
<path d=""  transform="translate(29764, 840)"/>
<path d=""  transform="translate(30598, 840)"/>
<path d=""  transform="translate(30858, 840)"/>
<path d=""  transform="translate(31491, 840)"/>
<path d=""  transform="translate(31871, 840)"/>
<path d=""  transform="translate(32793, 840)"/>
<path d=""  transform="translate(33453, 840)"/>
<path d=""  transform="translate(33904, 840)"/>
<path d=""  transform="translate(34411, 840)"/>
<path d=""  transform="translate(34671, 840)"/>
<path d=""  transform="translate(35304, 840)"/>
<path d=""  transform="translate(35981, 840)"/>
<path d=""  transform="translate(36488, 840)"/>
<path d=""  transform="translate(37194, 840)"/>
<path d=""  transform="translate(37601, 840)"/>
<path d=""  transform="translate(38261, 840)"/>
<path d=""  transform="translate(38521, 840)"/>
<path d=""  transform="translate(39154, 840)"/>
<path d=""  transform="translate(39831, 840)"/>
<path d=""  transform="translate(40260, 840)"/>
<path d=""  transform="translate(41094, 840)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 42100 2130" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 840)"/>
<path d=""  transform="translate(633, 840)"/>
<path d=""  transform="translate(1140, 840)"/>
<path d=""  transform="translate(1764, 840)"/>
<path d=""  transform="translate(2024, 840)"/>
<path d=""  transform="translate(2453, 840)"/>
<path d=""  transform="translate(2880, 840)"/>
<path d=""  transform="translate(3140, 840)"/>
<path d=""  transform="translate(3773, 840)"/>
<path d=""  transform="translate(4450, 840)"/>
<path d=""  transform="translate(5497, 840)"/>
<path d=""  transform="translate(5916, 840)"/>
<path d=""  transform="translate(6889, 840)"/>
<path d=""  transform="translate(7149, 840)"/>
<path d=""  transform="translate(7782, 840)"/>
<path d=""  transform="translate(8616, 840)"/>
<path d=""  transform="translate(8876, 840)"/>
<path d=""  transform="translate(9509, 840)"/>
<path d=""  transform="translate(10186, 840)"/>
<path d=""  transform="translate(10615, 840)"/>
<path d=""  transform="translate(11449, 840)"/>
<path d=""  transform="translate(12399, 840)"/>
<path d=""  transform="translate(12659, 840)"/>
<path d=""  transform="translate(13609, 840)"/>
<path d=""  transform="translate(14401, 840)"/>
<path d=""  transform="translate(15078, 840)"/>
<path d=""  transform="translate(15585, 840)"/>
<path d=""  transform="translate(16218, 840)"/>
<path d=""  transform="translate(16478, 840)"/>
<path d=""  transform="translate(16863, 840)"/>
<path d=""  transform="translate(17487, 840)"/>
<path d=""  transform="translate(17747, 840)"/>
<path d=""  transform="translate(18539, 840)"/>
<path d=""  transform="translate(19586, 840)"/>
<path d=""  transform="translate(19586, 840)"/>
<path d=""  transform="translate(19846, 840)"/>
<path d=""  transform="translate(19846, 840)"/>
<path d=""  transform="translate(20446, 840)"/>
<path d=""  transform="translate(21046, 840)"/>
<path d=""  transform="translate(21306, 840)"/>
<path d=""  transform="translate(21939, 840)"/>
<path d=""  transform="translate(22572, 840)"/>
<path d=""  transform="translate(23001, 840)"/>
<path d=""  transform="translate(23661, 840)"/>
<path d=""  transform="translate(24326, 840)"/>
<path d=""  transform="translate(24586, 840)"/>
<path d=""  transform="translate(24586, 840)"/>
<path d=""  transform="translate(24846, 840)"/>
<path d=""  transform="translate(24846, 840)"/>
<path d=""  transform="translate(25353, 840)"/>
<path d=""  transform="translate(26303, 840)"/>
<path d=""  transform="translate(26810, 840)"/>
<path d=""  transform="translate(27470, 840)"/>
<path d=""  transform="translate(28420, 840)"/>
<path d=""  transform="translate(28927, 840)"/>
<path d=""  transform="translate(29187, 840)"/>
<path d=""  transform="translate(29820, 840)"/>
<path d=""  transform="translate(30654, 840)"/>
<path d=""  transform="translate(30914, 840)"/>
<path d=""  transform="translate(31547, 840)"/>
<path d=""  transform="translate(31927, 840)"/>
<path d=""  transform="translate(32849, 840)"/>
<path d=""  transform="translate(33509, 840)"/>
<path d=""  transform="translate(33960, 840)"/>
<path d=""  transform="translate(34467, 840)"/>
<path d=""  transform="translate(34727, 840)"/>
<path d=""  transform="translate(35360, 840)"/>
<path d=""  transform="translate(36037, 840)"/>
<path d=""  transform="translate(36544, 840)"/>
<path d=""  transform="translate(37250, 840)"/>
<path d=""  transform="translate(37657, 840)"/>
<path d=""  transform="translate(38317, 840)"/>
<path d=""  transform="translate(38577, 840)"/>
<path d=""  transform="translate(39210, 840)"/>
<path d=""  transform="translate(39887, 840)"/>
<path d=""  transform="translate(40316, 840)"/>
<path d=""  transform="translate(41150, 840)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐫀𐫖𐫗𐫀 𐫀𐫏𐫐𐫀 𐫆𐫇 𐫏𐫓𐫆 𐫘𐫏𐫇𐫖𐫀‬ ‫ 𐫖𐫓𐫇𐫀𐫀 28‬ ‫ 𐫐𐫓 𐫍𐫅 𐫀𐫏𐫤𐫓𐫆 𐫆𐫞𐫇𐫤𐫀 𐫞𐫀 𐫡𐫏𐫉𐫀 𐫢𐫇𐫤𐫛𐫏𐫀 𐫇𐫤𐫁𐫓𐫏𐫀</span></li>


<pre>Expected: u10AC0=76+633|u10ACF.fina=75+507|u10AD3.medi=74+660|u10AC1.init=73+706|u10AE4=72+677|u10AC7=71+451|space=70+260|u10AC0=69+633|u10ACF.fina=68+507|u10ADB.init=67+487|u10AE4=66+677|u10AC7=65+451|u10AE2=64+973|space=63+260|u10AC0=62+633|u10AC9=61+493|u10ACF=60+507|u10AE1=59+419|space=58+260|u10AC0.fina=57+633|u10ADE.init=56+834|space=55+260|u10AC0=54+633|u10AE4=53+677|u10AC7.fina=52+429|u10ADE.init=51+834|u10AC6=50+950|space=49+260|u10AC6=48+950|u10AD3=47+792|u10AE4=46+677|u10ACF.fina=45+507|u10AC0.init=44+633|space=43+260|u10AC5.fina=42+385|u10ACD.init=41+624|space=40+260|u10AD3=39+792|u10AD0=38+1047|space=37+260|space=36+0|space=35+260|space=34+0|.notdef=33+600|.notdef=32+600|space=31+260|u10AC0.fina=30+633|u10AC0.init=29+633|u10AC7.fina=28+429|u10AD3.medi=27+660|u10AD6.init=26+665|space=25+260|space=24+0|space=23+260|space=22+0|u10AC0.fina=21+633|u10AD6.init=20+665|u10AC7=19+451|u10ACF.fina=18+507|u10AD8.init=17+766|space=16+260|u10AC6=15+950|u10AD3=14+792|u10ACF=13+507|space=12+260|u10AC7=11+451|u10AC6=10+950|space=9+260|u10AC0=8+633|u10AD0=7+1047|u10ACF.fina=6+507|u10AC0.init=5+633|space=4+260|u10AC0.fina=3+633|u10AD7.init=2+380|u10AD6.fina=1+994|u10AC0.init=0+633</pre>



<pre>Got     : u10AC0=76+633|u10ACF.fina=75+507|u10AD3.medi=74+660|u10AC1.init=73+706|u10AE4=72+677|u10AC7=71+451|space=70+260|u10AC0=69+633|u10ACF.fina=68+507|u10ADB.init=67+487|u10AE4=66+677|u10AC7=65+451|u10AE2=64+973|space=63+260|u10AC0=62+633|u10AC9=61+493|u10ACF=60+507|u10AE1=59+419|space=58+260|u10AC0.fina=57+633|u10ADE.init=56+834|space=55+260|u10AC0=54+633|u10AE4=53+677|u10AC7.fina=52+429|u10ADE.init=51+834|u10AC6=50+950|space=49+260|u10AC6=48+950|u10AD3=47+792|u10AE4=46+677|u10ACF.fina=45+507|u10AC0.init=44+633|space=43+260|u10AC5.fina=42+385|u10ACD.init=41+624|space=40+260|u10AD3=39+792|u10AD0=38+1047|space=37+260|space=36+0|space=35+260|space=34+0|eight=33+572|two=32+572|space=31+260|u10AC0.fina=30+633|u10AC0.init=29+633|u10AC7.fina=28+429|u10AD3.medi=27+660|u10AD6.init=26+665|space=25+260|space=24+0|space=23+260|space=22+0|u10AC0.fina=21+633|u10AD6.init=20+665|u10AC7=19+451|u10ACF.fina=18+507|u10AD8.init=17+766|space=16+260|u10AC6=15+950|u10AD3=14+792|u10ACF=13+507|space=12+260|u10AC7=11+451|u10AC6=10+950|space=9+260|u10AC0=8+633|u10AD0=7+1047|u10ACF.fina=6+507|u10AC0.init=5+633|space=4+260|u10AC0.fina=3+633|u10AD7.init=2+380|u10AD6.fina=1+994|u10AC0.init=0+633</pre>



<pre>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       ^^ ^^^^^^^^^^^^^^^^^^^^^^^^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 41267 2130" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 840)"/>
<path d=""  transform="translate(633, 840)"/>
<path d=""  transform="translate(1140, 840)"/>
<path d=""  transform="translate(1800, 840)"/>
<path d=""  transform="translate(2506, 840)"/>
<path d=""  transform="translate(3183, 840)"/>
<path d=""  transform="translate(3634, 840)"/>
<path d=""  transform="translate(3894, 840)"/>
<path d=""  transform="translate(4527, 840)"/>
<path d=""  transform="translate(5034, 840)"/>
<path d=""  transform="translate(5521, 840)"/>
<path d=""  transform="translate(6198, 840)"/>
<path d=""  transform="translate(6649, 840)"/>
<path d=""  transform="translate(7622, 840)"/>
<path d=""  transform="translate(7882, 840)"/>
<path d=""  transform="translate(8515, 840)"/>
<path d=""  transform="translate(9008, 840)"/>
<path d=""  transform="translate(9515, 840)"/>
<path d=""  transform="translate(9934, 840)"/>
<path d=""  transform="translate(10194, 840)"/>
<path d=""  transform="translate(10827, 840)"/>
<path d=""  transform="translate(11661, 840)"/>
<path d=""  transform="translate(11921, 840)"/>
<path d=""  transform="translate(12554, 840)"/>
<path d=""  transform="translate(13231, 840)"/>
<path d=""  transform="translate(13660, 840)"/>
<path d=""  transform="translate(14494, 840)"/>
<path d=""  transform="translate(15444, 840)"/>
<path d=""  transform="translate(15704, 840)"/>
<path d=""  transform="translate(16654, 840)"/>
<path d=""  transform="translate(17446, 840)"/>
<path d=""  transform="translate(18123, 840)"/>
<path d=""  transform="translate(18630, 840)"/>
<path d=""  transform="translate(19263, 840)"/>
<path d=""  transform="translate(19523, 840)"/>
<path d=""  transform="translate(19908, 840)"/>
<path d=""  transform="translate(20532, 840)"/>
<path d=""  transform="translate(20792, 840)"/>
<path d=""  transform="translate(21584, 840)"/>
<path d=""  transform="translate(22631, 840)"/>
<path d=""  transform="translate(22891, 840)"/>
<path d=""  transform="translate(22891, 840)"/>
<path d=""  transform="translate(23151, 840)"/>
<path d=""  transform="translate(23151, 840)"/>
<path d=""  transform="translate(23723, 840)"/>
<path d=""  transform="translate(24295, 840)"/>
<path d=""  transform="translate(24555, 840)"/>
<path d=""  transform="translate(25188, 840)"/>
<path d=""  transform="translate(25821, 840)"/>
<path d=""  transform="translate(26250, 840)"/>
<path d=""  transform="translate(26910, 840)"/>
<path d=""  transform="translate(27575, 840)"/>
<path d=""  transform="translate(27835, 840)"/>
<path d=""  transform="translate(27835, 840)"/>
<path d=""  transform="translate(28095, 840)"/>
<path d=""  transform="translate(28095, 840)"/>
<path d=""  transform="translate(28728, 840)"/>
<path d=""  transform="translate(29393, 840)"/>
<path d=""  transform="translate(29844, 840)"/>
<path d=""  transform="translate(30351, 840)"/>
<path d=""  transform="translate(31117, 840)"/>
<path d=""  transform="translate(31377, 840)"/>
<path d=""  transform="translate(32327, 840)"/>
<path d=""  transform="translate(33119, 840)"/>
<path d=""  transform="translate(33626, 840)"/>
<path d=""  transform="translate(33886, 840)"/>
<path d=""  transform="translate(34337, 840)"/>
<path d=""  transform="translate(35287, 840)"/>
<path d=""  transform="translate(35547, 840)"/>
<path d=""  transform="translate(36180, 840)"/>
<path d=""  transform="translate(37227, 840)"/>
<path d=""  transform="translate(37734, 840)"/>
<path d=""  transform="translate(38367, 840)"/>
<path d=""  transform="translate(38627, 840)"/>
<path d=""  transform="translate(39260, 840)"/>
<path d=""  transform="translate(39640, 840)"/>
<path d=""  transform="translate(40634, 840)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 41323 2130" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 840)"/>
<path d=""  transform="translate(633, 840)"/>
<path d=""  transform="translate(1140, 840)"/>
<path d=""  transform="translate(1800, 840)"/>
<path d=""  transform="translate(2506, 840)"/>
<path d=""  transform="translate(3183, 840)"/>
<path d=""  transform="translate(3634, 840)"/>
<path d=""  transform="translate(3894, 840)"/>
<path d=""  transform="translate(4527, 840)"/>
<path d=""  transform="translate(5034, 840)"/>
<path d=""  transform="translate(5521, 840)"/>
<path d=""  transform="translate(6198, 840)"/>
<path d=""  transform="translate(6649, 840)"/>
<path d=""  transform="translate(7622, 840)"/>
<path d=""  transform="translate(7882, 840)"/>
<path d=""  transform="translate(8515, 840)"/>
<path d=""  transform="translate(9008, 840)"/>
<path d=""  transform="translate(9515, 840)"/>
<path d=""  transform="translate(9934, 840)"/>
<path d=""  transform="translate(10194, 840)"/>
<path d=""  transform="translate(10827, 840)"/>
<path d=""  transform="translate(11661, 840)"/>
<path d=""  transform="translate(11921, 840)"/>
<path d=""  transform="translate(12554, 840)"/>
<path d=""  transform="translate(13231, 840)"/>
<path d=""  transform="translate(13660, 840)"/>
<path d=""  transform="translate(14494, 840)"/>
<path d=""  transform="translate(15444, 840)"/>
<path d=""  transform="translate(15704, 840)"/>
<path d=""  transform="translate(16654, 840)"/>
<path d=""  transform="translate(17446, 840)"/>
<path d=""  transform="translate(18123, 840)"/>
<path d=""  transform="translate(18630, 840)"/>
<path d=""  transform="translate(19263, 840)"/>
<path d=""  transform="translate(19523, 840)"/>
<path d=""  transform="translate(19908, 840)"/>
<path d=""  transform="translate(20532, 840)"/>
<path d=""  transform="translate(20792, 840)"/>
<path d=""  transform="translate(21584, 840)"/>
<path d=""  transform="translate(22631, 840)"/>
<path d=""  transform="translate(22891, 840)"/>
<path d=""  transform="translate(22891, 840)"/>
<path d=""  transform="translate(23151, 840)"/>
<path d=""  transform="translate(23151, 840)"/>
<path d=""  transform="translate(23751, 840)"/>
<path d=""  transform="translate(24351, 840)"/>
<path d=""  transform="translate(24611, 840)"/>
<path d=""  transform="translate(25244, 840)"/>
<path d=""  transform="translate(25877, 840)"/>
<path d=""  transform="translate(26306, 840)"/>
<path d=""  transform="translate(26966, 840)"/>
<path d=""  transform="translate(27631, 840)"/>
<path d=""  transform="translate(27891, 840)"/>
<path d=""  transform="translate(27891, 840)"/>
<path d=""  transform="translate(28151, 840)"/>
<path d=""  transform="translate(28151, 840)"/>
<path d=""  transform="translate(28784, 840)"/>
<path d=""  transform="translate(29449, 840)"/>
<path d=""  transform="translate(29900, 840)"/>
<path d=""  transform="translate(30407, 840)"/>
<path d=""  transform="translate(31173, 840)"/>
<path d=""  transform="translate(31433, 840)"/>
<path d=""  transform="translate(32383, 840)"/>
<path d=""  transform="translate(33175, 840)"/>
<path d=""  transform="translate(33682, 840)"/>
<path d=""  transform="translate(33942, 840)"/>
<path d=""  transform="translate(34393, 840)"/>
<path d=""  transform="translate(35343, 840)"/>
<path d=""  transform="translate(35603, 840)"/>
<path d=""  transform="translate(36236, 840)"/>
<path d=""  transform="translate(37283, 840)"/>
<path d=""  transform="translate(37790, 840)"/>
<path d=""  transform="translate(38423, 840)"/>
<path d=""  transform="translate(38683, 840)"/>
<path d=""  transform="translate(39316, 840)"/>
<path d=""  transform="translate(39696, 840)"/>
<path d=""  transform="translate(40690, 840)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">29‬ ‫𐫐𐫓 𐫍𐫅 𐫀𐫗𐫢𐫀 𐫀𐫏𐫤𐫓𐫆 𐫇𐫃𐫁𐫇𐫤𐫀 𐫓𐫛𐫇𐫤 𐫢𐫇𐫤𐫛𐫇𐫤𐫀 𐫀𐫏𐫐𐫀 𐫖‬ ‫𐫎𐫇𐫡𐫗𐫇𐫤𐫀 𐫛𐫡𐫘𐫇𐫛𐫏𐫤𐫀 𐫏𐫓𐫆 𐫖𐫇𐫖𐫐𐫇𐫗‬</span></li>


<pre>Expected: space=78+0|u10AD7=77+380|u10AC7=76+451|u10AD0.fina=75+1047|u10AD6.init=74+665|u10AC7.fina=73+429|u10AD6.init=72+665|space=71+260|u10AC6=70+950|u10AD3=69+792|u10ACF=68+507|space=67+260|u10AC0=66+633|u10AE4=65+677|u10ACF.fina=64+507|u10ADB.init=63+487|u10AC7.fina=62+429|u10AD8.init=61+766|u10AE1.fina=60+385|u10ADB.init=59+487|space=58+260|u10AC0=57+633|u10AE4=56+677|u10AC7.fina=55+429|u10AD7.init=54+380|u10AE1=53+419|u10AC7=52+451|u10ACE=51+520|space=50+0|space=49+260|space=48+0|u10AD6=47+994|space=46+260|u10AC0=45+633|u10AD0=44+1047|u10ACF.fina=43+507|u10AC0.init=42+633|space=41+260|u10AC0=40+633|u10AE4=39+677|u10AC7.fina=38+429|u10ADB.init=37+487|u10AE4=36+677|u10AC7=35+451|u10AE2=34+973|space=33+260|u10AE4=32+677|u10AC7.fina=31+429|u10ADB.medi=30+487|u10AD3.init=29+660|space=28+260|u10AC0=27+633|u10AE4=26+677|u10AC7.fina=25+429|u10AC1.medi=24+706|u10AC3.init=23+427|u10AC7=22+451|space=21+260|u10AC6=20+950|u10AD3=19+792|u10AE4=18+677|u10ACF.fina=17+507|u10AC0.init=16+633|space=15+260|u10AC0=14+633|u10AE2=13+973|u10AD7=12+380|u10AC0=11+633|space=10+260|u10AC5.fina=9+385|u10ACD.init=8+624|space=7+260|u10AD3=6+792|u10AD0=5+1047|space=4+0|space=3+260|space=2+0|.notdef=1+600|.notdef=0+600</pre>



<pre>Got     : space=78+0|u10AD7=77+380|u10AC7=76+451|u10AD0.fina=75+1047|u10AD6.init=74+665|u10AC7.fina=73+429|u10AD6.init=72+665|space=71+260|u10AC6=70+950|u10AD3=69+792|u10ACF=68+507|space=67+260|u10AC0=66+633|u10AE4=65+677|u10ACF.fina=64+507|u10ADB.init=63+487|u10AC7.fina=62+429|u10AD8.init=61+766|u10AE1.fina=60+385|u10ADB.init=59+487|space=58+260|u10AC0=57+633|u10AE4=56+677|u10AC7.fina=55+429|u10AD7.init=54+380|u10AE1=53+419|u10AC7=52+451|u10ACE=51+520|space=50+0|space=49+260|space=48+0|u10AD6=47+994|space=46+260|u10AC0=45+633|u10AD0=44+1047|u10ACF.fina=43+507|u10AC0.init=42+633|space=41+260|u10AC0=40+633|u10AE4=39+677|u10AC7.fina=38+429|u10ADB.init=37+487|u10AE4=36+677|u10AC7=35+451|u10AE2=34+973|space=33+260|u10AE4=32+677|u10AC7.fina=31+429|u10ADB.medi=30+487|u10AD3.init=29+660|space=28+260|u10AC0=27+633|u10AE4=26+677|u10AC7.fina=25+429|u10AC1.medi=24+706|u10AC3.init=23+427|u10AC7=22+451|space=21+260|u10AC6=20+950|u10AD3=19+792|u10AE4=18+677|u10ACF.fina=17+507|u10AC0.init=16+633|space=15+260|u10AC0=14+633|u10AE2=13+973|u10AD7=12+380|u10AC0=11+633|space=10+260|u10AC5.fina=9+385|u10ACD.init=8+624|space=7+260|u10AD3=6+792|u10AD0=5+1047|space=4+0|space=3+260|space=2+0|nine=1+572|two=0+572</pre>



<pre>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 ^^ ^^^^^^^^^^^^^^^^^^^^^^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 41033 2130" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 840)"/>
<path d=""  transform="translate(0, 840)"/>
<path d=""  transform="translate(380, 840)"/>
<path d=""  transform="translate(831, 840)"/>
<path d=""  transform="translate(1878, 840)"/>
<path d=""  transform="translate(2543, 840)"/>
<path d=""  transform="translate(2972, 840)"/>
<path d=""  transform="translate(3637, 840)"/>
<path d=""  transform="translate(3897, 840)"/>
<path d=""  transform="translate(4847, 840)"/>
<path d=""  transform="translate(5639, 840)"/>
<path d=""  transform="translate(6146, 840)"/>
<path d=""  transform="translate(6406, 840)"/>
<path d=""  transform="translate(7039, 840)"/>
<path d=""  transform="translate(7716, 840)"/>
<path d=""  transform="translate(8223, 840)"/>
<path d=""  transform="translate(8710, 840)"/>
<path d=""  transform="translate(9139, 840)"/>
<path d=""  transform="translate(9905, 840)"/>
<path d=""  transform="translate(10290, 840)"/>
<path d=""  transform="translate(10777, 840)"/>
<path d=""  transform="translate(11037, 840)"/>
<path d=""  transform="translate(11670, 840)"/>
<path d=""  transform="translate(12347, 840)"/>
<path d=""  transform="translate(12776, 840)"/>
<path d=""  transform="translate(13156, 840)"/>
<path d=""  transform="translate(13575, 840)"/>
<path d=""  transform="translate(14026, 840)"/>
<path d=""  transform="translate(14546, 840)"/>
<path d=""  transform="translate(14546, 840)"/>
<path d=""  transform="translate(14806, 840)"/>
<path d=""  transform="translate(14806, 840)"/>
<path d=""  transform="translate(15800, 840)"/>
<path d=""  transform="translate(16060, 840)"/>
<path d=""  transform="translate(16693, 840)"/>
<path d=""  transform="translate(17740, 840)"/>
<path d=""  transform="translate(18247, 840)"/>
<path d=""  transform="translate(18880, 840)"/>
<path d=""  transform="translate(19140, 840)"/>
<path d=""  transform="translate(19773, 840)"/>
<path d=""  transform="translate(20450, 840)"/>
<path d=""  transform="translate(20879, 840)"/>
<path d=""  transform="translate(21366, 840)"/>
<path d=""  transform="translate(22043, 840)"/>
<path d=""  transform="translate(22494, 840)"/>
<path d=""  transform="translate(23467, 840)"/>
<path d=""  transform="translate(23727, 840)"/>
<path d=""  transform="translate(24404, 840)"/>
<path d=""  transform="translate(24833, 840)"/>
<path d=""  transform="translate(25320, 840)"/>
<path d=""  transform="translate(25980, 840)"/>
<path d=""  transform="translate(26240, 840)"/>
<path d=""  transform="translate(26873, 840)"/>
<path d=""  transform="translate(27550, 840)"/>
<path d=""  transform="translate(27979, 840)"/>
<path d=""  transform="translate(28685, 840)"/>
<path d=""  transform="translate(29112, 840)"/>
<path d=""  transform="translate(29563, 840)"/>
<path d=""  transform="translate(29823, 840)"/>
<path d=""  transform="translate(30773, 840)"/>
<path d=""  transform="translate(31565, 840)"/>
<path d=""  transform="translate(32242, 840)"/>
<path d=""  transform="translate(32749, 840)"/>
<path d=""  transform="translate(33382, 840)"/>
<path d=""  transform="translate(33642, 840)"/>
<path d=""  transform="translate(34275, 840)"/>
<path d=""  transform="translate(35248, 840)"/>
<path d=""  transform="translate(35628, 840)"/>
<path d=""  transform="translate(36261, 840)"/>
<path d=""  transform="translate(36521, 840)"/>
<path d=""  transform="translate(36906, 840)"/>
<path d=""  transform="translate(37530, 840)"/>
<path d=""  transform="translate(37790, 840)"/>
<path d=""  transform="translate(38582, 840)"/>
<path d=""  transform="translate(39629, 840)"/>
<path d=""  transform="translate(39629, 840)"/>
<path d=""  transform="translate(39889, 840)"/>
<path d=""  transform="translate(39889, 840)"/>
<path d=""  transform="translate(40461, 840)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 41089 2130" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 840)"/>
<path d=""  transform="translate(0, 840)"/>
<path d=""  transform="translate(380, 840)"/>
<path d=""  transform="translate(831, 840)"/>
<path d=""  transform="translate(1878, 840)"/>
<path d=""  transform="translate(2543, 840)"/>
<path d=""  transform="translate(2972, 840)"/>
<path d=""  transform="translate(3637, 840)"/>
<path d=""  transform="translate(3897, 840)"/>
<path d=""  transform="translate(4847, 840)"/>
<path d=""  transform="translate(5639, 840)"/>
<path d=""  transform="translate(6146, 840)"/>
<path d=""  transform="translate(6406, 840)"/>
<path d=""  transform="translate(7039, 840)"/>
<path d=""  transform="translate(7716, 840)"/>
<path d=""  transform="translate(8223, 840)"/>
<path d=""  transform="translate(8710, 840)"/>
<path d=""  transform="translate(9139, 840)"/>
<path d=""  transform="translate(9905, 840)"/>
<path d=""  transform="translate(10290, 840)"/>
<path d=""  transform="translate(10777, 840)"/>
<path d=""  transform="translate(11037, 840)"/>
<path d=""  transform="translate(11670, 840)"/>
<path d=""  transform="translate(12347, 840)"/>
<path d=""  transform="translate(12776, 840)"/>
<path d=""  transform="translate(13156, 840)"/>
<path d=""  transform="translate(13575, 840)"/>
<path d=""  transform="translate(14026, 840)"/>
<path d=""  transform="translate(14546, 840)"/>
<path d=""  transform="translate(14546, 840)"/>
<path d=""  transform="translate(14806, 840)"/>
<path d=""  transform="translate(14806, 840)"/>
<path d=""  transform="translate(15800, 840)"/>
<path d=""  transform="translate(16060, 840)"/>
<path d=""  transform="translate(16693, 840)"/>
<path d=""  transform="translate(17740, 840)"/>
<path d=""  transform="translate(18247, 840)"/>
<path d=""  transform="translate(18880, 840)"/>
<path d=""  transform="translate(19140, 840)"/>
<path d=""  transform="translate(19773, 840)"/>
<path d=""  transform="translate(20450, 840)"/>
<path d=""  transform="translate(20879, 840)"/>
<path d=""  transform="translate(21366, 840)"/>
<path d=""  transform="translate(22043, 840)"/>
<path d=""  transform="translate(22494, 840)"/>
<path d=""  transform="translate(23467, 840)"/>
<path d=""  transform="translate(23727, 840)"/>
<path d=""  transform="translate(24404, 840)"/>
<path d=""  transform="translate(24833, 840)"/>
<path d=""  transform="translate(25320, 840)"/>
<path d=""  transform="translate(25980, 840)"/>
<path d=""  transform="translate(26240, 840)"/>
<path d=""  transform="translate(26873, 840)"/>
<path d=""  transform="translate(27550, 840)"/>
<path d=""  transform="translate(27979, 840)"/>
<path d=""  transform="translate(28685, 840)"/>
<path d=""  transform="translate(29112, 840)"/>
<path d=""  transform="translate(29563, 840)"/>
<path d=""  transform="translate(29823, 840)"/>
<path d=""  transform="translate(30773, 840)"/>
<path d=""  transform="translate(31565, 840)"/>
<path d=""  transform="translate(32242, 840)"/>
<path d=""  transform="translate(32749, 840)"/>
<path d=""  transform="translate(33382, 840)"/>
<path d=""  transform="translate(33642, 840)"/>
<path d=""  transform="translate(34275, 840)"/>
<path d=""  transform="translate(35248, 840)"/>
<path d=""  transform="translate(35628, 840)"/>
<path d=""  transform="translate(36261, 840)"/>
<path d=""  transform="translate(36521, 840)"/>
<path d=""  transform="translate(36906, 840)"/>
<path d=""  transform="translate(37530, 840)"/>
<path d=""  transform="translate(37790, 840)"/>
<path d=""  transform="translate(38582, 840)"/>
<path d=""  transform="translate(39629, 840)"/>
<path d=""  transform="translate(39629, 840)"/>
<path d=""  transform="translate(39889, 840)"/>
<path d=""  transform="translate(39889, 840)"/>
<path d=""  transform="translate(40489, 840)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐫅𐫀𐫖𐫇𐫤𐫀 𐫖𐫍𐫏𐫅‬ ‫𐫀‬ ‫ 𐫖𐫓𐫇𐫀𐫀 30‬ ‫ 𐫖𐫗𐫅𐫏𐫗𐫀 𐫅𐫓𐫏𐫗𐫀 𐫛𐫏𐫢𐫀 𐫖𐫇𐫤𐫍𐫡𐫀 𐫃𐫇 𐫀𐫆𐫀 𐫁𐫇𐫅𐫞𐫀 𐫃𐫡𐫃 𐫓𐫀 𐫛𐫏‬</span></li>


<pre>Expected: space=78+0|u10ACF.fina=77+507|u10ADB.init=76+487|space=75+260|u10AC0.fina=74+633|u10AD3.init=73+660|space=72+260|u10AC3=71+529|u10AE1.fina=70+385|u10AC3.init=69+427|space=68+260|u10AC0.fina=67+633|u10ADE.init=66+834|u10AC5=65+419|u10AC7.fina=64+429|u10AC1.init=63+706|space=62+260|u10AC0=61+633|u10AC6=60+950|u10AC0=59+633|space=58+260|u10AC7.fina=57+429|u10AC3.init=56+427|space=55+260|u10AC0=54+633|u10AE1.fina=53+385|u10ACD.init=52+624|u10AE4=51+677|u10AC7.fina=50+429|u10AD6.init=49+665|space=48+260|u10AC0=47+633|u10AE2=46+973|u10ACF.fina=45+507|u10ADB.init=44+487|space=43+260|u10AC0.fina=42+633|u10AD7.init=41+380|u10ACF.fina=40+507|u10AD3.init=39+660|u10AC5=38+419|space=37+260|u10AC0.fina=36+633|u10AD7.init=35+380|u10ACF=34+507|u10AC5.fina=33+385|u10AD7.init=32+380|u10AD6=31+994|space=30+260|space=29+0|space=28+260|space=27+0|.notdef=26+600|.notdef=25+600|space=24+260|u10AC0.fina=23+633|u10AC0.init=22+633|u10AC7.fina=21+429|u10AD3.medi=20+660|u10AD6.init=19+665|space=18+260|space=17+0|space=16+260|space=15+0|u10AC0=14+633|space=13+0|space=12+260|space=11+0|u10AC5=10+419|u10ACF.fina=9+507|u10ACD.init=8+624|u10AD6=7+994|space=6+260|u10AC0=5+633|u10AE4=4+677|u10AC7.fina=3+429|u10AD6.medi=2+665|u10AC0.init=1+633|u10AC5=0+419</pre>



<pre>Got     : space=78+0|u10ACF.fina=77+507|u10ADB.init=76+487|space=75+260|u10AC0.fina=74+633|u10AD3.init=73+660|space=72+260|u10AC3=71+529|u10AE1.fina=70+385|u10AC3.init=69+427|space=68+260|u10AC0.fina=67+633|u10ADE.init=66+834|u10AC5=65+419|u10AC7.fina=64+429|u10AC1.init=63+706|space=62+260|u10AC0=61+633|u10AC6=60+950|u10AC0=59+633|space=58+260|u10AC7.fina=57+429|u10AC3.init=56+427|space=55+260|u10AC0=54+633|u10AE1.fina=53+385|u10ACD.init=52+624|u10AE4=51+677|u10AC7.fina=50+429|u10AD6.init=49+665|space=48+260|u10AC0=47+633|u10AE2=46+973|u10ACF.fina=45+507|u10ADB.init=44+487|space=43+260|u10AC0.fina=42+633|u10AD7.init=41+380|u10ACF.fina=40+507|u10AD3.init=39+660|u10AC5=38+419|space=37+260|u10AC0.fina=36+633|u10AD7.init=35+380|u10ACF=34+507|u10AC5.fina=33+385|u10AD7.init=32+380|u10AD6=31+994|space=30+260|space=29+0|space=28+260|space=27+0|zero=26+572|three=25+572|space=24+260|u10AC0.fina=23+633|u10AC0.init=22+633|u10AC7.fina=21+429|u10AD3.medi=20+660|u10AD6.init=19+665|space=18+260|space=17+0|space=16+260|space=15+0|u10AC0=14+633|space=13+0|space=12+260|space=11+0|u10AC5=10+419|u10ACF.fina=9+507|u10ACD.init=8+624|u10AD6=7+994|space=6+260|u10AC0=5+633|u10AE4=4+677|u10AC7.fina=3+429|u10AD6.medi=2+665|u10AC0.init=1+633|u10AC5=0+419</pre>



<pre>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                ^^ ^^^^^^^^^^^^^^^^^^^^^^^^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 36569 2130" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 840)"/>
<path d=""  transform="translate(0, 840)"/>
<path d=""  transform="translate(507, 840)"/>
<path d=""  transform="translate(994, 840)"/>
<path d=""  transform="translate(1254, 840)"/>
<path d=""  transform="translate(1887, 840)"/>
<path d=""  transform="translate(2547, 840)"/>
<path d=""  transform="translate(2807, 840)"/>
<path d=""  transform="translate(3336, 840)"/>
<path d=""  transform="translate(3721, 840)"/>
<path d=""  transform="translate(4148, 840)"/>
<path d=""  transform="translate(4408, 840)"/>
<path d=""  transform="translate(5041, 840)"/>
<path d=""  transform="translate(5875, 840)"/>
<path d=""  transform="translate(6294, 840)"/>
<path d=""  transform="translate(6723, 840)"/>
<path d=""  transform="translate(7429, 840)"/>
<path d=""  transform="translate(7689, 840)"/>
<path d=""  transform="translate(8322, 840)"/>
<path d=""  transform="translate(9272, 840)"/>
<path d=""  transform="translate(9905, 840)"/>
<path d=""  transform="translate(10165, 840)"/>
<path d=""  transform="translate(10594, 840)"/>
<path d=""  transform="translate(11021, 840)"/>
<path d=""  transform="translate(11281, 840)"/>
<path d=""  transform="translate(11914, 840)"/>
<path d=""  transform="translate(12299, 840)"/>
<path d=""  transform="translate(12923, 840)"/>
<path d=""  transform="translate(13600, 840)"/>
<path d=""  transform="translate(14029, 840)"/>
<path d=""  transform="translate(14694, 840)"/>
<path d=""  transform="translate(14954, 840)"/>
<path d=""  transform="translate(15587, 840)"/>
<path d=""  transform="translate(16560, 840)"/>
<path d=""  transform="translate(17067, 840)"/>
<path d=""  transform="translate(17554, 840)"/>
<path d=""  transform="translate(17814, 840)"/>
<path d=""  transform="translate(18447, 840)"/>
<path d=""  transform="translate(18827, 840)"/>
<path d=""  transform="translate(19334, 840)"/>
<path d=""  transform="translate(19994, 840)"/>
<path d=""  transform="translate(20413, 840)"/>
<path d=""  transform="translate(20673, 840)"/>
<path d=""  transform="translate(21306, 840)"/>
<path d=""  transform="translate(21686, 840)"/>
<path d=""  transform="translate(22193, 840)"/>
<path d=""  transform="translate(22578, 840)"/>
<path d=""  transform="translate(22958, 840)"/>
<path d=""  transform="translate(23952, 840)"/>
<path d=""  transform="translate(24212, 840)"/>
<path d=""  transform="translate(24212, 840)"/>
<path d=""  transform="translate(24472, 840)"/>
<path d=""  transform="translate(24472, 840)"/>
<path d=""  transform="translate(25044, 840)"/>
<path d=""  transform="translate(25616, 840)"/>
<path d=""  transform="translate(25876, 840)"/>
<path d=""  transform="translate(26509, 840)"/>
<path d=""  transform="translate(27142, 840)"/>
<path d=""  transform="translate(27571, 840)"/>
<path d=""  transform="translate(28231, 840)"/>
<path d=""  transform="translate(28896, 840)"/>
<path d=""  transform="translate(29156, 840)"/>
<path d=""  transform="translate(29156, 840)"/>
<path d=""  transform="translate(29416, 840)"/>
<path d=""  transform="translate(29416, 840)"/>
<path d=""  transform="translate(30049, 840)"/>
<path d=""  transform="translate(30049, 840)"/>
<path d=""  transform="translate(30309, 840)"/>
<path d=""  transform="translate(30309, 840)"/>
<path d=""  transform="translate(30728, 840)"/>
<path d=""  transform="translate(31235, 840)"/>
<path d=""  transform="translate(31859, 840)"/>
<path d=""  transform="translate(32853, 840)"/>
<path d=""  transform="translate(33113, 840)"/>
<path d=""  transform="translate(33746, 840)"/>
<path d=""  transform="translate(34423, 840)"/>
<path d=""  transform="translate(34852, 840)"/>
<path d=""  transform="translate(35517, 840)"/>
<path d=""  transform="translate(36150, 840)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 36625 2130" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 840)"/>
<path d=""  transform="translate(0, 840)"/>
<path d=""  transform="translate(507, 840)"/>
<path d=""  transform="translate(994, 840)"/>
<path d=""  transform="translate(1254, 840)"/>
<path d=""  transform="translate(1887, 840)"/>
<path d=""  transform="translate(2547, 840)"/>
<path d=""  transform="translate(2807, 840)"/>
<path d=""  transform="translate(3336, 840)"/>
<path d=""  transform="translate(3721, 840)"/>
<path d=""  transform="translate(4148, 840)"/>
<path d=""  transform="translate(4408, 840)"/>
<path d=""  transform="translate(5041, 840)"/>
<path d=""  transform="translate(5875, 840)"/>
<path d=""  transform="translate(6294, 840)"/>
<path d=""  transform="translate(6723, 840)"/>
<path d=""  transform="translate(7429, 840)"/>
<path d=""  transform="translate(7689, 840)"/>
<path d=""  transform="translate(8322, 840)"/>
<path d=""  transform="translate(9272, 840)"/>
<path d=""  transform="translate(9905, 840)"/>
<path d=""  transform="translate(10165, 840)"/>
<path d=""  transform="translate(10594, 840)"/>
<path d=""  transform="translate(11021, 840)"/>
<path d=""  transform="translate(11281, 840)"/>
<path d=""  transform="translate(11914, 840)"/>
<path d=""  transform="translate(12299, 840)"/>
<path d=""  transform="translate(12923, 840)"/>
<path d=""  transform="translate(13600, 840)"/>
<path d=""  transform="translate(14029, 840)"/>
<path d=""  transform="translate(14694, 840)"/>
<path d=""  transform="translate(14954, 840)"/>
<path d=""  transform="translate(15587, 840)"/>
<path d=""  transform="translate(16560, 840)"/>
<path d=""  transform="translate(17067, 840)"/>
<path d=""  transform="translate(17554, 840)"/>
<path d=""  transform="translate(17814, 840)"/>
<path d=""  transform="translate(18447, 840)"/>
<path d=""  transform="translate(18827, 840)"/>
<path d=""  transform="translate(19334, 840)"/>
<path d=""  transform="translate(19994, 840)"/>
<path d=""  transform="translate(20413, 840)"/>
<path d=""  transform="translate(20673, 840)"/>
<path d=""  transform="translate(21306, 840)"/>
<path d=""  transform="translate(21686, 840)"/>
<path d=""  transform="translate(22193, 840)"/>
<path d=""  transform="translate(22578, 840)"/>
<path d=""  transform="translate(22958, 840)"/>
<path d=""  transform="translate(23952, 840)"/>
<path d=""  transform="translate(24212, 840)"/>
<path d=""  transform="translate(24212, 840)"/>
<path d=""  transform="translate(24472, 840)"/>
<path d=""  transform="translate(24472, 840)"/>
<path d=""  transform="translate(25072, 840)"/>
<path d=""  transform="translate(25672, 840)"/>
<path d=""  transform="translate(25932, 840)"/>
<path d=""  transform="translate(26565, 840)"/>
<path d=""  transform="translate(27198, 840)"/>
<path d=""  transform="translate(27627, 840)"/>
<path d=""  transform="translate(28287, 840)"/>
<path d=""  transform="translate(28952, 840)"/>
<path d=""  transform="translate(29212, 840)"/>
<path d=""  transform="translate(29212, 840)"/>
<path d=""  transform="translate(29472, 840)"/>
<path d=""  transform="translate(29472, 840)"/>
<path d=""  transform="translate(30105, 840)"/>
<path d=""  transform="translate(30105, 840)"/>
<path d=""  transform="translate(30365, 840)"/>
<path d=""  transform="translate(30365, 840)"/>
<path d=""  transform="translate(30784, 840)"/>
<path d=""  transform="translate(31291, 840)"/>
<path d=""  transform="translate(31915, 840)"/>
<path d=""  transform="translate(32909, 840)"/>
<path d=""  transform="translate(33169, 840)"/>
<path d=""  transform="translate(33802, 840)"/>
<path d=""  transform="translate(34479, 840)"/>
<path d=""  transform="translate(34908, 840)"/>
<path d=""  transform="translate(35573, 840)"/>
<path d=""  transform="translate(36206, 840)"/>
</svg>


</div> [code: shaping-regression]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni00A0.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni0308 (U+0308), uni030A (U+030A), uni030B (U+030B) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* u10AC4 (U+10AC4): L<<310.0,-68.0>--<308.0,-63.0>> -> L<<308.0,-63.0>--<283.0,0.0>> [code: found-colinear-vectors]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 6 | 5 | 115 | 8 | 101 | 0 |
| 0% | 3% | 2% | 49% | 3% | 43% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**