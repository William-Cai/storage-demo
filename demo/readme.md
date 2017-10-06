# localStorage & sessionStorage
## 简单使用与测试
###备注
`` 
1、同一浏览器打开了两个同源页面,其中一个页面修改了localStorage,另一个网页注册了这个事件</p>
2、同一个页面下触发不了storage事件</p>
3、在IE9里发现一个问题,相同的key,不管你value是否与之前一样,都会触发storage事件,
 而firefox中不会,只有当value与之前不同时,才会触发。``