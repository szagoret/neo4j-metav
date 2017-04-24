all: model.png

%.png: %.dot
	dot -Tpng $^ -o $@

clean:
	rm *.png
