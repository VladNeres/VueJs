<template>
    <main>
        <div class="text-top">Videos novos toda <b>Quinta</b> as <b>20h</b></div>
      <a href="http://youtube.com/wdevoficial" target="blanck">
        <img alt="inscreva-se" id="subscribe" 
        src="https://raw.githubusercontent.com/william-costa/wdev-mock-site-resources/master/assets/images/subscribe.svg">
      </a> 

        <div class="text-bottom">youtube.com/wdevoficial</div>
        
    </main>

</template>

<script>
export default{
    name: 'Home'
}
   
</script>

<style scopped>

main{
    background-color: var(--color-background-home);
    justify-content: center;
    align-items: center;
}

.text-top{
    color: var(--color-text-alight);
    font-size: 22px;
}

#subscribe{
    width: 340px;
}
.text-bottom{
    color: var(--color-text-alight);
    font-size:18px;
    margin-top:20px;
}   

@media (min-width:700px){
    #subscribe{
        width:370px;
    }
}
</style>