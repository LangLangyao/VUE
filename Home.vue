<template>
<div>
  <h3>我是Home组件</h3>
    <Index></Index>   
</div>
</template>
<script>
import Index from "./index"
export default {
    data : function(){
        return{
            mages:"马啸天。。。脑补"
        }
    },
    components:{
        Index
    }
}
</script>
