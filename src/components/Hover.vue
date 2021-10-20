<template >
<div>
    <h2>2.Подчеркивание текста</h2>
    <div>
        <p> Вы можете выбрать файл, вставить ссылку, перетащить изображние в любую область или нажмите PrintScreen и после ctrl+v. Это бесплатный инструмент с помощью которого вы сможет</p>
        <p> Вы можете выбрать файл, вставить ссылку, перетащить изображние в любую область или нажмит</p>

        <div class="text">
            <p>то первая глава в пошаговом руководстве про основные понятия в React. Оглавление находится в боковой панели. </p>
            <p>Если вы читаете руководство с мобильного устройства, открыть навигационное меню можно, нажав кнопку в правом нижнем углу экрана.</p>
        </div>
    </div>
    </div>
</template>
<script>
export default {
    
}
</script>
<style >

p{
    
    background-image: linear-gradient(#ffc501, #ffc501);
    background-position: 0% 100%;
    background-repeat: no-repeat;
    background-size: 0% 2px;
    transition: background-size .9s;
    
}
p:hover{
    background-size: 100% 2px;
}

.text{
    display: inline-block;
    margin-top: 10px ;
    background-image: linear-gradient(#ffc501, #ffc501);
    background-position: 0% 100%;
    background-repeat: no-repeat;
    background-size: 0% 2px;
    transition: background-size .9s;
    
}

.text:hover{
    background-size: 100% 2px;
}

</style>