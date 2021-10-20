DOCKER 
========
úvodem
---
Docker je užitečný nástroj, který e hojně používá pro webové technologie, zejména se pak pouřívá pro lokální vývoj. Pompcí tohoto nástroje si můžeme ošetřit mnoho práce a starostí. 

Nástroj lze rozjet na OS Windows i na OS Linux, který preferuji, protože je dobrým nástrojem pro vývoj a celkově se mi s ním dobře pracuje. 

Můžeme si testovat různé technologie, aniž bychom za ně museli zaplatit. 

Tento nástroj používám na vývoj webů. Simuluje reálný web s použitím reálních služeb podle toho, jak si nakonfigurujeme svůj **docker-compose.yml** file. 

**Jak Docker funguje** ....
---

Pomocí thoto nástroje muáme pod kontrolou, co se děje napozadí. 
- nejprve si nakonfigujeme **docker-compose** soubor

který obsahuje několik důležitých věcí. A to zejména:  
---
- jméno containeru - **identifikace dané služby** tzn. container_name
- image - jakou službu chceme použít (například webserver na které nám poběží web). Pokud se připojíme do xoitaneru pomocí příkazu, zobrazí e nám rozhraní, které nám simuluje prostředí opradového linux serveru. Stejné je to v případě, když zvolíme jakýkoliv image. Vždy se dostaneme do prostředí dané služby. Pokud si definujeme image s databází mysql, dostaneme se k místu, kde je možno se připojit k databázi a provádět různé sql příkazy. Pokud NodeJS, tak nám to opět simuluje image s Node JS. 
Myslím, že k této problematice se nětřeba vyjadřovat a všichni jsme pochopili fakt, k čemu vlastně takový image slouží. 
- port - dá služba musí pibět vždy pod nějakým portem (to je to číslo za dvojtečkou *localhost:**82***). Máme dva typy portů: 
    - **vnitřní**
        - pod jakým portem služba poběží (*port TCP*)
    - **vnější**
        - port, který zadáme fyzicky do řádu pro URL adresy (právě *localhost:82*)

        
    


----
Dobré články o technologii docker sepsal můj známý **Josef Jebavý**, který se uzajímá o správů serverů. Mezi jeho projekty patří například **migrace aplikace na nový server pro TOP 09**
Nabízí také instalaci aplikací na linuxové servery a následnou správu (tzn. například údžbu aplikací na nejnovějších verzích), podle Vašich preferencí 
------

S Josefem občas spolupracuji. Tvořil jsem šablonu na na jeho web **[https://linuxserveradmin.eu]**

___
Ale myslkím, že toto už je jiná kapitola, která s docker moc nesouvisí. 
Mé dosavadní projekty lze najít v rubric **Reference**
