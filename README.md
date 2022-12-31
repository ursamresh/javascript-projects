# Amresh Maurya (@ursamresh)  Javascript Projects
## javascript-projects

## 1.Calculator JS


### JS Logic
```
 function valueButton(e){
    
   calculator.screen.value +=e.value;
  
  
 }

function Clear(){
   
   calculator.screen.value=null;
}
function Calculate(){
   //eval()=evaluate expression;
  calculator.screen.value=eval(calculator.screen.value);
  
}
function Equal(){
   
   Calculate();
}
```

### HTML Code
```

<form class="calculator" name="calculator">

<div class ="screen">

<input type="text" name="screen"id="input-screen" readonly>
</div>


<div class="btn">

<input type="button"
value="clear" onClick="Clear()" name="clear"

class="clear-btn"

>
</div>

<div class="btn">

<input class="numbers" type="button"
value="1" name="num1"
onClick="valueButton(this);"
>

<input class="numbers" type="button"
value="2" name="num2"
onClick="valueButton(this);"
>

<input class="numbers" type="button"
value="3" name="num3"
onClick="valueButton(this);"
>
<input class="numbers" type="button"
value="+" name="plus"
onClick="valueButton(this);"
>
</div>



<div class="btn">

<input class="numbers" type="button"
value="4" name="num4"
onClick="valueButton(this);"
>

<input class="numbers" type="button"
value="5" name="num5"
onClick="valueButton(this);"
>

<input class="numbers" type="button"
value="6" name="num6"
onClick="valueButton(this);"
>
<input class="numbers" type="button"
value="-" name="minus"
onClick="valueButton(this);"
>
</div>

<div class="btn">

<input class="numbers" type="button"
value="7" name="num7"
onClick="valueButton(this);"
>

<input class="numbers" type="button"
value="8" name="num8"
onClick="valueButton(this);"
>

<input class="numbers" type="button"
value="9" name="num9"
onClick="valueButton(this);"
>
<input class="numbers" type="button"
value="*" name="multiply"
onClick="valueButton(this);"
>
</div>


<div class="btn" id="last-line">

<input class="numbers" type="button"
value="0" name="num10"
onClick="valueButton(this);"
>
<input class="numbers" type="button"
value="00" name="num11"
onClick="valueButton(this);"
>

<input class="numbers" type="button"
value="/" name="divide"
onClick="valueButton(this);"
>

<input class="numbers" type="button"
value="=" name="equal"
onClick="Equal();"
>

</div>


</form


```




## [LinkedIn](https://www.linkedin.com/in/ursamresh)
