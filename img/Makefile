.PHONY: all clean

pngs = ambulance.png \
       benasque.png \
       butterflies.png \
       cern_landscape.png \
       donkey.png \
	   anti_donkey.png \
       madamewu.png \
       mountains.png \
       rostock.png \
       wu.png \
       wu_flipped.png \
	   anti_wu.png \
	   anti_wu_flipped.png \
	   dracula.png \
	   et.png \
	   cattlemastication_nature1927.png \
	   cattlemastication_franklin1979.png \
	   cow.png \
	   newton.png \
	   rotated_coil.png \
	   iceberg.png \
	   antimatter_factory.png \
	   dirac.png \
	   cosmos.png \
	   ams02.png \
	   lhcb_logo.png \
	   cup.png \
	   lhcb_collaboration.png \
	   cern_map.png \
	   lhcb_detector.png \
	   bd2kpi_cpv.png \
	   bmbf.png \
	   uni_logo.png \
	   physik_logo.png \
	   cern_logo.png \
	   me.png \
	   lhcb_pit.png \
	   cpv_Bu2DK.png \
	   cpv_Bu2DK_key.png \
	   ams02_results.png

all: $(pngs)

clean:
	rm -f $(pngs)

%.png: original/%.png
	convert $< -resize 1920x1080\> $@

anti_%.png: %.png
	convert -negate $*.png $@

rotated_%.png: %.png
	convert -rotate "-90" $*.png $@
