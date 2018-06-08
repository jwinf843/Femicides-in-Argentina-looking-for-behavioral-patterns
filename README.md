# Femicides in Argentina: looking for behavioral patterns

## Description

Between January the 1st and December 31 of 2017, and according to Observatory of Violence Against Women “Not One [Woman] Less” (“Ni Una Menos”) belonging to MuMaLá, [a total of 298 femicides were registered in Argentina](http://www.observatorioniunamenos.org.ar/2018/01/26/1-femicidio-cada-29hs-en-el-2017/). In the absence of official statistics on femicides in Argentina, the Civil Association La Casa del Encuentro produces in 2008 the first report of femicides in Argentina.

Lavaca, an alternative media cooperative, takes the data generated by [La Casa del Encuentro](http://www.lacasadelencuentro.org/femicidios.html) to start [a femicides database](https://www.lavaca.org/notas/una-muestra-parcial/), with its first records dated in 1974. It aims to be a transparent and focused on the victim.
  
There is also an [official database](http://datos.gob.ar/dataset/registro-sistematizacion-seguimiento-femicidios-homicidios-agravados-por-genero/archivo/050a5c1d-b4fa-4e98-b254-5938b9ef863a) of the Supreme Court of Justice of the Nation with records of femicides since 2012. This database includes transvesticides and it says if the killed person is the final victim of the femicide or a relative/friend.

There are two behaviors that catch my attention: the first is the one described before, the killing of a relative/friend of the final victim in order to control and torment her; the other one is the [suicide of the femicide after having killed his victim](https://lmdiario.com.ar/noticia/3041/muchos-femicidios-no-llegan-a-juicio-por-el-suicidio-de-los-criminales). Both behaviors respond to a way of demonstrate their power and to make clear they “own” those women, so they can decide what to do with their lives. I have reasons to think that there are also some behaviors related to period of the month and year or payment date, for example, so I hope to get some favorable result from the analysis of the databases.
  
The final idea is to write about the process and make some convincing conclusions illustrated with interesting graphics like [this study](https://elgatoylacaja.com.ar/jugada-preparada/).
    
## Futures supported

1. Show accurate information about femicides in Argentina using government databases
1. Medium post about the DS project
1. Jupyter Notebook with the DS project
1. Web page about the project

## Analizing dataset

The data is located in the `registro-de-femicidios-2018-04-13.csv` CSV file. 

- **number**: _case number_ (continuous).
- **age**: _victim's age_ (continuous).
- **gender_identity**: _victim's gender identity_: mujer, transgenero, trans femenina, hombre, travesti, mujer lesbiana (string).
- **victim_type**: _if the victim is the real objective or a related person of the victim_: principal, vinculado (string).
- **province**: _where the femicide happenned_: Buenos Aires, Chaco, Tucuman, Neuquen, Salta, Mendoza, Córdoba, Jujuy, Ciudad de Buenos Aires, Santa Fe, Corrientes, Chubut, Misiones, Santa Cruz, San Luis, Santiago del Estero, La Rioja, Catamarca, Formosa, Entre Rios, San Juan, Rio Negro, La Pampa,Tierra del Fuego (string).
- **murder_type**: _how the victim was killed. Could be one single value or a combination_: quemaduras, empalamiento, acuchillamiento, golpes, abuso sexual, asfixia, estrangulamiento, atropellamiento, disparo de bala, apuñalamiento, degollamiento, ahorcamiento, descuartizamiento, desbarrancamiento, otros (string).
- **date**: _when the femicide happened_ (date).
