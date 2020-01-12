---
layout: post
title:  "Making a Triangle (Algorithm)"
date:   2020-01-11 11:00:00 +0700
image:  pr4.jpg
tags:   Algorithm, Triangle, Code, Dart, Lesson
---
`Happy New Year 2020`, we hope in the following year, we always success. This is the first meet-up in the 2020. In this meet-up we review all the lessons, from the previous meet-up.

And we also do live coding using #dart language to create triangle like above. This app cover, loops, conditional, and also exception handling.

{% highlight dart %}
...
int h = 0;
for(int i=0; i < inputNumber; i++) {
  
  for(int k=0; k < inputNumber - i; k++) {
    stdout.write(' ');
  }

  h++;
  for(int j=0;j < h + i;j++){
    stdout.write('*');
  }
  
  stdout.write('\n');
}
...
{% endhighlight %}

If you want further information, just read the code, and if you'd like to join, just drop to our Instagram.

[dart-docs]: https://dart.dev/guides
[final-result]: https://github.com/horeeorg/demo/bintangsegitiga.dart