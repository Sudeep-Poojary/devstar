<script>
    import image from "$lib/assets/StackEdit.jpg"
    import Pencil from "~icons/mdi/lead-pencil"
    
</script>

<div>
    <nav class="flex bg-neutral-800 px-2 py-0">
        <div class="container mx-auto flex items-center justify-center">
            <div class="flex items-center justify-between py-2">
                <ul class="flex items-center justify-center">
                    <li class="text-center">
                        <a class="text-2xl flex text-neutral-400" href="/editor"><Pencil class="flex pr-1"/>START WRITING</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
</div>





<div class="flex flex-row justify-center items-center h-screen">

<div class="font-sans flex justify-center items-center h-screen">
    <img src={image} alt="StackEdit">
</div>

<div class="pl-5 font-sans flex flex-col justify-center items-center h-screen text-gray-500">
      <h1 class="text-9xl font-semibold">StackEdit</h1> 
      <p class="font-semibold">In-browser Markdown Editor</p>

</div>

</div>

<style lang="postcss">
    :global(html) {
        background-color: theme(colors.gray.100);
    }
</style>

