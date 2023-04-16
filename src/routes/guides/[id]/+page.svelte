<script>
     export let data;
     let guide = data.props.guide;
</script>

<div>
     <h2>{guide.title}</h2>
     <p>{guide.body}</p>
</div>
<ul class="mt-20">
     <li>
          <a href="/">Home</a>
          <a href="/about">About</a>
     </li>
</ul>