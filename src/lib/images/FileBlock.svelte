<script>
    export let title = "";
    export let source = "";

</script>


<div class="file-block-container">
    <div class="sub-file-block-left">
        <div>{title}</div>
        <div>下載</div>
    </div>
    <div class="sub-file-block-right">
        預覽
    </div>
</div>

<style>
.file-block-container{
    display: flex;
    height: 60px;
    margin-bottom: 8px;
}
.sub-file-block-left{
    display: flex;
    flex: 1;
    background-color: #fff;
    display: flex;
    align-items: center;
    padding: 0px 8px;
    justify-content: space-between;
}
.sub-file-block-right{
    flex: 0 0 200px;
    background-color: #55f;
    color: #fff;
    display: flex;
    align-items: center;
    justify-content: center;
}
</style>
