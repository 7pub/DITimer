<!DOCTYPE html>
<html><head><title>Opening Multiple Popup Windows</title> <script language="javascript"> function myPopup(url,windowname,w,h,x,y){ window.open(url,windowname,"resizable=no,toolbar=no,scrollbars=no,menubar=no,status=no,directories=n o,width="+w+",height="+h+",left="+x+",top="+y+""); console.log("Opening: " + windowname); } </script> </head> <body>
 
  
  
<section align="right">

[![](https://img.shields.io/badge/github&nbsp;profile-grey?style=for-the-badge)](https://github.com/7pub/)
[![](https://img.shields.io/badge/Docker-blue?style=for-the-badge)](https://github.com/7pub/timeroll/tree/main/docker/)
[![](https://img.shields.io/badge/API-yellow?style=for-the-badge)](https://docs.rs/crate/redant/latest)
[![](https://img.shields.io/badge/Crates.io-orange?style=for-the-badge)](https://crates.io/crates/redant)
[![](https://img.shields.io/badge/Lib.rs-lightgrey?style=for-the-badge)](https://lib.rs/crates/redant)

</section>

<section align="right">

[![](https://img.shields.io/badge/Open-Webapp-lightgrey?style=for-the-badge)](https://7pub.github.io/timeroll/app/)

</section>


<p align = "right">
  <a href="https://7pub.github.io/timeroll/app/"><img src="https://img.shields.io/badge/Open-Webapp-blue"/>
</p>

<hr/>

https://img.shields.io/badge/Open-Webapp-blue

---

## Install

`git clone https://7pub.github.io/notime2explain.git`

`cd notime2explain`

`npm i gulp@4.0.0 --save-dev`

`yarn`

`npm run serve`


<img src="./docs/nt2e_install.gif" style="width:70%" />

---

## 📄 License

| DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE |

---

| MACHEN DAMIT WAS VERDAMMT NOCHMAL DU AUCH IMMER MIT DIESER ÖFFENTLICHE LIZENZ MACHEN WILST |

| | Version.02  |
|- | -|
| Copyright (C) 2019 Karl Achleitner theorem.system@protonmail.com |![Crown](https://7pub.github.io/_site/license/WTFPL/wtfpl-badge-4.png) |
  > Weitere Informationen finden Sie unter [http://unlicense.org](http://unlicense.org)

---

<!-- Inside the parenthesis the order goes URL, window name, width, height, position from left, position from top-->
<!-- Note that by giving each popup window a different name each page will open in a seperate popup window-->

<a href="javascript:myPopup('http://www.cnn.com', 'CNN','300','300','10','300')">Open popup 1</a>

<br>

<a href="javascript:myPopup('http://example.com', 'Example.com','300','300','100','300')">Open popup 2</a>

<br>

<a href="javascript:myPopup('http://www.nbc.com', 'NBC','300','300','200','500')">Open popup 3</a>

</body>

</html>
