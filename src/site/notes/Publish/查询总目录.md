```dataviewjs
var i = [dv.pages().length,dv.pages(`"200 Songs"`).length,dv.pages(`"300 Events"`).length,
         dv.pages(`"400 Topics"`).length, dv.pages().file.etags.distinct().length]
dv.paragraph(`总共有 **${i[0]}** 个文件`)
dv.paragraph(`其中==歌曲== **${i[1]}** 首，==活动== **${i[2]}** 个，==话题== **${i[3]}** 个`)
dv.paragraph(`==标签== **${i[4]}**个`)
```