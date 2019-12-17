服务计算API
get 请求
curl https://test-blog.com

登录
curl --login https://test-blog.com -u username:password

登出
curl --logout https://test-blog.com

查看某篇博客
curl --article https://test-blog.com -i article_id

查看评论
curl --viewcomment https://test-blog.com -i article_id

//登录后可执行操作
查看个人信息
curl --info https://test-blog.com

新建博客
curl --create https://test-blog.com

设置博客权限
curl --authority https://test-blog.com -i article_id -v authority_level

删除博客
curl --delete https://test-blog.com -i article_id

留下博客评论
curl --comment https://test-blog.com -i article_id -c comment
