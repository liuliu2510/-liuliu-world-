# -liuliu-world-
 liuliu world 
out<<"( "<<a.X<<" , "<<a.Y<<" )";
void printFrameCoord(Frame a)
printCoord(a.position[0]);
cout<<" - ";
printCoord(a.position[1]);
int drawMenu()
SetPos(30, 1);
cout<<"P l a n e  W a r";
drawRow(3, 0, 79, '-');
drawRow(5, 0, 79, '-');
SetPos(28, 4);
cout<<"w 和 s 选择， k 确定";
SetPos(15, 11);
cout<<"1. 简单的敌人";
SetPos(51, 13);
cout<<"简单敌人有着较慢的移动速度。";
SetPos(24, 21);
cout<<"制作：嘻嘻嘻";
int j=11;
tPos(12, j);
cout<<">>";
//drawFrame(45, 9, 79, 17, '=', '|');
while(1)
{if( _kbhit() )
char x=_getch();
switch (x)
case 'w' :
if( j == 13)
SetPos(12, j);
cout<<"　";
j = 11;
SetPos(12, j);
cout<<">>";
