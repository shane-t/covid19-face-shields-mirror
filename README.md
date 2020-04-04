
* TOC {:toc}

# Overview

Makers and enthusiasts are 3D printing disposable splash protection face shields to address a shortage of PPE during the COVID-19 crisis in Ireland.

We are using the European 3DVerkstan headband with the Prusa bottom reinforcement. The headband is 3d printable with PETG or PLA, and the shield part can be made with acetate (150+ micron preferred, thicker is better)

This document is a **work in progress and not an official guide from any organisation, project or institution** but an attempt to summarise the information that is available. Follow the conversation in the slack and facebook groups. This document is primarily aimed at those with 3D printers who wish to join this effort and are confused with the variety of information available.

If you have a 3D printer but do not have the ability to create full shields, there are options available for you. See 

### You will need


- Hole punch (ideally an adjustable hole punch capable of punching A6)
- Transparent plastic, ideally A4 size

If you don't have transparencies or the hole punch, you should still print the headbands, as there are solutions in the works to produce the shields separately.

[Bill of materials and suppliers](https://docs.google.com/spreadsheets/d/1P82SjNFjnlUv9jMCV1lQ58hv1xy0e82Laxkcx2OgL20/edit#gid=0) from OSV-X.

### STL Files

- 💾 [3dverkstan EUROPE Headband](/stl/Visor_frame_EUROPE_ISO838_v3.stl) (Visor\_frame\_EUROPE\_ISO838\_v3.stl : 211kB)
- 💾 [Prusa bottom reinforcement](/stl/bottom_reinforcement.stl) (bottom\_reinforcement.stl : 383 kB) 

### STEP Files

- 💾 [Prusa bottom reinforcement](/step/bottom_reinforcement.step) (bottom\_reinforcement.step : 329 kB) 

### Print settings

[https://3dverkstan.se/protective-visor/protective-visor-print-guide/](https://3dverkstan.se/protective-visor/protective-visor-print-guide/)

Tl;dr:

| Material      | PETG (preferred), PLA     |
| Layer height  | 0.2mm (for 0.4mm nozzle)  |
| Line width    | 0.4mm                     |
| Infill        | 0%                        |
| Wall count    | 4                         |

### Cleanliness ⚠️

- Do not make shields if you are not practicing isolation - you are risking the lives of patients and healthcare workers
- Even so, you must act like you are already infected
- Practice [aseptic technique](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4579997/) when handling printed parts or assembling shields. Understand the difference between sanitizing and sterilising something - 3D printed shields cannot be sterilized and must be discarded after use or contamination
- Wear gloves and frequently wash hands when handling printed parts. Do not touch your face or body while wearing gloves
- Maintain a clean workspace. Clean your print bed, ideally with 90% or above isopropyl alcohol
- Immediately store completed parts in airtight bags
- Leave printed or completed parts for 3 days without touching them before shipping them
- Acetate accumulates static electricity which causes it to be covered with dust and contaminants. Wear an antistatic wristband ([instructions for DIY](https://www.instructables.com/id/How-To-Make-A-Grounding-Wrist-Band/)), and operate in a clean room away from sources of dust such as pets.

## What to do with completed headbands if you cannot produce shields

Benchspace based in Cork ([website](https://benchspacecork.ie/3d-printed-faceshield-for-irish-healthcare-workers/)/[facebook](https://www.facebook.com/3dprintedfaceshields)) are collecting printed parts using the blood bike network from everywhere in the country. They have a [crowdfunding campaign](https://www.gofundme.com/f/3d-printed-faceshields-for-frontline-staff) for obtaining materials.

They have a [getting started document](https://docs.google.com/document/d/1fa9RBVyz0xO1DSHTA3a_CUmjIGVTAJh6QOq5_PqGjqQ/edit) which includes a sign up form and a [job tracker](https://docs.google.com/spreadsheets/d/1ySXC6XBCXWqMnbxaJr-0udGCNy299FHu5ZY_5JT23No/edit#gid=0). This group is preparing a HSE provided facility for central assembly and sanitizing of 3d printed parts, as well as machinery for cut-and-die of acetate sheets.

### Creating the shield

Until laser cut versions of the shield plastic are available, you can use transparent cellulose acetate sheets from office suppliers, used in binding or overhead projection.

#### Obtaining acetate

- [Q-Connect 200 micron acetate](https://www.theofficecentre.ie/q-connect-clear-a4-pvc-binding-covers-250-micron-pack-of-100-kf24011--5?fbclid=IwAR05Gf-6n0NugTUoxUMnn7gsRlD37Dx_0PgHNm7_RDUdI0YSgFI4KmAjmLU%C3%A1) from the office centre (Courier delivery)
- [150 Micron binding covers](https://www.huntoffice.ie/5-star-office-comb-binding-covers-pvc-150-micron-a4-clear-pack-100-916345.html) from huntoffice.ie
- [125 micron clear transparency film](https://www.vikingdirect.ie/en/office-depot-a4-clear-transparency-film-for-colour-laser-printers-125-micron-pack-of-50-p-5752341) from viking direct

#### Preparing the acetate (Work in Progress)

There is documentation on cutting the acetate on the [3dverkstan page](https://3dverkstan.se/protective-visor/protective-visor-versions/). Follow the instructions for the European version. 

You can use a [3d printable cutting guide](https://www.thingiverse.com/thing:4251419) for slicing the corners.

- TODO: Add a video of the acetate being prepared.
- TODO: Add template for cutting out acetate

#### Shield Assembly

- 💾 [Printout for assembling face shields](pdf/how-to-assemble-face-shield.pdf) that you can include with shipments of unassembled face shields

### What to do with completed shields (Work in progress)

- There are currently several efforts underway to coordinate how PPE is made and delivered, as well as validation of designs. The best recommendation is to contact [Covid Community Response](https://covidcommunityresponse.ie/) if you are unsure.

#### Find out where they need to go:

- Contact local healthcare centres and establish the demand for face shields
- Follow the conversation in the facebook and slack groups
- See the OSV-X slack channel [#urgent\_appeals\_volunteersneeded](https://app.slack.com/client/T01049EC3AN/C010FFHV5FC/) to find where help is needed the most

#### Prepare for shipment

- OSV-X are suggesting to label shields "CUSTOM"
- If you want to send by motorbike, leave the shields unassembled and include the above printout. Motorbike panniers can only bring about a shopping bag sized cargo
- Do not open the seal of bags containing printed parts
- See the OSV-X slack channel [#legal\_regulatory\_information group](https://app.slack.com/client/T01049EC3AN) for a legal disclaimer that should be signed by a healthcare centre

#### Ship to healthcare centre

- Contact info@covidcommunityresponse.ie and arrange transport of the PPE to healthcare centres

## Reuse of masks

In general, full face shields are single use and cannot be reused without creating an infection risk.

Whether face shields are being reused depends on the setting (hospital vs community) and the type of patients they deal with, and the workers who are using the shields.

Some facilities are cleaning the printed parts (headbands) and replacing the acetate sheets. It follows that if you can oversupply acetate, some centres may be able to get additional use out of the headbands. If you find out which facilities are doing this, please share this information with the printiing community or one of the design/distribution projects.

### Useful links

- [Google Form](https://forms.gle/iBgn1YcejnERhFzx9) to track who has 3d printers and can produce shields
- [3d Printed face shields for Irish Healthcare workers](https://www.facebook.com/104090071254209/posts/104128811250335/?d=n) - a facebook group based in Cork 
- [OSV-X face shield project working notes](https://docs.google.com/document/d/1hrgpJx-KlVm7Zv1EhKEWJzXrp8pYcDepGpfr0J4zAzk/edit)
- [Covid community response](https://covidcommunityresponse.ie/)
- [3d printing Ireland facebook group](https://www.facebook.com/groups/3dprintingireland)
- [OSV-X Slack](https://join.slack.com/t/osv-x/shared_invite/zt-cz1m3vck-Cx23KdEYUSVAKmSpd4_C3Q) 
- [Covid med supply](https://covidmedsupply.org/) - List of healthcare centres that need PPE and individuals offering it
- [Bravo Charlie Tango - Bikers coming through](https://www.facebook.com/bravocharlietango1) - formerly organised by the [Irish Photo Rally](https://www.facebook.com/groups/380561575647815/) - volunteer motorcyclists delivering PPE

## This document

This document is up to date as of 4 April 2020. Please reach out to `me``(at)``shanet.ie` for corrections or if you wish to contribute.
