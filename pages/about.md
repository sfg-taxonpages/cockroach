---
# See project.yml for variables.
---

## Overview

The _{{ app:project_name }}_ file offers a community-curated collection of richly-cited and annotated information on the Earth’s {{app:focal_taxon_common_name}}. Data found here come from a collaboratively compiled database originating in an instance of [TaxonWorks](https://taxonworks.org) managed by the [Species File Group](https://speciesfilegroup.org). This site is built using TaxonPages, learn more [here](https://github.com/SpeciesFileGroup/taxonpages). These pages are built with open-source software; read more [here](http://speciesfilegroup.org/docs/taxonworks_in_production_at_sfg.html) about what drives them and how they are supported by the Species File Group and their many collaborators. To get further involved join weekly support meetings [here](https://speciesfilegroup.org/events.html).

## Project development and maintenance

|name|role|
|----|----|
| Heidi Hopkins | Lead Curator, Founding curator of termite data, with principal contributions from Krishna et al., 2013  |
| Christian Lucanas | Data Contributor |
| Dominic Evangelista| Data Contributor |
| George Beccaloni\* | Founding curator of cockroach data |
| David C. Eades\* | Species File Developer |

_\* Past contributor, now inactive._

- **Cite** this website: Blattodea Species File. [retrieval date]. <https://cockroach.speciesfile.org>. See also [Terms of use](#terms-of-use).

### Contribute or get help
The Earth's biodiversity is vast and the data captured to describe it, while minimal in comparison, are still immense. All projects of this nature contain gaps and errors, and contributions and corrections from users are always welcome. Known gaps in this project may include an incomplete catalog of type-material, lack of species depictions, missing biological associations, incomplete distribution records, and incomplete taxonomic/publication histories. <TrackerReport label="Report a problem, offer data, or get involved" tag="a" button-class="cursor-pointer" /> on our issue tracker if you would like to help us address these or other gaps in the data, or if you find a bug.

### Extended data access
A goal of these pages is to ensure that the underlying data behind them are accessible in their digital format. By diversifying the ways the data are accessible (e.g. on the web page, in JSON, in Darwin Core standard), we increase the opportunities to both spot errors and provide new services and portals.

- Anyone interested in working on any group of insects contained in this project can obtain tutoring on how to use the rich, multi-faceted TaxonWorks' interfaces (e.g. filters, reporting, downloads). <TrackerReport label="Contact us" tag="a" button-class="cursor-pointer" /> on our issue tracker if you would like to pursue this opportunity.
- Data behind individual panels per page can be seen via the _Sitemap_ functionality.
- Each page offers an option to download a _DarwinCore formatted table_ containing all data for this taxon and its children.
- Panel data (each section on a page) and other information not available on these pages are accessible via a [TaxonWorks API](https://api.taxonworks.org) at [https://sfg.taxonworks.org/api/v1](https://sfg.taxonworks.org/api/v1).
- Core taxonomic data are exported to and available at the [Catalogue of Life](https://www.catalogueoflife.org/data/dataset/315660).


## History

The following are the major efforts to catalog the cockroaches and termites of the world.

### Cockroaches:
- Orthoptera Descripta (1838) by Hermann Burmeister
- Catalogue of the Specimens of Blattariae in the Collection of the British Museum (1868) by Francis Walker
- Genera Insectorum: Blattidae Series (1906–1910) by Robert Walter Campbell Shelford
- Orthopterorum Catalogus: Pars 3, 4, 6, 7, 11, 13, 14: Blattariae (1962–1971) by Karlis Princis
- Cockroach Species File (Digital) by George Beccaloni (~2005-2015)
  
### Termites:
- Monographie der Termiten (1855–1860) by Hermann Hagen
- Catalog of the Termites (Isoptera) of the World (1949) by Thomas Elliott Snyder
- Catalog of the Living Termites of the New World (1998) by Reginaldo Constantino
- Treatise on the Isoptera of the World (2013) in 7 Volumes by Kumar Krishna, David A. Grimaldi, Valerie Krishna, and Michael S. Engel
- Isoptera Species File (2023-2026) (Digital) by Heidi Hopkins

In 2007, Inward et al. published their well-known paper showing that termites were phylogenetically a part of the cockroach order.

Inward, D., Beccaloni, G., & Eggleton, P. (2007). Death of an order: a comprehensive molecular phylogenetic study confirms that termites are eusocial cockroaches. Biology Letters, 3(3), 331–335. DOI: 10.1098/rsbl.2007.0102 

In 2023, the Cockroach Species File transferred to a new platform (TaxonWorks), and the Isoptera Species File originated on the same platform. At the time there was no mechanism for combining these databases, but in June, 2026 the two were finally unified to reflect the work of Inward et al. (2007), and the name modified to Blattodea Species File to better reflect the name of the now complete order.

Blattodea Species Files aims to become a complete catalog of the living and extinct cockroaches and termites of the world, including the current phylogeny of the order, full taxonomic histories of individual names, asserted distributions and images of each species, bibliographies of research, and keys. Blattodea research has never been more active all over the globe and new discoveries are published monthly. Significant contributions have been made to the BSF by a number of cockroach researchers in an on-going effort to keep the species file current, and to fill in data that is missing.


## Support and funding

This Species File functionality and content is serviced in part by the Species File Group.

## Terms of use

<div class="flex items-center gap-2">
  <a
    class="min-w-fit"
    href="{{ app:copyright_image_link }}"
  >
    <img 
      src="{{ app:copyright_image }}" 
      alt="copyright" 
      class="m-0"
    >
  </a>
  <span>{{ app:copyright_text }}</span>
</div>


