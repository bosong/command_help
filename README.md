# command_help
command help for zsh  命令行笔记

# start
 
 **1.**首先把command_help 库克隆到本地一个目录下  
 **2.**mac 自带zsh 命令行，其他系统请自行搜索如何安装zsh  
 **3.**在终端中输入 **vim ~/.zshrc** 打开zsh的配置文件  
 **4.**找到“#aliases” 这一行 配置命令行别名 配置如下别名：  
     alias zshconfig="vim  ~/.zshrc"  
     alias command_help='cd command_help文件夹的路劲'           
     alias command_help_git='vim command_help_git.txt文件的路径'  
     alias command_help_screen='vim command_help_screen.txt文件的路径'  
     alias command_help_pod='vim command_help_pod.txt文件的路径'  
 **5.****例如**:**command_help** 库我放在 **/Users/songbo/Documents/B_Work/** 目录下           

     alias command_help='cd /Users/song/Documents/B_Work/command_help'           
     alias command_help_git='vim /Users/song/Documents/B_Work/command_help/command_help_git.txt'  
     alias command_help_screen='vim /Users/song/Documents/B_Work/command_help/command_help_screen.txt'  
     alias command_help_pod='vim /Users/song/Documents/B_Work/command_help/command_help_pod.txt'  


# other
   
  配合强大的插件**“oh my zsh”** 使用zsh 命令行
  详情请查看本人简书文章:["oh my zsh 安装以及使用"](http://www.jianshu.com/p/563dc1da2199)
    

