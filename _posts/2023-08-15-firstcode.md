---
layout: post
title: a post of my first code 
date: 2023-08-15 15:09:00
description: my first coding in university
tags: c code
categories: sample-posts
featured: true
---

my first challenging problem in programming

````markdown
```c
code code code
```
````

```c++
#include<stdio.h>

int main(){
    double x1,y1,x2,y2,x3,y3,x,y,arae,arae1,arae2,arae3;
    
    scanf("%lf%lf",&x1,&y1);
    scanf("%lf%lf",&x2,&y2);
    scanf("%lf%lf",&x3,&y3);
    scanf("%lf%lf",&x,&y);

    arae=(x1*(y2-y3)+x2*(y3-y1)+x3*(y1-y2));
    arae1=(x*(y2-y3)+x2*(y3-y)+x3*(y-y2));
    arae2=(x1*(y-y3)+x*(y3-y1)+x3*(y1-y));
    arae3=(x1*(y2-y)+x2*(y-y1)+x*(y1-y2));

    if(arae<0){
        arae=-(arae);
        }
    if(arae1<0){
        arae1=-(arae1);
        }
    if(arae2<0){
        arae2=-(arae2);
        }
    if(arae3<0){
        arae3=-(arae3);
        }

    if(arae>=arae1+arae2+arae3){
        if(arae1==0 || arae2==0 || arae3==0){
            printf("on");
            }
        else
        {
            printf("in");
            }
    }
    else{
        printf("out");
        }
    return 0 ;


    
    
}
```

one of the website witch help me alot in programing is [Stackoverflow answer](https://stackoverflow.com/questions/34987908/embed-a-code-block-in-a-list-item-with-proper-indentation-in-kramdown/38090598#38090598). 

````markdown
...

   ...

      ```c
      printf("Hello, World!");
      ```

   ...
````



      ```c
      printf("Hello, World!");
      ```



{% raw %}
{% highlight c++ linenos %} <br/> code code code <br/> {% endhighlight %}
{% endraw %}



{% highlight c++ linenos %}






{% endhighlight %}
