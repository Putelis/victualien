<script>
    import Sidebar from "./Sidebar.svelte";
</script>

<div id='box' class="flex text-center m-2 rounded-lg">
    <Sidebar/>
    <div id='center-screen' class="grow h-14">
      <h1>To edit me go to src/components/xxx.svelte</h1>
      <h1>For the parent window edit Main.svelte</h1>
      <h1>Main.svelte is the only file you will generally need to edit for grid and inner layouts</h1>
      <h1>It is also the file where you can see other imported files from the same directory</h1>
      <h1>Edit /src/routes/+layout.svelte to adjust general screen/viewport properties</h1>
    </div>
    <div class="flex-none w-56 bg-white rounded-r-lg">
    03
    </div>
</div>

<style>
 #box{
    height:95vh;
    background-color: #fbfbfd;
 }
</style>