#HTML#


#CSS#

da linha 12 a linha 41.
- precisei ver um video para me auxiliar a fazer uma navbar do jeito que eu queria. (https://www.youtube.com/watch?v=bHRXRYTppHM)

video que usei para deixar o menu fixo na tela (https://www.youtube.com/watch?v=xPZcH78GFRM)

video que vou usar para fazer os cards dos projetos (https://www.youtube.com/watch?v=_-3nHZHkn4M)



#JAVASCRIPT QUE ACHEI LEGAL#

    <!-- JAVASCRIPT PARA EVITAR QUE USEM O BOTÃO DIREITO DO MOUSE (APENAS TESTE) -->

    <script>   
        function disableselect(e){   
        return false   
        }   

        function reEnable(){   
        return true   
        }   

        //if IE4+   
        document.onselectstart=new Function ("return false")   
        document.oncontextmenu=new Function ("return false")   
        //if NS6   
        if (window.sidebar){   
        document.onmousedown=disableselect   
        document.onclick=reEnable   
        }   
    </script>

#CSS QUE ACHEI LEGAL#

/* SERVE PARA DEIXAR O SCROLL OCULTO
::-webkit-scrollbar {
    width: 0px#9595f1;
} */