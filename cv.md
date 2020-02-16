# Anton Hotvianskyi
## Contact Info
- Telephone - 0958789090fake
- Email - gotvjanskii@gmail.com

## Personal Qualities
- Communication.
- Self-motivation.
- Conflict Resolution.
- Adaptability.
- Learn fast.
- Punctuality.
- Mindfulness.
- Decency.

## Skills
- Basic knowledge HTML/CSS.
- Basic knowledge BEM methodology.
- Basic knowledge JS.
- Tools:GIT, Gulp, Photoshop.

## Code examples 
```
<script>
      var numberOne;
      var numberTwo;
      var mathAct;
      var answer;
      $('.btn-info').click(function() {
      document.getElementById('inp').value=document.getElementById('inp').value + this.value;
        });
    
      $('#del').click(function() {
      document.getElementById('inp').value="";
        });
    
      $('.btn-success').click(function() {
      numberOne=document.getElementById('inp').value;
      mathAct=this.value;
      document.getElementById('inp').value="";
        });

      $('#sqrt').click(function() {
       var answer=Math.sqrt(parseInt(numberOne));
       document.getElementById('inp').value=answer;
      });

      $('#equ').click(function() {
      numberTwo=document.getElementById('inp').value;
      numberOne=parseInt(numberOne);
      numberTwo=parseInt(numberTwo);

      switch (mathAct) {
    case "*":
       answer=numberOne*numberTwo;
       break;
    case "/":
        answer=numberOne/numberTwo;
        break;
    case "+":
       answer=numberOne+numberTwo;
        break;
    case "-":
        answer=numberOne-numberTwo;
        break;
        }
        document.getElementById('inp').value=answer;
      });
      
    </script>
```
## Experience
- Only couple of pet projects