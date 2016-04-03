all: 20160403_PJLNum_AmendementsCommission.pdf

20160403_PJLNum_AmendementsCommission.pdf: 20160403_PJLNum_AmendementsCommission.md logo.png header.md
	cat header.md 20160403_PJLNum_AmendementsCommission.md | sed 's/^\(#[^#]\)/\\newpage\n\n\1/' | pandoc --variable=lang:fr -s -S --toc --toc-depth=1 -o 20160403_PJLNum_AmendementsCommission.pdf /dev/stdin
