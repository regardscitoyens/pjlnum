all: 20150114_PJLNum_AmendementsHemicycle.pdf

20150114_PJLNum_AmendementsHemicycle.pdf: 20150114_PJLNum_AmendementsHemicycle.md
	cat header.md 20150114_PJLNum_AmendementsHemicycle.md | sed 's/^\(#[^#]\)/\\newpage\n\n\1/' | pandoc --variable=lang:french -s -S --toc --toc-depth=1 -o 20150114_PJLNum_AmendementsHemicycle.pdf /dev/stdin
