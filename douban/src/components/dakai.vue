<template>
    <div>
        <div class="com">
            
            <div class="btn">
                <button>极速下载</button>
                <button>打开</button>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
    .com{
        width: 100%;
        height: .8rem;
        background: url(../../static/bg.jpg);
        background-size: 100% .8rem;
        font-size: 0;
    }
  .btn{
      margin-left: 1.6rem;
  }
    button{
        height: .28rem;
        border: 1px solid #42bd56;
        padding: 0 .1rem;
        margin-right: .1rem;
        border-radius:.05rem; 
        font-size: .13rem;
        margin-top: .26rem;
    }
    button:first-child{
        background: #2ca532;
        color: white;
        margin-left: .64rem;

    }
     button:last-child{
        background: transparent;
        color: #2ca532;
    }
</style>