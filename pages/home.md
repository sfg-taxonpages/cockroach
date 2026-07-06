---
layout: blank
---
<GalleryCarousel :depiction-id="[1279055,1279127,1279183,1279052,1279184,1279185,1279054,1279186,1279187,1279070,1279188,1279189,1279071,1279190,1279191,1279072,1279192,1279193,1279073,1279194,1279195,1279196]" height="470px">
  <div class="flex flex-col justify-center items-center w-full h-full bg-black/25 text-white gap-4 px-4 box-border">
    <span class="text-4xl font-medium">{{ app:project_name }}</span>
    <p class="text-lg sm:text-xl">A comprehensive source of knowledge on the world’s cockroaches and termites</p>
    <div class="mx-auto flex flex-col items-center mt-6 sm:mt-10 w-full">
      <autocomplete-otu class="w-full sm:w-96 text-base-content ml-2 sm:ml-0" placeholder="Search by taxon name" autofocus/>
        <p class="text-sm sm:text-base"><em>Explore! Try searching for any taxa from order <router-link to="/otus/856752">Blattodea</router-link> or just type Blatella to get started</em></p>
    </div>
  </div>
</GalleryCarousel>
        
<div class="container mx-auto my-8 px-4 md:px-0 box-border">

# {{ app:project_name }}
## Mission statement
The Blattodea Species File is a comprehensive source of knowledge about the world’s cockroaches and termites. Information found here includes valid nomenclature, classification, scientific sources, specimen data, images, keys, and distributions for all known Blattodea species of the world. This site may serve researchers in taxonomy, systematics, ecology, ethology, conservation, and evolution, as well as educators, policy makers, and citizen scientists.
        
## Discover more
See our [About](about) page for an [overview](about#overview) of the project, its data, the development [team](about#project-development-and-maintenance), and details about how you can [access the data, contribute, contact us, or get help](about#contribute-or-get-help). 

## Announcements

July 2026: Launch of Blattodea Species File, where termites were at last united with cockroaches

</div>
