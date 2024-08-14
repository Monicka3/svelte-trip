<script>
  import Trip from "./trip.svelte"
  import TripSelect from "./tripSelect.svelte"

  let place='agra'
function placechgfn(a){
place=a;
}
</script>
<div class="d">
<TripSelect kutyfn={placechgfn}/>
<Trip loci={place}/>
</div>

<style>
  .d{
    display:flex;
    justify-content: center;
    flex-direction: column;
  }
</style>
