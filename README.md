# the-maximum-value-of-the-array
функция поиска максимального значения в массиве целых чисел 
javascript


<p>
<script><br>
var arr = [700,30,40,10,1,8,300,102,1,400];
<br>
function arrlen(arrin){
 
 var result = 0;
    for(var i = 0; i < arrin.length; i++)
        if (arrin[i] != undefined)
          result++;
    return result;
}
//
function maxout(arrin,arrln)
{
  var max=0;
  for (var i = 0; i < arrln; i++)
    {
      if(arr[i]>max){max=arr[i];}  
    }
  return max;
}

alert(maxout(arr,arrlen(arr)));
</script>
</p>
