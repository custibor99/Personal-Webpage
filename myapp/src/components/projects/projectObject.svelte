<script>
    import { goto } from "$app/navigation";

  export let title = "Placeholder title";
  export let text = "Placeholder text";
  export let link = "https://www.google.com";

</script>

<div class="card w-66 h-50 bg-base-200 shadow-xl relative">
    <div class="card-body">
      <h2 class="card-title">{title}</h2>
      <p>{text}</p>
      <div class="card-actions justify-end" on:click={ (e) => { goto(link) }}>
        <button class="btn btn-primary">See project</button>
      </div>
    </div>
  </div>