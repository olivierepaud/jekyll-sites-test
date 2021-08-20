---
layout: post
title:  "test of Markdown language"
date:   2021-07-30 10:47:00 -0400
categories: jekyll update
---




--TITLES--
---------------

H1 title sample, the line below is a line of dash ---
---------------

H2 title sample, the line below this title is a line of equal ===
===============

# header 1 (one hash \#)
## header 2 (two hashes \#\#)
### header 3 (three hashes \#\#\#)
#### header 4 (four hashes \#\#\#\#)
##### header 5 (five hashes \#\#\#\#\#)
###### header 6 (six hashes \#\#\#\#\#\#)




--OTHER--
---------------


--emphasis--
===============

_text wrapped by single underscores is in Italic_: \_like this\_

*(also: text wrapped by single asterisks is in Italic too*: \*like this\*)

**text wrapped by double asterisks is in Bold**: \*\*like this\*\*

__(also: text wrapped by double underscores is in Bold too__: \_\_like this\_\_)

`text between brackets appears as code formatting:` \`like this\`

If I write a sentence with no space at the end, and whith no blank line, then the carriage return of the text file is not taken into account:  
There is a carriage return after the colon here in the text file **(colon)**:
but there isn't any on the web page.

If I write a sentence with **two spaces** at the end of the line, and whith no blank line, then it is interpreted as a new line in the web page:  
There are two spaces at the end of this line after the coma **(coma)**,  
and it is interpreted as a new line on the web page.

If I add a blank line between two lines, then it is interpreted as a new paragraph:  
There is a blank line after this line in the text file:  

and it is interpreted as a new paragraph on the web page.


--lists--
===============

simple bullets list with asterisks:
* one 
* two 
* three

nested:
* one 
  * one-one
  * one-two
  * one-three
* two 
* three
  * three-one
  * three-two
    * three-two-one
    * three-two-two
  * three-three




--code blocks--
===============

Markdown also support predefined code blocks formatting.

code block for Ruby sample:
{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Also, preformatted code block is simply done with tab or 4 spaces at the beginning of the line:

    $ sudo apt-get install ruby-full build-essential zlib1g-dev
    $ gem install bundler jekyll
    $ jekyll new my-awesome-site
    $ cd my-awesome-site/
    $ bundle exec jekyll serve





--links--
===============

A [first example](http://localhost:4000/jekyll/update/2021/07/29/welcome-to-jekyll.html "My welcome page").
Using a direct reference to the URL.  
It might be convenient but the text file doesn't look very nice.

A [second example][link1]. Using _link1_ reference to the URL. Then, anywhere else in the doc, define `link1`, which is absolute here.
(it is just below this comment in the text file but invisible on the web page).

  [link1]: http://localhost:4000/jekyll/update/2021/07/29/welcome-to-jekyll.html "My welcome page"

A [third example][]. the name of the link displayed on the web page is also the name of the link reference.

  [third example]: http://localhost:4000/ "root page"


We can also used relative links:  
Here is a [relative link][] to my Welcome page.  

  [relative link]: /jekyll/update/2021/07/29/welcome-to-jekyll.html "relative link to my Welcome page"



links sample:  
Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll.  
File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh].  
If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].  

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/


links sample:  
Check out the [Jekyll docs][] for more info on how to get the most out of Jekyll.  
File all bugs/feature requests at [Jekyll’s GitHub repo][].  
If you have questions, you can ask them on [Jekyll Talk][].  

[Jekyll docs]: https://jekyllrb.com/docs/home
[Jekyll’s GitHub repo]:   https://github.com/jekyll/jekyll
[Jekyll Talk]: https://talk.jekyllrb.com/

