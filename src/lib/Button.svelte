<script>
    export let text = '';
</script>

<button class="btn">{text}</button>

<style>
    .btn{
        background-color: black;
        color: white;
        border: 2px solid white;
        padding: 20px 50px;
        font-size: 18px;
        cursor: pointer;
        margin: 10px;
        border-radius: 25px;
        text-transform: uppercase;
    }
    .btn:hover{
        background-color: green;
        color: black;
    }
</style>