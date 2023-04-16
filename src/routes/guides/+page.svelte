<script>
     export let data;
     let guides = data.props.guides;
</script>

<div>
     <ul>
          {#each guides as guide}
               <li class="my-4">
                    <a href={`/guides/${guide.id}`}>{guide.title}</a>
               </li>
          {/each}
     </ul>
</div>
<ul class="mt-20">
     <li>
          <a href="/">Home</a>
          <a href="/about">About</a>
     </li>
</ul>