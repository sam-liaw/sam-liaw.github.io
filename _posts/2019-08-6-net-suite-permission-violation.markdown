---
layout: post
title:  "NET Suite 出現 Permission Violation 的訊息處理"
date:   2019-08-6 13:32:00 +0800
categories: jekyll update
---

在操作 `NET Suite` 的時候，出現了下列的訊息： 

{% highlight ruby %}
"Permission Violation:   
You need a higher level of the 'Transactions -> Sales Order' permission to access this page.   
Please contact your account administrator."  
{% endhighlight %}

![Alt text](/image/github.io/NETSUITE00.png)  

輸入 `page:role`    
選擇 `Page:Manage Roles`  

![Alt text](/image/github.io/NETSUITE01.png)  

選擇 `Token Based Authentication`  

![Alt text](/image/github.io/NETSUITE02.png)  
選擇 `Transactions`  
選擇 `Sales Order`  
`Level` 調到 `Full`  
並記得 `Save` 設定  