# Balancující robot

## Vlastnosti

Robot se pohybuje pomocí dvou kol. Zároveň dokáže zastavit a balancovat na místě. Převážně je jeho pohyb ovládán člověkem (například spárováním robota s mobilem přes bluetooth), ale trasa se nechá naplánovat i dopředu. Díky kloubům, které mají podobnou funkci jako koleno u člověka, dokáže vyskočit i do schodu.

## Konstrukce

Tělo robota můžeme rozdělit do 3 hlavních částí:

- **"hlava"** = obal, ve kterém je uložena hlavní deska, která řídí chování robota, je napojena na bluetooth modul a čidla pro kontrolu orientace - akcelerometr s gyroskopem, dále obsahuje drivery pro motory

- **2 "nohy"** = mechanická obdoba stehna + kolene + lýtka, spojuje kola s hlavou

- **2 kola** - na konci nohou umístěny motory, na které jsou napojena kola

>Na obrázcích jsou ukázány dvě varianty tohoto robota.

<img src="https://www.inceptivemind.com/wp-content/uploads/2020/06/Ascento-robot.jpg" height="200" /> <img src="https://www.plasticportal.cz/image.php?path=image/clanky/7127/tn_15606.jpg&width=230" height="200" />

## Rozbor ceny

Náklady na výrobu robota by neměly být nijak vysoké. Zvláště, když bude vyráběno několik miliónů kusů. Spokojíme-li se s jednodušší verzí robota, může program běžet ně nějaké *Arduino* desce, popřípadně méně značkovém *klonu*. Desku i senzory tak můžeme dohromady prořídit v řádech stovek korun. Na pohyb kol by zřejmě bylo vhodnější použít spíše *krokové* motory, aby robot snáze udržel balanc. Opět se však pohybujeme řádově ve stovkách. Pokud by se jednalo o produkci mála kusů mohla by být kostra vytisknuta i na *3D tiskárně*. Při tovární pak náklady na kostru robota ještě více klesnou - samozřejmě se ale musí počítat s počáteční investicí do stojů, které ji budou vyrábět. 

Myslím si, že by se nakonec mohl robot prodávat jako stavebnice, neboť by jeho sestavení nemělo být nijak náročné.

Celkové náklady na výrobu by tedy měly být kolem 1000 Kč.