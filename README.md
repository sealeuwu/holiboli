<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NO ESTES TRISTE AMIGUI:D!</title>
    <style>
     .body{
        background-color: azure ;
        text-align: center;
     }   

     .body__title{
            color: red;
     }

    </style>

</head>

<body class="body">
 <h1 class="body__title"> 😸NO ESTES TRISTE AMIGUI:D!😸</h1>   
 <img src="https://media.discordapp.net/attachments/850125682440798262/1105268897638264852/e8d6b2fb-1f98-43b7-8805-87cf16230b38.png
 " alt="perrosideeye" class="body__image"/>
 <button id="yes">🤩YA🤩</button>
 <button id="no">😿ño😿</button>

 <script>
      const vutonSi = document.getElementById('yes');
    const vutonNo = document.getElementById('no');
    
    const noaladepresion = () =>{
        alert('😸YEEEIII😸');
        alert('No a la depresion amiguis');
        location.href='https://www.youtube.com/watch?v=W6c1_61zVaw&ab_channel=JóseanLog'
    }

    const noalnoamiguis= () => {
        vutonNo.style.position= 'absolute';
        vutonNo.style.top = (Math.random() * window.innerHeight) +'px';
        vutonNo.style.left = (Math.random() * window.innerHeight) +'px';
    }

    vutonSi.addEventListener('click', noaladepresion);
    vutonNo.addEventListener('mouseover', noalnoamiguis)
 
 </script>
 
  
</body>

</html>
