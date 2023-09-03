<script>
    export let score =25;
    export let name ="red";
     //test
    function increase(){
        score++;
    }
    function decrease(){
        score--;
    }
</script>

<div style="border:dashed red 5px" class="col">

    <h2 class="text-danger">Team {name}: {score}</h2>
    <button on:click={increase} class="btn btn-success">+</button>
    <button on:click={decrease} class="btn btn-danger">-</button>

</div>


<style>

    div.col{

     padding: 20px;
     margin: 15px;
     text-align: center;
    }
</style>
