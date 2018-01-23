---
layout: page
title: Contact
permalink: /contact/
---
<p>Email: zhuxilei511@gmail.com</p>
<p>Address:99th,Wantong Rd,Hangzhou,Zhejiang,China</p>

<p>You also could choose leave your Contact Infomation here</p>
<div id="container"></div>
<link rel="stylesheet" href="https://imsun.github.io/gitment/style/default.css">
<script src="https://imsun.github.io/gitment/dist/gitment.browser.js"></script>
<script>
    var gitment = new Gitment({
        id: '页面 ID', // 可选。这个选项不写（不是留空），默认为 location.href
        owner: 'zhuxilei',
        repo: 'Wind-Energy',
        oauth: {
            client_id: 'ca60c87940e9bd089883',
            client_secret: 'ac1fd5f2972a029871cb4632e3968533b27499e9',
        },
     });
    gitment.render('container'); //container为你要显示评论的id
</script>
