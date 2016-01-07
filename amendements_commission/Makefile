all: 20150107_PJLNum_AmendementsCommission.pdf

20150107_PJLNum_AmendementsCommission.pdf: 20150107_PJLNum_AmendementsCommission.md header.md
	cat header.md 20150107_PJLNum_AmendementsCommission.md | pandoc --variable=lang:french -s -S --toc --toc-depth=1 -o 20150107_PJLNum_AmendementsCommission.pdf /dev/stdin
