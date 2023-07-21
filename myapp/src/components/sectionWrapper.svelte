<script>
    export let sectionTitle="SectionTitle";
</script>
<div class="flex justify-center pt-32">
    <div class="flex flex-col w-2/3">
        <h1 class="p-2 text-5xl pb-7l border-b-4 border-indigo-500 w-1/3">{sectionTitle}</h1>
        <slot/>
    </div>
</div>