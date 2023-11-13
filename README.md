# swift-api-structure
Building **baseUrl** per environments and more useful information in a structured single file with many usages.

![image](https://github.com/manuelsalinas-mx/swift-api-structure/assets/110424672/b3f048cc-431b-4828-bc1d-7a968939de65)

### Sample Output
```
* * * * * * *  Environment info * * * * * * 
baseURL: http://test.subdomain.domain.com/api/v2
Domain: domain.com
Host: test.subdomain.domain.com
Subdomain: test.subdomain
Url Protocol: http
Route: /api/v2

* * * * * * *  Main Path methods * * * * * * 
Login path: http://test.subdomain.domain.com/api/v2/login
Sign up path: http://test.subdomain.domain.com/api/v2/signUp
Forgot password path: http://test.subdomain.domain.com/api/v2/forgotPassword
Logout path: http://test.subdomain.domain.com/api/v2/logout

* * * * * * *  User methods * * * * * * 
Get User path: http://test.subdomain.domain.com/api/v2/profile
Delete user path: http://test.subdomain.domain.com/api/v2/profile/777
Get tasks path: http://test.subdomain.domain.com/api/v2/tasks
Get task detail path: http://test.subdomain.domain.com/api/v2/profile/333/task/20

* * * * * * *  Feed methods * * * * * * 
Get item path: http://test.subdomain.domain.com/api/v2/feed
Delete item path: http://test.subdomain.domain.com/api/v2/feed/delete/item/666
Item detail path: http://test.subdomain.domain.com/api/v2/feed/detail/item/666
Update item path: http://test.subdomain.domain.com/api/v2/feed/update/item/666
```
