Readme for the pure javascript blog system
===============

* * *

This is blog system write in pure javascript and run at any static site space.
I strongly recommend you deploy it on github using github pages.

With this system,you can simply write blog using markdown code.
So forget the layout,or evil WYSIWYG html editor.

Get markdown syntax from [ here ](http://daringfireball.net/projects/markdown/basics/)

how to use it
------------------

When you put yout blog file in blogs directory,such as myblog.txt
you can access your blog with url: http://yourdomain/index.html?p=myblog.txt

But at this time,you can't see the blog display on your index page.

You must edit the list.json file manually.

The json like next:

    {data:[
        {
            "name":"myblog.txt",
            "title":"Readme for the pure javascript blog system",
            "disp":"This is blog system write in pure javascript and run at any static site space.",
            "date":"2012/3/14 23:11:25"
        },
    ]}

Save the list.json file,and the blog will display on index page.

how to deploy the blog on github pages?
-----------------------

1. reigst an account.
2. create a repository named of youraccountname.github.com
3. follow the steps on the page github show you when you create your account.
4. put all files in local directory.add,commit,pull it.

after all at last.You can access your blog in youraccount.github.com

Enjoy it!

