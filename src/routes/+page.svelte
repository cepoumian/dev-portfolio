<script>
  import { HeroSection, AboutMeSection  }  from "$components";
  import MyWorkSection from "$components/Sections/MyWorkSection.svelte";

  const { data } = $props();
  let { workExperience, projects } = data;
</script>

<HeroSection />
<AboutMeSection {workExperience} />
<MyWorkSection {projects} />
