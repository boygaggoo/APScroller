# APScroller

Animated letters of UILabel in circular way.

iOS 4.3+. ARC.

Video preview: http://youtu.be/qGB4Ob0uUFU

![A Screenshot](https://raw.github.com/elpsk/APScroller/master/A.png "A")
![B Screenshot](https://raw.github.com/elpsk/APScroller/master/B.png "B")

More example on www.albertopasca.it/whiletrue


## How to use

very easy:

``` objective-c
   [...]
   _Scroller = [[APScroller alloc] initWithFrame:CGRectMake(32, 100, 12 * MAXSCROLL, 50)];
   [self.view addSubview:_Scroller];


	- (void)Animate:(UIButton*)sender
	{
	  [_Scroller setWorld:@"THIS3IS6ANIMATED" animated:YES];
	}

	- (IBAction)Reset:(UIButton*)sender
	{
	  [_Scroller setWorld:@"0000000000000000" animated:NO];
	}

	- (IBAction)SetSpeed:(UISlider*)sender
	{
	  _Scroller.Speed = sender.value;
	}
```

## TODO

More customization and bug fix. Enjoy.

## Copyrigth

(c)2012 Alberto Pasca. More info -> albertopasca.it.

## License

APScroller is available under the MIT license.

Copyright (c) 2012 Alberto Pasca (albertopasca.it). All rights reserved.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

<script async src="//pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script>
<ins class="adsbygoogle" style="display:inline-block;width:728px;height:90px" data-ad-client="ca-pub-5388991997823793" data-ad-slot="6371521888"></ins>
<script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
