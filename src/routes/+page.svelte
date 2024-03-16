<script lang="ts">
    import selectedTab from '$lib/selectedTab.js';
    $selectedTab = "Home";
</script>

<div class="flex flex-col items-center bg-neutral-800 main-panel h-auto rounded-lg px-4">
    <div class="bg-neutral-950 mt-4 sub-panel rounded-lg self-start">
      <h1 class="roboto-medium mx-4 my-2"> PlagueDoctorJL / JL-NZ</h1>
    </div>
    <div class="bg-neutral-950 my-4 sub-panel rounded-lg self-start">
      <h2 class="roboto-regular mx-4 my-3 mb-2"> Professional Experience</h2>
      <p class="roboto-light mx-4 mb-4"> 
        I've been working full-time as a software engineer for 5+ years, primarily as a 'Full Stack Software Engineer' and 
        'Unreal Engine Software Engineer'. Outside of these roles I've also been working on commissioned projects in my spare
        time for content creators, and livestreamers. For examples of the commissioned projects I've worked on, see the 'Previous
        Projects' section below.
      </p>
      <h2 class="roboto-regular mx-4 mt-3 mb-2"> Commission Pricing & Contract Work</h2>
      <p class="roboto-light mx-4 mb-4"> 
        Contract/Commission pricing is decided on a case by case basis. Before agreeing to work on a project I will provide a quote
        based on the complexity of the project, the estimated number of hours required to complete said project, and any other relevant
        factors that will effect the cost or difficulty of said project. 
      </p>
      <h2 class="roboto-regular mx-4 mt-3 mb-2"> Availability</h2>
      <p class="roboto-light mx-4 mb-4"> 
        As I work full-time as a software engineer, my availability is often quite limited. I may be unable to take on projects depending on their
        complexity and time sensitivity. Feel free to get in touch regardless, we can discuss the amount of time I have available if I am interested in 
        taking on your project/commission.
      </p>
      <h2 class="roboto-regular mx-4 mt-3 mb-2"> Previous Projects</h2>
      <div class="mx-4 mb-4">
        <p class="roboto-light"> 
          Below is a non-exhaustive list of some of the commissioned projects I've worked on:                
        </p>
        <p class="roboto-light">
          (list does not include projects related, or previously related to my day job)  
        </p>
        <ul class="roboto-light list-disc pl-3.5 mt-1">
          <li>Commercial Leadership Consulting Website</li>
          <li>VRChat Avatar Setup</li>
          <li>VRChat Worlds (bespoke design, mechanics, and visual effects)</li>
          <li>Markov Chain Twitch Bots</li>
          <li>Twitch Administration Chat Bots</li>
          <li>Discord Server Authentication Bots & Services</li>
          <li>Music Production</li>
          <li>Animated Emote Art</li>
        </ul>
      </div>      
    </div>
    <div class="bg-neutral-950 mb-4 sub-panel rounded-lg self-start">      
      <div class="roboto-light mx-4 my-4"> 
        The source code for this website is publically available at 
        <a class="hover:text-sky-400" href="https://github.com/blahblahblah">https://github.com/JL-NZ/CommissionWebsite</a> 
        as a Svelte and Typescript portfolio piece.
      </div>    
    </div>
</div>

<style lang="postcss">
  @import "../css/panels.css";
</style>