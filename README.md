# Amresh Maurya (@ursamresh)  Javascript Projects
## javascript-projects

### 1.Calculator JS

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
