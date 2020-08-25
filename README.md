# LearnRegex

/คำที่ต้องการค้นหาในtext/

/ ... /g = หาที่ matchทั้งหมดใน string  


/ ... /i = พิมพ์เล็กพิมพ์ใหญ่เอาทั้งหมด


/ [aeiou] / = match กับ text aeiou


/ b[aui]g / = match กับ Ex.  bag,bug,big 


หรือจะใช้แบบนี้ก็ได้


/ [a-z] / = เอา a-z


หรือแบบนี้


/[a-z0-9]/ig; = a-z 0-9 พิมพ์เล็กพิมพ์ใหญ่


^ คือตัวที่ถูกระบุไว้จะไม่ match


/[^0-9 .]/gi; = 
```ruby
  let quoteSample = "3 blind mice.";
  let myRegex = /[^0-9 .]/gi; // Change this line
  let result = quoteSample.match(myRegex); // Change this line
  console.log(result)
  [ 'b', 'l', 'i', 'n', 'd', 'm', 'i', 'c', 'e' ]

```



