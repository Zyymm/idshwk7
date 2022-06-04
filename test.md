利用LSB算法将文本信息隐藏到png图片中

隐藏信息：python LSBSteg.py encode -i test.png -o encode.png -f info.txt

提取信息：python LSBSteg.py decode -i encode.png -o decode.txt
