[comment]: <> (Setup)
[comment]: <> (Step 1: VSC Extension: Markdown Preview Enhanced)
[comment]: <> (Step 2: View .md, right click > Markdown Preview Enhanced)

[comment]: <> (Comment goes here, no inline comments)
[comment]: <> (Note: Limitations of GitHub README.md, no raw HTML, css, line issues)
# H1
## H2
### H3
#### H4
##### H5
###### H6

**Fonts**<br>
*italic*<br>
**bold**<br>
***italic & bold***<br>
**~~Strikethru & bold~~**<br>

**Highlight** **~~(NOT SUPPORTED IN GITHUB)~~**

"Highlight <span style="background-color:yellow">Pikachu</span>"

[comment]: <> (Inline HTML, rarely used)
<dl>
  <dt>Definition list</dt>
  <dd>Is something people use sometimes.</dd>

  <dt>Markdown in HTML</dt>
  <dd>Does *not* work **very** well. Don't use HTML <em>tags</em>.</dd>
</dl>

[comment]: <> (Note: No text before list)
**List**
1. First ordered list item
2. Another item
   * Unordered sub-list
      * Unordered sub-list
3. Actual numbers don't matter, just that it's a number
  1. Ordered sub-list
4. And another item

[comment]: <> (Note: Need space after *)
**Bullet List**
* Section 1 
- Section 2
+ Section 3

**Checkbox**
- [ ] unchecked checkbox<br>
   &#9744; alt unchecked checkbox<br>
- [x] checked checkbox<br>
   &#9745; alt checkbox

**Emojis**<br>
:white_check_mark:<br>
:heavy_check_mark:<br>
:heart_eyes:

https://gist.github.com/rxaviers/7360908

[comment]: <> (Create Codeblock w/ ` not ')
**Codeblock**
```html
<html>
    <h1>Hacker was here</h1>
</html>
```

```c++
#include <iostream>
using namespace std;

int main(){
    cout << "Learn to code" << endl;

    return 0;
}
```

**Blockquotes** (Double space at end for \n)
> Blockquotes are handy in email to emulate reply text.  
> "Trung was the best dealer ever" *by anonymous user*
>> Tab Style

**Quote break (need return)**
> This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you ***can*** *put* **Markdown** into a blockquote. 

**Links**<br>
[Du's Homepage](https://trungdullc.github.io/ "Howdy")

[comment]: <> (: is alignment)

**Tables**
| Pokemon       | Element       | Cost  |
| ------------- |:-------------:| -----:|
| `Pikachu`     |      Electric |    $1 |
| Blastoise     |     Water     |   $69 |
| Charizard     | Fire          | **$1337** |

[comment]: <> (Add Images)
**Image w/o link**<br>
![alt text](/Markdown/images/aiPikachu.jfif "Pikachuuuu")

**Image w/ link**
[![Pokemon](https://cdn.pixabay.com/photo/2016/08/05/15/24/team-1572483_1280.jpg)](https://www.pokemon.com/)

**Youtube Video**

<a href="http://www.youtube.com/watch?feature=player_embedded&v=YOUTUBE_VIDEO_ID_HERE
" target="_blank"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/fc/Youtube_shorts_icon.svg/724px-Youtube_shorts_icon.svg.png" alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>

[comment]: <> (Internal Codeblock, don't mix with html tags)
Learn to `code` at [duprogramllc](https://trungdullc.github.io/)

[comment]: <> (Add Horizontal Line)

***
---
___

<!-- css not work on GitHub README.md -->
<div style="background-color:rgba(0, 0, 0); text-align:center; vertical-align: middle; padding:40px 0;">
<a href="https://trungdullc.github.io/">DONATE to Du</a>
</div><br>


<!-- HTML code also works in markdown-->
<!-- but not for GitHub README.md no raw HTML Tags <font><center> -->

&#169; 2023 Trung Du &copy;
