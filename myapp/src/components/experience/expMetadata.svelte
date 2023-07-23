<script>
    export let jobTitle = "Job title";
    export let location = "Location";
    export let duration = "month year - month year";
    export let companyName = "company name";
</script>
<div class="flex gap-5">
    <div >
        <slot name="img" class="resize-none"></slot>
    </div>
    <div class="pl-4 w-3/4">
        <h1 class="font-bold text-xl text-gray-900">{jobTitle}</h1>
        <p class="font-semibold text-lg text-gray-700">
            {companyName}
        </p>
        <div class="flex flex-row lg:flex-col  w-full">
            <p class="text-base text-gray-800">
                {location}
            </p>
            <p class="text-base text-gray-800 ml-auto lg:ml-0">
                {duration}
            </p>
        </div>

    </div>

</div>