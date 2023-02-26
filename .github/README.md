<h1 align="center">
  <img src="https://i.ibb.co/5KcFHJZ/social-to-rss-banner.png" alt="Social to RSS" />
</h1>


<h3>About</h3>
My personal blog site pulls data from various sources (Dev.to, Twitter, LinkedI, etc) in RSS format.<br>
But many of these services have strict rate limits, CORS and sometimes slow or tempromental responses.<br>
To avoid this, I'm using GitHub Actions to download and cache the feeds in this repo nightly.<br>
My site then fetches the RSS from here via GitHub CDN, rather than from the original social network.<br>
Using Git for this, also means that all my blog posts are backed-up, and a changelog is kept.<br>

---

<h3 align="center">Included Feeds</h3>

<p align="center">
<i>(link to profile source) → (link to generated feed)</i>
<br><br>
<kbd><a href="https://notes.aliciasykes.com" title="Personal Blog - notes.aliciasykes.com"><img src="https://img.shields.io/badge/-Notes-262654?style=flat&amp;logo=micro.blog&amp;logoColor=white" alt="Notes - notes.aliciasykes.com"></a> ➡️ <a href="https://raw.githubusercontent.com/Lissy93/feeds/main/blog.atom"><img src="https://img.shields.io/badge/-RSS-FFF?style=flat&amp;logo=rss&amp;logoColor=FFA500" alt="RSS Feed"></a></kbd>
<br><br>
<kbd><a href="https://www.reddit.com/user/lissy93" title="Reddit - u/lissy93"><img src="https://img.shields.io/badge/-Lissy93-ff4500?style=flat&amp;logo=reddit&amp;logoColor=white" alt="Reddit - u/lissy93"></a> ➡️ <a href="https://raw.githubusercontent.com/Lissy93/feeds/main/reddit.atom"><img src="https://img.shields.io/badge/-RSS-FFF?style=flat&amp;logo=rss&amp;logoColor=FFA500" alt="RSS Feed"></a></kbd>
<br><br>
<kbd><a href="https://mastodon.social/@lissy93" title="Mastodon - Lissy93"><img src="https://img.shields.io/badge/-Alicia_Sykes-6364FF?style=flat&amp;logo=mastodon&amp;logoColor=white" alt="Mastodon - Lissy93"></a> ➡️ <a href="https://raw.githubusercontent.com/Lissy93/feeds/main/mastodon.atom"><img src="https://img.shields.io/badge/-RSS-FFF?style=flat&amp;logo=rss&amp;logoColor=FFA500" alt="RSS Feed"></a></kbd>
<br><br>
<kbd><a href="https://stackoverflow.com/users/979052/alicia" title="StackOverflow - Alicia Sykes"><img src="https://img.shields.io/badge/-Alicia-f48225?style=flat&amp;logo=Stackoverflow&amp;logoColor=white" alt="StackOverflow - Alicia Sykes"></a> ➡️ <a href="https://raw.githubusercontent.com/Lissy93/feeds/main/stackoverflow.atom"><img src="https://img.shields.io/badge/-RSS-FFF?style=flat&amp;logo=rss&amp;logoColor=FFA500" alt="RSS Feed"></a></kbd>
<br><br>
<kbd><a href="https://github.com/Lissy93" title="GitHub - @Lissy93"><img src="https://img.shields.io/badge/-Lissy93-3a3a3a?style=flat&amp;logo=GitHub&amp;logoColor=white" alt="GitHub - @Lissy93"></a> ➡️ <a href="https://raw.githubusercontent.com/Lissy93/feeds/main/github.atom"><img src="https://img.shields.io/badge/-RSS-FFF?style=flat&amp;logo=rss&amp;logoColor=FFA500" alt="RSS Feed"></a></kbd>
<br><br>
<kbd><a href="https://youtube.com/@AliciaSykes" title="YouTube - Alicia Sykes"><img src="https://img.shields.io/badge/-Alicia_Sykes-FF0000?style=flat&amp;logo=youtube&amp;logoColor=white" alt="YouTube - Alicia Sykes"></a> ➡️ <a href="https://raw.githubusercontent.com/Lissy93/feeds/main/youtube.atom"><img src="https://img.shields.io/badge/-RSS-FFF?style=flat&amp;logo=rss&amp;logoColor=FFA500" alt="RSS Feed"></a></kbd>
<br><br>
<kbd><a href="https://dev.to/lissy93" title="Dev.to - @Lissy93"><img src="https://img.shields.io/badge/-Lissy93-a75fff?style=flat&amp;logo=Dev.to&amp;logoColor=white" alt="Dev.to - @Lissy93"></a> ➡️ <a href="https://raw.githubusercontent.com/Lissy93/feeds/main/dev-to.atom"><img src="https://img.shields.io/badge/-RSS-FFF?style=flat&amp;logo=rss&amp;logoColor=FFA500" alt="RSS Feed"></a></kbd>
<br><br>
<kbd><a href="https://lissy93.blogspot.com/" title="Blogger - Lissy93"><img src="https://img.shields.io/badge/-Lissy93-FF5722?style=flat&amp;logo=blogger&amp;logoColor=white" alt="Blogger - Lissy93"></a> ➡️ <a href="https://raw.githubusercontent.com/Lissy93/feeds/main/blogger.atom"><img src="https://img.shields.io/badge/-RSS-FFF?style=flat&amp;logo=rss&amp;logoColor=FFA500" alt="RSS Feed"></a></kbd>
<br><br>
<kbd><a href="https://twitter.com/Lissy_Sykes" title="Twitter - @Lissy_Sykes"><img src="https://img.shields.io/badge/-@Lissy_Sykes-00acee?style=flat&amp;logo=Twitter&amp;logoColor=white" alt="Twitter - @Lissy_Sykes"></a> ➡️ <a href="https://raw.githubusercontent.com/Lissy93/feeds/main/twitter.atom"><img src="https://img.shields.io/badge/-RSS-FFF?style=flat&amp;logo=rss&amp;logoColor=FFA500" alt="RSS Feed"></a></kbd>
<br><br>
<kbd><a href="https://www.linkedin.com/in/aliciasykes" title="LinkedIn - Alicia Sykes"><img src="https://img.shields.io/badge/-Alicia_Sykes-0072b1?style=flat&amp;logo=Linkedin&amp;logoColor=white" alt="LinkedIn - Alicia Sykes"></a> ➡️ <a href="https://raw.githubusercontent.com/Lissy93/feeds/main/linkedin.atom"><img src="https://img.shields.io/badge/-RSS-FFF?style=flat&amp;logo=rss&amp;logoColor=FFA500" alt="RSS Feed"></a></kbd>
<br><br>
<sub><a href="https://github.com/Lissy93/feeds/blob/main/RECENT.md"><b>View Summary</b></a></sub>
</p>

---

<!-- License + Copyright -->
<p  align="center">
  <i>© <a href="https://aliciasykes.com">Alicia Sykes</a> 2023</i><br>
  <i>Licensed under <a href="https://gist.github.com/Lissy93/143d2ee01ccc5c052a17">MIT</a></i><br>
  <a href="https://github.com/lissy93"><img src="https://i.ibb.co/4KtpYxb/octocat-clean-mini.png" /></a><br>
  <sup>Thanks for visiting :)</sup>
</p>

<!-- Dinosaur -->
<!-- 
                        . - ~ ~ ~ - .
      ..     _      .-~               ~-.
     //|     \ `..~                      `.
    || |      }  }              /       \  \
(\   \\ \~^..'                 |         }  \
 \`.-~  o      /       }       |        /    \
 (__          |       /        |       /      `.
  `- - ~ ~ -._|      /_ - ~ ~ ^|      /- _      `.
              |     /          |     /     ~-.     ~- _
              |_____|          |_____|         ~ - . _ _~_-_
-->


