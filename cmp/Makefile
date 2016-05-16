all: 20160515_PJLNum_CMP.pdf

20160515_PJLNum_CMP.pdf: 20160515_PJLNum_CMP.md logo.png header.md
	cat header.md 20160515_PJLNum_CMP.md | sed 's/^\(#[^#]\)/\\newpage\n\n\1/' | pandoc --variable=lang:fr -s -S -o 20160515_PJLNum_CMP.pdf /dev/stdin
