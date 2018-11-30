# My (not so awesome) CV using [awesomeCV](https://github.com/posquit0/Awesome-CV) template

Even though this looks like awesomeCV, the template was not cooperating so I decided to 
start from scratch. The colors are also different, these are more pastel. My implementation 
uses `minipages` to create the two-column layout and the header is bigger. The main difference 
is the way education is presented and the website's icons. Some changes were also based on 
[Anjana Vakil's](https://github.com/vakila) [CV](https://vakila.github.io/pdf/Vakil-Resume.pdf). 

There is still a `print` option, which generates a black and white document. There are 
two options:

* `printWhiteHeader`: generates a white header with gray font. 
* `printGrayHeader`: generates a gray header with white font, similar to the original version. 

There are two more options, `blue` and `pink` but they don't look so good, I'd refrain from 
using them. To choose **one** from these options, change the value from `0` to `1`. 

    \def\printWhiteHeader{0}
    \def\printGrayHeader{0}
    \def\pink{0}
    \def\blue{0}

PS: I know you're not supposed to upload `.pdf` files but I'm lazy, sometimes I just want 
to check something on my CV and I really don't want to download and compile it again. 

:blue_heart::blue_heart::blue_heart:
