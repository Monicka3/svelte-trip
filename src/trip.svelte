<script>
    export let loci
    let tripLocations={
        agra:"https://i.pinimg.com/564x/ac/94/35/ac9435b1dae07a86462fa6fa691498c4.jpg",
        bangalore:"https://i.pinimg.com/564x/3f/02/e6/3f02e624f101b2be8d85cc6e3d39227b.jpg",
        chennai:"https://i.pinimg.com/564x/73/2d/af/732daf87b5d026550ca355c3facd3f09.jpg"
    }
</script>
<div>
<img src={tripLocations[loci]} class="i"/>
</div>

<style>
.i{
    width:256px;
}
div{
    display: flex;
    justify-content: center;
}
</style>