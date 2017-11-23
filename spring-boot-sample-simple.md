#### spring-boot-sample-simple

##### 1.Banner
在/src/main/resources/目录下的banner.jpg和banner.txt

banner.jpg:
```

                                            .&.*.                             
                                       *::o::oooooo                           
                                      *o&o:o:o::oooooooooo                    
                                    :oo&88ooo&:oo&&&&&&&&ooooooo              
                                     o*:o:o::8oo&&&o&&&&&&o&&o&&o             
                                     *:o:::o:&&8ooooo&&&&&&&&&&&&o            
                                     ::&:o:oo:**:::oooooo&ooo:o8@             
                                    *&*oo::o:&:::::::oooooooo&oo#             
                                    .*::::::&8888888oo:ooo8ooooo&             
                                    *:ooo*:*&:o::::ooooooooooo&&o             
                                   .*:::::o@8oo::oooooooooooooooo             
                                    o#::8:oo:oo:ooooooooooooooooo:            
                                  *8o:&oo*&ooooooooooooooooooo:oo&            
                                :&o:&&o:oo:8&&ooo&ooooooooooooooo8:           
                              *::o#o8:&&&&oo&&&&ooo&&oooooooooooo&o:          
                             *:oo8*o::o&ooooooooooooooooooooooooo&oo:         
                           *o*#oo:&ooo::ooo:oo::ooooooooooooooooo&:o:         
                         :&*o*:8.:8::::::::::oooooooooooo:oo:::oooooo:        
                   *o o&:* 8o::::.&:::::::::ooooo::ooooo:oooo&ooooooo:        
         .**.******:. 8o::o:::::::::::::oooo:::::&&&oooooo&o:ooooooooo        
      .******:*:::::.*::::::ooooooooo:ooo:oooo:::::oooo&oooooooooooooo        
     .*****:::*o::::o:::ooooo&o:o:::::::oooo:ooooooooooooooooooo:::oo:*       
    ..**::::::::::::::::::::::oo:o:o:::::::::::::o::o&ooooo::oooooooo:        
    .*.***:*:::::::::::::::::::oo::::::ooooooo:::::::::::ooooo::ooooo:.       
    .***:::*:*:::::::::::::**:::oo:oooooooo::o:::::::::::::ooo:o:oooo:*       
    .****::::::::::::::::::::ooooooooooooo&8*o:::::*::::o:oo:o:oooooo::       
      **:::::o::::::::::o::::::ooo&ooo&oo:::::::::::::::::::::::oo&o**.       
          .*:oo::::8::::@::::@o:o88&::*....  . *:::##:::#::::8&&o*.           
                                                                             
```
注：JPG的图片在控制台(Console)中打印出来竟然是用符号拼接的！很好玩。

banner.txt
原文内容：
```
${Ansi.GREEN} :: Sample application build with Spring Boot${spring-boot.formatted-version} ::${Ansi.DEFAULT}
```
打印效果:
```
 :: Sample application build with Spring Boot (v1.5.8.RELEASE) ::
```


