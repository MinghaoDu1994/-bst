# tianwenxuebao-bst
为了更好的引用！


鉴于天文学报的引用方式比较麻烦，只能手动输入，因此利用makebst产生了对用的bst文件

但是生成的bst文件有一个问题，就是不能讲期刊名缩写，因此.bib文件需要用对用的python脚本进行修改，使用方式为在终端输入：

python abbreviate_journal_names_bib.py yourbib outputbib

此脚本来自于https://gist.github.com/peci1/4e67f3d0521ce014fc952bcca664b37d，thank you very much

journalList文件中添加了一些对应的期刊全称及缩写名，可以根据需要自由添加http://adsabs.harvard.edu/abs_doc/journals.html

祝好
