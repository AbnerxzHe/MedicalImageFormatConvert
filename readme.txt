1��
ConsoleApplication1.exe "image.kfb" image num
����1������·�������·�����ɡ�
����2������ļ��������numΪ2�����ļ����ֱ�Ϊimage0.jpeg, image1.jpeg, image2.jpeg
����3��numΪ�ָ�ĸ�������1��ʼ�ԣ���ˮƽ�ָ�ġ�

2,
convert +append image*.jpeg image.jpeg
������+append ��ʾˮƽƴ��

3��
convert image.jpeg -define tiff:tile-geometry=256x256 -compress LZW "ptif:image.tif"
����:image.jpegΪ����ͼƬ��LZWΪѹ���㷨��image.tifΪ���ͼƬ



