# KB74-portfolio

*Portfolio voor de minor Applied Data Science (KB74).*

**Naam:** Isa Isaku  
**Studentnummer:** 14149486  
**Datum:** 26-01-2018

## Inhoudsopgave

1. Individueel werk  
    1.1 Datacamp  
    1.2 Coursera  
    1.3 Workshops  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.3.1 SCRUM-workshop  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.3.2 JupyterHub tutorials  
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.3.3 Calling Bullshit  
2. Projectwerk  
    2.1 Projectmatige taken  
    2.2 Inhoudelijke taken  
    * Taak 4 - Literatuur Scan: LSD-SLAM  

TODO: inhoudsopgave afmaken

## 1. Individueel werk

Binnen de minor heb ik aangeleverde lesstof en opdrachten op o.a. DataCamp, Coursera en de JupyterHub zoveel als mogelijk doorlopen. In dit hoofdstuk staat aangegeven welke onderdelen ik heb afgerond inclusief bewijs.

### 1.1 Datacamp

Op DataCamp heb ik nagenoeg alle verplichte onderdelen gevolgd. Het enige wat momenteel ontbreekt zijn de 4 hoofdstukken van de cursus 'Supervised Learning with scikit-learn'. In de map [DataCamp](DataCamp "DataCamp") is het bewijsmateriaal te vinden. Niet alle verplichte onderdelen staan in het overzicht van voltooide opdrachten. Vandaar dat ik een extra afbeelding ter aanvulling heb toegevoegd.

### 1.2 Coursera

Op Coursera heb ik de eerste twee weken van de cursus 'Machine Learning' voltooid. Het materiaal van week 3 en 6 moet ik nog doorlopen. In de map [Coursera](Coursera "Coursera") is het bewijsmateriaal te vinden.

### 1.3 Workshops

Naast het online lesmateriaal hebben we ook allerlei workshops gehad over onderwerpen gerelateerd aan data science.

#### 1.3.1 SCRUM-workshop

Voor het onderzoek binnen de minor is gebruikgemaakt van de SCRUM-methodiek. Daarom hebben we in week 1 een workshop gehad over SCRUM. Bij deze workshop waren wat opdrachten die ik uitgewerkt heb in een [document](Workshops/SCRUM-workshop.pdf "document").

#### 1.3.2 JupyterHub tutorials

Op de JupyterHub van de minor heb ik de tutorials van 'Spark' en 'Exploratory Data Analysis' nog niet afgerond.

#### 1.3.3 Calling Bullshit

De 'Calling Bullshit'-opdracht heb ik nog niet afgerond.

## 2. Projectwerk

Binnen de minor heb ik met een projectgroep onderzoek gedaan naar het maken van een semantische map van stedelijke omgevingen ten behoeve van autonoom rijden. In dit hoofdstuk zal ik ingaan op mijn werkzaamheden binnen dit onderzoek.

### 2.1 Projectmatige taken

De volgende presentaties zijn o.a. door mij gecreëerd en gepresenteerd:

- [Presentatie week 6](Presentaties/Presentatie%20week%206.pdf "Presentatie week 6")
- [Presentatie week 15](Presentaties/Presentatie%20week%2015.pdf "Presentatie week 15")
- [Presentatie week 16](Presentaties/Presentatie%20week%2016.pdf "Presentatie week 16")

Verder heb ik ook de volgende notule opgesteld:

TODO: Notulen opzoeken die ik gemaakt heb.

### 2.2 Inhoudelijke taken

Binnen het onderzoek heb ik een bijdrage geleverd aan verschillende taken. Hieronder geef ik per taak aan wat mijn bijdrage is geweest.

#### Taak 4 - Literatuur Scan: LSD-SLAM

Al vrij snel in het onderzoek kwam LSD-SLAM ter sprake als een potentieel algoritme voor het gedeeltelijk opstellen van een semantische kaart. Om meer te kennis te krijgen over SLAM-algoritmes en specifiek LSD-SLAM, heb ik samen met Nektarios informatiemateriaal, zoals papers, op internet gezocht en doorgenomen. Ook heb ik met anderen van de groep die zich in het onderwerp verdiept hebben, gesproken om een beter begrip te krijgen. Uiteindelijk hebben we het informatiemateriaal in de map [LSD-SLAM informatiemateriaal](LSD-SLAM%20informatiemateriaal "LSD-SLAM informatiemateriaal") weten te verzamelen.

#### Taak 23 - Werking LSD SLAM algoritme begrijpen

Er is bij taak 4 veel informatiemateriaal over LSD-SLAM gevonden. Voor deze taak ben ik samen met Nektarios en Jeroen dieper ingegaan op de werking van LSD-SLAM. Uiteindelijk hebben we een overzichtelijke [samenvatting](Taken/Taak%204%20-%20LSD-SLAM.pdf "samenvatting") gemaakt voor de rest van de groep.

#### Taak 27 - SVO Paper bestuderen

Een ander potentieel algoritme voor een semantische kaart was SVO. Samen met Daniëllo heb ik de [paper](SVO%20informatiemateriaal/SVO_Visual_Odometry.pdf "paper") over SVO bestudeerd en de werking van het algoritme samengevat. De [samenvatting](Taken/Taak%2027%20-%20SVO.pdf "samenvatting") was opgesteld om binnen de groep een beter beeld te krijgen van het algoritme.

#### Taak 53 - Github repo maken voor eigen ORB2 branch

ORB2 bleek na enig literatuuronderzoek een goede kandidaat te zijn voor het opstellen van een semantische kaart. Het SLAM-alogirtme is open-source beschikbaar en om verder inzicht te krijgen of het algoritme binnen ons onderzoek bruikbaar was, moesten we de code kunnen bewerken. Vandaar dat ik en wat andere teamgenoten voor deze taak uiteindelijk een eigen [repository](https://github.com/urbinn/orb2 "repository") hebben gemaakt op GitHub die geforked is van de repository [ORB_SLAM2](https://github.com/Alkaid-Benetnash/ORB_SLAM2 "ORB_SLAM2") van Alkaid-Benetnash. Het vergde nog enig werk om de ORB2 software aan de praat te krijgen op de server.

#### Taak 55 - Object detection papers lezen

Na een zekere mate van progressie op het gebied van SLAM-algoritmes zijn we de focus gaan leggen op een ander belangrijk onderdeel voor het opstellen van een semantische kaart, namelijk objectdetectie. Allereerst is er gekeken naar bestaande objectdectie algoritmes. Er zijn verschillende papers gevonden waarvan er twee veelbelovend waren. Deze [papers](Objectdetectie%20informatiemateriaal "papers") hebben we allemaal grondig doorgelezen en besproken tijdens een 'Close Reading'-sessie.

#### Taak 63 - Evaluatie: aanpak pointcloud vs pointcloud

Op een gegeven moment zijn we steeds meer experimenten gaan uitvoeren met SLAM-setups, zoals ORB2, en kwam er behoefte om op formele wijze de kwaliteit van een point cloud (een ruimte met 3D-coördinaten) vast te stellen. De point cloud vormt namelijk een belangrijk onderdeel van onze semantische kaart en heeft daarom grote invloed op de kwaliteit ervan. Binnen deze taak hebben Bob en ik een [evaluatieplan](taken/Taak%2063%20-%20Evaluatieplan%20point%20cloud.pdf "evaluatieplan") voor point clouds opgesteld.

#### Taak 64 - Evaluatie implementatie: pointcloud vs pointcloud

Voor deze taak hebben Jeroen, Jeffrey, Viradj en ik het evaluatieplan geprobeerd te implementeren. In het evaluatieplan was al beschreven met welke metrics en welke tool de point clouds vergeleken dienen te worden. De uitdaging lag bij het verkrijgen van een goede ground truth point cloud. We hebben naar drie verschillende manieren gekeken om een ground truth op te stellen van de omgeving, namelijk op basis van:

* LIDAR-data
* Dieptebeeld
* ZED mesh generatie

##### LIDAR-DATA

Allereerst hebben Jeroen, Jeffrey en ik gekeken naar LIDAR-data, omdat de KITTI-dataset dit o.a. als ground truth aanbiedt en binnen de minor mogelijkheden waren om aan een LIDAR te komen. Het probleem was dat er per frame een point cloud van de LIDAR was in de KITTI-dataset. Deze moesten samengevoegd worden tot één point cloud, zodat het gebruikt kon worden om te evalueren. Dit bleek niet zo eenvoudig te zijn, omdat point clouds van opvolgende frames een verschuiving hebben, zoals te zien is in de afbeelding hieronder.

![LIDAR point clouds](Afbeeldingen/LIDAR%20point%20clouds.png)

 In een notebook, dat helaas per ongeluk verwijderd is door Jeroen, hebben we geprobeerd dit te doen met behulp van pose informatie afkomstig van de KITTI-dataset. Helaas zijn we er na lang proberen niet in geslaagd om dat voor elkaar te krijgen, waardoor deze aanpak ook niet gebruikt kon worden voor eigen opnames in bijvoorbeeld Delft.

Als gevolg van deze uitkomst hebben Jeffrey en ik gekeken naar een per frame evaluatie aanpak met behulp van het nearest neighbour algoritme. Hiervoor hebben we een test gemaakt in een [notebook](Taken/Taak%2064%20-%20Notebooks/keyframe_conversion.md "notebook"). Helaas kwamen we er al snel achter dat de LIDAR minder ver 3D-punten vind dan een visueel SLAM-algoritme voor hetzelfde opnamemoment. Bovendien bleek na een tijdje dat de beschikbare LIDAR voor deze minor niet goed genoeg was, waardoor deze optie definitief afviel.

##### Dieptebeeld

 Het volgende waarnaar we gekeken hebben is het opstellen van een ground truth met behulp van dieptebeelden. Hiervoor hebben we een tool gebruikt die beschikbaar is voor de ZED-camera en een klein [experiment](Taken/Taak%2064%20-%20Notebooks/depth_map.md "experiment") opgezet. Het gegenereerde dieptebeeld bleek altijd relatief te zijn binnen een frame. Daarnaast was het dieptebeeld niet nauwkeurig genoeg, omdat het sommige vlakken niet herkende. We zijn tot de conclusie gekomen dat deze optie ook niet ging werken.

##### ZED mesh generatie

Een andere tool voor de ZED-camera is ZEDfu die een 3D mesh, een soort point cloud zoals te zien is in de afbeelding hieronder, genereert aan de hand van een SLAM algoritme. Ik en Viradj zijn met deze tool aan de slag gegaan om te kijken of het bruikbaar was. Hiervoor hebben we beeldmateriaal van de gangen van de Slinger gebruikt. Uiteindelijk bleek dat deze tool te onnauwkeurig was, omdat het geen loop closing functionaliteit bevatte, drift vertoonde in opnames en niet goed met reflectie omging bij de bepaling van diepte.

![3D mesh van een hal in de Slinger](Afbeeldingen/3D%20mesh%20Slinger.png)

Nadat alle mogelijkheden afvielen, hebben we besloten dat het formeel evalueren van een point cloud niet gaat lukken met de middelen en kennis die wij hebben. Vandaar dat we besloten hebben dit voorlopig op informele basis te zullen gaan evalueren.

#### Taak 94 - Dieptebeeld genereren slinger

Deze taak is al beschreven bij taak 64 onder het kopje 'Dieptebeeld '.

#### Taak 95 - Evalueren slinger

Tekst

#### Taak 100 - Opnamen slinger met kruisjes op grond

Tekst

#### Taak 101 - Opnemen van beeldmateriaal in de hhs

Tekst

#### Taak 103 - Beeldmateriaal van slinger en rugzak omzetten voor orb slam 2

Tekst

#### Taak 104 - Opnemen beeldmateriaal van ovaal en buiten

Tekst

#### Taak 108 - URB: Tracking

Tekst

#### Taak 109 - URB: ORB2 in Python

Tekst

#### Taak 140 - URB uitbreiden

Tekst

#### Taak 142 - Run URB over dataset delft #141

Tekst

#### Taak 146 - Analyseren URB foute sequences Kitti

Tekst

#### Taak 152 - 1. Introduction

TODO: Link toevoegen naar paper

In een vergadering hebben we de plannen besproken voor het op te leveren paper dat gaat over onze vernieuwingen aan het orginele ORB2-algoritme. Voor deze taak hebben ik en wat andere groepsgenoten de introductie van het paper geschreven.

#### Taak 153 - 2. Related Work

TODO: Link toevoegen naar paper

Voor deze taak heb ik samen met Viradj een bijdrage geleverd aan het hoofdstuk 'Related work' van het paper, namelijk het stuk tekst over SLAM.
