<script>
    export let jobTitle = "Job title";
    export let location = "Location";
    export let duration = "month year - month year";
</script>
<div>
    <div class="flex flex-row">
        <slot name="img"></slot>
        <h1 class="self-center">{jobTitle}</h1>
    </div>
    <p class="pl-20">
        Company name
    </p>
    <p class="pl-20">
        {location}, {duration}
    </p>
</div>