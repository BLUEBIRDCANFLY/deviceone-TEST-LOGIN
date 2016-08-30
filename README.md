# deviceone-TEST-LOGIN
还是不了解GITHUB对项目的管理机制，只好再建了一个
这次对商品页面没有进行修改，主要是新增加了一个LOGING和regedit的页面，但是REGEDIT限于服务端还没准备好，就只是做了简单的编写
但是对于LOGIN来说，相对完善一些
进入登录页面，首先进行do_Page.on("refreshuser", function(){中的内容，加载本地的DO_CACHE_STATE中已有内容，这个CACHE如果存在已登录信
息，就先读出来，为了简便，我在登录的时候把用户登录信息存在CACHE的123当中。在这里同样取这个地址中的内容。如果没有内容，就意味着没有登录信息
