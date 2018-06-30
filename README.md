# the-maximum-value-of-the-array
функция поиска максимального значения в массиве целых чисел 
javascript


<p>
<script><br>
var arr = [700,30,40,10,1,8,300,102,1,400];
<br>
function arrlen(arrin){<br>
 var result = 0;<br>
    for(var i = 0; i < arrin.length; i++)<br>
        if (arrin[i] != undefined)<br>
          result++;<br>
    return result;<br>
}
<br>
function maxout(arrin,arrln)<br>
{<br>
  var max=0;<br>
  for (var i = 0; i < arrln; i++)<br>
    {<br>
      if(arr[i]>max){max=arr[i];}  <br>
    }<br>
  return max;<br>
}<br>

alert(maxout(arr,arrlen(arr)));<br>
</script>
</p>
