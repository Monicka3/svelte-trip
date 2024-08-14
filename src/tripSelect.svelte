<script>
   let b
   export let kutyfn

    function touch(){
        kutyfn(b)
    }

</script>
<select bind:value={b} on:change={touch} class="s">
    <option value="agra">Agra</option>
    <option value="bangalore">Bangalore</option>
    <option value="chennai">Chennai</option>
</select>

<style>
.s{
    padding:10px 10px;
    border-radius:15px;
    margin:10px auto;
    background-color: rgb(41, 31, 31);
    color:rgb(243, 175, 198);
    border-color:rgb(243, 175, 198) ;
}
</style>