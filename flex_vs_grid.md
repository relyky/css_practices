# CSS Grid 與 CSS Flexbox 比較
__CSS Flexbox Layout__ (之後簡稱`flex`)與 __CSS Grid Layout__ (之後簡稱`grid`) 都適合用來設計 RWD webpage。

`flex`與`grid`應該都是多人共同創作的成果，因為查不到主要作者，都是太概在2008年提出。兩者在一開始的渲染(render)都跑得很慢都是歷經約十年的調校才成熟可用。   
`flex`與`grid`的主要差異用抽象來對比的話，`gird`是二維的；而`flex`是一維的。當然透過巢狀迭代技巧 flex 也可以作出二維或更複雜的 layout。   
像 __grid layout__ 這種想法是延用數百年來的工程技巧，而 __flexbox layout__ 應該是因應手機等小螢幕的行動平台設計的，單向來回滑動的操作行為。不過桌上型電腦螢幕在解析度與尺寸都越來越大，二維的 grid layout 顯然比較適合。   

### 小結
`flex`大概在2018年底開始可用。`gird`的實作難度比較高大概在2020年底開始可用。應用上`grid`與`flex`可以混用、可以互相嵌套，建議一套為主一套為輔各自發揮所長。若是手機應用建議以 flex 為主；若是桌面應用建議 grid 為主。然而若是導入了現成的 **CSS Framework** 的話，就看事辦事吧。   

# 歷史沿革
`flex`與`grid`各有主要推廣的網站，不過應該都不是官網，在實務上就以__W3C__的官方文件為主也是大家都服氣的地方。
* [W3C - CSS Grid Layout Module Level 1 Publication History](https://www.w3.org/standards/history/css-grid-1)   
* [W3C - CSS Flexible Box Layout Module Level 1 Publication History](https://www.w3.org/standards/history/css-flexbox-1)   
* [The Story of CSS Grid, from Its Creators](https://alistapart.com/article/the-story-of-css-grid-from-its-creators/)   
* [Flexbox History](https://annairish.github.io/historicizing/history)   
* [History of CSS Grid and CSS Flexbox](https://medium.com/@BennyOgidan/history-of-css-grid-and-css-flexbox-658ae6cfe6d2)   

# 教學參考

[CSS GRID.](https://cssgrid.io/)







# Example 1
## 用 display:grid 取代 <table> 語法

