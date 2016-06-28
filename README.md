# delete-the-min_num-letter
delete the least letter in a string

#本函数的功能：删除字符串中出现最少的字符；
关键代码如下：（注意i--的作用，删除多个字符时候，每次删除之后，字符缩进，下标减一）
for (k=0;k<255;k++)
	{
		if(a[k]==temp)
		{
           	for (i=0;i<n;i++)
			{
	        	if(p[i]==k)
				{
                     for (j=i;j<n;j++) p[j]=p[j+1];
					 i--;
				}
			}
		}
	}
	return p;
