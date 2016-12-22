#第一次用retext 报错,解决方法
 
##错误信息：  
打开编辑器，无法即时预览，提示  
Could not parse file contents, check if you have the necessary module installed！  

##解决方法：

sudo apt-get install python3-docutils python3-markdown  
关掉retext，重新打开，就可以即时预览了