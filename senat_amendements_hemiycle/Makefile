all: 20160419_PJLNum_AmendementsHemicycle.pdf

20160419_PJLNum_AmendementsHemicycle.pdf: 20160419_PJLNum_AmendementsHemicycle.md logo.png header.md
	cat header.md 20160419_PJLNum_AmendementsHemicycle.md | sed 's/^\(#[^#]\)/\\newpage\n\n\1/' | pandoc --variable=lang:fr -s -S --toc --toc-depth=1 -o 20160419_PJLNum_AmendementsHemicycle.pdf /dev/stdin
