# pythonstudy
the process of studying python
#1 spider study
 it will record my spider studying.
  
 simplespider_1 using Python3.5 ,and spider the movie data of douban,then using xltw3 so that save the data to excel. when install
 xltw3 packets, it will occur the errors:ValueError: '__init__' in __slots__ conflicts with class variable ,you just modify as follows:
open Python33\Lib\site-packages\xlwt3\formula.py file ，and find the line

__slots__ = ["__init__",  "__s", "__parser", "__sheet_refs", "__xcall_refs"]

modify to 

__slots__ = [ "__s", "__parser", "__sheet_refs", "__xcall_refs"]

 simplespider_2 using Python3.5 ,and spider the movie data of douban choosing 10 different types' movie,then save the data to  redis ,and the key is movie_title,and the value is  ranking number.

simplespider_3 example using Python3.5, BeautifulSoup and lxml  so that get the https://knewone.com/ data.

simplespider_4 and simplespider_5  examples using Python3.5, BeautifulSoup and lxml so that get the 58 tongcheng data ,and save the data to MongoDB，simplespider_5 spider the zhuanzhuan data.



