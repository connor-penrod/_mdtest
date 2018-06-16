# _mdtest

## i'm large

#### i'm small

[External link](http://www.neopets.com/)

[Internal link to other.md](../master/other.md)


Internal image:

![why did i make this](../master/cornmaze.png "completely unedited footage")

External image:

![randall munroe is my hero](https://imgs.xkcd.com/comics/git.png "accurate")


Quake's famous inverse square root function (author unknown):

```
float Q_rsqrt( float number )
{
	long i;
	float x2, y;
	const float threehalfs = 1.5F;

	x2 = number * 0.5F;
	y  = number;
	i  = * ( long * ) &y;                       // evil floating point bit level hacking
	i  = 0x5f3759df - ( i >> 1 );               // what the fuck? 
	y  = * ( float * ) &i;
	y  = y * ( threehalfs - ( x2 * y * y ) );   // 1st iteration
//	y  = y * ( threehalfs - ( x2 * y * y ) );   // 2nd iteration, this can be removed

	return y;
}
```

> a blockquote

bulleted list:
* item 1
* item 2

numbered list:
1. item 2
2. item 1

| i'm        | a           | table  |
| ------------- |:-------------:| -----:|
| row 1 col 1   | a | 1 |
| row 2 col 1   | b | 2 |
| row 3 col 1   | c | 3 |

**bold text**

*italics*

~~strikethrough text~~

---

