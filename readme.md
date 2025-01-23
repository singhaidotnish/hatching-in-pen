![new-pexels-alara-thorn-2148851274-30351491.jpg](../../Downloads/ffmpeg-images/output/new-pexels-alara-thorn-2148851274-30351491.jpg)
![new-pexels-andre-tran-86421513-12487241.jpg](../../Downloads/ffmpeg-images/output/new-pexels-andre-tran-86421513-12487241.jpg)
![new-pexels-anh-nguyen-517648218-30323170.jpg](../../Downloads/ffmpeg-images/output/new-pexels-anh-nguyen-517648218-30323170.jpg)
![new-pexels-chris-schippers-139261-421927.jpg](../../Downloads/ffmpeg-images/output/new-pexels-chris-schippers-139261-421927.jpg)
![new-pexels-chris-spain-1559126760-27303085.jpg](../../Downloads/ffmpeg-images/output/new-pexels-chris-spain-1559126760-27303085.jpg)
![new-pexels-erik-karits-2093459-3737300.jpg](../../Downloads/ffmpeg-images/output/new-pexels-erik-karits-2093459-3737300.jpg)
![new-pexels-felixmittermeier-957024.jpg](../../Downloads/ffmpeg-images/output/new-pexels-felixmittermeier-957024.jpg)
![new-pexels-fox-58267-30319472.jpg](../../Downloads/ffmpeg-images/output/new-pexels-fox-58267-30319472.jpg)
![new-pexels-francesco-ungaro-1671325.jpg](../../Downloads/ffmpeg-images/output/new-pexels-francesco-ungaro-1671325.jpg)
![new-pexels-jvdm-1564839.jpg](../../Downloads/ffmpeg-images/output/new-pexels-jvdm-1564839.jpg)
![new-pexels-matthias-oben-2060028-3687957.jpg](../../Downloads/ffmpeg-images/output/new-pexels-matthias-oben-2060028-3687957.jpg)
![new-pexels-pixabay-53435.jpg](../../Downloads/ffmpeg-images/output/new-pexels-pixabay-53435.jpg)
![new-pexels-pixabay-60611.jpg](../../Downloads/ffmpeg-images/output/new-pexels-pixabay-60611.jpg)
![new-pexels-pixabay-357159.jpg](../../Downloads/ffmpeg-images/output/new-pexels-pixabay-357159.jpg)
![new-pexels-tobiasbjorkli-2360684.jpg](../../Downloads/ffmpeg-images/output/new-pexels-tobiasbjorkli-2360684.jpg)
![new-pexels-veeterzy-38136.jpg](../../Downloads/ffmpeg-images/output/new-pexels-veeterzy-38136.jpg)


### for i in *.*; do ffmpeg -i "$i" -vf hue=s=0 output/new-"$i"; done