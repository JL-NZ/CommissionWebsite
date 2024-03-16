<script lang="ts">
  import "../css/main.css";
  import "../css/fonts.css";
  import selectedTab from '$lib/selectedTab.js';    
  import EmailIcon from "$lib/emailIcon.svelte";
</script>

<main class="flex flex-col items-center justify-items-start p-4 mx-0 bg-black h-screen">
    <div class="flex tabs justify-center">
      <a class="flex m-0 justify-center [&_h2]:hover:underline" href="/">
        <button class="flex tab bg-red-500 justify-center mx-3" aria-checked={$selectedTab == "Home"}>
          <h2 class="roboto-regular mt-2">Home</h2>
        </button>
      </a>
      <a class="flex m-0 justify-center [&_h2]:hover:underline" href="/development">
        <button class="flex tab bg-blue-500 justify-center mx-3" aria-checked={$selectedTab == "Development"}>
          <h2 class="roboto-regular mt-2 ">Development</h2>
        </button>
      </a>      
      <div class="flex disabled-tab bg-green-500 justify-center mx-3"/>
      <div class="flex disabled-tab bg-orange-500 justify-center mx-3"/>
    </div>
    <slot></slot>
    <a class="flex justify-center h-12 roboto-light mx-4 my-4" href="mailto:plaguedoctorjl@gmail.com"> 
      <EmailIcon/>
    </a>    
</main>

<style lang="postcss">  
    @import "../css/tabs.css";

    :global(body) {
      background-color: black;
    }
  
    :global(h1) {
        color: white;
        font-size: 32px;
    }
  
    :global(h2) {
        color: white;
        font-size: 16px;
    }
  
    :global(p) {
        color: white;
        font-size: 14px;
    }

    :global(li) {
        color: white;
        font-size: 14px;
    }

    :global(div) {
        color: white;
        font-size: 14px;
    }
</style>