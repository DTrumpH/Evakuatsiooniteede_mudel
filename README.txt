KOODI JOOKSUTAMISEKS VAJALIKUD DEM-id SAAB MAA-AMETILT VÕI TÖÖ AUTORITELT. GITHUB-I ANDMELIMIIT EI LASE SUURI RASTERFAILE SEAL HOIUSTADA.

Projekt koosneb kahest skriptist:

1. Data_preprocessing - Skript keskendub andmetöötlusele ja kontrollile.
	DEM Kõrgusandmed saadi maa-ametist kaardilehe numbrid (53633, 53721, 		53722, 53731). Need neli kaardilehte liidetakse kokku üheks kaardiks.

2. Evac_model - Skript leiab teekonnad alguspunktidest lõpp-punktideni 	kasutades raster ja vektor meetodeid.

Puuduolevad failid:

Kõrgusmudeli kaardilehed
1."53633_dtm_1m.tif"
2."53721_dtm_1m.tif"
3."53722_dtm_1m.tif"
4."53731_dtm_1m.tif"

Liitetud kõrgusmudel
1."merged_DEM_1m.tif"

Veesügavuse rastrid
1."water_depth_scenario1.tif"
2."water_depth_scenario2.tif"
3."water_depth_scenario3.tif"

Kogu koodi jooksutamiseks on vajalik ainult kõrgusmudeli kaardilehed. Teised puuduolevad failid saab koodi rakendades arvutada.

Töö autorid: Mihkel Paal, Daniel Henri Trump, Iris Luik, Ülle Kass
