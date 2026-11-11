# Fancy ReadMe Guide
I tend to forget how to do certain stuff on GitHub READMEs. This will be a guide on how to do fancy READMEs. Feel free to use anything from here for your own READMEs.


<!-- Headline Guide. -->
# Headlines! Oh, this is one too!
Adding headlines is as easy as adding a # (hashtag) to a piece of text.

<!-- This a markdown comment. It does not render in the README. -->
```
# A headline!
## Adding 2 makes it a bit smaller than just 1, but a bit bigger than normal text
### Adding 3 makes it still bold, but the same size as normal text. 
```




<details>
<summary>Example</summary>

# Super badass and epic project
Blah blah blah......
## Features
Blah blah blah......

### Credits
Me

</details>

<details>
<summary>Code for the example </summary>

```
# Super badass and epic project
Blah blah blah......
## Features
Blah blah blah......

### Credits

```
</details>


<!-- End of Headline Guide. -->

<!-- Text fun stuff Guide. -->
# Text fun stuff

## Quotes
You can make a block of a "normal quote" by adding > (greater-than sign) and ending it with a < (less-than sign).

**How it looks in raw:**

``` > // I still call DoomGuy "The Marine", it's cooler that way. (Jakie, Spider's Delight) < ```

**In Preview**
> // I still call DoomGuy "The Marine", it's cooler that way. (Jakie, Spider's Delight) <


## Code Quotes
You can also quote code by adding a set ``` (backtick or tilde key). Hint hint, that's how I've been showing you the raw code sections! Unfortunately, that means I can't easily show it off. But I can show you the end result. 

```
map SDEYE lookup "Blind Lover's Eye"
{
 next = "EndGameC"
 secretnext = "SDSEC3"
 sky1 = "PLSKY1", 0
 sky2 = "SKY3", 0.2
 NoInfighting
 Music = "$MUSIC_SHAWN2"
 Cluster = 73
}

```

This ignores formatting, so it's nice to use when showing how to format something with bold, strikethrough, etc.

``` ***This text is a bit too exposed to be Bold in the moment.*** ```


## Tables


Tables can be tricky. It is text that is "closed" by | (pipes). This forms a "section." Add more and you got a table. 

It goes in this order.

``` | WORD | ANOTHER WORD | EVEN MORE WORDS | ```

Note, the separator between the headers and the rest of the table is actually it's own entry. You have to make changes to it if you are editing the table. It does not do it automatically.  

You can add on any amount of sections as you need. But you need every entry to match the number of sections you made.  

**Example:**

| Sonic Character  | Favorite Food | Color  | Best Friend |
| ------------- | ------------ | ------------- | ------------- |
| Sonic  | Chilidogs | Blue | Tails | 
| Tails  | Mints | Yellow | Sonic |
| Knuckles  | Grapes | Red | Who? |
| Amy  | Ice Cream | Pink | Cream |
| Cream  | Also Ice Cream | Tan | Amy | 

**Raw Example:**
```
| Sonic Character  | Favorite Food | Color  | Best Friend |
| ------------- | - | ------------- | ------------- |
| Sonic  | Chilidogs | Blue | Tails | 
| Tails  | Mints | Yellow | Sonic |
| Knuckles  | Grapes | Red | Who? |
| Amy  | Ice Cream | Pink | Cream |
| Cream  | Also Ice Cream | Tan | Amy | 

```

You can add formatting to your text while they're in a table. With this, I will also show you all of basic text formatting you can use on your README.

**Example:**
| Style | How to use it | Example |
| ------------- | ------------- | ------------- |
| Italic | ```*``` (1 Asterisk on both sides on the text) | *Italic text!* |
| Bold | ```**``` (2 Asterisk on both sides on the text) | **Bold text!** |
| Italic and Bold | ```***``` (3 Asterisk on both sides on the text) | ***Italic and Bold text!*** |
| Strikethrough | ```~~``` (2 tildes on both sides on the text) | ~~Strkethrough!~~|
| Subscript | ```<sub> TEXT </sub>``` | <sub> Subscript! </sub> |
| Superscript | ```<sup> TEXT </sup>``` | <sup> SUEPRscript! </sup> |
| Underline | ```<ins> TEXT </ins>``` | <ins> Underline! </ins> |

**Raw Example:**
```
| Style | How to use it | Example |
| ------------- | ------------- | ------------- |
| Italic | ```*``` (1 Asterisk on both sides on the text) | *Italic text!* |
| Bold | ```**``` (2 Asterisk on both sides on the text) | **Bold text!** |
| Italic and Bold | ```***``` (3 Asterisk on both sides on the text) | ***Italic and Bold text!*** |
| Strikethrough | ```~~``` (2 tildes on both sides on the text) | ~~Strkethrough!~~|
| Subscript | ```<sub> TEXT </sub>``` | <sub> Subscript! </sub> |
| Superscript | ```<sup> TEXT </sup>``` | <sup> SUEPRscript! </sup> |
| Underline | ```<ins> TEXT </ins>``` | <ins> Underline! </ins> |
```

## List and Check lists
These are easy. Just add a - (minus) to the beginning of your text to make a list.

**Example:**
- Windows
- Mac
- Linux

**Raw Example**
```
- Windows
- Mac
- Linux
```

To do a number list...just add a number next to your text.

1. Pathways Into Darkness
2. Marathon
3. Myth
4. Halo

For a check list, you need type a - (minus), then trap a poor ```x``` around 2 ```[ ]``` square brackets. For entries that are not fulfilled, you place a space. 

**Example:**

- [x] Keyboard 
- [x] Mouse 
- [ ] Controller

**Raw Example:**

```
- [x] Keyboard 
- [x] Mouse 
- [ ] Controller
```
## Links
Links are also tricky. First, wrap your text around with ```[]``` (square brackets), then with ```()``` (parentheses), wrap the link you want on your text.

**Example:**

[Jakie's Github](https://github.com/SnakieJakie)


**Raw Example:**

```

[Jakie's Github](https://github.com/SnakieJakie)

```

Like formatting, you can have text links in tables.

**Example:**
| Linux Distro  | Download Links |
| ------------- | - 
| Mint  | [Download(github.com/linuxmint)](https://github.com/linuxmint) |
| Ubuntu  | [Download(ubuntu.com/)](https://ubuntu.com/) |
| Kubuntu  | [Download(kubuntu.org/)](https://kubuntu.org/) |

**Raw Example:**

```
| Linux Distro  | Download Links |
| ------------- | - 
| Mint  | [Download(github.com/linuxmint)](https://github.com/linuxmint) |
| Ubuntu  | [Download(ubuntu.com/)](https://ubuntu.com/) |
| Kubuntu  | [Download(kubuntu.org/)](https://kubuntu.org/) |

```

# Images
Images are probably the most wanted to have in a README. Luckily, they are simple to put in. In fact, they are the same as links.

The first section will be the text when you hover the image. Place a ! before you text and then wrap it around with ```[]``` (square brackets) , then with ```()``` (parentheses), wrap the link to your image. Note, you need to have the image open separately from a page. If you just link to the page where you image, it will become a text link. You must link to the image itself.

**Example:**
![Steamboat Willie](https://thumb.wikimedia.org/wikipedia/commons/thumb/5/50/Steamboat_Willie_1928_Poster.png/960px-Steamboat_Willie_1928_Poster.png?utm_source=en.wikipedia.org&utm_campaign=imageinfo&utm_content=thumbnail)

** Raw Example**

```
![Steamboat Willie](https://thumb.wikimedia.org/wikipedia/commons/thumb/5/50/Steamboat_Willie_1928_Poster.png/960px-Steamboat_Willie_1928_Poster.png?utm_source=en.wikipedia.org&utm_campaign=imageinfo&utm_content=thumbnail)
```

Before you ask, GIFs do work on READMEs too. 

**Example:**
![Steamboat Willie](https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExdDNpanU4Y2lzbzA0eGE1ajdoaHVpY3c3a2NucjEzdGJqYTl5bzh0YiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/l2JhL0Gpfbvs4Y07K/giphy.gif)

** Raw Example**
```
![Steamboat Willie](https://media1.tenor.com/m/53qNI-bTs0oAAAAd/mickey-mouse-steamboat-willie.gif)
```
