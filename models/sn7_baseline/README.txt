# split weight file
mkdir weight_split
split -b 80m xdxd_final.pth weight_split/
# re-combine weight file
cat weight_split/* > xdxd_final.pth