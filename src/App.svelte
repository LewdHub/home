<script>
  import { onMount } from "svelte";
  //export let date;

  onMount(async () => {
    //const res = await fetch("/api/date");
    //const newDate = await res.text();
    //date = newDate;
  });
</script>

<main>
  <div class="left-c">
    <div class="left-bar">
      <div class="gradt"></div>
      <div class="cont">
        <p class="title"><b>[ lewd ]</b></p>
        <div class="project-list">
          <p style="text-align: center">No active projects yet.</p>
        </div>
        <div class="hx-links">
          <a class="list" href="https://github.com/LewdHub" target="_blank">GitHub</a>
          <a class="list" href="/#" target="_blank">Discord</a>
        </div>
      </div>
    </div>
    <div class="left-bar def-cursor">
      <div class="gradt"></div>
      <div class="cont">
        <p class="title"><b>api status</b></p>
        <div class="api-list">
          <div class="api-b up">auth</div>
          <div class="api-b down">eu-endpoint</div>
          <div class="api-b down">us-endpoint</div>
        </div>
      </div>
    </div>
    <div class="left-bar">
      <div class="cont">
        <p class="title" style="font-size: 1rem">2021 (c) Lewd.li</p>
      </div>
    </div>
  </div>
</main>
