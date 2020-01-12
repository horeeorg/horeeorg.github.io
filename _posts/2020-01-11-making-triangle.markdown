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
int helper = 0;
for(int lineCount=0; lineCount < inputNumber; lineCount++) {
  
  for(int spaceCount=0; spaceCount < inputNumber - lineCount; spaceCount++) {
    stdout.write(' ');
  }

  for(int startCount=0; starCount < ++helper + lineCount; starCount++){
    stdout.write('*');
  }
  
  stdout.write('\n');
}
...
{% endhighlight %}

If you want further information, just read the code [here][final-result] and click [this][dart-docs] for dart language references, and if you'd like to join, just drop to our Instagram.

[dart-docs]: https://dart.dev/guides/language/language-tour
[final-result]: https://github.com/horeeorg/demo/blob/master/bintangsegitiga.dart