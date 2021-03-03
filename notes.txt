const challenge = () => {
  let animal = prompt(
    "Please Select One of the Following:\n 1. Vertebrates \n 2. Invertebrates \n 3. Herbivores \n 4. Carnivores"
  );
  if (animal !== "1" && animal !== "2" && animal !== "3" && animal !== "4") {
    alert(
      "You Must Choose an Option Between 1 and 4 \nPlease Refresh the Page to Start Over"
    );
  } else {
    if ((animal === "1")) {
      let selection1 = prompt(
        "Please Select an Option Below to Find Out More:\n 1. Bengal Tiger \n 2. White Shark \n 3. African Elephant \n 4. Chipmunk \n 5. Snow Leopard"
      );
      if(selection1!=="1" && selection1!=="2" &&selection1!=="3" && selection1!=="4" && selection1!=="5"){
        alert("Please Enter a Number Between 1 and 5")
      }else{
      switch (selection1) {
        case "1":
          alert("The Bengal tiger is a tiger from a specific population of the Panthera tigris tigris subspecies that is native to the Indian subcontinent. It is threatened by poaching, loss, and fragmentation of habitat, and was estimated at comprising fewer than 2,500 wild individuals by 2011.");
          break;
        case "2":
          alert("The great white shark, also known as the great white, white shark or white pointer, is a species of large mackerel shark which can be found in the coastal surface waters of all the major oceans.");
          break;
        case "3":
          alert("The African elephant is a genus comprising two living elephant species, the African bush elephant and the smaller African forest elephant. Both are social herbivores with grey skin, but differ in the size and color of their tusks and in the shape and size of their ears and skulls.");
          break;
        case "4":
          alert("Chipmunks are small, striped rodents of the family Sciuridae. Chipmunks are found in North America, with the exception of the Siberian chipmunk which is found primarily in Asia.");
          break;
        case "5":
          alert("The snow leopard, also known as the ounce, is a large cat native to the mountain ranges of Central and South Asia. It is listed as Vulnerable on the IUCN Red List because the global population is estimated to number less than 10,000 mature individuals and is expected to decline about 10% by 2040.");
          break;
      }
      }
    }
    if ((animal === "2")) {
      let selection2 = prompt(
        "Please Select an Option Below to Find Out More:\n 1. Goliath Birdeater \n 2. Colossal Squid \n 3. Monarch Butterfly \n 4. Portuguese Man O' War \n 5. Black Widow"
      );
      if(selection2!=="1" && selection2!=="2" &&selection2!=="3" && selection2!=="4" && selection2!=="5"){
        alert("Please Enter a Number Between 1 and 5")
      }else{
      switch (selection2) {
        case "1":
          alert("The Goliath birdeater belongs to the tarantula family Theraphosidae. Found in northern South America, it is the largest spider in the world by mass – 175 g – and body length – up to 13 cm – but it is second to the giant huntsman spider by leg span.");
          break;
        case "2":
          alert("The colossal squid is part of the family Cranchiidae. It is sometimes called the Antarctic squid or giant cranch squid and is believed to be the largest squid species in terms of mass. It is the only recognized member of the genus Mesonychoteuthis and is known from only a small number of specimens.");
          break;
        case "3":
          alert("The monarch butterfly or simply monarch is a milkweed butterfly in the family Nymphalidae. Other common names, depending on region, include milkweed, common tiger, wanderer, and black veined brown. It may be the most familiar North American butterfly, and is considered an iconic pollinator species.");
          break;
        case "4":
          alert("The Portuguese man o' war, also known as the man-of-war, bluebottle, or floating terror is a marine hydrozoan found in the Atlantic Ocean and Indian Oceans. It is considered to be the same species as the Pacific man o' war, which is found mainly in the Pacific Ocean.");
          break;
        case "5":
          alert("Latrodectus is a broadly distributed genus of spiders with several species that, together, are referred to as true widows. This group is composed of those often loosely called black widow spiders, brown widow spiders, and similar spiders");
          break;
      }
      }
    }
    if ((animal === "3")) {
      let selection3 = prompt(
        "Please Select an Option Below to Find Out More:\n 1. Antelope \n 2. Beaver \n 3. Bison \n 4. Camel \n 5. Giraffe"
      );
      if(selection3!=="1" && selection3!=="2" &&selection3!=="3" && selection3!=="4" && selection3!=="5"){
        alert("Please Enter a Number Between 1 and 5")
      }else{
      switch (selection3) {
        case "1":
          alert("The term antelope is used to refer to many species of even-toed ruminant indigenous to various regions in Africa and Eurasia. Antelopes comprise a wastebasket taxon within the family Bovidae, encompassing all Old World ruminants that are not bovines, sheep, or goats. A group of antelope is called a herd.");
          break;
        case "2":
          alert("Beavers are large, semiaquatic rodents of the temperate Northern Hemisphere. There are two extant species in the genus Castor, the North American beaver and the Eurasian beaver. Beavers are the second-largest living rodents after the capybaras.");
          break;
        case "3":
          alert("Bison are large, even-toed ungulates in the genus Bison within the subfamily Bovinae. Two extant and six extinct species are recognised. Of the six extinct species, five became extinct in the Quaternary extinction event. ");
          break;
        case "4":
          alert("A camel is an even-toed ungulate in the genus Camelus that bears distinctive fatty deposits known as 'humps' on its back. Camels have long been domesticated and, as livestock, they provide food and textiles");
          break;
        case "5":
          alert("The giraffe is an African artiodactyl mammal, the tallest living terrestrial animal and the largest ruminant. It is traditionally considered to be one species, Giraffa camelopardalis, with nine subspecies.");
          break;
      }
      }
    }
    if ((animal === "4")) {
      let selection4 = prompt(
        "Please Select an Option Below to Find Out More:\n 1. Venus Fly Trap \n 2. Bald Eagle \n 3. Crocodile \n 4. Praying Mantis \n 5. Lion"
      );
      if(selection4!=="1" && selection4!=="2" &&selection4!=="3" && selection4!=="4" && selection4!=="5"){
        alert("Please Enter a Number Between 1 and 5")
      }else{
      switch (selection4) {
        case "1":
          alert("The Venus flytrap is a carnivorous plant native to subtropical wetlands on the East Coast of the United States in North Carolina and South Carolina.");
          break;
        case "2":
          alert("The bald eagle is a bird of prey found in North America. A sea eagle, it has two known subspecies and forms a species pair with the white-tailed eagle. Its range includes most of Canada and Alaska, all of the contiguous United States, and northern Mexico.");
          break;
        case "3":
          alert("Crocodiles or true crocodiles are large semiaquatic reptiles that live throughout the tropics in Africa, Asia, the Americas and Australia. Crocodylinae, all of whose members are considered true crocodiles, is classified as a biological subfamily.");
          break;
        case "4":
          alert("Mantises are an order of insects that contains over 2,400 species in about 430 genera in 30 families. The largest family is the Mantidae. Mantises are distributed worldwide in temperate and tropical habitats. They have triangular heads with bulging eyes supported on flexible necks.");
          break;
        case "5":
          alert("The lion is a species in the family Felidae and a member of the genus Panthera. It has a muscular, deep-chested body, short, rounded head, round ears, and a hairy tuft at the end of its tail. It is sexually dimorphic; adult male lions have a prominent mane.");
          break;
        }
      }
    }
  }
};