<script>
export default {

}
</script>
<template lang="">
    <div class="container">
       <div class="row">
            <div class="col blue"> 
                <ul class="j-between flex stampatello">
                    <li>digital comincs</li>
                    <li>dc merchandise</li>
                    <li>subscription</li>
                    <li>comic shop locator</li>
                    <li>dc power visa</li>
                </ul>
            </div>
            <div class="col backcol2 h100 flex">
                <div class="h100 pad">
                    <ul>
                        <li class="title">DC COMICS</li>
                        <li id="block">movie</li>
                        <li id="block">movie</li>
                        <li id="block">movie</li>
                        <li id="block">movie</li>
                        <li id="block">movie</li>
                        <li id="block">movie</li>
                        <li id="block">movie</li>
                        
                        <li class="title">SHOP</li>
                        <li id="block">movie</li>
                        <li id="block">movie</li>
                    </ul>
                </div>
                <div class="h100 pad">
                    <ul>
                        <li class="title">DC</li>
                        <li id="block">movie</li>
                        <li id="block">movie</li>
                        <li id="block">movie</li>
                        <li id="block">movie</li>
                        <li id="block">movie</li>
                        <li id="block">movie</li>
                        <li id="block">movie</li>
                        <li id="block">movie</li>
                        <li id="block">movie</li>
                        <li id="block">movie</li>
                        <li id="block">movie</li>

                    </ul>
                </div>
                <div class="h100 pad">
                    <ul>
                        <li class="title">SITES</li>
                        <li id="block">movie</li>
                        <li id="block">movie</li>
                        <li id="block">movie</li>
                        <li id="block">movie</li>
                        <li id="block">movie</li>
                    </ul>
                </div>
            </div>
            <div class="col gray j-between flex">
                <div>sing-up now!</div>
                <div>
                    
                        <ul>
                            <li>follows us</li>
                            <li><a href="#"><i class="fa-brands fa-facebook-f" style="color: #989ea9;"></i></a></li>
                            <li><a href="#"></a><i class="fa-brands fa-youtube"></i></li>
                            <li><a href="#"><i class="fa-brands fa-twitter"></i></a></li>
                            <li><a href="#"><i class="fa-brands fa-pinterest"></i></a></li>
                            <li><a href="#"></a><i class="fa-solid fa-location-dot"></i></li>  
                        </ul>
                    
                </div>
            </div>
       </div>
    </div>
</template>

<style lang="scss" scoped>
.container {
    width: 100%;
    height: 100%;
}

.row {

    justify-content: space-between;
}

.col {
    flex: 1;
    padding: 20px;
    color: white;
}

.blue {
    background-color: blue;
}

.backcol2 {
    background-image: url(../img/footer-bg.jpg);
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
}

.gray {
    background-color: gray;
}

.title {
    font-size: 20px;
}

ul {
    list-style-type: none;
    padding: 0;
}

a {
    text-decoration: none;
    color: inherit;
}

li {
    display: inline-block;
}

#block {
    display: block;
}

.h100 {
    height: 100%;
}

.pad {
    padding: 20px;
}
</style>




