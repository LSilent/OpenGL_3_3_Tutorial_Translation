Math Cheatsheet
��ѧ������
����ѧ
Pi
���Һ�����
��λԲ
����
�������
����
���
���
�ӷ��ͼ���
�˷�
��һ��
����
���������˷�
�����������˷�
���õ�ת��

����ѧ
Pi
const float pi = 3.14159265f; // but an infinity of digits in reality
����������
(From http://commons.wikimedia.org/wiki/User:Geek3 , under GNU Free Documentation License )
��λԲ
( Modified from http://en.wikipedia.org/wiki/User:Gustavb under Crative Commons 3.0 )
t��ʾ���������һ���Ƕ�
0 radians = 0 degrees
180 degrees = Pi radians
360 degrees ( ��Բ) = 2*Pi radians
90 degrees = Pi/2 radians

����
ʱ����������ĸ�����ϵ�±�ʾ������������ϸ�ڲ鿴�������֡�
�������
һ����ά������(x, y, z),���������ϵ����ά������(x, y, z, w).
w=0 : ��ʾһ������
w=1 : ��ʾһ��λ��
else : ��Ȼ������ȷ�������֪��������ʲô.
һ�������������ֻ�ܳ���4*4�ľ���

����
�����ڵѿ������룺sqrt( x*x + y*y + z*z ). w����������.

���
( Modified from http://en.wikipedia.org/wiki/User:Acdx , former image under Creative Commons 3.0 )
��˷�����X��length( a x b ) == length(a)*length(b)������������ѽ��normalize()��

���
( from http://en.wikipedia.org/wiki/File:Dot_Product.svg )
A.B = length(A)*length(B)*cos(Theta) , ���Ǹ���ʱ�����ΪA.x*B.x +A.y*B.y +A.z*B.z

�ӷ��ͼ���
������ʽ :
res.x = A.x + B.x
res.y = A.y + B.y
...
 

�˷�
������ʽ:
res.x = A.x * B.x
res.y = A.y * B.y
...

��һ��
�������������ĳ��ȣ�
normalizedVector = vec * ( 1.0f / vec.length() )


����
���������˷�
��һ��ƽ�ƾ���Ϊ���ӣ�

���������˷�

���ñ任


...�����������ɫ���У�Ҳ���������߿ռ��б�ʾ����������������Ч����post-effects��ʱҲ������ͼ��ռ��б�ʾ��
�� but in your shaders, you can also represent your vectors in tangent space. And in image-space when you do post-effects.