Let's make a game!
	name:Insekten Klicker
	by:MineMausCraft and Wollä!
	desc:Erstelle eine große Insektenkolonie!
	created:16/02/2019
	updated:07/03/2019
	version:3

Settings
	background:https://i.imgur.com/wCNA1I9.jpg
	building cost increase:115%
	building cost refund:50%
	spritesheet:icons, 48 by 48, https://i.imgur.com/dJSgs3Y.png
	spritesheet:iconsa, 48 by 48, https://i.imgur.com/Bbff71y.png
	spritesheet:iconsb, 48 by 48, https://i.imgur.com/NG2x5U2.png
	
	spritesheet:iconsgr, 128 by 128, https://i.imgur.com/rIBALOu.png
	spritesheet:iconskl, 40 by 40, https://i.imgur.com/GiXFNjR.png
	stylesheet:https://pastebin.com/raw/8iFdUmTb
	on start:SuperB=2
	
Layout
	*main
  contains:res, buttons
  *res
    contains:Resources
    class:fullWidth
  *buttons
    contains:Buttons
*store
  contains:buildings, upgrades
  *buildings
    contains:BulkDisplay, Buildings
    header:Buildings
    tooltip origin:left
  *upgrades
    contains:tag:upgradesII, Upgrades
    header:Upgrades
    costs:hide
    names:hide
 *limtupgrades
                contains:tag:limitupgrades
                header:Limited Upgrades
                in:upgrades
                costs:hide
                names:hide	
					
*ownedupgrades
	contains:tag:owned
	header:Owned Upgrades
	in:upgrades
	costs:hide
	names:hide


		
Buttons



*SuperButton
        name:Superbutton
        desc:Nur Tada
        icon:https://imgur.com/5tf1r8K.png
        class:SuperButton
        text:Tada
        no tooltip
 
*SuperButton1
        name:Superbutton1
        desc:Nur Buff1
        icon:iconskl[0,0]
        class:SuperButton1
        text:Tada1
        no tooltip
      on click:anim icon wobble
      on click:yield 1 BauMaterial
*SuperButton2
        name:Superbutton1
        desc:Nur Buff1
        icon:iconskl[0,1]
        class:SuperButton2
        text:Tada2
        no tooltip
      on click:anim icon wobble
      on click:yield 1 BauMaterial
*SuperButton3
        name:Superbutton1
        desc:Nur Buff1
        icon:iconskl[0,2]
        class:SuperButton3
        text:Tada3
        no tooltip
      on click:anim icon wobble
      on click:yield 1 BauMaterial
*SuperButton4
        name:Superbutton1
        desc:Nur Buff1
        icon:iconskl[0,3]
        class:SuperButton4
        text:Tada4
        no tooltip
      on click:anim icon wobble
      on click:yield 1 BauMaterial
*SuperButton5
        name:Superbutton1
        desc:Nur Buff1
        icon:iconskl[0,4]
        class:SuperButton5
        text:Tada5
        no tooltip
      on click:anim icon wobble
      on click:yield 1 BauMaterial
*SuperButton6
        name:Superbutton1
        desc:Nur Buff1
        icon:iconskl[0,5]
        class:SuperButton6
        text:Tada6
        no tooltip
      on click:anim icon wobble
      on click:yield 1 BauMaterial
*SuperButton7
        name:Superbutton1
        desc:Nur Buff1
        icon:iconskl[0,6]
        class:SuperButton7
        text:Tada7
        no tooltip
      on click:anim icon wobble
      on click:yield 1 BauMaterial
*SuperButton8
        name:Superbutton1
        desc:Nur Buff1
        icon:iconskl[0,7]
        class:SuperButton8
        text:Tada8
        no tooltip
      on click:anim icon wobble
      on click:yield 1 BauMaterial
*SuperButton9
        name:Superbutton1
        desc:Nur Buff1
        icon:iconskl[0,8]
        class:SuperButton9
        text:Tada9
        no tooltip
      on click:anim icon wobble
      on click:yield 1 BauMaterial
*SuperButton10
        name:Superbutton10
        desc:Nur Buff1
        icon:iconskl[0,9]
        class:SuperButton10
        text:Tada10
        no tooltip
      on click:anim icon wobble
      on click:yield 1 BauMaterial
*SuperButton11
        name:Superbutton1
        desc:Nur Buff1
        icon:iconskl[0,10]
        class:SuperButton11
        text:Tada11  
        no tooltip
      on click:anim icon wobble
      on click:yield 1 BauMaterial
*SuperButton12
        name:Superbutton1
        desc:Nur Buff1
        icon:iconskl[0,11]
        class:SuperButton12
        text:Tada12
        no tooltip
      on click:anim icon wobble
      on click:yield 1 BauMaterial
*SuperButton13
        name:Superbutton1
        desc:Nur Buff1
        icon:iconskl[0,12]
        class:SuperButton13
        text:Tada13
        no tooltip
      on click:anim icon wobble
      on click:yield 1 BauMaterial
*SuperButton14
        name:Superbutton1
        desc:Nur Buff1
        icon:iconskl[0,13]
        class:SuperButton14
        text:Tada14
        no tooltip
      on click:anim icon wobble
      on click:yield 1 BauMaterial
*SuperButton15
        name:Superbutton1
        desc:Nur Buff1
        icon:iconskl[0,14]
        class:SuperButton15
        text:Tada15
        no tooltip
      on click:anim icon wobble
      on click:yield 1 BauMaterial
*SuperButton16
        name:Superbutton1
        desc:Nur Buff1
        icon:iconskl[0,15]
        class:SuperButton16
        text:Tada16
        no tooltip
      on click:anim icon wobble
      on click:yield 1 BauMaterial
*SuperButton17
        name:Superbutton1
        desc:Nur Buff1
        icon:iconskl[0,16]
        class:SuperButton17
        text:Tada17
        no tooltip
      on click:anim icon wobble
      on click:yield 1 BauMaterial
*SuperButton18
        name:Superbutton1
        desc:Nur Buff1
        icon:iconskl[0,17]
        class:SuperButton18
        text:Tada18
        no tooltip
      on click:anim icon wobble
      on click:yield 1 BauMaterial
*SuperButton19
        name:Superbutton1
        desc:Nur Buff1
        icon:iconskl[0,18]
        class:SuperButton19
        text:Tada19
        no tooltip
      on click:anim icon wobble
      on click:yield 1 BauMaterial
*SuperButton20
        name:Superbutton1
        desc:Nur Buff1
        icon:iconskl[0,19]
        class:SuperButton20
        text:Tada20
        no tooltip
      on click:anim icon wobble
      on click:yield 1 BauMaterial
*SuperButton21
        name:Superbutton1
        desc:Nur Buff1
        icon:iconskl[0,20]
        class:SuperButton21
        text:Tada21
        no tooltip
      on click:anim icon wobble
      on click:yield 1 BauMaterial
*SuperButton22
        name:Superbutton1
        desc:Nur Buff1
        icon:iconskl[1,0]
        class:SuperButton22
        text:Tada22
        no tooltip
      on click:anim icon wobble
      on click:yield 1 BauMaterial
*SuperButton23
        name:Superbutton1
        desc:Nur Buff1
        icon:iconskl[1,1]
        class:SuperButton23
        text:Tada23
        no tooltip
      on click:anim icon wobble
      on click:yield 1 BauMaterial
*SuperButton24
        name:Superbutton1
        desc:Nur Buff1
        icon:iconskl[1,2]
        class:SuperButton24
        text:Tada24
        no tooltip
      on click:anim icon wobble
      on click:yield 1 BauMaterial
*SuperButton25
        name:Superbutton1
        desc:Nur Buff1
        icon:iconskl[1,3]
        class:SuperButton25
        text:Tada25
        no tooltip
      on click:anim icon wobble
      on click:yield 1 BauMaterial
*SuperButton26
        name:Superbutton1
        desc:Nur Buff1
        icon:iconskl[1,4]
        class:SuperButton26
        text:Tada26
        no tooltip
      on click:anim icon wobble
      on click:yield 1 BauMaterial
*SuperButton27
        name:Superbutton1
        desc:Nur Buff1
        icon:iconskl[1,5]
        class:SuperButton27
        text:Tada27
        no tooltip
      on click:anim icon wobble
      on click:yield 1 BauMaterial
*SuperButton28
        name:Superbutton1
        desc:Nur Buff1
        icon:iconskl[1,6]
        class:SuperButton28
        text:Tada28
        no tooltip
      on click:anim icon wobble
      on click:yield 1 BauMaterial
*SuperButton29
        name:Superbutton1
        desc:Nur Buff1
        icon:iconskl[1,7]
        class:SuperButton29
        text:Tada29
        no tooltip
      on click:anim icon wobble
      on click:yield 1 BauMaterial
*SuperButton30
        name:Superbutton1
        desc:Nur Buff1
        icon:iconskl[1,8]
        class:SuperButton30
        text:Tada30
        no tooltip
      on click:anim icon wobble
      on click:yield 1 BauMaterial
*SuperButton31
        name:Superbutton1
        desc:Nur Buff1
        icon:iconskl[1,9]
        class:SuperButton31
        text:Tada31
        no tooltip
      on click:anim icon wobble
      on click:yield 1 BauMaterial
*SuperButton32
        name:Superbutton1
        desc:Nur Buff1
        icon:iconskl[1,10]
        class:SuperButton32
        text:Tada32
        no tooltip
      on click:anim icon wobble
      on click:yield 1 BauMaterial
*SuperButton33
        name:Superbutton1
        desc:Nur Buff1
        icon:iconskl[1,11]
        class:SuperButton33
        text:Tada33
        no tooltip
      on click:anim icon wobble
      on click:yield 1 BauMaterial
*SuperButton34
        name:Superbutton1
        desc:Nur Buff1
        icon:iconskl[1,12]
        class:SuperButton34
        text:Tada34
        no tooltip
      on click:anim icon wobble
      on click:yield 1 BauMaterial
*SuperButton35
        name:Superbutton1
        desc:Nur Buff1
        icon:iconskl[1,13]
        class:SuperButton35
        text:Tada35
        no tooltip
      on click:anim icon wobble
      on click:yield 1 BauMaterial
*SuperButton36
        name:Superbutton1
        desc:Nur Buff1
        icon:iconskl[1,14]
        class:SuperButton36
        text:Tada36
        no tooltip
      on click:anim icon wobble
      on click:yield 1 BauMaterial
*SuperButton37
        name:Superbutton1
        desc:Nur Buff1
        icon:iconskl[1,15]
        class:SuperButton37
        text:Tada38
        no tooltip
      on click:anim icon wobble
      on click:yield 1 BauMaterial
*SuperButton38
        name:Superbutton1
        desc:Nur Buff1
        icon:iconskl[1,16]
        class:SuperButton38
        text:Tada38
        no tooltip
      on click:anim icon wobble
      on click:yield 1 BauMaterial
*SuperButton39
        name:Superbutton39
        desc:Nur Buff1
        icon:iconskl[1,17]
        class:SuperButton39
        text:Tada39
        no tooltip
      on click:anim icon wobble
      on click:yield 1 BauMaterial
*SuperButton40
        name:Superbutton40
        desc:Nur Buff1
        icon:iconskl[1,18]
        class:SuperButton40
        text:Tada40
        no tooltip
      on click:anim icon wobble
      on click:yield 1 BauMaterial
*SuperButton41
        name:Superbutton41
        desc:Nur Buff1
        icon:iconskl[1,19]
        class:SuperButton41
        text:Tada41
        no tooltip
      on click:anim icon wobble
      on click:yield 1 BauMaterial
*SuperButton42
        name:Superbutton42
        desc:Nur Buff1
        icon:iconskl[1,20]
        class:SuperButton42
        text:Tada42
        no tooltip
      on click:anim icon wobble
      on click:yield 1 BauMaterial
*SuperButtonOn
        name:SuperbuttonOn
        desc:Nur Buff1
        icon:icons[9,10]
        class:SuperButtonOn
        text:Tada On
        no tooltip
      on click:anim icon wobble
      on click:yield 1 BauMaterial
        on click:show SuperButton
        on click:show SuperButton1
        on click:show SuperButton2
        on click:show SuperButton3
        on click:show SuperButton4
        on click:show SuperButton5
        on click:show SuperButton6
        on click:show SuperButton7
        on click:show SuperButton8
        on click:show SuperButton9
        on click:show SuperButton10
        on click:show SuperButton11
        on click:show SuperButton12
        on click:show SuperButton13
        on click:show SuperButton14
        on click:show SuperButton15
        on click:show SuperButton16
        on click:show SuperButton17
        on click:show SuperButton18
        on click:show SuperButton19
        on click:show SuperButton20
        on click:show SuperButton21
        on click:show SuperButton22
        on click:show SuperButton23
        on click:show SuperButton24
        on click:show SuperButton25
        on click:show SuperButton26
        on click:show SuperButton27
        on click:show SuperButton28
        on click:show SuperButton29
        on click:show SuperButton30
        on click:show SuperButton31
        on click:show SuperButton32
        on click:show SuperButton33
        on click:show SuperButton34
        on click:show SuperButton35
        on click:show SuperButton36
        on click:show SuperButton37
        on click:show SuperButton38
        on click:show SuperButton39
        on click:show SuperButton40
        on click:show SuperButton41
        on click:show SuperButton42
        on click:show SuperButtonOff
        on click:hide SuperButtonOn        
*SuperButtonOff
        name:SuperbuttonOff
        desc:Nur Buff1
        icon:icons[9,10]
        class:SuperButtonOff
        text:Tada Off
        no tooltip
      on click:anim icon wobble
      on click:yield 1 BauMaterial     
        on click:hide SuperButton
        on click:hide SuperButton1
        on click:hide SuperButton2
        on click:hide SuperButton3
        on click:hide SuperButton4
        on click:hide SuperButton5
        on click:hide SuperButton6
        on click:hide SuperButton7
        on click:hide SuperButton8
        on click:hide SuperButton9
        on click:hide SuperButton10
        on click:hide SuperButton11
        on click:hide SuperButton12
        on click:hide SuperButton13
        on click:hide SuperButton14
        on click:hide SuperButton15
        on click:hide SuperButton16
        on click:hide SuperButton17
        on click:hide SuperButton18
        on click:hide SuperButton19
        on click:hide SuperButton20
        on click:hide SuperButton21
        on click:hide SuperButton22
        on click:hide SuperButton23
        on click:hide SuperButton24
        on click:hide SuperButton25
        on click:hide SuperButton26
        on click:hide SuperButton27
        on click:hide SuperButton28
        on click:hide SuperButton29
        on click:hide SuperButton30
        on click:hide SuperButton31
        on click:hide SuperButton32
        on click:hide SuperButton33
        on click:hide SuperButton34
        on click:hide SuperButton35
        on click:hide SuperButton36
        on click:hide SuperButton37
        on click:hide SuperButton38
        on click:hide SuperButton39
        on click:hide SuperButton40
        on click:hide SuperButton41
        on click:hide SuperButton42
        on click:show SuperButtonOn
        on click:hide SuperButtonOff	




*InsektenButton
		name:Fleißiges Insekt
		desc:Klicke dieses Insekt um mehr zu bekommen!
		on click:anim icon wobble
		on click:yield 1 Insekt		
		icon:https://i.imgur.com/zacpiOy.png
		no text
		class:bigButton hasFlares
		icon class:shadowed
		tooltip origin:bottom
		tooltip class:red

*LarveButton
      name:Larve
      desc:Lass deine Larven schlüpfen!
      on click:anim icon wobble
      on click:yield 1 Larve
      icon:https://i.imgur.com/o3LDvcJ.png
      no text
      class:LarveButton hasFlares
        on tick:
            if (Zeit=30)
                lose BLarvenMulti
                lose BInsektenMulti
                lose BBauMaterialMulti
                lose BLarven333
                lose BLarven666
                lose BInsekten333
                lose BInsekten666
                lose BBauMaterial333
                lose BBauMaterial666
                toast Der Boost ist vorbei!!!
                hide tag:booster    
            end
        end

*TreeButton
      name:Alter Baumstamm
      desc:Suche hier nach BauMaterial!
      on click:anim icon wobble
      on click:yield 1 BauMaterial
      icon:https://i.imgur.com/nPpMXuV.png
      no text
	  class:TreeButton


*BrutkammerButton    
      name:Brutkammer
      desc:Ein effektiver Weg aus Larven Insekten schlüpfen zu lassen!<//> <i>Allerdings überleben nur 80% der Insekten diesen beschleunigten Vorgang.</i> <//>Von den restlichen 20% Bekommst du InsektenPanzer!
      on click:anim icon wobble
      icon:https://i.imgur.com/tBPB0Iu.png
      no text
      show clicks      
      class:BrutkammerButton
          on click:
            if ((Larven>=100) and (Larven<=999)) 
                yield 80 Insekten 
                lose 100 Larven 
				yield 20 InsektenPanzer               
            end            
            if ((Larven>=1000) and (Larven<=99999)) 
                yield 8000 Insekten 
                lose 10000 Larven 
				yield 2000 InsektenPanzer               
            end			
            if ((Larven>=100000) and (Larven<=9999999)) 
                yield 800000 Insekten 
                lose 1000000 Larven 
				yield 200000 InsektenPanzer               
            end
            if ((Larven>=10000000) and (Larven<=999999999)) 
                yield 80000000 Insekten 
                lose 100000000 Larven 
				yield 20000000 InsektenPanzer               
            end
			if ((Larven>=1000000000) and (Larven<=99999999999)) 
                yield 8000000000 Insekten 
                lose 10000000000 Larven 
				yield 2000000000 InsektenPanzer               
            end
			if ((Larven>=100000000000) and (Larven<=9999999999999)) 
                yield 800000000000 Insekten 
                lose 1000000000000 Larven 
				yield 200000000000 InsektenPanzer               
            end
			if ((Larven>=10000000000000) and (Larven<=999999999999999)) 
                yield 80000000000000 Insekten 
                lose 100000000000000 Larven 
				yield 20000000000000 InsektenPanzer               
            end
			if (Larven>=10000000000000) 
                yield 80000000000000 Insekten 
                lose 100000000000000 Larven 
				yield 20000000000000 InsektenPanzer               
            end
        end
      cost:100 Larven



*PanzerButton
		name:InsektenPanzer
		desc:Nur zur Anzeige des InsektenPanzer Anzahl
		icon:https://i.imgur.com/3LTqnss.png
		class:PanzerButton
		text:[InsektenPanzer] InsektenPanzer
		no tooltip


*TerritoriumButton    
        name:Territorium
        desc:Die Welt gehört Dir! <//><.>Macht aus <b>1000</b> Baumaterial <b>1</B> Territorium
        on click:anim icon wobble
        icon:https://i.imgur.com/asXnnnQ.png
        no text
        show clicks      
        class:TerritoriumButton
            on click:
            if ((BauMaterial>=1000) and (BauMaterial<=9999)) 
                yield 10 Territorium 
                lose 1000 BauMaterial 
            end
            if ((BauMaterial>=10000) and (BauMaterial<=999999)) 
                yield 1000 Territorium 
                lose 100000 BauMaterial 
            end
			if ((BauMaterial>=1000000) and (BauMaterial<=99999999)) 
                yield 100000 Territorium 
                lose 10000000 BauMaterial 
            end
            if ((BauMaterial>=100000000) and (BauMaterial<=9999999999)) 
                yield 10000000 Territorium 
                lose 1000000000 BauMaterial 
            end
            if ((BauMaterial>=10000000000) and (BauMaterial<=999999999999)) 
                yield 1000000000 Territorium 
                lose 100000000000 BauMaterial 
            end
            if ((BauMaterial>=1000000000000) and (BauMaterial<=99999999999999)) 
                yield 100000000000 Territorium 
                lose 10000000000000 BauMaterial 
            end
			if (BauMaterial>=100000000000000) 
                yield 10000000000000 Territorium 
                lose 1000000000000000 BauMaterial 
            end
			
        end
        cost:1000 BauMaterial
        req:1000 BauMaterial

*TerritButton
        name:Territ fdafd
        desc:Nur zur Anzeige der Territorium Anzahl
        icon:https://i.imgur.com/Xi4CwLq.png
        class:TerritButton
        text:[Territorium] Territorien
        no tooltip
		

*OPButton    
      name:Bssst
      desc:Ein bssssst 
      on click:anim icon wobble
      icon:https://imgur.com/7ulsbid.png
      no text
      show clicks      
      class:OPButton 


*statusbar
	  tag:booster
 	  name:sooooooLang
      desc:bla bla  
     // icon:https://imgur.com/7ulsbid.png
      no text
      show clicks     
      cost:100 Larven
      no text
      class:statusbar
	
*TeichButton
		name:Teich
		desc:<.> Um so besser die Wasserqualität ist, um so mehr produzierst du! <//><.>  Status: <b>Schlammpfütze</b>
		icon:https://i.imgur.com/mcb3TfY.png
		no text
		class:TeichButton
		icon class:shadowed
		tooltip origin:bottom
		tooltip class:red
		passive:multiply yield of Larven by ((Erfolge*1/100)+1)
		passive:multiply yield of Insekten by ((Erfolge*1/100)+1)
		passive:multiply yield of BauMaterial by ((Erfolge*1/100)+1)
		
		
Resources

*upgradesII
   		tag:upgradesII
    	name:Unlocked
  		desc:[upgradesII]/825 //([((upgradesII/795)*100)]%)
		
*Zeit
        name:Zeit
        desc:Als Timer für alles
        //icon:https://i.imgur.com/ICiQOnw.png.jpg
        class:noBackground
		on tick:yield 1 Zeit
        always hidden

*Larve|Larven
        name:Larve|Larven
        desc:Diese kleinen Larven werden deine Kolonie wachsen lassen!
        icon:icons[1,0]
        class:noBackground
        show earned
		
*Insekt|Insekten
		name:Insekt|Insekten
		desc:Das sind deine Insekten. Du kannst sie benutzen um dir Dinge zu kaufen. Habe so viele von ihnen wie möglich!
		icon:icons[0,0]
		class:noBackground
		show earned
		
*BauMaterial
        name:BauMaterial
        desc:Sammle BauMaterial um deine Insekten Kolonie zu vergrößern!
        icon:icons[5,0]
        class:noBackground
        show earned

*Nahrung
		name:Nahrung
		desc:Deine Kolonie braucht viel Nahrung um zu wachsen!
		icon:icons[4,2]
		class:noBackground
		show earned		
		
*Erfahrung
		name:Erfahrung
		desc:Du bekommst Erfahrung indem du Gebäude kaufst!
		icon:icons[6,1]
		class:noBackground
		show earned		
		
*InsektenPanzer|InsektenPanzer
		name:InsektenPanzer|InsektenPanzer
		desc:Eine harte Welt braucht harte Währung!
		icon:icons[5,2]
		class:noBackground
		no tooltip
		always hidden	

*Territorium|Territorien
        name:Territorium|Territorien
        desc:Sammle Territorium um deine Insekten Kolonie zu vergrößern!
        icon:icons[5,1]
        class:noBackground
        no tooltip
        always hidden
		

		
// Gebäudeproduktions Ressourcen		------------------------------------------


*TEMPLATE
		always hidden

	
		
*Raupep
		name:Produktion der Raupen
		always hidden
*Bienenstockp
		name:Produktion der Bienenstöcke
		always hidden
*Termitenbaup
		name:Produktion der Termitenbauten
		always hidden
*Blattp
		name:Produktion der Blätter
		always hidden	
*WNestp
		name:Produktion der WespenNester
		always hidden
*VApfelp
		name:Produktion der VerfaultenÄpfel
		always hidden		
		
*SammlerAp
		name:Produktion der SammlerAmeise
		always hidden
	

*ANestp
		name:Produktion der AltenNester
*Schuhp
		name:Produktion der UeberwucherterSchuh
*Pizzap
		name:Produktion der Pizzen
*Ivanp
		name:Produktion der SchneckeIvan
*Eimerp
		name:Produktion der WasserEimer
		
		

//Shinies --------------------------

	
Shinies


//1

*luckyFly
        on click:log Woop
        frequency:600
        frequency variation:600
		movement:onRight moveLeft fade bounce:0.05
		icon:iconsgr[2,0]
        class:bigButton
        on click:yield Nahrung*0.01% Nahrung
        on click:toast Du hast der kleinen Fliege <b>[Nahrung*0.01%]</b> Nahrung geklaut!
		
//2 
 
*luckyBug
	on click:log Woop   
    frequency:700
    frequency variation:600
    duration:10
    movement:anywhere fade grow
    icon:iconsgr[2,3]
    class:bigButton
    on click:yield Nahrung*0.03% Nahrung
    on click:toast Der kleine Käfer brachte dir <b>[Nahrung*0.03%]</b> Nahrung!
	
//3	
	
*luckyMai
	on click:log Woop
    frequency:800
    frequency variation:600
    duration:10
    movement:onLeft moveRight bobVertical
    icon:iconsgr[2,1]
    class:bigButton
    on click:yield Nahrung*0.02% Nahrung
    on click:toast Der kleine Maikäfer brachte dir <b>[Nahrung*0.02%]</b> Nahrung!

//4

*luckyGemeinerKaefer
	on click:log Woop  
    frequency:900
    frequency variation:600
    duration:10
    movement:moveRandom growShrink
    icon:iconsgr[2,2]
    class:bigButton
    on click:lose Nahrung*0.01% Nahrung
    on click:toast Der gemeine Käfer stahl dir <b>[Nahrung*0.2%]</b> Nahrung!
	
//5	
	
*luckyMariechen
 	on click:log Woop  
    frequency:1000
    frequency variation:600
    duration:10
    movement:anywhere pulse growShrink
    icon:iconsgr[2,6]
    class:bigButton
    on click:yield Nahrung*0.01% Nahrung
    on click:toast Mariechen brachte dir <b>[Nahrung*0.01%]</b> Nahrung!

//6	
	
*luckyKakerlake
	on click:log Woop   
    frequency:1100
    frequency variation:600
    duration:10
    movement:anywhere fade growShrink
    icon:iconsgr[2,5]
    class:bigButton
    on click:yield Nahrung*0.001% Nahrung
    on click:toast Die faule Kakerlake brachte dir <b>[Nahrung*0.001%]</b> Nahrung!
	
//7	
	
*luckyMike
 	on click:log Woop  
    frequency:1200
    frequency variation:600
    duration:5
	movement:onRight fade moveLeft
    icon:iconsgr[2,4]
    class:bigButton
    on click:yield Nahrung*0.01% Nahrung
    on click:toast Der schnelle Mike brachte dir <b>[Nahrung*0.01%]</b> Nahrung!
	
//8

*luckyBee
    on click:log Woop
    frequency:1300
    frequency variation:600
	movement:onRight moveLeft fade bounce:0.05
	icon:iconsgr[2,7]
	class:bigButton
    on click:yield Nahrung*0.01% Nahrung
    on click:toast Die kleine Biene brachte dir <b>[Nahrung*0.01%]</b> Nahrung!
	
//9
	
*luckyMaikaefer
	on click:log Woop   
    frequency:600
    frequency variation:360
    duration:10
    movement:anywhere fade growShrink
    icon:iconsgr[2,8]
    class:bigButton
	    on click:
        if (chance(1%))
            lose Zeit
            show tag:booster
            yield BInsektenMulti  
			toast Insektenproduktion x7!
        else
            yield Nahrung*0.002% Nahrung
            toast Der Maikäfer brachte dir <b>[Nahrung*0.002%]</b> Nahrung!
        end
    end    

		
//10

*luckyBienchen
    on click:log Woop
    frequency:700
    frequency variation:360
	movement:onRight moveLeft fade bounce:0.05
	icon:iconsgr[2,9]
	class:bigButton
	    on click:
        if (chance(1%))
            lose Zeit
            show tag:booster
            yield BBauMaterial666
			toast Holzfäller!
        else
            yield Nahrung*0.02% Nahrung
            toast Das kleine Bienchen brachte dir <b>[Nahrung*0.02%]</b> Nahrung!
        end
    end    

		
//11
	
*luckyMai2
	on click:log Woop   
    frequency:800
    frequency variation:360
    duration:10
    movement:anywhere fade growShrink
    icon:iconsgr[3,0]
    class:bigButton
	    on click:
        if (chance(1%))
            lose Zeit
            show tag:booster
            yield BBauMaterial333
			toast Kettensäge!
        else
            yield Nahrung*0.001% Nahrung
            toast Der Maikäfer brachte dir <b>[Nahrung*0.001%]</b> Nahrung!
        end
    end    

	
//12
	
*luckyFliege
	on click:log Woop   
    frequency:900
    frequency variation:360
    duration:10
    movement:anywhere fade growShrink
    icon:iconsgr[3,1]
    class:bigButton
	    on click:
        if (chance(1%))
            lose Zeit
            show tag:booster
            yield BInsekten666
			toast Insekten klicken mal 666!
        else
            yield Nahrung*0.002% Nahrung
            toast Die Fliege brachte dir <b>[Nahrung*0.002%]</b> Nahrung!
        end
    end    

  
//13
	
*luckyGrKaefer
	on click:log Woop   
    frequency:1000
    frequency variation:360
    duration:10
    movement:anywhere fade growShrink
    icon:iconsgr[3,2]
    class:bigButton
	    on click:
        if (chance(1%))
            lose Zeit
            show tag:booster
            yield BInsekten333  
			toast Klick das Insekt!
        else
            yield Nahrung*0.012% Nahrung
            toast Der grüne Käfer brachte dir <b>[Nahrung*0.012%]</b> Nahrung!
        end
    end    

	
	
//14
	
*luckyMoskito
	on click:log Woop   
    frequency:1100
    frequency variation:360
    duration:10
    movement:anywhere fade growShrink
    icon:iconsgr[3,3]
    class:bigButton
	    on click:
        if (chance(1%))
            lose Zeit
            show tag:booster
            yield BLarven666 
			toast Massenschlüpfen!
        else
            yield Nahrung*0.02% Nahrung
            toast Der Moskito brachte dir <b>[Nahrung*0.02%]</b> Nahrung!
        end
    end    

	
//15
	
*luckyMuecke
	on click:log Woop   
    frequency:1200
    frequency variation:360
    duration:10
    movement:anywhere fade growShrink
    icon:iconsgr[3,4]
    class:bigButton
	    on click:
        if (chance(1%))
            lose Zeit
            show tag:booster
            yield BLarven333
			toast Klick die Larve, klicken bringt 333 mal so viel!
        else
            yield Nahrung*0.01% Nahrung
            toast Die Mücke brachte dir <b>[Nahrung*0.01%]</b> Nahrung!
        end
    end    

	
//16
	
*luckyGelb
	on click:log Woop   
    frequency:1300
    frequency variation:360
    duration:10
    movement:anywhere fade growShrink
    icon:iconsgr[3,5]
    class:bigButton
	    on click:
        if (chance(1%))
            lose Zeit
            show tag:booster
            yield BBauMaterialMulti
			toast Sägewerk!
        else
            yield Nahrung*0.02% Nahrung
            toast Der gelbe Käfer brachte dir <b>[Nahrung*0.02%]</b> Nahrung!
        end
    end    

	
		

//17	
	
*luckyBird
 	on click:log Woop  
    frequency:1400
    frequency variation:360
    duration:5
	movement:onLeft fade moveRight bounce
    icon:iconsgr[3,6]
    class:bigButton
	    
    on click:
        if (chance(1%))
            lose Zeit
            show tag:booster
            yield BLarvenMulti
			toast Larvenproduktion mal 7!
        else
            yield Nahrung*0.01% Nahrung
            toast Das kleine Vögelchen brachte dir <b>[Nahrung*0.01%]</b> Nahrung!
        end
    end    


//18

*luckyAngryBird
     on click:log Woop  
    frequency:1500
    frequency variation:360
    duration:5
    movement:onRight fade moveLeft
    icon:iconsgr[3,7]
    class:bigButton
    
    on click:
        if (chance(1%))
            lose Zeit
            show tag:booster
            yield BInsektenMulti
			toast Du produzierst 7 mal so viele Insekten!
        else
            yield Nahrung*0.01% Nahrung
            toast Der böse Vogel brachte dir <b>[Nahrung*0.01%]</b> Nahrung!
        end
    end    

	
Buildings
	*TEMPLATE
		on click:anim glow


// **** BOOST MULTI ****	
// 1-1 / 2-0.5 / 3-0.33333333 / 4-0.25 / 5-0.2 / 6-0.16666667 / 7-0.14285714 / 8-0.125 / 9-0.11111111 / 10-0.1 / 11-0.09090909
// 333-0.003003 / 666-0.0015015
*BLarvenMulti
		name:Larven x7
		desc:Larven Boost
		cost:0 Larven
		passive:multiply yield of Larven by 7
		passive:multiply yield of LarveButton by 0.14285714
		always hidden	
*BInsektenMulti
		name:Insekten x11
		desc:Insekten Boost
		cost:0 Larven
		passive:multiply yield of Insekten by 11
		passive:multiply yield of InsektenButton by 0.09090909
		always hidden
*BBauMaterialMulti
		name:BauMaterial x5
		desc:BauMaterial Boost
		cost:0 Larven
		passive:multiply yield of BauMaterial by 5
		passive:multiply yield of TreeButton by 0.2
		always hidden
*BLarven333
		name:Larven x333
		desc:Larven Boost
		cost:0 Larven
		passive:multiply yield of LarveButton by 333
		always hidden
*BLarven666
		name:Larven x666
		desc:Larven Boost
		cost:0 Larven
		passive:multiply yield of LarveButton by 666
		always hidden
*BInsekten333
		name:Insekten x333
		desc:Insekten Boost
		cost:0 Larven
		passive:multiply yield of InsektenButton by 333
		always hidden
*BInsekten666
		name:Insekten x666
		desc:Insekten Boost
		cost:0 Larven
		passive:multiply yield of InsektenButton by 666
		always hidden
*BBauMaterial333
		name:BauMaterial x333
		desc:BauMaterial Boost
		cost:0 Larven
		passive:multiply yield of TreeButton by 333
		always hidden
*BBauMaterial666
		name:BauMaterial x666
		desc:BauMaterial Boost
		cost:0 Larven
		passive:multiply yield of TreeButton by 666	
 		always hidden

		
*Erfolg|Erfolge
		name:Erfolg|Erfolge
		desc:nur für mich
		class:noBackground
        no tooltip
		no buy


//Nahrungs Gebäude -----------------

 //1
*SammlerAmeise|SammlerAmeisen
    name:SammlerAmeise|SammlerAmeisen
    desc:Fleißge SammlerAmeisen die Nahrung in die Kolonie bringen!<//><b><.></b> Produziert <b>3</b> Nps. Aktuell: <b>[SammlerAp:ps/SammlerAmeise]</b> Nps<//><.> Produktion aktuell: <b>[SammlerAp:ps]</b> Nps
    icon:icons[4,3]
    cost:18 Insekten
	cost increase:105%
    on tick:yield 3 Nahrung
	on tick:yield 3 SammlerAp
    req:1000 Insekten:earned   
	on earn:yield 0.1 Erfahrung
	
//2
	   
*SucherAmeise|SucherAmeisen
    name:SucherAmeise|SucherAmeisen
    desc:Sie sind sehr effizient bei der Nahrungssuche!<//><b><.></b> Produziert <b>260</b> Nps.<//><.> Produktion: <b>[SucherAmeise*260]</b> /Nps 
    icon:icons[4,4]
    cost:112000 Insekten
	cost increase:102%
    on tick:yield 260 Nahrung
    req:112000 Insekten:earned and 900 SammlerAmeisen
	on earn:yield 0.1 Erfahrung
	
//3
	   
*JaegerAmeise|JaegerAmeisen
    name:JägerAmeise|JägerAmeisen
    desc:Sie sind großarte Jäger!<//><b><.></b> Produziert <b>380000</b> Nps.<//><.> Produktion: <b>[JaegerAmeise*380000]</b> /Nps 
    icon:icons[4,5]
    cost:420000000 Insekten
	cost increase:102%
    on tick:yield 380000 Nahrung
    req:420000000 Insekten:earned and 900 SucherAmeise
	on earn:yield 0.1 Erfahrung
	
 
 
 
 
 
//Larven Gebäude ---------------
 
 
 
 //1
*Raupe|Raupen
    name:Raupe|Raupen
    desc:Diese Raupe produziert viele Larven!<//><b><.></b> Produziert <b>0.3</b> Lps. Aktuell: <b>[Raupep:ps/Raupe]</b> Lps <//><b><.></b> Produktion aktuell: <b>[Raupep:ps]</b> Lps 
    icon:icons[18,0]
    cost:16 Larven
    on tick:yield 0.3 Larve
	on tick:yield 0.3 Raupep
	on earn:yield 0.1 Erfahrung
    req:1 Larve:earned   
	
//2
	   
*Bienenstock
    name:Bienenstock|Bienenstöcke
    desc:Viele kleine Bienenlarven wachsen hier! <//><b><.></b> Produziert <b>1</b> Lps. Aktuell: <b>[Bienenstockp:ps/Bienenstock]</b> Lps <//><b><.></b> Produktion aktuell: <b>[Bienenstockp:ps]</b> Lps <//><b><.></b> Verbrauch: <b>1</b> Bps und <b>1</b> Nps <//><b><.></b> Gesamter Vb: <b>[Bienenstock*1]</b>/Bps und <b>[Bienenstock*1]</b>/Nps
    icon:icons[1,1]
    cost:112 Larven, 10 Nahrung, 1 Territorien
    on tick:yield 1 Larven
    on tick:yield 1 Bienenstockp
	on tick:lose 1 BauMaterial
 	on tick:lose 1 Nahrung
	on earn:yield 1 Erfahrung
	req:112 Larven:earned 
	
//3
	   
*Termitenbau
    name:Termitenbau
    desc:So viel Platz für kleine Larven! <//><b><.></b> Produziert <b>8</b> Lps. Aktuell: <b>[Termitenbaup:ps/Termitenbau]</b> Lps <//><b><.></b> Produktion aktuell: <b>[Termitenbaup:ps]</b> Lps <//><b><.></b> Verbrauch: <b>2</b> Bps und <b>5</b> Nps <//><b><.></b> Gesamter Vb: <b>[Termitenbau*2]</b>/Bps und <b>[Termitenbau*5]</b>/Nps
    icon:icons[1,2]
    cost:1232 Larven, 123 Nahrung, 10 Territorien
    on tick:yield 8 Larven
    on tick:yield 8 Termitenbaup
 	on tick:lose 2 BauMaterial
	on tick:lose 5 Nahrung
	on earn:yield 1 Erfahrung
	req:1232 Larven:earned  
	
 //4
	  
*Blatt
    name:Blatt|Blätter
    desc:An der Unterseite dieses Blattes kleben viele Larven! <//><b><.></b> Produziert <b>48</b> Lps. Aktuell: <b>[Blattp:ps/Blatt]</b> Lps <//><b><.></b> Produktion aktuell: <b>[Blattp:ps]</b> Lps <//><b><.></b> Verbrauch: <b>3</b> Bps und <b>10</b> Nps <//><b><.></b> Gesamter Vb: <b>[Blatt*3]</b>/Bps und <b>[Blatt*10]</b>/Nps
    icon:icons[1,3]
    cost:13440 Larven, 1344 Nahrung, 100 Territorien
    on tick:yield 48 Larven
    on tick:yield 48 Blattp  
 	on tick:lose 3 BauMaterial
	on tick:lose 10 Nahrung
	on earn:yield 1 Erfahrung
	req:13440 Larven:earned 
	
//5
	     
*WespenNest|WespenNester
    name:WespenNest|WespenNester
    desc:Vorsicht sie stechen! <//><b><.></b> Produziert <b>266</b> Lps. Aktuell: <b>[WNestp:ps/WespenNest]</b> Lps <//><b><.></b> Produktion aktuell: <b>[WNestp:ps]</b> Lps <//><b><.></b> Verbrauch: <b>15</b> Bps und <b>75</b> Nps <//><b><.></b> Gesamter Vb: <b>[WespenNest*15]</b>/Bps und <b>[WespenNest*50]</b>/Nps
    icon:icons[1,4]
    cost:145600 Larven, 14560 Nahrung, 1000 Territorien
    on tick:yield 266 Larven
	on tick:yield 266 WNestp
	on tick:lose 15 BauMaterial
	on tick:lose 50 Nahrung
	on earn:yield 1 Erfahrung
    req:145600 Larven:earned   
	
//6
	      
*VerfaulterApfel|VerfaulteAepfel
    name:VerfaulterApfel|VerfaulteÄpfel
    desc:So schön faulig, bietet Platz für einige Larven! <//><b><.></b> Produziert <b>1430</b> Lps. Aktuell: <b>[VApfelp:ps/VerfaulterApfel]</b> Lps <//><b><.></b> Produktion aktuell: <b>[VApfelp:ps]</b> Lps <//><b><.></b> Verbrauch: <b>80</b> Bps und <b>75</b> Nps<//><b><.></b> Gesamter Vb: <b>[VerfaulterApfel*80]</b>/Bps und <b>[VerfaulterApfel*75]</b>/Nps
    icon:icons[1,5]
    cost:1568000 Larven, 156800 Nahrung, 10000 Territorien
    on tick:yield 1430 Larven
	on tick:yield 1430 VApfelp
   	on tick:lose 80 BauMaterial
	on tick:lose 75 Nahrung
	on earn:yield 1 Erfahrung
    req:1568000 Larven:earned   
	
//7
	   
*AltesNest|AlteNester
    name:AltesNest|AlteNester
    desc:Niemand weiß wer es gebaut hat aber es ist dunkel! <//><b><.></b> Produziert <b>7966</b> Lps. Aktuell: <b>[ANestp:ps/AltesNest]</b> Lps <//><b><.></b> Produktion aktuell: <b>[ANestp:ps]</b> Lps <//><b><.></b> Verbrauch: <b>300</b> Bps und <b>100</b> Nps<//><b><.></b> Gesamter Vb: <b>[AltesNest*300]</b>/Bps und <b>[AltesNest*100]</b>/Nps
    icon:icons[1,6]
    cost:22400000 Larven, 2240000 Nahrung, 100000 Territorien
    on tick:yield 7966 Larven
    on tick:yield 7966 ANestp
    req:22400000 Larven:earned   
   	on tick:lose 300 BauMaterial
	on tick:lose 100 Nahrung
	on earn:yield 1 Erfahrung
	
//8
	   
*UeberwucherterSchuh|UeberwucherteSchuhe
    name:ÜberwucherterSchuh|ÜberwucherteSchuhe
    desc:Alt und stinkig, wie lange steht er wohl schon hier?!<//><b><.></b> Produziert <b>44936</b> Lps. Aktuell: <b>[Schuhp:ps/UeberwucherterSchuh]</b> Lps <//><b><.></b> Produktion aktuell: <b>[Schuhp:ps]</b> Lps <//><b><.></b> Verbrauch: <b>300</b> Bps und <b>100</b> Nps<//><b><.></b> Gesamter Vb: <b>[UeberwucherterSchuh*1201]</b>/Bps und <b>[UeberwucherterSchuh*125]</b>/Nps
    icon:icons[1,7]
    cost:369600000 Larven, 36960000 Nahrung, 1000000 Territorien
    on tick:yield 44936 Larven
	on tick:yield 44936 Schuhp
    req:369600000 Larven:earned
 	on tick:lose 1201 BauMaterial
	on tick:lose 125 Nahrung
	on earn:yield 1 Erfahrung
	
//9
	   
*Pizza|Pizzen
    name:Pizza|Pizzen
    desc:Sie war mal lecker!<//><b><.></b> Produziert <b>265532</b> Lps. Aktuell: <b>[Pizzap:ps/Pizza]</b> Lps <//><b><.></b> Produktion aktuell: <b>[Pizzap:ps]</b> Lps <//><b><.></b> Verbrauch: <b>10000</b> Bps und <b>150</b> Nps<//><b><.></b> Gesamter Vb: <b>[Pizza*10000]</b>/Bps und <b>[Pizza*150]</b>/Nps
    icon:icons[1,8]
    cost:5712000000 Larven, 571200000 Nahrung, 10000000 Territorien
    on tick:yield 265532 Larven
	on tick:yield 265532 Pizzap
    req:5712000000 Larven:earned
 	on tick:lose 10000 BauMaterial
	on tick:lose 150 Nahrung
	on earn:yield 1 Erfahrung
	
//10
	   
*SchneckeIvan|SchneckenIvan
    name:SchneckeIvan|SchneckenIvan
    desc:Er ist nicht schnell aber sein Haus ist voller Eier!<//><b><.></b> Produziert <b>1634043</b> Lps. Aktuell: <b>[Ivanp:ps/SchneckeIvan]</b> Lps <//><b><.></b> Produktion aktuell: <b>[Ivanp:ps]</b> Lps <//><b><.></b> Verbrauch: <b>50000</b> Bps und <b>175</b> Nps<//><.> Gesamter Vb: <b>[SchneckeIvan*50000]</b>/Bps und <b>[SchneckeIvan*175]</b>/Nps
    icon:icons[1,9]
    cost:84000000000 Larven, 8400000000 Nahrung, 100000000 Territorien
    on tick:yield 1634043 Larven
    on tick:yield 1634043 Ivanp
    req:84000000000 Larven:earned
 	on tick:lose 50000 BauMaterial
	on tick:lose 175 Nahrung
	on earn:yield 1 Erfahrung
	
//11
	   
*WasserEimer
    name:WasserEimer
    desc:Ein wunderbares zuhause für Wasser liebende Larven!<//><b><.></b> Produziert <b>10212766</b> Lps. Aktuell: <b>[Eimerp:ps/WasserEimer]</b> Lps <//><b><.></b> Produktion aktuell: <b>[Eimerp:ps]</b> Lps <//><b><.></b> Verbrauch: <b>300000</b> Bps und <b>200</b> Nps<//><.> Gesamter Vb: <b>[WasserEimer*300000]</b>/Bps und <b>[WasserEimer*200]</b>/Nps
    icon:icons[1,10]
    cost:1120000000000 Larven, 112000000000 Nahrung, 1000000000 Territorien
    on tick:yield 10212766 Larven
    on tick:yield 10212766 Eimerp
    req:1120000000000 Larven:earned 
   	on tick:lose 300000 BauMaterial
	on tick:lose 200 Nahrung
	on earn:yield 1 Erfahrung
	
//12
	   
*DahlienBusch|DahlienBuesche
    name:DahlienBusch|DahlienBüsche
    desc:Schmetterlingslarven fühen sich hier pudelwohl!<//><b><.></b> Produziert <b>66382979</b> Lps.<//><.> Produktion: <b>[DahlienBusch*66382979]</b> /Lps <//><.> Verbrauch: <b>2147929</b> Bps und <b>225</b> Nps<//><.> Gesamter Vb: <b>[DahlienBusch*2147929]</b>/Bps und <b>[DahlienBusch*225]</b>/Nps
    icon:icons[1,11]
    cost:15680000000000 Larven, 15680000000000 Nahrung, 10000000000 Territorien
    on tick:yield 66382979 Larven
    req:15680000000000 Larven:earned
 	on tick:lose 2147929 BauMaterial
	on tick:lose 225 Nahrung
	on earn:yield 1 Erfahrung
	
//13
	   
*Maruscha|Maruschas
    name:Maruscha|Maruschas
    desc:Sie ist eine Krabbe und rot!<//><b><.></b> Produziert <b>439148936</b> Lps.<//><.> Produktion: <b>[Maruscha*439148936]</b> /Lps <//><.> Verbrauch: <b>12887574</b> Bps und <b>250</b> Nps<//><.> Gesamter Vb: <b>[Maruscha*12887574]</b>/Bps und <b>[Maruscha*250]</b>/Nps
    icon:icons[1,12]
    cost:190400000000000 Larven, 190400000000000 Nahrung, 100000000000 Territorien
    on tick:yield 439148936 Larven
    req:190400000000000 Larven:earned      
	on tick:lose 12887574 BauMaterial
	on tick:lose 250 Nahrung
	on earn:yield 1 Erfahrung
	
//14
	   
*Gelbfisch|Gelbfische
	name:Gelbfisch|Gelbfische
	desc:Dieser Gelbfisch ist geschickt im Larven fangen!<//><b><.></b> Produziert <b>2961702128</b> Lps.<//><.> Produktion: <b>[Gelbfisch*2961702128]</b> /Lps <//><.> Verbrauch: <b>85256259</b> Bps und <b>275</b> Nps<//><.> Gesamter Vb: <b>[Gelbfisch*85256259]</b>/Bps und <b>[Gelbfisch*275]</b>/Nps
	icon:icons[1,13]
	cost:2352000000000000 Larven, 235200000000000 Nahrung, 1000000000000 Territorien
	on tick:yield 2961702128 Larven
	req:2352000000000000 Larven:earned   
	on tick:lose 85256259 BauMaterial
	on tick:lose 275 Nahrung
	on earn:yield 1 Erfahrung
	
//15
	   
*Schildkroete|Schildkroeten
	name:Schildkröte|Schildkröten
	desc:Unter einem Schildkröten Panzer kann man viele Larven vestecken!<//><b><.></b> Produziert <b>21446808511</b> Lps.<//><.> Produktion: <b>[Schildkroete*21446808511]</b> /Lps <//><.> Verbrauch: <b>574984069</b> Bps und <b>300</b> Nps<//><.> Gesamter Vb: <b>[Schildkroete*574984069]</b>/Bps und <b>[Schildkroete*300]</b>/Nps
	icon:icons[1,14]
	cost:30576000000000000 Larven, 3057600000000000 Nahrung, 10000000000000 Territorien
	on tick:yield 21446808511 Larven
	req:30576000000000000 Larven:earned
	on tick:lose 574984069 BauMaterial
	on tick:lose 300 Nahrung
	on earn:yield 1 Erfahrung
	
//16
	   
*Banane|Bananen
	name:Banane|Bananen
	desc:Bananen sind süß und safig, ein prima ort für unsere Larven!<//><b><.></b> Produziert <b>153191489362</b> Lps.<//><.> Produktion: <b>[Banane*153191489362]</b> /Lps <//><.> Verbrauch: <b>4163677742</b> Bps und <b>325</b> Nps<//><.> Gesamter Vb: <b>[Banane*4163677742]</b>/Bps und <b>[Banane*325]</b>/Nps
	icon:icons[1,15]
	cost:364560000000000000 Larven, 36456000000000000 Nahrung, 100000000000000 Territorien
	on tick:yield 153191489362 Larven
	req:364560000000000000 Larven:earned 
	on tick:lose 4163677742 BauMaterial
	on tick:lose 325 Nahrung
	on earn:yield 1 Erfahrung
	
//17
	   
*Kroete|Kroeten
	name:Kröte|Kröten
	desc:So viel Laich!<//><b><.></b> Produziert <b>919148936170</b> Lps.<//><.> Produktion: <b>[Kroete*919148936170]</b> /Lps <//><.> Verbrauch: <b>29740555303</b> Bps und <b>350</b> Nps<//><.> Gesamter Vb: <b>[Kroete*29740555303]</b>/Bps und <b>[Kroete*350]</b>/Nps
	icon:icons[1,16]
	cost:4739280000000000000 Larven, 473928000000000000 Nahrung, 1000000000000000 Territorien
	on tick:yield 919148936170 Larven
	req:4739280000000000000 Larven:earned   
	on tick:lose 29740555303 BauMaterial
	on tick:lose 350 Nahrung
	on earn:yield 1 Erfahrung
	

//Insekten Gebäude ------------------------------------------------

//1	   
 
*Ameise|Ameisen
    name:Ameise|Ameisen
    desc:kleine Ameisen<//><b><.></b> Produziert <b>0.2</b> Insekten pro Sekunde.<//><.> Produktion: <b>[Ameise*0.2]</b> /Ips
    icon:icons[0,0]
    cost:14 Insekten,7 Larven,2 BauMaterial
    on tick:yield 0.2 Insekten
    req:1 Insekten:earned
	on earn:yield 0.1 Erfahrung
	
//2
	   
*Termite|Termiten
    name:Termite|Termiten
    desc:kleine Termiten<//><b><.></b> Produziert <b>1</b> Insekt pro Sekunde.<//><.> Produktion: <b>[Termite*1]</b> /Ips <//><.> Verbrauch: <b>1</b> Bps Total: <b>[Termiten*1]</b>/Bps
    icon:icons[0,1]
    cost:140 Insekten,70 Larven,35 BauMaterial
    on tick:yield 1 Insekten
    req:14 Insekten:earned and UpgITermitorium
 	on tick:lose 1 BauMaterial
	on earn:yield 1 Erfahrung
	
//3
	   
*Fliege|Fliegen
    name:Fliege|Fliegen
    desc:kleine Fliegen<//><b><.></b> Produziert <b>7</b> Insekt pro Sekunde.<//><.> Produktion: <b>[Fliegen*7]</b> /Ips <//><.> Verbrauch: <b>2</b> Baumaterial pro Sekunde <//><.> Gesamter Vb: <b>[Fliege*2]</b>/Bps
    icon:icons[0,2]
    cost:1540 Insekten,770 Larven,385 BauMaterial
    on tick:yield 7 Insekten
    req:1540 Insekten:earned and UpgISchmeisfliege
 	on tick:lose 2 BauMaterial
	on earn:yield 1 Erfahrung
	
//4
	   
*Kaefer
    name:Käfer
    desc:Kleine Käfer<//><b><.></b> Produziert <b>39</b> Insekt pro Sekunde.<//><.> Produktion: <b>[Kaefer*39]</b> /Ips <//><.> Verbrauch: <b>3</b> Baumaterial pro Sekunde <//><.> Gesamter Vb: <b>[Kaefer*3]</b>/Bps
    icon:icons[0,3]
    cost:16800 Insekten,8400 Larven, 4200 BauMaterial
    on tick:yield 39 Insekten
    req:16800 Insekten:earned and UpgIBuggy
 	on tick:lose 3 BauMaterial
	on earn:yield 1 Erfahrung
	
//5
	   
*Biene|Bienen
    name:Biene|Bienen
    desc:Kleine Biene<//><b><.></b> Produziert <b>217</b> Insekt pro Sekunde.<//><.> Produktion: <b>[Biene*217]</b> /Ips <//><.> Verbrauch: <b>15</b> Baumaterial pro Sekunde <//><.> Gesamter Vb: <b>[Biene*15]</b>/Bps
    icon:icons[0,4]
    cost:182000 Insekten,91000 Larven,45500 BauMaterial
    on tick:yield 217 Insekten
    req:182000 Insekten:earned and UpgIBienenqueen
	on tick:lose 15 BauMaterial
	on earn:yield 1 Erfahrung
	
//6
	   
*RoteAmeise|RoteAmeisen
    name:RoteAmeise|RoteAmeisen
    desc:Fleißige rote Ameisen<//><b><.></b> Produziert <b>1168</b> Insekt pro Sekunde.<//><.> Produktion: <b>[RoteAmeise*1168]</b> /Ips <//><.> Verbrauch: <b>80</b> Baumaterial pro Sekunde <//><.> Gesamter Vb: <b>[RoteAmeise*80]</b>/Bps
    icon:icons[0,5]
    cost:1960000 Insekten,980000 Larven,490000 BauMaterial
    on tick:yield 1168 Insekten
    req:1960000 Insekten:earned and UpgIRoteAmeise
	on tick:lose 80 BauMaterial
	on earn:yield 1 Erfahrung
	
//7
	   
*GrosserKaefer|GrosseKaefer
    name:GroßerKäfer|GroßeKäfer
    desc:So groß!<//><b>Effect:</b><.>Produziert <b>6506</b> Insekt pro Sekunde.<//><.> Produktion: <b>[GrosserKaefer*6506]</b> /Ips <//><.> Verbrauch: <b>300</b> Baumaterial pro Sekunde <//><.> Gesamter Vb: <b>[GrosserKaefer*300]</b>/Bps
    icon:icons[0,6]
    cost:28000000 Insekten,14000000 Larven,7000000 BauMaterial
    on tick:yield 6506 Insekten
    req:28000000 Insekten:earned and UpgIGrosserBug
  	on tick:lose 300 BauMaterial
	on earn:yield 1 Erfahrung
	
//8
	   
*Schmetterling|Schmetterlinge
    name:Schmetterling|Schmetterlinge
    desc:Bunte Schmetterlinge<//><b><.></b> Produziert <b>36698</b> Insekt pro Sekunde.<//><.> Produktion: <b>[Schmetterling*36698]</b> /Ips <//><.> Verbrauch: <b>1201</b> Baumaterial pro Sekunde <//><.> Gesamter Vb: <b>[Schmetterling*1201]</b>/Bps
    icon:icons[0,7]
    cost:420000000 Insekten,210000000 Larven,105000000 BauMaterial
    on tick:yield 36698 Insekten
    req:420000000 Insekten:earned and UpgISchmetterl
  	on tick:lose 1201 BauMaterial
	on earn:yield 1 Erfahrung
	
//9
	   
*Schabe|Schaben
    name:Schabe|Schaben
    desc:So flach sie sind!<//><b><.></b> Produziert <b>216851</b> Insekt pro Sekunde.<//><.> Produktion: <b>[Schabe*216851]</b> /Ips <//><.> Verbrauch: <b>10000</b> Baumaterial pro Sekunde <//><.> Gesamter Vb: <b>[Schabe*10000]</b>/Bps
    icon:icons[0,8]
    cost:6490909091 Insekten,3245454545 Larven,1622727273 BauBaterial
    on tick:yield 216851 Insekten
    req:6490909091 Insekten:earned and UpgISchabe
 	on tick:lose 10000 BauMaterial
	on earn:yield 1 Erfahrung
	
//10
	   
*Skorpion|Skorpione
    name:Skorpion|Skorpione
    desc:Aus der heißen Wüste er kommt!<//><b><.></b> Produziert <b>1322791</b> Insekt pro Sekunde.<//><.> Produktion: <b>[Skorpion*1322791]</b> /Ips <//><.> Verbrauch: <b>50000</b> Baumaterial pro Sekunde <//><.> Gesamter Vb: <b>[Skorpion*50000]</b>/Bps
    icon:icons[0,9]
    cost:95454545455 Insekten,47727272727 Larven,23863636364 Baumaterial
    on tick:yield 1322791 Insekten
    req:95454545455 Insekten:earned and UpgISkorion
	on tick:lose 50000 BauMaterial
	on earn:yield 1 Erfahrung
	
//11
	   
*Moskito|Moskitos
    name:Mücke|Mücken
    desc:Sie bringen so viel Blut!<//><b><.></b> Produziert <b>8267447</b> Insekt pro Sekunde.<//><.> Produktion: <b>[Moskito*8267447]</b> /Ips <//><.> Verbrauch: <b>300000</b> Baumaterial pro Sekunde <//><.> Gesamter Vb: <b>[Moskito*300000]</b>/Bps
    icon:icons[0,10]
    cost:1272727272727 Insekten,636363636364 Larven,318181818182 BauMaterial
    on tick:yield 8267447 Insekten
    req:1272727272727 Insekten:earned and UpgIMoskito
	on tick:lose 300000 BauMaterial
	on earn:yield 1 Erfahrung
		
//12
	   
*Willi|Willis
    name:Willi|Willis
    desc:Er war immer ein kluger Grashüpfer!<//><b><.></b> Produziert <b>53738404</b> Insekt pro Sekunde.<//><.> Produktion: <b>[Willi*53738404]</b> /Ips <//><.> Verbrauch: <b>2147929</b> Baumaterial pro Sekunde <//><.> Gesamter Vb: <b>[Willi*2147929]</b>/Bps
    icon:icons[0,11]
    cost:17818181818182 Insekten,8909090909091 Larven,4454545454545 BauMaterial
    on tick:yield 53738404 Insekten
    req:17818181818182 Insekten:earned and UpgIWilli
	on tick:lose 2147929 BauMaterial
	on earn:yield 1 Erfahrung
	
//13
	   
*Libelle|Libellen
    name:Libelle|Libellen<//><b><.></b> Produziert <b>355500213</b> Insekt pro Sekunde.<//><.> Produktion: <b>[Libelle*355500213]</b> /Ips <//><.> Verbrauch: <b>12887574</b> Baumaterial pro Sekunde <//><.> Gesamter Vb: <b>[Libelle*12887574]</b>/Bps
    desc:Brumm Brumm!
    icon:icons[0,12]
    cost:216363636363636 Insekten,108181818181818 Larven,54090909090909 BauMaterial
    on tick:yield 355500213 Insekten
    req:216363636363636 Insekten:earned and UpgILibelle
	on tick:lose 12887574 BauMaterial
	on earn:yield 1 Erfahrung
	
//14
	   
*Gluehwurm|Gluehwuermchen
    name:Glühwurm|Glühwürmchen
    desc:Möge es dir ein Licht sein an dunklen Orten, wenn alle anderen Lichter ausgehen.<//><b><.></b> Produziert <b>2397559574</b> Insekt pro Sekunde.<//><.> Produktion: <b>[Gluehwurm*2397559574]</b> /Ips <//><.> Verbrauch: <b>85256259</b> Baumaterial pro Sekunde <//><.> Gesamter Vb: <b>[Gluehwurm*85256259]</b>/Bps
    icon:icons[0,13]
    cost:2672727272727270 Insekten,1336363636363640 Larven,668181818181818 BauMaterial
    on tick:yield 2397559574 Insekten
    req:2672727272727270 Insekten:earned and UpgIGluehwurm
	on tick:lose 85256259 BauMaterial
	on earn:yield 1 Erfahrung
	
//15
	   
*Mistroller
    name:Mistroller
    desc:Er macht aus Mist Leben!<//><b><.></b> Produziert <b>17361638298</b> Insekt pro Sekunde.<//><.> Produktion: <b>[Mistroller*17361638298]</b> /Ips <//><.> Verbrauch: <b>574984069</b> Baumaterial pro Sekunde <//><.> Gesamter Vb: <b>[Mistroller*574984069]</b>/Bps
    icon:icons[0,14]
    cost:33090909090909100 Insekten,16545454545454500 Larven,8272727272727270 BauMaterial
    on tick:yield 17361638298 Insekten
    req:33090909090909100 Insekten:earned and UpgIMistroller
	on tick:lose 574984069 BauMaterial
	on earn:yield 1 Erfahrung
	
//16
	   
*Nachtfalter
    name:Nachtfalter
    desc:Er sucht das Licht!<//><b><.></b> Produziert <b>124011702128</b> Insekt pro Sekunde.<//><.> Produktion: <b>[Nachtfalter*124011702128]</b> /Ips <//><.> Verbrauch: <b>4163677742</b> Baumaterial pro Sekunde <//><.> Gesamter Vb: <b>[Nachtfalter*4163677742]</b>/Bps
    icon:icons[0,15]
    cost:394545454545455000 Insekten,197272727272727000 Larven,98636363636363700 BauMaterial
    on tick:yield 124011702128 Insekten
    req:394545454545455000 Insekten:earned and UpgINachtfalter
	on tick:lose 4163677742 BauMaterial
	on earn:yield 1 Erfahrung
	


// Baumaterial Gebäude ----------------------------------------------------

 
 //1 
 
*Gras
    name:Gras
    desc:Saftiges grünes Gras, gut um den Bau zu polstern.<//><b><.></b> Produziert <b>0.1</b> BauMaterial pro Sekunde.<//><.> Produktion: <b>[Gras*0.1]</b> /Bps
    icon:icons[2,0]
    cost:13 BauMaterial
    on tick:yield 0.1 BauMaterial
    req:1 BauMaterial:earned
	on earn:yield 0.1 Erfahrung
 //2
 
*Ast|Aeste
    name:Ast|Äste
    desc:Gutes stabiles BauMaterial.<//><b><.></b> Produziert <b>1</b> BauMaterial pro Sekunde.<//><.> Produktion: <b>[Ast*1]</b> /Bps
    icon:icons[2,1]
    cost:187 BauMaterial
    on tick:yield 1 BauMaterial
    req:121 BauMaterial:earned
	on earn:yield 0.1 Erfahrung
 //3
 
*Wurzel|Wurzeln
    name:Wurzel|Wurzeln
    desc:Hier gibt es viel BauMaterial zu holen!<//><b><.></b> Produziert <b>6</b> BauMaterial pro Sekunde.<//><.> Produktion: <b>[Wurzel*6]</b> /Bps
    icon:icons[2,2]
    cost:953 BauMaterial
    on tick:yield 6 BauMaterial
    req:943 BauMaterial:earned
	on earn:yield 1 Erfahrung
 //4
 
*Stein|Steine
    name:Stein|Steine
    desc:Kleine, feine, deine!<//><b><.></b> Produziert <b>36</b> BauMaterial pro Sekunde.<//><.> Produktion: <b>[Stein*36]</b> /Bps
    icon:icons[2,3]
    cost:10400 BauMaterial
    on tick:yield 36 BauMaterial
    req:9191 BauMaterial:earned
	on earn:yield 1 Erfahrung
 //5
 
*Dreck
    name:Dreck
    desc:Ein bißchen Dreck muß sein.<//><b><.></b> Produziert <b>180</b> BauMaterial pro Sekunde.<//><.> Produktion: <b>[Dreck*180]</b> /Bps
    icon:icons[2,4]
    cost:112667 BauMaterial
    on tick:yield 180 BauMaterial
    req:90000 BauMaterial:earned
	on earn:yield 1 Erfahrung
 //6
 
 *AltesBuch|AlteBuecher
	name:AltesBuch|AlteBücher
	desc:Watership Down<//><b><.></b> Produziert <b>969</b> BauMaterial pro Sekunde.<//><.> Produktion: <b>[AltesBuch*969]</b> /Bps
	icon:icons[2,5]
	cost:1213333 BauMaterial
	on tick:yield 969 BauMaterial
	req:969231 BauMaterial:earned
	on earn:yield 1 Erfahrung
	
 //7
 
 *Karnickel
	name:Karnickel
	desc:Es ist so flauschig und so produktiv!<//><b><.></b> Produziert <b>5400</b> BauMaterial pro Sekunde.<//><.> Produktion: <b>[Karnickel*5400]</b> /Bps
	icon:icons[2,6]
	cost:17333333 BauMaterial
	on tick:yield 5400 BauMaterial
	req:13846154 BauMaterial:earned
	on earn:yield 1 Erfahrung
	
 //8
 
 *Sonnenblume|Sonnenblumen
	name:Sonnenblume|Sonnenblumen
	desc:Sonnenblumenfasern sind schwer beliebt!<//><b><.></b> Produziert <b>30462</b> BauMaterial pro Sekunde.<//><.> Produktion: <b>[Sonnenblume*30462]</b> /Bps
	icon:icons[2,7]
	cost:286000000 BauMaterial
	on tick:yield 30462 BauMaterial
	req:228461538 BauMaterial:earned
	on earn:yield 1 Erfahrung
	
 	
 //9
 
 *Fred|Freds
	name:Fred der Maulwurf
	desc:Fred buddelt den ganzen Tag!<//><b><.></b> Produziert <b>167538</b> BauMaterial pro Sekunde.<//><.> Produktion: <b>[Fred*167538]</b> /Bps
	icon:icons[2,8]
	cost:4420000000 BauMaterial
	on tick:yield 167538 BauMaterial
	req:3286331361 BauMaterial:earned
	on earn:yield 1 Erfahrung
	
 	
 //10
 
 *Blumenbusch|Blumenbuesche
	name:Blumenbusch|Blumenbüsche
	desc:Ein Busch der viele Arten von BauMaterial produziert!<//><b><.></b> Produziert <b>1031006</b> BauMaterial pro Sekunde.<//><.> Produktion: <b>[Blumenbusch*1031006]</b> /Bps
	icon:icons[2,9]
	cost:65000000000 BauMaterial
	on tick:yield 1031006 BauMaterial
	req:48328402367 BauMaterial:earned
	on earn:yield 1 Erfahrung
	
 //11
 
 *Wollmaus|Wollmaeuse
	name:Wollmaus|Wollmäuse
	desc:Endlich hat sie einen Zweck zu erfüllen!<//><b><.></b> Produziert <b>6443787</b> BauMaterial pro Sekunde.<//><.> Produktion: <b>[Wollmaus*6443787]</b> /Bps
	icon:icons[2,10]
	cost:866666666667 BauMaterial
	on tick:yield 6443787 BauMaterial
	req:644378698225 BauMaterial:earned	
	on earn:yield 1 Erfahrung
	 	
 //12
 
 *VogelNest|VogelNester
	name:VogelNest|VogelNester
	desc:Ein unendlicher Vorrat an Baumaterial lagert hier!<//><b><.></b> Produziert <b>38662722</b> BauMaterial pro Sekunde.<//><.> Produktion: <b>[VogelNest*38662722]</b> /Bps
	icon:icons[2,11]
	cost:12133333333333 BauMaterial
	on tick:yield 38662722 BauMaterial
	req:8327355484752 BauMaterial:earned
	on earn:yield 1 Erfahrung
	
 //13
 
 *HolzStapel
	name:HolzStapel
	desc:Gibt es einen besseren Weg BauMaterial zu lagern als es zu stapeln?<//><b><.></b> Produziert <b>255768776</b> BauMaterial pro Sekunde.<//><.> Produktion: <b>[HolzStapel*255768776]</b> /Bps
	icon:icons[2,12]
	cost:147333333333333 BauMaterial
	on tick:yield 255768776 BauMaterial
	req:101117888029131 BauMaterial:earned
	on earn:yield 1 Erfahrung
	 	
 //14
 
 *HerbstLaub
	name:HerbstLaub
	desc:Es ist bunt und raschelt, damit baut Ameise gerne!<//><b><.></b> Produziert <b>1724952208</b> BauMaterial pro Sekunde.<//><.> Produktion: <b>[HerbstLaub*1724952208]</b> /Bps
	icon:icons[2,13]
	cost:1820000000000000 BauMaterial
	on tick:yield 1724952208 BauMaterial
	req:1249103322712790 BauMaterial:earned
	on earn:yield 1 Erfahrung
	 	
 //15
 
 *EuleFrieda|EulenFrieda
	name:EuleFrieda|EulenFrieda
	desc:Diese Eule ist in der Mauser und liefert uns so viel weiches BauMaterial!<//><b><.></b> Produziert <b>12491033227</b> BauMaterial pro Sekunde.<//><.> Produktion: <b>[EuleFrieda*12491033227]</b> /Bps
	icon:icons[2,14]
	cost:22533333333333300 BauMaterial
	on tick:yield 12491033227 BauMaterial
	req:15465088757396500 BauMaterial:earned
	on earn:yield 1 Erfahrung
	
 //16
 
 *CreepyTree|CreepyTrees
	name:CreepyTree|CreepyTrees
	desc:Asdpkl ntt dffie djftgtv ojsle Cndu!<//><b><.></b> Produziert <b>89221665908</b> BauMaterial pro Sekunde.<//><.> Produktion: <b>[CreepyTree*89221665908]</b> /Bps
	icon:icons[2,15]
	cost:268666666666667000 BauMaterial
	on tick:yield 89221665908 BauMaterial
	req:184391442876650000 BauMaterial:earned
	on earn:yield 1 Erfahrung
	 



*important
	on tick:show :Upgrades
	on tick:hide :Upgrades:owned
	on tick:show tag:prestige
	always hidden


Upgrades

//Muster für limit
	*UgLimitOOO
        tag:limitupgrades
        name:LimitOOO
        desc:<.> Limit von 100
        icon:icons[4,3] icons[4,1]
        cost:10 InsektenPanzer
        req:1 Insekten


	*TEMPLATE
		tag:upgrades
		on tick:if (have this) hide this
		on earn:hide this
		on earn:yield 1 upgradesII
		on click:anim glow
		class:noBackground
	
	
	

// Larven Multi mit Erfahrung

*UgRLErfahrung1
		name:Brüter
		desc:<.> Erhöht die Produktion von Larven um <b>3</b> %.
		icon:icons[6,4]
		cost:14000 Erfahrung
		passive:multiply yield of Larven by 1.03
		req:12000 Erfahrung:earned
*UgRLErfahrung2
		name:Schlüpfer
		desc:<.> Erhöht die Produktion von Larven um <b>3</b> %.
		icon:icons[6,4]
		cost:55000 Erfahrung
		passive:multiply yield of Larven by 1.03
		req:40000 Erfahrung and UgRLErfahrung1
*UgRLErfahrung3
		name:Wachser
		desc:<.> Erhöht die Produktion von Larven um <b>3</b> %.
		icon:icons[6,4]
		cost:125000 Erfahrung
		passive:multiply yield of Larven by 1.03
		req:120000 Erfahrung and UgRLErfahrung2
*UgRLErfahrung4
		name:Säher
		desc:<.> Erhöht die Produktion von Larven um <b>3</b> %.
		icon:icons[6,4]
		cost:220000 Erfahrung
		passive:multiply yield of Larven by 1.03
		req:200000 Erfahrung and UgRLErfahrung3
*UgRLErfahrung5
		name:Pfleger
		desc:<.> Erhöht die Produktion von Larven um <b>3</b> %.
		icon:icons[6,4]
		cost:340000 Erfahrung
		passive:multiply yield of Larven by 1.03
		req:320000 Erfahrung and UgRLErfahrung4
*UgRLErfahrung6
		name:Amme
		desc:<.> Erhöht die Produktion von Larven um <b>3</b> %.
		icon:icons[6,4]
		cost:500000 Erfahrung
		passive:multiply yield of Larven by 1.03
		req:480000 Erfahrung and UgRLErfahrung5
*UgRLErfahrung7
		name:Hebamme
		desc:<.> Erhöht die Produktion von Larven um <b>3</b> %.
		icon:icons[6,4]
		cost:660000 Erfahrung
		passive:multiply yield of Larven by 1.03
		req:640000 Erfahrung and UgRLErfahrung6
*UgRLErfahrung8
		name:Geburtshelfer
		desc:<.> Erhöht die Produktion von Larven um <b>3</b> %.
		icon:icons[6,4]
		cost:880000 Erfahrung
		passive:multiply yield of Larven by 1.03
		req:840000 Erfahrung and UgRLErfahrung7
*UgRLErfahrung9
		name:Entbindungshelfer
		desc:<.> Erhöht die Produktion von Larven um <b>3</b> %.
		icon:icons[6,4]
		cost:1100000 Erfahrung
		passive:multiply yield of Larven by 1.03
		req:1000000 Erfahrung and UgRLErfahrung8
*UgRLErfahrung10
		name:Schlüpfstation
		desc:<.> Erhöht die Produktion von Larven um <b>3</b> %.
		icon:icons[6,4]
		cost:1370000 Erfahrung
		passive:multiply yield of Larven by 1.03
		req:1110000 Erfahrung and UgRLErfahrung9
		
		

// Insekten Multi mit Erfahrung

*UgRIErfahrung1
		name:Insektenzüchter
		desc:<.> Erhöht die Produktion von Insekten um <b>3</b> %.
		icon:icons[6,5]
		cost:14000 Erfahrung
		passive:multiply yield of Insekten by 1.03
		req:12000 Erfahrung:earned
*UgRIErfahrung2
		name:Insektenpfleger
		desc:<.> Erhöht die Produktion von Insekten um <b>3</b> %.
		icon:icons[6,5]
		cost:55000 Erfahrung
		passive:multiply yield of Insekten by 1.03
		req:40000 Erfahrung and UgRIErfahrung1
*UgRIErfahrung3
		name:Insektenforscher
		desc:<.> Erhöht die Produktion von Insekten um <b>3</b> %.
		icon:icons[6,5]
		cost:125000 Erfahrung
		passive:multiply yield of Insekten by 1.03
		req:120000 Erfahrung and UgRIErfahrung2
*UgRIErfahrung4
		name:Insektenfinder
		desc:<.> Erhöht die Produktion von Insekten um <b>3</b> %.
		icon:icons[6,5]
		cost:220000 Erfahrung
		passive:multiply yield of Insekten by 1.03
		req:200000 Erfahrung and UgRIErfahrung3
*UgRIErfahrung5
		name:Insektenberater
		desc:<.> Erhöht die Produktion von Insekten um <b>3</b> %.
		icon:icons[6,5]
		cost:340000 Erfahrung
		passive:multiply yield of Insekten by 1.03
		req:320000 Erfahrung and UgRIErfahrung4
*UgRIErfahrung6
		name:Insektenentomologe
		desc:<.> Erhöht die Produktion von Insekten um <b>3</b> %.
		icon:icons[6,5]
		cost:500000 Erfahrung
		passive:multiply yield of Insekten by 1.03
		req:480000 Erfahrung and UgRIErfahrung5
*UgRIErfahrung7
		name:Insektenprofessor
		desc:<.> Erhöht die Produktion von Insekten um <b>3</b> %.
		icon:icons[6,5]
		cost:660000 Erfahrung
		passive:multiply yield of Insekten by 1.03
		req:640000 Erfahrung and UgRIErfahrung6
*UgRIErfahrung8
		name:Insektenlehrer
		desc:<.> Erhöht die Produktion von Insekten um <b>3</b> %.
		icon:icons[6,5]
		cost:880000 Erfahrung
		passive:multiply yield of Insekten by 1.03
		req:840000 Erfahrung and UgRIErfahrung7
*UgRIErfahrung9
		name:Insektengelehrter
		desc:<.> Erhöht die Produktion von Insekten um <b>3</b> %.
		icon:icons[6,5]
		cost:1100000 Erfahrung
		passive:multiply yield of Insekten by 1.03
		req:1000000 Erfahrung and UgRIErfahrung8
*UgRIErfahrung10
		name:Insektenwissenschaftler
		desc:<.> Erhöht die Produktion von Insekten um <b>3</b> %.
		icon:icons[6,5]
		cost:1370000 Erfahrung
		passive:multiply yield of Insekten by 1.03
		req:1110000 Erfahrung and UgRIErfahrung9
		
		

// BauMaterial Multi mit Erfahrung

*UgRBErfahrung1
		name:Straßenbauer
		desc:<.> Erhöht die Produktion von BauMaterial um <b>3</b> %.
		icon:icons[6,6]
		cost:14000 Erfahrung
		passive:multiply yield of BauMaterial by 1.03
		req:12000 Erfahrung:earned
*UgRBErfahrung2
		name:Baustoffprüfer
		desc:<.> Erhöht die Produktion von BauMaterial um <b>3</b> %.
		icon:icons[6,6]
		cost:55000 Erfahrung
		passive:multiply yield of BauMaterial by 1.03
		req:40000 Erfahrung and UgRBErfahrung1
*UgRBErfahrung3
		name:Bauzeichner
		desc:<.> Erhöht die Produktion von BauMaterial um <b>3</b> %.
		icon:icons[6,6]
		cost:125000 Erfahrung
		passive:multiply yield of BauMaterial by 1.03
		req:120000 Erfahrung and UgRBErfahrung2
*UgRBErfahrung4
		name:Kanalbauer
		desc:<.> Erhöht die Produktion von BauMaterial um <b>3</b> %.
		icon:icons[6,6]
		cost:220000 Erfahrung
		passive:multiply yield of BauMaterial by 1.03
		req:200000 Erfahrung and UgRBErfahrung3
*UgRBErfahrung5
		name:Maurer
		desc:<.> Erhöht die Produktion von BauMaterial um <b>3</b> %.
		icon:icons[6,6]
		cost:340000 Erfahrung
		passive:multiply yield of BauMaterial by 1.03
		req:320000 Erfahrung and UgRBErfahrung4
*UgRBErfahrung6
		name:Drechsler
		desc:<.> Erhöht die Produktion von BauMaterial um <b>3</b> %.
		icon:icons[6,6]
		cost:500000 Erfahrung
		passive:multiply yield of BauMaterial by 1.03
		req:480000 Erfahrung and UgRBErfahrung5
*UgRBErfahrung7
		name:Flechtwerkgestalter
		desc:<.> Erhöht die Produktion von BauMaterial um <b>3</b> %.
		icon:icons[6,6]
		cost:660000 Erfahrung
		passive:multiply yield of BauMaterial by 1.03
		req:640000 Erfahrung and UgRBErfahrung6
*UgRBErfahrung8
		name:Tischler
		desc:<.> Erhöht die Produktion von BauMaterial um <b>3</b> %.
		icon:icons[6,6]
		cost:880000 Erfahrung
		passive:multiply yield of BauMaterial by 1.03
		req:840000 Erfahrung and UgRBErfahrung7
*UgRBErfahrung9
		name:Zimmerer
		desc:<.> Erhöht die Produktion von BauMaterial um <b>3</b> %.
		icon:icons[6,6]
		cost:1100000 Erfahrung
		passive:multiply yield of BauMaterial by 1.03
		req:1000000 Erfahrung and UgRBErfahrung8
*UgRBErfahrung10
		name:Steinmetz
		desc:<.> Erhöht die Produktion von BauMaterial um <b>3</b> %.
		icon:icons[6,6]
		cost:1370000 Erfahrung
		passive:multiply yield of BauMaterial by 1.03
		req:1110000 Erfahrung and UgRBErfahrung9
		
		
		
		
		
		
		
				
		
		
		
		
				
		
		
		
		
			
	
	
	

// Sammler Upgrades -----------------------------------




	
//1 	
	
*UgBIPSammlerA1
		name:SammlerAmeisenPanzer I
		desc:<.> Erhöht die Produktion der SammlerAmeisen um <b>75</b> %.
		icon:icons[4,3] icons[4,1]
		cost:10 InsektenPanzer
		passive:multiply yield of SammlerAmeise by 1.75
		req:1 InsektenPanzer
		class:noBackground

*UgBIPSammlerA2
		name:SammlerAmeisenPanzer II
		desc:<.> Erhöht die Produktion der SammlerAmeisen um <b>75</b> %.
		icon:icons[4,3] icons[4,1]
		cost:100 InsektenPanzer
		passive:multiply yield of SammlerAmeise by 1.75
		req:UgBIPSammlerA1
		class:noBackground
	

*UgBIPSammlerA3
		name:SammlerAmeisenPanzer III
		desc:<.> Erhöht die Produktion der SammlerAmeisen um <b>75</b> %.
		icon:icons[4,3] icons[4,1]
		cost:10000 InsektenPanzer
		passive:multiply yield of SammlerAmeise by 1.75
		req:UgBIPSammlerA2
		class:noBackground

*UgBIPSammlerA4
		name:SammlerAmeisenPanzer IV
		desc:<.> Erhöht die Produktion der SammlerAmeisen um <b>75</b> %.
		icon:icons[4,3] icons[4,1]
		cost:100000 InsektenPanzer
		passive:multiply yield of SammlerAmeise by 1.75
		req:UgBIPSammlerA3
		class:noBackground

*UgBIPSammlerA5
		name:SammlerAmeisenPanzer V
		desc:<.> Erhöht die Produktion der SammlerAmeisen um <b>75</b> %.
		icon:icons[4,3] icons[4,1]
		cost:1000000 InsektenPanzer
		passive:multiply yield of SammlerAmeise by 1.75
		req:UgBIPSammlerA4
		class:noBackground

*UgBIPSammlerA6
		name:SammlerAmeisenPanzer VI
		desc:<.> Erhöht die Produktion der SammlerAmeisen um <b>75</b> %.
		icon:icons[4,3] icons[4,1]
		cost:10000000 InsektenPanzer
		passive:multiply yield of SammlerAmeise by 1.75
		req:UgBIPSammlerA5
		class:noBackground

*UgBIPSammlerA7
		name:SammlerAmeisenPanzer VII
		desc:<.> Erhöht die Produktion der SammlerAmeisen um <b>75</b> %.
		icon:icons[4,3] icons[4,1]
		cost:100000000 InsektenPanzer
		passive:multiply yield of SammlerAmeise by 1.75
		req:UgBIPSammlerA6
		class:noBackground

*UgBIPSammlerA8
		name:SammlerAmeisenPanzer VIII
		desc:<.> Erhöht die Produktion der SammlerAmeisen um <b>75</b> %.
		icon:icons[4,3] icons[4,1]
		cost:1000000000 InsektenPanzer
		passive:multiply yield of SammlerAmeise by 1.75
		req:UgBIPSammlerA7
		class:noBackground

*UgBIPSammlerA9
		name:SammlerAmeisenPanzer IX
		desc:<.> Erhöht die Produktion der SammlerAmeisen um <b>75</b> %.
		icon:icons[4,3] icons[4,1]
		cost:10000000000 InsektenPanzer
		passive:multiply yield of SammlerAmeise by 1.75
		req:UgBIPSammlerA8
		class:noBackground

*UgBIPSammlerA10
		name:SammlerAmeisenPanzer X
		desc:<.> Erhöht die Produktion der SammlerAmeisen um <b>75</b> %.
		icon:icons[4,3] icons[4,1]
		cost:100000000000 InsektenPanzer
		passive:multiply yield of SammlerAmeise by 1.75
		req:UgBIPSammlerA9
		class:noBackground
		
*UgBIPSammlerA11
		name:SammlerAmeisenPanzer XI
		desc:<.> Erhöht die Produktion der SammlerAmeisen um <b>75</b> %.
		icon:icons[4,3] icons[4,1]
		cost:10000000000000 InsektenPanzer
		passive:multiply yield of SammlerAmeise by 1.75
		req:UgBIPSammlerA10
		class:noBackground
		
*UgBIPSammlerA12
		name:SammlerAmeisenPanzer XII
		desc:<.> Erhöht die Produktion der SammlerAmeisen um <b>75</b> %.
		icon:icons[4,3] icons[4,1]
		cost:1000000000000000 InsektenPanzer
		passive:multiply yield of SammlerAmeise by 1.75
		req:UgBIPSammlerA11
		class:noBackground
		
*UgBIPSammlerA13
		name:SammlerAmeisenPanzer XIII
		desc:<.> Erhöht die Produktion der SammlerAmeisen um <b>75</b> %.
		icon:icons[4,3] icons[4,1]
		cost:100000000000000000 InsektenPanzer
		passive:multiply yield of SammlerAmeise by 1.75
		req:UgBIPSammlerA12
		class:noBackground
		
*UgBIPSammlerA14
		name:SammlerAmeisenPanzer XIV
		desc:<.> Erhöht die Produktion der SammlerAmeisen um <b>75</b> %.
		icon:icons[4,3] icons[4,1]
		cost:10000000000000000000 InsektenPanzer
		passive:multiply yield of SammlerAmeise by 1.75
		req:UgBIPSammlerA13
		class:noBackground
		
*UgBIPSammlerA15
		name:SammlerAmeisenPanzer XV
		desc:<.> Erhöht die Produktion der SammlerAmeisen um <b>75</b> %.
		icon:icons[4,3] icons[4,1]
		cost:1000000000000000000000 InsektenPanzer
		passive:multiply yield of SammlerAmeise by 1.75
		req:UgBIPSammlerA14
		class:noBackground		

	
	
	
	
	

//Larvenupgrades ------------------------------
	

	


		
		
		

*UgRLMandala1
		name:Ein buntes Mandala
		desc:<.>Etwas Kunst belebt die Larven Produktion! <//><.> Erhöht die Produktion von Larven um <b>1</b> %.
		icon:iconsa[8,0]
		cost:999999 Larven
		passive:multiply yield of Larven by 1.01
		req:50000 Larven:earned
*UgRLMandala2
		name:Schwarzes Mandala
		desc:<.> Erhöht die Produktion von Larven um <b>1</b> %.
		icon:iconsa[8,1]
		cost:5000000 Larven
		passive:multiply yield of Larven by 1.01
		req:250000 Larven:earned and UgRLMandala1
*UgRLMandala3
		name:Türkises Mandala
		desc:<.> Erhöht die Produktion von Larven um <b>1</b> %.
		icon:iconsa[8,2]
		cost:10000000 Larven
		passive:multiply yield of Larven by 1.01
		req:500000 Larven:earned and UgRLMandala2
*UgRLMandala4
		name:Hellblaues Mandala
		desc:<.> Erhöht die Produktion von Larven um <b>1</b> %.
		icon:iconsa[8,3]
		cost:50000000 Larven
		passive:multiply yield of Larven by 1.01
		req:2500000 Larven:earned and UgRLMandala3
*UgRLMandala5
		name:Buntes Mandala
		desc:<.> Erhöht die Produktion von Larven um <b>1</b> %.
		icon:iconsa[8,4]
		cost:100000000 Larven
		passive:multiply yield of Larven by 1.01
		req:5000000 Larven:earned and UgRLMandala4
*UgRLMandala6
		name:Feines Mandala
		desc:<.> Erhöht die Produktion von Larven um <b>1</b> %.
		icon:iconsa[8,5]
		cost:500000000 Larven
		passive:multiply yield of Larven by 1.01
		req:25000000 Larven:earned and UgRLMandala5
*UgRLMandala7
		name:Rundes Mandala
		desc:<.> Erhöht die Produktion von Larven um <b>1</b> %.
		icon:iconsa[8,6]
		cost:1000000000 Larven
		passive:multiply yield of Larven by 1.01
		req:50000000 Larven:earned and UgRLMandala6
*UgRLMandala8
		name:Braunes Mandala
		desc:<.> Erhöht die Produktion von Larven um <b>1</b> %.
		icon:iconsa[8,7]
		cost:5000000000 Larven
		passive:multiply yield of Larven by 1.01
		req:250000000 Larven:earned and UgRLMandala7
*UgRLMandala9
		name:Plattes Mandala
		desc:<.> Erhöht die Produktion von Larven um <b>1</b> %.
		icon:iconsa[8,8]
		cost:10000000000 Larven
		passive:multiply yield of Larven by 1.01
		req:500000000 Larven:earned and UgRLMandala8
*UgRLMandala10
		name:Rahmen Mandala
		desc:<.> Erhöht die Produktion von Larven um <b>1</b> %.
		icon:iconsa[8,9]
		cost:50000000000 Larven
		passive:multiply yield of Larven by 1.01
		req:2500000000 Larven:earned and UgRLMandala9
*UgRLMandala11
		name:Schönes Mandala
		desc:<.> Erhöht die Produktion von Larven um <b>1</b> %.
		icon:iconsa[8,10]
		cost:100000000000 Larven
		passive:multiply yield of Larven by 1.01
		req:5000000000 Larven:earned and UgRLMandala10
*UgRLMandala12
		name:Dunkles Mandala
		desc:<.> Erhöht die Produktion von Larven um <b>1</b> %.
		icon:iconsa[8,11]
		cost:500000000000 Larven
		passive:multiply yield of Larven by 1.01
		req:25000000000 Larven:earned and UgRLMandala11
*UgRLMandala13
		name:Rotes Mandala
		desc:<.> Erhöht die Produktion von Larven um <b>1</b> %.
		icon:iconsa[8,12]
		cost:1000000000000 Larven
		passive:multiply yield of Larven by 1.01
		req:50000000000 Larven:earned and UgRLMandala12
*UgRLMandala14
		name:Einfarbiges Mandala
		desc:<.> Erhöht die Produktion von Larven um <b>1</b> %.
		icon:iconsa[8,13]
		cost:5000000000000 Larven
		passive:multiply yield of Larven by 1.01
		req:250000000000 Larven:earned and UgRLMandala13
*UgRLMandala15
		name:Regenbogen Mandala
		desc:<.> Erhöht die Produktion von Larven um <b>1</b> %.
		icon:iconsa[8,14]
		cost:10000000000000 Larven
		passive:multiply yield of Larven by 1.01
		req:500000000000 Larven:earned and UgRLMandala14
*UgRLMandala16
		name:Abstraktes Mandala
		desc:<.> Erhöht die Produktion von Larven um <b>1</b> %.
		icon:iconsa[8,15]
		cost:50000000000000 Larven
		passive:multiply yield of Larven by 1.01
		req:5000000000000 Larven:earned and UgRLMandala15
*UgRLMandala17
		name:Originelles Mandala
		desc:<.> Erhöht die Produktion von Larven um <b>1</b> %.
		icon:iconsa[8,16]
		cost:100000000000000 Larven
		passive:multiply yield of Larven by 1.01
		req:25000000000000 Larven:earned and UgRLMandala16
*UgRLMandala18
		name:Altmodisches Mandala
		desc:<.> Erhöht die Produktion von Larven um <b>1</b> %.
		icon:iconsa[8,17]
		cost:500000000000000 Larven
		passive:multiply yield of Larven by 1.01
		req:50000000000000 Larven:earned and UgRLMandala17
*UgRLMandala19
		name:Modernes Mandala
		desc:<.> Erhöht die Produktion von Larven um <b>1</b> %.
		icon:iconsa[8,18]
		cost:1000000000000000 Larven
		passive:multiply yield of Larven by 1.01
		req:250000000000000 Larven:earned and UgRLMandala18
*UgRLMandala20
		name:Gelbes Mandala
		desc:<.> Erhöht die Produktion von Larven um <b>1</b> %.
		icon:iconsa[8,19]
		cost:5000000000000000 Larven
		passive:multiply yield of Larven by 1.01
		req:500000000000000 Larven:earned and UgRLMandala19
*UgRLMandala21
		name:Großes Mandala
		desc:<.> Erhöht die Produktion von Larven um <b>1</b> %.
		icon:iconsa[8,20]
		cost:10000000000000000 Larven
		passive:multiply yield of Larven by 1.01
		req:2500000000000000 Larven:earned and UgRLMandala20
		
			

		
		

*UgRLNudelK1
		name:Bandnudel
        desc:<.> Beim Klicken der Larve bekommst du <b>2</b> mal so viel!
		icon:iconsa[9,0]
		cost:999999 Larve
		passive:multiply yield of LarveButton by 2
		req:50000 Larve:earned
*UgRLNudelK2
		name:Davette
        desc:<.> Beim Klicken der Larve bekommst du <b>3</b> mal so viel!
		icon:iconsa[9,1]
		cost:5000000 Larve
		passive:multiply yield of LarveButton by 3
		req:250000 Larve:earned and UgRLNudelK1
*UgRLNudelK3
		name:Bucatini
        desc:<.> Beim Klicken der Larve bekommst du <b>3</b> mal so viel!
		icon:iconsa[9,2]
		cost:10000000 Larve
		passive:multiply yield of LarveButton by 3
		req:500000 Larve:earned and UgRLNudelK2
*UgRLNudelK4
		name:Cannelloni
        desc:<.> Beim Klicken der Larve bekommst du <b>3</b> mal so viel!
		icon:iconsa[9,3]
		cost:50000000 Larve
		passive:multiply yield of LarveButton by 3
		req:2500000 Larve:earned and UgRLNudelK3
*UgRLNudelK5
		name:Ditalini
		desc:<.> Beim Klicken der Larve bekommst du <b>3</b> mal so viel!
		icon:iconsa[9,4]
		cost:100000000 Larve
		passive:multiply yield of LarveButton by 3
		req:5000000 Larve:earned and UgRLNudelK4
*UgRLNudelK6
		name:Farfalle
		desc:<.> Beim Klicken der Larve bekommst du <b>3</b> mal so viel!
		icon:iconsa[9,5]
		cost:500000000 Larve
		passive:multiply yield of LarveButton by 3
		req:25000000 Larve:earned and UgRLNudelK5
*UgRLNudelK7
		name:Fettuccine
		desc:<.> Beim Klicken der Larve bekommst du <b>3</b> mal so viel!
		icon:iconsa[9,6]
		cost:1000000000 Larve
		passive:multiply yield of LarveButton by 3
		req:50000000 Larve:earned and UgRLNudelK6
*UgRLNudelK8
		name:Gnocchi
		desc:<.> Beim Klicken der Larve bekommst du <b>3</b> mal so viel!
		icon:iconsa[9,7]
		cost:5000000000 Larve
		passive:multiply yield of LarveButton by 3
		req:250000000 Larve:earned and UgRLNudelK7
*UgRLNudelK9
		name:Linguine
		desc:<.> Beim Klicken der Larve bekommst du <b>3</b> mal so viel!
		icon:iconsa[9,8]
		cost:10000000000 Larve
		passive:multiply yield of LarveButton by 3
		req:500000000 Larve:earned and UgRLNudelK8
*UgRLNudelK10
		name:Lumaconi
		desc:<.> Beim Klicken der Larve bekommst du <b>3</b> mal so viel!
		icon:iconsa[9,9]
		cost:50000000000 Larve
		passive:multiply yield of LarveButton by 3
		req:2500000000 Larve:earned and UgRLNudelK9
*UgRLNudelK11
		name:Makkaroni
		desc:<.> Beim Klicken der Larve bekommst du <b>3</b> mal so viel!
		icon:iconsa[9,10]
		cost:100000000000 Larve
		passive:multiply yield of LarveButton by 3
		req:5000000000 Larve:earned and UgRLNudelK10
*UgRLNudelK12
		name:Orecchiette
		desc:<.> Beim Klicken der Larve bekommst du <b>3</b> mal so viel!
		icon:iconsa[9,11]
		cost:500000000000 Larve
		passive:multiply yield of LarveButton by 3
		req:25000000000 Larve:earned and UgRLNudelK11
*UgRLNudelK13
		name:Pappardelle
		desc:<.> Beim Klicken der Larve bekommst du <b>3</b> mal so viel!
		icon:iconsa[9,12]
		cost:1000000000000 Larve
		passive:multiply yield of LarveButton by 3
		req:50000000000 Larve:earned and UgRLNudelK12
*UgRLNudelK14
		name:Penne lisce
		desc:<.> Beim Klicken der Larve bekommst du <b>3</b> mal so viel!
		icon:iconsa[9,13]
		cost:5000000000000 Larve
		passive:multiply yield of LarveButton by 3
		req:250000000000 Larve:earned and UgRLNudelK13
*UgRLNudelK15
		name:Penne Rigate
		desc:<.> Beim Klicken der Larve bekommst du <b>3</b> mal so viel!
		icon:iconsa[9,14]
		cost:10000000000000 Larve
		passive:multiply yield of LarveButton by 3
		req:250000000000 Larve:earned and UgRLNudelK14
*UgRLNudelK16
		name:Ravioli
		desc:<.> Beim Klicken der Larve bekommst du <b>3</b> mal so viel!
		icon:iconsa[9,15]
		cost:50000000000000 Larve
		passive:multiply yield of LarveButton by 3
		req:5000000000000 Larve:earned and UgRLNudelK15
*UgRLNudelK17
		name:Rigatoni
		desc:<.> Beim Klicken der Larve bekommst du <b>3</b> mal so viel!
		icon:iconsa[9,16]
		cost:100000000000000 Larve
		passive:multiply yield of LarveButton by 3
		req:25000000000000 Larve:earned and UgRLNudelK16
*UgRLNudelK18
		name:Spaghetti
		desc:<.> Beim Klicken der Larve bekommst du <b>3</b> mal so viel!
		icon:iconsa[9,17]
		cost:500000000000000 Larve
		passive:multiply yield of LarveButton by 3
		req:50000000000000 Larve:earned and UgRLNudelK17
*UgRLNudelK19
		name:Tagliatelle
		desc:<.> Beim Klicken der Larve bekommst du <b>3</b> mal so viel!
		icon:iconsa[9,18]
		cost:1000000000000000 Larve
		passive:multiply yield of LarveButton by 3
		req:250000000000000 Larve:earned and UgRLNudelK18
*UgRLNudelK20
		name:Tortellini
		desc:<.> Beim Klicken der Larve bekommst du <b>3</b> mal so viel!
		icon:iconsa[9,19]
		cost:5000000000000000 Larve
		passive:multiply yield of LarveButton by 3
		req:500000000000000 Larve:earned and UgRLNudelK19
*UgRLNudelK21
		name:Trenette
		desc:<.> Beim Klicken der Larve bekommst du <b>3</b> mal so viel!
		icon:iconsa[9,20]
		cost:10000000000000000 Larve
		passive:multiply yield of LarveButton by 3
		req:2500000000000000 Larve:earned and UgRLNudelK20
		


*UgRLMinecraftk1
        name:Schleimball
        desc:<.> Beim Klicken der Larve bekommst du <b>1</b> Larve mehr!
        icon:iconsa[10,0]
        cost:1000 Larve
        passive:increase yield of LarveButton by 1
        req:10 Larve:earned
*UgRLMinecraftk2
        name:Redstone
        desc:<.> Beim Klicken der Larve bekommst du <b>1</b> Larve mehr!
        icon:iconsa[10,1]
        cost:10000 Larve
        passive:increase yield of LarveButton by 1
        req:100 Larve:earned and UgRLMinecraftk1
*UgRLMinecraftk3
        name:Smaragd
        desc:<.> Beim Klicken der Larve bekommst du <b>1</b> Larve mehr!
        icon:iconsa[10,2]
        cost:100000 Larve
        passive:increase yield of LarveButton by 1
        req:1000 Larve:earned and UgRLMinecraftk2
*UgRLMinecraftk4
        name:Leder
        desc:<.> Beim Klicken der Larve bekommst du <b>1</b> Larve mehr!
        icon:iconsa[10,3]
        cost:1000000 Larve
        passive:increase yield of LarveButton by 1
        req:10000 Larve:earned and UgRLMinecraftk3
*UgRLMinecraftk5
        name:Goldbarren
        desc:<.> Beim Klicken der Larve bekommst du <b>1</b> Larve mehr!
        icon:iconsa[10,4]
        cost:10000000 Larve
        passive:increase yield of LarveButton by 1
        req:100000 Larve:earned and UgRLMinecraftk4
*UgRLMinecraftk6
        name:Diamant
        desc:<.> Beim Klicken der Larve bekommst du <b>1</b> Larve mehr!
        icon:iconsa[10,5]
        cost:100000000 Larve
        passive:increase yield of LarveButton by 1
        req:1000000 Larve:earned and UgRLMinecraftk5

				

		
*UgBLRaupe1
		name:Raupen Tango
		desc:<.> Erhöht die Produktion der Raupen um <b>75</b> %.
		icon:icons[1,0] icons[3,0]
		cost:1000 Larven,1 Territorien
		passive:multiply yield of Raupe by 1.75
		req:1000 Larven:earned

*UgBLRaupe2
		name:Raupenmarsch
		desc:<.> Erhöht die Produktion der Raupen um <b>75</b> %.
		icon:icons[1,0] icons[3,1]
		cost:10000 Larven,10 Territorien
		passive:multiply yield of Raupe by 1.75
		req:10000 Larven:earned and UgBLRaupe1
				
*UgBLRaupe3
		name:Raupenparty
		desc:<.> Erhöht die Produktion der Raupen um <b>75</b> %.
		icon:icons[1,0] icons[3,2]
		cost:1000000 Larven,100 Territorien
		passive:multiply yield of Raupe by 1.75
		req:1000000 Larven:earned and UgBLRaupe2

*UgBLRaupe4
		name:Raupenmusik
		desc:<.> Erhöht die Produktion der Raupen um <b>75</b> %.
		icon:icons[1,0] icons[3,3]
		cost:100000000 Larven,1000 Territorien
		passive:multiply yield of Raupe by 1.75
		req:100000000 Larven:earned and UgBLRaupe3
		
*UgBLRaupe5
		name:Raupastik
		desc:<.> Erhöht die Produktion der Raupen um <b>75</b> %.
		icon:icons[1,0] icons[3,4]
		cost:10000000000 Larven,10000 Territorien
		passive:multiply yield of Raupe by 1.75
		req:10000000000 Larven:earned and UgBLRaupe4
		
*UgBLRaupe6
		name:Raupenpuppe
		desc:<.> Erhöht die Produktion der Raupen um <b>75</b> %.
		icon:icons[1,0] icons[3,5]
		cost:1000000000000 Larven,100000 Territorien
		passive:multiply yield of Raupe by 1.75
		req:1000000000000 Larven:earned and UgBLRaupe5
		
*UgBLRaupe7
		name:Raupenmania
		desc:<.> Erhöht die Produktion der Raupen um <b>75</b> %.
		icon:icons[1,0] icons[3,6]
		cost:100000000000000 Larven,1000000 Territorien
		passive:multiply yield of Raupe by 1.75
		req:100000000000000 Larven:earned and UgBLRaupe6
		
*UgBLRaupe8
		name:Raupengesang
		desc:<.> Erhöht die Produktion der Raupen um <b>75</b> %.
		icon:icons[1,0] icons[3,7]
		cost:10000000000000000 Larven,10000000 Territorien
		passive:multiply yield of Raupe by 1.75
		req:10000000000000000 Larven:earned and UgBLRaupe7
		
*UgBLRaupe9
		name:Raupenlolli
		desc:<.> Erhöht die Produktion der Raupen um <b>75</b> %.
		icon:icons[1,0] icons[3,8]
		cost:1000000000000000000 Larven,100000000 Territorien
		passive:multiply yield of Raupe by 1.75
		req:1000000000000000000 Larven:earned and UgBLRaupe8
		
*UgBLRaupe10
		name:Raupensymphonie
		desc:<.> Erhöht die Produktion der Raupen um <b>75</b> %.
		icon:icons[1,0] icons[3,9]
		cost:100000000000000000000 Larven,1000000000 Territorien
		passive:multiply yield of Raupe by 1.75
		req:100000000000000000000 Larven:earned and UgBLRaupe9
		
*UgBLRaupe11
		name:Raupenklatschen
		desc:<.> Erhöht die Produktion der Raupen um <b>75</b> %.
		icon:icons[1,0] icons[3,10]
		cost:10000000000000000000000 Larven,10000000000 Territorien
		passive:multiply yield of Raupe by 1.75
		req:10000000000000000000000 Larven:earned and UgBLRaupe10
		
*UgBLRaupe12
		name:Raupenwetter
		desc:<.> Erhöht die Produktion der Raupen um <b>75</b> %.
		icon:icons[1,0] icons[3,11]
		cost:1000000000000000000000000 Larven,100000000000 Territorien
		passive:multiply yield of Raupe by 1.75
		req:1000000000000000000000000 Larven:earned and UgBLRaupe11
		
				

	
*UgBLRaupeF1
		name:Raupenpanzer
		desc:<.> Erhöht die Produktion der Raupen um <b>75</b> %.
		icon:icons[5,5] icons[1,0] icons[8,0]
		cost:10 Raupen
		passive:multiply yield of Raupe by 1.75
		req:10 Raupen
*UgBLRaupeF2
		name:HolzRaupe
		desc:<.> Erhöht die Produktion der Raupen um <b>75</b> %.
		icon:icons[5,5] icons[1,0] icons[8,1]
		cost:25 Raupen
		passive:multiply yield of Raupe by 1.75
		req:25 Raupen and UgBLRaupeF1
*UgBLRaupeF3
		name:SteinRaupe
		desc:<.> Erhöht die Produktion der Raupen um <b>75</b> %.
		icon:icons[5,5] icons[1,0] icons[8,2]
		cost:50 Raupen
		passive:multiply yield of Raupe by 1.75
		req:50 Raupen and UgBLRaupeF2
*UgBLRaupeF4
		name:EisenRaupe
		desc:<.> Erhöht die Produktion der Raupen um <b>75</b> %.
		icon:icons[5,5] icons[1,0] icons[8,3]
		cost:75 Raupen
		passive:multiply yield of Raupe by 1.75
		req:75 Raupen and UgBLRaupeF3
*UgBLRaupeF5
		name:StahlRaupe
		desc:<.> Erhöht die Produktion der Raupen um <b>75</b> %.
		icon:icons[5,5] icons[1,0] icons[8,4]
		cost:100 Raupen
		passive:multiply yield of Raupe by 1.75
		req:100 Raupen and UgBLRaupeF4
*UgBLRaupeF6
		name:KadmiumRaupe
		desc:<.> Erhöht die Produktion der Raupen um <b>75</b> %.
		icon:icons[5,5] icons[1,0] icons[8,5]
		cost:125 Raupen
		passive:multiply yield of Raupe by 1.75
		req:125 Raupen and UgBLRaupeF5
*UgBLRaupeF7
		name:KobaltRaupe
		desc:<.> Erhöht die Produktion der Raupen um <b>75</b> %.
		icon:icons[5,5] icons[1,0] icons[8,6]
		cost:150 Raupen
		passive:multiply yield of Raupe by 1.75
		req:150 Raupen and UgBLRaupeF6
*UgBLRaupeF8
		name:LithiumRaupe
		desc:<.> Erhöht die Produktion der Raupen um <b>75</b> %.
		icon:icons[5,5] icons[1,0] icons[8,7]
		cost:175 Raupen
		passive:multiply yield of Raupe by 1.75
		req:175 Raupen and UgBLRaupeF7
*UgBLRaupeF9
		name:BleiRaupe
		desc:<.> Erhöht die Produktion der Raupen um <b>75</b> %.
		icon:icons[5,5] icons[1,0] icons[8,8]
		cost:200 Raupen
		passive:multiply yield of Raupe by 1.75
		req:200 Raupen and UgBLRaupeF8
*UgBLRaupeF10
		name:BronzeRaupe
		desc:<.> Erhöht die Produktion der Raupen um <b>75</b> %.
		icon:icons[5,5] icons[1,0] icons[8,9]
		cost:225 Raupen
		passive:multiply yield of Raupe by 1.75
		req:225 Raupen and UgBLRaupeF9
*UgBLRaupeF11
		name:AluminiumRaupe
		desc:<.> Erhöht die Produktion der Raupen um <b>75</b> %.
		icon:icons[5,5] icons[1,0] icons[8,10]
		cost:250 Raupen
		passive:multiply yield of Raupe by 1.75
		req:250 Raupen and UgBLRaupeF10
*UgBLRaupeF12
		name:ChromRaupe
		desc:<.> Erhöht die Produktion der Raupen um <b>75</b> %.
		icon:icons[5,5] icons[1,0] icons[8,11]
		cost:275 Raupen
		passive:multiply yield of Raupe by 1.75
		req:275 Raupen and UgBLRaupeF11
*UgBLRaupeF13
		name:NickelRaupe
		desc:<.> Erhöht die Produktion der Raupen um <b>75</b> %.
		icon:icons[5,5] icons[1,0] icons[8,12]
		cost:300 Raupen
		passive:multiply yield of Raupe by 1.75
		req:300 Raupen and UgBLRaupeF12
*UgBLRaupeF14
		name:WolframRaupe
		desc:<.> Erhöht die Produktion der Raupen um <b>75</b> %.
		icon:icons[5,5] icons[1,0] icons[8,12]
		cost:325 Raupen
		passive:multiply yield of Raupe by 1.75
		req:325 Raupen and UgBLRaupeF13
*UgBLRaupeF15
		name:ZinnRaupe
		desc:<.> Erhöht die Produktion der Raupen um <b>75</b> %.
		icon:icons[5,5] icons[1,0] icons[8,12]
		cost:350 Raupen
		passive:multiply yield of Raupe by 1.75
		req:350 Raupen and UgBLRaupeF14	
		
		
		
	
									

		
*UgBLBienenstock1
		name:Bienenwabe
		desc:<.> Erhöht die Produktion der Bienenstöcke um <b>75</b> %.
		icon:icons[1,1] icons[3,0]
		cost:12000 Larven,10 Territorien
		passive:multiply yield of Bienenstock by 1.75
		req:12000 Larven:earned
				
*UgBLBienenstock2
		name:Bienenkönigin
		desc:<.> Erhöht die Produktion der Bienenstöcke um <b>75</b> %.
		icon:icons[1,1] icons[3,1]
		cost:90000 Larven,100 Territorien
		passive:multiply yield of Bienenstock by 1.75
		req:90000 Larven:earned and UgBLBienenstock1
		
*UgBLBienenstock3
		name:Binentango
		desc:<.> Erhöht die Produktion der Bienenstöcke um <b>75</b> %.
		icon:icons[1,1] icons[3,2]
		cost:9000000 Larven,1000 Territorien
		passive:multiply yield of Bienenstock by 1.75
		req:9000000 Larven:earned and UgBLBienenstock2
		
*UgBLBienenstock4
		name:Bienenfieber
		desc:<.> Erhöht die Produktion der Bienenstöcke um <b>75</b> %.
		icon:icons[1,1] icons[3,3]
		cost:900000000 Larven,10000 Territorien
		passive:multiply yield of Bienenstock by 1.75
		req:900000000 Larven:earned and UgBLBienenstock3
		
*UgBLBienenstock5
		name:Bienensummen
		desc:<.> Erhöht die Produktion der Bienenstöcke um <b>75</b> %.
		icon:icons[1,1] icons[3,4]
		cost:90000000000 Larven,100000 Territorien
		passive:multiply yield of Bienenstock by 1.75
		req:90000000000 Larven:earned and UgBLBienenstock4
		
*UgBLBienenstock6
		name:Bienenparty
		desc:<.> Erhöht die Produktion der Bienenstöcke um <b>75</b> %.
		icon:icons[1,1] icons[3,5]
		cost:9000000000000 Larven,1000000 Territorien
		passive:multiply yield of Bienenstock by 1.75
		req:9000000000000 Larven:earned and UgBLBienenstock5
		
*UgBLBienenstock7
		name:Bienenflügel
		desc:<.> Erhöht die Produktion der Bienenstöcke um <b>75</b> %.
		icon:icons[1,1] icons[3,6]
		cost:900000000000000 Larven,10000000 Territorien
		passive:multiply yield of Bienenstock by 1.75
		req:900000000000000 Larven:earned and UgBLBienenstock6
		
*UgBLBienenstock8
		name:Bienentorte
		desc:<.> Erhöht die Produktion der Bienenstöcke um <b>75</b> %.
		icon:icons[1,1] icons[3,7]
		cost:90000000000000000 Larven,100000000 Territorien
		passive:multiply yield of Bienenstock by 1.75
		req:90000000000000000 Larven:earned and UgBLBienenstock7
		
*UgBLBienenstock9
		name:Bienenkuchen
		desc:<.> Erhöht die Produktion der Bienenstöcke um <b>75</b> %.
		icon:icons[1,1] icons[3,8]
		cost:9000000000000000000 Larven,1000000000 Territorien
		passive:multiply yield of Bienenstock by 1.75
		req:9000000000000000000 Larven:earned and UgBLBienenstock8
		
*UgBLBienenstock10
		name:Bienensafari
		desc:<.> Erhöht die Produktion der Bienenstöcke um <b>75</b> %.
		icon:icons[1,1] icons[3,9]
		cost:900000000000000000000 Larven,10000000000 Territorien
		passive:multiply yield of Bienenstock by 1.75
		req:900000000000000000000 Larven:earned and UgBLBienenstock9
		
*UgBLBienenstock11
		name:Bienenpolka
		desc:<.> Erhöht die Produktion der Bienenstöcke um <b>75</b> %.
		icon:icons[1,1] icons[3,10]
		cost:90000000000000000000000 Larven,100000000000 Territorien
		passive:multiply yield of Bienenstock by 1.75
		req:90000000000000000000000 Larven:earned and UgBLBienenstock10
		
*UgBLBienenstock12
		name:Bientasium
		desc:<.> Erhöht die Produktion der Bienenstöcke um <b>75</b> %.
		icon:icons[1,1] icons[3,11]
		cost:9000000000000000000000000 Larven,1000000000000 Territorien
		passive:multiply yield of Bienenstock by 1.75
		req:9000000000000000000000000 Larven:earned and UgBLBienenstock11

		


//2
	
*UgBLBienenstF1
		name:Stroh Verkleidung
		desc:<.> Erhöht die Produktion der Bienenstöcke um <b>75</b> %.
		icon:icons[5,5] icons[1,1] icons[8,0]
		cost:10 Bienenstock
		passive:multiply yield of Bienenstock by 1.75
		req:10 Bienenstock
*UgBLBienenstF2
		name:Holz Verkleidung
		desc:<.> Erhöht die Produktion der Bienenstöcke um <b>75</b> %.
		icon:icons[5,5] icons[1,1] icons[8,1]
		cost:25 Bienenstock
		passive:multiply yield of Bienenstock by 1.75
		req:25 Bienenstock and UgBLBienenstF1
*UgBLBienenstF3
		name:Stein Verkleidung
		desc:<.> Erhöht die Produktion der Bienenstöcke um <b>75</b> %.
		icon:icons[5,5] icons[1,1] icons[8,2]
		cost:50 Bienenstock
		passive:multiply yield of Bienenstock by 1.75
		req:50 Bienenstock and UgBLBienenstF2
*UgBLBienenstF4
		name:Eisen Verkleidung
		desc:<.> Erhöht die Produktion der Bienenstöcke um <b>75</b> %.
		icon:icons[5,5] icons[1,1] icons[8,3]
		cost:75 Bienenstock
		passive:multiply yield of Bienenstock by 1.75
		req:75 Bienenstock and UgBLBienenstF3
*UgBLBienenstF5
		name:Stahl Verkleidung
		desc:<.> Erhöht die Produktion der Bienenstöcke um <b>75</b> %.
		icon:icons[5,5] icons[1,1] icons[8,4]
		cost:100 Bienenstock
		passive:multiply yield of Bienenstock by 1.75
		req:100 Bienenstock and UgBLBienenstF4
*UgBLBienenstF6
		name:Kadmium Verkleidung
		desc:<.> Erhöht die Produktion der Bienenstöcke um <b>75</b> %.
		icon:icons[5,5] icons[1,1] icons[8,5]
		cost:125 Bienenstock
		passive:multiply yield of Bienenstock by 1.75
		req:125 Bienenstock and UgBLBienenstF5
*UgBLBienenstF7
		name:Kobalt Verkleidung
		desc:<.> Erhöht die Produktion der Bienenstöcke um <b>75</b> %.
		icon:icons[5,5] icons[1,1] icons[8,6]
		cost:150 Bienenstock
		passive:multiply yield of Bienenstock by 1.75
		req:150 Bienenstock and UgBLBienenstF6
*UgBLBienenstF8
		name:Lithium Verkleidung
		desc:<.> Erhöht die Produktion der Bienenstöcke um <b>75</b> %.
		icon:icons[5,5] icons[1,1] icons[8,7]
		cost:175 Bienenstock
		passive:multiply yield of Bienenstock by 1.75
		req:175 Bienenstock and UgBLBienenstF7
*UgBLBienenstF9
		name:Blei Verkleidung
		desc:<.> Erhöht die Produktion der Bienenstöcke um <b>75</b> %.
		icon:icons[5,5] icons[1,1] icons[8,8]
		cost:200 Bienenstock
		passive:multiply yield of Bienenstock by 1.75
		req:200 Bienenstock and UgBLBienenstF8
*UgBLBienenstF10
		name:Bronze Verkleidung
		desc:<.> Erhöht die Produktion der Bienenstöcke um <b>75</b> %.
		icon:icons[5,5] icons[1,1] icons[8,9]
		cost:225 Bienenstock
		passive:multiply yield of Bienenstock by 1.75
		req:225 Bienenstock and UgBLBienenstF9
*UgBLBienenstF11
		name:Aluminium Verkleidung
		desc:<.> Erhöht die Produktion der Bienenstöcke um <b>75</b> %.
		icon:icons[5,5] icons[1,1] icons[8,10]
		cost:250 Bienenstock
		passive:multiply yield of Bienenstock by 1.75
		req:250 Bienenstock and UgBLBienenstF10
*UgBLBienenstF12
		name:Chrom Verkleidung
		desc:<.> Erhöht die Produktion der Bienenstöcke um <b>75</b> %.
		icon:icons[5,5] icons[1,1] icons[8,11]
		cost:275 Bienenstock
		passive:multiply yield of Bienenstock by 1.75
		req:275 Bienenstock and UgBLBienenstF11
*UgBLBienenstF13
		name:Nickel Verkleidung
		desc:<.> Erhöht die Produktion der Bienenstöcke um <b>75</b> %.
		icon:icons[5,5] icons[1,1] icons[8,12]
		cost:300 Bienenstock
		passive:multiply yield of Bienenstock by 1.75
		req:300 Bienenstock and UgBLBienenstF12
*UgBLBienenstF14
		name:Wolfram Verkleidung
		desc:<.> Erhöht die Produktion der Bienenstöcke um <b>75</b> %.
		icon:icons[5,5] icons[1,1] icons[8,12]
		cost:325 Bienenstock
		passive:multiply yield of Bienenstock by 1.75
		req:325 Bienenstock and UgBLBienenstF13
*UgBLBienenstF15
		name:Zinn Verkleidung
		desc:<.> Erhöht die Produktion der Bienenstöcke um <b>75</b> %.
		icon:icons[5,5] icons[1,1] icons[8,12]
		cost:350 Bienenstock
		passive:multiply yield of Bienenstock by 1.75
		req:350 Bienenstock and UgBLBienenstF14	
		



*UgBLTermitenbau1
		name:Termitenpolka
		desc:<.> Erhöht die Produktion der Termitenbauten um <b>75</b> %.
		icon:icons[1,1] icons[3,0]
		cost:810000 Larven,100 Territorien
		passive:multiply yield of Termitenbau by 1.75
		req:810000 Larven:earned
		
*UgBLTermitenbau2
		name:Termitenmeister
		desc:<.> Erhöht die Produktion der Termitenbauten um <b>75</b> %.
		icon:icons[1,2] icons[3,1]
		cost:81000000 Larven,1000 Territorien
		passive:multiply yield of Termitenbau by 1.75
		req:81000000 Larven:earned and UgBLTermitenbau1
		
*UgBLTermitenbau3
		name:Termitits
		desc:<.> Erhöht die Produktion der Termitenbauten um <b>75</b> %.
		icon:icons[1,2] icons[3,2]
		cost:8100000000 Larven,10000 Territorien
		passive:multiply yield of Termitenbau by 1.75
		req:8100000000 Larven:earned and UgBLTermitenbau2
		
*UgBLTermitenbau4
		name:Termitenermaster
		desc:<.> Erhöht die Produktion der Termitenbauten um <b>75</b> %.
		icon:icons[1,2] icons[3,3]
		cost:810000000000 Larven,100000 Territorien
		passive:multiply yield of Termitenbau by 1.75
		req:810000000000 Larven:earned and UgBLTermitenbau3
				
*UgBLTermitenbau5
		name:Termitenkaffee
		desc:<.> Erhöht die Produktion der Termitenbauten um <b>75</b> %.
		icon:icons[1,2] icons[3,4]
		cost:81000000000000 Larven,1000000 Territorien
		passive:multiply yield of Termitenbau by 1.75
		req:81000000000000 Larven:earned and UgBLTermitenbau4
				
*UgBLTermitenbau6
		name:Termitenmusik
		desc:<.> Erhöht die Produktion der Termitenbauten um <b>75</b> %.
		icon:icons[1,2] icons[3,5]
		cost:8100000000000000 Larven,10000000 Territorien
		passive:multiply yield of Termitenbau by 1.75
		req:8100000000000000 Larven:earned and UgBLTermitenbau5
				
*UgBLTermitenbau7
		name:Termitenrising
		desc:<.> Erhöht die Produktion der Termitenbauten um <b>75</b> %.
		icon:icons[1,2] icons[3,6]
		cost:810000000000000000 Larven,100000000 Territorien
		passive:multiply yield of Termitenbau by 1.75
		req:810000000000000000 Larven:earned and UgBLTermitenbau6
				
*UgBLTermitenbau8
		name:Termitenbonbon
		desc:<.> Erhöht die Produktion der Termitenbauten um <b>75</b> %.
		icon:icons[1,2] icons[3,7]
		cost:81000000000000000000 Larven,1000000000 Territorien
		passive:multiply yield of Termitenbau by 1.75
		req:81000000000000000000 Larven:earned and UgBLTermitenbau7
				
*UgBLTermitenbau9
		name:Termitensamba
		desc:<.> Erhöht die Produktion der Termitenbauten um <b>75</b> %.
		icon:icons[1,2] icons[3,8]
		cost:8100000000000000000000 Larven,10000000000 Territorien
		passive:multiply yield of Termitenbau by 1.75
		req:8100000000000000000000 Larven:earned and UgBLTermitenbau8
				
*UgBLTermitenbau10
		name:Termitosis
		desc:<.> Erhöht die Produktion der Termitenbauten um <b>75</b> %.
		icon:icons[1,2] icons[3,9]
		cost:810000000000000000000000 Larven,100000000000 Territorien
		passive:multiply yield of Termitenbau by 1.75
		req:810000000000000000000000 Larven:earned and UgBLTermitenbau9
				
*UgBLTermitenbau11
		name:Termitenerhebung
		desc:<.> Erhöht die Produktion der Termitenbauten um <b>75</b> %.
		icon:icons[1,2] icons[3,10]
		cost:81000000000000000000000000 Larven,1000000000000 Territorien
		passive:multiply yield of Termitenbau by 1.75
		req:81000000000000000000000000 Larven:earned and UgBLTermitenbau10
				
*UgBLTermitenbau12
		name:Termitengesang
		desc:<.> Erhöht die Produktion der Termitenbauten um <b>75</b> %.
		icon:icons[1,2] icons[3,11]
		cost:8100000000000000000000000000 Larven,10000000000000 Territorien
		passive:multiply yield of Termitenbau by 1.75
		req:8100000000000000000000000000 Larven:earned and UgBLTermitenbau11
		
		


//3
	
*UgBLTermitenbF1
		name:Stroh Verkleidung
		desc:<.> Erhöht die Produktion der Termitenbauten um <b>75</b> %.
		icon:icons[5,5] icons[11,0]
		cost:10 Termitenbau
		passive:multiply yield of Termitenbau by 1.75
		req:10 Termitenbau
*UgBLTermitenbF2
		name:Holz Verkleidung
		desc:<.> Erhöht die Produktion der Termitenbauten um <b>75</b> %.
		icon:icons[5,5] icons[11,1] 
		cost:25 Termitenbau
		passive:multiply yield of Termitenbau by 1.75
		req:25 Termitenbau and UgBLTermitenbF1
*UgBLTermitenbF3
		name:Stein Verkleidung
		desc:<.> Erhöht die Produktion der Termitenbauten um <b>75</b> %.
		icon:icons[5,5] icons[11,2]
		cost:50 Termitenbau
		passive:multiply yield of Termitenbau by 1.75
		req:50 Termitenbau and UgBLTermitenbF2
*UgBLTermitenbF4
		name:Eisen Verkleidung
		desc:<.> Erhöht die Produktion der Termitenbauten um <b>75</b> %.
		icon:icons[5,5] icons[11,3]
		cost:75 Termitenbau
		passive:multiply yield of Termitenbau by 1.75
		req:75 Termitenbau and UgBLTermitenbF3
*UgBLTermitenbF5
		name:Stahl Verkleidung
		desc:<.> Erhöht die Produktion der Termitenbauten um <b>75</b> %.
		icon:icons[5,5] icons[11,4]
		cost:100 Termitenbau
		passive:multiply yield of Termitenbau by 1.75
		req:100 Termitenbau and UgBLTermitenbF4
*UgBLTermitenbF6
		name:Kadmium Verkleidung
		desc:<.> Erhöht die Produktion der Termitenbauten um <b>75</b> %.
		icon:icons[5,5] icons[11,5]
		cost:125 Termitenbau
		passive:multiply yield of Termitenbau by 1.75
		req:125 Termitenbau and UgBLTermitenbF5
*UgBLTermitenbF7
		name:Kobalt Verkleidung
		desc:<.> Erhöht die Produktion der Termitenbauten um <b>75</b> %.
		icon:icons[5,5] icons[11,6]
		cost:150 Termitenbau
		passive:multiply yield of Termitenbau by 1.75
		req:150 Termitenbau and UgBLTermitenbF6
*UgBLTermitenbF8
		name:Lithium Verkleidung
		desc:<.> Erhöht die Produktion der Termitenbauten um <b>75</b> %.
		icon:icons[5,5] icons[11,7]
		cost:175 Termitenbau
		passive:multiply yield of Termitenbau by 1.75
		req:175 Termitenbau and UgBLTermitenbF7
*UgBLTermitenbF9
		name:Blei Verkleidung
		desc:<.> Erhöht die Produktion der Termitenbauten um <b>75</b> %.
		icon:icons[5,5] icons[11,8]
		cost:200 Termitenbau
		passive:multiply yield of Termitenbau by 1.75
		req:200 Termitenbau and UgBLTermitenbF8
*UgBLTermitenbF10
		name:Bronze Verkleidung
		desc:<.> Erhöht die Produktion der Termitenbauten um <b>75</b> %.
		icon:icons[5,5] icons[11,9]
		cost:225 Termitenbau
		passive:multiply yield of Termitenbau by 1.75
		req:225 Termitenbau and UgBLTermitenbF9
*UgBLTermitenbF11
		name:Aluminium Verkleidung
		desc:<.> Erhöht die Produktion der Termitenbauten um <b>75</b> %.
		icon:icons[5,5] icons[11,10]
		cost:250 Termitenbau
		passive:multiply yield of Termitenbau by 1.75
		req:250 Termitenbau and UgBLTermitenbF10
*UgBLTermitenbF12
		name:Chrom Verkleidung
		desc:<.> Erhöht die Produktion der Termitenbauten um <b>75</b> %.
		icon:icons[5,5] icons[11,11]
		cost:275 Termitenbau
		passive:multiply yield of Termitenbau by 1.75
		req:275 Termitenbau and UgBLTermitenbF11
*UgBLTermitenbF13
		name:Nickel Verkleidung
		desc:<.> Erhöht die Produktion der Termitenbauten um <b>75</b> %.
		icon:icons[5,5] icons[11,12]
		cost:300 Termitenbau
		passive:multiply yield of Termitenbau by 1.75
		req:300 Termitenbau and UgBLTermitenbF12
*UgBLTermitenbF14
		name:Wolfram Verkleidung
		desc:<.> Erhöht die Produktion der Termitenbauten um <b>75</b> %.
		icon:icons[5,5] icons[11,13]
		cost:325 Termitenbau
		passive:multiply yield of Termitenbau by 1.75
		req:325 Termitenbau and UgBLTermitenbF13
*UgBLTermitenbF15
		name:Zinn Verkleidung
		desc:<.> Erhöht die Produktion der Termitenbauten um <b>75</b> %.
		icon:icons[5,5] icons[11,14]
		cost:350 Termitenbau
		passive:multiply yield of Termitenbau by 1.75
		req:350 Termitenbau and UgBLTermitenbF14	
				
		

*UgBLBlatt1
		name:Ahornblatt
		desc:<.> Erhöht die Produktion der Blätter um <b>75</b> %.
		icon:icons[1,3] icons[3,0]
		cost:260000 Larven,100 Territorien
		passive:multiply yield of Blatt by 1.75
		req:260000 Larven:earned
		
*UgBLBlatt2
		name:Eichenblatt
		desc:<.> Erhöht die Produktion der Blätter um <b>75</b> %.
		icon:icons[1,3] icons[3,1]
		cost:26000000 Larven,1000 Territorien
		passive:multiply yield of Blatt by 1.75
		req:26000000 Larven:earned and UgBLBlatt1
		
*UgBLBlatt3
		name:Buchenblatt
		desc:<.> Erhöht die Produktion der Blätter um <b>75</b> %.
		icon:icons[1,3] icons[3,2]
		cost:2600000000 Larven,10000 Territorien
		passive:multiply yield of Blatt by 1.75
		req:2600000000 Larven:earned and UgBLBlatt2

*UgBLBlatt4
		name:Birkenblatt
		desc:<.> Erhöht die Produktion der Blätter um <b>75</b> %.
		icon:icons[1,3] icons[3,3]
		cost:260000000000 Larven,100000 Territorien
		passive:multiply yield of Blatt by 1.75
		req:260000000000 Larven:earned and UgBLBlatt3
		

*UgBLBlatt5
		name:Eschenblatt
		desc:<.> Erhöht die Produktion der Blätter um <b>75</b> %.
		icon:icons[1,3] icons[3,4]
		cost:26000000000000 Larven,1000000 Territorien
		passive:multiply yield of Blatt by 1.75
		req:26000000000000 Larven:earned and UgBLBlatt4


*UgBLBlatt6
		name:Erlenblatt
		desc:<.> Erhöht die Produktion der Blätter um <b>75</b> %.
		icon:icons[1,3] icons[3,5]
		cost:2600000000000000 Larven,10000000 Territorien
		passive:multiply yield of Blatt by 1.75
		req:2600000000000000 Larven:earned and UgBLBlatt5
				

*UgBLBlatt7
		name:Haselblatt
		desc:<.> Erhöht die Produktion der Blätter um <b>75</b> %.
		icon:icons[1,3] icons[3,6]
		cost:260000000000000000 Larven,100000000 Territorien
		passive:multiply yield of Blatt by 1.75
		req:260000000000000000 Larven:earned and UgBLBlatt6


*UgBLBlatt8
		name:Wallnussblatt
		desc:<.> Erhöht die Produktion der Blätter um <b>75</b> %.
		icon:icons[1,3] icons[3,7]
		cost:26000000000000000000 Larven,1000000000 Territorien
		passive:multiply yield of Blatt by 1.75
		req:26000000000000000000 Larven:earned and UgBLBlatt7


*UgBLBlatt9
		name:Kastanienblatt
		desc:<.> Erhöht die Produktion der Blätter um <b>75</b> %.
		icon:icons[1,3] icons[3,8]
		cost:2600000000000000000000 Larven,10000000000 Territorien
		passive:multiply yield of Blatt by 1.75
		req:2600000000000000000000 Larven:earned and UgBLBlatt8


*UgBLBlatt10
		name:Lärchenblatt
		desc:<.> Erhöht die Produktion der Blätter um <b>75</b> %.
		icon:icons[1,3] icons[3,9]
		cost:260000000000000000000000 Larven,100000000000 Territorien
		passive:multiply yield of Blatt by 1.75
		req:260000000000000000000000 Larven:earned and UgBLBlatt9


*UgBLBlatt11
		name:Palmenblatt
		desc:<.> Erhöht die Produktion der Blätter um <b>75</b> %.
		icon:icons[1,3] icons[3,10]
		cost:26000000000000000000000000 Larven,1000000000000 Territorien
		passive:multiply yield of Blatt by 1.75
		req:26000000000000000000000000 Larven:earned and UgBLBlatt10


*UgBLBlatt12
		name:Lindenblatt
		desc:<.> Erhöht die Produktion der Blätter um <b>75</b> %.
		icon:icons[1,3] icons[3,11]
		cost:2600000000000000000000000000 Larven,10000000000000 Territorien
		passive:multiply yield of Blatt by 1.75
		req:2600000000000000000000000000 Larven:earned and UgBLBlatt11
		

		
		


//4
	
*UgBLBlattF1
		name:Ahorn Blatt
		desc:<.> Erhöht die Produktion der Blätter um <b>75</b> %.
		icon:icons[5,5] icons[12,0]
		cost:10 Blatt
		passive:multiply yield of Blatt by 1.75
		req:10 Blatt
		class:noBackground
*UgBLBlattF2
		name:Birken Blatt
		desc:<.> Erhöht die Produktion der Blätter um <b>75</b> %.
		icon:icons[5,5] icons[12,1] 
		cost:25 Blatt
		passive:multiply yield of Blatt by 1.75
		req:25 Blatt and UgBLBlattF1
		class:noBackground
*UgBLBlattF3
		name:Eichen Blatt
		desc:<.> Erhöht die Produktion der Blätter um <b>75</b> %.
		icon:icons[5,5] icons[12,2]
		cost:50 Blatt
		passive:multiply yield of Blatt by 1.75
		req:50 Blatt and UgBLBlattF2
		class:noBackground
*UgBLBlattF4
		name:Buchen Blatt
		desc:<.> Erhöht die Produktion der Blätter um <b>75</b> %.
		icon:icons[5,5] icons[12,3]
		cost:75 Blatt
		passive:multiply yield of Blatt by 1.75
		req:75 Blatt and UgBLBlattF3
		class:noBackground
*UgBLBlattF5
		name:Birnen Blatt
		desc:<.> Erhöht die Produktion der Blätter um <b>75</b> %.
		icon:icons[5,5] icons[12,4]
		cost:100 Blatt
		passive:multiply yield of Blatt by 1.75
		req:100 Blatt and UgBLBlattF4
		class:noBackground
*UgBLBlattF6
		name:Ebereschen Blatt
		desc:<.> Erhöht die Produktion der Blätter um <b>75</b> %.
		icon:icons[5,5] icons[12,5]
		cost:125 Blatt
		passive:multiply yield of Blatt by 1.75
		req:125 Blatt and UgBLBlattF5
		class:noBackground
*UgBLBlattF7
		name:Erlen Blatt
		desc:<.> Erhöht die Produktion der Blätter um <b>75</b> %.
		icon:icons[5,5] icons[12,6]
		cost:150 Blatt
		passive:multiply yield of Blatt by 1.75
		req:150 Blatt and UgBLBlattF6
		class:noBackground
*UgBLBlattF8
		name:Kastanien Blatt
		desc:<.> Erhöht die Produktion der Blätter um <b>75</b> %.
		icon:icons[5,5] icons[12,7]
		cost:175 Blatt
		passive:multiply yield of Blatt by 1.75
		req:175 Blatt and UgBLBlattF7
		class:noBackground
*UgBLBlattF9
		name:Linden Blatt
		desc:<.> Erhöht die Produktion der Blätter um <b>75</b> %.
		icon:icons[5,5] icons[12,8]
		cost:200 Blatt
		passive:multiply yield of Blatt by 1.75
		req:200 Blatt and UgBLBlattF8
		class:noBackground
*UgBLBlattF10
		name:Schwarzdorn Blatt
		desc:<.> Erhöht die Produktion der Blätter um <b>75</b> %.
		icon:icons[5,5] icons[12,9]
		cost:225 Blatt
		passive:multiply yield of Blatt by 1.75
		req:225 Blatt and UgBLBlattF9
		class:noBackground
*UgBLBlattF11
		name:Stechpalmen Blatt
		desc:<.> Erhöht die Produktion der Blätter um <b>75</b> %.
		icon:icons[5,5] icons[12,10]
		cost:250 Blatt
		passive:multiply yield of Blatt by 1.75
		req:250 Blatt and UgBLBlattF10
		class:noBackground
*UgBLBlattF12
		name:Ulmen Blatt
		desc:<.> Erhöht die Produktion der Blätter um <b>75</b> %.
		icon:icons[5,5] icons[12,11]
		cost:275 Blatt
		passive:multiply yield of Blatt by 1.75
		req:275 Blatt and UgBLBlattF11
		class:noBackground
*UgBLBlattF13
		name:Weiden Blatt
		desc:<.> Erhöht die Produktion der Blätter um <b>75</b> %.
		icon:icons[5,5] icons[12,12]
		cost:300 Blatt
		passive:multiply yield of Blatt by 1.75
		req:300 Blatt and UgBLBlattF12
		class:noBackground
*UgBLBlattF14
		name:Pappel Blatt
		desc:<.> Erhöht die Produktion der Blätter um <b>75</b> %.
		icon:icons[5,5] icons[12,13]
		cost:325 Blatt
		passive:multiply yield of Blatt by 1.75
		req:325 Blatt and UgBLBlattF13
		class:noBackground
*UgBLBlattF15
		name:Apfel Blatt
		desc:<.> Erhöht die Produktion der Blätter um <b>75</b> %.
		icon:icons[5,5] icons[12,14]
		cost:350 Blatt
		passive:multiply yield of Blatt by 1.75
		req:350 Blatt and UgBLBlattF14	
		class:noBackground
		
		
//5


*UgBLWNest1
		name:Bssst!
		desc:<.> Erhöht die Produktion der WespenNester um <b>75</b> %.
		icon:icons[1,4] icons[3,0]
		cost:1456000 Larven,100 Territorien
		passive:multiply yield of WespenNest by 1.75
		req:1456000 Larven:earned
		
*UgBLWNest2
		name:Zartes WespenNest
		desc:<.> Erhöht die Produktion der WespenNester um <b>75</b> %.
		icon:icons[1,4] icons[3,1]
		cost:145600000 Larven,1000 Territorien
		passive:multiply yield of WespenNest by 1.75
		req:145600000 Larven:earned and UgBLWNest1
		
*UgBLWNest3
		name:Feines WespenNest
		desc:<.> Erhöht die Produktion der WespenNester um <b>75</b> %.
		icon:icons[1,4] icons[3,2]
		cost:14560000000 Larven,10000 Territorien
		passive:multiply yield of WespenNest by 1.75
		req:14560000000 Larven:earned and UgBLWNest2

*UgBLWNest4
		name:Großes WespenNest
		desc:<.> Erhöht die Produktion der WespenNester um <b>75</b> %.
		icon:icons[1,4] icons[3,3]
		cost:1456000000000 Larven,100000 Territorien
		passive:multiply yield of WespenNest by 1.75
		req:1456000000000 Larven:earned and UgBLWNest3
		

*UgBLWNest5
		name:Langes WespenNest
		desc:<.> Erhöht die Produktion der WespenNester um <b>75</b> %.
		icon:icons[1,4] icons[3,4]
		cost:145600000000000 Larven,1000000 Territorien
		passive:multiply yield of WespenNest by 1.75
		req:145600000000000 Larven:earned and UgBLWNest4


*UgBLWNest6
		name:Dickes WespenNest
		desc:<.> Erhöht die Produktion der WespenNester um <b>75</b> %.
		icon:icons[1,4] icons[3,5]
		cost:14560000000000000 Larven,10000000 Territorien
		passive:multiply yield of WespenNest by 1.75
		req:14560000000000000 Larven:earned and UgBLWNest5
				

*UgBLWNest7
		name:Dünnes WespenNest
		desc:<.> Erhöht die Produktion der WespenNester um <b>75</b> %.
		icon:icons[1,4] icons[3,6]
		cost:1456000000000000000 Larven,100000000 Territorien
		passive:multiply yield of WespenNest by 1.75
		req:1456000000000000000 Larven:earned and UgBLWNest6


*UgBLWNest8
		name:Altes WespenNest
		desc:<.> Erhöht die Produktion der WespenNester um <b>75</b> %.
		icon:icons[1,4] icons[3,7]
		cost:145600000000000000000 Larven,1000000000 Territorien
		passive:multiply yield of WespenNest by 1.75
		req:145600000000000000000 Larven:earned and UgBLWNest7


*UgBLWNest9
		name:Dunkles WespenNest
		desc:<.> Erhöht die Produktion der WespenNester um <b>75</b> %.
		icon:icons[1,4] icons[3,8]
		cost:14560000000000000000000 Larven,10000000000 Territorien
		passive:multiply yield of WespenNest by 1.75
		req:14560000000000000000000 Larven:earned and UgBLWNest8


*UgBLWNest10
		name:Helles WespenNest
		desc:<.> Erhöht die Produktion der WespenNester um <b>75</b> %.
		icon:icons[1,4] icons[3,9]
		cost:1456000000000000000000000 Larven,100000000000 Territorien
		passive:multiply yield of WespenNest by 1.75
		req:1456000000000000000000000 Larven:earned and UgBLWNest9


*UgBLWNest11
		name:Gespaltenes WespenNest
		desc:<.> Erhöht die Produktion der WespenNester um <b>75</b> %.
		icon:icons[1,4] icons[3,10]
		cost:145600000000000000000000000 Larven,1000000000000 Territorien
		passive:multiply yield of WespenNest by 1.75
		req:145600000000000000000000000 Larven:earned and UgBLWNest10


*UgBLWNest12
		name:WespenNester Haufen
		desc:<.> Erhöht die Produktion der WespenNester um <b>75</b> %.
		icon:icons[1,4] icons[3,11]
		cost:14560000000000000000000000000 Larven,10000000000000 Territorien
		passive:multiply yield of WespenNest by 1.75
		req:14560000000000000000000000000 Larven:earned and UgBLWNest11
		


		
//5
	
*UgBLWespenNestF1
		name:Kleine Verstärkung
		desc:<.> Erhöht die Produktion der WespenNester um <b>75</b> %.
		icon:icons[5,5] icons[13,0]
		cost:10 WespenNest
		passive:multiply yield of WespenNest by 1.75
		req:10 WespenNest
		class:noBackground
*UgBLWespenNestF2
		name:Holz Vertäfelung
		desc:<.> Erhöht die Produktion der WespenNester um <b>75</b> %.
		icon:icons[5,5] icons[13,1] 
		cost:25 WespenNest
		passive:multiply yield of WespenNest by 1.75
		req:25 WespenNest and UgBLWespenNestF1
		class:noBackground
*UgBLWespenNestF3
		name:Strauch Schutz
		desc:<.> Erhöht die Produktion der WespenNester um <b>75</b> %.
		icon:icons[5,5] icons[13,2]
		cost:50 WespenNest
		passive:multiply yield of WespenNest by 1.75
		req:50 WespenNest and UgBLWespenNestF2
		class:noBackground
*UgBLWespenNestF4
		name:Äste Rahmen
		desc:<.> Erhöht die Produktion der WespenNester um <b>75</b> %.
		icon:icons[5,5] icons[13,3]
		cost:75 WespenNest
		passive:multiply yield of WespenNest by 1.75
		req:75 WespenNest and UgBLWespenNestF3
		class:noBackground
*UgBLWespenNestF5
		name:Dornen
		desc:<.> Erhöht die Produktion der WespenNester um <b>75</b> %.
		icon:icons[5,5] icons[13,4]
		cost:100 WespenNest
		passive:multiply yield of WespenNest by 1.75
		req:100 WespenNest and UgBLWespenNestF4
		class:noBackground
*UgBLWespenNestF6
		name:Dickere Wände
		desc:<.> Erhöht die Produktion der WespenNester um <b>75</b> %.
		icon:icons[5,5] icons[13,5]
		cost:125 WespenNest
		passive:multiply yield of WespenNest by 1.75
		req:125 WespenNest and UgBLWespenNestF5
		class:noBackground
*UgBLWespenNestF7
		name:Brutplätze
		desc:<.> Erhöht die Produktion der WespenNester um <b>75</b> %.
		icon:icons[5,5] icons[13,6]
		cost:150 WespenNest
		passive:multiply yield of WespenNest by 1.75
		req:150 WespenNest and UgBLWespenNestF6
		class:noBackground
*UgBLWespenNestF8
		name:Zweiter Eingang
		desc:<.> Erhöht die Produktion der WespenNester um <b>75</b> %.
		icon:icons[5,5] icons[13,7]
		cost:175 WespenNest
		passive:multiply yield of WespenNest by 1.75
		req:175 WespenNest and UgBLWespenNestF7
		class:noBackground
*UgBLWespenNestF9
		name:Harte Schale
		desc:<.> Erhöht die Produktion der WespenNester um <b>75</b> %.
		icon:icons[5,5] icons[13,8]
		cost:200 WespenNest
		passive:multiply yield of WespenNest by 1.75
		req:200 WespenNest and UgBLWespenNestF8
		class:noBackground
*UgBLWespenNestF10
		name:Windschutz
		desc:<.> Erhöht die Produktion der WespenNester um <b>75</b> %.
		icon:icons[5,5] icons[13,9]
		cost:225 WespenNest
		passive:multiply yield of WespenNest by 1.75
		req:225 WespenNest and UgBLWespenNestF9
		class:noBackground
*UgBLWespenNestF11
		name:Ein paar Zweige mehr
		desc:<.> Erhöht die Produktion der WespenNester um <b>75</b> %.
		icon:icons[5,5] icons[13,10]
		cost:250 WespenNest
		passive:multiply yield of WespenNest by 1.75
		req:250 WespenNest and UgBLWespenNestF10
		class:noBackground
*UgBLWespenNestF12
		name:Nestbauerinnen
		desc:<.> Erhöht die Produktion der WespenNester um <b>75</b> %.
		icon:icons[5,5] icons[13,11]
		cost:275 WespenNest
		passive:multiply yield of WespenNest by 1.75
		req:275 WespenNest and UgBLWespenNestF11
		class:noBackground
*UgBLWespenNestF13
		name:Wespen Königin
		desc:<.> Erhöht die Produktion der WespenNester um <b>75</b> %.
		icon:icons[5,5] icons[13,12]
		cost:300 WespenNest
		passive:multiply yield of WespenNest by 1.75
		req:300 WespenNest and UgBLWespenNestF12
		class:noBackground
*UgBLWespenNestF14
		name:Wespen Prinzessin
		desc:<.> Erhöht die Produktion der WespenNester um <b>75</b> %.
		icon:icons[5,5] icons[13,13]
		cost:325 WespenNest
		passive:multiply yield of WespenNest by 1.75
		req:325 WespenNest and UgBLWespenNestF13
		class:noBackground
*UgBLWespenNestF15
		name:Wespen Staat
		desc:<.> Erhöht die Produktion der WespenNester um <b>75</b> %.
		icon:icons[5,5] icons[13,14]
		cost:350 WespenNest
		passive:multiply yield of WespenNest by 1.75
		req:350 WespenNest and UgBLWespenNestF14	
		class:noBackground
		
		
//6


*UgBLVApfel1
		name:Verfaulter Elstar
		desc:<.> Erhöht die Produktion der VerfaultenÄpfel um <b>75</b> %.
		icon:icons[1,5] icons[3,0]
		cost:165800000 Larven, 16580000 Nahrung,1000 Territorien
		passive:multiply yield of VerfaulterApfel by 1.75
		req:165800000 Larven:earned
		
*UgBLVApfel2
		name:Verfaulter Gala
		desc:<.> Erhöht die Produktion der VerfaultenÄpfel um <b>75</b> %.
		icon:icons[1,5] icons[3,1]
		cost:16580000000 Larven, 1658000000 Nahrung,10000 Territorien
		passive:multiply yield of VerfaulterApfel by 1.75
		req:16580000000 Larven:earned and UgBLVApfel1
		
*UgBLVApfel3
		name:Verfaulter Iduna
		desc:<.> Erhöht die Produktion der VerfaultenÄpfel um <b>75</b> %.
		icon:icons[1,5] icons[3,2]
		cost:1658000000000 Larven, 165800000000 Nahrung,100000 Territorien
		passive:multiply yield of VerfaulterApfel by 1.75
		req:1658000000000 Larven:earned and UgBLVApfel2

*UgBLVApfel4
		name:Verfaulter Maigold
		desc:<.> Erhöht die Produktion der VerfaultenÄpfel um <b>75</b> %.
		icon:icons[1,5] icons[3,3]
		cost:165800000000000 Larven, 16580000000000 Nahrung,1000000 Territorien
		passive:multiply yield of VerfaulterApfel by 1.75
		req:165800000000000 Larven:earned and UgBLVApfel3
		

*UgBLVApfel5
		name:Verfaulter Brauner Apfel
		desc:<.> Erhöht die Produktion der VerfaultenÄpfel um <b>75</b> %.
		icon:icons[1,5] icons[3,4]
		cost:16580000000000000 Larven, 1658000000000000 Nahrung,10000000 Territorien
		passive:multiply yield of VerfaulterApfel by 1.75
		req:16580000000000000 Larven:earned and UgBLVApfel4


*UgBLVApfel6
		name:Verfaulter Alter Apfel
		desc:<.> Erhöht die Produktion der VerfaultenÄpfel um <b>75</b> %.
		icon:icons[1,5] icons[3,5]
		cost:1658000000000000000 Larven, 165800000000000000 Nahrung,100000000 Territorien
		passive:multiply yield of VerfaulterApfel by 1.75
		req:1658000000000000000 Larven:earned and UgBLVApfel5
				

*UgBLVApfel7
		name:Verfaulter Red Delicious
		desc:<.> Erhöht die Produktion der VerfaultenÄpfel um <b>75</b> %.
		icon:icons[1,5] icons[3,6]
		cost:165800000000000000000 Larven, 16580000000000000000 Nahrung,1000000000 Territorien
		passive:multiply yield of VerfaulterApfel by 1.75
		req:165800000000000000000 Larven:earned and UgBLVApfel6


*UgBLVApfel8
		name:Verfaulter Golden Delicious
		desc:<.> Erhöht die Produktion der VerfaultenÄpfel um <b>75</b> %.
		icon:icons[1,5] icons[3,7]
		cost:16580000000000000000000 Larven, 1658000000000000000000 Nahrung,10000000000 Territorien
		passive:multiply yield of VerfaulterApfel by 1.75
		req:16580000000000000000000 Larven:earned and UgBLVApfel7


*UgBLVApfel9
		name:Verfaulter Yataka
		desc:<.> Erhöht die Produktion der VerfaultenÄpfel um <b>75</b> %.
		icon:icons[1,5] icons[3,8]
		cost:1658000000000000000000000 Larven, 165800000000000000000000 Nahrung,100000000000 Territorien
		passive:multiply yield of VerfaulterApfel by 1.75
		req:1658000000000000000000000 Larven:earned and UgBLVApfel8


*UgBLVApfel10
		name:Verfaulter Jonagold
		desc:<.> Erhöht die Produktion der VerfaultenÄpfel um <b>75</b> %.
		icon:icons[1,5] icons[3,9]
		cost:165800000000000000000000000 Larven, 16580000000000000000000000 Nahrung,1000000000000 Territorien
		passive:multiply yield of VerfaulterApfel by 1.75
		req:165800000000000000000000000 Larven:earned and UgBLVApfel9


*UgBLVApfel11
		name:Verfaulter Kanzi
		desc:<.> Erhöht die Produktion der VerfaultenÄpfel um <b>75</b> %.
		icon:icons[1,5] icons[3,10]
		cost:16580000000000000000000000000 Larven, 1658000000000000000000000000 Nahrung,10000000000000 Territorien
		passive:multiply yield of VerfaulterApfel by 1.75
		req:16580000000000000000000000000 Larven:earned and UgBLVApfel10


*UgBLVApfel12
		name:Verfaulter Kleiner Apfel
		desc:<.> Erhöht die Produktion der VerfaultenÄpfel um <b>75</b> %.
		icon:icons[1,5] icons[3,11]
		cost:1658000000000000000000000000000 Larven, 165800000000000000000000000000 Nahrung,100000000000000 Territorien
		passive:multiply yield of VerfaulterApfel by 1.75
		req:1658000000000000000000000000000 Larven:earned and UgBLVApfel11
		


//6
	
*UgBLVApfelF1
		name:Brauner Apfel
		desc:<.> Erhöht die Produktion der VerfaultenÄpfel um <b>75</b> %.
		icon:icons[5,5] icons[14,0]
		cost:10 VerfaulterApfel
		passive:multiply yield of VerfaulterApfel by 1.75
		req:10 VerfaulterApfel
		class:noBackground
*UgBLVApfelF2
		name:Schrumpeliger Apfel
		desc:<.> Erhöht die Produktion der VerfaultenÄpfel um <b>75</b> %.
		icon:icons[5,5] icons[14,1] 
		cost:25 VerfaulterApfel
		passive:multiply yield of VerfaulterApfel by 1.75
		req:25 VerfaulterApfel and UgBLVApfelF1
		class:noBackground
*UgBLVApfelF3
		name:Angeschlagener Apfel
		desc:<.> Erhöht die Produktion der VerfaultenÄpfel um <b>75</b> %.
		icon:icons[5,5] icons[14,2]
		cost:50 VerfaulterApfel
		passive:multiply yield of VerfaulterApfel by 1.75
		req:50 VerfaulterApfel and UgBLVApfelF2
		class:noBackground
*UgBLVApfelF4
		name:Matschiger Apfel
		desc:<.> Erhöht die Produktion der VerfaultenÄpfel um <b>75</b> %.
		icon:icons[5,5] icons[14,3]
		cost:75 VerfaulterApfel
		passive:multiply yield of VerfaulterApfel by 1.75
		req:75 VerfaulterApfel and UgBLVApfelF3
		class:noBackground
*UgBLVApfelF5
		name:Angefressener Apfel
		desc:<.> Erhöht die Produktion der VerfaultenÄpfel um <b>75</b> %.
		icon:icons[5,5] icons[14,4]
		cost:100 VerfaulterApfel
		passive:multiply yield of VerfaulterApfel by 1.75
		req:100 VerfaulterApfel and UgBLVApfelF4
		class:noBackground
*UgBLVApfelF6
		name:Fauliger Apfel
		desc:<.> Erhöht die Produktion der VerfaultenÄpfel um <b>75</b> %.
		icon:icons[5,5] icons[14,5]
		cost:125 VerfaulterApfel
		passive:multiply yield of VerfaulterApfel by 1.75
		req:125 VerfaulterApfel and UgBLVApfelF5
		class:noBackground
*UgBLVApfelF7
		name:Stinkender Apfel
		desc:<.> Erhöht die Produktion der VerfaultenÄpfel um <b>75</b> %.
		icon:icons[5,5] icons[14,6]
		cost:150 VerfaulterApfel
		passive:multiply yield of VerfaulterApfel by 1.75
		req:150 VerfaulterApfel and UgBLVApfelF6
		class:noBackground
*UgBLVApfelF8
		name:Weicher Apfel
		desc:<.> Erhöht die Produktion der VerfaultenÄpfel um <b>75</b> %.
		icon:icons[5,5] icons[14,7]
		cost:175 VerfaulterApfel
		passive:multiply yield of VerfaulterApfel by 1.75
		req:175 VerfaulterApfel and UgBLVApfelF7
		class:noBackground
*UgBLVApfelF9
		name:Fester Apfel
		desc:<.> Erhöht die Produktion der VerfaultenÄpfel um <b>75</b> %.
		icon:icons[5,5] icons[14,8]
		cost:200 VerfaulterApfel
		passive:multiply yield of VerfaulterApfel by 1.75
		req:200 VerfaulterApfel and UgBLVApfelF8
		class:noBackground
*UgBLVApfelF10
		name:Großer Apfel
		desc:<.> Erhöht die Produktion der VerfaultenÄpfel um <b>75</b> %.
		icon:icons[5,5] icons[14,9]
		cost:225 VerfaulterApfel
		passive:multiply yield of VerfaulterApfel by 1.75
		req:225 VerfaulterApfel and UgBLVApfelF9
		class:noBackground
*UgBLVApfelF11
		name:Ein Stück Apfel
		desc:<.> Erhöht die Produktion der VerfaultenÄpfel um <b>75</b> %.
		icon:icons[5,5] icons[14,10]
		cost:250 VerfaulterApfel
		passive:multiply yield of VerfaulterApfel by 1.75
		req:250 VerfaulterApfel and UgBLVApfelF10
		class:noBackground
*UgBLVApfelF12
		name:Mehliger Apfel
		desc:<.> Erhöht die Produktion der VerfaultenÄpfel um <b>75</b> %.
		icon:icons[5,5] icons[14,11]
		cost:275 VerfaulterApfel
		passive:multiply yield of VerfaulterApfel by 1.75
		req:275 VerfaulterApfel and UgBLVApfelF11
		class:noBackground
*UgBLVApfelF13
		name:Alter Apfel
		desc:<.> Erhöht die Produktion der VerfaultenÄpfel um <b>75</b> %.
		icon:icons[5,5] icons[14,12]
		cost:300 VerfaulterApfel
		passive:multiply yield of VerfaulterApfel by 1.75
		req:300 VerfaulterApfel and UgBLVApfelF12
		class:noBackground
*UgBLVApfelF14
		name:Grüner Apfel
		desc:<.> Erhöht die Produktion der VerfaultenÄpfel um <b>75</b> %.
		icon:icons[5,5] icons[14,13]
		cost:325 VerfaulterApfel
		passive:multiply yield of VerfaulterApfel by 1.75
		req:325 VerfaulterApfel and UgBLVApfelF13
		class:noBackground
*UgBLVApfelF15
		name:Runder Apfel
		desc:<.> Erhöht die Produktion der VerfaultenÄpfel um <b>75</b> %.
		icon:icons[5,5] icons[14,14]
		cost:350 VerfaulterApfel
		passive:multiply yield of VerfaulterApfel by 1.75
		req:350 VerfaulterApfel and UgBLVApfelF14	
		class:noBackground
			

//7


*UgBLANest1
		name:VogelNest
		desc:<.> Erhöht die Produktion der AltenNester um <b>75</b> %.
		icon:iconsb[0,0]
		cost:22400000000 Larven, 2240000000 Nahrung,1000 Territorien
		passive:multiply yield of AltesNest by 1.75
		req:22400000000 Larven:earned
*UgBLANest2
		name:EntenNest
		desc:<.> Erhöht die Produktion der AltenNester um <b>75</b> %.
		icon:iconsb[0,1]
		cost:2240000000000 Larven, 224000000000 Nahrung,10000 Territorien
		passive:multiply yield of AltesNest by 1.75
		req:2240000000000 Larven:earned and UgBLANest1
*UgBLANest3
		name:EulenNest
		desc:<.> Erhöht die Produktion der AltenNester um <b>75</b> %.
		icon:iconsb[0,2]
		cost:224000000000000 Larven, 22400000000000 Nahrung,100000 Territorien
		passive:multiply yield of AltesNest by 1.75
		req:224000000000000 Larven:earned and UgBLANest2
*UgBLANest4
		name:SpatzNest
		desc:<.> Erhöht die Produktion der AltenNester um <b>75</b> %.
		icon:iconsb[0,3]
		cost:22400000000000000 Larven, 2240000000000000 Nahrung,1000000 Territorien
		passive:multiply yield of AltesNest by 1.75
		req:22400000000000000 Larven:earned and UgBLANest3
*UgBLANest5
		name:BaumNest
		desc:<.> Erhöht die Produktion der AltenNester um <b>75</b> %.
		icon:iconsb[0,4]
		cost:2240000000000000000 Larven, 224000000000000000 Nahrung,10000000 Territorien
		passive:multiply yield of AltesNest by 1.75
		req:2240000000000000000 Larven:earned and UgBLANest4
*UgBLANest6
		name:SchwalbenNest
		desc:<.> Erhöht die Produktion der AltenNester um <b>75</b> %.
		icon:iconsb[0,5]
		cost:224000000000000000000 Larven, 22400000000000000000 Nahrung,100000000 Territorien
		passive:multiply yield of AltesNest by 1.75
		req:224000000000000000000 Larven:earned and UgBLANest5
*UgBLANest7
		name:AdlerNest
		desc:<.> Erhöht die Produktion der AltenNester um <b>75</b> %.
		icon:iconsb[0,6]
		cost:22400000000000000000000 Larven, 2240000000000000000000 Nahrung,1000000000 Territorien
		passive:multiply yield of AltesNest by 1.75
		req:22400000000000000000000 Larven:earned and UgBLANest6
*UgBLANest8
		name:FalkenNest
		desc:<.> Erhöht die Produktion der AltenNester um <b>75</b> %.
		icon:iconsb[0,7]
		cost:2240000000000000000000000 Larven, 224000000000000000000000 Nahrung,10000000000 Territorien
		passive:multiply yield of AltesNest by 1.75
		req:2240000000000000000000000 Larven:earned and UgBLANest7
*UgBLANest9
		name:BussardNest
		desc:<.> Erhöht die Produktion der AltenNester um <b>75</b> %.
		icon:iconsb[0,8]
		cost:224000000000000000000000000 Larven, 22400000000000000000000000 Nahrung,100000000000 Territorien
		passive:multiply yield of AltesNest by 1.75
		req:224000000000000000000000000 Larven:earned and UgBLANest8
*UgBLANest10
		name:Verfaulter Jonagold
		desc:<.> Erhöht die Produktion der AltenNester um <b>75</b> %.
		icon:iconsb[0,9]
		cost:22400000000000000000000000000 Larven, 2240000000000000000000000000 Nahrung,1000000000000 Territorien
		passive:multiply yield of AltesNest by 1.75
		req:22400000000000000000000000000 Larven:earned and UgBLANest9
*UgBLANest11
		name:HabichtNest
		desc:<.> Erhöht die Produktion der AltenNester um <b>75</b> %.
		icon:iconsb[0,10]
		cost:2240000000000000000000000000000 Larven, 224000000000000000000000000000 Nahrung,10000000000000 Territorien
		passive:multiply yield of AltesNest by 1.75
		req:2240000000000000000000000000000 Larven:earned and UgBLANest10
*UgBLANest12
		name:HühnerNest
		desc:<.> Erhöht die Produktion der AltenNester um <b>75</b> %.
		icon:iconsb[0,11]
		cost:224000000000000000000000000000000 Larven, 22400000000000000000000000000000 Nahrung,100000000000000 Territorien
		passive:multiply yield of AltesNest by 1.75
		req:224000000000000000000000000000000 Larven:earned and UgBLANest11
		


	


//7
	
*UgBLANestF1
		name:Nestlein
		desc:<.> Erhöht die Produktion der AltenNester um <b>75</b> %.
		icon:icons[5,5] iconsa[20,0]
		cost:10 AlteNester
		passive:multiply yield of AlteNester by 1.75
		req:10 AlteNester
		class:noBackground
*UgBLANestF2
		name:Nest im Baum
		desc:<.> Erhöht die Produktion der AltenNester um <b>75</b> %.
		icon:icons[5,5] iconsa[20,1] 
		cost:25 AlteNester
		passive:multiply yield of AlteNester by 1.75
		req:25 AlteNester and UgBLANestF1
		class:noBackground
*UgBLANestF3
		name:Ovales Nest
		desc:<.> Erhöht die Produktion der AltenNester um <b>75</b> %.
		icon:icons[5,5] iconsa[20,2]
		cost:50 AlteNester
		passive:multiply yield of AlteNester by 1.75
		req:50 AlteNester and UgBLANestF2
		class:noBackground
*UgBLANestF4
		name:Rundes Nest 
		desc:<.> Erhöht die Produktion der AltenNester um <b>75</b> %.
		icon:icons[5,5] iconsa[20,3]
		cost:75 AlteNester
		passive:multiply yield of AlteNester by 1.75
		req:75 AlteNester and UgBLANestF3
		class:noBackground
*UgBLANestF5
		name:Zugiges Nest
		desc:<.> Erhöht die Produktion der AltenNester um <b>75</b> %.
		icon:icons[5,5] iconsa[20,4]
		cost:100 AlteNester
		passive:multiply yield of AlteNester by 1.75
		req:100 AlteNester and UgBLANestF4
		class:noBackground
*UgBLANestF6
		name:Warmes Nest
		desc:<.> Erhöht die Produktion der AltenNester um <b>75</b> %.
		icon:icons[5,5] iconsa[20,5]
		cost:125 AlteNester
		passive:multiply yield of AlteNester by 1.75
		req:125 AlteNester and UgBLANestF5
		class:noBackground
*UgBLANestF7
		name:Löchriges Nest
		desc:<.> Erhöht die Produktion der AltenNester um <b>75</b> %.
		icon:icons[5,5] iconsa[20,6]
		cost:150 AlteNester
		passive:multiply yield of AlteNester by 1.75
		req:150 AlteNester and UgBLANestF6
		class:noBackground
*UgBLANestF8
		name:Kaputtes Nest
		desc:<.> Erhöht die Produktion der AltenNester um <b>75</b> %.
		icon:icons[5,5] iconsa[20,7]
		cost:175 AlteNester
		passive:multiply yield of AlteNester by 1.75
		req:175 AlteNester and UgBLANestF7
		class:noBackground
*UgBLANestF9
		name:Feines Nest
		desc:<.> Erhöht die Produktion der AltenNester um <b>75</b> %.
		icon:icons[5,5] iconsa[20,8]
		cost:200 AlteNester
		passive:multiply yield of AlteNester by 1.75
		req:200 AlteNester and UgBLANestF8
		class:noBackground
*UgBLANestF10
		name:Verstecktes Nest
		desc:<.> Erhöht die Produktion der AltenNester um <b>75</b> %.
		icon:icons[5,5] iconsa[20,9]
		cost:225 AlteNester
		passive:multiply yield of AlteNester by 1.75
		req:225 AlteNester and UgBLANestF9
		class:noBackground
*UgBLANestF11
		name:Verworrenes Nest
		desc:<.> Erhöht die Produktion der AltenNester um <b>75</b> %.
		icon:icons[5,5] iconsa[20,10]
		cost:250 AlteNester
		passive:multiply yield of AlteNester by 1.75
		req:250 AlteNester and UgBLANestF10
		class:noBackground
*UgBLANestF12
		name:Großes Nest
		desc:<.> Erhöht die Produktion der AltenNester um <b>75</b> %.
		icon:icons[5,5] iconsa[20,11]
		cost:275 AlteNester
		passive:multiply yield of AlteNester by 1.75
		req:275 AlteNester and UgBLANestF11
		class:noBackground
*UgBLANestF13
		name:Spatzle Nestle
		desc:<.> Erhöht die Produktion der AltenNester um <b>75</b> %.
		icon:icons[5,5] iconsa[20,12]
		cost:300 AlteNester
		passive:multiply yield of AlteNester by 1.75
		req:300 AlteNester and UgBLANestF12
		class:noBackground
*UgBLANestF14
		name:Hühner Nest
		desc:<.> Erhöht die Produktion der AltenNester um <b>75</b> %.
		icon:icons[5,5] iconsa[20,13]
		cost:325 AlteNester
		passive:multiply yield of AlteNester by 1.75
		req:325 AlteNester and UgBLANestF13
		class:noBackground
*UgBLANestF15
		name:Vogel Nest
		desc:<.> Erhöht die Produktion der AltenNester um <b>75</b> %.
		icon:icons[5,5] iconsa[20,14]
		cost:350 AlteNester
		passive:multiply yield of AlteNester by 1.75
		req:350 AlteNester and UgBLANestF14	
		class:noBackground




	
//8	


*UgBLSchuh1
		name:Sniker
		desc:<.> Erhöht die Produktion der Schuhe um <b>75</b> %.
		icon:iconsb[1,0]
		cost:3584000000 Larven, 358400000 Nahrung,10000000 Territorien
		passive:multiply yield of UeberwucherterSchuh by 1.75
		req:3584000000 Larven:earned
*UgBLSchuh2
		name:Sportschuh
		desc:<.> Erhöht die Produktion der Schuhe um <b>75</b> %.
		icon:iconsb[1,1]
		cost:358400000000 Larven, 35840000000 Nahrung,100000000 Territorien
		passive:multiply yield of UeberwucherterSchuh by 1.75
		req:358400000000 Larven:earned and UgBLSchuh1
*UgBLSchuh3
		name:Pump
		desc:<.> Erhöht die Produktion der Schuhe um <b>75</b> %.
		icon:iconsb[1,2]
		cost:35840000000000 Larven, 3584000000000 Nahrung,1000000000 Territorien
		passive:multiply yield of UeberwucherterSchuh by 1.75
		req:35840000000000 Larven:earned and UgBLSchuh2
*UgBLSchuh4
		name:Ballerina
		desc:<.> Erhöht die Produktion der Schuhe um <b>75</b> %.
		icon:iconsb[1,3]
		cost:3584000000000000 Larven, 358400000000000 Nahrung,10000000000 Territorien
		passive:multiply yield of UeberwucherterSchuh by 1.75
		req:3584000000000000 Larven:earned and UgBLSchuh3
*UgBLSchuh5
		name:Stiefel
		desc:<.> Erhöht die Produktion der Schuhe um <b>75</b> %.
		icon:iconsb[1,4]
		cost:358400000000000000 Larven, 35840000000000000 Nahrung,100000000000 Territorien
		passive:multiply yield of UeberwucherterSchuh by 1.75
		req:358400000000000000 Larven:earned and UgBLSchuh4
*UgBLSchuh6
		name:Sandale
		desc:<.> Erhöht die Produktion der Schuhe um <b>75</b> %.
		icon:iconsb[1,5]
		cost:35840000000000000000 Larven, 3584000000000000000 Nahrung,1000000000000 Territorien
		passive:multiply yield of UeberwucherterSchuh by 1.75
		req:35840000000000000000 Larven:earned and UgBLSchuh5
*UgBLSchuh7
		name:Schnürschuh
		desc:<.> Erhöht die Produktion der Schuhe um <b>75</b> %.
		icon:iconsb[1,6]
		cost:3584000000000000000000 Larven, 358400000000000000000 Nahrung,10000000000000 Territorien
		passive:multiply yield of UeberwucherterSchuh by 1.75
		req:3584000000000000000000 Larven:earned and UgBLSchuh6
*UgBLSchuh8
		name:Gummistiefel
		desc:<.> Erhöht die Produktion der Schuhe um <b>75</b> %.
		icon:iconsb[1,7]
		cost:358400000000000000000000 Larven, 35840000000000000000000 Nahrung,100000000000000 Territorien
		passive:multiply yield of UeberwucherterSchuh by 1.75
		req:358400000000000000000000 Larven:earned and UgBLSchuh7
*UgBLSchuh9
		name:Boots
		desc:<.> Erhöht die Produktion der Schuhe um <b>75</b> %.
		icon:iconsb[1,8]
		cost:35840000000000000000000000 Larven, 3584000000000000000000000 Nahrung,1000000000000000 Territorien
		passive:multiply yield of UeberwucherterSchuh by 1.75
		req:35840000000000000000000000 Larven:earned and UgBLSchuh8
*UgBLSchuh10
		name:Rollschuh
		desc:<.> Erhöht die Produktion der Schuhe um <b>75</b> %.
		icon:iconsb[1,9]
		cost:3584000000000000000000000000 Larven, 358400000000000000000000000 Nahrung,10000000000000000 Territorien
		passive:multiply yield of UeberwucherterSchuh by 1.75
		req:3584000000000000000000000000 Larven:earned and UgBLSchuh9
*UgBLSchuh11
		name:Stieflette
		desc:<.> Erhöht die Produktion der Schuhe um <b>75</b> %.
		icon:iconsb[1,10]
		cost:358400000000000000000000000000 Larven, 35840000000000000000000000000 Nahrung,100000000000000000 Territorien
		passive:multiply yield of UeberwucherterSchuh by 1.75
		req:358400000000000000000000000000 Larven:earned and UgBLSchuh10
*UgBLSchuh12
		name:Hausschuh
		desc:<.> Erhöht die Produktion der Schuhe um <b>75</b> %.
		icon:iconsb[1,11]
		cost:35840000000000000000000000000000 Larven, 3584000000000000000000000000000 Nahrung,1000000000000000000 Territorien
		passive:multiply yield of UeberwucherterSchuh by 1.75
		req:35840000000000000000000000000000 Larven:earned and UgBLSchuh11
		




//8
	
*UgBLSchuhF1
		name:Trockener Schuh
		desc:<.> Erhöht die Produktion der Schuhe um <b>75</b> %.
		icon:icons[5,5] iconsb[2,0]
		cost:10 UeberwucherterSchuh
		passive:multiply yield of UeberwucherterSchuh by 1.75
		req:10 UeberwucherterSchuh
		class:noBackground
*UgBLSchuhF2
		name:Feuchter Schuh
		desc:<.> Erhöht die Produktion der Schuhe um <b>75</b> %.
		icon:icons[5,5] iconsb[2,1] 
		cost:25 UeberwucherterSchuh
		passive:multiply yield of UeberwucherterSchuh by 1.75
		req:25 UeberwucherterSchuh and UgBLSchuhF1
		class:noBackground
*UgBLSchuhF3
		name:Nasser Schuh
		desc:<.> Erhöht die Produktion der Schuhe um <b>75</b> %.
		icon:icons[5,5] iconsb[2,2]
		cost:50 UeberwucherterSchuh
		passive:multiply yield of UeberwucherterSchuh by 1.75
		req:50 UeberwucherterSchuh and UgBLSchuhF2
		class:noBackground
*UgBLSchuhF4
		name:Bunter Schuh
		desc:<.> Erhöht die Produktion der Schuhe um <b>75</b> %.
		icon:icons[5,5] iconsb[2,3]
		cost:75 UeberwucherterSchuh
		passive:multiply yield of UeberwucherterSchuh by 1.75
		req:75 UeberwucherterSchuh and UgBLSchuhF3
		class:noBackground
*UgBLSchuhF5
		name:Spitzer Schuh
		desc:<.> Erhöht die Produktion der Schuhe um <b>75</b> %.
		icon:icons[5,5] iconsb[2,4]
		cost:100 UeberwucherterSchuh
		passive:multiply yield of UeberwucherterSchuh by 1.75
		req:100 UeberwucherterSchuh and UgBLSchuhF4
		class:noBackground
*UgBLSchuhF6
		name:Leder Schuh
		desc:<.> Erhöht die Produktion der Schuhe um <b>75</b> %.
		icon:icons[5,5] iconsb[2,5]
		cost:125 UeberwucherterSchuh
		passive:multiply yield of UeberwucherterSchuh by 1.75
		req:125 UeberwucherterSchuh and UgBLSchuhF5
		class:noBackground
*UgBLSchuhF7
		name:Brauner Schuh
		desc:<.> Erhöht die Produktion der Schuhe um <b>75</b> %.
		icon:icons[5,5] iconsb[2,6]
		cost:150 UeberwucherterSchuh
		passive:multiply yield of UeberwucherterSchuh by 1.75
		req:150 UeberwucherterSchuh and UgBLSchuhF6
		class:noBackground
*UgBLSchuhF8
		name:Alter Schuh
		desc:<.> Erhöht die Produktion der Schuhe um <b>75</b> %.
		icon:icons[5,5] iconsb[2,7]
		cost:175 UeberwucherterSchuh
		passive:multiply yield of UeberwucherterSchuh by 1.75
		req:175 UeberwucherterSchuh and UgBLSchuhF7
		class:noBackground
*UgBLSchuhF9
		name:Eingewachsener Schuh
		desc:<.> Erhöht die Produktion der Schuhe um <b>75</b> %.
		icon:icons[5,5] iconsb[2,8]
		cost:200 UeberwucherterSchuh
		passive:multiply yield of UeberwucherterSchuh by 1.75
		req:200 UeberwucherterSchuh and UgBLSchuhF8
		class:noBackground
*UgBLSchuhF10
		name:Verfaulter Schuh
		desc:<.> Erhöht die Produktion der Schuhe um <b>75</b> %.
		icon:icons[5,5] iconsb[2,9]
		cost:225 UeberwucherterSchuh
		passive:multiply yield of UeberwucherterSchuh by 1.75
		req:225 UeberwucherterSchuh and UgBLSchuhF9
		class:noBackground
*UgBLSchuhF11
		name:Vermoderter Schuh
		desc:<.> Erhöht die Produktion der Schuhe um <b>75</b> %.
		icon:icons[5,5] iconsb[2,10]
		cost:250 UeberwucherterSchuh
		passive:multiply yield of UeberwucherterSchuh by 1.75
		req:250 UeberwucherterSchuh and UgBLSchuhF10
		class:noBackground
*UgBLSchuhF12
		name:Löchriger Schuh
		desc:<.> Erhöht die Produktion der Schuhe um <b>75</b> %.
		icon:icons[5,5] iconsb[2,11]
		cost:275 UeberwucherterSchuh
		passive:multiply yield of UeberwucherterSchuh by 1.75
		req:275 UeberwucherterSchuh and UgBLSchuhF11
		class:noBackground
*UgBLSchuhF13
		name:Zerfetzter Schuh
		desc:<.> Erhöht die Produktion der Schuhe um <b>75</b> %.
		icon:icons[5,5] iconsb[2,12]
		cost:300 UeberwucherterSchuh
		passive:multiply yield of UeberwucherterSchuh by 1.75
		req:300 UeberwucherterSchuh and UgBLSchuhF12
		class:noBackground
*UgBLSchuhF14
		name:Angenagter Schuh
		desc:<.> Erhöht die Produktion der Schuhe um <b>75</b> %.
		icon:icons[5,5] iconsb[2,13]
		cost:325 UeberwucherterSchuh
		passive:multiply yield of UeberwucherterSchuh by 1.75
		req:325 UeberwucherterSchuh and UgBLSchuhF13
		class:noBackground
*UgBLSchuhF15
		name:Zerkratzter Schuh
		desc:<.> Erhöht die Produktion der Schuhe um <b>75</b> %.
		icon:icons[5,5] iconsb[2,14]
		cost:350 UeberwucherterSchuh
		passive:multiply yield of UeberwucherterSchuh by 1.75
		req:350 UeberwucherterSchuh and UgBLSchuhF14	
		class:noBackground
			

//9


*UgBLPizza1
		name:Pizza Margherita
		desc:<.> Erhöht die Produktion der Pizzen um <b>75</b> %.
		icon:iconsb[3,0]
		cost:49560000000 Larven, 4956000000 Nahrung,10000000 Territorien
		passive:multiply yield of Pizza by 1.75
		req:49560000000 Larven:earned
*UgBLPizza2
		name:Pizza Salamie
		desc:<.> Erhöht die Produktion der Pizzen um <b>75</b> %.
		icon:iconsb[3,1]
		cost:4956000000000 Larven, 495600000000 Nahrung,100000000 Territorien
		passive:multiply yield of Pizza by 1.75
		req:4956000000000 Larven:earned and UgBLPizza1
*UgBLPizza3
		name:Pizza Prosciutto
		desc:<.> Erhöht die Produktion der Pizzen um <b>75</b> %.
		icon:iconsb[3,2]
		cost:495600000000000 Larven, 49560000000000 Nahrung,1000000000 Territorien
		passive:multiply yield of Pizza by 1.75
		req:495600000000000 Larven:earned and UgBLPizza2
*UgBLPizza4
		name:Pizza Funghi
		desc:<.> Erhöht die Produktion der Pizzen um <b>75</b> %.
		icon:iconsb[3,3]
		cost:49560000000000000 Larven, 4956000000000000 Nahrung,10000000000 Territorien
		passive:multiply yield of Pizza by 1.75
		req:49560000000000000 Larven:earned and UgBLPizza3
*UgBLPizza5
		name:Pizza Peperoni
		desc:<.> Erhöht die Produktion der Pizzen um <b>75</b> %.
		icon:iconsb[3,4]
		cost:4956000000000000000 Larven, 495600000000000000 Nahrung,100000000000 Territorien
		passive:multiply yield of Pizza by 1.75
		req:4956000000000000000 Larven:earned and UgBLPizza4
*UgBLPizza6
		name:Pizza Quattro Stagion
		desc:<.> Erhöht die Produktion der Pizzen um <b>75</b> %.
		icon:iconsb[3,5]
		cost:495600000000000000000 Larven, 49560000000000000000 Nahrung,1000000000000 Territorien
		passive:multiply yield of Pizza by 1.75
		req:495600000000000000000 Larven:earned and UgBLPizza5
*UgBLPizza7
		name:Pizza Tonno
		desc:<.> Erhöht die Produktion der Pizzen um <b>75</b> %.
		icon:iconsb[3,6]
		cost:49560000000000000000000 Larven, 4956000000000000000000 Nahrung,10000000000000 Territorien
		passive:multiply yield of Pizza by 1.75
		req:49560000000000000000000 Larven:earned and UgBLPizza6
*UgBLPizza8
		name:Pizza Bolognese
		desc:<.> Erhöht die Produktion der Pizzen um <b>75</b> %.
		icon:iconsb[3,7]
		cost:4956000000000000000000000 Larven, 495600000000000000000000 Nahrung,100000000000000 Territorien
		passive:multiply yield of Pizza by 1.75
		req:4956000000000000000000000 Larven:earned and UgBLPizza7
*UgBLPizza9
		name:Pizza Calzone
		desc:<.> Erhöht die Produktion der Pizzen um <b>75</b> %.
		icon:iconsb[3,8]
		cost:495600000000000000000000000 Larven, 49560000000000000000000000 Nahrung,1000000000000000 Territorien
		passive:multiply yield of Pizza by 1.75
		req:495600000000000000000000000 Larven:earned and UgBLPizza8
*UgBLPizza10
		name:Pizza Napoli
		desc:<.> Erhöht die Produktion der Pizzen um <b>75</b> %.
		icon:iconsb[3,9]
		cost:49560000000000000000000000000 Larven, 4956000000000000000000000000 Nahrung,10000000000000000 Territorien
		passive:multiply yield of Pizza by 1.75
		req:49560000000000000000000000000 Larven:earned and UgBLPizza9
*UgBLPizza11
		name:Pizza Verdi
		desc:<.> Erhöht die Produktion der Pizzen um <b>75</b> %.
		icon:iconsb[3,10]
		cost:4956000000000000000000000000000 Larven, 495600000000000000000000000000 Nahrung,100000000000000000 Territorien
		passive:multiply yield of Pizza by 1.75
		req:4956000000000000000000000000000 Larven:earned and UgBLPizza10
*UgBLPizza12
		name:Pizza Vulcano
		desc:<.> Erhöht die Produktion der Pizzen um <b>75</b> %.
		icon:iconsb[3,11]
		cost:495600000000000000000000000000000 Larven, 49560000000000000000000000000000 Nahrung,1000000000000000000 Territorien
		passive:multiply yield of Pizza by 1.75
		req:495600000000000000000000000000000 Larven:earned and UgBLPizza11
		

	


//9
	
*UgBLPizzaF1
		name:Pizza Rustika
		desc:<.> Erhöht die Produktion der Pizzen um <b>75</b> %.
		icon:icons[5,5] iconsb[4,0]
		cost:10 Pizza
		passive:multiply yield of Pizza by 1.75
		req:10 Pizza
		class:noBackground
*UgBLPizzaF2
		name:Pizza La Bella
		desc:<.> Erhöht die Produktion der Pizzen um <b>75</b> %.
		icon:icons[5,5] iconsb[4,1] 
		cost:25 Pizza
		passive:multiply yield of Pizza by 1.75
		req:25 Pizza and UgBLPizzaF1
		class:noBackground
*UgBLPizzaF3
		name:Pizza Peperoniwurst
		desc:<.> Erhöht die Produktion der Pizzen um <b>75</b> %.
		icon:icons[5,5] iconsb[4,2]
		cost:50 Pizza
		passive:multiply yield of Pizza by 1.75
		req:50 Pizza and UgBLPizzaF2
		class:noBackground
*UgBLPizzaF4
		name:Familienpizza
		desc:<.> Erhöht die Produktion der Pizzen um <b>75</b> %.
		icon:icons[5,5] iconsb[4,3]
		cost:75 Pizza
		passive:multiply yield of Pizza by 1.75
		req:75 Pizza and UgBLPizzaF3
		class:noBackground
*UgBLPizzaF5
		name:Pizza alla Panna
		desc:<.> Erhöht die Produktion der Pizzen um <b>75</b> %.
		icon:icons[5,5] iconsb[4,4]
		cost:100 Pizza
		passive:multiply yield of Pizza by 1.75
		req:100 Pizza and UgBLPizzaF4
		class:noBackground
*UgBLPizzaF6
		name:Weiche Pizza
		desc:<.> Erhöht die Produktion der Pizzen um <b>75</b> %.
		icon:icons[5,5] iconsb[4,5]
		cost:125 Pizza
		passive:multiply yield of Pizza by 1.75
		req:125 Pizza and UgBLPizzaF5
		class:noBackground
*UgBLPizzaF7
		name:Matschige Pizza 
		desc:<.> Erhöht die Produktion der Pizzen um <b>75</b> %.
		icon:icons[5,5] iconsb[4,6]
		cost:150 Pizza
		passive:multiply yield of Pizza by 1.75
		req:150 Pizza and UgBLPizzaF6
		class:noBackground
*UgBLPizzaF8
		name:Trockene Pizza
		desc:<.> Erhöht die Produktion der Pizzen um <b>75</b> %.
		icon:icons[5,5] iconsb[4,7]
		cost:175 Pizza
		passive:multiply yield of Pizza by 1.75
		req:175 Pizza and UgBLPizzaF7
		class:noBackground
*UgBLPizzaF9
		name:Knusprige Pizza
		desc:<.> Erhöht die Produktion der Pizzen um <b>75</b> %.
		icon:icons[5,5] iconsb[4,8]
		cost:200 Pizza
		passive:multiply yield of Pizza by 1.75
		req:200 Pizza and UgBLPizzaF8
		class:noBackground
*UgBLPizzaF10
		name:Leckere Pizza
		desc:<.> Erhöht die Produktion der Pizzen um <b>75</b> %.
		icon:icons[5,5] iconsb[4,9]
		cost:225 Pizza
		passive:multiply yield of Pizza by 1.75
		req:225 Pizza and UgBLPizzaF9
		class:noBackground
*UgBLPizzaF11
		name:Faulige Pizza
		desc:<.> Erhöht die Produktion der Pizzen um <b>75</b> %.
		icon:icons[5,5] iconsb[4,10]
		cost:250 Pizza
		passive:multiply yield of Pizza by 1.75
		req:250 Pizza and UgBLPizzaF10
		class:noBackground
*UgBLPizzaF12
		name:Schimmlige Pizza
		desc:<.> Erhöht die Produktion der Pizzen um <b>75</b> %.
		icon:icons[5,5] iconsb[4,11]
		cost:275 Pizza
		passive:multiply yield of Pizza by 1.75
		req:275 Pizza and UgBLPizzaF11
		class:noBackground
*UgBLPizzaF13
		name:Großes Pizza Stück
		desc:<.> Erhöht die Produktion der Pizzen um <b>75</b> %.
		icon:icons[5,5] iconsb[4,12]
		cost:300 Pizza
		passive:multiply yield of Pizza by 1.75
		req:300 Pizza and UgBLPizzaF12
		class:noBackground
*UgBLPizzaF14
		name:Angenagte Pizza
		desc:<.> Erhöht die Produktion der Pizzen um <b>75</b> %.
		icon:icons[5,5] iconsb[4,13]
		cost:325 Pizza
		passive:multiply yield of Pizza by 1.75
		req:325 Pizza and UgBLPizzaF13
		class:noBackground
*UgBLPizzaF15
		name:Pizzakrümel
		desc:<.> Erhöht die Produktion der Pizzen um <b>75</b> %.
		icon:icons[5,5] iconsb[4,14]
		cost:350 Pizza
		passive:multiply yield of Pizza by 1.75
		req:350 Pizza and UgBLPizzaF14	
		class:noBackground
			
		
		

//Insekten Upgrades

	
		
		
// Upgrade Ressource Insekten		
		
		
		

*UgRIBlume1
		name:Ackerwinde
		desc:<.> Erhöht die Produktion von Insekten um <b>1</b> %.
		icon:iconsa[5,0]
		cost:999999 Insekten
		passive:multiply yield of Insekten by 1.01
		req:50000 Insekten:earned
*UgRIBlume2
		name:Azalee
		desc:<.> Erhöht die Produktion von Insekten um <b>1</b> %.
		icon:iconsa[5,1]
		cost:5000000 Insekten
		passive:multiply yield of Insekten by 1.01
		req:250000 Insekten:earned and UgRIBlume1
*UgRIBlume3
		name:Mandelröschen
		desc:<.> Erhöht die Produktion von Insekten um <b>1</b> %.
		icon:iconsa[5,2]
		cost:10000000 Insekten
		passive:multiply yield of Insekten by 1.01
		req:500000 Insekten:earned and UgRIBlume2
*UgRIBlume4
		name:Löwenmaul
		desc:<.> Erhöht die Produktion von Insekten um <b>1</b> %.
		icon:iconsa[5,3]
		cost:50000000 Insekten
		passive:multiply yield of Insekten by 1.01
		req:2500000 Insekten:earned and UgRIBlume3
*UgRIBlume5
		name:Geranie
		desc:<.> Erhöht die Produktion von Insekten um <b>1</b> %.
		icon:iconsa[5,4]
		cost:100000000 Insekten
		passive:multiply yield of Insekten by 1.01
		req:5000000 Insekten:earned and UgRIBlume4
*UgRIBlume6
		name:Aster
		desc:<.> Erhöht die Produktion von Insekten um <b>1</b> %.
		icon:iconsa[5,5]
		cost:500000000 Insekten
		passive:multiply yield of Insekten by 1.01
		req:25000000 Insekten:earned and UgRIBlume5
*UgRIBlume7
		name:Begonie
		desc:<.> Erhöht die Produktion von Insekten um <b>1</b> %.
		icon:iconsa[5,6]
		cost:1000000000 Insekten
		passive:multiply yield of Insekten by 1.01
		req:50000000 Insekten:earned and UgRIBlume6
*UgRIBlume8
		name:Fleißiges Lieschen
		desc:<.> Erhöht die Produktion von Insekten um <b>1</b> %.
		icon:iconsa[5,7]
		cost:5000000000 Insekten
		passive:multiply yield of Insekten by 1.01
		req:250000000 Insekten:earned and UgRIBlume7
*UgRIBlume9
		name:Kornrade
		desc:<.> Erhöht die Produktion von Insekten um <b>1</b> %.
		icon:iconsa[5,8]
		cost:10000000000 Insekten
		passive:multiply yield of Insekten by 1.01
		req:500000000 Insekten:earned and UgRIBlume8
*UgRIBlume10
		name:Rose
		desc:<.> Erhöht die Produktion von Insekten um <b>1</b> %.
		icon:iconsa[5,9]
		cost:50000000000 Insekten
		passive:multiply yield of Insekten by 1.01
		req:2500000000 Insekten:earned and UgRIBlume9
*UgRIBlume11
		name:Wicke
		desc:<.> Erhöht die Produktion von Insekten um <b>1</b> %.
		icon:iconsa[5,10]
		cost:100000000000 Insekten
		passive:multiply yield of Insekten by 1.01
		req:5000000000 Insekten:earned and UgRIBlume10
*UgRIBlume12
		name:Zinnie
		desc:<.> Erhöht die Produktion von Insekten um <b>1</b> %.
		icon:iconsa[5,11]
		cost:500000000000 Insekten
		passive:multiply yield of Insekten by 1.01
		req:25000000000 Insekten:earned and UgRIBlume11
*UgRIBlume13
		name:Strohblume
		desc:<.> Erhöht die Produktion von Insekten um <b>1</b> %.
		icon:iconsa[5,12]
		cost:1000000000000 Insekten
		passive:multiply yield of Insekten by 1.01
		req:50000000000 Insekten:earned and UgRIBlume12

*UgRIBlume14
		name:Kosmee
		desc:<.> Erhöht die Produktion von Insekten um <b>1</b> %.
		icon:iconsa[5,13]
		cost:5000000000000 Insekten
		passive:multiply yield of Insekten by 1.01
		req:250000000000 Insekten:earned and UgRIBlume13

*UgRIBlume15
		name:Iberis
		desc:<.> Erhöht die Produktion von Insekten um <b>1</b> %.
		icon:iconsa[5,14]
		cost:10000000000000 Insekten
		passive:multiply yield of Insekten by 1.01
		req:UgRIBlume14

*UgRIBlume16
		name:Elfenblume
		desc:<.> Erhöht die Produktion von Insekten um <b>1</b> %.
		icon:iconsa[5,15]
		cost:50000000000000 Insekten
		passive:multiply yield of Insekten by 1.01
		req:5000000000000 Insekten:earned and UgRIBlume15

*UgRIBlume17
		name:Blaukissen
		desc:<.> Erhöht die Produktion von Insekten um <b>1</b> %.
		icon:iconsa[5,16]
		cost:100000000000000 Insekten
		passive:multiply yield of Insekten by 1.01
		req:25000000000000 Insekten:earned and UgRIBlume16
*UgRIBlume18
		name:Eibisch
		desc:<.> Erhöht die Produktion von Insekten um <b>1</b> %.
		icon:iconsa[5,17]
		cost:500000000000000 Insekten
		passive:multiply yield of Insekten by 1.01
		req:50000000000000 Insekten:earned and UgRIBlume17
*UgRIBlume19
		name:Glockenblume
		desc:<.> Erhöht die Produktion von Insekten um <b>1</b> %.
		icon:iconsa[5,18]
		cost:1000000000000000 Insekten
		passive:multiply yield of Insekten by 1.01
		req:250000000000000 Insekten:earned and UgRIBlume18
*UgRIBlume20
		name:Eisenhut
		desc:<.> Erhöht die Produktion von Insekten um <b>1</b> %.
		icon:iconsa[5,19]
		cost:5000000000000000 Insekten
		passive:multiply yield of Insekten by 1.01
		req:500000000000000 Insekten:earned and UgRIBlume19
*UgRIBlume21
		name:Schleierkraut
		desc:<.> Erhöht die Produktion von Insekten um <b>1</b> %.
		icon:iconsa[5,20]
		cost:10000000000000000 Insekten
		passive:multiply yield of Insekten by 1.01
		req:2500000000000000 Insekten:earned and UgRIBlume20
		

		
		

*UgRINuss1
		name:Mandeln
        desc:<.> Beim Klicken des Insektes bekommst du <b>2</b> mal so viel!
		icon:iconsa[6,0]
		cost:999999 Insekten
		passive:multiply yield of InsektenButton by 2
		req:50000 Insekten:earned
*UgRINuss2
		name:Cashewkerne
        desc:<.> Beim Klicken des Insektes bekommst du <b>3</b> mal so viel!
		icon:iconsa[6,1]
		cost:5000000 Insekten
		passive:multiply yield of InsektenButton by 3
		req:250000 Insekten:earned and UgRINuss1
*UgRINuss3
		name:Haselnüsse
        desc:<.> Beim Klicken des Insektes bekommst du <b>3</b> mal so viel!
		icon:iconsa[6,2]
		cost:10000000 Insekten
		passive:multiply yield of InsektenButton by 3
		req:500000 Insekten:earned and UgRINuss2
*UgRINuss4
		name:Paranuss
        desc:<.> Beim Klicken des Insektes bekommst du <b>3</b> mal so viel!
		icon:iconsa[6,3]
		cost:50000000 Insekten
		passive:multiply yield of InsektenButton by 3
		req:2500000 Insekten:earned and UgRINuss3
*UgRINuss5
		name:Pakannuss
		desc:<.> Beim Klicken des Insektes bekommst du <b>3</b> mal so viel!
		icon:iconsa[6,4]
		cost:100000000 Insekten
		passive:multiply yield of InsektenButton by 3
		req:5000000 Insekten:earned and UgRINuss4
*UgRINuss6
		name:Pistazien
		desc:<.> Beim Klicken des Insektes bekommst du <b>3</b> mal so viel!
		icon:iconsa[6,5]
		cost:500000000 Insekten
		passive:multiply yield of InsektenButton by 3
		req:25000000 Insekten:earned and UgRINuss5
*UgRINuss7
		name:Macadamianuss
		desc:<.> Beim Klicken des Insektes bekommst du <b>3</b> mal so viel!
		icon:iconsa[6,6]
		cost:1000000000 Insekten
		passive:multiply yield of InsektenButton by 3
		req:50000000 Insekten:earned and UgRINuss6
*UgRINuss8
		name:Walnuss
		desc:<.> Beim Klicken des Insektes bekommst du <b>3</b> mal so viel!
		icon:iconsa[6,7]
		cost:5000000000 Insekten
		passive:multiply yield of InsektenButton by 3
		req:250000000 Insekten:earned and UgRINuss7
*UgRINuss9
		name:Erdnuss
		desc:<.> Beim Klicken des Insektes bekommst du <b>3</b> mal so viel!
		icon:iconsa[6,8]
		cost:10000000000 Insekten
		passive:multiply yield of InsektenButton by 3
		req:500000000 Insekten:earned and UgRINuss8
*UgRINuss10
		name:Eichel
		desc:<.> Beim Klicken des Insektes bekommst du <b>3</b> mal so viel!
		icon:iconsa[6,9]
		cost:50000000000 Insekten
		passive:multiply yield of InsektenButton by 3
		req:2500000000 Insekten:earned and UgRINuss9
*UgRINuss11
		name:Edelkastanie
		desc:<.> Beim Klicken des Insektes bekommst du <b>3</b> mal so viel!
		icon:iconsa[6,10]
		cost:100000000000 Insekten
		passive:multiply yield of InsektenButton by 3
		req:5000000000 Insekten:earned and UgRINuss10
*UgRINuss12
		name:Bucheckern
		desc:<.> Beim Klicken des Insektes bekommst du <b>3</b> mal so viel!
		icon:iconsa[6,11]
		cost:500000000000 Insekten
		passive:multiply yield of InsektenButton by 3
		req:25000000000 Insekten:earned and UgRINuss11
*UgRINuss13
		name:Steinnuss
		desc:<.> Beim Klicken des Insektes bekommst du <b>3</b> mal so viel!
		icon:iconsa[6,12]
		cost:1000000000000 Insekten
		passive:multiply yield of InsektenButton by 3
		req:50000000000 Insekten:earned and UgRINuss12
*UgRINuss14
		name:Kleine Nuss
		desc:<.> Beim Klicken des Insektes bekommst du <b>3</b> mal so viel!
		icon:iconsa[6,13]
		cost:5000000000000 Insekten
		passive:multiply yield of InsektenButton by 3
		req:250000000000 Insekten:earned and UgRINuss13
*UgRINuss15
		name:Dicke Nuss
		desc:<.> Beim Klicken des Insektes bekommst du <b>3</b> mal so viel!
		icon:iconsa[6,14]
		cost:10000000000000 Insekten
		passive:multiply yield of InsektenButton by 3
		req:250000000000 Insekten:earned and UgRINuss14
*UgRINuss16
		name:Große Nuss
		desc:<.> Beim Klicken des Insektes bekommst du <b>3</b> mal so viel!
		icon:iconsa[6,15]
		cost:50000000000000 Insekten
		passive:multiply yield of InsektenButton by 3
		req:5000000000000 Insekten:earned and UgRINuss15
*UgRINuss17
		name:Komische Nuss
		desc:<.> Beim Klicken des Insektes bekommst du <b>3</b> mal so viel!
		icon:iconsa[6,16]
		cost:100000000000000 Insekten
		passive:multiply yield of InsektenButton by 3
		req:25000000000000 Insekten:earned and UgRINuss16
*UgRINuss18
		name:Braune Nuss
		desc:<.> Beim Klicken des Insektes bekommst du <b>3</b> mal so viel!
		icon:iconsa[6,17]
		cost:500000000000000 Insekten
		passive:multiply yield of InsektenButton by 3
		req:50000000000000 Insekten:earned and UgRINuss17
*UgRINuss19
		name:Helle Nuss
		desc:<.> Beim Klicken des Insektes bekommst du <b>3</b> mal so viel!
		icon:iconsa[6,18]
		cost:1000000000000000 Insekten
		passive:multiply yield of InsektenButton by 3
		req:250000000000000 Insekten:earned and UgRINuss18
*UgRINuss20
		name:Weise Nuss
		desc:<.> Beim Klicken des Insektes bekommst du <b>3</b> mal so viel!
		icon:iconsa[6,19]
		cost:5000000000000000 Insekten
		passive:multiply yield of InsektenButton by 3
		req:500000000000000 Insekten:earned and UgRINuss19
*UgRINuss21
		name:Krumme Nuss
		desc:<.> Beim Klicken des Insektes bekommst du <b>3</b> mal so viel!
		icon:iconsa[6,20]
		cost:10000000000000000 Insekten
		passive:multiply yield of InsektenButton by 3
		req:2500000000000000 Insekten:earned and UgRINuss20
		
		


*UgRILegok1
        name:Lego!
        desc:<.> Beim Klicken des Insektes bekommst du <b>1</b> Insekt dazu!
        icon:iconsa[7,0]
        cost:1000 Insekt
        passive:increase yield of InsektenButton by 1
        req:10 Insekt:earned
*UgRILegok2
        name:Schnelles Stapeln!
        desc:<.> Beim Klicken des Insektes bekommst du <b>1</b> Insekt dazu!
        icon:iconsa[7,1]
        cost:10000 Insekt
        passive:increase yield of InsektenButton by 1
        req:100 Insekt:earned and UgRILegok1
*UgRILegok3
        name:Gelber Klotz
        desc:<.> Beim Klicken des Insektes bekommst du <b>1</b> Insekt dazu!
        icon:iconsa[7,2]
        cost:100000 Insekt
        passive:increase yield of InsektenButton by 1
        req:1000 Insekt:earned and UgRILegok2
*UgRILegok4
        name:Grüner Stein
        desc:<.> Beim Klicken des Insektes bekommst du <b>1</b> Insekt dazu!
        icon:iconsa[7,3]
        cost:1000000 Insekt
        passive:increase yield of InsektenButton by 1
        req:10000 Insekt:earned and UgRILegok3
*UgRILegok5
        name:Viel Klackern!
        desc:<.> Beim Klicken des Insektes bekommst du <b>1</b> Insekt dazu!
        icon:iconsa[7,4]
        cost:10000000 Insekt
        passive:increase yield of InsektenButton by 1
        req:100000 Insekt:earned and UgRILegok4
*UgRILegok6
        name:Stapel es!
        desc:<.> Beim Klicken des Insektes bekommst du <b>1</b> Insekt dazu!
        icon:iconsa[7,5]
        cost:100000000 Insekt
        passive:increase yield of InsektenButton by 1
        req:1000000 Insekt:earned and UgRILegok5

				
		


*UgBIAmeise1
		name:Ameisenlimbo
		desc:<.> Erhöht die Produktion der Ameisen um <b>75</b> %.
		icon:icons[0,0] icons[3,0]
		cost:130 Insekten,60 Larven,10 BauMaterial
		passive:multiply yield of Ameise by 1.75
		req:130 Insekten:earned

*UgBIAmeise2
		name:Ameisenrama
		desc:<.> Erhöht die Produktion der Ameisen um <b>75</b> %.
		icon:icons[0,0] icons[3,1]
		cost:13000 Insekten,6000 Larven,1000 BauMaterial
		passive:multiply yield of Ameise by 1.75
		req:13000 Insekten:earned and UgBIAmeise1

*UgBIAmeise3
		name:Ameisenstraße
		desc:<.> Erhöht die Produktion der Ameisen um <b>75</b> %.
		icon:icons[0,0] icons[3,2]
		cost:1300000 Insekten,600000 Larven,100000 BauMaterial
		passive:multiply yield of Ameise by 1.75
		req:1300000 Insekten:earned and UgBIAmeise2

*UgBIAmeise4
		name:Ameisenbrücke
		desc:<.> Erhöht die Produktion der Ameisen um <b>75</b> %.
		icon:icons[0,0] icons[3,3]
		cost:130000000 Insekten,60000000 Larven,10000000 BauMaterial
		passive:multiply yield of Ameise by 1.75
		req:130000000 Insekten:earned and UgBIAmeise3

*UgBIAmeise5
		name:Ameisenhighway
		desc:<.> Erhöht die Produktion der Ameisen um <b>75</b> %.
		icon:icons[0,0] icons[3,4]
		cost:13000000000 Insekten,6000000000 Larven,1000000000 BauMaterial
		passive:multiply yield of Ameise by 1.75
		req:13000000000 Insekten:earned and UgBIAmeise4
		

*UgBIAmeise6
		name:Ameisenkreuzung
		desc:<.> Erhöht die Produktion der Ameisen um <b>75</b> %.
		icon:icons[0,0] icons[3,5]
		cost:1300000000000 Insekten,600000000000 Larven,100000000000 BauMaterial
		passive:multiply yield of Ameise by 1.75
		req:1300000000000 Insekten:earned and UgBIAmeise5

*UgBIAmeise7
		name:Ameisenmonopol
		desc:<.> Erhöht die Produktion der Ameisen um <b>75</b> %.
		icon:icons[0,0] icons[3,6]
		cost:130000000000000 Insekten,60000000000000 Larven,10000000000000 BauMaterial
		passive:multiply yield of Ameise by 1.75
		req:130000000000000 Insekten:earned and UgBIAmeise6

*UgBIAmeise8
		name:Ameisenunterführung
		desc:<.> Erhöht die Produktion der Ameisen um <b>75</b> %.
		icon:icons[0,0] icons[3,7]
		cost:13000000000000000 Insekten,6000000000000000 Larven,1000000000000000 BauMaterial
		passive:multiply yield of Ameise by 1.75
		req:13000000000000000 Insekten:earned and UgBIAmeise7

*UgBIAmeise9
		name:Ameisenboot
		desc:<.> Erhöht die Produktion der Ameisen um <b>75</b> %.
		icon:icons[0,0] icons[3,8]
		cost:1300000000000000000 Insekten,600000000000000000 Larven,100000000000000000 BauMaterial
		passive:multiply yield of Ameise by 1.75
		req:1300000000000000000 Insekten:earned and UgBIAmeise8

*UgBIAmeise10
		name:Ameisensalsa
		desc:<.> Erhöht die Produktion der Ameisen um <b>75</b> %.
		icon:icons[0,0] icons[3,9]
		cost:130000000000000000000 Insekten,60000000000000000000 Larven,10000000000000000000 BauMaterial
		passive:multiply yield of Ameise by 1.75
		req:130000000000000000000 Insekten:earned and UgBIAmeise9
		

*UgBIAmeise11
		name:Ameisensalat
		desc:<.> Erhöht die Produktion der Ameisen um <b>75</b> %.
		icon:icons[0,0] icons[3,10]
		cost:13000000000000000000000 Insekten,6000000000000000000000 Larven,1000000000000000000000 BauMaterial
		passive:multiply yield of Ameise by 1.75
		req:13000000000000000000000 Insekten:earned and UgBIAmeise10
		

*UgBIAmeise12
		name:Ameisenkönig
		desc:<.> Erhöht die Produktion der Ameisen um <b>75</b> %.
		icon:icons[0,0] icons[3,11]
		cost:1300000000000000000000000 Insekten,600000000000000000000000 Larven,100000000000000000000000 BauMaterial
		passive:multiply yield of Ameise by 1.75
		req:1300000000000000000000000 Insekten:earned and UgBIAmeise11
				

*UgBIPAmeise1
		name:AmeisenPanzer I
		desc:<.> Erhöht die Produktion der Ameisen um <b>75</b> %.
		icon:icons[0,0] icons[4,1]
		cost:100 InsektenPanzer
		passive:multiply yield of Ameise by 1.75
		req:1 InsektenPanzer
		class:noBackground

*UgBIPAmeise2
		name:AmeisenPanzer II
		desc:<.> Erhöht die Produktion der Ameisen um <b>75</b> %.
		icon:icons[0,0] icons[4,1]
		cost:10000 InsektenPanzer
		passive:multiply yield of Ameise by 1.75
		req:UgBIPAmeise1
		class:noBackground
	

*UgBIPAmeise3
		name:AmeisenPanzer III
		desc:<.> Erhöht die Produktion der Ameisen um <b>75</b> %.
		icon:icons[0,0] icons[4,1]
		cost:1000000 InsektenPanzer
		passive:multiply yield of Ameise by 1.75
		req:UgBIPAmeise2
		class:noBackground

*UgBIPAmeise4
		name:AmeisenPanzer IV
		desc:<.> Erhöht die Produktion der Ameisen um <b>75</b> %.
		icon:icons[0,0] icons[4,1]
		cost:100000000 InsektenPanzer
		passive:multiply yield of Ameise by 1.75
		req:UgBIPAmeise3
		class:noBackground

*UgBIPAmeise5
		name:AmeisenPanzer V
		desc:<.> Erhöht die Produktion der Ameisen um <b>75</b> %.
		icon:icons[0,0] icons[4,1]
		cost:10000000000 InsektenPanzer
		passive:multiply yield of Ameise by 1.75
		req:UgBIPAmeise4
		class:noBackground

*UgBIPAmeise6
		name:AmeisenPanzer VI
		desc:<.> Erhöht die Produktion der Ameisen um <b>75</b> %.
		icon:icons[0,0] icons[4,1]
		cost:1000000000000 InsektenPanzer
		passive:multiply yield of Ameise by 1.75
		req:UgBIPAmeise5
		class:noBackground

*UgBIPAmeise7
		name:AmeisenPanzer VII
		desc:<.> Erhöht die Produktion der Ameisen um <b>75</b> %.
		icon:icons[0,0] icons[4,1]
		cost:100000000000000 InsektenPanzer
		passive:multiply yield of Ameise by 1.75
		req:UgBIPAmeise6
		class:noBackground

*UgBIPAmeise8
		name:AmeisenPanzer VIII
		desc:<.> Erhöht die Produktion der Ameisen um <b>75</b> %.
		icon:icons[0,0] icons[4,1]
		cost:10000000000000000 InsektenPanzer
		passive:multiply yield of Ameise by 1.75
		req:UgBIPAmeise7
		class:noBackground

*UgBIPAmeise9
		name:AmeisenPanzer IX
		desc:<.> Erhöht die Produktion der Ameisen um <b>75</b> %.
		icon:icons[0,0] icons[4,1]
		cost:1000000000000000000 InsektenPanzer
		passive:multiply yield of Ameise by 1.75
		req:UgBIPAmeise8
		class:noBackground

*UgBIPAmeise10
		name:AmeisenPanzer X
		desc:<.> Erhöht die Produktion der Ameisen um <b>75</b> %.
		icon:icons[0,0] icons[4,1]
		cost:100000000000000000000 InsektenPanzer
		passive:multiply yield of Ameise by 1.75
		req:UgBIPAmeise9
		class:noBackground


				
				
			
				
				
				
*UgBITermite1
		name:Termitenmarsch
		desc:<.> Erhöht die Produktion der Termiten um <b>75</b> %.
		icon:icons[0,1] icons[3,0]
		cost:1348 Insekten,697 Larven,343 BauMaterial
		passive:multiply yield of Termite by 1.75
		req:1400 Insekten:earned and 1 Termite

*UgBITermite2
		name:Termitarium
		desc:<.> Erhöht die Produktion der Termiten um <b>75</b> %.
		icon:icons[0,1] icons[3,1]
		cost:13480000 Insekten,6970000 Larven,3430000 BauMaterial
		passive:multiply yield of Termite by 1.75
		req:14000000 Insekten:earned and UgBITermite1

*UgBITermite3
		name:Termitenkette
		desc:<.> Erhöht die Produktion der Termiten um <b>75</b> %.
		icon:icons[0,1] icons[3,2]
		cost:1348000000 Insekten,697000000 Larven,343000000 BauMaterial
		passive:multiply yield of Termite by 1.75
		req:1400000000 Insekten:earned and UgBITermite2

*UgBITermite4
		name:Termitenpuder
		desc:<.> Erhöht die Produktion der Termiten um <b>75</b> %.
		icon:icons[0,1] icons[3,3]
		cost:134800000000 Insekten,69700000000 Larven,34300000000 BauMaterial
		passive:multiply yield of Termite by 1.75
		req:140000000000 Insekten:earned and UgBITermite3

*UgBITermite5
		name:Termitenwache
		desc:<.> Erhöht die Produktion der Termiten um <b>75</b> %.
		icon:icons[0,1] icons[3,4]
		cost:13480000000000 Insekten,6970000000000 Larven,3430000000000 BauMaterial
		passive:multiply yield of Termite by 1.75
		req:14000000000000 Insekten:earned and UgBITermite4

*UgBITermite6
		name:Termitenmarmelade
		desc:<.> Erhöht die Produktion der Termiten um <b>75</b> %.
		icon:icons[0,1] icons[3,5]
		cost:1348000000000000 Insekten,697000000000000 Larven,343000000000000 BauMaterial
		passive:multiply yield of Termite by 1.75
		req:1400000000000000 Insekten:earned and UgBITermite5

*UgBITermite7
		name:Termitenbrot
		desc:<.> Erhöht die Produktion der Termiten um <b>75</b> %.
		icon:icons[0,1] icons[3,6]
		cost:134800000000000000 Insekten,69700000000000000 Larven,34300000000000000 BauMaterial
		passive:multiply yield of Termite by 1.75
		req:140000000000000000 Insekten:earned and UgBITermite6

*UgBITermite8
		name:Termitenlink
		desc:<.> Erhöht die Produktion der Termiten um <b>75</b> %.
		icon:icons[0,1] icons[3,7]
		cost:13480000000000000000 Insekten,6970000000000000000 Larven,3430000000000000000 BauMaterial
		passive:multiply yield of Termite by 1.75
		req:14000000000000000000 Insekten:earned and UgBITermite7

*UgBITermite9
		name:Termitendisko
		desc:<.> Erhöht die Produktion der Termiten um <b>75</b> %.
		icon:icons[0,1] icons[3,8]
		cost:1348000000000000000000 Insekten,697000000000000000000 Larven,343000000000000000000 BauMaterial
		passive:multiply yield of Termite by 1.75
		req:1400000000000000000000 Insekten:earned and UgBITermite8

*UgBITermite10
		name:Termitenküche
		desc:<.> Erhöht die Produktion der Termiten um <b>75</b> %.
		icon:icons[0,1] icons[3,9]
		cost:134800000000000000000000 Insekten,69700000000000000000000 Larven,34300000000000000000000 BauMaterial
		passive:multiply yield of Termite by 1.75
		req:140000000000000000000000 Insekten:earned and UgBITermite9

*UgBITermite11
		name:Termitenwalzer
		desc:<.> Erhöht die Produktion der Termiten um <b>75</b> %.
		icon:icons[0,1] icons[3,10]
		cost:13480000000000000000000000 Insekten,6970000000000000000000000 Larven,3430000000000000000000000 BauMaterial
		passive:multiply yield of Termite by 1.75
		req:14000000000000000000000000 Insekten:earned and UgBITermite10

*UgBITermite12
		name:Termitenkuscheln
		desc:<.> Erhöht die Produktion der Termiten um <b>75</b> %.
		icon:icons[0,1] icons[3,11]
		cost:1348000000000000000000000000 Insekten,697000000000000000000000000 Larven,343000000000000000000000000 BauMaterial
		passive:multiply yield of Termite by 1.75
		req:1400000000000000000000000000 Insekten:earned and UgBITermite11

		
	


*UgBIPTermite1
		name:TermitenPanzer I
		desc:<.> Erhöht die Produktion der Termiten um <b>75</b> %.
		icon:icons[0,1] icons[4,1]
		cost:1430 InsektenPanzer
		passive:multiply yield of Termite by 1.75
		req:1 InsektenPanzer and 1 Termite
		class:noBackground

*UgBIPTermite2
		name:TermitenPanzer II
		desc:<.> Erhöht die Produktion der Termiten um <b>75</b> %.
		icon:icons[0,1] icons[4,1]
		cost:143000 InsektenPanzer
		passive:multiply yield of Termite by 1.75
		req:UgBIPTermite1
		class:noBackground

*UgBIPTermite3
		name:TermitenPanzer III
		desc:<.> Erhöht die Produktion der Termiten um <b>75</b> %.
		icon:icons[0,1] icons[4,1]
		cost:14300000 InsektenPanzer
		passive:multiply yield of Termite by 1.75
		req:UgBIPTermite2
		class:noBackground

*UgBIPTermite4
		name:TermitenPanzer IV
		desc:<.> Erhöht die Produktion der Termiten um <b>75</b> %.
		icon:icons[0,1] icons[4,1]
		cost:1430000000 InsektenPanzer
		passive:multiply yield of Termite by 1.75
		req:UgBIPTermite3
		class:noBackground

*UgBIPTermite5
		name:TermitenPanzer V
		desc:<.> Erhöht die Produktion der Termiten um <b>75</b> %.
		icon:icons[0,1] icons[4,1]
		cost:143000000000 InsektenPanzer
		passive:multiply yield of Termite by 1.75
		req:UgBIPTermite4
		class:noBackground

*UgBIPTermite6
		name:TermitenPanzer VI
		desc:<.> Erhöht die Produktion der Termiten um <b>75</b> %.
		icon:icons[0,1] icons[4,1]
		cost:14300000000000 InsektenPanzer
		passive:multiply yield of Termite by 1.75
		req:UgBIPTermite5
		class:noBackground

*UgBIPTermite7
		name:TermitenPanzer VII
		desc:<.> Erhöht die Produktion der Termiten um <b>75</b> %.
		icon:icons[0,1] icons[4,1]
		cost:1430000000000000 InsektenPanzer
		passive:multiply yield of Termite by 1.75
		req:UgBIPTermite6
		class:noBackground

*UgBIPTermite8
		name:TermitenPanzer VIII
		desc:<.> Erhöht die Produktion der Termiten um <b>75</b> %.
		icon:icons[0,1] icons[4,1]
		cost:143000000000000000 InsektenPanzer
		passive:multiply yield of Termite by 1.75
		req:UgBIPTermite7
		class:noBackground

*UgBIPTermite9
		name:TermitenPanzer IX
		desc:<.> Erhöht die Produktion der Termiten um <b>75</b> %.
		icon:icons[0,1] icons[4,1]
		cost:14300000000000000000 InsektenPanzer
		passive:multiply yield of Termite by 1.75
		req:UgBIPTermite8
		class:noBackground

*UgBIPTermite10
		name:TermitenPanzer X
		desc:<.> Erhöht die Produktion der Termiten um <b>75</b> %.
		icon:icons[0,1] icons[4,1]
		cost:1430000000000000000000 InsektenPanzer
		passive:multiply yield of Termite by 1.75
		req:UgBIPTermite9
		class:noBackground




*UgBIFliegen1
		name:Fliegenklatsche
		desc:<.> Erhöht die Produktion der Fliegen um <b>75</b> %.
		icon:icons[0,2] icons[3,0]
		cost:14800 Insekten,6800 Larven,3750 BauMaterial
		passive:multiply yield of Fliege by 1.75
		req:14800 Insekten:earned and 1 Fliege

*UgBIFliegen2
		name:Fliegenrumba
		desc:<.> Erhöht die Produktion der Fliegen um <b>75</b> %.
		icon:icons[0,2] icons[3,1]
		cost:1480000 Insekten,680000 Larven,375000 BauMaterial
		passive:multiply yield of Fliege by 1.75
		req:1480000 Insekten:earned and UgBIFliegen1


*UgBIFliegen3
		name:BrummBrummFliege
		desc:<.> Erhöht die Produktion der Fliegen um <b>75</b> %.
		icon:icons[0,2] icons[3,2]
		cost:148000000 Insekten,68000000 Larven,37500000 BauMaterial
		passive:multiply yield of Fliege by 1.75
		req:148000000 Insekten:earned and UgBIFliegen2

*UgBIFliegen4
		name:Fliegenflügel
		desc:<.> Erhöht die Produktion der Fliegen um <b>75</b> %.
		icon:icons[0,2] icons[3,3]
		cost:14800000000 Insekten,6800000000 Larven,3750000000 BauMaterial
		passive:multiply yield of Fliege by 1.75
		req:14800000000 Insekten:earned and UgBIFliegen3

*UgBIFliegen5
		name:Fliegerbrille
		desc:<.> Erhöht die Produktion der Fliegen um <b>75</b> %.
		icon:icons[0,2] icons[3,4]
		cost:1480000000000 Insekten,680000000000 Larven,375000000000 BauMaterial
		passive:multiply yield of Fliege by 1.75
		req:1480000000000 Insekten:earned and UgBIFliegen4

*UgBIFliegen6
		name:Fliegeneier
		desc:<.> Erhöht die Produktion der Fliegen um <b>75</b> %.
		icon:icons[0,2] icons[3,5]
		cost:148000000000000 Insekten,68000000000000 Larven,37500000000000 BauMaterial
		passive:multiply yield of Fliege by 1.75
		req:148000000000000 Insekten:earned and UgBIFliegen5

*UgBIFliegen7
		name:Fliegelarven
		desc:<.> Erhöht die Produktion der Fliegen um <b>75</b> %.
		icon:icons[0,2] icons[3,6]
		cost:14800000000000000 Insekten,6800000000000000 Larven,3750000000000000 BauMaterial
		passive:multiply yield of Fliege by 1.75
		req:14800000000000000 Insekten:earned and UgBIFliegen6

*UgBIFliegen8
		name:Fliegengekreisch
		desc:<.> Erhöht die Produktion der Fliegen um <b>75</b> %.
		icon:icons[0,2] icons[3,7]
		cost:1480000000000000000 Insekten,680000000000000000 Larven,375000000000000000 BauMaterial
		passive:multiply yield of Fliege by 1.75
		req:1480000000000000000 Insekten:earned and UgBIFliegen7

*UgBIFliegen9
		name:Fliegenpaarung
		desc:<.> Erhöht die Produktion der Fliegen um <b>75</b> %.
		icon:icons[0,2] icons[3,8]
		cost:148000000000000000000 Insekten,68000000000000000000 Larven,37500000000000000000 BauMaterial
		passive:multiply yield of Fliege by 1.75
		req:148000000000000000000 Insekten:earned and UgBIFliegen8

*UgBIFliegen10
		name:Fliege in der Suppe
		desc:<.> Erhöht die Produktion der Fliegen um <b>75</b> %.
		icon:icons[0,2] icons[3,9]
		cost:14800000000000000000000 Insekten,6800000000000000000000 Larven,3750000000000000000000 BauMaterial
		passive:multiply yield of Fliege by 1.75
		req:14800000000000000000000 Insekten:earned and UgBIFliegen9

*UgBIFliegen11
		name:Fliegenwein
		desc:<.> Erhöht die Produktion der Fliegen um <b>75</b> %.
		icon:icons[0,2] icons[3,10]
		cost:1480000000000000000000000 Insekten,680000000000000000000000 Larven,375000000000000000000000 BauMaterial
		passive:multiply yield of Fliege by 1.75
		req:1480000000000000000000000 Insekten:earned and UgBIFliegen10

*UgBIFliegen12
		name:Fliegenragou
		desc:<.> Erhöht die Produktion der Fliegen um <b>75</b> %.
		icon:icons[0,2] icons[3,11]
		cost:148000000000000000000000000 Insekten,68000000000000000000000000 Larven,37500000000000000000000000 BauMaterial
		passive:multiply yield of Fliege by 1.75
		req:148000000000000000000000000 Insekten:earned and UgBIFliegen11
				
	





*UgBIPFliege1
		name:FliegenPanzer I
		desc:<.> Erhöht die Produktion der Fliegen um <b>75</b> %.
		icon:icons[0,2] icons[4,1]
		cost:10000 InsektenPanzer
		passive:multiply yield of Fliege by 1.75
		req:1 InsektenPanzer and 1 Fliege
		class:noBackground

*UgBIPFliege2
		name:FliegenPanzer II
		desc:<.> Erhöht die Produktion der Fliegen um <b>75</b> %.
		icon:icons[0,2] icons[4,1]
		cost:1000000 InsektenPanzer
		passive:multiply yield of Fliege by 1.75
		req:UgBIPFliege1
		class:noBackground

*UgBIPFliege3
		name:FliegenPanzer III
		desc:<.> Erhöht die Produktion der Fliegen um <b>75</b> %.
		icon:icons[0,2] icons[4,1]
		cost:100000000 InsektenPanzer
		passive:multiply yield of Fliege by 1.75
		req:UgBIPFliege2
		class:noBackground

*UgBIPFliege4
		name:FliegenPanzer IV
		desc:<.> Erhöht die Produktion der Fliegen um <b>75</b> %.
		icon:icons[0,2] icons[4,1]
		cost:10000000000 InsektenPanzer
		passive:multiply yield of Fliege by 1.75
		req:UgBIPFliege3
		class:noBackground

*UgBIPFliege5
		name:FliegenPanzer V
		desc:<.> Erhöht die Produktion der Fliegen um <b>75</b> %.
		icon:icons[0,2] icons[4,1]
		cost:1000000000000 InsektenPanzer
		passive:multiply yield of Fliege by 1.75
		req:UgBIPFliege4
		class:noBackground

*UgBIPFliege6
		name:FliegenPanzer VI
		desc:<.> Erhöht die Produktion der Fliegen um <b>75</b> %.
		icon:icons[0,2] icons[4,1]
		cost:100000000000000 InsektenPanzer
		passive:multiply yield of Fliege by 1.75
		req:UgBIPFliege5
		class:noBackground

*UgBIPFliege7
		name:FliegenPanzer VII
		desc:<.> Erhöht die Produktion der Fliegen um <b>75</b> %.
		icon:icons[0,2] icons[4,1]
		cost:10000000000000000 InsektenPanzer
		passive:multiply yield of Fliege by 1.75
		req:UgBIPFliege6
		class:noBackground

*UgBIPFliege8
		name:FliegenPanzer VIII
		desc:<.> Erhöht die Produktion der Fliegen um <b>75</b> %.
		icon:icons[0,2] icons[4,1]
		cost:1000000000000000000 InsektenPanzer
		passive:multiply yield of Fliege by 1.75
		req:UgBIPFliege7
		class:noBackground

*UgBIPFliege9
		name:FliegenPanzer IX
		desc:<.> Erhöht die Produktion der Fliegen um <b>75</b> %.
		icon:icons[0,2] icons[4,1]
		cost:100000000000000000000 InsektenPanzer
		passive:multiply yield of Fliege by 1.75
		req:UgBIPFliege8
		class:noBackground

*UgBIPFliege10
		name:FliegenPanzer X
		desc:<.> Erhöht die Produktion der Fliegen um <b>75</b> %.
		icon:icons[0,2] icons[4,1]
		cost:10000000000000000000000 InsektenPanzer
		passive:multiply yield of Fliege by 1.75
		req:UgBIPFliege9
		class:noBackground


	
	
	
	

*UgBIKaefer1
		name:Käfersummen
		desc:<.> Erhöht die Produktion der Käfer um <b>75</b> %.
		icon:icons[0,3] icons[3,0]
		cost:168000 Insekten,84000 Larven, 42000 BauMaterial
		passive:multiply yield of Kaefer by 1.75
		req:168000 Insekten:earned and 1 Kaefer

*UgBIKaefer2
		name:Käferitis
		desc:<.> Erhöht die Produktion der Käfer um <b>75</b> %.
		icon:icons[0,3] icons[3,1]
		cost:16800000 Insekten,8400000 Larven, 4200000 BauMaterial
		passive:multiply yield of Kaefer by 1.75
		req:16800000 Insekten:earned and UgBIKaefer1

*UgBIKaefer3
		name:Käferlolli
		desc:<.> Erhöht die Produktion der Käfer um <b>75</b> %.
		icon:icons[0,3] icons[3,2]
		cost:1680000000 Insekten,840000000 Larven, 420000000 BauMaterial
		passive:multiply yield of Kaefer by 1.75
		req:1680000000 Insekten:earned and UgBIKaefer2

*UgBIKaefer4
		name:Käferkugeln
		desc:<.> Erhöht die Produktion der Käfer um <b>75</b> %.
		icon:icons[0,3] icons[3,3]
		cost:168000000000 Insekten,84000000000 Larven, 42000000000 BauMaterial
		passive:multiply yield of Kaefer by 1.75
		req:168000000000 Insekten:earned and UgBIKaefer3

*UgBIKaefer5
		name:Käfersammlung
		desc:<.> Erhöht die Produktion der Käfer um <b>75</b> %.
		icon:icons[0,3] icons[3,4]
		cost:16800000000000 Insekten,8400000000000 Larven, 4200000000000 BauMaterial
		passive:multiply yield of Kaefer by 1.75
		req:16800000000000 Insekten:earned and UgBIKaefer4

*UgBIKaefer6
		name:Käferrumba
		desc:<.> Erhöht die Produktion der Käfer um <b>75</b> %.
		icon:icons[0,3] icons[3,5]
		cost:1680000000000000 Insekten,840000000000000 Larven, 420000000000000 BauMaterial
		passive:multiply yield of Kaefer by 1.75
		req:1680000000000000 Insekten:earned and UgBIKaefer5

*UgBIKaefer7
		name:Käferhotel
		desc:<.> Erhöht die Produktion der Käfer um <b>75</b> %.
		icon:icons[0,3] icons[3,6]
		cost:168000000000000000 Insekten,84000000000000000 Larven, 42000000000000000 BauMaterial
		passive:multiply yield of Kaefer by 1.75
		req:168000000000000000 Insekten:earned and UgBIKaefer6

*UgBIKaefer8
		name:Käferhuddel
		desc:<.> Erhöht die Produktion der Käfer um <b>75</b> %.
		icon:icons[0,3] icons[3,7]
		cost:16800000000000000000 Insekten,8400000000000000000 Larven, 4200000000000000000 BauMaterial
		passive:multiply yield of Kaefer by 1.75
		req:16800000000000000000 Insekten:earned and UgBIKaefer7

*UgBIKaefer9
		name:Käferpolka
		desc:<.> Erhöht die Produktion der Käfer um <b>75</b> %.
		icon:icons[0,3] icons[3,8]
		cost:1680000000000000000000 Insekten,840000000000000000000 Larven, 420000000000000000000 BauMaterial
		passive:multiply yield of Kaefer by 1.75
		req:1680000000000000000000 Insekten:earned and UgBIKaefer8

*UgBIKaefer10
		name:Käferkäse
		desc:<.> Erhöht die Produktion der Käfer um <b>75</b> %.
		icon:icons[0,3] icons[3,9]
		cost:168000000000000000000000 Insekten,84000000000000000000000 Larven, 42000000000000000000000 BauMaterial
		passive:multiply yield of Kaefer by 1.75
		req:168000000000000000000000 Insekten:earned and UgBIKaefer9

*UgBIKaefer11
		name:Käferbrunch
		desc:<.> Erhöht die Produktion der Käfer um <b>75</b> %.
		icon:icons[0,3] icons[3,10]
		cost:16800000000000000000000000 Insekten,8400000000000000000000000 Larven, 4200000000000000000000000 BauMaterial
		passive:multiply yield of Kaefer by 1.75
		req:16800000000000000000000000 Insekten:earned and UgBIKaefer10

*UgBIKaefer12
		name:Käfergarten
		desc:<.> Erhöht die Produktion der Käfer um <b>75</b> %.
		icon:icons[0,3] icons[3,11]
		cost:1680000000000000000000000000 Insekten,840000000000000000000000000 Larven, 420000000000000000000000000 BauMaterial
		passive:multiply yield of Kaefer by 1.75
		req:1680000000000000000000000000 Insekten:earned and UgBIKaefer11
	




*UgBIPKaefer1
		name:KäferPanzer I
		desc:<.> Erhöht die Produktion der Käfer um <b>75</b> %.
		icon:icons[0,3] icons[4,1]
		cost:175000 InsektenPanzer
		passive:multiply yield of Kaefer by 1.75
		req:1 InsektenPanzer and 1 Kaefer
		class:noBackground

*UgBIPKaefer2
		name:KäferPanzer II
		desc:<.> Erhöht die Produktion der Käfer um <b>75</b> %.
		icon:icons[0,3] icons[4,1]
		cost:17500000 InsektenPanzer
		passive:multiply yield of Kaefer by 1.75
		req:UgBIPKaefer1
		class:noBackground

*UgBIPKaefer3
		name:KäferPanzer III
		desc:<.> Erhöht die Produktion der Käfer um <b>75</b> %.
		icon:icons[0,3] icons[4,1]
		cost:1750000000 InsektenPanzer
		passive:multiply yield of Kaefer by 1.75
		req:UgBIPKaefer2
		class:noBackground

*UgBIPKaefer4
		name:KäferPanzer IV
		desc:<.> Erhöht die Produktion der Käfer um <b>75</b> %.
		icon:icons[0,3] icons[4,1]
		cost:175000000000 InsektenPanzer
		passive:multiply yield of Kaefer by 1.75
		req:UgBIPKaefer3
		class:noBackground

*UgBIPKaefer5
		name:KäferPanzer V
		desc:<.> Erhöht die Produktion der Käfer um <b>75</b> %.
		icon:icons[0,3] icons[4,1]
		cost:17500000000000 InsektenPanzer
		passive:multiply yield of Kaefer by 1.75
		req:UgBIPKaefer4
		class:noBackground

*UgBIPKaefer6
		name:KäferPanzer VI
		desc:<.> Erhöht die Produktion der Käfer um <b>75</b> %.
		icon:icons[0,3] icons[4,1]
		cost:1750000000000000 InsektenPanzer
		passive:multiply yield of Kaefer by 1.75
		req:UgBIPKaefer5
		class:noBackground

*UgBIPKaefer7
		name:KäferPanzer VII
		desc:<.> Erhöht die Produktion der Käfer um <b>75</b> %.
		icon:icons[0,3] icons[4,1]
		cost:175000000000000000 InsektenPanzer
		passive:multiply yield of Kaefer by 1.75
		req:UgBIPKaefer6
		class:noBackground

*UgBIPKaefer8
		name:KäferPanzer VIII
		desc:<.> Erhöht die Produktion der Käfer um <b>75</b> %.
		icon:icons[0,3] icons[4,1]
		cost:17500000000000000000 InsektenPanzer
		passive:multiply yield of Kaefer by 1.75
		req:UgBIPKaefer7
		class:noBackground

*UgBIPKaefer9
		name:KäferPanzer IX
		desc:<.> Erhöht die Produktion der Käfer um <b>75</b> %.
		icon:icons[0,3] icons[4,1]
		cost:1750000000000000000000 InsektenPanzer
		passive:multiply yield of Kaefer by 1.75
		req:UgBIPKaefer8
		class:noBackground

*UgBIPKaefer10
		name:KäferPanzer X
		desc:<.> Erhöht die Produktion der Käfer um <b>75</b> %.
		icon:icons[0,3] icons[4,1]
		cost:175000000000000000000000 InsektenPanzer
		passive:multiply yield of Kaefer by 1.75
		req:UgBIPKaefer9
		class:noBackground





	

	
	
*UgBIBiene1
		name:Sumsebiene
		desc:<.> Erhöht die Produktion der Bienen um <b>75</b> %.
		icon:icons[0,4] icons[3,0]
		cost:17900000 Insekten,8900000 Larven, 5670000 BauMaterial
		passive:multiply yield of Biene by 1.75
		req:17900000 Insekten:earned and 1 Biene

*UgBIBiene2
		name:Bienengelb
		desc:<.> Erhöht die Produktion der Bienen um <b>75</b> %.
		icon:icons[0,4] icons[3,1]
		cost:1790000000 Insekten,890000000 Larven, 567000000 BauMaterial
		passive:multiply yield of Biene by 1.75
		req:1790000000 Insekten:earned and UgBIBiene1

*UgBIBiene3
		name:Bienentreffen
		desc:<.> Erhöht die Produktion der Bienen um <b>75</b> %.
		icon:icons[0,4] icons[3,2]
		cost:179000000000 Insekten,89000000000 Larven, 56700000000 BauMaterial
		passive:multiply yield of Biene by 1.75
		req:179000000000 Insekten:earned and UgBIBiene2

*UgBIBiene4
		name:Bienensirup
		desc:<.> Erhöht die Produktion der Bienen um <b>75</b> %.
		icon:icons[0,4] icons[3,3]
		cost:17900000000000 Insekten,8900000000000 Larven, 5670000000000 BauMaterial
		passive:multiply yield of Biene by 1.75
		req:17900000000000 Insekten:earned and UgBIBiene3

*UgBIBiene5
		name:Bienenchachacha
		desc:<.> Erhöht die Produktion der Bienen um <b>75</b> %.
		icon:icons[0,4] icons[3,4]
		cost:1790000000000000 Insekten,890000000000000 Larven, 567000000000000 BauMaterial
		passive:multiply yield of Biene by 1.75
		req:1790000000000000 Insekten:earned and UgBIBiene4

*UgBIBiene6
		name:Bienemeeting
		desc:<.> Erhöht die Produktion der Bienen um <b>75</b> %.
		icon:icons[0,4] icons[3,5]
		cost:179000000000000000 Insekten,89000000000000000 Larven, 56700000000000000 BauMaterial
		passive:multiply yield of Biene by 1.75
		req:179000000000000000 Insekten:earned and UgBIBiene5

*UgBIBiene7
		name:Bienenstamm
		desc:<.> Erhöht die Produktion der Bienen um <b>75</b> %.
		icon:icons[0,4] icons[3,6]
		cost:17900000000000000000 Insekten,8900000000000000000 Larven, 5670000000000000000 BauMaterial
		passive:multiply yield of Biene by 1.75
		req:17900000000000000000 Insekten:earned and UgBIBiene6

*UgBIBiene8
		name:Bienendorf
		desc:<.> Erhöht die Produktion der Bienen um <b>75</b> %.
		icon:icons[0,4] icons[3,7]
		cost:1790000000000000000000 Insekten,890000000000000000000 Larven, 567000000000000000000 BauMaterial
		passive:multiply yield of Biene by 1.75
		req:1790000000000000000000 Insekten:earned and UgBIBiene7

*UgBIBiene9
		name:Bienenstadt
		desc:<.> Erhöht die Produktion der Bienen um <b>75</b> %.
		icon:icons[0,4] icons[3,8]
		cost:179000000000000000000000 Insekten,89000000000000000000000 Larven, 56700000000000000000000 BauMaterial
		passive:multiply yield of Biene by 1.75
		req:179000000000000000000000 Insekten:earned and UgBIBiene8

*UgBIBiene10
		name:Bienenmonopol
		desc:<.> Erhöht die Produktion der Bienen um <b>75</b> %.
		icon:icons[0,4] icons[3,9]
		cost:17900000000000000000000000 Insekten,8900000000000000000000000 Larven, 5670000000000000000000000 BauMaterial
		passive:multiply yield of Biene by 1.75
		req:17900000000000000000000000 Insekten:earned and UgBIBiene9

*UgBIBiene11
		name:Bienenrisiko
		desc:<.> Erhöht die Produktion der Bienen um <b>75</b> %.
		icon:icons[0,4] icons[3,10]
		cost:1790000000000000000000000000 Insekten,890000000000000000000000000 Larven, 567000000000000000000000000 BauMaterial
		passive:multiply yield of Biene by 1.75
		req:1790000000000000000000000000 Insekten:earned and UgBIBiene10

*UgBIBiene12
		name:Maya
		desc:<.> Erhöht die Produktion der Bienen um <b>75</b> %.
		icon:icons[0,4] icons[3,11]
		cost:179000000000000000000000000000 Insekten,89000000000000000000000000000 Larven, 56700000000000000000000000000 BauMaterial
		passive:multiply yield of Biene by 1.75
		req:179000000000000000000000000000 Insekten:earned and UgBIBiene11







*UgBIPBiene1
		name:BienenPanzer I
		desc:<.> Erhöht die Produktion der Bienen um <b>75</b> %.
		icon:icons[0,4] icons[4,1]
		cost:1710000 InsektenPanzer
		passive:multiply yield of Biene by 1.75
		req:1 InsektenPanzer and 1 Biene
		class:noBackground

*UgBIPBiene2
		name:BienenPanzer II
		desc:<.> Erhöht die Produktion der Bienen um <b>75</b> %.
		icon:icons[0,4] icons[4,1]
		cost:171000000 InsektenPanzer
		passive:multiply yield of Biene by 1.75
		req:UgBIPBiene1
		class:noBackground

*UgBIPBiene3
		name:BienenPanzer III
		desc:<.> Erhöht die Produktion der Bienen um <b>75</b> %.
		icon:icons[0,4] icons[4,1]
		cost:17100000000 InsektenPanzer
		passive:multiply yield of Biene by 1.75
		req:UgBIPBiene2
		class:noBackground

*UgBIPBiene4
		name:BienenPanzer IV
		desc:<.> Erhöht die Produktion der Bienen um <b>75</b> %.
		icon:icons[0,4] icons[4,1]
		cost:1710000000000 InsektenPanzer
		passive:multiply yield of Biene by 1.75
		req:UgBIPBiene3
		class:noBackground

*UgBIPBiene5
		name:BienenPanzer V
		desc:<.> Erhöht die Produktion der Bienen um <b>75</b> %.
		icon:icons[0,4] icons[4,1]
		cost:171000000000000 InsektenPanzer
		passive:multiply yield of Biene by 1.75
		req:UgBIPBiene4
		class:noBackground

*UgBIPBiene6
		name:BienenPanzer VI
		desc:<.> Erhöht die Produktion der Bienen um <b>75</b> %.
		icon:icons[0,4] icons[4,1]
		cost:17100000000000000 InsektenPanzer
		passive:multiply yield of Biene by 1.75
		req:UgBIPBiene5
		class:noBackground

*UgBIPBiene7
		name:BienenPanzer VII
		desc:<.> Erhöht die Produktion der Bienen um <b>75</b> %.
		icon:icons[0,4] icons[4,1]
		cost:1710000000000000000 InsektenPanzer
		passive:multiply yield of Biene by 1.75
		req:UgBIPBiene6
		class:noBackground

*UgBIPBiene8
		name:BienenPanzer VIII
		desc:<.> Erhöht die Produktion der Bienen um <b>75</b> %.
		icon:icons[0,4] icons[4,1]
		cost:171000000000000000000 InsektenPanzer
		passive:multiply yield of Biene by 1.75
		req:UgBIPBiene7
		class:noBackground

*UgBIPBiene9
		name:BienenPanzer IX
		desc:<.> Erhöht die Produktion der Bienen um <b>75</b> %.
		icon:icons[0,4] icons[4,1]
		cost:17100000000000000000000 InsektenPanzer
		passive:multiply yield of Biene by 1.75
		req:UgBIPBiene8
		class:noBackground

*UgBIPBiene10
		name:BienenPanzer X
		desc:<.> Erhöht die Produktion der Bienen um <b>75</b> %.
		icon:icons[0,4] icons[4,1]
		cost:1710000000000000000000000 InsektenPanzer
		passive:multiply yield of Biene by 1.75
		req:UgBIPBiene9
		class:noBackground


		
		


*UgBIRoteAmeise1
		name:RoteAmeisenSalat
		desc:<.> Erhöht die Produktion der RotenAmeisen um <b>75</b> %.
		icon:icons[0,5] icons[3,0]
		cost:195900000 Insekten,98700000 Larven, 47000000 BauMaterial
		passive:multiply yield of RoteAmeise by 1.75
		req:195900000 Insekten:earned and 1 RoteAmeise

*UgBIRoteAmeise2
		name:RoteAmeisenStraße
		desc:<.> Erhöht die Produktion der RotenAmeisen um <b>75</b> %.
		icon:icons[0,5] icons[3,1]
		cost:19590000000 Insekten,9870000000 Larven, 4700000000 BauMaterial
		passive:multiply yield of RoteAmeise by 1.75
		req:19590000000 Insekten:earned and UgBIRoteAmeise1

*UgBIRoteAmeise3
		name:RoteAmeisenSpur
		desc:<.> Erhöht die Produktion der RotenAmeisen um <b>75</b> %.
		icon:icons[0,5] icons[3,2]
		cost:1959000000000 Insekten,987000000000 Larven, 470000000000 BauMaterial
		passive:multiply yield of RoteAmeise by 1.75
		req:1959000000000 Insekten:earned and UgBIRoteAmeise2

*UgBIRoteAmeise4
		name:RoteAmeisenFutter
		desc:<.> Erhöht die Produktion der RotenAmeisen um <b>75</b> %.
		icon:icons[0,5] icons[3,3]
		cost:195900000000000 Insekten,98700000000000 Larven, 47000000000000 BauMaterial
		passive:multiply yield of RoteAmeise by 1.75
		req:195900000000000 Insekten:earned and UgBIRoteAmeise3

*UgBIRoteAmeise5
		name:RoteAmeisenGift
		desc:<.> Erhöht die Produktion der RotenAmeisen um <b>75</b> %.
		icon:icons[0,5] icons[3,4]
		cost:19590000000000000 Insekten,9870000000000000 Larven, 4700000000000000 BauMaterial
		passive:multiply yield of RoteAmeise by 1.75
		req:19590000000000000 Insekten:earned and UgBIRoteAmeise4

*UgBIRoteAmeise6
		name:RoteAmeisenBrücke
		desc:<.> Erhöht die Produktion der RotenAmeisen um <b>75</b> %.
		icon:icons[0,5] icons[3,5]
		cost:1959000000000000000 Insekten,987000000000000000 Larven, 470000000000000000 BauMaterial
		passive:multiply yield of RoteAmeise by 1.75
		req:1959000000000000000 Insekten:earned and UgBIRoteAmeise5

*UgBIRoteAmeise7
		name:RoteAmeisenBrüter
		desc:<.> Erhöht die Produktion der RotenAmeisen um <b>75</b> %.
		icon:icons[0,5] icons[3,6]
		cost:195900000000000000000 Insekten,98700000000000000000 Larven, 47000000000000000000 BauMaterial
		passive:multiply yield of RoteAmeise by 1.75
		req:195900000000000000000 Insekten:earned and UgBIRoteAmeise6

*UgBIRoteAmeise8
		name:RoteAmeisenPrinzessin
		desc:<.> Erhöht die Produktion der RotenAmeisen um <b>75</b> %.
		icon:icons[0,5] icons[3,7]
		cost:19590000000000000000000 Insekten,9870000000000000000000 Larven, 4700000000000000000000 BauMaterial
		passive:multiply yield of RoteAmeise by 1.75
		req:19590000000000000000000 Insekten:earned and UgBIRoteAmeise7

*UgBIRoteAmeise9
		name:RoteAmeisenSoldat
		desc:<.> Erhöht die Produktion der RotenAmeisen um <b>75</b> %.
		icon:icons[0,5] icons[3,8]
		cost:1959000000000000000000000 Insekten,987000000000000000000000 Larven, 470000000000000000000000 BauMaterial
		passive:multiply yield of RoteAmeise by 1.75
		req:1959000000000000000000000 Insekten:earned and UgBIRoteAmeise8

*UgBIRoteAmeise10
		name:RoteAmeisenArbeiter
		desc:<.> Erhöht die Produktion der RotenAmeisen um <b>75</b> %.
		icon:icons[0,5] icons[3,9]
		cost:195900000000000000000000000 Insekten,98700000000000000000000000 Larven, 47000000000000000000000000 BauMaterial
		passive:multiply yield of RoteAmeise by 1.75
		req:195900000000000000000000000 Insekten:earned and UgBIRoteAmeise9

*UgBIRoteAmeise11
		name:RoteAmeisenWache
		desc:<.> Erhöht die Produktion der RotenAmeisen um <b>75</b> %.
		icon:icons[0,5] icons[3,10]
		cost:19590000000000000000000000000 Insekten,9870000000000000000000000000 Larven, 4700000000000000000000000000 BauMaterial
		passive:multiply yield of RoteAmeise by 1.75
		req:19590000000000000000000000000 Insekten:earned and UgBIRoteAmeise10

*UgBIRoteAmeise12
		name:Rotes Treiben
		desc:<.> Erhöht die Produktion der RotenAmeisen um <b>75</b> %.
		icon:icons[0,5] icons[3,11]
		cost:1959000000000000000000000000000 Insekten,987000000000000000000000000000 Larven, 470000000000000000000000000000 BauMaterial
		passive:multiply yield of RoteAmeise by 1.75
		req:1959000000000000000000000000000 Insekten:earned and UgBIRoteAmeise11
		
		


*UgBIPRoteAmeise1
		name:RoteAmeisenPanzer I
		desc:<.> Erhöht die Produktion der RotenAmeisen um <b>75</b> %.
		icon:icons[0,5] icons[4,1]
		cost:19200000 InsektenPanzer
		passive:multiply yield of RoteAmeise by 1.75
		req:1 InsektenPanzer and 1 RoteAmeise
		class:noBackground

*UgBIPRoteAmeise2
		name:RoteAmeisenPanzer II
		desc:<.> Erhöht die Produktion der RotenAmeisen um <b>75</b> %.
		icon:icons[0,5] icons[4,1]
		cost:1920000000 InsektenPanzer
		passive:multiply yield of RoteAmeise by 1.75
		req:UgBIPRoteAmeise1
		class:noBackground

*UgBIPRoteAmeise3
		name:RoteAmeisenPanzer III
		desc:<.> Erhöht die Produktion der RotenAmeisen um <b>75</b> %.
		icon:icons[0,5] icons[4,1]
		cost:192000000000 InsektenPanzer
		passive:multiply yield of RoteAmeise by 1.75
		req:UgBIPRoteAmeise2
		class:noBackground

*UgBIPRoteAmeise4
		name:RoteAmeisenPanzer IV
		desc:<.> Erhöht die Produktion der RotenAmeisen um <b>75</b> %.
		icon:icons[0,5] icons[4,1]
		cost:19200000000000 InsektenPanzer
		passive:multiply yield of RoteAmeise by 1.75
		req:UgBIPRoteAmeise3
		class:noBackground

*UgBIPRoteAmeise5
		name:RoteAmeisenPanzer V
		desc:<.> Erhöht die Produktion der RotenAmeisen um <b>75</b> %.
		icon:icons[0,5] icons[4,1]
		cost:1920000000000000 InsektenPanzer
		passive:multiply yield of RoteAmeise by 1.75
		req:UgBIPRoteAmeise4
		class:noBackground

*UgBIPRoteAmeise6
		name:RoteAmeisenPanzer VI
		desc:<.> Erhöht die Produktion der RotenAmeisen um <b>75</b> %.
		icon:icons[0,5] icons[4,1]
		cost:192000000000000000 InsektenPanzer
		passive:multiply yield of RoteAmeise by 1.75
		req:UgBIPRoteAmeise5
		class:noBackground

*UgBIPRoteAmeise7
		name:RoteAmeisenPanzer VII
		desc:<.> Erhöht die Produktion der RotenAmeisen um <b>75</b> %.
		icon:icons[0,5] icons[4,1]
		cost:19200000000000000000 InsektenPanzer
		passive:multiply yield of RoteAmeise by 1.75
		req:UgBIPRoteAmeise6
		class:noBackground

*UgBIPRoteAmeise8
		name:RoteAmeisenPanzer VIII
		desc:<.> Erhöht die Produktion der RotenAmeisen um <b>75</b> %.
		icon:icons[0,5] icons[4,1]
		cost:1920000000000000000000 InsektenPanzer
		passive:multiply yield of RoteAmeise by 1.75
		req:UgBIPRoteAmeise7
		class:noBackground

*UgBIPRoteAmeise9
		name:RoteAmeisenPanzer IX
		desc:<.> Erhöht die Produktion der RotenAmeisen um <b>75</b> %.
		icon:icons[0,5] icons[4,1]
		cost:192000000000000000000000 InsektenPanzer
		passive:multiply yield of RoteAmeise by 1.75
		req:UgBIPRoteAmeise8
		class:noBackground

*UgBIPRoteAmeise10
		name:RoteAmeisenPanzer X
		desc:<.> Erhöht die Produktion der RotenAmeisen um <b>75</b> %.
		icon:icons[0,5] icons[4,1]
		cost:10000000000 InsektenPanzer
		passive:multiply yield of RoteAmeise by 1.75
		req:UgBIPRoteAmeise9
		class:noBackground





*UgBIGrosserKaefer1
		name:BockKäfer
		desc:<.> Erhöht die Produktion der GroßenKäfer um <b>75</b> %.
		icon:icons[0,6] icons[3,0]
		cost:2799000000 Insekten,1399000000 Larven, 699000000 BauMaterial
		passive:multiply yield of GrosserKaefer by 1.75
		req:2799000000 Insekten:earned and 1 GrosserKaefer

*UgBIGrosserKaefer2
		name:SchwarzKäfer
		desc:<.> Erhöht die Produktion der GroßenKäfer um <b>75</b> %.
		icon:icons[0,6] icons[3,1]
		cost:279900000000 Insekten,139900000000 Larven, 69900000000 BauMaterial
		passive:multiply yield of GrosserKaefer by 1.75
		req:279900000000 Insekten:earned and UgBIGrosserKaefer1

*UgBIGrosserKaefer3
		name:Laufkäfer
		desc:<.> Erhöht die Produktion der GroßenKäfer um <b>75</b> %.
		icon:icons[0,6] icons[3,2]
		cost:27990000000000 Insekten,13990000000000 Larven, 6990000000000 BauMaterial
		passive:multiply yield of GrosserKaefer by 1.75
		req:27990000000000 Insekten:earned and UgBIGrosserKaefer2

*UgBIGrosserKaefer4
		name:Speckkäfer
		desc:<.> Erhöht die Produktion der GroßenKäfer um <b>75</b> %.
		icon:icons[0,6] icons[3,3]
		cost:2799000000000000 Insekten,1399000000000000 Larven, 699000000000000 BauMaterial
		passive:multiply yield of GrosserKaefer by 1.75
		req:2799000000000000 Insekten:earned and UgBIGrosserKaefer3

*UgBIGrosserKaefer5
		name:Brotkäfer
		desc:<.> Erhöht die Produktion der GroßenKäfer um <b>75</b> %.
		icon:icons[0,6] icons[3,4]
		cost:279900000000000000 Insekten,139900000000000000 Larven, 69900000000000000 BauMaterial
		passive:multiply yield of GrosserKaefer by 1.75
		req:279900000000000000 Insekten:earned and UgBIGrosserKaefer4

*UgBIGrosserKaefer6
		name:Blatthornkäfer
		desc:<.> Erhöht die Produktion der GroßenKäfer um <b>75</b> %.
		icon:icons[0,6] icons[3,5]
		cost:27990000000000000000 Insekten,13990000000000000000 Larven, 6990000000000000000 BauMaterial
		passive:multiply yield of GrosserKaefer by 1.75
		req:27990000000000000000 Insekten:earned and UgBIGrosserKaefer5

*UgBIGrosserKaefer7
		name:Schnellkäfer
		desc:<.> Erhöht die Produktion der GroßenKäfer um <b>75</b> %.
		icon:icons[0,6] icons[3,6]
		cost:2799000000000000000000 Insekten,1399000000000000000000 Larven, 699000000000000000000 BauMaterial
		passive:multiply yield of GrosserKaefer by 1.75
		req:2799000000000000000000 Insekten:earned and UgBIGrosserKaefer6

*UgBIGrosserKaefer8
		name:Ölkäfer
		desc:<.> Erhöht die Produktion der GroßenKäfer um <b>75</b> %.
		icon:icons[0,6] icons[3,7]
		cost:279900000000000000000000 Insekten,139900000000000000000000 Larven, 69900000000000000000000 BauMaterial
		passive:multiply yield of GrosserKaefer by 1.75
		req:279900000000000000000000 Insekten:earned and UgBIGrosserKaefer7

*UgBIGrosserKaefer9
		name:Flohkäfer
		desc:<.> Erhöht die Produktion der GroßenKäfer um <b>75</b> %.
		icon:icons[0,6] icons[3,8]
		cost:27990000000000000000000000 Insekten,13990000000000000000000000 Larven, 6990000000000000000000000 BauMaterial
		passive:multiply yield of GrosserKaefer by 1.75
		req:27990000000000000000000000 Insekten:earned and UgBIGrosserKaefer8

*UgBIGrosserKaefer10
		name:Aaskäfer
		desc:<.> Erhöht die Produktion der GroßenKäfer um <b>75</b> %.
		icon:icons[0,6] icons[3,9]
		cost:2799000000000000000000000000 Insekten,1399000000000000000000000000 Larven, 699000000000000000000000000 BauMaterial
		passive:multiply yield of GrosserKaefer by 1.75
		req:2799000000000000000000000000 Insekten:earned and UgBIGrosserKaefer9

*UgBIGrosserKaefer11
		name:Buntkäfer
		desc:<.> Erhöht die Produktion der GroßenKäfer um <b>75</b> %.
		icon:icons[0,6] icons[3,10]
		cost:279900000000000000000000000000 Insekten,139900000000000000000000000000 Larven, 69900000000000000000000000000 BauMaterial
		passive:multiply yield of GrosserKaefer by 1.75
		req:279900000000000000000000000000 Insekten:earned and UgBIGrosserKaefer10

*UgBIGrosserKaefer12
		name:Scarabaeos
		desc:<.> Erhöht die Produktion der GroßenKäfer um <b>75</b> %.
		icon:icons[0,6] icons[3,11]
		cost:27990000000000000000000000000000 Insekten,13990000000000000000000000000000 Larven, 6990000000000000000000000000000 BauMaterial
		passive:multiply yield of GrosserKaefer by 1.75
		req:27990000000000000000000000000000 Insekten:earned and UgBIGrosserKaefer11

		
		

		




*UgBIPGrosserKaefer1
		name:GroßerKäferPanzer I
		desc:<.> Erhöht die Produktion der GroßenKäfer um <b>75</b> %.
		icon:icons[0,6] icons[4,1]
		cost:275000000 InsektenPanzer
		passive:multiply yield of GrosserKaefer by 1.75
		req:1 InsektenPanzer and 1 GrosserKaefer
		class:noBackground

*UgBIPGrosserKaefer2
		name:GroßerKäferPanzer II
		desc:<.> Erhöht die Produktion der GroßenKäfer um <b>75</b> %.
		icon:icons[0,6] icons[4,1]
		cost:27500000000 InsektenPanzer
		passive:multiply yield of GrosserKaefer by 1.75
		req:UgBIPGrosserKaefer1
		class:noBackground

*UgBIPGrosserKaefer3
		name:GroßerKäferPanzer III
		desc:<.> Erhöht die Produktion der GroßenKäfer um <b>75</b> %.
		icon:icons[0,6] icons[4,1]
		cost:2750000000000 InsektenPanzer
		passive:multiply yield of GrosserKaefer by 1.75
		req:UgBIPGrosserKaefer2
		class:noBackground

*UgBIPGrosserKaefer4
		name:GroßerKäferPanzer IV
		desc:<.> Erhöht die Produktion der GroßenKäfer um <b>75</b> %.
		icon:icons[0,6] icons[4,1]
		cost:275000000000000 InsektenPanzer
		passive:multiply yield of GrosserKaefer by 1.75
		req:UgBIPGrosserKaefer3
		class:noBackground

*UgBIPGrosserKaefer5
		name:GroßerKäferPanzer V
		desc:<.> Erhöht die Produktion der GroßenKäfer um <b>75</b> %.
		icon:icons[0,6] icons[4,1]
		cost:27500000000000000 InsektenPanzer
		passive:multiply yield of GrosserKaefer by 1.75
		req:UgBIPGrosserKaefer4
		class:noBackground

*UgBIPGrosserKaefer6
		name:GroßerKäferPanzer VI
		desc:<.> Erhöht die Produktion der GroßenKäfer um <b>75</b> %.
		icon:icons[0,6] icons[4,1]
		cost:2750000000000000000 InsektenPanzer
		passive:multiply yield of GrosserKaefer by 1.75
		req:UgBIPGrosserKaefer5
		class:noBackground

*UgBIPGrosserKaefer7
		name:GroßerKäferPanzer VII
		desc:<.> Erhöht die Produktion der GroßenKäfer um <b>75</b> %.
		icon:icons[0,6] icons[4,1]
		cost:275000000000000000000 InsektenPanzer
		passive:multiply yield of GrosserKaefer by 1.75
		req:UgBIPGrosserKaefer6
		class:noBackground

*UgBIPGrosserKaefer8
		name:GroßerKäferPanzer VIII
		desc:<.> Erhöht die Produktion der GroßenKäfer um <b>75</b> %.
		icon:icons[0,6] icons[4,1]
		cost:27500000000000000000000 InsektenPanzer
		passive:multiply yield of GrosserKaefer by 1.75
		req:UgBIPGrosserKaefer7
		class:noBackground

*UgBIPGrosserKaefer9
		name:GroßerKäferPanzer IX
		desc:<.> Erhöht die Produktion der GroßenKäfer um <b>75</b> %.
		icon:icons[0,6] icons[4,1]
		cost:2750000000000000000000000 InsektenPanzer
		passive:multiply yield of GrosserKaefer by 1.75
		req:UgBIPGrosserKaefer8
		class:noBackground

*UgBIPGrosserKaefer10
		name:GroßerKäferPanzer X
		desc:<.> Erhöht die Produktion der GroßenKäfer um <b>75</b> %.
		icon:icons[0,6] icons[4,1]
		cost:275000000000000000000000000 InsektenPanzer
		passive:multiply yield of GrosserKaefer by 1.75
		req:UgBIPGrosserKaefer9
		class:noBackground






*UgBISchmetterling1
		name:Feuerfalter
		desc:<.> Erhöht die Produktion der Schmetterlinge um <b>75</b> %.
		icon:icons[0,7] icons[3,0]
		cost:42000000000 Insekten,21000000000 Larven, 10500000000 BauMaterial
		passive:multiply yield of Schmetterling by 1.75
		req:42000000000 Insekten:earned and 1 Schmetterling

*UgBISchmetterling2
		name:Gabelschwanz
		desc:<.> Erhöht die Produktion der Schmetterlinge um <b>75</b> %.
		icon:icons[0,7] icons[3,1]
		cost:4200000000000 Insekten,2100000000000 Larven, 1050000000000 BauMaterial
		passive:multiply yield of Schmetterling by 1.75
		req:4200000000000 Insekten:earned and UgBISchmetterling1

*UgBISchmetterling3
		name:Mohrenfalter
		desc:<.> Erhöht die Produktion der Schmetterlinge um <b>75</b> %.
		icon:icons[0,7] icons[3,2]
		cost:420000000000000 Insekten,210000000000000 Larven, 105000000000000 BauMaterial
		passive:multiply yield of Schmetterling by 1.75
		req:420000000000000 Insekten:earned and UgBISchmetterling2

*UgBISchmetterling4
		name:Schillerfalter
		desc:<.> Erhöht die Produktion der Schmetterlinge um <b>75</b> %.
		icon:icons[0,7] icons[3,3]
		cost:42000000000000000 Insekten,21000000000000000 Larven, 10500000000000000 BauMaterial
		passive:multiply yield of Schmetterling by 1.75
		req:42000000000000000 Insekten:earned and UgBISchmetterling3

*UgBISchmetterling5
		name:Nachtpfauenauge
		desc:<.> Erhöht die Produktion der Schmetterlinge um <b>75</b> %.
		icon:icons[0,7] icons[3,4]
		cost:4200000000000000000 Insekten,2100000000000000000 Larven, 1050000000000000000 BauMaterial
		passive:multiply yield of Schmetterling by 1.75
		req:4200000000000000000 Insekten:earned and UgBISchmetterling4

*UgBISchmetterling6
		name:Schneckenspinner
		desc:<.> Erhöht die Produktion der Schmetterlinge um <b>75</b> %.
		icon:icons[0,7] icons[3,5]
		cost:420000000000000000000 Insekten,210000000000000000000 Larven, 105000000000000000000 BauMaterial
		passive:multiply yield of Schmetterling by 1.75
		req:420000000000000000000 Insekten:earned and UgBISchmetterling5

*UgBISchmetterling7
		name:Bunteulchen
		desc:<.> Erhöht die Produktion der Schmetterlinge um <b>75</b> %.
		icon:icons[0,7] icons[3,6]
		cost:42000000000000000000000 Insekten,21000000000000000000000 Larven, 10500000000000000000000 BauMaterial
		passive:multiply yield of Schmetterling by 1.75
		req:42000000000000000000000 Insekten:earned and UgBISchmetterling6

*UgBISchmetterling8
		name:Ligustenwickler
		desc:<.> Erhöht die Produktion der Schmetterlinge um <b>75</b> %.
		icon:icons[0,7] icons[3,7]
		cost:4200000000000000000000000 Insekten,2100000000000000000000000 Larven, 1050000000000000000000000 BauMaterial
		passive:multiply yield of Schmetterling by 1.75
		req:4200000000000000000000000 Insekten:earned and UgBISchmetterling7

*UgBISchmetterling9
		name:Dickkopffalter
		desc:<.> Erhöht die Produktion der Schmetterlinge um <b>75</b> %.
		icon:icons[0,7] icons[3,8]
		cost:420000000000000000000000000 Insekten,210000000000000000000000000 Larven, 105000000000000000000000000 BauMaterial
		passive:multiply yield of Schmetterling by 1.75
		req:420000000000000000000000000 Insekten:earned and UgBISchmetterling8

*UgBISchmetterling10
		name:Pantherspanner
		desc:<.> Erhöht die Produktion der Schmetterlinge um <b>75</b> %.
		icon:icons[0,7] icons[3,9]
		cost:42000000000000000000000000000 Insekten,21000000000000000000000000000 Larven, 10500000000000000000000000000 BauMaterial
		passive:multiply yield of Schmetterling by 1.75
		req:42000000000000000000000000000 Insekten:earned and UgBISchmetterling9

*UgBISchmetterling11
		name:Purpurzünsler
		desc:<.> Erhöht die Produktion der Schmetterlinge um <b>75</b> %.
		icon:icons[0,7] icons[3,10]
		cost:4200000000000000000000000000000 Insekten,2100000000000000000000000000000 Larven, 1050000000000000000000000000000 BauMaterial
		passive:multiply yield of Schmetterling by 1.75
		req:4200000000000000000000000000000 Insekten:earned and UgBISchmetterling10

*UgBISchmetterling12
		name:Gelbe Tigermotte
		desc:<.> Erhöht die Produktion der Schmetterlinge um <b>75</b> %.
		icon:icons[0,7] icons[3,11]
		cost:420000000000000000000000000000000 Insekten,210000000000000000000000000000000 Larven, 105000000000000000000000000000000 BauMaterial
		passive:multiply yield of Schmetterling by 1.75
		req:420000000000000000000000000000000 Insekten:earned and UgBISchmetterling11



*UgBIPSchmetterling1
		name:SchmetterlingsPanzer I
		desc:<.> Erhöht die Produktion der Schmetterlinge um <b>75</b> %.
		icon:icons[0,7] icons[4,1]
		cost:3900000000 InsektenPanzer
		passive:multiply yield of Schmetterling by 1.75
		req:1 InsektenPanzer and 1 Schmetterling
		class:noBackground

*UgBIPSchmetterling2
		name:SchmetterlingsPanzer II
		desc:<.> Erhöht die Produktion der Schmetterlinge um <b>75</b> %.
		icon:icons[0,7] icons[4,1]
		cost:390000000000 InsektenPanzer
		passive:multiply yield of Schmetterling by 1.75
		req:UgBIPSchmetterling1
		class:noBackground

*UgBIPSchmetterling3
		name:SchmetterlingsPanzer III
		desc:<.> Erhöht die Produktion der Schmetterlinge um <b>75</b> %.
		icon:icons[0,7] icons[4,1]
		cost:39000000000000 InsektenPanzer
		passive:multiply yield of Schmetterling by 1.75
		req:UgBIPSchmetterling2
		class:noBackground

*UgBIPSchmetterling4
		name:SchmetterlingsPanzer IV
		desc:<.> Erhöht die Produktion der Schmetterlinge um <b>75</b> %.
		icon:icons[0,7] icons[4,1]
		cost:3900000000000000 InsektenPanzer
		passive:multiply yield of Schmetterling by 1.75
		req:UgBIPSchmetterling3
		class:noBackground

*UgBIPSchmetterling5
		name:SchmetterlingsPanzer V
		desc:<.> Erhöht die Produktion der Schmetterlinge um <b>75</b> %.
		icon:icons[0,7] icons[4,1]
		cost:390000000000000000 InsektenPanzer
		passive:multiply yield of Schmetterling by 1.75
		req:UgBIPSchmetterling4
		class:noBackground

*UgBIPSchmetterling6
		name:SchmetterlingsPanzer VI
		desc:<.> Erhöht die Produktion der Schmetterlinge um <b>75</b> %.
		icon:icons[0,7] icons[4,1]
		cost:39000000000000000000 InsektenPanzer
		passive:multiply yield of Schmetterling by 1.75
		req:UgBIPSchmetterling5
		class:noBackground

*UgBIPSchmetterling7
		name:SchmetterlingsPanzer VII
		desc:<.> Erhöht die Produktion der Schmetterlinge um <b>75</b> %.
		icon:icons[0,7] icons[4,1]
		cost:3900000000000000000000 InsektenPanzer
		passive:multiply yield of Schmetterling by 1.75
		req:UgBIPSchmetterling6
		class:noBackground

*UgBIPSchmetterling8
		name:SchmetterlingsPanzer VIII
		desc:<.> Erhöht die Produktion der Schmetterlinge um <b>75</b> %.
		icon:icons[0,7] icons[4,1]
		cost:390000000000000000000000 InsektenPanzer
		passive:multiply yield of Schmetterling by 1.75
		req:UgBIPSchmetterling7
		class:noBackground

*UgBIPSchmetterling9
		name:SchmetterlingsPanzer IX
		desc:<.> Erhöht die Produktion der Schmetterlinge um <b>75</b> %.
		icon:icons[0,7] icons[4,1]
		cost:39000000000000000000000000 InsektenPanzer
		passive:multiply yield of Schmetterling by 1.75
		req:UgBIPSchmetterling8
		class:noBackground

*UgBIPSchmetterling10
		name:SchmetterlingsPanzer X
		desc:<.> Erhöht die Produktion der Schmetterlinge um <b>75</b> %.
		icon:icons[0,7] icons[4,1]
		cost:3900000000000000000000000000 InsektenPanzer
		passive:multiply yield of Schmetterling by 1.75
		req:UgBIPSchmetterling9
		class:noBackground


//9

*UgBISchabe1
		name:Küchenschabe
		desc:<.> Erhöht die Produktion der Schaben um <b>75</b> %.
		icon:icons[15,0]
		cost:65000000000 Insekten,31000000000 Larven, 15500000000 BauMaterial
		passive:multiply yield of Schabe by 1.75
		req:65000000000 Insekten:earned and 1 Schabe

*UgBISchabe2
		name:Kakerlake
		desc:<.> Erhöht die Produktion der Schaben um <b>75</b> %.
		icon:icons[15,1]
		cost:6500000000000 Insekten,3100000000000 Larven, 1550000000000 BauMaterial
		passive:multiply yield of Schabe by 1.75
		req:6500000000000 Insekten:earned and UgBISchabe1

*UgBISchabe3
		name:Waldschabe 
		desc:<.> Erhöht die Produktion der Schaben um <b>75</b> %.
		icon:icons[15,2]
		cost:650000000000000 Insekten,310000000000000 Larven, 155000000000000 BauMaterial
		passive:multiply yield of Schabe by 1.75
		req:650000000000000 Insekten:earned and UgBISchabe2

*UgBISchabe4
		name:Amerikanische Schabe
		desc:<.> Erhöht die Produktion der Schaben um <b>75</b> %.
		icon:icons[15,3]
		cost:65000000000000000 Insekten,31000000000000000 Larven, 15500000000000000 BauMaterial
		passive:multiply yield of Schabe by 1.75
		req:65000000000000000 Insekten:earned and UgBISchabe3

*UgBISchabe5
		name:Asiatische Schabe
		desc:<.> Erhöht die Produktion der Schaben um <b>75</b> %.
		icon:icons[15,4]
		cost:6500000000000000000 Insekten,3100000000000000000 Larven, 1550000000000000000 BauMaterial
		passive:multiply yield of Schabe by 1.75
		req:6500000000000000000 Insekten:earned and UgBISchabe4

*UgBISchabe6
		name:Australische Schabe
		desc:<.> Erhöht die Produktion der Schaben um <b>75</b> %.
		icon:icons[15,5]
		cost:650000000000000000000 Insekten,310000000000000000000 Larven, 155000000000000000000 BauMaterial
		passive:multiply yield of Schabe by 1.75
		req:650000000000000000000 Insekten:earned and UgBISchabe5

*UgBISchabe7
		name:Braunbandschabe
		desc:<.> Erhöht die Produktion der Schaben um <b>75</b> %.
		icon:icons[15,6]
		cost:65000000000000000000000 Insekten,31000000000000000000000 Larven, 15500000000000000000000 BauMaterial
		passive:multiply yield of Schabe by 1.75
		req:65000000000000000000000 Insekten:earned and UgBISchabe6

*UgBISchabe8
		name:Orientalische Schabe
		desc:<.> Erhöht die Produktion der Schaben um <b>75</b> %.
		icon:icons[15,7]
		cost:6500000000000000000000000 Insekten,3100000000000000000000000 Larven, 1550000000000000000000000 BauMaterial
		passive:multiply yield of Schabe by 1.75
		req:6500000000000000000000000 Insekten:earned and UgBISchabe7

*UgBISchabe9
		name:Spanische Schabe
		desc:<.> Erhöht die Produktion der Schaben um <b>75</b> %.
		icon:icons[15,8]
		cost:650000000000000000000000000 Insekten,310000000000000000000000000 Larven, 155000000000000000000000000 BauMaterial
		passive:multiply yield of Schabe by 1.75
		req:650000000000000000000000000 Insekten:earned and UgBISchabe8

*UgBISchabe10
		name:Europäische Schabe
		desc:<.> Erhöht die Produktion der Schaben um <b>75</b> %.
		icon:icons[15,9]
		cost:65000000000000000000000000000 Insekten,31000000000000000000000000000 Larven, 15500000000000000000000000000 BauMaterial
		passive:multiply yield of Schabe by 1.75
		req:65000000000000000000000000000 Insekten:earned and UgBISchabe9

*UgBISchabe11
		name:Französiche Schabe
		desc:<.> Erhöht die Produktion der Schaben um <b>75</b> %.
		icon:icons[15,10]
		cost:6500000000000000000000000000000 Insekten,3100000000000000000000000000000 Larven, 1550000000000000000000000000000 BauMaterial
		passive:multiply yield of Schabe by 1.75
		req:6500000000000000000000000000000 Insekten:earned and UgBISchabe10

*UgBISchabe12
		name:Russische Schabe
		desc:<.> Erhöht die Produktion der Schaben um <b>75</b> %.
		icon:icons[15,11]
		cost:650000000000000000000000000000000 Insekten,310000000000000000000000000000000 Larven, 155000000000000000000000000000000 BauMaterial
		passive:multiply yield of Schabe by 1.75
		req:650000000000000000000000000000000 Insekten:earned and UgBISchabe11


*UgBIPSchabe1
		name:SchabenPanzer I
		desc:<.> Erhöht die Produktion der Schmetterlinge um <b>75</b> %.
		icon:icons[0,8] icons[4,1]
		cost:62909090910 InsektenPanzer
		passive:multiply yield of Schabe by 1.75
		req:1 InsektenPanzer and 1 Schmetterling
		class:noBackground

*UgBIPSchabe2
		name:SchabenPanzer II
		desc:<.> Erhöht die Produktion der Schmetterlinge um <b>75</b> %.
		icon:icons[0,8] icons[4,1]
		cost:6290909091000 InsektenPanzer
		passive:multiply yield of Schabe by 1.75
		req:UgBIPSchabe1
		class:noBackground

*UgBIPSchabe3
		name:SchabenPanzer III
		desc:<.> Erhöht die Produktion der Schmetterlinge um <b>75</b> %.
		icon:icons[0,8] icons[4,1]
		cost:629090909100000 InsektenPanzer
		passive:multiply yield of Schabe by 1.75
		req:UgBIPSchabe2
		class:noBackground

*UgBIPSchabe4
		name:SchabenPanzer IV
		desc:<.> Erhöht die Produktion der Schmetterlinge um <b>75</b> %.
		icon:icons[0,8] icons[4,1]
		cost:62909090910000000 InsektenPanzer
		passive:multiply yield of Schabe by 1.75
		req:UgBIPSchabe3
		class:noBackground

*UgBIPSchabe5
		name:SchabenPanzer V
		desc:<.> Erhöht die Produktion der Schmetterlinge um <b>75</b> %.
		icon:icons[0,8] icons[4,1]
		cost:6290909091000000000 InsektenPanzer
		passive:multiply yield of Schabe by 1.75
		req:UgBIPSchabe4
		class:noBackground

*UgBIPSchabe6
		name:SchabenPanzer VI
		desc:<.> Erhöht die Produktion der Schmetterlinge um <b>75</b> %.
		icon:icons[0,8] icons[4,1]
		cost:629090909100000000000 InsektenPanzer
		passive:multiply yield of Schabe by 1.75
		req:UgBIPSchabe5
		class:noBackground

*UgBIPSchabe7
		name:SchabenPanzer VII
		desc:<.> Erhöht die Produktion der Schmetterlinge um <b>75</b> %.
		icon:icons[0,8] icons[4,1]
		cost:62909090910000000000000 InsektenPanzer
		passive:multiply yield of Schabe by 1.75
		req:UgBIPSchabe6
		class:noBackground

*UgBIPSchabe8
		name:SchabenPanzer VIII
		desc:<.> Erhöht die Produktion der Schmetterlinge um <b>75</b> %.
		icon:icons[0,8] icons[4,1]
		cost:6290909091000000000000000 InsektenPanzer
		passive:multiply yield of Schabe by 1.75
		req:UgBIPSchabe7
		class:noBackground

*UgBIPSchabe9
		name:SchabenPanzer IX
		desc:<.> Erhöht die Produktion der Schmetterlinge um <b>75</b> %.
		icon:icons[0,8] icons[4,1]
		cost:629090909100000000000000000 InsektenPanzer
		passive:multiply yield of Schabe by 1.75
		req:UgBIPSchabe8
		class:noBackground

*UgBIPSchabe10
		name:SchabenPanzer X
		desc:<.> Erhöht die Produktion der Schmetterlinge um <b>75</b> %.
		icon:icons[0,8] icons[4,1]
		cost:62909090910000000000000000000 InsektenPanzer
		passive:multiply yield of Schabe by 1.75
		req:UgBIPSchabe9
		class:noBackground		
	
	

//10

*UgBISkorpion1
		name:Großer Stachel
		desc:<.> Erhöht die Produktion der Skorpione um <b>75</b> %.
		icon:icons[16,0]
		cost:980000000000 Insekten,460000000000 Larven, 245000000000 BauMaterial
		passive:multiply yield of Schabe by 1.75
		req:980000000000 Insekten:earned and 1 Skorpion

*UgBISkorpion2
		name:Dicker Stachel
		desc:<.> Erhöht die Produktion der Skorpione um <b>75</b> %.
		icon:icons[16,1]
		cost:98000000000000 Insekten,46000000000000 Larven, 24500000000000 BauMaterial
		passive:multiply yield of Schabe by 1.75
		req:98000000000000 Insekten:earned and UgBISkorpion1

*UgBISkorpion3
		name:Dicker Panzer
		desc:<.> Erhöht die Produktion der Skorpione um <b>75</b> %.
		icon:icons[16,2]
		cost:9800000000000000 Insekten,4600000000000000 Larven, 2450000000000000 BauMaterial
		passive:multiply yield of Schabe by 1.75
		req:9800000000000000 Insekten:earned and UgBISkorpion2

*UgBISkorpion4
		name:Schnelle Füße
		desc:<.> Erhöht die Produktion der Skorpione um <b>75</b> %.
		icon:icons[16,3]
		cost:980000000000000000 Insekten,460000000000000000 Larven, 245000000000000000 BauMaterial
		passive:multiply yield of Schabe by 1.75
		req:980000000000000000 Insekten:earned and UgBISkorpion3

*UgBISkorpion5
		name:Hitze resistent
		desc:<.> Erhöht die Produktion der Skorpione um <b>75</b> %.
		icon:icons[16,4]
		cost:98000000000000000000 Insekten,46000000000000000000 Larven, 24500000000000000000 BauMaterial
		passive:multiply yield of Schabe by 1.75
		req:98000000000000000000 Insekten:earned and UgBISkorpion4

*UgBISkorpion6
		name:Kälte resistent
		desc:<.> Erhöht die Produktion der Skorpione um <b>75</b> %.
		icon:icons[16,5]
		cost:9800000000000000000000 Insekten,4600000000000000000000 Larven, 2450000000000000000000 BauMaterial
		passive:multiply yield of Schabe by 1.75
		req:9800000000000000000000 Insekten:earned and UgBISkorpion5

*UgBISkorpion7
		name:Wüsten Skorpion
		desc:<.> Erhöht die Produktion der Skorpione um <b>75</b> %.
		icon:icons[16,6]
		cost:980000000000000000000000 Insekten,460000000000000000000000 Larven, 245000000000000000000000 BauMaterial
		passive:multiply yield of Schabe by 1.75
		req:980000000000000000000000 Insekten:earned and UgBISkorpion6

*UgBISkorpion8
		name:Roter Skorpion
		desc:<.> Erhöht die Produktion der Skorpione um <b>75</b> %.
		icon:icons[16,7]
		cost:98000000000000000000000000 Insekten,46000000000000000000000000 Larven, 24500000000000000000000000 BauMaterial
		passive:multiply yield of Schabe by 1.75
		req:98000000000000000000000000 Insekten:earned and UgBISkorpion7

*UgBISkorpion9
		name:Brauner Skorpion
		desc:<.> Erhöht die Produktion der Skorpione um <b>75</b> %.
		icon:icons[16,8]
		cost:9800000000000000000000000000 Insekten,4600000000000000000000000000 Larven, 2450000000000000000000000000 BauMaterial
		passive:multiply yield of Schabe by 1.75
		req:9800000000000000000000000000 Insekten:earned and UgBISkorpion8

*UgBISkorpion10
		name:Kurze Füße
		desc:<.> Erhöht die Produktion der Skorpione um <b>75</b> %.
		icon:icons[16,9]
		cost:980000000000000000000000000000 Insekten,460000000000000000000000000000 Larven, 245000000000000000000000000000 BauMaterial
		passive:multiply yield of Schabe by 1.75
		req:980000000000000000000000000000 Insekten:earned and UgBISkorpion9

*UgBISkorpion11
		name:Langer Stachel
		desc:<.> Erhöht die Produktion der Skorpione um <b>75</b> %.
		icon:icons[16,10]
		cost:98000000000000000000000000000000 Insekten,46000000000000000000000000000000 Larven, 24500000000000000000000000000000 BauMaterial
		passive:multiply yield of Schabe by 1.75
		req:98000000000000000000000000000000 Insekten:earned and UgBISkorpion10

*UgBISkorpion12
		name:Amerikanischer Skorpion
		desc:<.> Erhöht die Produktion der Skorpione um <b>75</b> %.
		icon:icons[16,11]
		cost:9800000000000000000000000000000000 Insekten,4600000000000000000000000000000000 Larven, 2450000000000000000000000000000000 BauMaterial
		passive:multiply yield of Schabe by 1.75
		req:9800000000000000000000000000000000 Insekten:earned and UgBISkorpion11

//10

*UgBIPSkorpion1
		name:SkorpionPanzer I
		desc:<.> Erhöht die Produktion der Skorpione um <b>75</b> %.
		icon:icons[0,9] icons[4,1]
		cost:724545454550 InsektenPanzer
		passive:multiply yield of Skorpion by 1.75
		req:1 InsektenPanzer and 1 Skorpion
		class:noBackground

*UgBIPSkorpion2
		name:SkorpionPanzer II
		desc:<.> Erhöht die Produktion der Skorpione um <b>75</b> %.
		icon:icons[0,9] icons[4,1]
		cost:72454545455000 InsektenPanzer
		passive:multiply yield of Skorpion by 1.75
		req:UgBIPSkorpion1
		class:noBackground

*UgBIPSkorpion3
		name:SkorpionPanzer III
		desc:<.> Erhöht die Produktion der Skorpione um <b>75</b> %.
		icon:icons[0,9] icons[4,1]
		cost:7245454545500000 InsektenPanzer
		passive:multiply yield of Skorpion by 1.75
		req:UgBIPSkorpion2
		class:noBackground

*UgBIPSkorpion4
		name:SkorpionPanzer IV
		desc:<.> Erhöht die Produktion der Skorpione um <b>75</b> %.
		icon:icons[0,9] icons[4,1]
		cost:724545454550000000 InsektenPanzer
		passive:multiply yield of Skorpion by 1.75
		req:UgBIPSkorpion3
		class:noBackground

*UgBIPSkorpion5
		name:SkorpionPanzer V
		desc:<.> Erhöht die Produktion der Skorpione um <b>75</b> %.
		icon:icons[0,9] icons[4,1]
		cost:72454545455000000000 InsektenPanzer
		passive:multiply yield of Skorpion by 1.75
		req:UgBIPSkorpion4
		class:noBackground

*UgBIPSkorpion6
		name:SkorpionPanzer VI
		desc:<.> Erhöht die Produktion der Skorpione um <b>75</b> %.
		icon:icons[0,9] icons[4,1]
		cost:7245454545500000000000 InsektenPanzer
		passive:multiply yield of Skorpion by 1.75
		req:UgBIPSkorpion5
		class:noBackground

*UgBIPSkorpion7
		name:SkorpionPanzer VII
		desc:<.> Erhöht die Produktion der Skorpione um <b>75</b> %.
		icon:icons[0,9] icons[4,1]
		cost:724545454550000000000000 InsektenPanzer
		passive:multiply yield of Skorpion by 1.75
		req:UgBIPSkorpion6
		class:noBackground

*UgBIPSkorpion8
		name:SkorpionPanzer VIII
		desc:<.> Erhöht die Produktion der Skorpione um <b>75</b> %.
		icon:icons[0,9] icons[4,1]
		cost:72454545455000000000000000 InsektenPanzer
		passive:multiply yield of Skorpion by 1.75
		req:UgBIPSkorpion7
		class:noBackground

*UgBIPSkorpion9
		name:SkorpionPanzer IX
		desc:<.> Erhöht die Produktion der Skorpione um <b>75</b> %.
		icon:icons[0,9] icons[4,1]
		cost:7245454545500000000000000000 InsektenPanzer
		passive:multiply yield of Skorpion by 1.75
		req:UgBIPSkorpion8
		class:noBackground

*UgBIPSkorpion10
		name:SkorpionPanzer X
		desc:<.> Erhöht die Produktion der Skorpione um <b>75</b> %.
		icon:icons[0,9] icons[4,1]
		cost:724545454550000000000000000000 InsektenPanzer
		passive:multiply yield of Skorpion by 1.75
		req:UgBIPSkorpion9
		class:noBackground	
		
		
		


	
//10

*UgBIMoskito1
		name:Moskitole
		desc:<.> Erhöht die Produktion der Moskitos um <b>75</b> %.
		icon:icons[17,0]
		cost:12700000000000 Insekten,3200000000000 Larven, 3150000000000 BauMaterial
		passive:multiply yield of Moskito by 1.75
		req:12700000000000 Insekten:earned and 1 Moskito

*UgBIMoskito2
		name:Nachtflügler
		desc:<.> Erhöht die Produktion der Moskitos um <b>75</b> %.
		icon:icons[17,1]
		cost:1270000000000000 Insekten,320000000000000 Larven, 315000000000000 BauMaterial
		passive:multiply yield of Moskito by 1.75
		req:1270000000000000 Insekten:earned and UgBIMoskito1

*UgBIMoskito3
		name:Vampier
		desc:<.> Erhöht die Produktion der Moskitos um <b>75</b> %.
		icon:icons[17,2]
		cost:127000000000000000 Insekten,32000000000000000 Larven, 31500000000000000 BauMaterial
		passive:multiply yield of Moskito by 1.75
		req:127000000000000000 Insekten:earned and UgBIMoskito2

*UgBIMoskito4
		name:Blutsauger
		desc:<.> Erhöht die Produktion der Moskitos um <b>75</b> %.
		icon:icons[17,3]
		cost:12700000000000000000 Insekten,3200000000000000000 Larven, 3150000000000000000 BauMaterial
		passive:multiply yield of Moskito by 1.75
		req:12700000000000000000 Insekten:earned and UgBIMoskito3

*UgBIMoskito5
		name:Weite Flügel
		desc:<.> Erhöht die Produktion der Moskitos um <b>75</b> %.
		icon:icons[17,4]
		cost:1270000000000000000000 Insekten,320000000000000000000 Larven, 315000000000000000000 BauMaterial
		passive:multiply yield of Moskito by 1.75
		req:1270000000000000000000 Insekten:earned and UgBIMoskito4

*UgBIMoskito6
		name:Schöne Flügel
		desc:<.> Erhöht die Produktion der Moskitos um <b>75</b> %.
		icon:icons[17,5]
		cost:127000000000000000000000 Insekten,32000000000000000000000 Larven, 31500000000000000000000 BauMaterial
		passive:multiply yield of Moskito by 1.75
		req:127000000000000000000000 Insekten:earned and UgBIMoskito5

*UgBIMoskito7
		name:Lange Flügel
		desc:<.> Erhöht die Produktion der Moskitos um <b>75</b> %.
		icon:icons[17,6]
		cost:12700000000000000000000000 Insekten,3200000000000000000000000 Larven, 3150000000000000000000000 BauMaterial
		passive:multiply yield of Moskito by 1.75
		req:12700000000000000000000000 Insekten:earned and UgBIMoskito6

*UgBIMoskito8
		name:Kurzer Stachel
		desc:<.> Erhöht die Produktion der Moskitos um <b>75</b> %.
		icon:icons[17,7]
		cost:1270000000000000000000000000 Insekten,320000000000000000000000000 Larven, 315000000000000000000000000 BauMaterial
		passive:multiply yield of Moskito by 1.75
		req:1270000000000000000000000000 Insekten:earned and UgBIMoskito7

*UgBIMoskito9
		name:Langer Stachel
		desc:<.> Erhöht die Produktion der Moskitos um <b>75</b> %.
		icon:icons[17,8]
		cost:127000000000000000000000000000 Insekten,32000000000000000000000000000 Larven, 31500000000000000000000000000 BauMaterial
		passive:multiply yield of Moskito by 1.75
		req:127000000000000000000000000000 Insekten:earned and UgBIMoskito8

*UgBIMoskito10
		name:Dicker Stachel
		desc:<.> Erhöht die Produktion der Moskitos um <b>75</b> %.
		icon:icons[17,9]
		cost:12700000000000000000000000000000 Insekten,3200000000000000000000000000000 Larven, 3150000000000000000000000000000 BauMaterial
		passive:multiply yield of Moskito by 1.75
		req:12700000000000000000000000000000 Insekten:earned and UgBIMoskito9

*UgBIMoskito11
		name:Dünner Stachel
		desc:<.> Erhöht die Produktion der Moskitos um <b>75</b> %.
		icon:icons[17,10]
		cost:1270000000000000000000000000000000 Insekten,320000000000000000000000000000000 Larven, 315000000000000000000000000000000 BauMaterial
		passive:multiply yield of Moskito by 1.75
		req:1270000000000000000000000000000000 Insekten:earned and UgBIMoskito10

*UgBIMoskito12
		name:Großer Mücken Stachel
		desc:<.> Erhöht die Produktion der Moskitos um <b>75</b> %.
		icon:icons[17,11]
		cost:127000000000000000000000000000000000 Insekten,32000000000000000000000000000000000 Larven, 31500000000000000000000000000000000 BauMaterial
		passive:multiply yield of Moskito by 1.75
		req:127000000000000000000000000000000000 Insekten:earned and UgBIMoskito11

	





//11

*UgBIPMoskito1
		name:MoskitoPanzer I
		desc:<.> Erhöht die Produktion der Moskitos um <b>75</b> %.
		icon:icons[0,10] icons[4,1]
		cost:9727272727270 InsektenPanzer
		passive:multiply yield of Moskito by 1.75
		req:1 InsektenPanzer and 1 Moskito
		class:noBackground

*UgBIPMoskito2
		name:MoskitoPanzer II
		desc:<.> Erhöht die Produktion der Moskitos um <b>75</b> %.
		icon:icons[0,10] icons[4,1]
		cost:972727272727000 InsektenPanzer
		passive:multiply yield of Moskito by 1.75
		req:UgBIPMoskito1
		class:noBackground

*UgBIPMoskito3
		name:MoskitoPanzer III
		desc:<.> Erhöht die Produktion der Moskitos um <b>75</b> %.
		icon:icons[0,10] icons[4,1]
		cost:97272727272700000 InsektenPanzer
		passive:multiply yield of Moskito by 1.75
		req:UgBIPMoskito2
		class:noBackground

*UgBIPMoskito4
		name:MoskitoPanzer IV
		desc:<.> Erhöht die Produktion der Moskitos um <b>75</b> %.
		icon:icons[0,10] icons[4,1]
		cost:9727272727270000000 InsektenPanzer
		passive:multiply yield of Moskito by 1.75
		req:UgBIPMoskito3
		class:noBackground

*UgBIPMoskito5
		name:MoskitoPanzer V
		desc:<.> Erhöht die Produktion der Moskitos um <b>75</b> %.
		icon:icons[0,10] icons[4,1]
		cost:972727272727000000000 InsektenPanzer
		passive:multiply yield of Moskito by 1.75
		req:UgBIPMoskito4
		class:noBackground

*UgBIPMoskito6
		name:MoskitoPanzer VI
		desc:<.> Erhöht die Produktion der Moskitos um <b>75</b> %.
		icon:icons[0,10] icons[4,1]
		cost:97272727272700000000000 InsektenPanzer
		passive:multiply yield of Moskito by 1.75
		req:UgBIPMoskito5
		class:noBackground

*UgBIPMoskito7
		name:MoskitoPanzer VII
		desc:<.> Erhöht die Produktion der Moskitos um <b>75</b> %.
		icon:icons[0,10] icons[4,1]
		cost:9727272727270000000000000 InsektenPanzer
		passive:multiply yield of Moskito by 1.75
		req:UgBIPMoskito6
		class:noBackground

*UgBIPMoskito8
		name:MoskitoPanzer VIII
		desc:<.> Erhöht die Produktion der Moskitos um <b>75</b> %.
		icon:icons[0,10] icons[4,1]
		cost:972727272727000000000000000 InsektenPanzer
		passive:multiply yield of Moskito by 1.75
		req:UgBIPMoskito7
		class:noBackground

*UgBIPMoskito9
		name:MoskitoPanzer IX
		desc:<.> Erhöht die Produktion der Moskitos um <b>75</b> %.
		icon:icons[0,10] icons[4,1]
		cost:97272727272700000000000000000 InsektenPanzer
		passive:multiply yield of Moskito by 1.75
		req:UgBIPMoskito8
		class:noBackground

*UgBIPMoskito10
		name:MoskitoPanzer X
		desc:<.> Erhöht die Produktion der Moskitos um <b>75</b> %.
		icon:icons[0,10] icons[4,1]
		cost:9727272727270000000000000000000 InsektenPanzer
		passive:multiply yield of Moskito by 1.75
		req:UgBIPMoskito9
		class:noBackground
	
		
		
// Schaltet insekten frei ----------------------------------------------------		
		




//2
*UpgITermitorium
	name:Termitorium
	desc:Schaltet Termiten frei.
	icon:icons[5,5] icons[0,1] icons[4,0]
	cost:10 Bienenstock,5 Ast
	req:10 Insekten:earned
	class:noBackground
//3
*UpgISchmeisfliege
	name:Schmeisfliege
	desc:Schaltet Fliegen frei.
	icon:icons[5,5] icons[0,2] icons[4,0]
	cost:10 Termitenbau,5 Knollenwurzel
	req:UpgITermitorium
	class:noBackground
//4
*UpgIBuggy
	name:Käferlinge
	desc:Schaltet Käfer frei.
	icon:icons[5,5] icons[0,3] icons[4,0]
	cost:10 Blatt,5 Steine
	req:UpgISchmeisfliege	
	class:noBackground
//5
*UpgIBienenqueen
	name:Bienenkönigin
	desc:Schaltet Bienen frei.
	icon:icons[5,5] icons[0,4] icons[4,0]
	cost:10 WespenNest,5 Dreck
	req:UpgIBuggy
	class:noBackground	
//6
*UpgIRoteAmeise
	name:Feuerameise
	desc:Schaltet RoteAmeisen frei.
	icon:icons[5,5] icons[0,5] icons[4,0]
	cost:10 VerfaulterApfel,5 AltesBuch
	req:UpgIBienenqueen
	class:noBackground	
//7		
*UpgIGrosserBug
	name:Pillendreher
	desc:Schaltet GroßeKäfer frei.
	icon:icons[5,5] icons[0,6] icons[4,0]
	cost:10 AlteNester,5 Karnickel
	req:UpgIRoteAmeise
	class:noBackground	
//8	
*UpgISchmetterl
	name:Zitronenfalter
	desc:Schaltet Schmetterlinge frei.
	icon:icons[5,5] icons[0,7] icons[4,0]
	cost:10 UeberwucherterSchuh,5 Sonnenblume
	req:UpgIGrosserBug
	class:noBackground			
//9		
*UpgISchabe
	name:Kakerlaki
	desc:Schaltet Schabe frei.
	icon:icons[5,5] icons[0,8] icons[4,0]
	cost:10 Pizzen,5 Freds
	req:UpgISchmetterl
	class:noBackground	
	
//10
*UpgISkorion
	name:Sultan Sting
	desc:Schaltet Skorpion frei.
	icon:icons[5,5] icons[0,9] icons[4,0]
	cost:10 SchneckeIvan,5 Blumenbusch
	req:UpgISchabe
	class:noBackground	
	
//11
*UpgIMoskito
	name:Stechmücke
	desc:Schaltet Moskitos frei.
	icon:icons[5,5] icons[0,10] icons[4,0]
	cost:10 WasserEimer,5 Wollmaus
	req:UpgISkorion
	class:noBackground	
	
//12
*UpgIWilli
	name:WilliWilli
	desc:Schaltet GroßeKäfer frei.
	icon:icons[5,5] icons[0,11] icons[4,0]
	cost:10 DahlienBusch,5 VogelNest
	req:UpgIMoskito
	class:noBackground	
	
//13
*UpgILibelle
	name:Urlibelle
	desc:Schaltet Libellen frei.
	icon:icons[5,5] icons[0,12] icons[4,0]
	cost:10 Maruscha,5 HolzStapel
	req:UpgIWilli
	class:noBackground	
	
//14
*UpgIGluehwurm
	name:Poleuchter
	desc:Schaltet Glühwürmchen frei.
	icon:icons[5,5] icons[0,13] icons[4,0]
	cost:10 Gelbfisch,5 HerbstLaub
	req:UpgILibelle
	class:noBackground	
	
//15
*UpgIMistroller
	name:Mistkäfer
	desc:Schaltet Mistroller frei.
	icon:icons[5,5] icons[0,14] icons[4,0]
	cost:10 Schildkroete,5 EuleFrieda
	req:UpgIGluehwurm
	class:noBackground	
	
//16
*UpgINachtfalter
	name:Flattermann
	desc:Schaltet Nachtfalter frei.
	icon:icons[5,5] icons[0,15] icons[4,0]
	cost:10 Banane,5 CreepyTree
	req:UpgIMistroller
	class:noBackground		
		
			
		
	



//BauMaterial Upgrades




//Upgrades Ressource Baumaterial	
		
		
		
		

*UgRBKiesel1
		name:Dacit
		desc:<.> Erhöht die Produktion von Baumaterial um <b>1</b> %.
		icon:iconsa[2,0]
		cost:999999 BauMaterial
		passive:multiply yield of BauMaterial by 1.01
		req:50000 BauMaterial:earned
*UgRBKiesel2
		name:Hornstein
		desc:<.> Erhöht die Produktion von Baumaterial um <b>1</b> %.
		icon:iconsa[2,1]
		cost:5000000 BauMaterial
		passive:multiply yield of BauMaterial by 1.01
		req:250000 BauMaterial:earned and UgRBKiesel1
*UgRBKiesel3
		name:Aplit
		desc:<.> Erhöht die Produktion von Baumaterial um <b>1</b> %.
		icon:iconsa[2,2]
		cost:10000000 BauMaterial
		passive:multiply yield of BauMaterial by 1.01
		req:500000 BauMaterial:earned and UgRBKiesel2
*UgRBKiesel4
		name:Eklogit
		desc:<.> Erhöht die Produktion von Baumaterial um <b>1</b> %.
		icon:iconsa[2,3]
		cost:50000000 BauMaterial
		passive:multiply yield of BauMaterial by 1.01
		req:2500000 BauMaterial:earned and UgRBKiesel3
*UgRBKiesel5
		name:Essexit
		desc:<.> Erhöht die Produktion von Baumaterial um <b>1</b> %.
		icon:iconsa[2,4]
		cost:100000000 BauMaterial
		passive:multiply yield of BauMaterial by 1.01
		req:5000000 BauMaterial:earned and UgRBKiesel4
*UgRBKiesel6
		name:Felsit
		desc:<.> Erhöht die Produktion von Baumaterial um <b>1</b> %.
		icon:iconsa[2,5]
		cost:500000000 BauMaterial
		passive:multiply yield of BauMaterial by 1.01
		req:25000000 BauMaterial:earned and UgRBKiesel5
*UgRBKiesel7
		name:Arkose
		desc:<.> Erhöht die Produktion von Baumaterial um <b>1</b> %.
		icon:iconsa[2,6]
		cost:1000000000 BauMaterial
		passive:multiply yield of BauMaterial by 1.01
		req:50000000 BauMaterial:earned and UgRBKiesel6
*UgRBKiesel8
		name:Jumillit
		desc:<.> Erhöht die Produktion von Baumaterial um <b>1</b> %.
		icon:iconsa[2,7]
		cost:5000000000 BauMaterial
		passive:multiply yield of BauMaterial by 1.01
		req:250000000 BauMaterial:earned and UgRBKiesel7
*UgRBKiesel9
		name:Lava
		desc:<.> Erhöht die Produktion von Baumaterial um <b>1</b> %.
		icon:iconsa[2,8]
		cost:10000000000 BauMaterial
		passive:multiply yield of BauMaterial by 1.01
		req:500000000 BauMaterial:earned and UgRBKiesel8
*UgRBKiesel10
		name:Kaolin
		desc:<.> Erhöht die Produktion von Baumaterial um <b>1</b> %.
		icon:iconsa[2,9]
		cost:50000000000 BauMaterial
		passive:multiply yield of BauMaterial by 1.01
		req:2500000000 BauMaterial:earned and UgRBKiesel9
*UgRBKiesel11
		name:Impaktit
		desc:<.> Erhöht die Produktion von Baumaterial um <b>1</b> %.
		icon:iconsa[2,10]
		cost:100000000000 BauMaterial
		passive:multiply yield of BauMaterial by 1.01
		req:5000000000 BauMaterial:earned and UgRBKiesel10
*UgRBKiesel12
		name:Löss
		desc:<.> Erhöht die Produktion von Baumaterial um <b>1</b> %.
		icon:iconsa[2,11]
		cost:500000000000 BauMaterial
		passive:multiply yield of BauMaterial by 1.01
		req:25000000000 BauMaterial:earned and UgRBKiesel11
*UgRBKiesel13
		name:Kalktuff
		desc:<.> Erhöht die Produktion von Baumaterial um <b>1</b> %.
		icon:iconsa[2,12]
		cost:1000000000000 BauMaterial
		passive:multiply yield of BauMaterial by 1.01
		req:50000000000 BauMaterial:earned and UgRBKiesel12

*UgRBKiesel14
		name:Weißschiefer
		desc:<.> Erhöht die Produktion von Baumaterial um <b>1</b> %.
		icon:iconsa[2,13]
		cost:5000000000000 BauMaterial
		passive:multiply yield of BauMaterial by 1.01
		req:250000000000 BauMaterial:earned and UgRBKiesel13

*UgRBKiesel15
		name:Suevit
		desc:<.> Erhöht die Produktion von Baumaterial um <b>1</b> %.
		icon:iconsa[2,14]
		cost:10000000000000 BauMaterial
		passive:multiply yield of BauMaterial by 1.01
		req:UgRBKiesel14

*UgRBKiesel16
		name:Migmatit
		desc:<.> Erhöht die Produktion von Baumaterial um <b>1</b> %.
		icon:iconsa[2,15]
		cost:50000000000000 BauMaterial
		passive:multiply yield of BauMaterial by 1.01
		req:5000000000000 BauMaterial:earned and UgRBKiesel15

*UgRBKiesel17
		name:MORB
		desc:<.> Erhöht die Produktion von Baumaterial um <b>1</b> %.
		icon:iconsa[2,16]
		cost:100000000000000 BauMaterial
		passive:multiply yield of BauMaterial by 1.01
		req:25000000000000 BauMaterial:earned and UgRBKiesel16
*UgRBKiesel18
		name:Tektit
		desc:<.> Erhöht die Produktion von Baumaterial um <b>1</b> %.
		icon:iconsa[2,17]
		cost:500000000000000 BauMaterial
		passive:multiply yield of BauMaterial by 1.01
		req:50000000000000 BauMaterial:earned and UgRBKiesel17
*UgRBKiesel19
		name:Schiefer
		desc:<.> Erhöht die Produktion von Baumaterial um <b>1</b> %.
		icon:iconsa[2,18]
		cost:1000000000000000 BauMaterial
		passive:multiply yield of BauMaterial by 1.01
		req:250000000000000 BauMaterial:earned and UgRBKiesel18
*UgRBKiesel20
		name:Rogenstein
		desc:<.> Erhöht die Produktion von Baumaterial um <b>1</b> %.
		icon:iconsa[2,19]
		cost:5000000000000000 BauMaterial
		passive:multiply yield of BauMaterial by 1.01
		req:500000000000000 BauMaterial:earned and UgRBKiesel19
*UgRBKiesel21
		name:Mylonit
		desc:<.> Erhöht die Produktion von Baumaterial um <b>1</b> %.
		icon:iconsa[2,20]
		cost:10000000000000000 BauMaterial
		passive:multiply yield of BauMaterial by 1.01
		req:2500000000000000 BauMaterial:earned and UgRBKiesel20
		
		




*UgRBPilz1
        name:Fliegenpilz
        desc:<.> Beim Klicken des Baumstammes bekommst du <b>2</b> mal so viel!
        icon:iconsa[3,0]
        cost:999999 BauMaterial
        passive:multiply yield of TreeButton by 2
        req:50000 BauMaterial:earned
*UgRBPilz2
        name:Saftapfel
        desc:<.> Beim Klicken des Baumstammes bekommst du <b>3</b> mal so viel!
        icon:iconsa[3,1]
        cost:5000000 BauMaterial
        passive:increase yield of TreeButton by 3
        req:250000 BauMaterial:earned and UgRBPilz1
*UgRBPilz3
        name:Aderige Blattflechte
        desc:<.> Beim Klicken des Baumstammes bekommst du <b>3</b> mal so viel!
        icon:iconsa[3,2]
        cost:10000000 BauMaterial
        passive:multiply yield of TreeButton by 3
        req:500000 BauMaterial:earned and UgRBPilz2
*UgRBPilz4
        name:Krustenflechte
        desc:<.> Beim Klicken des Baumstammes bekommst du <b>3</b> mal so viel!
        icon:iconsa[3,3]
        cost:50000000 BauMaterial
        passive:multiply yield of TreeButton by 3
        req:2500000 BauMaterial:earned and UgRBPilz3
*UgRBPilz5
        name:Kugelpilz
        desc:<.> Beim Klicken des Baumstammes bekommst du <b>3</b> mal so viel!
        icon:iconsa[3,4]
        cost:100000000 BauMaterial
        passive:multiply yield of TreeButton by 3
        req:5000000 BauMaterial:earned and UgRBPilz4
*UgRBPilz6
        name:Schildflechte
        desc:<.> Beim Klicken des Baumstammes bekommst du <b>3</b> mal so viel!
        icon:iconsa[3,5]
        cost:500000000 BauMaterial
        passive:multiply yield of TreeButton by 3
        req:25000000 BauMaterial:earned and UgRBPilz5
*UgRBPilz7
        name:Becherflechte
        desc:<.> Beim Klicken des Baumstammes bekommst du <b>3</b> mal so viel!
        icon:iconsa[3,6]
        cost:1000000000 BauMaterial
        passive:multiply yield of TreeButton by 3
        req:50000000 BauMaterial:earned and UgRBPilz6
*UgRBPilz8
        name:Binsenkeule
        desc:<.> Beim Klicken des Baumstammes bekommst du <b>3</b> mal so viel!
        icon:iconsa[3,7]
        cost:5000000000 BauMaterial
        passive:multiply yield of TreeButton by 3
        req:250000000 BauMaterial:earned and UgRBPilz7
*UgRBPilz9
        name:Trichterling
        desc:<.> Beim Klicken des Baumstammes bekommst du <b>3</b> mal so viel!
        icon:iconsa[3,8]
        cost:10000000000 BauMaterial
        passive:multiply yield of TreeButton by 3
        req:500000000 BauMaterial:earned and UgRBPilz8
*UgRBPilz10
        name:Klumpfuß
        desc:<.> Beim Klicken des Baumstammes bekommst du <b>3</b> mal so viel!
        icon:iconsa[3,9]
        cost:50000000000 BauMaterial
        passive:multiply yield of TreeButton by 3
        req:2500000000 BauMaterial:earned and UgRBPilz9
*UgRBPilz11
        name:Milchling
        desc:<.> Beim Klicken des Baumstammes bekommst du <b>3</b> mal so viel!
        icon:iconsa[3,10]
        cost:100000000000 BauMaterial
        passive:multiply yield of TreeButton by 3
        req:5000000000 BauMaterial:earned and UgRBPilz10
*UgRBPilz12
        name:Rötling
        desc:<.> Beim Klicken des Baumstammes bekommst du <b>3</b> mal so viel!
        icon:iconsa[3,11]
        cost:500000000000 BauMaterial
        passive:multiply yield of TreeButton by 3
        req:25000000000 BauMaterial:earned and UgRBPilz11  
*UgRBPilz13
        name:Düngerling
        desc:<.> Beim Klicken des Baumstammes bekommst du <b>3</b> mal so viel!
        icon:iconsa[3,12]
        cost:1000000000000 BauMaterial
        passive:multiply yield of TreeButton by 3
        req:50000000000 BauMaterial:earned and UgRBPilz12
*UgRBPilz14
        name:Tintling
        desc:<.> Beim Klicken des Baumstammes bekommst du <b>3</b> mal so viel!
        icon:iconsa[3,13]
        cost:5000000000000 BauMaterial
        passive:multiply yield of TreeButton by 3
        req:250000000000 BauMaterial:earned and UgRBPilz13
*UgRBPilz15
        name:Bovist
        desc:<.> Beim Klicken des Baumstammes bekommst du <b>3</b> mal so viel!
        icon:iconsa[3,14]
        cost:10000000000000 BauMaterial
        passive:multiply yield of TreeButton by 3
        req:500000000000 BauMaterial:earned and UgRBPilz14
*UgRBPilz16
        name:Migmatit
        desc:<.> Beim Klicken des Baumstammes bekommst du <b>3</b> mal so viel!
        icon:iconsa[3,15]
        cost:50000000000000 BauMaterial
        passive:multiply yield of TreeButton by 3
        req:5000000000000 BauMaterial:earned and UgRBPilz15
*UgRBPilz17
        name:Helmling
        desc:<.> Beim Klicken des Baumstammes bekommst du <b>3</b> mal so viel!
        icon:iconsa[3,16]
        cost:100000000000000 BauMaterial
        passive:multiply yield of TreeButton by 3
        req:25000000000000 BauMaterial:earned and UgRBPilz16
*UgRBPilz18
        name:Rindenpilz
        desc:<.> Beim Klicken des Baumstammes bekommst du <b>3</b> mal so viel!
        icon:iconsa[3,17]
        cost:500000000000000 BauMaterial
        passive:multiply yield of TreeButton by 3
        req:50000000000000 BauMaterial:earned and UgRBPilz17
*UgRBPilz19
        name:Rasling
        desc:<.> Beim Klicken des Baumstammes bekommst du <b>3</b> mal so viel!
        icon:iconsa[3,18]
        cost:1000000000000000 BauMaterial
        passive:multiply yield of TreeButton by 3
        req:250000000000000 BauMaterial:earned and UgRBPilz18  
*UgRBPilz20
        name:Warzenpilz
        desc:<.> Beim Klicken des Baumstammes bekommst du <b>3</b> mal so viel!
        icon:iconsa[3,19]
        cost:5000000000000000 BauMaterial
        passive:multiply yield of TreeButton by 3
        req:500000000000000 BauMaterial:earned and UgRBPilz19
*UgRBPilz21
        name:Hautkopf
        desc:<.> Beim Klicken des Baumstammes bekommst du <b>3</b> mal so viel!
        icon:iconsa[3,20]
        cost:10000000000000000 BauMaterial
        passive:multiply yield of TreeButton by 3
        req:2500000000000000 BauMaterial:earned and UgRBPilz20     
        

*UgRBPilzk1
        name:Violettmilchling
        desc:<.> Beim Klicken des Baumstammes bekommst du <b>1</b> BauMaterial mehr!
        icon:iconsa[4,0]
        cost:1000 BauMaterial
        passive:increase yield of TreeButton by 1
        req:10 BauMaterial:earned
*UgRBPilzk2
        name:Schiltrötling
        desc:<.> Beim Klicken des Baumstammes bekommst du <b>1</b> BauMaterial mehr!
        icon:iconsa[4,1]
        cost:10000 BauMaterial
        passive:increase yield of TreeButton by 1
        req:100 BauMaterial:earned and UgRBPilzk1
*UgRBPilzk3
        name:Ockerbovist
        desc:<.> Beim Klicken des Baumstammes bekommst du <b>1</b> BauMaterial mehr!
        icon:iconsa[4,2]
        cost:100000 BauMaterial
        passive:increase yield of TreeButton by 1
        req:1000 BauMaterial:earned and UgRBPilzk2
*UgRBPilzk4
        name:Tugzitterling
        desc:<.> Beim Klicken des Baumstammes bekommst du <b>1</b> BauMaterial mehr!
        icon:iconsa[4,3]
        cost:1000000 BauMaterial
        passive:increase yield of TreeButton by 1
        req:10000 BauMaterial:earned and UgRBPilzk3
*UgRBPilzk5
        name:Schnallen Hauchpilz
        desc:<.> Beim Klicken des Baumstammes bekommst du <b>1</b> BauMaterial mehr!
        icon:iconsa[4,4]
        cost:10000000 BauMaterial
        passive:increase yield of TreeButton by 1
        req:100000 BauMaterial:earned and UgRBPilzk4
*UgRBPilzk6
        name:Roßpilz
        desc:<.> Beim Klicken des Baumstammes bekommst du <b>1</b> BauMaterial mehr!
        icon:iconsa[4,5]
        cost:100000000 BauMaterial
        passive:increase yield of TreeButton by 1
        req:1000000 BauMaterial:earned and UgRBPilzk5

		
		
		
				


*UgbBGras1
		name:Zittergras
		desc:<.> Erhöht die Produktion von Gras um <b>75</b> %.
		icon:icons[2,0] icons[3,0]
		cost:790 BauMaterial
		passive:multiply yield of Gras by 1.75
		req:790 BauMaterial:earned and 1 Gras

*UgbBGras2
		name:Knäuelgras
		desc:<.> Erhöht die Produktion von Gras um <b>75</b> %.
		icon:icons[2,0] icons[3,1]
		cost:7900 BauMaterial
		passive:multiply yield of Gras by 1.75
		req:7900 BauMaterial:earned and UgbBGras1

*UgbBGras3
		name:Pampasgras
		desc:<.> Erhöht die Produktion von Gras um <b>75</b> %.
		icon:icons[2,0] icons[3,2]
		cost:840000 BauMaterial
		passive:multiply yield of Gras by 1.75
		req:840000 BauMaterial:earned and UgbBGras2

*UgbBGras4
		name:Wollgras
		desc:<.> Erhöht die Produktion von Gras um <b>75</b> %.
		icon:icons[2,0] icons[3,3]
		cost:9800000000 BauMaterial
		passive:multiply yield of Gras by 1.75
		req:9800000000 BauMaterial:earned and UgbBGras3

*UgbBGras5
		name:Pfeifengras
		desc:<.> Erhöht die Produktion von Gras um <b>75</b> %.
		icon:icons[2,0] icons[3,4]
		cost:980000000000 BauMaterial
		passive:multiply yield of Gras by 1.75
		req:980000000000 BauMaterial:earned and UgbBGras4

*UgbBGras6
		name:Federborstengras
		desc:<.> Erhöht die Produktion von Gras um <b>75</b> %.
		icon:icons[2,0] icons[3,5]
		cost:98000000000000 BauMaterial
		passive:multiply yield of Gras by 1.75
		req:98000000000000 BauMaterial:earned and UgbBGras5

*UgbBGras7
		name:Grünes Gras
		desc:<.> Erhöht die Produktion von Gras um <b>75</b> %.
		icon:icons[2,0] icons[3,6]
		cost:9800000000000000 BauMaterial
		passive:multiply yield of Gras by 1.75
		req:9800000000000000 BauMaterial:earned and UgbBGras6

*UgbBGras8
		name:Rollrasen
		desc:<.> Erhöht die Produktion von Gras um <b>75</b> %.
		icon:icons[2,0] icons[3,7]
		cost:980000000000000000 BauMaterial
		passive:multiply yield of Gras by 1.75
		req:980000000000000000 BauMaterial:earned and UgbBGras7
		
*UgbBGras9
		name:Lampenputzergras
		desc:<.> Erhöht die Produktion von Gras um <b>75</b> %.
		icon:icons[2,0] icons[3,8]
		cost:98000000000000000000 BauMaterial
		passive:multiply yield of Gras by 1.75
		req:98000000000000000000 BauMaterial:earned and UgbBGras8
		
*UgbBGras10
		name:Timotheusgras
		desc:<.> Erhöht die Produktion von Gras um <b>75</b> %.
		icon:icons[2,0] icons[3,9]
		cost:9800000000000000000000 BauMaterial
		passive:multiply yield of Gras by 1.75
		req:9800000000000000000000 BauMaterial:earned and UgbBGras9
		
*UgbBGras11
		name:Raugras
		desc:<.> Erhöht die Produktion von Gras um <b>75</b> %.
		icon:icons[2,0] icons[3,10]
		cost:980000000000000000000000 BauMaterial
		passive:multiply yield of Gras by 1.75
		req:980000000000000000000000 BauMaterial:earned and UgbBGras10
		
*UgbBGras12
		name:Riesenfedergras
		desc:<.> Erhöht die Produktion von Gras um <b>75</b> %.
		icon:icons[2,0] icons[3,11]
		cost:98000000000000000000000000 BauMaterial
		passive:multiply yield of Gras by 1.75
		req:980000000000000000000000000 BauMaterial:earned and UgbBGras11
		
*UgbBGras13
		name:Rossschweifgras
		desc:<.> Erhöht die Produktion von Gras um <b>75</b> %.
		icon:icons[2,0] icons[3,12]
		cost:9800000000000000000000000000 BauMaterial
		passive:multiply yield of Gras by 1.75
		req:9800000000000000000000000000 BauMaterial:earned and UgbBGras12
	


*UgbBGrasF1
		name:Zittergräser
		desc:<.> Erhöht die Produktion von Gras um <b>75</b> %.
		icon:icons[5,5] icons[2,0] icons[3,0]
		cost:10 Gras
		passive:multiply yield of Gras by 1.75
		req:790 BauMaterial:earned and 1 Gras

*UgbBGrasF2
		name:Knäuelgräser
		desc:<.> Erhöht die Produktion von Gras um <b>75</b> %.
		icon:icons[5,5] icons[2,0] icons[3,1]
		cost:50 Gras
		passive:multiply yield of Gras by 1.75
		req:79000 BauMaterial:earned and UgbBGrasF1

*UgbBGrasF3
		name:Pampasgräser
		desc:<.> Erhöht die Produktion von Gras um <b>75</b> %.
		icon:icons[5,5] icons[2,0] icons[3,2]
		cost:100 Gras
		passive:multiply yield of Gras by 1.75
		req:8400000 BauMaterial:earned and UgbBGrasF2

*UgbBGrasF4
		name:Wollgräser
		desc:<.> Erhöht die Produktion von Gras um <b>75</b> %.
		icon:icons[5,5] icons[2,0] icons[3,3]
		cost:125 Gras
		passive:multiply yield of Gras by 1.75
		req:98000000000 BauMaterial:earned and UgbBGrasF3

*UgbBGrasF5
		name:Pfeifengräser
		desc:<.> Erhöht die Produktion von Gras um <b>75</b> %.
		icon:icons[5,5] icons[2,0] icons[3,4]
		cost:150 Gras
		passive:multiply yield of Gras by 1.75
		req:9800000000000 BauMaterial:earned and UgbBGrasF4

*UgbBGrasF6
		name:Federborstengräser
		desc:<.> Erhöht die Produktion von Gras um <b>75</b> %.
		icon:icons[5,5] icons[2,0] icons[3,5]
		cost:175 Gras
		passive:multiply yield of Gras by 1.75
		req:980000000000000 BauMaterial:earned and UgbBGrasF5

*UgbBGrasF7
		name:Grüne Gräser
		desc:<.> Erhöht die Produktion von Gras um <b>75</b> %.
		icon:icons[5,5] icons[2,0] icons[3,6]
		cost:200 Gras
		passive:multiply yield of Gras by 1.75
		req:98000000000000000 BauMaterial:earned and UgbBGrasF6

*UgbBGrasF8
		name:Rollrasenmatten
		desc:<.> Erhöht die Produktion von Gras um <b>75</b> %.
		icon:icons[5,5] icons[2,0] icons[3,7]
		cost:225 Gras
		passive:multiply yield of Gras by 1.75
		req:9800000000000000000 BauMaterial:earned and UgbBGrasF7
		
*UgbBGrasF9
		name:Lampenputzergräser
		desc:<.> Erhöht die Produktion von Gras um <b>75</b> %.
		icon:icons[5,5] icons[2,0] icons[3,8]
		cost:250 Gras
		passive:multiply yield of Gras by 1.75
		req:980000000000000000000 BauMaterial:earned and UgbBGrasF8
		
*UgbBGrasF10
		name:Timotheusgräser
		desc:<.> Erhöht die Produktion von Gras um <b>75</b> %.
		icon:icons[5,5] icons[2,0] icons[3,9]
		cost:275 Gras
		passive:multiply yield of Gras by 1.75
		req:98000000000000000000000 BauMaterial:earned and UgbBGrasF9
		
*UgbBGrasF11
		name:Raugräser
		desc:<.> Erhöht die Produktion von Gras um <b>75</b> %.
		icon:icons[5,5] icons[2,0] icons[3,10]
		cost:300 Gras
		passive:multiply yield of Gras by 1.75
		req:9800000000000000000000000 BauMaterial:earned and UgbBGrasF10
		
*UgbBGrasF12
		name:Riesenfedergräser
		desc:<.> Erhöht die Produktion von Gras um <b>75</b> %.
		icon:icons[5,5] icons[2,0] icons[3,11]
		cost:325 Gras
		passive:multiply yield of Gras by 1.75
		req:980000000000000000000000000 BauMaterial:earned and UgbBGrasF11
		
*UgbBGrasF13
		name:Rossschweifgräser
		desc:<.> Erhöht die Produktion von Gras um <b>75</b> %.
		icon:icons[5,5] icons[2,0] icons[3,12]
		cost:350 Gras
		passive:multiply yield of Gras by 1.75
		req:98000000000000000000000000000 BauMaterial:earned and UgbBGrasF12
	





//1	


*UgbBGrasA1
		name:Gras Sammler
		desc:<.> Erhöht die Produktion von Gras um <b>75</b> %.
		icon:icons[5,5] iconsa[1,0]
		cost:10 Ameisen,10 SammlerAmeisen
		passive:multiply yield of Gras by 1.75
		req:790 BauMaterial:earned and 1 Gras

*UgbBGrasA2
		name:Mehr Sammler
		desc:<.> Erhöht die Produktion von Gras um <b>75</b> %.
		icon:icons[5,5] iconsa[1,1]
		cost:19 Ameisen,19 SammlerAmeisen
		passive:multiply yield of Gras by 1.75
		req:UgbBGrasA1

*UgbBGrasA3
		name:Mehr Arbeiter
		desc:<.> Erhöht die Produktion von Gras um <b>75</b> %.
		icon:icons[5,5] iconsa[1,2]
		cost:42 Ameisen,42 SammlerAmeisen
		passive:multiply yield of Gras by 1.75
		req:UgbBGrasA2

*UgbBGrasA4
		name:Mehr Träger
		desc:<.> Erhöht die Produktion von Gras um <b>75</b> %.
		icon:icons[5,5] iconsa[1,3]
		cost:50 Ameisen,50 SammlerAmeisen
		passive:multiply yield of Gras by 1.75
		req:UgbBGrasA3

*UgbBGrasA5
		name:Logistiker
		desc:<.> Erhöht die Produktion von Gras um <b>75</b> %.
		icon:icons[5,5] iconsa[1,4]
		cost:75 Ameisen,75 SammlerAmeisen
		passive:multiply yield of Gras by 1.75
		req:UgbBGrasA4

*UgbBGrasA6
		name:Ingenieure
		desc:<.> Erhöht die Produktion von Gras um <b>75</b> %.
		icon:icons[5,5] iconsa[1,5]
		cost:100 Ameisen,100 SammlerAmeisen
		passive:multiply yield of Gras by 1.75
		req:UgbBGrasA5

*UgbBGrasA7
		name:Statiker
		desc:<.> Erhöht die Produktion von Gras um <b>75</b> %.
		icon:icons[5,5] iconsa[1,6]
		cost:125 Ameisen,125 SammlerAmeisen
		passive:multiply yield of Gras by 1.75
		req:UgbBGrasA6

*UgbBGrasA8
		name:Bauplaner
		desc:<.> Erhöht die Produktion von Gras um <b>75</b> %.
		icon:icons[5,5] iconsa[1,7]
		cost:150 Ameisen,150 SammlerAmeisen
		passive:multiply yield of Gras by 1.75
		req:UgbBGrasA7
		
*UgbBGrasA9
		name:Transporter
		desc:<.> Erhöht die Produktion von Gras um <b>75</b> %.
		icon:icons[5,5] iconsa[1,8]
		cost:175 Ameisen,175 SammlerAmeisen
		passive:multiply yield of Gras by 1.75
		req:UgbBGrasA8
		
*UgbBGrasA10
		name:Transportunternehmen
		desc:<.> Erhöht die Produktion von Gras um <b>75</b> %.
		icon:icons[5,5] iconsa[1,9]
		cost:200 Ameisen,200 SammlerAmeisen
		passive:multiply yield of Gras by 1.75
		req:UgbBGrasA9
		
*UgbBGrasA11
		name:Minivan
		desc:<.> Erhöht die Produktion von Gras um <b>75</b> %.
		icon:icons[5,5] iconsa[1,10]
		cost:225 Ameisen,225 SammlerAmeisen
		passive:multiply yield of Gras by 1.75
		req:UgbBGrasA10
		
*UgbBGrasA12
		name:LKW
		desc:<.> Erhöht die Produktion von Gras um <b>75</b> %.
		icon:icons[5,5] iconsa[1,11]
		cost:250 Ameisen,250 SammlerAmeisen
		passive:multiply yield of Gras by 1.75
		req:UgbBGrasA11
		
*UgbBGrasA13
		name:Transportesel
		desc:<.> Erhöht die Produktion von Gras um <b>75</b> %.
		icon:icons[5,5] iconsa[1,12]
		cost:275 Ameisen,275 SammlerAmeisen
		passive:multiply yield of Gras by 1.75
		req:UgbBGrasA12
		
*UgbBGrasA14
		name:Lasttier
		desc:<.> Erhöht die Produktion von Gras um <b>75</b> %.
		icon:icons[5,5] iconsa[1,12]
		cost:300 Ameisen,300 SammlerAmeisen
		passive:multiply yield of Gras by 1.75
		req:UgbBGrasA13
		
		
	
	
*UgbBAst1
		name:Ästling
		desc:<.> Erhöht die Produktion von Ästen um <b>75</b> %.
		icon:icons[2,1] icons[3,0]
		cost:1111 BauMaterial,10 Gras
		passive:multiply yield of Ast by 1.75
		req:11111 BauMaterial:earned and 9 Ast

*UgbBAst2
		name:Zweig
		desc:<.> Erhöht die Produktion von Ästen um <b>75</b> %.
		icon:icons[2,1] icons[3,1]
		cost:1111100 BauMaterial,20 Gras
		passive:multiply yield of Ast by 1.75
		req:111110 BauMaterial:earned and 45 Ast and UgbBAst1
		
*UgbBAst3
		name:Stock
		desc:<.> Erhöht die Produktion von Ästen um <b>75</b> %.
		icon:icons[2,1] icons[3,2]
		cost:11111000 BauMaterial,30 Gras
		passive:multiply yield of Ast by 1.75
		req:11111000 BauMaterial:earned and 75 Ast and UgbBAst2
		
*UgbBAst4
		name:Stecken
		desc:<.> Erhöht die Produktion von Ästen um <b>75</b> %.
		icon:icons[2,1] icons[3,3]
		cost:1111100000 BauMaterial,40 Gras
		passive:multiply yield of Ast by 1.75
		req:1111100000 BauMaterial:earned and 100 Ast and UgbBAst3
		
*UgbBAst5
		name:Blätterzweig
		desc:<.> Erhöht die Produktion von Ästen um <b>75</b> %.
		icon:icons[2,1] icons[3,4]
		cost:111110000000 BauMaterial,50 Gras
		passive:multiply yield of Ast by 1.75
		req:111110000000 BauMaterial:earned and 125 Ast and UgbBAst4
		
*UgbBAst6
		name:Dicker Ast
		desc:<.> Erhöht die Produktion von Ästen um <b>75</b> %.
		icon:icons[2,1] icons[3,5]
		cost:11111000000000 BauMaterial,75 Gras
		passive:multiply yield of Ast by 1.75
		req:11111000000000 BauMaterial:earned and 150 Ast and UgbBAst5
		
*UgbBAst7
		name:Astgabel
		desc:<.> Erhöht die Produktion von Ästen um <b>75</b> %.
		icon:icons[2,1] icons[3,6]
		cost:1111100000000000 BauMaterial,100 Gras
		passive:multiply yield of Ast by 1.75
		req:1111100000000000 BauMaterial:earned and 175 Ast and UgbBAst6
			
*UgbBAst8
		name:Astlöffel
		desc:<.> Erhöht die Produktion von Ästen um <b>75</b> %.
		icon:icons[2,1] icons[3,7]
		cost:111110000000000000 BauMaterial,125 Gras
		passive:multiply yield of Ast by 1.75
		req:111110000000000000 BauMaterial:earned and 200 Ast and UgbBAst7
			
*UgbBAst9
		name:Astbündel
		desc:<.> Erhöht die Produktion von Ästen um <b>75</b> %.
		icon:icons[2,1] icons[3,8]
		cost:11111000000000000000 BauMaterial,150 Gras
		passive:multiply yield of Ast by 1.75
		req:11111000000000000000 BauMaterial:earned and 225 Ast and UgbBAst8
			
*UgbBAst10
		name:Toter Ast
		desc:<.> Erhöht die Produktion von Ästen um <b>75</b> %.
		icon:icons[2,1] icons[3,9]
		cost:1111100000000000000000 BauMaterial,175 Gras
		passive:multiply yield of Ast by 1.75
		req:1111100000000000000000 BauMaterial:earned and 250 Ast and UgbBAst9
			
*UgbBAst11
		name:Morscher Ast
		desc:<.> Erhöht die Produktion von Ästen um <b>75</b> %.
		icon:icons[2,1] icons[3,10]
		cost:111110000000000000000000 BauMaterial,200 Gras
		passive:multiply yield of Ast by 1.75
		req:111110000000000000000000 BauMaterial:earned and 275 Ast and UgbBAst10
			
*UgbBAst12
		name:Astoteles
		desc:<.> Erhöht die Produktion von Ästen um <b>75</b> %.
		icon:icons[2,1] icons[3,11]
		cost:11111000000000000000000000 BauMaterial,225 Gras
		passive:multiply yield of Ast by 1.75
		req:11111000000000000000000000 BauMaterial:earned and 300 Ast and UgbBAst11
	

*UgbBAstF1
		name:Ästlinge
		desc:<.> Erhöht die Produktion von Ästen um <b>75</b> %.
		icon:icons[5,5] icons[2,1] icons[3,0]
		cost:10 Ast
		passive:multiply yield of Ast by 1.75
		req:11111 BauMaterial:earned and 9 Ast

*UgbBAstF2
		name:Zweige
		desc:<.> Erhöht die Produktion von Ästen um <b>75</b> %.
		icon:icons[5,5] icons[2,1] icons[3,1]
		cost:50 Ast
		passive:multiply yield of Ast by 1.75
		req:1111100 BauMaterial:earned and 45 Ast and UgbBAstF1
		
*UgbBAstF3
		name:Stöcke
		desc:<.> Erhöht die Produktion von Ästen um <b>75</b> %.
		icon:icons[5,5] icons[2,1] icons[3,2]
		cost:100 Ast
		passive:multiply yield of Ast by 1.75
		req:111110000 BauMaterial:earned and 75 Ast and UgbBAstF2
		
*UgbBAstF4
		name:Spazierstock
		desc:<.> Erhöht die Produktion von Ästen um <b>75</b> %.
		icon:icons[5,5] icons[2,1] icons[3,3]
		cost:125 Ast
		passive:multiply yield of Ast by 1.75
		req:11111000000 BauMaterial:earned and 100 Ast and UgbBAstF3
		
*UgbBAstF5
		name:Blätterzweigling
		desc:<.> Erhöht die Produktion von Ästen um <b>75</b> %.
		icon:icons[5,5] icons[2,1] icons[3,4]
		cost:150 Ast
		passive:multiply yield of Ast by 1.75
		req:1111100000000 BauMaterial:earned and 125 Ast and UgbBAstF4
		
*UgbBAstF6
		name:Dicke Äste
		desc:<.> Erhöht die Produktion von Ästen um <b>75</b> %.
		icon:icons[5,5] icons[2,1] icons[3,5]
		cost:175 Ast
		passive:multiply yield of Ast by 1.75
		req:111110000000000 BauMaterial:earned and 150 Ast and UgbBAstF5
		
*UgbBAstF7
		name:Astgabelungen
		desc:<.> Erhöht die Produktion von Ästen um <b>75</b> %.
		icon:icons[5,5] icons[2,1] icons[3,6]
		cost:200 Ast
		passive:multiply yield of Ast by 1.75
		req:11111000000000000 BauMaterial:earned and 175 Ast and UgbBAstF6
			
*UgbBAstF8
		name:Astlöffele
		desc:<.> Erhöht die Produktion von Ästen um <b>75</b> %.
		icon:icons[5,5] icons[2,1] icons[3,7]
		cost:225 Ast
		passive:multiply yield of Ast by 1.75
		req:1111100000000000000 BauMaterial:earned and 200 Ast and UgbBAstF7
			
*UgbBAstF9
		name:Zerbrochener Ast
		desc:<.> Erhöht die Produktion von Ästen um <b>75</b> %.
		icon:icons[5,5] icons[2,1] icons[3,8]
		cost:250 Ast
		passive:multiply yield of Ast by 1.75
		req:111110000000000000000 BauMaterial:earned and 225 Ast and UgbBAstF8
			
*UgbBAstF10
		name:Tote Äste
		desc:<.> Erhöht die Produktion von Ästen um <b>75</b> %.
		icon:icons[5,5] icons[2,1] icons[3,9]
		cost:275 Ast
		passive:multiply yield of Ast by 1.75
		req:11111000000000000000000 BauMaterial:earned and 250 Ast and UgbBAstF9
			
*UgbBAstF11
		name:Morsche Äste
		desc:<.> Erhöht die Produktion von Ästen um <b>75</b> %.
		icon:icons[5,5] icons[2,1] icons[3,10]
		cost:300 Ast
		passive:multiply yield of Ast by 1.75
		req:1111100000000000000000000 BauMaterial:earned and 275 Ast and UgbBAstF10
			
*UgbBAstF12
		name:Astreich
		desc:<.> Erhöht die Produktion von Ästen um <b>75</b> %.
		icon:icons[5,5] icons[2,1] icons[3,11]
		cost:325 Ast
		passive:multiply yield of Ast by 1.75
		req:111110000000000000000000000 BauMaterial:earned and 300 Ast and UgbBAstF11
	
	
	

*UgbBWurzeln1
		name:Baumwurzel
		desc:<.> Erhöht die Produktion von Wurzeln um <b>75</b> %.
		icon:icons[2,2] icons[3,0]
		cost:89600 BauMaterial,10 Ast
		passive:multiply yield of Wurzeln by 1.75
		req:89600 BauMaterial:earned and 9 Wurzeln

*UgbBWurzeln2
		name:Kleine Wurzel
		desc:<.> Erhöht die Produktion von Wurzeln um <b>75</b> %.
		icon:icons[2,2] icons[3,1]
		cost:8960000 BauMaterial,20 Ast
		passive:multiply yield of Wurzeln by 1.75
		req:8960000 BauMaterial:earned and 45 Wurzeln
		
*UgbBWurzeln3
		name:Knollenwurzel
		desc:<.> Erhöht die Produktion von Wurzeln um <b>75</b> %.
		icon:icons[2,2] icons[3,2]
		cost:896000000 BauMaterial,30 Ast
		passive:multiply yield of Wurzeln by 1.75
		req:896000000 BauMaterial:earned and 75 Wurzeln
		
*UgbBWurzeln4
		name:Fadenwurzel
		desc:<.> Erhöht die Produktion von Wurzeln um <b>75</b> %.
		icon:icons[2,2] icons[3,3]
		cost:89600000000 BauMaterial,40 Ast
		passive:multiply yield of Wurzeln by 1.75
		req:89600000000 BauMaterial:earned and 100 Wurzeln
		
*UgbBWurzeln5
		name:Graswurzel
		desc:<.> Erhöht die Produktion von Wurzeln um <b>75</b> %.
		icon:icons[2,2] icons[3,4]
		cost:8960000000000 BauMaterial,50 Ast
		passive:multiply yield of Wurzeln by 1.75
		req:8960000000000 BauMaterial:earned and 125 Wurzeln
		
*UgbBWurzeln6
		name:Unkrautwurzel
		desc:<.> Erhöht die Produktion von Wurzeln um <b>75</b> %.
		icon:icons[2,2] icons[3,5]
		cost:896000000000000 BauMaterial,75 Ast
		passive:multiply yield of Wurzeln by 1.75
		req:896000000000000 BauMaterial:earned and 150 Wurzeln
		
*UgbBWurzeln7
		name:Dicke Wurzel
		desc:<.> Erhöht die Produktion von Wurzeln um <b>75</b> %.
		icon:icons[2,2] icons[3,6]
		cost:89600000000000000 BauMaterial,100 Ast
		passive:multiply yield of Wurzeln by 1.75
		req:89600000000000000 BauMaterial:earned and 175 Wurzeln
			
*UgbBWurzeln8
		name:Feine Wurzel
		desc:<.> Erhöht die Produktion von Wurzeln um <b>75</b> %.
		icon:icons[2,2] icons[3,7]
		cost:8960000000000000000 BauMaterial,125 Ast
		passive:multiply yield of Wurzeln by 1.75
		req:8960000000000000000 BauMaterial:earned and 200 Wurzeln
			
*UgbBWurzeln9
		name:Kaputte Wurzel
		desc:<.> Erhöht die Produktion von Wurzeln um <b>75</b> %.
		icon:icons[2,2] icons[3,8]
		cost:896000000000000000000 BauMaterial,150 Ast
		passive:multiply yield of Wurzeln by 1.75
		req:896000000000000000000 BauMaterial:earned and 225 Wurzeln
			
*UgbBWurzeln10
		name:Feste Wurzel
		desc:<.> Erhöht die Produktion von Wurzeln um <b>75</b> %.
		icon:icons[2,2] icons[3,9]
		cost:89600000000000000000000 BauMaterial,175 Ast
		passive:multiply yield of Wurzeln by 1.75
		req:89600000000000000000000 BauMaterial:earned and 250 Wurzeln
			
*UgbBWurzeln11
		name:Morsche Wurzel
		desc:<.> Erhöht die Produktion von Wurzeln um <b>75</b> %.
		icon:icons[2,2] icons[3,10]
		cost:8960000000000000000000000 BauMaterial,200 Ast
		passive:multiply yield of Wurzeln by 1.75
		req:8960000000000000000000000 BauMaterial:earned and 275 Wurzeln
			
*UgbBWurzeln12
		name:Tiefe Wurzel
		desc:<.> Erhöht die Produktion von Wurzeln um <b>75</b> %.
		icon:icons[2,2] icons[3,11]
		cost:896000000000000000000000000 BauMaterial,225 Ast
		passive:multiply yield of Wurzeln by 1.75
		req:896000000000000000000000000 BauMaterial:earned and 300 Wurzeln
	


*UgbBWurzelnF1
		name:Baumwurzeln
		desc:<.> Erhöht die Produktion von Wurzeln um <b>75</b> %.
		icon:icons[5,5] icons[2,2] icons[3,0]
		cost:10 Wurzeln
		passive:multiply yield of Wurzeln by 1.75
		req:89600 BauMaterial:earned and 9 Wurzeln

*UgbBWurzelnF2
		name:Kleine Wurzeln
		desc:<.> Erhöht die Produktion von Wurzeln um <b>75</b> %.
		icon:icons[5,5] icons[2,2] icons[3,1]
		cost:50 Wurzeln
		passive:multiply yield of Wurzeln by 1.75
		req:8960000 BauMaterial:earned and 45 Wurzeln
		
*UgbBWurzelnF3
		name:Knollenwurzeln
		desc:<.> Erhöht die Produktion von Wurzeln um <b>75</b> %.
		icon:icons[5,5] icons[2,2] icons[3,2]
		cost:100 Wurzeln
		passive:multiply yield of Wurzeln by 1.75
		req:896000000 BauMaterial:earned and 75 Wurzeln
		
*UgbBWurzelnF4
		name:Fadenwurzeln
		desc:<.> Erhöht die Produktion von Wurzeln um <b>75</b> %.
		icon:icons[5,5] icons[2,2] icons[3,3]
		cost:125 Wurzeln
		passive:multiply yield of Wurzeln by 1.75
		req:89600000000 BauMaterial:earned and 100 Wurzeln
		
*UgbBWurzelnF5
		name:Graswurzeln
		desc:<.> Erhöht die Produktion von Wurzeln um <b>75</b> %.
		icon:icons[5,5] icons[2,2] icons[3,4]
		cost:150 Wurzeln
		passive:multiply yield of Wurzeln by 1.75
		req:8960000000000 BauMaterial:earned and 125 Wurzeln
		
*UgbBWurzelnF6
		name:Unkrautwurzeln
		desc:<.> Erhöht die Produktion von Wurzeln um <b>75</b> %.
		icon:icons[5,5] icons[2,2] icons[3,5]
		cost:175 Wurzeln
		passive:multiply yield of Wurzeln by 1.75
		req:896000000000000 BauMaterial:earned and 150 Wurzeln
		
*UgbBWurzelnF7
		name:Dicke Wurzeln
		desc:<.> Erhöht die Produktion von Wurzeln um <b>75</b> %.
		icon:icons[5,5] icons[2,2] icons[3,6]
		cost:200 Wurzeln
		passive:multiply yield of Wurzeln by 1.75
		req:89600000000000000 BauMaterial:earned and 175 Wurzeln
			
*UgbBWurzelnF8
		name:Feine Wurzeln
		desc:<.> Erhöht die Produktion von Wurzeln um <b>75</b> %.
		icon:icons[5,5] icons[2,2] icons[3,7]
		cost:225 Wurzeln
		passive:multiply yield of Wurzeln by 1.75
		req:8960000000000000000 BauMaterial:earned and 200 Wurzeln
			
*UgbBWurzelnF9
		name:Kaputte Wurzeln
		desc:<.> Erhöht die Produktion von Wurzeln um <b>75</b> %.
		icon:icons[5,5] icons[2,2] icons[3,8]
		cost:250 Wurzeln
		passive:multiply yield of Wurzeln by 1.75
		req:896000000000000000000 BauMaterial:earned and 225 Wurzeln
			
*UgbBWurzelnF10
		name:Feste Wurzeln
		desc:<.> Erhöht die Produktion von Wurzeln um <b>75</b> %.
		icon:icons[5,5] icons[2,2] icons[3,9]
		cost:275 Wurzeln
		passive:multiply yield of Wurzeln by 1.75
		req:89600000000000000000000 BauMaterial:earned and 250 Wurzeln
			
*UgbBWurzelnF11
		name:Morsche Wurzeln
		desc:<.> Erhöht die Produktion von Wurzeln um <b>75</b> %.
		icon:icons[5,5] icons[2,2] icons[3,10]
		cost:300 Wurzeln
		passive:multiply yield of Wurzeln by 1.75
		req:8960000000000000000000000 BauMaterial:earned and 275 Wurzeln
			
*UgbBWurzelnF12
		name:Tiefe Wurzeln
		desc:<.> Erhöht die Produktion von Wurzeln um <b>75</b> %.
		icon:icons[5,5] icons[2,2] icons[3,11]
		cost:325 Wurzeln
		passive:multiply yield of Wurzeln by 1.75
		req:896000000000000000000000000 BauMaterial:earned and 300 Wurzeln
		
	

*UgbBSteine1
		name:Kieselstein
		desc:<.> Erhöht die Produktion von Steinen um <b>75</b> %.
		icon:icons[2,3] icons[3,0]
		cost:912900 BauMaterial,10 Wurzeln
		passive:multiply yield of Steine by 1.75
		req:912900 BauMaterial:earned and 9 Steine

*UgbBSteine2
		name:Backstein
		desc:<.> Erhöht die Produktion von Steinen um <b>75</b> %.
		icon:icons[2,3] icons[3,1]
		cost:91290000 BauMaterial,20 Wurzeln
		passive:multiply yield of Steine by 1.75
		req:91290000 BauMaterial:earned and 45 Steine
		
*UgbBSteine3
		name:Scharfer Stein
		desc:<.> Erhöht die Produktion von Steinen um <b>75</b> %.
		icon:icons[2,3] icons[3,2]
		cost:9129000000 BauMaterial,30 Wurzeln
		passive:multiply yield of Steine by 1.75
		req:9129000000 BauMaterial:earned and 75 Steine
		
*UgbBSteine4
		name:Runder Stein
		desc:<.> Erhöht die Produktion von Steinen um <b>75</b> %.
		icon:icons[2,3] icons[3,3]
		cost:912900000000 BauMaterial,40 Wurzeln
		passive:multiply yield of Steine by 1.75
		req:912900000000 BauMaterial:earned and 100 Steine
		
*UgbBSteine5
		name:Glitzerstein
		desc:<.> Erhöht die Produktion von Steinen um <b>75</b> %.
		icon:icons[2,3] icons[3,4]
		cost:91290000000000 BauMaterial,50 Wurzeln
		passive:multiply yield of Steine by 1.75
		req:91290000000000 BauMaterial:earned and 125 Steine
		
*UgbBSteine6
		name:Dreckiger Stein
		desc:<.> Erhöht die Produktion von Steinen um <b>75</b> %.
		icon:icons[2,3] icons[3,5]
		cost:9129000000000000 BauMaterial,75 Wurzeln
		passive:multiply yield of Steine by 1.75
		req:9129000000000000 BauMaterial:earned and 150 Steine
		
*UgbBSteine7
		name:Glänzender Stein
		desc:<.> Erhöht die Produktion von Steinen um <b>75</b> %.
		icon:icons[2,3] icons[3,6]
		cost:912900000000000000 BauMaterial,100 Wurzeln
		passive:multiply yield of Steine by 1.75
		req:912900000000000000 BauMaterial:earned and 175 Steine
			
*UgbBSteine8
		name:Großer Stein
		desc:<.> Erhöht die Produktion von Steinen um <b>75</b> %.
		icon:icons[2,3] icons[3,7]
		cost:91290000000000000000 BauMaterial,125 Wurzeln
		passive:multiply yield of Steine by 1.75
		req:91290000000000000000 BauMaterial:earned and 200 Steine
			
*UgbBSteine9
		name:Versteckter Stein
		desc:<.> Erhöht die Produktion von Steinen um <b>75</b> %.
		icon:icons[2,3] icons[3,8]
		cost:9129000000000000000000 BauMaterial,150 Wurzeln
		passive:multiply yield of Steine by 1.75
		req:9129000000000000000000 BauMaterial:earned and 225 Steine
			
*UgbBSteine10
		name:Steinhaufen
		desc:<.> Erhöht die Produktion von Steinen um <b>75</b> %.
		icon:icons[2,3] icons[3,9]
		cost:912900000000000000000000 BauMaterial,175 Wurzeln
		passive:multiply yield of Steine by 1.75
		req:912900000000000000000000 BauMaterial:earned and 250 Steine
			
*UgbBSteine11
		name:Steinnest
		desc:<.> Erhöht die Produktion von Steinen um <b>75</b> %.
		icon:icons[2,3] icons[3,10]
		cost:91290000000000000000000000 BauMaterial,200 Wurzeln
		passive:multiply yield of Steine by 1.75
		req:91290000000000000000000000 BauMaterial:earned and 275 Steine
			
*UgbBSteine12
		name:Steinreich
		desc:<.> Erhöht die Produktion von Steinen um <b>75</b> %.
		icon:icons[2,3] icons[3,11]
		cost:9129000000000000000000000000 BauMaterial,225 Wurzeln
		passive:multiply yield of Steine by 1.75
		req:9129000000000000000000000000 BauMaterial:earned and 300 Steine



*UgbBSteineF1
		name:Glitzernde Kieselsteine
		desc:<.> Erhöht die Produktion von Steinen um <b>75</b> %.
		icon:icons[5,5] icons[2,3] icons[3,0]
		cost:10 Steine
		passive:multiply yield of Steine by 1.75
		req:912900 BauMaterial:earned and 9 Steine

*UgbBSteineF2
		name:rote Backsteine
		desc:<.> Erhöht die Produktion von Steinen um <b>75</b> %.
		icon:icons[5,5] icons[2,3] icons[3,1]
		cost:50 Steine
		passive:multiply yield of Steine by 1.75
		req:91290000 BauMaterial:earned and 45 Steine
		
*UgbBSteineF3
		name:Scharfe Steine
		desc:<.> Erhöht die Produktion von Steinen um <b>75</b> %.
		icon:icons[5,5] icons[2,3] icons[3,2]
		cost:100 Steine
		passive:multiply yield of Steine by 1.75
		req:9129000000 BauMaterial:earned and 75 Steine
		
*UgbBSteineF4
		name:Runde Steine
		desc:<.> Erhöht die Produktion von Steinen um <b>75</b> %.
		icon:icons[5,5] icons[2,3] icons[3,3]
		cost:125 Steine
		passive:multiply yield of Steine by 1.75
		req:912900000000 BauMaterial:earned and 100 Steine
		
*UgbBSteineF5
		name:Glitzersteine
		desc:<.> Erhöht die Produktion von Steinen um <b>75</b> %.
		icon:icons[5,5] icons[2,3] icons[3,4]
		cost:150 Steine
		passive:multiply yield of Steine by 1.75
		req:91290000000000 BauMaterial:earned and 125 Steine
		
*UgbBSteineF6
		name:Dreckige Steine
		desc:<.> Erhöht die Produktion von Steinen um <b>75</b> %.
		icon:icons[5,5] icons[2,3] icons[3,5]
		cost:175 Steine
		passive:multiply yield of Steine by 1.75
		req:9129000000000000 BauMaterial:earned and 150 Steine
		
*UgbBSteineF7
		name:Glänzende Steine
		desc:<.> Erhöht die Produktion von Steinen um <b>75</b> %.
		icon:icons[5,5] icons[2,3] icons[3,6]
		cost:200 Steine
		passive:multiply yield of Steine by 1.75
		req:912900000000000000 BauMaterial:earned and 175 Steine
			
*UgbBSteineF8
		name:Große Steine
		desc:<.> Erhöht die Produktion von Steinen um <b>75</b> %.
		icon:icons[5,5] icons[2,3] icons[3,7]
		cost:225 Steine
		passive:multiply yield of Steine by 1.75
		req:91290000000000000000 BauMaterial:earned and 200 Steine
			
*UgbBSteineF9
		name:Versteckte Steine
		desc:<.> Erhöht die Produktion von Steinen um <b>75</b> %.
		icon:icons[5,5] icons[2,3] icons[3,8]
		cost:250 Steine
		passive:multiply yield of Steine by 1.75
		req:9129000000000000000000 BauMaterial:earned and 225 Steine
			
*UgbBSteineF10
		name:Zerbrachener Stein
		desc:<.> Erhöht die Produktion von Steinen um <b>75</b> %.
		icon:icons[5,5] icons[2,3] icons[3,9]
		cost:275 Steine
		passive:multiply yield of Steine by 1.75
		req:912900000000000000000000 BauMaterial:earned and 250 Steine
			
*UgbBSteineF11
		name:Steinnester
		desc:<.> Erhöht die Produktion von Steinen um <b>75</b> %.
		icon:icons[5,5] icons[2,3] icons[3,10]
		cost:300 Steine
		passive:multiply yield of Steine by 1.75
		req:91290000000000000000000000 BauMaterial:earned and 275 Steine
			
*UgbBSteineF12
		name:Steinigung
		desc:<.> Erhöht die Produktion von Steinen um <b>75</b> %.
		icon:icons[5,5] icons[2,3] icons[3,11]
		cost:325 Steine
		passive:multiply yield of Steine by 1.75
		req:9129000000000000000000000000 BauMaterial:earned and 300 Steine
				

*UgbBDreck1
		name:Nasser Dreck
		desc:<.> Erhöht die Produktion von Dreck um <b>75</b> %.
		icon:icons[2,4] icons[3,0]
		cost:9230000 BauMaterial,10 Steine
		passive:multiply yield of Dreck by 1.75
		req:9230000 BauMaterial:earned and 9 Dreck

*UgbBDreck2
		name:Staubiger Dreck
		desc:<.> Erhöht die Produktion von Dreck um <b>75</b> %.
		icon:icons[2,4] icons[3,1]
		cost:923000000 BauMaterial,20 Steine
		passive:multiply yield of Dreck by 1.75
		req:923000000 BauMaterial:earned and 45 Dreck
		
*UgbBDreck3
		name:Matschiger Dreck
		desc:<.> Erhöht die Produktion von Dreck um <b>75</b> %.
		icon:icons[2,4] icons[3,2]
		cost:92300000000 BauMaterial,30 Steine
		passive:multiply yield of Dreck by 1.75
		req:92300000000 BauMaterial:earned and 75 Dreck
		
*UgbBDreck4
		name:Klumpiger Dreck
		desc:<.> Erhöht die Produktion von Dreck um <b>75</b> %.
		icon:icons[2,4] icons[3,3]
		cost:9230000000000 BauMaterial,40 Steine
		passive:multiply yield of Dreck by 1.75
		req:9230000000000 BauMaterial:earned and 100 Dreck
		
*UgbBDreck5
		name:Viel Dreck
		desc:<.> Erhöht die Produktion von Dreck um <b>75</b> %.
		icon:icons[2,4] icons[3,4]
		cost:923000000000000 BauMaterial,50 Steine
		passive:multiply yield of Dreck by 1.75
		req:923000000000000 BauMaterial:earned and 125 Dreck
		
*UgbBDreck6
		name:Grober Dreck
		desc:<.> Erhöht die Produktion von Dreck um <b>75</b> %.
		icon:icons[2,4] icons[3,5]
		cost:92300000000000000 BauMaterial,75 Steine
		passive:multiply yield of Dreck by 1.75
		req:92300000000000000 BauMaterial:earned and 150 Dreck
		
*UgbBDreck7
		name:Feiner Dreck
		desc:<.> Erhöht die Produktion von Dreck um <b>75</b> %.
		icon:icons[2,4] icons[3,6]
		cost:9230000000000000000 BauMaterial,100 Steine
		passive:multiply yield of Dreck by 1.75
		req:9230000000000000000 BauMaterial:earned and 175 Dreck
			
*UgbBDreck8
		name:Drecks Sack
		desc:<.> Erhöht die Produktion von Dreck um <b>75</b> %.
		icon:icons[2,4] icons[3,7]
		cost:923000000000000000000 BauMaterial,125 Steine
		passive:multiply yield of Dreck by 1.75
		req:923000000000000000000 BauMaterial:earned and 200 Dreck
			
*UgbBDreck9
		name:Harter Dreck
		desc:<.> Erhöht die Produktion von Dreck um <b>75</b> %.
		icon:icons[2,4] icons[3,8]
		cost:92300000000000000000000 BauMaterial,150 Steine
		passive:multiply yield of Dreck by 1.75
		req:92300000000000000000000 BauMaterial:earned and 225 Dreck
			
*UgbBDreck10
		name:Dreckonia
		desc:<.> Erhöht die Produktion von Dreck um <b>75</b> %.
		icon:icons[2,4] icons[3,9]
		cost:9230000000000000000000000 BauMaterial,175 Steine
		passive:multiply yield of Dreck by 1.75
		req:9230000000000000000000000 BauMaterial:earned and 250 Dreck
			
*UgbBDreck11
		name:Humus
		desc:<.> Erhöht die Produktion von Dreck um <b>75</b> %.
		icon:icons[2,4] icons[3,10]
		cost:923000000000000000000000000 BauMaterial,200 Steine
		passive:multiply yield of Dreck by 1.75
		req:923000000000000000000000000 BauMaterial:earned and 275 Dreck
			
*UgbBDreck12
		name:Lehm
		desc:<.> Erhöht die Produktion von Dreck um <b>75</b> %.
		icon:icons[2,4] icons[3,11]
		cost:92300000000000000000000000000 BauMaterial,225 Steine
		passive:multiply yield of Dreck by 1.75
		req:92300000000000000000000000000 BauMaterial:earned and 300 Dreck
		

*UgbBDreckF1
		name:Braunfarbiger Dreck
		desc:<.> Erhöht die Produktion von Dreck um <b>75</b> %.
		icon:icons[5,5] icons[2,4] icons[3,0]
		cost:10 Dreck
		passive:multiply yield of Dreck by 1.75
		req:9230000 BauMaterial:earned and 9 Dreck

*UgbBDreckF2
		name:Graufarbiger Dreck
		desc:<.> Erhöht die Produktion von Dreck um <b>75</b> %.
		icon:icons[5,5] icons[2,4] icons[3,1]
		cost:50 Dreck
		passive:multiply yield of Dreck by 1.75
		req:923000000 BauMaterial:earned and 45 Dreck
		
*UgbBDreckF3
		name:Hellbraunfarbiger Dreck
		desc:<.> Erhöht die Produktion von Dreck um <b>75</b> %.
		icon:icons[5,5] icons[2,4] icons[3,2]
		cost:100 Dreck
		passive:multiply yield of Dreck by 1.75
		req:92300000000 BauMaterial:earned and 75 Dreck
		
*UgbBDreckF4
		name:Klumpen Dreck
		desc:<.> Erhöht die Produktion von Dreck um <b>75</b> %.
		icon:icons[5,5] icons[2,4] icons[3,3]
		cost:125 Dreck
		passive:multiply yield of Dreck by 1.75
		req:9230000000000 BauMaterial:earned and 100 Dreck
		
*UgbBDreckF5
		name:Ockerfarbiger Dreck
		desc:<.> Erhöht die Produktion von Dreck um <b>75</b> %.
		icon:icons[5,5] icons[2,4] icons[3,4]
		cost:150 Dreck
		passive:multiply yield of Dreck by 1.75
		req:923000000000000 BauMaterial:earned and 125 Dreck
		
*UgbBDreckF6
		name:Gelbfarbiger Dreck
		desc:<.> Erhöht die Produktion von Dreck um <b>75</b> %.
		icon:icons[5,5] icons[2,4] icons[3,5]
		cost:175 Dreck
		passive:multiply yield of Dreck by 1.75
		req:92300000000000000 BauMaterial:earned and 150 Dreck
		
*UgbBDreckF7
		name:Orangefarbiger Dreck
		desc:<.> Erhöht die Produktion von Dreck um <b>75</b> %.
		icon:icons[5,5] icons[2,4] icons[3,6]
		cost:200 Dreck
		passive:multiply yield of Dreck by 1.75
		req:9230000000000000000 BauMaterial:earned and 175 Dreck
			
*UgbBDreckF8
		name:Beigefarbiger Dreck
		desc:<.> Erhöht die Produktion von Dreck um <b>75</b> %.
		icon:icons[5,5] icons[2,4] icons[3,7]
		cost:225 Dreck
		passive:multiply yield of Dreck by 1.75
		req:923000000000000000000 BauMaterial:earned and 200 Dreck
			
*UgbBDreckF9
		name:Camelfarbiger Dreck
		desc:<.> Erhöht die Produktion von Dreck um <b>75</b> %.
		icon:icons[5,5] icons[2,4] icons[3,8]
		cost:250 Dreck
		passive:multiply yield of Dreck by 1.75
		req:92300000000000000000000 BauMaterial:earned and 225 Dreck
			
*UgbBDreckF10
		name:Nougatfarbiger Dreck
		desc:<.> Erhöht die Produktion von Dreck um <b>75</b> %.
		icon:icons[5,5] icons[2,4] icons[3,9]
		cost:275 Dreck
		passive:multiply yield of Dreck by 1.75
		req:9230000000000000000000000 BauMaterial:earned and 250 Dreck
			
*UgbBDreckF11
		name:Mahagonifarbiger Dreck
		desc:<.> Erhöht die Produktion von Dreck um <b>75</b> %.
		icon:icons[5,5] icons[2,4] icons[3,10]
		cost:300 Dreck
		passive:multiply yield of Dreck by 1.75
		req:923000000000000000000000000 BauMaterial:earned and 275 Dreck
			
*UgbBDreckF12
		name:Kupferbraunfarbiger Dreck
		desc:<.> Erhöht die Produktion von Dreck um <b>75</b> %.
		icon:icons[5,5] icons[2,4] icons[3,11]
		cost:325 Dreck
		passive:multiply yield of Dreck by 1.75
		req:92300000000000000000000000000 BauMaterial:earned and 300 Dreck
		
			
					
	




*TEMPLATE
no buy
tag:owned
class:noBackground



// Larven Multi mit Erfahrung a

*UgRLErfahrung1a
		name:Brüter
		desc:<.> Erhöht die Produktion von Larven um <b>3</b> %.
		icon:icons[6,4]
		req:UgRLErfahrung1
*UgRLErfahrung2a
		name:Schlüpfer
		desc:<.> Erhöht die Produktion von Larven um <b>3</b> %.
		icon:icons[6,4]
		req:40000 Erfahrung and UgRLErfahrung2
*UgRLErfahrung3a
		name:Wachser
		desc:<.> Erhöht die Produktion von Larven um <b>3</b> %.
		icon:icons[6,4]
		req:120000 Erfahrung and UgRLErfahrung3
*UgRLErfahrung4a
		name:Säher
		desc:<.> Erhöht die Produktion von Larven um <b>3</b> %.
		icon:icons[6,4]
		req:200000 Erfahrung and UgRLErfahrung4
*UgRLErfahrung5a
		name:Pfleger
		desc:<.> Erhöht die Produktion von Larven um <b>3</b> %.
		icon:icons[6,4]
		req:320000 Erfahrung and UgRLErfahrung5
*UgRLErfahrung6a
		name:Amme
		desc:<.> Erhöht die Produktion von Larven um <b>3</b> %.
		icon:icons[6,4]
		req:480000 Erfahrung and UgRLErfahrung6
*UgRLErfahrung7a
		name:Hebamme
		desc:<.> Erhöht die Produktion von Larven um <b>3</b> %.
		icon:icons[6,4]
		req:640000 Erfahrung and UgRLErfahrung7
*UgRLErfahrung8a
		name:Geburtshelfer
		desc:<.> Erhöht die Produktion von Larven um <b>3</b> %.
		icon:icons[6,4]
		req:840000 Erfahrung and UgRLErfahrung8
*UgRLErfahrung9a
		name:Entbindungshelfer
		desc:<.> Erhöht die Produktion von Larven um <b>3</b> %.
		icon:icons[6,4]
		req:1000000 Erfahrung and UgRLErfahrung9
*UgRLErfahrung10a
		name:Schlüpfstation
		desc:<.> Erhöht die Produktion von Larven um <b>3</b> %.
		icon:icons[6,4]
		req:1110000 Erfahrung and UgRLErfahrung10
		


// Insekten Multi mit Erfahrung a

*UgRIErfahrung1a
		name:Insektenzüchter
		desc:<.> Erhöht die Produktion von Insekten um <b>3</b> %.
		icon:icons[6,5]
		req:UgRIErfahrung1
*UgRIErfahrung2a
		name:Insektenpfleger
		desc:<.> Erhöht die Produktion von Insekten um <b>3</b> %.
		icon:icons[6,5]
		req:40000 Erfahrung and UgRIErfahrung2
*UgRIErfahrung3a
		name:Insektenforscher
		desc:<.> Erhöht die Produktion von Insekten um <b>3</b> %.
		icon:icons[6,5]
		req:120000 Erfahrung and UgRIErfahrung3
*UgRIErfahrung4a
		name:Insektenfinder
		desc:<.> Erhöht die Produktion von Insekten um <b>3</b> %.
		icon:icons[6,5]
		req:200000 Erfahrung and UgRIErfahrung4
*UgRIErfahrung5a
		name:Insektenberater
		desc:<.> Erhöht die Produktion von Insekten um <b>3</b> %.
		icon:icons[6,5]
		req:320000 Erfahrung and UgRIErfahrung5
*UgRIErfahrung6a
		name:Insektenentomologe
		desc:<.> Erhöht die Produktion von Insekten um <b>3</b> %.
		icon:icons[6,5]
		req:480000 Erfahrung and UgRIErfahrung6
*UgRIErfahrung7a
		name:Insektenprofessor
		desc:<.> Erhöht die Produktion von Insekten um <b>3</b> %.
		icon:icons[6,5]
		req:640000 Erfahrung and UgRIErfahrung7
*UgRIErfahrung8a
		name:Insektenlehrer
		desc:<.> Erhöht die Produktion von Insekten um <b>3</b> %.
		icon:icons[6,5]
		req:840000 Erfahrung and UgRIErfahrung8
*UgRIErfahrung9a
		name:Insektengelehrter
		desc:<.> Erhöht die Produktion von Insekten um <b>3</b> %.
		icon:icons[6,5]
		req:1000000 Erfahrung and UgRIErfahrung9
*UgRIErfahrung10a
		name:Insektenwissenschaftler
		desc:<.> Erhöht die Produktion von Insekten um <b>3</b> %.
		icon:icons[6,5]
		req:1110000 Erfahrung and UgRIErfahrung10
		
		

// BauMaterial Multi mit Erfahrung

*UgRBErfahrung1a
		name:Straßenbauer
		desc:<.> Erhöht die Produktion von BauMaterial um <b>3</b> %.
		icon:icons[6,6]
		req:UgRBErfahrung1
*UgRBErfahrung2a
		name:Baustoffprüfer
		desc:<.> Erhöht die Produktion von BauMaterial um <b>3</b> %.
		icon:icons[6,6]
		req:40000 Erfahrung and UgRBErfahrung2
*UgRBErfahrung3a
		name:Bauzeichner
		desc:<.> Erhöht die Produktion von BauMaterial um <b>3</b> %.
		icon:icons[6,6]
		req:120000 Erfahrung and UgRBErfahrung3
*UgRBErfahrung4a
		name:Kanalbauer
		desc:<.> Erhöht die Produktion von BauMaterial um <b>3</b> %.
		icon:icons[6,6]
		req:200000 Erfahrung and UgRBErfahrung4
*UgRBErfahrung5a
		name:Maurer
		desc:<.> Erhöht die Produktion von BauMaterial um <b>3</b> %.
		icon:icons[6,6]
		req:320000 Erfahrung and UgRBErfahrung5
*UgRBErfahrung6a
		name:Drechsler
		desc:<.> Erhöht die Produktion von BauMaterial um <b>3</b> %.
		icon:icons[6,6]
		req:480000 Erfahrung and UgRBErfahrung6
*UgRBErfahrung7a
		name:Flechtwerkgestalter
		desc:<.> Erhöht die Produktion von BauMaterial um <b>3</b> %.
		icon:icons[6,6]
		req:640000 Erfahrung and UgRBErfahrung7
*UgRBErfahrung8a
		name:Tischler
		desc:<.> Erhöht die Produktion von BauMaterial um <b>3</b> %.
		icon:icons[6,6]
		req:840000 Erfahrung and UgRBErfahrung8
*UgRBErfahrung9a
		name:Zimmerer
		desc:<.> Erhöht die Produktion von BauMaterial um <b>3</b> %.
		icon:icons[6,6]
		req:1000000 Erfahrung and UgRBErfahrung9
*UgRBErfahrung10a
		name:Steinmetz
		desc:<.> Erhöht die Produktion von BauMaterial um <b>3</b> %.
		icon:icons[6,6]
		req:1110000 Erfahrung and UgRBErfahrung10
		
		
		
		
		
	
		






//Sammler Upgrades a----------------------------------------------------



	
//1a 	
	
*UgBIPSammlerA1a
		name:SammlerAmeisenPanzer I
		desc:<.> Erhöht die Produktion der SammlerAmeisen um <b>75</b> %.
		icon:icons[4,3] icons[4,1]
		req:UgBIPSammlerA1
		class:noBackground
*UgBIPSammlerA2a
		name:SammlerAmeisenPanzer II
		desc:<.> Erhöht die Produktion der SammlerAmeisen um <b>75</b> %.
		icon:icons[4,3] icons[4,1]
		req:UgBIPSammlerA2
		class:noBackground
*UgBIPSammlerA3a
		name:SammlerAmeisenPanzer III
		desc:<.> Erhöht die Produktion der SammlerAmeisen um <b>75</b> %.
		icon:icons[4,3] icons[4,1]
		req:UgBIPSammlerA3
		class:noBackground
*UgBIPSammlerA4a
		name:SammlerAmeisenPanzer IV
		desc:<.> Erhöht die Produktion der SammlerAmeisen um <b>75</b> %.
		icon:icons[4,3] icons[4,1]
		req:UgBIPSammlerA4
		class:noBackground
*UgBIPSammlerA5a
		name:SammlerAmeisenPanzer V
		desc:<.> Erhöht die Produktion der SammlerAmeisen um <b>75</b> %.
		icon:icons[4,3] icons[4,1]
		req:UgBIPSammlerA5
		class:noBackground
*UgBIPSammlerA6a
		name:SammlerAmeisenPanzer VI
		desc:<.> Erhöht die Produktion der SammlerAmeisen um <b>75</b> %.
		icon:icons[4,3] icons[4,1]
		req:UgBIPSammlerA6
		class:noBackground
*UgBIPSammlerA7a
		name:SammlerAmeisenPanzer VII
		desc:<.> Erhöht die Produktion der SammlerAmeisen um <b>75</b> %.
		icon:icons[4,3] icons[4,1]
		req:UgBIPSammlerA7
		class:noBackground
*UgBIPSammlerA8a
		name:SammlerAmeisenPanzer VIII
		desc:<.> Erhöht die Produktion der SammlerAmeisen um <b>75</b> %.
		icon:icons[4,3] icons[4,1]
		req:UgBIPSammlerA8
		class:noBackground
*UgBIPSammlerA9a
		name:SammlerAmeisenPanzer IX
		desc:<.> Erhöht die Produktion der SammlerAmeisen um <b>75</b> %.
		icon:icons[4,3] icons[4,1]
		req:UgBIPSammlerA9
		class:noBackground
*UgBIPSammlerA10a
		name:SammlerAmeisenPanzer X
		desc:<.> Erhöht die Produktion der SammlerAmeisen um <b>75</b> %.
		icon:icons[4,3] icons[4,1]
		req:UgBIPSammlerA10
		class:noBackground
*UgBIPSammlerA11a
		name:SammlerAmeisenPanzer XI
		desc:<.> Erhöht die Produktion der SammlerAmeisen um <b>75</b> %.
		icon:icons[4,3] icons[4,1]
		req:UgBIPSammlerA11
		class:noBackground
*UgBIPSammlerA12a
		name:SammlerAmeisenPanzer XII
		desc:<.> Erhöht die Produktion der SammlerAmeisen um <b>75</b> %.
		icon:icons[4,3] icons[4,1]
		req:UgBIPSammlerA12
		class:noBackground
*UgBIPSammlerA13a
		name:SammlerAmeisenPanzer XIII
		desc:<.> Erhöht die Produktion der SammlerAmeisen um <b>75</b> %.
		icon:icons[4,3] icons[4,1]
		req:UgBIPSammlerA13
		class:noBackground
*UgBIPSammlerA14a
		name:SammlerAmeisenPanzer XIV
		desc:<.> Erhöht die Produktion der SammlerAmeisen um <b>75</b> %.
		icon:icons[4,3] icons[4,1]
		req:UgBIPSammlerA14
		class:noBackground
*UgBIPSammlerA15a
		name:SammlerAmeisenPanzer XV
		desc:<.> Erhöht die Produktion der SammlerAmeisen um <b>75</b> %.
		icon:icons[4,3] icons[4,1]
		req:UgBIPSammlerA15
		class:noBackground		







//Larven Upgrades a ----------------------------






		
		
		

*UgRLMandala1a
		name:Ein buntes Mandala
		desc:<.>Etwas Kunst belebt die Larven Produktion! <//><.> Erhöht die Produktion von Larven um <b>1</b> %.
		icon:iconsa[8,0]
		req:UgRLMandala1
*UgRLMandala2a
		name:Schwarzes Mandala
		desc:<.> Erhöht die Produktion von Larven um <b>1</b> %.
		icon:iconsa[8,1]
		req:250000 Larven:earned and UgRLMandala2
*UgRLMandala3a
		name:Türkises Mandala
		desc:<.> Erhöht die Produktion von Larven um <b>1</b> %.
		icon:iconsa[8,2]
		req:500000 Larven:earned and UgRLMandala3
*UgRLMandala4a
		name:Hellblaues Mandala
		desc:<.> Erhöht die Produktion von Larven um <b>1</b> %.
		icon:iconsa[8,3]
		req:2500000 Larven:earned and UgRLMandala4
*UgRLMandala5a
		name:Buntes Mandala
		desc:<.> Erhöht die Produktion von Larven um <b>1</b> %.
		icon:iconsa[8,4]
		req:5000000 Larven:earned and UgRLMandala5
*UgRLMandala6a
		name:Feines Mandala
		desc:<.> Erhöht die Produktion von Larven um <b>1</b> %.
		icon:iconsa[8,5]
		req:25000000 Larven:earned and UgRLMandala6
*UgRLMandala7a
		name:Rundes Mandala
		desc:<.> Erhöht die Produktion von Larven um <b>1</b> %.
		icon:iconsa[8,6]
		req:50000000 Larven:earned and UgRLMandala7
*UgRLMandala8a
		name:Braunes Mandala
		desc:<.> Erhöht die Produktion von Larven um <b>1</b> %.
		icon:iconsa[8,7]
		req:250000000 Larven:earned and UgRLMandala8
*UgRLMandala9a
		name:Plattes Mandala
		desc:<.> Erhöht die Produktion von Larven um <b>1</b> %.
		icon:iconsa[8,8]
		req:500000000 Larven:earned and UgRLMandala9
*UgRLMandala10a
		name:Rahmen Mandala
		desc:<.> Erhöht die Produktion von Larven um <b>1</b> %.
		icon:iconsa[8,9]
		req:2500000000 Larven:earned and UgRLMandala10
*UgRLMandala11a
		name:Schönes Mandala
		desc:<.> Erhöht die Produktion von Larven um <b>1</b> %.
		icon:iconsa[8,10]
		req:5000000000 Larven:earned and UgRLMandala11
*UgRLMandala12a
		name:Dunkles Mandala
		desc:<.> Erhöht die Produktion von Larven um <b>1</b> %.
		icon:iconsa[8,11]
		req:25000000000 Larven:earned and UgRLMandala12
*UgRLMandala13a
		name:Rotes Mandala
		desc:<.> Erhöht die Produktion von Larven um <b>1</b> %.
		icon:iconsa[8,12]
		req:50000000000 Larven:earned and UgRLMandala13
*UgRLMandala14a
		name:Einfarbiges Mandala
		desc:<.> Erhöht die Produktion von Larven um <b>1</b> %.
		icon:iconsa[8,13]
		req:250000000000 Larven:earned and UgRLMandala14
*UgRLMandala15a
		name:Regenbogen Mandala
		desc:<.> Erhöht die Produktion von Larven um <b>1</b> %.
		icon:iconsa[8,14]
		req:500000000000 Larven:earned and UgRLMandala15
*UgRLMandala16a
		name:Abstraktes Mandala
		desc:<.> Erhöht die Produktion von Larven um <b>1</b> %.
		icon:iconsa[8,15]
		req:5000000000000 Larven:earned and UgRLMandala16
*UgRLMandala17a
		name:Originelles Mandala
		desc:<.> Erhöht die Produktion von Larven um <b>1</b> %.
		icon:iconsa[8,16]
		req:25000000000000 Larven:earned and UgRLMandala17
*UgRLMandala18a
		name:Altmodisches Mandala
		desc:<.> Erhöht die Produktion von Larven um <b>1</b> %.
		icon:iconsa[8,17]
		req:50000000000000 Larven:earned and UgRLMandala18
*UgRLMandala19a
		name:Modernes Mandala
		desc:<.> Erhöht die Produktion von Larven um <b>1</b> %.
		icon:iconsa[8,18]
		req:250000000000000 Larven:earned and UgRLMandala19
*UgRLMandala20a
		name:Gelbes Mandala
		desc:<.> Erhöht die Produktion von Larven um <b>1</b> %.
		icon:iconsa[8,19]
		req:500000000000000 Larven:earned and UgRLMandala20
*UgRLMandala21a
		name:Großes Mandala
		desc:<.> Erhöht die Produktion von Larven um <b>1</b> %.
		icon:iconsa[8,20]
		req:2500000000000000 Larven:earned and UgRLMandala21
					

		
		

*UgRLNudelK1a
		name:Bandnudel
        desc:<.> Beim Klicken der Larve bekommst du <b>2</b> mal so viel!
		icon:iconsa[9,0]
		req:UgRLNudelK1
*UgRLNudelK2a
		name:Davette
        desc:<.> Beim Klicken der Larve bekommst du <b>3</b> mal so viel!
		icon:iconsa[9,1]
		req:250000 Larve:earned and UgRLNudelK2
*UgRLNudelK3a
		name:Bucatini
        desc:<.> Beim Klicken der Larve bekommst du <b>3</b> mal so viel!
		icon:iconsa[9,2]
		req:500000 Larve:earned and UgRLNudelK3
*UgRLNudelK4a
		name:Cannelloni
        desc:<.> Beim Klicken der Larve bekommst du <b>3</b> mal so viel!
		icon:iconsa[9,3]
		req:2500000 Larve:earned and UgRLNudelK4
*UgRLNudelK5a
		name:Ditalini
		desc:<.> Beim Klicken der Larve bekommst du <b>3</b> mal so viel!
		icon:iconsa[9,4]
		req:5000000 Larve:earned and UgRLNudelK5
*UgRLNudelK6a
		name:Farfalle
		desc:<.> Beim Klicken der Larve bekommst du <b>3</b> mal so viel!
		icon:iconsa[9,5]
		req:25000000 Larve:earned and UgRLNudelK6
*UgRLNudelK7a
		name:Fettuccine
		desc:<.> Beim Klicken der Larve bekommst du <b>3</b> mal so viel!
		icon:iconsa[9,6]
		req:50000000 Larve:earned and UgRLNudelK7
*UgRLNudelK8a
		name:Gnocchi
		desc:<.> Beim Klicken der Larve bekommst du <b>3</b> mal so viel!
		icon:iconsa[9,7]
		req:250000000 Larve:earned and UgRLNudelK8
*UgRLNudelK9a
		name:Linguine
		desc:<.> Beim Klicken der Larve bekommst du <b>3</b> mal so viel!
		icon:iconsa[9,8]
		req:500000000 Larve:earned and UgRLNudelK9
*UgRLNudelK10a
		name:Lumaconi
		desc:<.> Beim Klicken der Larve bekommst du <b>3</b> mal so viel!
		icon:iconsa[9,9]
		req:2500000000 Larve:earned and UgRLNudelK10
*UgRLNudelK11a
		name:Makkaroni
		desc:<.> Beim Klicken der Larve bekommst du <b>3</b> mal so viel!
		icon:iconsa[9,10]
		req:5000000000 Larve:earned and UgRLNudelK11
*UgRLNudelK12a
		name:Orecchiette
		desc:<.> Beim Klicken der Larve bekommst du <b>3</b> mal so viel!
		icon:iconsa[9,11]
		req:25000000000 Larve:earned and UgRLNudelK12
*UgRLNudelK13a
		name:Pappardelle
		desc:<.> Beim Klicken der Larve bekommst du <b>3</b> mal so viel!
		icon:iconsa[9,12]
		req:50000000000 Larve:earned and UgRLNudelK13
*UgRLNudelK14a
		name:Penne lisce
		desc:<.> Beim Klicken der Larve bekommst du <b>3</b> mal so viel!
		icon:iconsa[9,13]
		req:250000000000 Larve:earned and UgRLNudelK14
*UgRLNudelK15a
		name:Penne Rigate
		desc:<.> Beim Klicken der Larve bekommst du <b>3</b> mal so viel!
		passive:multiply yield of LarveButton by 3
		req:250000000000 Larve:earned and UgRLNudelK15
*UgRLNudelK16a
		name:Ravioli
		desc:<.> Beim Klicken der Larve bekommst du <b>3</b> mal so viel!
		icon:iconsa[9,15]
		req:5000000000000 Larve:earned and UgRLNudelK16
*UgRLNudelK17a
		name:Rigatoni
		desc:<.> Beim Klicken der Larve bekommst du <b>3</b> mal so viel!
		icon:iconsa[9,16]
		req:25000000000000 Larve:earned and UgRLNudelK17
*UgRLNudelK18a
		name:Spaghetti
		desc:<.> Beim Klicken der Larve bekommst du <b>3</b> mal so viel!
		icon:iconsa[9,17]
		req:50000000000000 Larve:earned and UgRLNudelK18
*UgRLNudelK19a
		name:Tagliatelle
		desc:<.> Beim Klicken der Larve bekommst du <b>3</b> mal so viel!
		icon:iconsa[9,18]
		req:250000000000000 Larve:earned and UgRLNudelK19
*UgRLNudelK20a
		name:Tortellini
		desc:<.> Beim Klicken der Larve bekommst du <b>3</b> mal so viel!
		icon:iconsa[9,19]
		req:500000000000000 Larve:earned and UgRLNudelK20
*UgRLNudelK21a
		name:Trenette
		desc:<.> Beim Klicken der Larve bekommst du <b>3</b> mal so viel!
		icon:iconsa[9,20]
		req:2500000000000000 Larve:earned and UgRLNudelK21
		


*UgRLMinecraftk1a
        name:Schleimball
        desc:<.> Beim Klicken der Larve bekommst du <b>1</b> Larve mehr!
        icon:iconsa[10,0]
        req:UgRLMinecraftk1
*UgRLMinecraftk2a
        name:Redstone
        desc:<.> Beim Klicken der Larve bekommst du <b>1</b> Larve mehr!
        icon:iconsa[10,1]
        req:100 Larve:earned and UgRLMinecraftk2
*UgRLMinecraftk3a
        name:Smaragd
        desc:<.> Beim Klicken der Larve bekommst du <b>1</b> Larve mehr!
        icon:iconsa[10,2]
        req:1000 Larve:earned and UgRLMinecraftk3
*UgRLMinecraftk4a
        name:Leder
        desc:<.> Beim Klicken der Larve bekommst du <b>1</b> Larve mehr!
        icon:iconsa[10,3]
        req:10000 Larve:earned and UgRLMinecraftk4
*UgRLMinecraftk5a
        name:Goldbarren
        desc:<.> Beim Klicken der Larve bekommst du <b>1</b> Larve mehr!
        icon:iconsa[10,4]
        req:100000 Larve:earned and UgRLMinecraftk5
*UgRLMinecraftk6a
        name:Diamant
        desc:<.> Beim Klicken der Larve bekommst du <b>1</b> Larve mehr!
        icon:iconsa[10,5]
        req:1000000 Larve:earned and UgRLMinecraftk6

				
		
		
					
			

		
*UgBLRaupe1a
		name:Raupen Tango
		desc:<.> Erhöht die Produktion der Raupen um <b>10</b> %.
		icon:icons[1,0] icons[3,0]
		req:UgBLRaupe1

*UgBLRaupe2a
		name:Raupenmarsch
		desc:<.> Erhöht die Produktion der Raupen um <b>10</b> %.
		icon:icons[1,0] icons[3,1]
		req:10000 Larven:earned and UgBLRaupe2
				
*UgBLRaupe3a
		name:Raupenparty
		desc:<.> Erhöht die Produktion der Raupen um <b>10</b> %.
		icon:icons[1,0] icons[3,2]
		req:1000000 Larven:earned and UgBLRaupe3

*UgBLRaupe4a
		name:Raupenmusik
		desc:<.> Erhöht die Produktion der Raupen um <b>10</b> %.
		icon:icons[1,0] icons[3,3]
		req:100000000 Larven:earned and UgBLRaupe4
		
*UgBLRaupe5a
		name:Raupastik
		desc:<.> Erhöht die Produktion der Raupen um <b>10</b> %.
		icon:icons[1,0] icons[3,4]
		req:10000000000 Larven:earned and UgBLRaupe5
		
*UgBLRaupe6a
		name:Raupenpuppe
		desc:<.> Erhöht die Produktion der Raupen um <b>10</b> %.
		icon:icons[1,0] icons[3,5]
		req:1000000000000 Larven:earned and UgBLRaupe6
		
*UgBLRaupe7a
		name:Raupenmania
		desc:<.> Erhöht die Produktion der Raupen um <b>10</b> %.
		icon:icons[1,0] icons[3,6]
		req:100000000000000 Larven:earned and UgBLRaupe7
		
*UgBLRaupe8a
		name:Raupengesang
		desc:<.> Erhöht die Produktion der Raupen um <b>10</b> %.
		icon:icons[1,0] icons[3,7]
		req:10000000000000000 Larven:earned and UgBLRaupe8
		
*UgBLRaupe9a
		name:Raupenlolli
		desc:<.> Erhöht die Produktion der Raupen um <b>10</b> %.
		icon:icons[1,0] icons[3,8]
		req:1000000000000000000 Larven:earned and UgBLRaupe9
		
*UgBLRaupe10a
		name:Raupensymphonie
		desc:<.> Erhöht die Produktion der Raupen um <b>10</b> %.
		icon:icons[1,0] icons[3,9]
		req:100000000000000000000 Larven:earned and UgBLRaupe10
		
*UgBLRaupe11a
		name:Raupenklatschen
		desc:<.> Erhöht die Produktion der Raupen um <b>10</b> %.
		icon:icons[1,0] icons[3,10]
		req:10000000000000000000000 Larven:earned and UgBLRaupe11
		
*UgBLRaupe12a
		name:Raupenwetter
		desc:<.> Erhöht die Produktion der Raupen um <b>10</b> %.
		icon:icons[1,0] icons[3,11]
		req:1000000000000000000000000 Larven:earned and UgBLRaupe12
		
				
	
*UgBLRaupeF1a
		name:Raupenpanzer
		desc:<.> Erhöht die Produktion der Raupen um <b>75</b> %.
		icon:icons[5,5] icons[1,0] icons[8,0]
		req:10 Raupen and UgBLRaupeF1
*UgBLRaupeF2a
		name:HolzRaupe
		desc:<.> Erhöht die Produktion der Raupen um <b>75</b> %.
		icon:icons[5,5] icons[1,0] icons[8,1]
		req:25 Raupen and UgBLRaupeF2
*UgBLRaupeF3a
		name:SteinRaupe
		desc:<.> Erhöht die Produktion der Raupen um <b>75</b> %.
		icon:icons[5,5] icons[1,0] icons[8,2]
		req:50 Raupen and UgBLRaupeF3
*UgBLRaupeF4a
		name:EisenRaupe
		desc:<.> Erhöht die Produktion der Raupen um <b>75</b> %.
		icon:icons[5,5] icons[1,0] icons[8,3]
		req:75 Raupen and UgBLRaupeF4
*UgBLRaupeF5a
		name:StahlRaupe
		desc:<.> Erhöht die Produktion der Raupen um <b>75</b> %.
		icon:icons[5,5] icons[1,0] icons[8,4]
		req:100 Raupen and UgBLRaupeF5
*UgBLRaupeF6a
		name:KadmiumRaupe
		desc:<.> Erhöht die Produktion der Raupen um <b>75</b> %.
		icon:icons[5,5] icons[1,0] icons[8,5]
		req:125 Raupen and UgBLRaupeF6
*UgBLRaupeF7a
		name:KobaltRaupe
		desc:<.> Erhöht die Produktion der Raupen um <b>75</b> %.
		icon:icons[5,5] icons[1,0] icons[8,6]
		req:150 Raupen and UgBLRaupeF7
*UgBLRaupeF8a
		name:LithiumRaupe
		desc:<.> Erhöht die Produktion der Raupen um <b>75</b> %.
		icon:icons[5,5] icons[1,0] icons[8,7]
		req:175 Raupen and UgBLRaupeF8
*UgBLRaupeF9a
		name:BleiRaupe
		desc:<.> Erhöht die Produktion der Raupen um <b>75</b> %.
		icon:icons[5,5] icons[1,0] icons[8,8]
		req:200 Raupen and UgBLRaupeF9
*UgBLRaupeF10a
		name:BronzeRaupe
		desc:<.> Erhöht die Produktion der Raupen um <b>75</b> %.
		icon:icons[5,5] icons[1,0] icons[8,9]
		req:225 Raupen and UgBLRaupeF10
*UgBLRaupeF11a
		name:AluminiumRaupe
		desc:<.> Erhöht die Produktion der Raupen um <b>75</b> %.
		icon:icons[5,5] icons[1,0] icons[8,10]
		req:250 Raupen and UgBLRaupeF11
*UgBLRaupeF12a
		name:ChromRaupe
		desc:<.> Erhöht die Produktion der Raupen um <b>75</b> %.
		icon:icons[5,5] icons[1,0] icons[8,11]
		req:275 Raupen and UgBLRaupeF12
*UgBLRaupeF13a
		name:NickelRaupe
		desc:<.> Erhöht die Produktion der Raupen um <b>75</b> %.
		icon:icons[5,5] icons[1,0] icons[8,12]
		req:300 Raupen and UgBLRaupeF13
*UgBLRaupeF14a
		name:WolframRaupe
		desc:<.> Erhöht die Produktion der Raupen um <b>75</b> %.
		icon:icons[5,5] icons[1,0] icons[8,12]
		req:325 Raupen and UgBLRaupeF14
*UgBLRaupeF15a
		name:ZinnRaupe
		desc:<.> Erhöht die Produktion der Raupen um <b>75</b> %.
		icon:icons[5,5] icons[1,0] icons[8,12]
		req:350 Raupen and UgBLRaupeF15	
						

		
*UgBLBienenstock1a
		name:Bienenwabe
		desc:<.> Erhöht die Produktion der Bienenstöcke um <b>10</b> %.
		icon:icons[1,1] icons[3,0]
		req:UgBLBienenstock1
*UgBLBienenstock2a
		name:Bienenkönigin
		desc:<.> Erhöht die Produktion der Bienenstöcke um <b>10</b> %.
		icon:icons[1,1] icons[3,1]
		req:90000 Larven:earned and UgBLBienenstock2
*UgBLBienenstock3a
		name:Binentango
		desc:<.> Erhöht die Produktion der Bienenstöcke um <b>10</b> %.
		icon:icons[1,1] icons[3,2]
		req:9000000 Larven:earned and UgBLBienenstock3
*UgBLBienenstock4a
		name:Bienenfieber
		desc:<.> Erhöht die Produktion der Bienenstöcke um <b>10</b> %.
		icon:icons[1,1] icons[3,3]
		req:900000000 Larven:earned and UgBLBienenstock4
*UgBLBienenstock5a
		name:Bienensummen
		desc:<.> Erhöht die Produktion der Bienenstöcke um <b>10</b> %.
		icon:icons[1,1] icons[3,4]
		req:90000000000 Larven:earned and UgBLBienenstock5
*UgBLBienenstock6a
		name:Bienenparty
		desc:<.> Erhöht die Produktion der Bienenstöcke um <b>10</b> %.
		icon:icons[1,1] icons[3,5]
		req:9000000000000 Larven:earned and UgBLBienenstock6
*UgBLBienenstock7a
		name:Bienenflügel
		desc:<.> Erhöht die Produktion der Bienenstöcke um <b>10</b> %.
		icon:icons[1,1] icons[3,6]
		req:900000000000000 Larven:earned and UgBLBienenstock7
*UgBLBienenstock8a
		name:Bienentorte
		desc:<.> Erhöht die Produktion der Bienenstöcke um <b>10</b> %.
		icon:icons[1,1] icons[3,7]
		req:90000000000000000 Larven:earned and UgBLBienenstock8
*UgBLBienenstock9a
		name:Bienenkuchen
		desc:<.> Erhöht die Produktion der Bienenstöcke um <b>10</b> %.
		icon:icons[1,1] icons[3,8]
		req:9000000000000000000 Larven:earned and UgBLBienenstock9
*UgBLBienenstock10a
		name:Bienensafari
		desc:<.> Erhöht die Produktion der Bienenstöcke um <b>10</b> %.
		icon:icons[1,1] icons[3,9]
		req:900000000000000000000 Larven:earned and UgBLBienenstock10
*UgBLBienenstock11a
		name:Bienenpolka
		desc:<.> Erhöht die Produktion der Bienenstöcke um <b>10</b> %.
		icon:icons[1,1] icons[3,10]
		req:90000000000000000000000 Larven:earned and UgBLBienenstock11
*UgBLBienenstock12a
		name:Bientasium
		desc:<.> Erhöht die Produktion der Bienenstöcke um <b>10</b> %.
		icon:icons[1,1] icons[3,11]
		req:9000000000000000000000000 Larven:earned and UgBLBienenstock12

//2a
	
*UgBLBienenstF1a
		name:Stroh Verkleidung
		desc:<.> Erhöht die Produktion der Bienenstöcke um <b>75</b> %.
		icon:icons[5,5] icons[1,1] icons[8,0]
		req:UgBLBienenstF1
*UgBLBienenstF2a
		name:Holz Verkleidung
		desc:<.> Erhöht die Produktion der Bienenstöcke um <b>75</b> %.
		icon:icons[5,5] icons[1,1] icons[8,1]
		req:25 Bienenstock and UgBLBienenstF2
*UgBLBienenstF3a
		name:Stein Verkleidung
		desc:<.> Erhöht die Produktion der Bienenstöcke um <b>75</b> %.
		icon:icons[5,5] icons[1,1] icons[8,2]
		req:50 Bienenstock and UgBLBienenstF3
*UgBLBienenstF4a
		name:Eisen Verkleidung
		desc:<.> Erhöht die Produktion der Bienenstöcke um <b>75</b> %.
		icon:icons[5,5] icons[1,1] icons[8,3]
		req:75 Bienenstock and UgBLBienenstF4
*UgBLBienenstF5a
		name:Stahl Verkleidung
		desc:<.> Erhöht die Produktion der Bienenstöcke um <b>75</b> %.
		icon:icons[5,5] icons[1,1] icons[8,4]
		req:100 Bienenstock and UgBLBienenstF5
*UgBLBienenstF6a
		name:Kadmium Verkleidung
		desc:<.> Erhöht die Produktion der Bienenstöcke um <b>75</b> %.
		icon:icons[5,5] icons[1,1] icons[8,5]
		req:125 Bienenstock and UgBLBienenstF6
*UgBLBienenstF7a
		name:Kobalt Verkleidung
		desc:<.> Erhöht die Produktion der Bienenstöcke um <b>75</b> %.
		icon:icons[5,5] icons[1,1] icons[8,6]
		req:150 Bienenstock and UgBLBienenstF7
*UgBLBienenstF8a
		name:Lithium Verkleidung
		desc:<.> Erhöht die Produktion der Bienenstöcke um <b>75</b> %.
		icon:icons[5,5] icons[1,1] icons[8,7]
		req:175 Bienenstock and UgBLBienenstF8
*UgBLBienenstF9a
		name:Blei Verkleidung
		desc:<.> Erhöht die Produktion der Bienenstöcke um <b>75</b> %.
		icon:icons[5,5] icons[1,1] icons[8,8]
		req:200 Bienenstock and UgBLBienenstF9
*UgBLBienenstF10a
		name:Bronze Verkleidung
		desc:<.> Erhöht die Produktion der Bienenstöcke um <b>75</b> %.
		icon:icons[5,5] icons[1,1] icons[8,9]
		req:225 Bienenstock and UgBLBienenstF10
*UgBLBienenstF11a
		name:Aluminium Verkleidung
		desc:<.> Erhöht die Produktion der Bienenstöcke um <b>75</b> %.
		icon:icons[5,5] icons[1,1] icons[8,10]
		req:250 Bienenstock and UgBLBienenstF11
*UgBLBienenstF12a
		name:Chrom Verkleidung
		desc:<.> Erhöht die Produktion der Bienenstöcke um <b>75</b> %.
		icon:icons[5,5] icons[1,1] icons[8,11]
		req:275 Bienenstock and UgBLBienenstF12
*UgBLBienenstF13a
		name:Nickel Verkleidung
		desc:<.> Erhöht die Produktion der Bienenstöcke um <b>75</b> %.
		icon:icons[5,5] icons[1,1] icons[8,12]
		req:300 Bienenstock and UgBLBienenstF13
*UgBLBienenstF14a
		name:Wolfram Verkleidung
		desc:<.> Erhöht die Produktion der Bienenstöcke um <b>75</b> %.
		icon:icons[5,5] icons[1,1] icons[8,12]
		req:325 Bienenstock and UgBLBienenstF14
*UgBLBienenstF15a
		name:Zinn Verkleidung
		desc:<.> Erhöht die Produktion der Bienenstöcke um <b>75</b> %.
		icon:icons[5,5] icons[1,1] icons[8,12]
		req:350 Bienenstock and UgBLBienenstF15
		


*UgBLTermitenbau1a
		name:Termitenpolka
		desc:<.> Erhöht die Produktion der Termitenbauten um <b>10</b> %.
		icon:icons[1,1] icons[3,0]
		req:UgBLTermitenbau1
*UgBLTermitenbau2a
		name:Termitenmeister
		desc:<.> Erhöht die Produktion der Termitenbauten um <b>10</b> %.
		icon:icons[1,2] icons[3,1]
		req:81000000 Larven:earned and UgBLTermitenbau2
*UgBLTermitenbau3a
		name:Termitits
		desc:<.> Erhöht die Produktion der Termitenbauten um <b>10</b> %.
		icon:icons[1,2] icons[3,2]
		req:8100000000 Larven:earned and UgBLTermitenbau3
*UgBLTermitenbau4a
		name:Termitenermaster
		desc:<.> Erhöht die Produktion der Termitenbauten um <b>10</b> %.
		icon:icons[1,2] icons[3,3]
		req:810000000000 Larven:earned and UgBLTermitenbau4
*UgBLTermitenbau5a
		name:Termitenkaffee
		desc:<.> Erhöht die Produktion der Termitenbauten um <b>10</b> %.
		icon:icons[1,2] icons[3,4]
		req:81000000000000 Larven:earned and UgBLTermitenbau5
*UgBLTermitenbau6a
		name:Termitenmusik
		desc:<.> Erhöht die Produktion der Termitenbauten um <b>10</b> %.
		icon:icons[1,2] icons[3,5]
		req:8100000000000000 Larven:earned and UgBLTermitenbau6
*UgBLTermitenbau7a
		name:Termitenrising
		desc:<.> Erhöht die Produktion der Termitenbauten um <b>10</b> %.
		icon:icons[1,2] icons[3,6]
		req:810000000000000000 Larven:earned and UgBLTermitenbau7
*UgBLTermitenbau8a
		name:Termitenbonbon
		desc:<.> Erhöht die Produktion der Termitenbauten um <b>10</b> %.
		icon:icons[1,2] icons[3,7]
		req:81000000000000000000 Larven:earned and UgBLTermitenbau8
*UgBLTermitenbau9a
		name:Termitensamba
		desc:<.> Erhöht die Produktion der Termitenbauten um <b>10</b> %.
		icon:icons[1,2] icons[3,8]
		req:8100000000000000000000 Larven:earned and UgBLTermitenbau9
*UgBLTermitenbau10a
		name:Termitosis
		desc:<.> Erhöht die Produktion der Termitenbauten um <b>10</b> %.
		icon:icons[1,2] icons[3,9]
		req:810000000000000000000000 Larven:earned and UgBLTermitenbau10
*UgBLTermitenbau11a
		name:Termitenerhebung
		desc:<.> Erhöht die Produktion der Termitenbauten um <b>10</b> %.
		icon:icons[1,2] icons[3,10]
		req:81000000000000000000000000 Larven:earned and UgBLTermitenbau11
*UgBLTermitenbau12a
		name:Termitengesang
		desc:<.> Erhöht die Produktion der Termitenbauten um <b>10</b> %.
		icon:icons[1,2] icons[3,11]
		req:8100000000000000000000000000 Larven:earned and UgBLTermitenbau12

//3
	
*UgBLTermitenbF1a
		name:Stroh Verkleidung
		desc:<.> Erhöht die Produktion der Termitenbauten um <b>75</b> %.
		icon:icons[11,0]
		req:UgBLTermitenbF1
*UgBLTermitenbF2a
		name:Holz Verkleidung
		desc:<.> Erhöht die Produktion der Termitenbauten um <b>75</b> %.
		icon:icons[11,1] 
		req:25 Termitenbau and UgBLTermitenbF2
*UgBLTermitenbF3a
		name:Stein Verkleidung
		desc:<.> Erhöht die Produktion der Termitenbauten um <b>75</b> %.
		icon:icons[11,2]
		req:50 Termitenbau and UgBLTermitenbF3
*UgBLTermitenbF4a
		name:Eisen Verkleidung
		desc:<.> Erhöht die Produktion der Termitenbauten um <b>75</b> %.
		icon:icons[11,3]
		req:75 Termitenbau and UgBLTermitenbF4
*UgBLTermitenbF5a
		name:Stahl Verkleidung
		desc:<.> Erhöht die Produktion der Termitenbauten um <b>75</b> %.
		icon:icons[11,4]
		req:100 Termitenbau and UgBLTermitenbF5
*UgBLTermitenbF6a
		name:Kadmium Verkleidung
		desc:<.> Erhöht die Produktion der Termitenbauten um <b>75</b> %.
		icon:icons[11,5]
		req:125 Termitenbau and UgBLTermitenbF6
*UgBLTermitenbF7a
		name:Kobalt Verkleidung
		desc:<.> Erhöht die Produktion der Termitenbauten um <b>75</b> %.
		icon:icons[11,6]
		req:150 Termitenbau and UgBLTermitenbF7
*UgBLTermitenbF8a
		name:Lithium Verkleidung
		desc:<.> Erhöht die Produktion der Termitenbauten um <b>75</b> %.
		icon:icons[11,7]
		req:175 Termitenbau and UgBLTermitenbF8
*UgBLTermitenbF9a
		name:Blei Verkleidung
		desc:<.> Erhöht die Produktion der Termitenbauten um <b>75</b> %.
		icon:icons[11,8]
		req:200 Termitenbau and UgBLTermitenbF9
*UgBLTermitenbF10a
		name:Bronze Verkleidung
		desc:<.> Erhöht die Produktion der Termitenbauten um <b>75</b> %.
		icon:icons[11,9]
		req:225 Termitenbau and UgBLTermitenbF10
*UgBLTermitenbF11a
		name:Aluminium Verkleidung
		desc:<.> Erhöht die Produktion der Termitenbauten um <b>75</b> %.
		icon:icons[11,10]
		req:250 Termitenbau and UgBLTermitenbF11
*UgBLTermitenbF12a
		name:Chrom Verkleidung
		desc:<.> Erhöht die Produktion der Termitenbauten um <b>75</b> %.
		icon:icons[11,11]
		req:275 Termitenbau and UgBLTermitenbF12
*UgBLTermitenbF13a
		name:Nickel Verkleidung
		desc:<.> Erhöht die Produktion der Termitenbauten um <b>75</b> %.
		icon:icons[11,12]
		req:300 Termitenbau and UgBLTermitenbF13
*UgBLTermitenbF14a
		name:Wolfram Verkleidung
		desc:<.> Erhöht die Produktion der Termitenbauten um <b>75</b> %.
		icon:icons[11,13]
		req:325 Termitenbau and UgBLTermitenbF14
*UgBLTermitenbF15a
		name:Zinn Verkleidung
		desc:<.> Erhöht die Produktion der Termitenbauten um <b>75</b> %.
		icon:icons[11,14]
		req:350 Termitenbau and UgBLTermitenbF15
				

*UgBLBlatt1a
		name:Ahornblatt
		desc:<.> Erhöht die Produktion der Blätter um <b>10</b> %.
		icon:icons[1,3] icons[3,0]
		req:UgBLBlatt1
*UgBLBlatt2a
		name:Eichenblatt
		desc:<.> Erhöht die Produktion der Blätter um <b>10</b> %.
		icon:icons[1,3] icons[3,1]
		req:26000000 Larven:earned and UgBLBlatt2
*UgBLBlatt3a
		name:Buchenblatt
		desc:<.> Erhöht die Produktion der Blätter um <b>10</b> %.
		icon:icons[1,3] icons[3,2]
		req:2600000000 Larven:earned and UgBLBlatt3
*UgBLBlatt4a
		name:Birkenblatt
		desc:<.> Erhöht die Produktion der Blätter um <b>10</b> %.
		icon:icons[1,3] icons[3,3]
		req:260000000000 Larven:earned and UgBLBlatt4
*UgBLBlatt5a
		name:Eschenblatt
		desc:<.> Erhöht die Produktion der Blätter um <b>10</b> %.
		icon:icons[1,3] icons[3,4]
		req:26000000000000 Larven:earned and UgBLBlatt5
*UgBLBlatt6a
		name:Erlenblatt
		desc:<.> Erhöht die Produktion der Blätter um <b>10</b> %.
		icon:icons[1,3] icons[3,5]
		req:2600000000000000 Larven:earned and UgBLBlatt6
*UgBLBlatt7a
		name:Haselblatt
		desc:<.> Erhöht die Produktion der Blätter um <b>10</b> %.
		icon:icons[1,3] icons[3,6]
		req:260000000000000000 Larven:earned and UgBLBlatt7
*UgBLBlatt8a
		name:Wallnussblatt
		desc:<.> Erhöht die Produktion der Blätter um <b>10</b> %.
		icon:icons[1,3] icons[3,7]
		req:26000000000000000000 Larven:earned and UgBLBlatt8
*UgBLBlatt9a
		name:Kastanienblatt
		desc:<.> Erhöht die Produktion der Blätter um <b>10</b> %.
		icon:icons[1,3] icons[3,8]
		req:2600000000000000000000 Larven:earned and UgBLBlatt9
*UgBLBlatt10a
		name:Lärchenblatt
		desc:<.> Erhöht die Produktion der Blätter um <b>10</b> %.
		icon:icons[1,3] icons[3,9]
		req:260000000000000000000000 Larven:earned and UgBLBlatt10
*UgBLBlatt11a
		name:Palmenblatt
		desc:<.> Erhöht die Produktion der Blätter um <b>10</b> %.
		icon:icons[1,3] icons[3,10]
		req:26000000000000000000000000 Larven:earned and UgBLBlatt11
*UgBLBlatt12a
		name:Lindenblatt
		desc:<.> Erhöht die Produktion der Blätter um <b>10</b> %.
		icon:icons[1,3] icons[3,11]
		req:2600000000000000000000000000 Larven:earned and UgBLBlatt12
		
//4a
	
*UgBLBlattF1a
		name:Ahorn Blatt
		desc:<.> Erhöht die Produktion der Blätter um <b>75</b> %.
		icon:icons[12,0]
		req:UgBLBlattF1
		class:noBackground
*UgBLBlattF2a
		name:Birken Blatt
		desc:<.> Erhöht die Produktion der Blätter um <b>75</b> %.
		icon:icons[12,1] 
		req:25 Blatt and UgBLBlattF2
		class:noBackground
*UgBLBlattF3a
		name:Eichen Blatt
		desc:<.> Erhöht die Produktion der Blätter um <b>75</b> %.
		icon:icons[12,2]
		req:50 Blatt and UgBLBlattF3
		class:noBackground 
*UgBLBlattF4a
		name:Buchen Blatt
		desc:<.> Erhöht die Produktion der Blätter um <b>75</b> %.
		icon:icons[12,3]
		req:75 Blatt and UgBLBlattF4
		class:noBackground
*UgBLBlattF5a
		name:Birnen Blatt
		desc:<.> Erhöht die Produktion der Blätter um <b>75</b> %.
		icon:icons[12,4]
		req:100 Blatt and UgBLBlattF5
		class:noBackground
*UgBLBlattF6a
		name:Ebereschen Blatt
		desc:<.> Erhöht die Produktion der Blätter um <b>75</b> %.
		icon:icons[12,5]
		req:125 Blatt and UgBLBlattF6
		class:noBackground
*UgBLBlattF7a
		name:Erlen Blatt
		desc:<.> Erhöht die Produktion der Blätter um <b>75</b> %.
		icon:icons[12,6]
		req:150 Blatt and UgBLBlattF7
		class:noBackground
*UgBLBlattF8a
		name:Kastanien Blatt
		desc:<.> Erhöht die Produktion der Blätter um <b>75</b> %.
		icon:icons[12,7]
		req:175 Blatt and UgBLBlattF8
		class:noBackground
*UgBLBlattF9a
		name:Linden Blatt
		desc:<.> Erhöht die Produktion der Blätter um <b>75</b> %.
		icon:icons[12,8]
		req:200 Blatt and UgBLBlattF9
		class:noBackground
*UgBLBlattF10a
		name:Schwarzdorn Blatt
		desc:<.> Erhöht die Produktion der Blätter um <b>75</b> %.
		icon:icons[12,9]
		req:225 Blatt and UgBLBlattF10
		class:noBackground
*UgBLBlattF11a
		name:Stechpalmen Blatt
		desc:<.> Erhöht die Produktion der Blätter um <b>75</b> %.
		icon:icons[12,10]
		req:250 Blatt and UgBLBlattF11
		class:noBackground
*UgBLBlattF12a
		name:Ulmen Blatt
		desc:<.> Erhöht die Produktion der Blätter um <b>75</b> %.
		icon:icons[12,11]
		req:275 Blatt and UgBLBlattF12
		class:noBackground
*UgBLBlattF13a
		name:Weiden Blatt
		desc:<.> Erhöht die Produktion der Blätter um <b>75</b> %.
		icon:icons[12,12]
		req:300 Blatt and UgBLBlattF13
		class:noBackground
*UgBLBlattF14a
		name:Pappel Blatt
		desc:<.> Erhöht die Produktion der Blätter um <b>75</b> %.
		icon:icons[12,13]
		req:325 Blatt and UgBLBlattF14
		class:noBackground
*UgBLBlattF15a
		name:Apfel Blatt
		desc:<.> Erhöht die Produktion der Blätter um <b>75</b> %.
		icon:icons[12,14]
		req:350 Blatt and UgBLBlattF15
		class:noBackground
		
//5a

*UgBLWNest1a
		name:Bssst!
		desc:<.> Erhöht die Produktion der WespenNester um <b>10</b> %.
		icon:icons[1,4] icons[3,0]
		req:UgBLWNest1
*UgBLWNest2a
		name:Zartes WespenNest
		desc:<.> Erhöht die Produktion der WespenNester um <b>10</b> %.
		icon:icons[1,4] icons[3,1]
		req:145600000 Larven:earned and UgBLWNest2
*UgBLWNest3a
		name:Feines WespenNest
		desc:<.> Erhöht die Produktion der WespenNester um <b>10</b> %.
		icon:icons[1,4] icons[3,2]
		req:14560000000 Larven:earned and UgBLWNest3
*UgBLWNest4a
		name:Großes WespenNest
		desc:<.> Erhöht die Produktion der WespenNester um <b>10</b> %.
		icon:icons[1,4] icons[3,3]
		req:1456000000000 Larven:earned and UgBLWNest4
*UgBLWNest5a
		name:Langes WespenNest
		desc:<.> Erhöht die Produktion der WespenNester um <b>10</b> %.
		icon:icons[1,4] icons[3,4]
		req:145600000000000 Larven:earned and UgBLWNest5
*UgBLWNest6a
		name:Dickes WespenNest
		desc:<.> Erhöht die Produktion der WespenNester um <b>10</b> %.
		icon:icons[1,4] icons[3,5]
		req:14560000000000000 Larven:earned and UgBLWNest6
*UgBLWNest7a
		name:Dünnes WespenNest
		desc:<.> Erhöht die Produktion der WespenNester um <b>10</b> %.
		icon:icons[1,4] icons[3,6]
		req:1456000000000000000 Larven:earned and UgBLWNest7
*UgBLWNest8a
		name:Altes WespenNest
		desc:<.> Erhöht die Produktion der WespenNester um <b>10</b> %.
		icon:icons[1,4] icons[3,7]
		req:145600000000000000000 Larven:earned and UgBLWNest8
*UgBLWNest9a
		name:Dunkles WespenNest
		desc:<.> Erhöht die Produktion der WespenNester um <b>10</b> %.
		icon:icons[1,4] icons[3,8]
		req:14560000000000000000000 Larven:earned and UgBLWNest9
*UgBLWNest10a
		name:Helles WespenNest
		desc:<.> Erhöht die Produktion der WespenNester um <b>10</b> %.
		icon:icons[1,4] icons[3,9]
		req:1456000000000000000000000 Larven:earned and UgBLWNest10
*UgBLWNest11a
		name:Gespaltenes WespenNest
		desc:<.> Erhöht die Produktion der WespenNester um <b>10</b> %.
		icon:icons[1,4] icons[3,10]
		req:145600000000000000000000000 Larven:earned and UgBLWNest11
*UgBLWNest12a
		name:WespenNester Haufen
		desc:<.> Erhöht die Produktion der WespenNester um <b>10</b> %.
		icon:icons[1,4] icons[3,11]
		req:14560000000000000000000000000 Larven:earned and UgBLWNest12

//5a
	
*UgBLWespenNestF1a
		name:Kleine Verstärkung
		desc:<.> Erhöht die Produktion der WespenNester um <b>75</b> %.
		icon:icons[13,0]
		req:UgBLWespenNestF1
		class:noBackground
*UgBLWespenNestF2a
		name:Holz Vertäfelung
		desc:<.> Erhöht die Produktion der WespenNester um <b>75</b> %.
		icon:icons[13,1] 
		req:25 WespenNest and UgBLWespenNestF2
		class:noBackground
*UgBLWespenNestF3a
		name:Strauch Schutz
		desc:<.> Erhöht die Produktion der WespenNester um <b>75</b> %.
		icon:icons[13,2]
		req:50 WespenNest and UgBLWespenNestF3
		class:noBackground
*UgBLWespenNestF4a
		name:Äste Rahmen
		desc:<.> Erhöht die Produktion der WespenNester um <b>75</b> %.
		icon:icons[13,3]
		req:75 WespenNest and UgBLWespenNestF4
		class:noBackground
*UgBLWespenNestF5a
		name:Dornen
		desc:<.> Erhöht die Produktion der WespenNester um <b>75</b> %.
		icon:icons[13,4]
		req:100 WespenNest and UgBLWespenNestF5
		class:noBackground
*UgBLWespenNestF6a
		name:Dickere Wände
		desc:<.> Erhöht die Produktion der WespenNester um <b>75</b> %.
		icon:icons[13,5]
		req:125 WespenNest and UgBLWespenNestF6
		class:noBackground
*UgBLWespenNestF7a
		name:Brutplätze
		desc:<.> Erhöht die Produktion der WespenNester um <b>75</b> %.
		icon:icons[13,6]
		req:150 WespenNest and UgBLWespenNestF7
		class:noBackground
*UgBLWespenNestF8a
		name:Zweiter Eingang
		desc:<.> Erhöht die Produktion der WespenNester um <b>75</b> %.
		icon:icons[13,7]
		req:175 WespenNest and UgBLWespenNestF8
		class:noBackground
*UgBLWespenNestF9a
		name:Harte Schale
		desc:<.> Erhöht die Produktion der WespenNester um <b>75</b> %.
		icon:icons[13,8]
		req:200 WespenNest and UgBLWespenNestF9
		class:noBackground
*UgBLWespenNestF10a
		name:Windschutz
		desc:<.> Erhöht die Produktion der WespenNester um <b>75</b> %.
		icon:icons[13,9]
		req:225 WespenNest and UgBLWespenNestF10
		class:noBackground
*UgBLWespenNestF11a
		name:Ein paar Zweige mehr
		desc:<.> Erhöht die Produktion der WespenNester um <b>75</b> %.
		icon:icons[13,10]
		req:250 WespenNest and UgBLWespenNestF11
		class:noBackground
*UgBLWespenNestF12a
		name:Nestbauerinnen
		desc:<.> Erhöht die Produktion der WespenNester um <b>75</b> %.
		icon:icons[13,11]
		req:275 WespenNest and UgBLWespenNestF12
		class:noBackground
*UgBLWespenNestF13a
		name:Wespen Königin
		desc:<.> Erhöht die Produktion der WespenNester um <b>75</b> %.
		icon:icons[13,12]
		req:300 WespenNest and UgBLWespenNestF13
		class:noBackground
*UgBLWespenNestF14a
		name:Wespen Prinzessin
		desc:<.> Erhöht die Produktion der WespenNester um <b>75</b> %.
		icon:icons[13,13]
		req:325 WespenNest and UgBLWespenNestF14
		class:noBackground
*UgBLWespenNestF15a
		name:Wespen Staat
		desc:<.> Erhöht die Produktion der WespenNester um <b>75</b> %.
		icon:icons[13,14]
		req:350 WespenNest and UgBLWespenNestF15
		class:noBackground
				

//6a


*UgBLVApfel1a
		name:Verfaulter Elstar
		desc:<.> Erhöht die Produktion der VerfaultenÄpfel um <b>10</b> %.
		icon:icons[1,5] icons[3,0]
		req:UgBLVApfel1
*UgBLVApfel2a
		name:Verfaulter Gala
		desc:<.> Erhöht die Produktion der VerfaultenÄpfel um <b>10</b> %.
		icon:icons[1,5] icons[3,1]
		req:16580000000 Larven:earned and UgBLVApfel2
*UgBLVApfel3a
		name:Verfaulter Iduna
		desc:<.> Erhöht die Produktion der VerfaultenÄpfel um <b>10</b> %.
		icon:icons[1,5] icons[3,2]
		req:1658000000000 Larven:earned and UgBLVApfel3
*UgBLVApfel4a
		name:Verfaulter Maigold
		desc:<.> Erhöht die Produktion der VerfaultenÄpfel um <b>10</b> %.
		icon:icons[1,5] icons[3,3]
		req:165800000000000 Larven:earned and UgBLVApfel4
*UgBLVApfel5a
		name:Verfaulter Brauner Apfel
		desc:<.> Erhöht die Produktion der VerfaultenÄpfel um <b>10</b> %.
		icon:icons[1,5] icons[3,4]
		req:16580000000000000 Larven:earned and UgBLVApfel5
*UgBLVApfel6a
		name:Verfaulter Alter Apfel
		desc:<.> Erhöht die Produktion der VerfaultenÄpfel um <b>10</b> %.
		icon:icons[1,5] icons[3,5]
		req:1658000000000000000 Larven:earned and UgBLVApfel6
*UgBLVApfel7a
		name:Verfaulter Red Delicious
		desc:<.> Erhöht die Produktion der VerfaultenÄpfel um <b>10</b> %.
		icon:icons[1,5] icons[3,6]
		req:165800000000000000000 Larven:earned and UgBLVApfel7
*UgBLVApfel8a
		name:Verfaulter Golden Delicious
		desc:<.> Erhöht die Produktion der VerfaultenÄpfel um <b>10</b> %.
		icon:icons[1,5] icons[3,7]
		req:16580000000000000000000 Larven:earned and UgBLVApfel8
*UgBLVApfel9a
		name:Verfaulter Yataka
		desc:<.> Erhöht die Produktion der VerfaultenÄpfel um <b>10</b> %.
		icon:icons[1,5] icons[3,8]
		req:1658000000000000000000000 Larven:earned and UgBLVApfel9
*UgBLVApfel10a
		name:Verfaulter Jonagold
		desc:<.> Erhöht die Produktion der VerfaultenÄpfel um <b>10</b> %.
		icon:icons[1,5] icons[3,9]
		req:165800000000000000000000000 Larven:earned and UgBLVApfel10
*UgBLVApfel11a
		name:Verfaulter Kanzi
		desc:<.> Erhöht die Produktion der VerfaultenÄpfel um <b>10</b> %.
		icon:icons[1,5] icons[3,10]
		req:16580000000000000000000000000 Larven:earned and UgBLVApfel11
*UgBLVApfel12a
		name:Verfaulter Kleiner Apfel
		desc:<.> Erhöht die Produktion der VerfaultenÄpfel um <b>10</b> %.
		icon:icons[1,5] icons[3,11]
		req:1658000000000000000000000000000 Larven:earned and UgBLVApfel12
		


//6a
	
*UgBLVApfelF1a
		name:Brauner Apfel
		desc:<.> Erhöht die Produktion der VerfaultenÄpfel um <b>75</b> %.
		icon:icons[14,0]
		req:UgBLVApfelF1
		class:noBackground
*UgBLVApfelF2a
		name:Schrumpeliger Apfel
		desc:<.> Erhöht die Produktion der VerfaultenÄpfel um <b>75</b> %.
		icon:icons[14,1] 
		req:25 VerfaulterApfel and UgBLVApfelF2
		class:noBackground
*UgBLVApfelF3a
		name:Angeschlagener Apfel
		desc:<.> Erhöht die Produktion der VerfaultenÄpfel um <b>75</b> %.
		icon:icons[14,2]
		req:50 VerfaulterApfel and UgBLVApfelF3
		class:noBackground
*UgBLVApfelF4a
		name:Matschiger Apfel
		desc:<.> Erhöht die Produktion der VerfaultenÄpfel um <b>75</b> %.
		icon:icons[14,3]
		req:75 VerfaulterApfel and UgBLVApfelF4
		class:noBackground
*UgBLVApfelF5a
		name:Angefressener Apfel
		desc:<.> Erhöht die Produktion der VerfaultenÄpfel um <b>75</b> %.
		icon:icons[14,4]
		req:100 VerfaulterApfel and UgBLVApfelF5
		class:noBackground
*UgBLVApfelF6a
		name:Fauliger Apfel
		desc:<.> Erhöht die Produktion der VerfaultenÄpfel um <b>75</b> %.
		icon:icons[14,5]
		req:125 VerfaulterApfel and UgBLVApfelF6
		class:noBackground
*UgBLVApfelF7a
		name:Stinkender Apfel
		desc:<.> Erhöht die Produktion der VerfaultenÄpfel um <b>75</b> %.
		icon:icons[14,6]
		req:150 VerfaulterApfel and UgBLVApfelF7
		class:noBackground
*UgBLVApfelF8a
		name:Weicher Apfel
		desc:<.> Erhöht die Produktion der VerfaultenÄpfel um <b>75</b> %.
		icon:icons[14,7]
		req:175 VerfaulterApfel and UgBLVApfelF8
		class:noBackground
*UgBLVApfelF9a
		name:Fester Apfel
		desc:<.> Erhöht die Produktion der VerfaultenÄpfel um <b>75</b> %.
		icon:icons[14,8]
		req:200 VerfaulterApfel and UgBLVApfelF9
		class:noBackground
*UgBLVApfelF10a
		name:Großer Apfel
		desc:<.> Erhöht die Produktion der VerfaultenÄpfel um <b>75</b> %.
		icon:icons[14,9]
		req:225 VerfaulterApfel and UgBLVApfelF10
		class:noBackground
*UgBLVApfelF11a
		name:Ein Stück Apfel
		desc:<.> Erhöht die Produktion der VerfaultenÄpfel um <b>75</b> %.
		icon:icons[14,10]
		req:250 VerfaulterApfel and UgBLVApfelF11
		class:noBackground
*UgBLVApfelF12a
		name:Mehliger Apfel
		desc:<.> Erhöht die Produktion der VerfaultenÄpfel um <b>75</b> %.
		icon:icons[14,11]
		req:275 VerfaulterApfel and UgBLVApfelF12
		class:noBackground
*UgBLVApfelF13a
		name:Alter Apfel
		desc:<.> Erhöht die Produktion der VerfaultenÄpfel um <b>75</b> %.
		icon:icons[14,12]
		req:300 VerfaulterApfel and UgBLVApfelF13
		class:noBackground
*UgBLVApfelF14a
		name:Grüner Apfel
		desc:<.> Erhöht die Produktion der VerfaultenÄpfel um <b>75</b> %.
		icon:icons[14,13]
		req:325 VerfaulterApfel and UgBLVApfelF14
		class:noBackground
*UgBLVApfelF15a
		name:Runder Apfel
		desc:<.> Erhöht die Produktion der VerfaultenÄpfel um <b>75</b> %.
		icon:icons[14,14]
		req:350 VerfaulterApfel and UgBLVApfelF15	
		class:noBackground
								
	

//7a


*UgBLANest1a
		name:VogelNest
		desc:<.> Erhöht die Produktion der AltenNester um <b>10</b> %.
		icon:icons[0,0]
		req:UgBLANest1
*UgBLANest2a
		name:EntenNest
		desc:<.> Erhöht die Produktion der AltenNester um <b>10</b> %.
		icon:icons[0,1]
		req:2240000000000 Larven:earned and UgBLANest2
*UgBLANest3a
		name:EulenNest
		desc:<.> Erhöht die Produktion der AltenNester um <b>10</b> %.
		icon:icons[0,2]
		req:224000000000000 Larven:earned and UgBLANest3
*UgBLANest4a
		name:SpatzNest
		desc:<.> Erhöht die Produktion der AltenNester um <b>10</b> %.
		icon:icons[0,3]
		req:22400000000000000 Larven:earned and UgBLANest4
*UgBLANest5a
		name:BaumNest
		desc:<.> Erhöht die Produktion der AltenNester um <b>10</b> %.
		icon:icons[0,4]
		req:2240000000000000000 Larven:earned and UgBLANest5
*UgBLANest6a
		name:SchwalbenNest
		desc:<.> Erhöht die Produktion der AltenNester um <b>10</b> %.
		icon:icons[0,5]
		req:224000000000000000000 Larven:earned and UgBLANest6
*UgBLANest7a
		name:AdlerNest
		desc:<.> Erhöht die Produktion der AltenNester um <b>10</b> %.
		icon:icons[0,6]
		req:22400000000000000000000 Larven:earned and UgBLANest7
*UgBLANest8a
		name:FalkenNest
		desc:<.> Erhöht die Produktion der AltenNester um <b>10</b> %.
		icon:icons[0,7]
		req:2240000000000000000000000 Larven:earned and UgBLANest8
*UgBLANest9a
		name:BussardNest
		desc:<.> Erhöht die Produktion der AltenNester um <b>10</b> %.
		icon:icons[0,8]
		req:224000000000000000000000000 Larven:earned and UgBLANest9
*UgBLANest10a
		name:Verfaulter Jonagold
		desc:<.> Erhöht die Produktion der AltenNester um <b>10</b> %.
		icon:icons[0,9]
		req:22400000000000000000000000000 Larven:earned and UgBLANest10
*UgBLANest11a
		name:HabichtNest
		desc:<.> Erhöht die Produktion der AltenNester um <b>10</b> %.
		icon:icons[0,10]
		req:2240000000000000000000000000000 Larven:earned and UgBLANest11
*UgBLANest12a
		name:HühnerNest
		desc:<.> Erhöht die Produktion der AltenNester um <b>10</b> %.
		icon:icons[0,11]
		req:224000000000000000000000000000000 Larven:earned and UgBLANest12
		


//7a
	
*UgBLANestF1a
		name:Nestlein
		desc:<.> Erhöht die Produktion der AltenNester um <b>75</b> %.
		icon:icons[5,5] icons[20,0]
		req:UgBLANestF1
*UgBLANestF2a
		name:Nest im Baum
		desc:<.> Erhöht die Produktion der AltenNester um <b>75</b> %.
		icon:icons[5,5] icons[20,1] 
		req:25 AlteNester and UgBLANestF2
*UgBLANestF3a
		name:Ovales Nest
		desc:<.> Erhöht die Produktion der AltenNester um <b>75</b> %.
		icon:icons[5,5] icons[20,2]
		req:50 AlteNester and UgBLANestF3
*UgBLANestF4a
		name:Rundes Nest 
		desc:<.> Erhöht die Produktion der AltenNester um <b>75</b> %.
		icon:icons[5,5] icons[20,3]
		req:75 AlteNester and UgBLANestF4
*UgBLANestF5a
		name:Zugiges Nest
		desc:<.> Erhöht die Produktion der AltenNester um <b>75</b> %.
		icon:icons[5,5] icons[20,4]
		req:100 AlteNester and UgBLANestF5
*UgBLANestF6a
		name:Warmes Nest
		desc:<.> Erhöht die Produktion der AltenNester um <b>75</b> %.
		icon:icons[5,5] icons[20,5]
		req:125 AlteNester and UgBLANestF6
*UgBLANestF7a
		name:Löchriges Nest
		desc:<.> Erhöht die Produktion der AltenNester um <b>75</b> %.
		icon:icons[5,5] icons[20,6]
		req:150 AlteNester and UgBLANestF7
*UgBLANestF8a
		name:Kaputtes Nest
		desc:<.> Erhöht die Produktion der AltenNester um <b>75</b> %.
		icon:icons[5,5] icons[20,7]
		req:175 AlteNester and UgBLANestF8
*UgBLANestF9a
		name:Feines Nest
		desc:<.> Erhöht die Produktion der AltenNester um <b>75</b> %.
		icon:icons[5,5] icons[20,8]
		req:200 AlteNester and UgBLANestF9
*UgBLANestF10a
		name:Verstecktes Nest
		desc:<.> Erhöht die Produktion der AltenNester um <b>75</b> %.
		icon:icons[5,5] icons[20,9]
		req:225 AlteNester and UgBLANestF10
*UgBLANestF11a
		name:Verworrenes Nest
		desc:<.> Erhöht die Produktion der AltenNester um <b>75</b> %.
		icon:icons[5,5] icons[20,10]
		req:250 AlteNester and UgBLANestF11
*UgBLANestF12a
		name:Großes Nest
		desc:<.> Erhöht die Produktion der AltenNester um <b>75</b> %.
		icon:icons[5,5] icons[20,11]
		req:275 AlteNester and UgBLANestF12
*UgBLANestF13a
		name:Spatzle Nestle
		desc:<.> Erhöht die Produktion der AltenNester um <b>75</b> %.
		icon:icons[5,5] icons[20,12]
		req:300 AlteNester and UgBLANestF13
*UgBLANestF14a
		name:Hühner Nest
		desc:<.> Erhöht die Produktion der AltenNester um <b>75</b> %.
		icon:icons[5,5] icons[20,13]
		req:325 AlteNester and UgBLANestF14
*UgBLANestF15a
		name:Vogel Nest
		desc:<.> Erhöht die Produktion der AltenNester um <b>75</b> %.
		icon:icons[5,5] icons[20,14]
		req:350 AlteNester and UgBLANestF15
			


	
//8	a


*UgBLSchuh1a
		name:Sniker
		desc:<.> Erhöht die Produktion der Schuhe um <b>75</b> %.
		icon:icons[1,0]
		req:UgBLSchuh1
*UgBLSchuh2a
		name:Sportschuh
		desc:<.> Erhöht die Produktion der Schuhe um <b>75</b> %.
		icon:icons[1,1]
		req:358400000000 Larven:earned and UgBLSchuh2
*UgBLSchuh3a
		name:Pump
		desc:<.> Erhöht die Produktion der Schuhe um <b>75</b> %.
		icon:icons[1,2]
		req:35840000000000 Larven:earned and UgBLSchuh3
*UgBLSchuh4a
		name:Ballerina
		desc:<.> Erhöht die Produktion der Schuhe um <b>75</b> %.
		icon:icons[1,3]
		req:3584000000000000 Larven:earned and UgBLSchuh4
*UgBLSchuh5a
		name:Stiefel
		desc:<.> Erhöht die Produktion der Schuhe um <b>75</b> %.
		icon:icons[1,4]
		req:358400000000000000 Larven:earned and UgBLSchuh5
*UgBLSchuh6a
		name:Sandale
		desc:<.> Erhöht die Produktion der Schuhe um <b>75</b> %.
		icon:icons[1,5]
		req:35840000000000000000 Larven:earned and UgBLSchuh6
*UgBLSchuh7a
		name:Schnürschuh
		desc:<.> Erhöht die Produktion der Schuhe um <b>75</b> %.
		icon:icons[1,6]
		req:3584000000000000000000 Larven:earned and UgBLSchuh7
*UgBLSchuh8a
		name:Gummistiefel
		desc:<.> Erhöht die Produktion der Schuhe um <b>75</b> %.
		icon:icons[1,7]
		req:358400000000000000000000 Larven:earned and UgBLSchuh8
*UgBLSchuh9a
		name:Boots
		desc:<.> Erhöht die Produktion der Schuhe um <b>75</b> %.
		icon:icons[1,8]
		req:35840000000000000000000000 Larven:earned and UgBLSchuh9
*UgBLSchuh10a
		name:Rollschuh
		desc:<.> Erhöht die Produktion der Schuhe um <b>75</b> %.
		icon:icons[1,9]
		req:3584000000000000000000000000 Larven:earned and UgBLSchuh10
*UgBLSchuh11a
		name:Stieflette
		desc:<.> Erhöht die Produktion der Schuhe um <b>75</b> %.
		icon:icons[1,10]
		req:358400000000000000000000000000 Larven:earned and UgBLSchuh11
*UgBLSchuh12a
		name:Hausschuh
		desc:<.> Erhöht die Produktion der Schuhe um <b>75</b> %.
		icon:icons[1,11]
		req:35840000000000000000000000000000 Larven:earned and UgBLSchuh12
		
	
//8a
	
*UgBLSchuhF1a
		name:Trockener Schuh
		desc:<.> Erhöht die Produktion der Schuhe um <b>75</b> %.
		icon:icons[2,0]
		req:UgBLSchuhF1
*UgBLSchuhF2a
		name:Feuchter Schuh
		desc:<.> Erhöht die Produktion der Schuhe um <b>75</b> %.
		icon:icons[2,1] 
		req:25 UeberwucherterSchuh and UgBLSchuhF2
*UgBLSchuhF3a
		name:Nasser Schuh
		desc:<.> Erhöht die Produktion der Schuhe um <b>75</b> %.
		icon:icons[2,2]
		req:50 UeberwucherterSchuh and UgBLSchuhF3
*UgBLSchuhF4a
		name:Bunter Schuh
		desc:<.> Erhöht die Produktion der Schuhe um <b>75</b> %.
		icon:icons[2,3]
		req:75 UeberwucherterSchuh and UgBLSchuhF4
*UgBLSchuhF5a
		name:Spitzer Schuh
		desc:<.> Erhöht die Produktion der Schuhe um <b>75</b> %.
		icon:icons[2,4]
		req:100 UeberwucherterSchuh and UgBLSchuhF5
*UgBLSchuhF6a
		name:Leder Schuh
		desc:<.> Erhöht die Produktion der Schuhe um <b>75</b> %.
		icon:icons[2,5]
		req:125 UeberwucherterSchuh and UgBLSchuhF6
*UgBLSchuhF7a
		name:Brauner Schuh
		desc:<.> Erhöht die Produktion der Schuhe um <b>75</b> %.
		icon:icons[2,6]
		req:150 UeberwucherterSchuh and UgBLSchuhF7
*UgBLSchuhF8a
		name:Alter Schuh
		desc:<.> Erhöht die Produktion der Schuhe um <b>75</b> %.
		icon:icons[2,7]
		req:175 UeberwucherterSchuh and UgBLSchuhF8
*UgBLSchuhF9a
		name:Eingewachsener Schuh
		desc:<.> Erhöht die Produktion der Schuhe um <b>75</b> %.
		icon:icons[2,8]
		req:200 UeberwucherterSchuh and UgBLSchuhF9
*UgBLSchuhF10a
		name:Verfaulter Schuh
		desc:<.> Erhöht die Produktion der Schuhe um <b>75</b> %.
		icon:icons[2,9]
		req:225 UeberwucherterSchuh and UgBLSchuhF10
*UgBLSchuhF11a
		name:Vermoderter Schuh
		desc:<.> Erhöht die Produktion der Schuhe um <b>75</b> %.
		icon:icons[2,10]
		req:250 UeberwucherterSchuh and UgBLSchuhF11
*UgBLSchuhF12a
		name:Löchriger Schuh
		desc:<.> Erhöht die Produktion der Schuhe um <b>75</b> %.
		icon:icons[2,11]
		req:275 UeberwucherterSchuh and UgBLSchuhF12
*UgBLSchuhF13a
		name:Zerfetzter Schuh
		desc:<.> Erhöht die Produktion der Schuhe um <b>75</b> %.
		icon:icons[2,12]
		req:300 UeberwucherterSchuh and UgBLSchuhF13
*UgBLSchuhF14a
		name:Angenagter Schuh
		desc:<.> Erhöht die Produktion der Schuhe um <b>75</b> %.
		icon:icons[2,13]
		req:325 UeberwucherterSchuh and UgBLSchuhF14
*UgBLSchuhF15a
		name:Zerkratzter Schuh
		desc:<.> Erhöht die Produktion der Schuhe um <b>75</b> %.
		icon:icons[2,14]
		req:350 UeberwucherterSchuh and UgBLSchuhF15
			
								

//9a


*UgBLPizza1a
		name:Pizza Margherita
		desc:<.> Erhöht die Produktion der Pizzen um <b>75</b> %.
		icon:iconsb[3,0]
		req:UgBLPizza1
*UgBLPizza2a
		name:Pizza Salamie
		desc:<.> Erhöht die Produktion der Pizzen um <b>75</b> %.
		icon:iconsb[3,1]
		req:4956000000000 Larven:earned and UgBLPizza2
*UgBLPizza3a
		name:Pizza Prosciutto
		desc:<.> Erhöht die Produktion der Pizzen um <b>75</b> %.
		icon:iconsb[3,2]
		req:495600000000000 Larven:earned and UgBLPizza3
*UgBLPizza4a
		name:Pizza Funghi
		desc:<.> Erhöht die Produktion der Pizzen um <b>75</b> %.
		icon:iconsb[3,3]
		req:49560000000000000 Larven:earned and UgBLPizza4
*UgBLPizza5a
		name:Pizza Peperoni
		desc:<.> Erhöht die Produktion der Pizzen um <b>75</b> %.
		icon:iconsb[3,4]
		req:4956000000000000000 Larven:earned and UgBLPizza5
*UgBLPizza6a
		name:Pizza Quattro Stagion
		desc:<.> Erhöht die Produktion der Pizzen um <b>75</b> %.
		icon:iconsb[3,5]
		req:495600000000000000000 Larven:earned and UgBLPizza6
*UgBLPizza7a
		name:Pizza Tonno
		desc:<.> Erhöht die Produktion der Pizzen um <b>75</b> %.
		icon:iconsb[3,6]
		req:49560000000000000000000 Larven:earned and UgBLPizza7
*UgBLPizza8a
		name:Pizza Bolognese
		desc:<.> Erhöht die Produktion der Pizzen um <b>75</b> %.
		icon:iconsb[3,7]
		req:4956000000000000000000000 Larven:earned and UgBLPizza8
*UgBLPizza9a
		name:Pizza Calzone
		desc:<.> Erhöht die Produktion der Pizzen um <b>75</b> %.
		icon:iconsb[3,8]
		req:495600000000000000000000000 Larven:earned and UgBLPizza9
*UgBLPizza10a
		name:Pizza Napoli
		desc:<.> Erhöht die Produktion der Pizzen um <b>75</b> %.
		icon:iconsb[3,9]
		req:49560000000000000000000000000 Larven:earned and UgBLPizza10
*UgBLPizza11a
		name:Pizza Verdi
		desc:<.> Erhöht die Produktion der Pizzen um <b>75</b> %.
		icon:iconsb[3,10]
		req:4956000000000000000000000000000 Larven:earned and UgBLPizza11
*UgBLPizza12a
		name:Pizza Vulcano
		desc:<.> Erhöht die Produktion der Pizzen um <b>75</b> %.
		icon:iconsb[3,11]
		req:495600000000000000000000000000000 Larven:earned and UgBLPizza12
		

	


//9
	
*UgBLPizzaF1a
		name:Pizza Rustika
		desc:<.> Erhöht die Produktion der Pizzen um <b>75</b> %.
		icon:icons[5,5] iconsb[4,0]
		req:UgBLPizzaF1
*UgBLPizzaF2a
		name:Pizza La Bella
		desc:<.> Erhöht die Produktion der Pizzen um <b>75</b> %.
		icon:icons[5,5] iconsb[4,1] 
		req:25 Pizza and UgBLPizzaF2
*UgBLPizzaF3a
		name:Pizza Peperoniwurst
		desc:<.> Erhöht die Produktion der Pizzen um <b>75</b> %.
		icon:icons[5,5] iconsb[4,2]
		req:50 Pizza and UgBLPizzaF3
*UgBLPizzaF4a
		name:Familienpizza
		desc:<.> Erhöht die Produktion der Pizzen um <b>75</b> %.
		icon:icons[5,5] iconsb[4,3]
		req:75 Pizza and UgBLPizzaF4
*UgBLPizzaF5a
		name:Pizza alla Panna
		desc:<.> Erhöht die Produktion der Pizzen um <b>75</b> %.
		icon:icons[5,5] iconsb[4,4]
		req:100 Pizza and UgBLPizzaF5
*UgBLPizzaF6a
		name:Weiche Pizza
		desc:<.> Erhöht die Produktion der Pizzen um <b>75</b> %.
		icon:icons[5,5] iconsb[4,5]
		req:125 Pizza and UgBLPizzaF6
*UgBLPizzaF7a
		name:Matschige Pizza 
		desc:<.> Erhöht die Produktion der Pizzen um <b>75</b> %.
		icon:icons[5,5] iconsb[4,6]
		req:150 Pizza and UgBLPizzaF7
*UgBLPizzaF8a
		name:Trockene Pizza
		desc:<.> Erhöht die Produktion der Pizzen um <b>75</b> %.
		icon:icons[5,5] iconsb[4,7]
		req:175 Pizza and UgBLPizzaF8
*UgBLPizzaF9a
		name:Knusprige Pizza
		desc:<.> Erhöht die Produktion der Pizzen um <b>75</b> %.
		icon:icons[5,5] iconsb[4,8]
		req:200 Pizza and UgBLPizzaF9
*UgBLPizzaF10a
		name:Leckere Pizza
		desc:<.> Erhöht die Produktion der Pizzen um <b>75</b> %.
		icon:icons[5,5] iconsb[4,9]
		req:225 Pizza and UgBLPizzaF10
*UgBLPizzaF11a
		name:Faulige Pizza
		desc:<.> Erhöht die Produktion der Pizzen um <b>75</b> %.
		icon:icons[5,5] iconsb[4,10]
		req:250 Pizza and UgBLPizzaF11
*UgBLPizzaF12a
		name:Schimmlige Pizza
		desc:<.> Erhöht die Produktion der Pizzen um <b>75</b> %.
		icon:icons[5,5] iconsb[4,11]
		req:275 Pizza and UgBLPizzaF12
*UgBLPizzaF13a
		name:Großes Pizza Stück
		desc:<.> Erhöht die Produktion der Pizzen um <b>75</b> %.
		icon:icons[5,5] iconsb[4,12]
		req:300 Pizza and UgBLPizzaF13
*UgBLPizzaF14a
		name:Angenagte Pizza
		desc:<.> Erhöht die Produktion der Pizzen um <b>75</b> %.
		icon:icons[5,5] iconsb[4,13]
		req:325 Pizza and UgBLPizzaF14
*UgBLPizzaF15a
		name:Pizzakrümel
		desc:<.> Erhöht die Produktion der Pizzen um <b>75</b> %.
		icon:icons[5,5] iconsb[4,14]
		req:350 Pizza and UgBLPizzaF15

			
							
					
						
						
						
						
						
						
						
						
						
						
//Insekten Upgrades a

	
		
		
// Upgrade Ressource Insekten	a	
		
		
		

*UgRIBlume1a
		name:Ackerwinde
		desc:<.> Erhöht die Produktion von Insekten um <b>1</b> %.
		icon:iconsa[5,0]
		req:UgRIBlume1
*UgRIBlume2a
		name:Azalee
		desc:<.> Erhöht die Produktion von Insekten um <b>1</b> %.
		icon:iconsa[5,1]
		req:250000 Insekten:earned and UgRIBlume2
*UgRIBlume3a
		name:Mandelröschen
		desc:<.> Erhöht die Produktion von Insekten um <b>1</b> %.
		icon:iconsa[5,2]
		req:500000 Insekten:earned and UgRIBlume3
*UgRIBlume4a
		name:Löwenmaul
		desc:<.> Erhöht die Produktion von Insekten um <b>1</b> %.
		icon:iconsa[5,3]
		req:2500000 Insekten:earned and UgRIBlume4
*UgRIBlume5a
		name:Geranie
		desc:<.> Erhöht die Produktion von Insekten um <b>1</b> %.
		icon:iconsa[5,4]
		req:5000000 Insekten:earned and UgRIBlume5
*UgRIBlume6a
		name:Aster
		desc:<.> Erhöht die Produktion von Insekten um <b>1</b> %.
		icon:iconsa[5,5]
		req:25000000 Insekten:earned and UgRIBlume6
*UgRIBlume7a
		name:Begonie
		desc:<.> Erhöht die Produktion von Insekten um <b>1</b> %.
		icon:iconsa[5,6]
		req:50000000 Insekten:earned and UgRIBlume7
*UgRIBlume8a
		name:Fleißiges Lieschen
		desc:<.> Erhöht die Produktion von Insekten um <b>1</b> %.
		icon:iconsa[5,7]
		req:250000000 Insekten:earned and UgRIBlume8
*UgRIBlume9a
		name:Kornrade
		desc:<.> Erhöht die Produktion von Insekten um <b>1</b> %.
		icon:iconsa[5,8]
		req:500000000 Insekten:earned and UgRIBlume9
*UgRIBlume10a
		name:Rose
		desc:<.> Erhöht die Produktion von Insekten um <b>1</b> %.
		icon:iconsa[5,9]
		req:2500000000 Insekten:earned and UgRIBlume10
*UgRIBlume11a
		name:Wicke
		desc:<.> Erhöht die Produktion von Insekten um <b>1</b> %.
		icon:iconsa[5,10]
		req:5000000000 Insekten:earned and UgRIBlume11
*UgRIBlume12a
		name:Zinnie
		desc:<.> Erhöht die Produktion von Insekten um <b>1</b> %.
		icon:iconsa[5,11]
		req:25000000000 Insekten:earned and UgRIBlume12
*UgRIBlume13a
		name:Strohblume
		desc:<.> Erhöht die Produktion von Insekten um <b>1</b> %.
		icon:iconsa[5,12]
		req:50000000000 Insekten:earned and UgRIBlume13
*UgRIBlume14a
		name:Kosmee
		desc:<.> Erhöht die Produktion von Insekten um <b>1</b> %.
		icon:iconsa[5,13]
		req:250000000000 Insekten:earned and UgRIBlume14
*UgRIBlume15a
		name:Iberis
		desc:<.> Erhöht die Produktion von Insekten um <b>1</b> %.
		icon:iconsa[5,14]
		req:UgRIBlume15
*UgRIBlume16a
		name:Elfenblume
		desc:<.> Erhöht die Produktion von Insekten um <b>1</b> %.
		icon:iconsa[5,15]
		req:5000000000000 Insekten:earned and UgRIBlume16
*UgRIBlume17a
		name:Blaukissen
		desc:<.> Erhöht die Produktion von Insekten um <b>1</b> %.
		icon:iconsa[5,16]
		req:25000000000000 Insekten:earned and UgRIBlume17
*UgRIBlume18a
		name:Eibisch
		desc:<.> Erhöht die Produktion von Insekten um <b>1</b> %.
		icon:iconsa[5,17]
		req:50000000000000 Insekten:earned and UgRIBlume18
*UgRIBlume19a
		name:Glockenblume
		desc:<.> Erhöht die Produktion von Insekten um <b>1</b> %.
		icon:iconsa[5,18]
		req:250000000000000 Insekten:earned and UgRIBlume19
*UgRIBlume20a
		name:Eisenhut
		desc:<.> Erhöht die Produktion von Insekten um <b>1</b> %.
		icon:iconsa[5,19]
		req:500000000000000 Insekten:earned and UgRIBlume20
*UgRIBlume21a
		name:Schleierkraut
		desc:<.> Erhöht die Produktion von Insekten um <b>1</b> %.
		icon:iconsa[5,20]
		req:2500000000000000 Insekten:earned and UgRIBlume21
		
		
		
	
		

		

*UgRINuss1a
		name:Mandeln
        desc:<.> Beim Klicken des Insektes bekommst du <b>2</b> mal so viel!
		icon:iconsa[6,0]
		req:UgRINuss1
*UgRINuss2a
		name:Cashewkerne
        desc:<.> Beim Klicken des Insektes bekommst du <b>3</b> mal so viel!
		icon:iconsa[6,1]
		req:250000 Insekten:earned and UgRINuss2
*UgRINuss3a
		name:Haselnüsse
        desc:<.> Beim Klicken des Insektes bekommst du <b>3</b> mal so viel!
		icon:iconsa[6,2]
		req:500000 Insekten:earned and UgRINuss3
*UgRINuss4a
		name:Paranuss
        desc:<.> Beim Klicken des Insektes bekommst du <b>3</b> mal so viel!
		icon:iconsa[6,3]
		req:2500000 Insekten:earned and UgRINuss4
*UgRINuss5a
		name:Pakannuss
		desc:<.> Beim Klicken des Insektes bekommst du <b>3</b> mal so viel!
		icon:iconsa[6,4]
		req:5000000 Insekten:earned and UgRINuss5
*UgRINuss6a
		name:Pistazien
		desc:<.> Beim Klicken des Insektes bekommst du <b>3</b> mal so viel!
		icon:iconsa[6,5]
		req:25000000 Insekten:earned and UgRINuss6
*UgRINuss7a
		name:Macadamianuss
		desc:<.> Beim Klicken des Insektes bekommst du <b>3</b> mal so viel!
		icon:iconsa[6,6]
		req:50000000 Insekten:earned and UgRINuss7
*UgRINuss8a
		name:Walnuss
		desc:<.> Beim Klicken des Insektes bekommst du <b>3</b> mal so viel!
		icon:iconsa[6,7]
		req:250000000 Insekten:earned and UgRINuss8
*UgRINuss9a
		name:Erdnuss
		desc:<.> Beim Klicken des Insektes bekommst du <b>3</b> mal so viel!
		icon:iconsa[6,8]
		req:500000000 Insekten:earned and UgRINuss9
*UgRINuss10a
		name:Eichel
		desc:<.> Beim Klicken des Insektes bekommst du <b>3</b> mal so viel!
		icon:iconsa[6,9]
		req:2500000000 Insekten:earned and UgRINuss10
*UgRINuss11a
		name:Edelkastanie
		desc:<.> Beim Klicken des Insektes bekommst du <b>3</b> mal so viel!
		icon:iconsa[6,10]
		req:5000000000 Insekten:earned and UgRINuss11
*UgRINuss12a
		name:Bucheckern
		desc:<.> Beim Klicken des Insektes bekommst du <b>3</b> mal so viel!
		icon:iconsa[6,11]
		req:25000000000 Insekten:earned and UgRINuss12
*UgRINuss13a
		name:Steinnuss
		desc:<.> Beim Klicken des Insektes bekommst du <b>3</b> mal so viel!
		icon:iconsa[6,12]
		req:50000000000 Insekten:earned and UgRINuss13
*UgRINuss14a
		name:Kleine Nuss
		desc:<.> Beim Klicken des Insektes bekommst du <b>3</b> mal so viel!
		icon:iconsa[6,13]
		req:250000000000 Insekten:earned and UgRINuss14
*UgRINuss15a
		name:Dicke Nuss
		desc:<.> Beim Klicken des Insektes bekommst du <b>3</b> mal so viel!
		icon:iconsa[6,14]
		req:250000000000 Insekten:earned and UgRINuss15
*UgRINuss16a
		name:Große Nuss
		desc:<.> Beim Klicken des Insektes bekommst du <b>3</b> mal so viel!
		icon:iconsa[6,15]
		req:5000000000000 Insekten:earned and UgRINuss16
*UgRINuss17a
		name:Komische Nuss
		desc:<.> Beim Klicken des Insektes bekommst du <b>3</b> mal so viel!
		icon:iconsa[6,16]
		req:25000000000000 Insekten:earned and UgRINuss17
*UgRINuss18a
		name:Braune Nuss
		desc:<.> Beim Klicken des Insektes bekommst du <b>3</b> mal so viel!
		icon:iconsa[6,17]
		req:50000000000000 Insekten:earned and UgRINuss18
*UgRINuss19a
		name:Helle Nuss
		desc:<.> Beim Klicken des Insektes bekommst du <b>3</b> mal so viel!
		icon:iconsa[6,18]
		req:250000000000000 Insekten:earned and UgRINuss19
*UgRINuss20a
		name:Weise Nuss
		desc:<.> Beim Klicken des Insektes bekommst du <b>3</b> mal so viel!
		icon:iconsa[6,19]
		req:500000000000000 Insekten:earned and UgRINuss20
*UgRINuss21a
		name:Krumme Nuss
		desc:<.> Beim Klicken des Insektes bekommst du <b>3</b> mal so viel!
		icon:iconsa[6,20]
		req:2500000000000000 Insekten:earned and UgRINuss21
		
		


*UgRILegok1a
        name:Lego!
        desc:<.> Beim Klicken des Insektes bekommst du <b>1</b> Insekt dazu!
        icon:iconsa[7,0]
        req:UgRILegok1
*UgRILegok2a
        name:Schnelles Stapeln!
        desc:<.> Beim Klicken des Insektes bekommst du <b>1</b> Insekt dazu!
        icon:iconsa[7,1]
        req:100 Insekt:earned and UgRILegok2
*UgRILegok3a
        name:Gelber Klotz
        desc:<.> Beim Klicken des Insektes bekommst du <b>1</b> Insekt dazu!
        icon:iconsa[7,2]
        req:1000 Insekt:earned and UgRILegok3
*UgRILegok4a
        name:Grüner Stein
        desc:<.> Beim Klicken des Insektes bekommst du <b>1</b> Insekt dazu!
        icon:iconsa[7,3]
        req:10000 Insekt:earned and UgRILegok4
*UgRILegok5a
        name:Viel Klackern!
        desc:<.> Beim Klicken des Insektes bekommst du <b>1</b> Insekt dazu!
        icon:iconsa[7,4]
        req:100000 Insekt:earned and UgRILegok5
*UgRILegok6a
        name:Stapel es!
        desc:<.> Beim Klicken des Insektes bekommst du <b>1</b> Insekt dazu!
        icon:iconsa[7,5]
        req:1000000 Insekt:earned and UgRILegok6

				
		
				
		
//Insekten Upgrades a		
		
		


*UgBIAmeise1a
		name:Ameisenlimbo
		desc:<.> Erhöht die Produktion der Ameisen um <b>10</b> %.
		icon:icons[0,0] icons[3,0]
		req:UgBIAmeise1

*UgBIAmeise2a
		name:Ameisenrama
		desc:<.> Erhöht die Produktion der Ameisen um <b>10</b> %.
		icon:icons[0,0] icons[3,1]
		req:13000 Insekten:earned and UgBIAmeise2

*UgBIAmeise3a
		name:Ameisenstraße
		desc:<.> Erhöht die Produktion der Ameisen um <b>10</b> %.
		icon:icons[0,0] icons[3,2]
		req:1300000 Insekten:earned and UgBIAmeise3

*UgBIAmeise4a
		name:Ameisenbrücke
		desc:<.> Erhöht die Produktion der Ameisen um <b>10</b> %.
		icon:icons[0,0] icons[3,3]
		req:130000000 Insekten:earned and UgBIAmeise4

*UgBIAmeise5a
		name:Ameisenhighway
		desc:<.> Erhöht die Produktion der Ameisen um <b>10</b> %.
		icon:icons[0,0] icons[3,4]
		req:13000000000 Insekten:earned and UgBIAmeise5
		

*UgBIAmeise6a
		name:Ameisenkreuzung
		desc:<.> Erhöht die Produktion der Ameisen um <b>10</b> %.
		icon:icons[0,0] icons[3,5]
		req:1300000000000 Insekten:earned and UgBIAmeise6

*UgBIAmeise7a
		name:Ameisenmonopol
		desc:<.> Erhöht die Produktion der Ameisen um <b>10</b> %.
		icon:icons[0,0] icons[3,6]
		req:130000000000000 Insekten:earned and UgBIAmeise7

*UgBIAmeise8a
		name:Ameisenunterführung
		desc:<.> Erhöht die Produktion der Ameisen um <b>10</b> %.
		icon:icons[0,0] icons[3,7]
		req:13000000000000000 Insekten:earned and UgBIAmeise8

*UgBIAmeise9a
		name:Ameisenboot
		desc:<.> Erhöht die Produktion der Ameisen um <b>10</b> %.
		icon:icons[0,0] icons[3,8]
		req:1300000000000000000 Insekten:earned and UgBIAmeise9

*UgBIAmeise10a
		name:Ameisensalsa
		desc:<.> Erhöht die Produktion der Ameisen um <b>10</b> %.
		icon:icons[0,0] icons[3,9]
		req:130000000000000000000 Insekten:earned and UgBIAmeise10
		

*UgBIAmeise11a
		name:Ameisensalat
		desc:<.> Erhöht die Produktion der Ameisen um <b>10</b> %.
		icon:icons[0,0] icons[3,10]
		req:13000000000000000000000 Insekten:earned and UgBIAmeise11
		

*UgBIAmeise12a
		name:Ameisenkönig
		desc:<.> Erhöht die Produktion der Ameisen um <b>10</b> %.
		icon:icons[0,0] icons[3,11]
		req:1300000000000000000000000 Insekten:earned and UgBIAmeise12
				

*UgBIPAmeise1a
		name:AmeisenPanzer I
		desc:<.> Erhöht die Produktion der Ameisen um <b>10</b> %.
		icon:icons[0,0] icons[4,1]
		req:UgBIPAmeise1
		class:noBackground

*UgBIPAmeise2a
		name:AmeisenPanzer II
		desc:<.> Erhöht die Produktion der Ameisen um <b>10</b> %.
		icon:icons[0,0] icons[4,1]
		req:UgBIPAmeise2
		class:noBackground
	

*UgBIPAmeise3a
		name:AmeisenPanzer III
		desc:<.> Erhöht die Produktion der Ameisen um <b>10</b> %.
		icon:icons[0,0] icons[4,1]
		req:UgBIPAmeise3
		class:noBackground

*UgBIPAmeise4a
		name:AmeisenPanzer IV
		desc:<.> Erhöht die Produktion der Ameisen um <b>10</b> %.
		icon:icons[0,0] icons[4,1]
		req:UgBIPAmeise4
		class:noBackground

*UgBIPAmeise5a
		name:AmeisenPanzer V
		desc:<.> Erhöht die Produktion der Ameisen um <b>10</b> %.
		icon:icons[0,0] icons[4,1]
		req:UgBIPAmeise5
		class:noBackground

*UgBIPAmeise6a
		name:AmeisenPanzer VI
		desc:<.> Erhöht die Produktion der Ameisen um <b>10</b> %.
		icon:icons[0,0] icons[4,1]
		req:UgBIPAmeise6
		class:noBackground

*UgBIPAmeise7a
		name:AmeisenPanzer VII
		desc:<.> Erhöht die Produktion der Ameisen um <b>10</b> %.
		icon:icons[0,0] icons[4,1]
		req:UgBIPAmeise7
		class:noBackground

*UgBIPAmeise8a
		name:AmeisenPanzer VIII
		desc:<.> Erhöht die Produktion der Ameisen um <b>10</b> %.
		icon:icons[0,0] icons[4,1]
		req:UgBIPAmeise8
		class:noBackground

*UgBIPAmeise9a
		name:AmeisenPanzer IX
		desc:<.> Erhöht die Produktion der Ameisen um <b>10</b> %.
		icon:icons[0,0] icons[4,1]
		req:UgBIPAmeise9
		class:noBackground

*UgBIPAmeise10a
		name:AmeisenPanzer X
		desc:<.> Erhöht die Produktion der Ameisen um <b>10</b> %.
		icon:icons[0,0] icons[4,1]
		req:UgBIPAmeise10
		class:noBackground


				
				
			
				
				
				
*UgBITermite1a
		name:Termitenmarsch
		desc:<.> Erhöht die Produktion der Termiten um <b>10</b> %.
		icon:icons[0,1] icons[3,0]
		req:UgBITermite1

*UgBITermite2a
		name:Termitarium
		desc:<.> Erhöht die Produktion der Termiten um <b>10</b> %.
		icon:icons[0,1] icons[3,1]
		req:14000000 Insekten:earned and UgBITermite2

*UgBITermite3a
		name:Termitenkette
		desc:<.> Erhöht die Produktion der Termiten um <b>10</b> %.
		icon:icons[0,1] icons[3,2]
		req:1400000000 Insekten:earned and UgBITermite3

*UgBITermite4a
		name:Termitenpuder
		desc:<.> Erhöht die Produktion der Termiten um <b>10</b> %.
		icon:icons[0,1] icons[3,3]
		req:140000000000 Insekten:earned and UgBITermite4

*UgBITermite5a
		name:Termitenwache
		desc:<.> Erhöht die Produktion der Termiten um <b>10</b> %.
		icon:icons[0,1] icons[3,4]
		req:14000000000000 Insekten:earned and UgBITermite5

*UgBITermite6a
		name:Termitenmarmelade
		desc:<.> Erhöht die Produktion der Termiten um <b>10</b> %.
		icon:icons[0,1] icons[3,5]
		req:1400000000000000 Insekten:earned and UgBITermite6

*UgBITermite7a
		name:Termitenbrot
		desc:<.> Erhöht die Produktion der Termiten um <b>10</b> %.
		icon:icons[0,1] icons[3,6]
		req:140000000000000000 Insekten:earned and UgBITermite7

*UgBITermite8a
		name:Termitenlink
		desc:<.> Erhöht die Produktion der Termiten um <b>10</b> %.
		icon:icons[0,1] icons[3,7]
		req:14000000000000000000 Insekten:earned and UgBITermite8

*UgBITermite9a
		name:Termitendisko
		desc:<.> Erhöht die Produktion der Termiten um <b>10</b> %.
		icon:icons[0,1] icons[3,8]
		req:1400000000000000000000 Insekten:earned and UgBITermite9

*UgBITermite10a
		name:Termitenküche
		desc:<.> Erhöht die Produktion der Termiten um <b>10</b> %.
		icon:icons[0,1] icons[3,9]
		req:140000000000000000000000 Insekten:earned and UgBITermite10

*UgBITermite11a
		name:Termitenwalzer
		desc:<.> Erhöht die Produktion der Termiten um <b>10</b> %.
		icon:icons[0,1] icons[3,10]
		req:14000000000000000000000000 Insekten:earned and UgBITermite11

*UgBITermite12a
		name:Termitenkuscheln
		desc:<.> Erhöht die Produktion der Termiten um <b>10</b> %.
		icon:icons[0,1] icons[3,11]
		req:1400000000000000000000000000 Insekten:earned and UgBITermite12

		

*UgBIPTermite1a
		name:TermitenPanzer I
		desc:<.> Erhöht die Produktion der Termiten um <b>10</b> %.
		icon:icons[0,1] icons[4,1]
		req:UgBIPTermite1
		class:noBackground

*UgBIPTermite2a
		name:TermitenPanzer II
		desc:<.> Erhöht die Produktion der Termiten um <b>10</b> %.
		icon:icons[0,1] icons[4,1]
		req:UgBIPTermite2
		class:noBackground

*UgBIPTermite3a
		name:TermitenPanzer III
		desc:<.> Erhöht die Produktion der Termiten um <b>10</b> %.
		icon:icons[0,1] icons[4,1]
		req:UgBIPTermite3
		class:noBackground

*UgBIPTermite4a
		name:TermitenPanzer IV
		desc:<.> Erhöht die Produktion der Termiten um <b>10</b> %.
		icon:icons[0,1] icons[4,1]
		req:UgBIPTermite4
		class:noBackground

*UgBIPTermite5a
		name:TermitenPanzer V
		desc:<.> Erhöht die Produktion der Termiten um <b>10</b> %.
		icon:icons[0,1] icons[4,1]
		req:UgBIPTermite5
		class:noBackground

*UgBIPTermite6a
		name:TermitenPanzer VI
		desc:<.> Erhöht die Produktion der Termiten um <b>10</b> %.
		icon:icons[0,1] icons[4,1]
		req:UgBIPTermite6
		class:noBackground

*UgBIPTermite7a
		name:TermitenPanzer VII
		desc:<.> Erhöht die Produktion der Termiten um <b>10</b> %.
		icon:icons[0,1] icons[4,1]
		req:UgBIPTermite7
		class:noBackground

*UgBIPTermite8a
		name:TermitenPanzer VIII
		desc:<.> Erhöht die Produktion der Termiten um <b>10</b> %.
		icon:icons[0,1] icons[4,1]
		req:UgBIPTermite8
		class:noBackground

*UgBIPTermite9a
		name:TermitenPanzer IX
		desc:<.> Erhöht die Produktion der Termiten um <b>10</b> %.
		icon:icons[0,1] icons[4,1]
		req:UgBIPTermite9
		class:noBackground

*UgBIPTermite10a
		name:TermitenPanzer X
		desc:<.> Erhöht die Produktion der Termiten um <b>10</b> %.
		icon:icons[0,1] icons[4,1]
		req:UgBIPTermite10
		class:noBackground




*UgBIFliegen1a
		name:Fliegenklatsche
		desc:<.> Erhöht die Produktion der Fliegen um <b>10</b> %.
		icon:icons[0,2] icons[3,0]
		req:UgBIFliegen1

*UgBIFliegen2a
		name:Fliegenrumba
		desc:<.> Erhöht die Produktion der Fliegen um <b>10</b> %.
		icon:icons[0,2] icons[3,1]
		req:1480000 Insekten:earned and UgBIFliegen2


*UgBIFliegen3a
		name:BrummBrummFliege
		desc:<.> Erhöht die Produktion der Fliegen um <b>10</b> %.
		icon:icons[0,2] icons[3,2]
		req:148000000 Insekten:earned and UgBIFliegen3

*UgBIFliegen4a
		name:Fliegenflügel
		desc:<.> Erhöht die Produktion der Fliegen um <b>10</b> %.
		icon:icons[0,2] icons[3,3]
		req:14800000000 Insekten:earned and UgBIFliegen4

*UgBIFliegen5a
		name:Fliegerbrille
		desc:<.> Erhöht die Produktion der Fliegen um <b>10</b> %.
		icon:icons[0,2] icons[3,4]
		req:1480000000000 Insekten:earned and UgBIFliegen5

*UgBIFliegen6a
		name:Fliegeneier
		desc:<.> Erhöht die Produktion der Fliegen um <b>10</b> %.
		icon:icons[0,2] icons[3,5]
		req:148000000000000 Insekten:earned and UgBIFliegen6

*UgBIFliegen7a
		name:Fliegelarven
		desc:<.> Erhöht die Produktion der Fliegen um <b>10</b> %.
		icon:icons[0,2] icons[3,6]
		req:14800000000000000 Insekten:earned and UgBIFliegen7

*UgBIFliegen8a
		name:Fliegengekreisch
		desc:<.> Erhöht die Produktion der Fliegen um <b>10</b> %.
		icon:icons[0,2] icons[3,7]
		req:1480000000000000000 Insekten:earned and UgBIFliegen8

*UgBIFliegen9a
		name:Fliegenpaarung
		desc:<.> Erhöht die Produktion der Fliegen um <b>10</b> %.
		icon:icons[0,2] icons[3,8]
		req:148000000000000000000 Insekten:earned and UgBIFliegen9

*UgBIFliegen10a
		name:Fliege in der Suppe
		desc:<.> Erhöht die Produktion der Fliegen um <b>10</b> %.
		icon:icons[0,2] icons[3,9]
		req:14800000000000000000000 Insekten:earned and UgBIFliegen10

*UgBIFliegen11a
		name:Fliegenwein
		desc:<.> Erhöht die Produktion der Fliegen um <b>10</b> %.
		icon:icons[0,2] icons[3,10]
		req:1480000000000000000000000 Insekten:earned and UgBIFliegen11

*UgBIFliegen12a
		name:Fliegenragou
		desc:<.> Erhöht die Produktion der Fliegen um <b>10</b> %.
		icon:icons[0,2] icons[3,11]
		req:148000000000000000000000000 Insekten:earned and UgBIFliegen12
				
	





*UgBIPFliege1a
		name:FliegenPanzer I
		desc:<.> Erhöht die Produktion der Fliegen um <b>10</b> %.
		icon:icons[0,2] icons[4,1]
		req:UgBIPFliege1
		class:noBackground

*UgBIPFliege2a
		name:FliegenPanzer II
		desc:<.> Erhöht die Produktion der Fliegen um <b>10</b> %.
		icon:icons[0,2] icons[4,1]
		req:UgBIPFliege2
		class:noBackground

*UgBIPFliege3a
		name:FliegenPanzer III
		desc:<.> Erhöht die Produktion der Fliegen um <b>10</b> %.
		icon:icons[0,2] icons[4,1]
		req:UgBIPFliege3
		class:noBackground

*UgBIPFliege4a
		name:FliegenPanzer IV
		desc:<.> Erhöht die Produktion der Fliegen um <b>10</b> %.
		icon:icons[0,2] icons[4,1]
		req:UgBIPFliege4
		class:noBackground

*UgBIPFliege5a
		name:FliegenPanzer V
		desc:<.> Erhöht die Produktion der Fliegen um <b>10</b> %.
		icon:icons[0,2] icons[4,1]
		req:UgBIPFliege5
		class:noBackground

*UgBIPFliege6a
		name:FliegenPanzer VI
		desc:<.> Erhöht die Produktion der Fliegen um <b>10</b> %.
		icon:icons[0,2] icons[4,1]
		req:UgBIPFliege6
		class:noBackground

*UgBIPFliege7a
		name:FliegenPanzer VII
		desc:<.> Erhöht die Produktion der Fliegen um <b>10</b> %.
		icon:icons[0,2] icons[4,1]
		req:UgBIPFliege7
		class:noBackground

*UgBIPFliege8a
		name:FliegenPanzer VIII
		desc:<.> Erhöht die Produktion der Fliegen um <b>10</b> %.
		icon:icons[0,2] icons[4,1]
		req:UgBIPFliege8
		class:noBackground

*UgBIPFliege9a
		name:FliegenPanzer IX
		desc:<.> Erhöht die Produktion der Fliegen um <b>10</b> %.
		icon:icons[0,2] icons[4,1]
		req:UgBIPFliege9
		class:noBackground

*UgBIPFliege10a
		name:FliegenPanzer X
		desc:<.> Erhöht die Produktion der Fliegen um <b>10</b> %.
		icon:icons[0,2] icons[4,1]
		req:UgBIPFliege10
		class:noBackground



*UgBIKaefer1a
		name:Käfersummen
		desc:<.> Erhöht die Produktion der Käfer um <b>10</b> %.
		icon:icons[0,3] icons[3,0]
		req:UgBIKaefer1

*UgBIKaefer2a
		name:Käferitis
		desc:<.> Erhöht die Produktion der Käfer um <b>10</b> %.
		icon:icons[0,3] icons[3,1]
		req:16800000 Insekten:earned and UgBIKaefer2

*UgBIKaefer3a
		name:Käferlolli
		desc:<.> Erhöht die Produktion der Käfer um <b>10</b> %.
		icon:icons[0,3] icons[3,2]
		req:1680000000 Insekten:earned and UgBIKaefer3

*UgBIKaefer4a
		name:Käferkugeln
		desc:<.> Erhöht die Produktion der Käfer um <b>10</b> %.
		icon:icons[0,3] icons[3,3]
		req:168000000000 Insekten:earned and UgBIKaefer4

*UgBIKaefer5a
		name:Käfersammlung
		desc:<.> Erhöht die Produktion der Käfer um <b>10</b> %.
		icon:icons[0,3] icons[3,4]
		req:16800000000000 Insekten:earned and UgBIKaefer5

*UgBIKaefer6a
		name:Käferrumba
		desc:<.> Erhöht die Produktion der Käfer um <b>10</b> %.
		icon:icons[0,3] icons[3,5]
		req:1680000000000000 Insekten:earned and UgBIKaefer6

*UgBIKaefer7a
		name:Käferhotel
		desc:<.> Erhöht die Produktion der Käfer um <b>10</b> %.
		icon:icons[0,3] icons[3,6]
		req:168000000000000000 Insekten:earned and UgBIKaefer7

*UgBIKaefer8a
		name:Käferhuddel
		desc:<.> Erhöht die Produktion der Käfer um <b>10</b> %.
		icon:icons[0,3] icons[3,7]
		req:16800000000000000000 Insekten:earned and UgBIKaefer8

*UgBIKaefer9a
		name:Käferpolka
		desc:<.> Erhöht die Produktion der Käfer um <b>10</b> %.
		icon:icons[0,3] icons[3,8]
		req:1680000000000000000000 Insekten:earned and UgBIKaefer9

*UgBIKaefer10a
		name:Käferkäse
		desc:<.> Erhöht die Produktion der Käfer um <b>10</b> %.
		icon:icons[0,3] icons[3,9]
		req:168000000000000000000000 Insekten:earned and UgBIKaefer10

*UgBIKaefer11a
		name:Käferbrunch
		desc:<.> Erhöht die Produktion der Käfer um <b>10</b> %.
		icon:icons[0,3] icons[3,10]
		req:16800000000000000000000000 Insekten:earned and UgBIKaefer11

*UgBIKaefer12a
		name:Käfergarten
		desc:<.> Erhöht die Produktion der Käfer um <b>10</b> %.
		icon:icons[0,3] icons[3,11]
		req:1680000000000000000000000000 Insekten:earned and UgBIKaefer12
	




*UgBIPKaefer1a
		name:KäferPanzer I
		desc:<.> Erhöht die Produktion der Käfer um <b>10</b> %.
		icon:icons[0,3] icons[4,1]
		req:UgBIPKaefer1
		class:noBackground

*UgBIPKaefer2a
		name:KäferPanzer II
		desc:<.> Erhöht die Produktion der Käfer um <b>10</b> %.
		icon:icons[0,3] icons[4,1]
		req:UgBIPKaefer2
		class:noBackground

*UgBIPKaefer3a
		name:KäferPanzer III
		desc:<.> Erhöht die Produktion der Käfer um <b>10</b> %.
		icon:icons[0,3] icons[4,1]
		req:UgBIPKaefer3
		class:noBackground

*UgBIPKaefer4a
		name:KäferPanzer IV
		desc:<.> Erhöht die Produktion der Käfer um <b>10</b> %.
		icon:icons[0,3] icons[4,1]
		req:UgBIPKaefer4
		class:noBackground

*UgBIPKaefer5a
		name:KäferPanzer V
		desc:<.> Erhöht die Produktion der Käfer um <b>10</b> %.
		icon:icons[0,3] icons[4,1]
		req:UgBIPKaefer5
		class:noBackground

*UgBIPKaefer6a
		name:KäferPanzer VI
		desc:<.> Erhöht die Produktion der Käfer um <b>10</b> %.
		icon:icons[0,3] icons[4,1]
		req:UgBIPKaefer6
		class:noBackground

*UgBIPKaefer7a
		name:KäferPanzer VII
		desc:<.> Erhöht die Produktion der Käfer um <b>10</b> %.
		icon:icons[0,3] icons[4,1]
		req:UgBIPKaefer7
		class:noBackground

*UgBIPKaefer8a
		name:KäferPanzer VIII
		desc:<.> Erhöht die Produktion der Käfer um <b>10</b> %.
		icon:icons[0,3] icons[4,1]
		req:UgBIPKaefer8
		class:noBackground

*UgBIPKaefer9a
		name:KäferPanzer IX
		desc:<.> Erhöht die Produktion der Käfer um <b>10</b> %.
		icon:icons[0,3] icons[4,1]
		req:UgBIPKaefer9
		class:noBackground

*UgBIPKaefer10a
		name:KäferPanzer X
		desc:<.> Erhöht die Produktion der Käfer um <b>10</b> %.
		icon:icons[0,3] icons[4,1]
		req:UgBIPKaefer10
		class:noBackground





	

	
	
*UgBIBiene1a
		name:Sumsebiene
		desc:<.> Erhöht die Produktion der Bienen um <b>10</b> %.
		icon:icons[0,4] icons[3,0]
		req:UgBIBiene1

*UgBIBiene2a
		name:Bienengelb
		desc:<.> Erhöht die Produktion der Bienen um <b>10</b> %.
		icon:icons[0,4] icons[3,1]
		req:1790000000 Insekten:earned and UgBIBiene2

*UgBIBiene3a
		name:Bienentreffen
		desc:<.> Erhöht die Produktion der Bienen um <b>10</b> %.
		icon:icons[0,4] icons[3,2]
		req:179000000000 Insekten:earned and UgBIBiene3

*UgBIBiene4a
		name:Bienensirup
		desc:<.> Erhöht die Produktion der Bienen um <b>10</b> %.
		icon:icons[0,4] icons[3,3]
		req:17900000000000 Insekten:earned and UgBIBiene4

*UgBIBiene5a
		name:Bienenchachacha
		desc:<.> Erhöht die Produktion der Bienen um <b>10</b> %.
		icon:icons[0,4] icons[3,4]
		req:1790000000000000 Insekten:earned and UgBIBiene5

*UgBIBiene6a
		name:Bienemeeting
		desc:<.> Erhöht die Produktion der Bienen um <b>10</b> %.
		icon:icons[0,4] icons[3,5]
		req:179000000000000000 Insekten:earned and UgBIBiene6

*UgBIBiene7a
		name:Bienenstamm
		desc:<.> Erhöht die Produktion der Bienen um <b>10</b> %.
		icon:icons[0,4] icons[3,6]
		req:17900000000000000000 Insekten:earned and UgBIBiene7

*UgBIBiene8a
		name:Bienendorf
		desc:<.> Erhöht die Produktion der Bienen um <b>10</b> %.
		icon:icons[0,4] icons[3,7]
		req:1790000000000000000000 Insekten:earned and UgBIBiene8

*UgBIBiene9a
		name:Bienenstadt
		desc:<.> Erhöht die Produktion der Bienen um <b>10</b> %.
		icon:icons[0,4] icons[3,8]
		req:179000000000000000000000 Insekten:earned and UgBIBiene9

*UgBIBiene10a
		name:Bienenmonopol
		desc:<.> Erhöht die Produktion der Bienen um <b>10</b> %.
		icon:icons[0,4] icons[3,9]
		req:17900000000000000000000000 Insekten:earned and UgBIBiene10

*UgBIBiene11a
		name:Bienenrisiko
		desc:<.> Erhöht die Produktion der Bienen um <b>10</b> %.
		icon:icons[0,4] icons[3,10]
		req:1790000000000000000000000000 Insekten:earned and UgBIBiene11

*UgBIBiene12a
		name:Maya
		desc:<.> Erhöht die Produktion der Bienen um <b>10</b> %.
		icon:icons[0,4] icons[3,11]
		req:179000000000000000000000000000 Insekten:earned and UgBIBiene12


*UgBIPBiene1a
		name:BienenPanzer I
		desc:<.> Erhöht die Produktion der Bienen um <b>10</b> %.
		icon:icons[0,4] icons[4,1]
		req:UgBIPBiene1
		class:noBackground

*UgBIPBiene2a
		name:BienenPanzer II
		desc:<.> Erhöht die Produktion der Bienen um <b>10</b> %.
		icon:icons[0,4] icons[4,1]
		req:UgBIPBiene2
		class:noBackground

*UgBIPBiene3a
		name:BienenPanzer III
		desc:<.> Erhöht die Produktion der Bienen um <b>10</b> %.
		icon:icons[0,4] icons[4,1]
		req:UgBIPBiene3
		class:noBackground

*UgBIPBiene4a
		name:BienenPanzer IV
		desc:<.> Erhöht die Produktion der Bienen um <b>10</b> %.
		icon:icons[0,4] icons[4,1]
		req:UgBIPBiene4
		class:noBackground

*UgBIPBiene5a
		name:BienenPanzer V
		desc:<.> Erhöht die Produktion der Bienen um <b>10</b> %.
		icon:icons[0,4] icons[4,1]
		req:UgBIPBiene5
		class:noBackground

*UgBIPBiene6a
		name:BienenPanzer VI
		desc:<.> Erhöht die Produktion der Bienen um <b>10</b> %.
		icon:icons[0,4] icons[4,1]
		req:UgBIPBiene6
		class:noBackground

*UgBIPBiene7a
		name:BienenPanzer VII
		desc:<.> Erhöht die Produktion der Bienen um <b>10</b> %.
		icon:icons[0,4] icons[4,1]
		req:UgBIPBiene7
		class:noBackground

*UgBIPBiene8a
		name:BienenPanzer VIII
		desc:<.> Erhöht die Produktion der Bienen um <b>10</b> %.
		icon:icons[0,4] icons[4,1]
		req:UgBIPBiene8
		class:noBackground

*UgBIPBiene9a
		name:BienenPanzer IX
		desc:<.> Erhöht die Produktion der Bienen um <b>10</b> %.
		icon:icons[0,4] icons[4,1]
		req:UgBIPBiene9
		class:noBackground

*UgBIPBiene10a
		name:BienenPanzer X
		desc:<.> Erhöht die Produktion der Bienen um <b>10</b> %.
		icon:icons[0,4] icons[4,1]
		req:UgBIPBiene10
		class:noBackground



*UgBIRoteAmeise1a
		name:RoteAmeisenSalat
		desc:<.> Erhöht die Produktion der RotenAmeisen um <b>10</b> %.
		icon:icons[0,5] icons[3,0]
		req:UgBIRoteAmeise1

*UgBIRoteAmeise2a
		name:RoteAmeisenStraße
		desc:<.> Erhöht die Produktion der RotenAmeisen um <b>10</b> %.
		icon:icons[0,5] icons[3,1]
		req:19590000000 Insekten:earned and UgBIRoteAmeise2

*UgBIRoteAmeise3a
		name:RoteAmeisenSpur
		desc:<.> Erhöht die Produktion der RotenAmeisen um <b>10</b> %.
		icon:icons[0,5] icons[3,2]
		req:1959000000000 Insekten:earned and UgBIRoteAmeise3

*UgBIRoteAmeise4a
		name:RoteAmeisenFutter
		desc:<.> Erhöht die Produktion der RotenAmeisen um <b>10</b> %.
		icon:icons[0,5] icons[3,3]
		req:195900000000000 Insekten:earned and UgBIRoteAmeise4

*UgBIRoteAmeise5a
		name:RoteAmeisenGift
		desc:<.> Erhöht die Produktion der RotenAmeisen um <b>10</b> %.
		icon:icons[0,5] icons[3,4]
		req:19590000000000000 Insekten:earned and UgBIRoteAmeise5

*UgBIRoteAmeise6a
		name:RoteAmeisenBrücke
		desc:<.> Erhöht die Produktion der RotenAmeisen um <b>10</b> %.
		icon:icons[0,5] icons[3,5]
		req:1959000000000000000 Insekten:earned and UgBIRoteAmeise6

*UgBIRoteAmeise7a
		name:RoteAmeisenBrüter
		desc:<.> Erhöht die Produktion der RotenAmeisen um <b>10</b> %.
		icon:icons[0,5] icons[3,6]
		req:195900000000000000000 Insekten:earned and UgBIRoteAmeise7

*UgBIRoteAmeise8a
		name:RoteAmeisenPrinzessin
		desc:<.> Erhöht die Produktion der RotenAmeisen um <b>10</b> %.
		icon:icons[0,5] icons[3,7]
		req:19590000000000000000000 Insekten:earned and UgBIRoteAmeise8

*UgBIRoteAmeise9a
		name:RoteAmeisenSoldat
		desc:<.> Erhöht die Produktion der RotenAmeisen um <b>10</b> %.
		icon:icons[0,5] icons[3,8]
		req:1959000000000000000000000 Insekten:earned and UgBIRoteAmeise9

*UgBIRoteAmeise10a
		name:RoteAmeisenArbeiter
		desc:<.> Erhöht die Produktion der RotenAmeisen um <b>10</b> %.
		icon:icons[0,5] icons[3,9]
		req:195900000000000000000000000 Insekten:earned and UgBIRoteAmeise10

*UgBIRoteAmeise11a
		name:RoteAmeisenWache
		desc:<.> Erhöht die Produktion der RotenAmeisen um <b>10</b> %.
		icon:icons[0,5] icons[3,10]
		req:19590000000000000000000000000 Insekten:earned and UgBIRoteAmeise11

*UgBIRoteAmeise12a
		name:Rotes Treiben
		desc:<.> Erhöht die Produktion der RotenAmeisen um <b>10</b> %.
		icon:icons[0,5] icons[3,11]
		req:1959000000000000000000000000000 Insekten:earned and UgBIRoteAmeise12
		
	
		


*UgBIPRoteAmeise1a
		name:RoteAmeisenPanzer I
		desc:<.> Erhöht die Produktion der RotenAmeisen um <b>10</b> %.
		icon:icons[0,5] icons[4,1]
		req:UgBIPRoteAmeise1
		class:noBackground

*UgBIPRoteAmeise2a
		name:RoteAmeisenPanzer II
		desc:<.> Erhöht die Produktion der RotenAmeisen um <b>10</b> %.
		icon:icons[0,5] icons[4,1]
		req:UgBIPRoteAmeise2
		class:noBackground

*UgBIPRoteAmeise3a
		name:RoteAmeisenPanzer III
		desc:<.> Erhöht die Produktion der RotenAmeisen um <b>10</b> %.
		icon:icons[0,5] icons[4,1]
		req:UgBIPRoteAmeise3
		class:noBackground

*UgBIPRoteAmeise4a
		name:RoteAmeisenPanzer IV
		desc:<.> Erhöht die Produktion der RotenAmeisen um <b>10</b> %.
		icon:icons[0,5] icons[4,1]
		req:UgBIPRoteAmeise4
		class:noBackground

*UgBIPRoteAmeise5a
		name:RoteAmeisenPanzer V
		desc:<.> Erhöht die Produktion der RotenAmeisen um <b>10</b> %.
		icon:icons[0,5] icons[4,1]
		req:UgBIPRoteAmeise5
		class:noBackground

*UgBIPRoteAmeise6a
		name:RoteAmeisenPanzer VI
		desc:<.> Erhöht die Produktion der RotenAmeisen um <b>10</b> %.
		icon:icons[0,5] icons[4,1]
		req:UgBIPRoteAmeise6
		class:noBackground

*UgBIPRoteAmeise7a
		name:RoteAmeisenPanzer VII
		desc:<.> Erhöht die Produktion der RotenAmeisen um <b>10</b> %.
		icon:icons[0,5] icons[4,1]
		req:UgBIPRoteAmeise7
		class:noBackground

*UgBIPRoteAmeise8a
		name:RoteAmeisenPanzer VIII
		desc:<.> Erhöht die Produktion der RotenAmeisen um <b>10</b> %.
		icon:icons[0,5] icons[4,1]
		req:UgBIPRoteAmeise8
		class:noBackground

*UgBIPRoteAmeise9a
		name:RoteAmeisenPanzer IX
		desc:<.> Erhöht die Produktion der RotenAmeisen um <b>10</b> %.
		icon:icons[0,5] icons[4,1]
		req:UgBIPRoteAmeise9
		class:noBackground

*UgBIPRoteAmeise10a
		name:RoteAmeisenPanzer X
		desc:<.> Erhöht die Produktion der RotenAmeisen um <b>10</b> %.
		icon:icons[0,5] icons[4,1]
		req:UgBIPRoteAmeise10
		class:noBackground



*UgBIGrosserKaefer1a
		name:BockKäfer
		desc:<.> Erhöht die Produktion der GroßenKäfer um <b>10</b> %.
		icon:icons[0,6] icons[3,0]
		req:UgBIGrosserKaefer1

*UgBIGrosserKaefer2a
		name:SchwarzKäfer
		desc:<.> Erhöht die Produktion der GroßenKäfer um <b>10</b> %.
		icon:icons[0,6] icons[3,1]
		req:279900000000 Insekten:earned and UgBIGrosserKaefer2

*UgBIGrosserKaefer3a
		name:Laufkäfer
		desc:<.> Erhöht die Produktion der GroßenKäfer um <b>10</b> %.
		icon:icons[0,6] icons[3,2]
		req:27990000000000 Insekten:earned and UgBIGrosserKaefer3

*UgBIGrosserKaefer4a
		name:Speckkäfer
		desc:<.> Erhöht die Produktion der GroßenKäfer um <b>10</b> %.
		icon:icons[0,6] icons[3,3]
		req:2799000000000000 Insekten:earned and UgBIGrosserKaefer4

*UgBIGrosserKaefer5a
		name:Brotkäfer
		desc:<.> Erhöht die Produktion der GroßenKäfer um <b>10</b> %.
		icon:icons[0,6] icons[3,4]
		req:279900000000000000 Insekten:earned and UgBIGrosserKaefer5

*UgBIGrosserKaefer6a
		name:Blatthornkäfer
		desc:<.> Erhöht die Produktion der GroßenKäfer um <b>10</b> %.
		icon:icons[0,6] icons[3,5]
		req:27990000000000000000 Insekten:earned and UgBIGrosserKaefer6

*UgBIGrosserKaefer7a
		name:Schnellkäfer
		desc:<.> Erhöht die Produktion der GroßenKäfer um <b>10</b> %.
		icon:icons[0,6] icons[3,6]
		req:2799000000000000000000 Insekten:earned and UgBIGrosserKaefer7

*UgBIGrosserKaefer8a
		name:Ölkäfer
		desc:<.> Erhöht die Produktion der GroßenKäfer um <b>10</b> %.
		icon:icons[0,6] icons[3,7]
		req:279900000000000000000000 Insekten:earned and UgBIGrosserKaefer8

*UgBIGrosserKaefer9a
		name:Flohkäfer
		desc:<.> Erhöht die Produktion der GroßenKäfer um <b>10</b> %.
		icon:icons[0,6] icons[3,8]
		req:27990000000000000000000000 Insekten:earned and UgBIGrosserKaefer9

*UgBIGrosserKaefer10a
		name:Aaskäfer
		desc:<.> Erhöht die Produktion der GroßenKäfer um <b>10</b> %.
		icon:icons[0,6] icons[3,9]
		req:2799000000000000000000000000 Insekten:earned and UgBIGrosserKaefer10

*UgBIGrosserKaefer11a
		name:Buntkäfer
		desc:<.> Erhöht die Produktion der GroßenKäfer um <b>10</b> %.
		icon:icons[0,6] icons[3,10]
		req:279900000000000000000000000000 Insekten:earned and UgBIGrosserKaefer11

*UgBIGrosserKaefer12a
		name:Scarabaeos
		desc:<.> Erhöht die Produktion der GroßenKäfer um <b>10</b> %.
		icon:icons[0,6] icons[3,11]
		req:27990000000000000000000000000000 Insekten:earned and UgBIGrosserKaefer12


*UgBIPGKaefer1a
		name:GroßerKäferPanzer I
		desc:<.> Erhöht die Produktion der GroßenKäfer um <b>10</b> %.
		icon:icons[0,6] icons[4,1]
		req:UgBIPGrosserKaefer1
		class:noBackground

*UgBIPGKaefer2a
		name:GroßerKäferPanzer II
		desc:<.> Erhöht die Produktion der GroßenKäfer um <b>10</b> %.
		icon:icons[0,6] icons[4,1]
		req:UgBIPGrosserKaefer2
		class:noBackground

*UgBIPGKaefer3a
		name:GroßerKäferPanzer III
		desc:<.> Erhöht die Produktion der GroßenKäfer um <b>10</b> %.
		icon:icons[0,6] icons[4,1]
		req:UgBIPGrosserKaefer3
		class:noBackground

*UgBIPGKaefer4a
		name:GroßerKäferPanzer IV
		desc:<.> Erhöht die Produktion der GroßenKäfer um <b>10</b> %.
		icon:icons[0,6] icons[4,1]
		req:UgBIPGrosserKaefer4
		class:noBackground

*UgBIPGKaefer5a
		name:GroßerKäferPanzer V
		desc:<.> Erhöht die Produktion der GroßenKäfer um <b>10</b> %.
		icon:icons[0,6] icons[4,1]
		req:UgBIPGrosserKaefer5
		class:noBackground

*UgBIPGKaefer6a
		name:GroßerKäferPanzer VI
		desc:<.> Erhöht die Produktion der GroßenKäfer um <b>10</b> %.
		icon:icons[0,6] icons[4,1]
		req:UgBIPGrosserKaefer6
		class:noBackground

*UgBIPGKaefer7a
		name:GroßerKäferPanzer VII
		desc:<.> Erhöht die Produktion der GroßenKäfer um <b>10</b> %.
		icon:icons[0,6] icons[4,1]
		req:UgBIPGrosserKaefer7
		class:noBackground

*UgBIPGKaefer8a
		name:GroßerKäferPanzer VIII
		desc:<.> Erhöht die Produktion der GroßenKäfer um <b>10</b> %.
		icon:icons[0,6] icons[4,1]
		req:UgBIPGrosserKaefer8
		class:noBackground

*UgBIPGKaefer9a
		name:GroßerKäferPanzer IX
		desc:<.> Erhöht die Produktion der GroßenKäfer um <b>10</b> %.
		icon:icons[0,6] icons[4,1]
		req:UgBIPGrosserKaefer9
		class:noBackground

*UgBIPGKaefer10a
		name:GroßerKäferPanzer X
		desc:<.> Erhöht die Produktion der GroßenKäfer um <b>10</b> %.
		icon:icons[0,6] icons[4,1]
		req:UgBIPGrosserKaefer10
		class:noBackground



*UgBISchmetterling1a
		name:Feuerfalter
		desc:<.> Erhöht die Produktion der Schmetterlinge um <b>10</b> %.
		icon:icons[0,7] icons[3,0]
		req:UgBISchmetterling1

*UgBISchmetterling2a
		name:Gabelschwanz
		desc:<.> Erhöht die Produktion der Schmetterlinge um <b>10</b> %.
		icon:icons[0,7] icons[3,1]
		req:4200000000000 Insekten:earned and UgBISchmetterling2

*UgBISchmetterling3a
		name:Mohrenfalter
		desc:<.> Erhöht die Produktion der Schmetterlinge um <b>10</b> %.
		icon:icons[0,7] icons[3,2]
		req:420000000000000 Insekten:earned and UgBISchmetterling3

*UgBISchmetterling4a
		name:Schillerfalter
		desc:<.> Erhöht die Produktion der Schmetterlinge um <b>10</b> %.
		icon:icons[0,7] icons[3,3]
		req:42000000000000000 Insekten:earned and UgBISchmetterling4

*UgBISchmetterling5a
		name:Nachtpfauenauge
		desc:<.> Erhöht die Produktion der Schmetterlinge um <b>10</b> %.
		icon:icons[0,7] icons[3,4]
		req:4200000000000000000 Insekten:earned and UgBISchmetterling5

*UgBISchmetterling6a
		name:Schneckenspinner
		desc:<.> Erhöht die Produktion der Schmetterlinge um <b>10</b> %.
		icon:icons[0,7] icons[3,5]
		req:420000000000000000000 Insekten:earned and UgBISchmetterling6

*UgBISchmetterling7a
		name:Bunteulchen
		desc:<.> Erhöht die Produktion der Schmetterlinge um <b>10</b> %.
		icon:icons[0,7] icons[3,6]
		req:42000000000000000000000 Insekten:earned and UgBISchmetterling7

*UgBISchmetterling8a
		name:Ligustenwickler
		desc:<.> Erhöht die Produktion der Schmetterlinge um <b>10</b> %.
		icon:icons[0,7] icons[3,7]
		req:4200000000000000000000000 Insekten:earned and UgBISchmetterling8

*UgBISchmetterling9a
		name:Dickkopffalter
		desc:<.> Erhöht die Produktion der Schmetterlinge um <b>10</b> %.
		icon:icons[0,7] icons[3,8]
		req:420000000000000000000000000 Insekten:earned and UgBISchmetterling9

*UgBISchmetterling10a
		name:Pantherspanner
		desc:<.> Erhöht die Produktion der Schmetterlinge um <b>10</b> %.
		icon:icons[0,7] icons[3,9]
		req:42000000000000000000000000000 Insekten:earned and UgBISchmetterling10

*UgBISchmetterling11a
		name:Purpurzünsler
		desc:<.> Erhöht die Produktion der Schmetterlinge um <b>10</b> %.
		icon:icons[0,7] icons[3,10]
		req:4200000000000000000000000000000 Insekten:earned and UgBISchmetterling11

*UgBISchmetterling12a
		name:Gelbe Tigermotte
		desc:<.> Erhöht die Produktion der Schmetterlinge um <b>10</b> %.
		icon:icons[0,7] icons[3,11]
		req:420000000000000000000000000000000 Insekten:earned and UgBISchmetterling12



*UgBIPSchmetter1a
		name:SchmetterlingsPanzer I
		desc:<.> Erhöht die Produktion der Schmetterlinge um <b>10</b> %.
		icon:icons[0,7] icons[4,1]
		req:UgBIPSchmetterling1
		class:noBackground

*UgBIPSchmetter2a
		name:SchmetterlingsPanzer II
		desc:<.> Erhöht die Produktion der Schmetterlinge um <b>10</b> %.
		icon:icons[0,7] icons[4,1]
		req:UgBIPSchmetterling2
		class:noBackground

*UgBIPSchmetter3a
		name:SchmetterlingsPanzer III
		desc:<.> Erhöht die Produktion der Schmetterlinge um <b>10</b> %.
		icon:icons[0,7] icons[4,1]
		req:UgBIPSchmetterling3
		class:noBackground

*UgBIPSchmetter4a
		name:SchmetterlingsPanzer IV
		desc:<.> Erhöht die Produktion der Schmetterlinge um <b>10</b> %.
		icon:icons[0,7] icons[4,1]
		req:UgBIPSchmetterling4
		class:noBackground

*UgBIPSchmetter5a
		name:SchmetterlingsPanzer V
		desc:<.> Erhöht die Produktion der Schmetterlinge um <b>10</b> %.
		icon:icons[0,7] icons[4,1]
		req:UgBIPSchmetterling5
		class:noBackground

*UgBIPSchmetter6a
		name:SchmetterlingsPanzer VI
		desc:<.> Erhöht die Produktion der Schmetterlinge um <b>10</b> %.
		icon:icons[0,7] icons[4,1]
		req:UgBIPSchmetterling6
		class:noBackground

*UgBIPSchmetter7a
		name:SchmetterlingsPanzer VII
		desc:<.> Erhöht die Produktion der Schmetterlinge um <b>10</b> %.
		icon:icons[0,7] icons[4,1]
		req:UgBIPSchmetterling7
		class:noBackground

*UgBIPSchmetter8a
		name:SchmetterlingsPanzer VIII
		desc:<.> Erhöht die Produktion der Schmetterlinge um <b>10</b> %.
		icon:icons[0,7] icons[4,1]
		req:UgBIPSchmetterling8
		class:noBackground

*UgBIPSchmetter9a
		name:SchmetterlingsPanzer IX
		desc:<.> Erhöht die Produktion der Schmetterlinge um <b>10</b> %.
		icon:icons[0,7] icons[4,1]
		req:UgBIPSchmetterling9
		class:noBackground

*UgBIPSchmetter10a
		name:SchmetterlingsPanzer X
		desc:<.> Erhöht die Produktion der Schmetterlinge um <b>10</b> %.
		icon:icons[0,7] icons[4,1]
		req:UgBIPSchmetterling10
		class:noBackground


//9

*UgBISchabe1a
		name:Küchenschabe
		desc:<.> Erhöht die Produktion der Schaben um <b>75</b> %.
		icon:icons[15,0]
		req:UgBISchabe1
*UgBISchabe2a
		name:Kakerlake
		desc:<.> Erhöht die Produktion der Schaben um <b>75</b> %.
		icon:icons[15,1]
		req:6500000000000 Insekten:earned and UgBISchabe2
*UgBISchabe3a
		name:Waldschabe 
		desc:<.> Erhöht die Produktion der Schaben um <b>75</b> %.
		icon:icons[15,2]
		req:650000000000000 Insekten:earned and UgBISchabe3
*UgBISchabe4a
		name:Amerikanische Schabe
		desc:<.> Erhöht die Produktion der Schaben um <b>75</b> %.
		icon:icons[15,3]
		req:65000000000000000 Insekten:earned and UgBISchabe4
*UgBISchabe5a
		name:Asiatische Schabe
		desc:<.> Erhöht die Produktion der Schaben um <b>75</b> %.
		icon:icons[15,4]
		req:6500000000000000000 Insekten:earned and UgBISchabe5
*UgBISchabe6a
		name:Australische Schabe
		desc:<.> Erhöht die Produktion der Schaben um <b>75</b> %.
		icon:icons[15,5]
		req:650000000000000000000 Insekten:earned and UgBISchabe6
*UgBISchabe7a
		name:Braunbandschabe
		desc:<.> Erhöht die Produktion der Schaben um <b>75</b> %.
		icon:icons[15,6]
		req:65000000000000000000000 Insekten:earned and UgBISchabe7
*UgBISchabe8a
		name:Orientalische Schabe
		desc:<.> Erhöht die Produktion der Schaben um <b>75</b> %.
		icon:icons[15,7]
		req:6500000000000000000000000 Insekten:earned and UgBISchabe8
*UgBISchabe9a
		name:Spanische Schabe
		desc:<.> Erhöht die Produktion der Schaben um <b>75</b> %.
		icon:icons[15,8]
		req:650000000000000000000000000 Insekten:earned and UgBISchabe9
*UgBISchabe10a
		name:Europäische Schabe
		desc:<.> Erhöht die Produktion der Schaben um <b>75</b> %.
		icon:icons[15,9]
		req:65000000000000000000000000000 Insekten:earned and UgBISchabe10
*UgBISchabe11a
		name:Französiche Schabe
		desc:<.> Erhöht die Produktion der Schaben um <b>75</b> %.
		icon:icons[15,10]
		req:6500000000000000000000000000000 Insekten:earned and UgBISchabe11
*UgBISchabe12a
		name:Russische Schabe
		desc:<.> Erhöht die Produktion der Schaben um <b>75</b> %.
		icon:icons[15,11]
		req:650000000000000000000000000000000 Insekten:earned and UgBISchabe12



*UgBIPSchabe1a
		name:SchabenPanzer I
		desc:<.> Erhöht die Produktion der Schaben um <b>10</b> %.
		icon:icons[0,8] icons[4,1]
		req:UgBIPSchabe1
		class:noBackground

*UgBIPSchabe2a
		name:SchabenPanzer II
		desc:<.> Erhöht die Produktion der Schaben um <b>10</b> %.
		icon:icons[0,8] icons[4,1]
		req:UgBIPSchabe2
		class:noBackground

*UgBIPSchabe3a
		name:SchabenPanzer III
		desc:<.> Erhöht die Produktion der Schaben um <b>10</b> %.
		icon:icons[0,8] icons[4,1]
		req:UgBIPSchabe3
		class:noBackground

*UgBIPSchabe4a
		name:SchabenPanzer IV
		desc:<.> Erhöht die Produktion der Schaben um <b>10</b> %.
		icon:icons[0,8] icons[4,1]
		req:UgBIPSchabe4
		class:noBackground

*UgBIPSchabe5a
		name:SchabenPanzer V
		desc:<.> Erhöht die Produktion der Schaben um <b>10</b> %.
		icon:icons[0,8] icons[4,1]
		req:UgBIPSchabe5
		class:noBackground

*UgBIPSchabe6a
		name:SchabenPanzer VI
		desc:<.> Erhöht die Produktion der Schaben um <b>10</b> %.
		icon:icons[0,8] icons[4,1]
		req:UgBIPSchabe6
		class:noBackground

*UgBIPSchabe7a
		name:SchabenPanzer VII
		desc:<.> Erhöht die Produktion der Schaben um <b>10</b> %.
		icon:icons[0,8] icons[4,1]
		req:UgBIPSchabe7
		class:noBackground

*UgBIPSchabe8a
		name:SchabenPanzer VIII
		desc:<.> Erhöht die Produktion der Schaben um <b>10</b> %.
		icon:icons[0,8] icons[4,1]
		req:UgBIPSchabe8
		class:noBackground

*UgBIPSchabe9a
		name:SchabenPanzer IX
		desc:<.> Erhöht die Produktion der Schaben um <b>10</b> %.
		icon:icons[0,8] icons[4,1]
		req:UgBIPSchabe9
		class:noBackground

*UgBIPSchabe10a
		name:SchabenPanzer X
		desc:<.> Erhöht die Produktion der Schaben um <b>10</b> %.
		icon:icons[0,8] icons[4,1]
		req:UgBIPSchabe10
		class:noBackground		
		

//9

*UgBISkorpion1a
		name:Großer Stachel
		desc:<.> Erhöht die Produktion der Skorpione um <b>75</b> %.
		icon:icons[16,0]
		req:UgBISkorpion1
*UgBISkorpion2a
		name:Dicker Stachel
		desc:<.> Erhöht die Produktion der Skorpione um <b>75</b> %.
		icon:icons[16,1]
		req:6500000000000 Insekten:earned and UgBISkorpion2
*UgBISkorpion3a
		name:Dicker Panzer
		desc:<.> Erhöht die Produktion der Skorpione um <b>75</b> %.
		icon:icons[16,2]
		req:650000000000000 Insekten:earned and UgBISkorpion3
*UgBISkorpion4a
		name:Schnelle Füße
		desc:<.> Erhöht die Produktion der Skorpione um <b>75</b> %.
		icon:icons[16,3]
		req:65000000000000000 Insekten:earned and UgBISkorpion4
*UgBISkorpion5a
		name:Hitze resistent
		desc:<.> Erhöht die Produktion der Skorpione um <b>75</b> %.
		icon:icons[16,4]
		req:6500000000000000000 Insekten:earned and UgBISkorpion5
*UgBISkorpion6a
		name:Kälte resistent
		desc:<.> Erhöht die Produktion der Skorpione um <b>75</b> %.
		icon:icons[16,5]
		req:650000000000000000000 Insekten:earned and UgBISkorpion6
*UgBISkorpion7a
		name:Wüsten Skorpion
		desc:<.> Erhöht die Produktion der Skorpione um <b>75</b> %.
		icon:icons[16,6]
		req:65000000000000000000000 Insekten:earned and UgBISkorpion7
*UgBISkorpion8a
		name:Roter Skorpion
		desc:<.> Erhöht die Produktion der Skorpione um <b>75</b> %.
		icon:icons[16,7]
		req:6500000000000000000000000 Insekten:earned and UgBISkorpion8
*UgBISkorpion9a
		name:Brauner Skorpion
		desc:<.> Erhöht die Produktion der Skorpione um <b>75</b> %.
		icon:icons[16,8]
		req:650000000000000000000000000 Insekten:earned and UgBISkorpion9
*UgBISkorpion10a
		name:Kurze Füße
		desc:<.> Erhöht die Produktion der Skorpione um <b>75</b> %.
		icon:icons[16,9]
		req:65000000000000000000000000000 Insekten:earned and UgBISkorpion10
*UgBISkorpion11a
		name:Langer Stachel
		desc:<.> Erhöht die Produktion der Skorpione um <b>75</b> %.
		icon:icons[16,10]
		req:6500000000000000000000000000000 Insekten:earned and UgBISkorpion11
*UgBISkorpion12a
		name:Amerikanischer Skorpion
		desc:<.> Erhöht die Produktion der Skorpione um <b>75</b> %.
		icon:icons[16,11]
		req:650000000000000000000000000000000 Insekten:earned and UgBISkorpion12



*UgBIPSkorpion1a
		name:SkorpionPanzer I
		desc:<.> Erhöht die Produktion der Skorpione um <b>10</b> %.
		icon:icons[0,9] icons[4,1]
		req:UgBIPSkorpion1
		class:noBackground

*UgBIPSkorpion2a
		name:SkorpionPanzer II
		desc:<.> Erhöht die Produktion der Skorpione um <b>10</b> %.
		icon:icons[0,9] icons[4,1]
		req:UgBIPSkorpion2
		class:noBackground

*UgBIPSkorpion3a
		name:SkorpionPanzer III
		desc:<.> Erhöht die Produktion der Skorpione um <b>10</b> %.
		icon:icons[0,9] icons[4,1]
		req:UgBIPSkorpion3
		class:noBackground

*UgBIPSkorpion4a
		name:SkorpionPanzer IV
		desc:<.> Erhöht die Produktion der Skorpione um <b>10</b> %.
		icon:icons[0,9] icons[4,1]
		req:UgBIPSkorpion4
		class:noBackground

*UgBIPSkorpion5a
		name:SkorpionPanzer V
		desc:<.> Erhöht die Produktion der Skorpione um <b>10</b> %.
		icon:icons[0,9] icons[4,1]
		req:UgBIPSkorpion5
		class:noBackground

*UgBIPSkorpion6a
		name:SkorpionPanzer VI
		desc:<.> Erhöht die Produktion der Skorpione um <b>10</b> %.
		icon:icons[0,9] icons[4,1]
		req:UgBIPSkorpion6
		class:noBackground

*UgBIPSkorpion7a
		name:SkorpionPanzer VII
		desc:<.> Erhöht die Produktion der Skorpione um <b>10</b> %.
		icon:icons[0,9] icons[4,1]
		req:UgBIPSkorpion7
		class:noBackground

*UgBIPSkorpion8a
		name:SkorpionPanzer VIII
		desc:<.> Erhöht die Produktion der Skorpione um <b>10</b> %.
		icon:icons[0,9] icons[4,1]
		req:UgBIPSkorpion8
		class:noBackground

*UgBIPSkorpion9a
		name:SkorpionPanzer IX
		desc:<.> Erhöht die Produktion der Skorpione um <b>10</b> %.
		icon:icons[0,9] icons[4,1]
		req:UgBIPSkorpion9
		class:noBackground

*UgBIPSkorpion10a
		name:SkorpionPanzer X
		desc:<.> Erhöht die Produktion der Skorpione um <b>10</b> %.
		icon:icons[0,9] icons[4,1]
		req:UgBIPSkorpion10
		class:noBackground		
		
	
//10

*UgBIMoskito1a
		name:Moskitole
		desc:<.> Erhöht die Produktion der Moskitos um <b>75</b> %.
		icon:icons[17,0]
		req:UgBIMoskito1
*UgBIMoskito2a
		name:Nachtflügler
		desc:<.> Erhöht die Produktion der Moskitos um <b>75</b> %.
		icon:icons[17,1]
		req:1270000000000000 Insekten:earned and UgBIMoskito2
*UgBIMoskito3a
		name:Vampier
		desc:<.> Erhöht die Produktion der Moskitos um <b>75</b> %.
		icon:icons[17,2]
		req:127000000000000000 Insekten:earned and UgBIMoskito3
*UgBIMoskito4a
		name:Blutsauger
		desc:<.> Erhöht die Produktion der Moskitos um <b>75</b> %.
		icon:icons[17,3]
		req:12700000000000000000 Insekten:earned and UgBIMoskito4
*UgBIMoskito5a
		name:Weite Flügel
		desc:<.> Erhöht die Produktion der Moskitos um <b>75</b> %.
		icon:icons[17,4]
		req:1270000000000000000000 Insekten:earned and UgBIMoskito5
*UgBIMoskito6a
		name:Schöne Flügel
		desc:<.> Erhöht die Produktion der Moskitos um <b>75</b> %.
		icon:icons[17,5]
		req:127000000000000000000000 Insekten:earned and UgBIMoskito6
*UgBIMoskito7a
		name:Lange Flügel
		desc:<.> Erhöht die Produktion der Moskitos um <b>75</b> %.
		icon:icons[17,6]
		req:12700000000000000000000000 Insekten:earned and UgBIMoskito7
*UgBIMoskito8a
		name:Kurzer Stachel
		desc:<.> Erhöht die Produktion der Moskitos um <b>75</b> %.
		icon:icons[17,7]
		req:1270000000000000000000000000 Insekten:earned and UgBIMoskito8
*UgBIMoskito9a
		name:Langer Stachel
		desc:<.> Erhöht die Produktion der Moskitos um <b>75</b> %.
		icon:icons[17,8]
		req:127000000000000000000000000000 Insekten:earned and UgBIMoskito9
*UgBIMoskito10a
		name:Dicker Stachel
		desc:<.> Erhöht die Produktion der Moskitos um <b>75</b> %.
		icon:icons[17,9]
		req:12700000000000000000000000000000 Insekten:earned and UgBIMoskito10
*UgBIMoskito11a
		name:Dünner Stachel
		desc:<.> Erhöht die Produktion der Moskitos um <b>75</b> %.
		icon:icons[17,10]
		req:1270000000000000000000000000000000 Insekten:earned and UgBIMoskito11
*UgBIMoskito12a
		name:Großer Mücken Stachel
		desc:<.> Erhöht die Produktion der Moskitos um <b>75</b> %.
		icon:icons[17,11]
		req:127000000000000000000000000000000000 Insekten:earned and UgBIMoskito12



//11



*UgBIPMoskito1a
		name:MoskitoPanzer I
		desc:<.> Erhöht die Produktion der Moskitos um <b>10</b> %.
		icon:icons[0,10] icons[4,1]
		req:UgBIPMoskito1
		class:noBackground
*UgBIPMoskito2a
		name:MoskitoPanzer II
		desc:<.> Erhöht die Produktion der Moskitos um <b>10</b> %.
		icon:icons[0,10] icons[4,1]
		req:UgBIPMoskito2
		class:noBackground
*UgBIPMoskito3a
		name:MoskitoPanzer III
		desc:<.> Erhöht die Produktion der Moskitos um <b>10</b> %.
		icon:icons[0,10] icons[4,1]
		req:UgBIPMoskito3
		class:noBackground
*UgBIPMoskito4a
		name:MoskitoPanzer IV
		desc:<.> Erhöht die Produktion der Moskitos um <b>10</b> %.
		icon:icons[0,10] icons[4,1]
		req:UgBIPMoskito4
		class:noBackground
*UgBIPMoskito5a
		name:MoskitoPanzer V
		desc:<.> Erhöht die Produktion der Moskitos um <b>10</b> %.
		icon:icons[0,10] icons[4,1]
		req:UgBIPMoskito5
		class:noBackground
*UgBIPMoskito6a
		name:MoskitoPanzer VI
		desc:<.> Erhöht die Produktion der Moskitos um <b>10</b> %.
		icon:icons[0,10] icons[4,1]
		req:UgBIPMoskito6
		class:noBackground
*UgBIPMoskito7a
		name:MoskitoPanzer VII
		desc:<.> Erhöht die Produktion der Moskitos um <b>10</b> %.
		icon:icons[0,10] icons[4,1]
		req:UgBIPMoskito7
		class:noBackground
*UgBIPMoskito8a
		name:MoskitoPanzer VIII
		desc:<.> Erhöht die Produktion der Moskitos um <b>10</b> %.
		icon:icons[0,10] icons[4,1]
		req:UgBIPMoskito8
		class:noBackground
*UgBIPMoskito9a
		name:MoskitoPanzer IX
		desc:<.> Erhöht die Produktion der Moskitos um <b>10</b> %.
		icon:icons[0,10] icons[4,1]
		req:UgBIPMoskito9
		class:noBackground
*UgBIPMoskito10a
		name:MoskitoPanzer X
		desc:<.> Erhöht die Produktion der Moskitos um <b>10</b> %.
		icon:icons[0,10] icons[4,1]
		req:UgBIPMoskito10
		class:noBackground		
		
		
// Schaltet insekten frei a----------------------------------------------------		

//2a
*UpgITermitoriuma
	name:Termitorium
	desc:Schaltet Termiten frei.
	icon:icons[0,1] icons[4,0]
	req:UpgITermitorium
	class:noBackground
//3a
*UpgISchmeisfliegea
	name:Schmeisfliege
	desc:Schaltet Fliegen frei.
	icon:icons[0,2] icons[4,0]
	req:UpgISchmeisfliege
	class:noBackground
//4a
*UpgIBuggya
	name:Käferlinge
	desc:Schaltet Käfer frei.
	icon:icons[0,3] icons[4,0]
	req:UpgIBuggy
	class:noBackground
//5a
*UpgIBienenqueena
	name:Bienenkönigin
	desc:Schaltet Bienen frei.
	icon:icons[0,4] icons[4,0]
	req:UpgIBienenqueen
	class:noBackground	
//6a
*UpgIRoteAmeisea
	name:Feuerameise
	desc:Schaltet RoteAmeisen frei.
	icon:icons[0,5] icons[4,0]
	req:UpgIRoteAmeise
	class:noBackground	
//7a		
*UpgIGrosserBuga
	name:Pillendreher
	desc:Schaltet GroßeKäfer frei.
	icon:icons[0,6]
	req:UpgIGrosserBug
	class:noBackground	
//8	a
*UpgISchmetterla
	name:Zitronenfalter
	desc:Schaltet Schmetterlinge frei.
	icon:icons[0,7] icons[4,0]
	req:UpgISchmetterl
	class:noBackground			
//9		a
*UpgISchabea
	name:Kakerlaki
	desc:Schaltet Schabe frei.
	icon:icons[0,8] icons[4,0]
	req:UpgISchabe
	class:noBackground	
//10a
*UpgISkoriona
	name:Sultan Sting
	desc:Schaltet Skorpion frei.
	icon:icons[0,9] icons[4,0]
	req:UpgISkorion
	class:noBackground	
//11a
*UpgIMoskitoa
	name:Stechmücke
	desc:Schaltet Moskitos frei.
	icon:icons[0,10] icons[4,0]
	req:UpgIMoskito
	class:noBackground	
//12a
*UpgIWillia
	name:WilliWilli
	desc:Schaltet GroßeKäfer frei.
	icon:icons[0,11] icons[4,0]
	req:UpgIWilli
	class:noBackground	
//13a
*UpgILibellea
	name:Urlibelle
	desc:Schaltet Libellen frei.
	icon:icons[0,12] icons[4,0]
	req:UpgILibelle
	class:noBackground	
//14a
*UpgIGluehwurma
	name:Poleuchter
	desc:Schaltet Glühwürmchen frei.
	icon:icons[0,13] icons[4,0]
	req:UpgIGluehwurm
	class:noBackground	
//15a
*UpgIMistrollera
	name:Mistkäfer
	desc:Schaltet Mistroller frei.
	icon:icons[0,14] icons[4,0]
	req:UpgIMistroller
	class:noBackground	
//16a
*UpgINachtfaltera
	name:Flattermann
	desc:Schaltet Nachtfalter frei.
	icon:icons[0,15] icons[4,0]
	req:UpgINachtfalter
	class:noBackground			





//BauMaterial Upgrades a ------------------------------------------------




//Upgrades Ressource Baumaterial	a
		

		
		
*UgRBKiesel1a
		name:Dacit
		desc:<.> Erhöht die Produktion von Baumaterial um <b>1</b> %.
		icon:iconsa[2,0]
		req:UgRBKiesel1
*UgRBKiesel2a
		name:Hornstein
		desc:<.> Erhöht die Produktion von Baumaterial um <b>1</b> %.
		icon:iconsa[2,1]
		req:250000 BauMaterial:earned and UgRBKiesel2
*UgRBKiesel3a
		name:Aplit
		desc:<.> Erhöht die Produktion von Baumaterial um <b>1</b> %.
		icon:iconsa[2,2]
		req:500000 BauMaterial:earned and UgRBKiesel3
*UgRBKiesel4a
		name:Eklogit
		desc:<.> Erhöht die Produktion von Baumaterial um <b>1</b> %.
		icon:iconsa[2,3]
		req:2500000 BauMaterial:earned and UgRBKiesel4
*UgRBKiesel5a
		name:Essexit
		desc:<.> Erhöht die Produktion von Baumaterial um <b>1</b> %.
		icon:iconsa[2,4]
		req:5000000 BauMaterial:earned and UgRBKiesel5
*UgRBKiesel6a
		name:Felsit
		desc:<.> Erhöht die Produktion von Baumaterial um <b>1</b> %.
		icon:iconsa[2,5]
		req:25000000 BauMaterial:earned and UgRBKiesel6
*UgRBKiesel7a
		name:Arkose
		desc:<.> Erhöht die Produktion von Baumaterial um <b>1</b> %.
		icon:iconsa[2,6]
		req:50000000 BauMaterial:earned and UgRBKiesel7
*UgRBKiesel8a
		name:Jumillit
		desc:<.> Erhöht die Produktion von Baumaterial um <b>1</b> %.
		icon:iconsa[2,7]
		req:250000000 BauMaterial:earned and UgRBKiesel8
*UgRBKiesel9a
		name:Lava
		desc:<.> Erhöht die Produktion von Baumaterial um <b>1</b> %.
		icon:iconsa[2,8]
		req:500000000 BauMaterial:earned and UgRBKiesel9
*UgRBKiesel10a
		name:Kaolin
		desc:<.> Erhöht die Produktion von Baumaterial um <b>1</b> %.
		icon:iconsa[2,9]
		req:2500000000 BauMaterial:earned and UgRBKiesel10
*UgRBKiesel11a
		name:Impaktit
		desc:<.> Erhöht die Produktion von Baumaterial um <b>1</b> %.
		icon:iconsa[2,10]
		req:5000000000 BauMaterial:earned and UgRBKiesel11
*UgRBKiesel12a
		name:Löss
		desc:<.> Erhöht die Produktion von Baumaterial um <b>1</b> %.
		icon:iconsa[2,11]
		req:25000000000 BauMaterial:earned and UgRBKiesel12
*UgRBKiesel13a
		name:Kalktuff
		desc:<.> Erhöht die Produktion von Baumaterial um <b>1</b> %.
		icon:iconsa[2,12]
		req:50000000000 BauMaterial:earned and UgRBKiesel13
*UgRBKiesel14a
		name:Weißschiefer
		desc:<.> Erhöht die Produktion von Baumaterial um <b>1</b> %.
		icon:iconsa[2,13]
		req:250000000000 BauMaterial:earned and UgRBKiesel14
*UgRBKiesel15a
		name:Suevit
		desc:<.> Erhöht die Produktion von Baumaterial um <b>1</b> %.
		icon:iconsa[2,14]
		req:UgRBKiesel15
*UgRBKiesel16a
		name:Migmatit
		desc:<.> Erhöht die Produktion von Baumaterial um <b>1</b> %.
		icon:iconsa[2,15]
		req:5000000000000 BauMaterial:earned and UgRBKiesel16
*UgRBKiesel17a
		name:MORB
		desc:<.> Erhöht die Produktion von Baumaterial um <b>1</b> %.
		icon:iconsa[2,16]
		req:25000000000000 BauMaterial:earned and UgRBKiesel17
*UgRBKiesel18a
		name:Tektit
		desc:<.> Erhöht die Produktion von Baumaterial um <b>1</b> %.
		icon:iconsa[2,17]
		req:50000000000000 BauMaterial:earned and UgRBKiesel18
*UgRBKiesel19a
		name:Schiefer
		desc:<.> Erhöht die Produktion von Baumaterial um <b>1</b> %.
		icon:iconsa[2,18]
		req:250000000000000 BauMaterial:earned and UgRBKiesel19
*UgRBKiesel20a
		name:Rogenstein
		desc:<.> Erhöht die Produktion von Baumaterial um <b>1</b> %.
		icon:iconsa[2,19]
		req:500000000000000 BauMaterial:earned and UgRBKiesel20
*UgRBKiesel21a
		name:Mylonit
		desc:<.> Erhöht die Produktion von Baumaterial um <b>1</b> %.
		icon:iconsa[2,20]
		req:2500000000000000 BauMaterial:earned and UgRBKiesel21	
		
		
		
		
*UgRBPilz1a
		name:Fliegenpilz
		desc:<.> Beim Klicken des Baumstammes bekommst du <b>2</b> mal so viel!
		icon:iconsa[3,0]
		req:UgRBPilz1
*UgRBPilz2a
		name:Saftapfel
		desc:<.> Beim Klicken des Baumstammes bekommst du <b>3</b> mal so viel!
		icon:iconsa[3,1]
		req:250000 BauMaterial:earned and UgRBPilz2
*UgRBPilz3a
		name:Aderige Blattflechte
		desc:<.> Beim Klicken des Baumstammes bekommst du <b>3</b> mal so viel!
		icon:iconsa[3,2]
		req:500000 BauMaterial:earned and UgRBPilz3
*UgRBPilz4a
		name:Krustenflechte
		desc:<.> Beim Klicken des Baumstammes bekommst du <b>3</b> mal so viel!
		icon:iconsa[3,3]
		req:2500000 BauMaterial:earned and UgRBPilz4
*UgRBPilz5a
		name:Kugelpilz
		desc:<.> Beim Klicken des Baumstammes bekommst du <b>3</b> mal so viel!
		icon:iconsa[3,4]
		req:5000000 BauMaterial:earned and UgRBPilz5
*UgRBPilz6a
		name:Schildflechte
		desc:<.> Beim Klicken des Baumstammes bekommst du <b>3</b> mal so viel!
		icon:iconsa[3,5]
		req:25000000 BauMaterial:earned and UgRBPilz6
*UgRBPilz7a
		name:Becherflechte
		desc:<.> Beim Klicken des Baumstammes bekommst du <b>3</b> mal so viel!
		icon:iconsa[3,6]
		req:50000000 BauMaterial:earned and UgRBPilz7
*UgRBPilz8a
		name:Binsenkeule
		desc:<.> Beim Klicken des Baumstammes bekommst du <b>3</b> mal so viel!
		icon:iconsa[3,7]
		req:250000000 BauMaterial:earned and UgRBPilz8
*UgRBPilz9a
		name:Trichterling
		desc:<.> Beim Klicken des Baumstammes bekommst du <b>3</b> mal so viel!
		icon:iconsa[3,8]
		req:500000000 BauMaterial:earned and UgRBPilz9
*UgRBPilz10a
		name:Klumpfuß
		desc:<.> Beim Klicken des Baumstammes bekommst du <b>3</b> mal so viel!
		icon:iconsa[3,9]
		req:2500000000 BauMaterial:earned and UgRBPilz10
*UgRBPilz11a
		name:Milchling
		desc:<.> Beim Klicken des Baumstammes bekommst du <b>3</b> mal so viel!
		icon:iconsa[3,10]
		req:5000000000 BauMaterial:earned and UgRBPilz11
*UgRBPilz12a
		name:Rötling
		desc:<.> Beim Klicken des Baumstammes bekommst du <b>3</b> mal so viel!
		icon:iconsa[3,11]
		req:25000000000 BauMaterial:earned and UgRBPilz12
*UgRBPilz13a
		name:Düngerling
		desc:<.> Beim Klicken des Baumstammes bekommst du <b>3</b> mal so viel!
		icon:iconsa[3,12]
		req:50000000000 BauMaterial:earned and UgRBPilz13
*UgRBPilz14a
		name:Tintling
		desc:<.> Beim Klicken des Baumstammes bekommst du <b>3</b> mal so viel!
		icon:iconsa[3,13]
		req:250000000000 BauMaterial:earned and UgRBPilz14
*UgRBPilz15a
		name:Bovist
		desc:<.> Beim Klicken des Baumstammes bekommst du <b>3</b> mal so viel!
		icon:iconsa[3,14]
		req:500000000000 BauMaterial:earned and UgRBPilz15
*UgRBPilz16a
		name:Migmatit
		desc:<.> Beim Klicken des Baumstammes bekommst du <b>3</b> mal so viel!
		icon:iconsa[3,15]
		req:5000000000000 BauMaterial:earned and UgRBPilz16
*UgRBPilz17a
		name:Helmling
		desc:<.> Beim Klicken des Baumstammes bekommst du <b>3</b> mal so viel!
		icon:iconsa[3,16]
		req:25000000000000 BauMaterial:earned and UgRBPilz17
*UgRBPilz18a
		name:Rindenpilz
		desc:<.> Beim Klicken des Baumstammes bekommst du <b>3</b> mal so viel!
		icon:iconsa[3,17]
		req:50000000000000 BauMaterial:earned and UgRBPilz18
*UgRBPilz19a
		name:Rasling
		desc:<.> Beim Klicken des Baumstammes bekommst du <b>3</b> mal so viel!
		icon:iconsa[3,18]
		req:250000000000000 BauMaterial:earned and UgRBPilz19
*UgRBPilz20a
		name:Warzenpilz
		desc:<.> Beim Klicken des Baumstammes bekommst du <b>3</b> mal so viel!
		icon:iconsa[3,19]
		req:500000000000000 BauMaterial:earned and UgRBPilz20
*UgRBPilz21a
		name:Hautkopf
		desc:<.> Beim Klicken des Baumstammes bekommst du <b>3</b> mal so viel!
		icon:iconsa[3,20]
		req:2500000000000000 BauMaterial:earned and UgRBPilz21
*UgRBPilzk1a
        name:Violettmilchling
		desc:<.> Beim Klicken des Baumstammes bekommst du <b>1</b> BauMaterial dazu!
        icon:iconsa[4,0]
        req:UgRBPilzk1
*UgRBPilzk2a
        name:Schiltrötling
		desc:<.> Beim Klicken des Baumstammes bekommst du <b>1</b> BauMaterial dazu!
        icon:iconsa[4,1]
        req:100 BauMaterial:earned and UgRBPilzk2
*UgRBPilzk3a
        name:Ockerbovist
		desc:<.> Beim Klicken des Baumstammes bekommst du <b>1</b> BauMaterial dazu!
        icon:iconsa[4,2]
        req:1000 BauMaterial:earned and UgRBPilzk3
*UgRBPilzk4a
        name:Tugzitterling
		desc:<.> Beim Klicken des Baumstammes bekommst du <b>1</b> BauMaterial dazu!
        icon:iconsa[4,3]
        req:10000 BauMaterial:earned and UgRBPilzk4
*UgRBPilzk5a
        name:Schnallen Hauchpilz
		desc:<.> Beim Klicken des Baumstammes bekommst du <b>1</b> BauMaterial dazu!
        icon:iconsa[4,4]
        req:100000 BauMaterial:earned and UgRBPilzk5
*UgRBPilzk6a
        name:Roßpilz
		desc:<.> Beim Klicken des Baumstammes bekommst du <b>1</b> BauMaterial dazu!
        icon:iconsa[4,5]
        req:1000000 BauMaterial:earned and UgRBPilzk6

		
		
		
//1a			
	

*UgbBGras1a
		name:Zittergras
		desc:<.> Erhöht die Produktion von Gras um <b>10</b> %.
		icon:icons[2,0] icons[3,0]
		req:UgbBGras1
*UgbBGras2a
		name:Knäuelgrass
		desc:<.> Erhöht die Produktion von Gras um <b>10</b> %.
		icon:icons[2,0] icons[3,1]
		req:79000 BauMaterial:earned and UgbBGras2
*UgbBGras3a
		name:Pampasgras
		desc:<.> Erhöht die Produktion von Gras um <b>10</b> %.
		icon:icons[2,0] icons[3,2]
		req:8400000 BauMaterial:earned and UgbBGras3
*UgbBGras4a
		name:Wollgrass
		desc:<.> Erhöht die Produktion von Gras um <b>10</b> %.
		icon:icons[2,0] icons[3,3]
		req:98000000000 BauMaterial:earned and UgbBGras4
*UgbBGras5a
		name:Pfeifengras
		desc:<.> Erhöht die Produktion von Gras um <b>10</b> %.
		icon:icons[2,0] icons[3,4]
		req:9800000000000 BauMaterial:earned and UgbBGras5
*UgbBGras6a
		name:Federborstengrass
		desc:<.> Erhöht die Produktion von Gras um <b>10</b> %.
		icon:icons[2,0] icons[3,5]
		req:980000000000000 BauMaterial:earned and UgbBGras6
*UgbBGras7a
		name:Grünes Gras
		desc:<.> Erhöht die Produktion von Gras um <b>10</b> %.
		icon:icons[2,0] icons[3,6]
		req:98000000000000000 BauMaterial:earned and UgbBGras7
*UgbBGras8a
		name:Rollrasen
		desc:<.> Erhöht die Produktion von Gras um <b>10</b> %.
		icon:icons[2,0] icons[3,7]
		req:9800000000000000000 BauMaterial:earned and UgbBGras8
*UgbBGras9a
		name:Lampenputzergras
		desc:<.> Erhöht die Produktion von Gras um <b>10</b> %.
		icon:icons[2,0] icons[3,8]
		req:980000000000000000000 BauMaterial:earned and UgbBGras9
*UgbBGras10a
		name:Timotheusgras
		desc:<.> Erhöht die Produktion von Gras um <b>10</b> %.
		icon:icons[2,0] icons[3,9]
		req:98000000000000000000000 BauMaterial:earned and UgbBGras10
*UgbBGras11a
		name:Raugras
		desc:<.> Erhöht die Produktion von Gras um <b>10</b> %.
		icon:icons[2,0] icons[3,10]
		req:9800000000000000000000000 BauMaterial:earned and UgbBGras11
*UgbBGras12a
		name:Riesenfedergras
		desc:<.> Erhöht die Produktion von Gras um <b>10</b> %.
		icon:icons[2,0] icons[3,11]
		req:980000000000000000000000000 BauMaterial:earned and UgbBGras12
*UgbBGras13a
		name:Rossschweifgras
		desc:<.> Erhöht die Produktion von Gras um <b>10</b> %.
		icon:icons[2,0] icons[3,12]
		req:98000000000000000000000000000 BauMaterial:earned and UgbBGras13
*UgbBGrasF1a
		name:Zittergräser
		desc:<.> Erhöht die Produktion von Gras um <b>75</b> %.
		icon:icons[2,0] icons[3,0]
		req:UgbBGrasF1
*UgbBGrasF2a
		name:Knäuelgräser
		desc:<.> Erhöht die Produktion von Gras um <b>75</b> %.
		icon:icons[2,0] icons[3,1]
		req:79000 BauMaterial:earned and UgbBGrasF2
*UgbBGrasF3a
		name:Pampasgräser
		desc:<.> Erhöht die Produktion von Gras um <b>75</b> %.
		icon:icons[2,0] icons[3,2]
		req:8400000 BauMaterial:earned and UgbBGrasF3
*UgbBGrasF4a
		name:Wollgräser
		desc:<.> Erhöht die Produktion von Gras um <b>75</b> %.
		icon:icons[2,0] icons[3,3]
		req:98000000000 BauMaterial:earned and UgbBGrasF4
*UgbBGrasF5a
		name:Pfeifengräser
		desc:<.> Erhöht die Produktion von Gras um <b>75</b> %.
		icon:icons[2,0] icons[3,4]
		req:9800000000000 BauMaterial:earned and UgbBGrasF5
*UgbBGrasF6a
		name:Federborstengräser
		desc:<.> Erhöht die Produktion von Gras um <b>75</b> %.
		icon:icons[2,0] icons[3,5]
		req:980000000000000 BauMaterial:earned and UgbBGrasF6
*UgbBGrasF7a
		name:Grüne Gräser
		desc:<.> Erhöht die Produktion von Gras um <b>75</b> %.
		icon:icons[2,0] icons[3,6]
		req:98000000000000000 BauMaterial:earned and UgbBGrasF7
*UgbBGrasF8a
		name:Rollrasenmatten
		desc:<.> Erhöht die Produktion von Gras um <b>75</b> %.
		icon:icons[2,0] icons[3,7]
		req:9800000000000000000 BauMaterial:earned and UgbBGrasF8
*UgbBGrasF9a
		name:Lampenputzergräser
		desc:<.> Erhöht die Produktion von Gras um <b>75</b> %.
		icon:icons[2,0] icons[3,8]
		req:980000000000000000000 BauMaterial:earned and UgbBGrasF9
*UgbBGrasF10a
		name:Timotheusgräser
		desc:<.> Erhöht die Produktion von Gras um <b>75</b> %.
		icon:icons[2,0] icons[3,9]
		req:98000000000000000000000 BauMaterial:earned and UgbBGrasF10
*UgbBGrasF11a
		name:Raugräser
		desc:<.> Erhöht die Produktion von Gras um <b>75</b> %.
		icon:icons[2,0] icons[3,10]
		req:9800000000000000000000000 BauMaterial:earned and UgbBGrasF11
*UgbBGrasF12a
		name:Riesenfedergräser
		desc:<.> Erhöht die Produktion von Gras um <b>75</b> %.
		icon:icons[2,0] icons[3,11]
		req:980000000000000000000000000 BauMaterial:earned and UgbBGrasF12
*UgbBGrasF13a
		name:Rossschweifgräser
		desc:<.> Erhöht die Produktion von Gras um <b>75</b> %.
		icon:icons[2,0] icons[3,12]
		req:98000000000000000000000000000 BauMaterial:earned and UgbBGrasF13







//1	a


*UgbBGrasA1a
		name:Gras Sammler
		desc:<.> Erhöht die Produktion von Gras um <b>75</b> %.
		icon:iconsa[1,0]
		req:UgbBGrasA1
*UgbBGrasA2a
		name:Mehr Sammler
		desc:<.> Erhöht die Produktion von Gras um <b>75</b> %.
		icon:iconsa[1,1]
		req:UgbBGrasA2
*UgbBGrasA3a
		name:Mehr Arbeiter
		desc:<.> Erhöht die Produktion von Gras um <b>75</b> %.
		icon:iconsa[1,2]
		req:UgbBGrasA3
*UgbBGrasA4a
		name:Mehr Träger
		desc:<.> Erhöht die Produktion von Gras um <b>75</b> %.
		icon:iconsa[1,3]
		req:UgbBGrasA4
*UgbBGrasA5a
		name:Logistiker
		desc:<.> Erhöht die Produktion von Gras um <b>75</b> %.
		icon:iconsa[1,4]
		req:UgbBGrasA5
*UgbBGrasA6a
		name:Ingenieure
		desc:<.> Erhöht die Produktion von Gras um <b>75</b> %.
		icon:iconsa[1,5]
		req:UgbBGrasA6
*UgbBGrasA7a
		name:Statiker
		desc:<.> Erhöht die Produktion von Gras um <b>75</b> %.
		icon:iconsa[1,6]
		req:UgbBGrasA7
*UgbBGrasA8a
		name:Bauplaner
		desc:<.> Erhöht die Produktion von Gras um <b>75</b> %.
		icon:iconsa[1,7]
		req:UgbBGrasA8
*UgbBGrasA9a
		name:Transporter
		desc:<.> Erhöht die Produktion von Gras um <b>75</b> %.
		icon:iconsa[1,8]
		req:UgbBGrasA9
*UgbBGrasA10a
		name:Transportunternehmen
		desc:<.> Erhöht die Produktion von Gras um <b>75</b> %.
		icon:iconsa[1,9]
		req:UgbBGrasA10
*UgbBGrasA11a
		name:Minivan
		desc:<.> Erhöht die Produktion von Gras um <b>75</b> %.
		icon:iconsa[1,10]
		req:UgbBGrasA11
*UgbBGrasA12a
		name:LKW
		desc:<.> Erhöht die Produktion von Gras um <b>75</b> %.
		icon:iconsa[1,11]
		req:UgbBGrasA12
*UgbBGrasA13a
		name:Transportesel
		desc:<.> Erhöht die Produktion von Gras um <b>75</b> %.
		icon:iconsa[1,12]
		req:UgbBGrasA13
*UgbBGrasA14a
		name:Lasttier
		desc:<.> Erhöht die Produktion von Gras um <b>75</b> %.
		icon:iconsa[1,12]
		req:UgbBGrasA14
		
//2a			

*UgbBAst1a
		name:Ästling
		desc:<.> Erhöht die Produktion von Ästen um <b>10</b> %.
		icon:icons[2,1] icons[3,0]
		req:UgbBAst1
*UgbBAst2a
		name:Zweig
		desc:<.> Erhöht die Produktion von Ästen um <b>10</b> %.
		icon:icons[2,1] icons[3,1]
		req:1111100 BauMaterial:earned and 45 Ast and UgbBAst2
*UgbBAst3a
		name:Stock
		desc:<.> Erhöht die Produktion von Ästen um <b>10</b> %.
		icon:icons[2,1] icons[3,2]
		req:111110000 BauMaterial:earned and 75 Ast and UgbBAst3
*UgbBAst4a
		name:Stecken
		desc:<.> Erhöht die Produktion von Ästen um <b>10</b> %.
		icon:icons[2,1] icons[3,3]
		req:11111000000 BauMaterial:earned and 100 Ast and UgbBAst4
*UgbBAst5a
		name:Blätterzweig
		desc:<.> Erhöht die Produktion von Ästen um <b>10</b> %.
		icon:icons[2,1] icons[3,4]
		req:1111100000000 BauMaterial:earned and 125 Ast and UgbBAst5
*UgbBAst6a
		name:Dicker Ast
		desc:<.> Erhöht die Produktion von Ästen um <b>10</b> %.
		icon:icons[2,1] icons[3,5]
		req:111110000000000 BauMaterial:earned and 150 Ast and UgbBAst6
*UgbBAst7a
		name:Astgabel
		desc:<.> Erhöht die Produktion von Ästen um <b>10</b> %.
		icon:icons[2,1] icons[3,6]
		req:11111000000000000 BauMaterial:earned and 175 Ast and UgbBAst7
*UgbBAst8a
		name:Astlöffel
		desc:<.> Erhöht die Produktion von Ästen um <b>10</b> %.
		icon:icons[2,1] icons[3,7]
		req:1111100000000000000 BauMaterial:earned and 200 Ast and UgbBAst8
*UgbBAst9a
		name:Astbündel
		desc:<.> Erhöht die Produktion von Ästen um <b>10</b> %.
		icon:icons[2,1] icons[3,8]
		req:111110000000000000000 BauMaterial:earned and 225 Ast and UgbBAst9
*UgbBAst10a
		name:Toter Ast
		desc:<.> Erhöht die Produktion von Ästen um <b>10</b> %.
		icon:icons[2,1] icons[3,9]
		req:11111000000000000000000 BauMaterial:earned and 250 Ast and UgbBAst10
*UgbBAst11a
		name:Morscher Ast
		desc:<.> Erhöht die Produktion von Ästen um <b>10</b> %.
		icon:icons[2,1] icons[3,10]
		req:1111100000000000000000000 BauMaterial:earned and 275 Ast and UgbBAst11
*UgbBAst12a
		name:Astoteles
		desc:<.> Erhöht die Produktion von Ästen um <b>10</b> %.
		icon:icons[2,1] icons[3,11]
		req:111110000000000000000000000 BauMaterial:earned and 300 Ast and UgbBAst12
	
//2a
	
*UgbBAstF1a
		name:Ästlinge
		desc:<.> Erhöht die Produktion von Ästen um <b>75</b> %.
		icon:icons[2,1] icons[3,0]
		req:UgbBAstF1
*UgbBAstF2a
		name:Zweige
		desc:<.> Erhöht die Produktion von Ästen um <b>75</b> %.
		icon:icons[2,1] icons[3,1]
		req:1111100 BauMaterial:earned and 45 Ast and UgbBAstF2
*UgbBAstF3a
		name:Stöcke
		desc:<.> Erhöht die Produktion von Ästen um <b>75</b> %.
		icon:icons[2,1] icons[3,2]
		req:111110000 BauMaterial:earned and 75 Ast and UgbBAstF3
*UgbBAstF4a
		name:Spazierstock
		desc:<.> Erhöht die Produktion von Ästen um <b>75</b> %.
		icon:icons[2,1] icons[3,3]
		req:11111000000 BauMaterial:earned and 100 Ast and UgbBAstF4
*UgbBAstF5a
		name:Blätterzweigling
		desc:<.> Erhöht die Produktion von Ästen um <b>75</b> %.
		icon:icons[2,1] icons[3,4]
		req:1111100000000 BauMaterial:earned and 125 Ast and UgbBAstF5
*UgbBAstF6a
		name:Dicke Äste
		desc:<.> Erhöht die Produktion von Ästen um <b>75</b> %.
		icon:icons[2,1] icons[3,5]
		req:111110000000000 BauMaterial:earned and 150 Ast and UgbBAstF6
*UgbBAstF7a
		name:Astgabelungen
		desc:<.> Erhöht die Produktion von Ästen um <b>75</b> %.
		icon:icons[2,1] icons[3,6]
		req:11111000000000000 BauMaterial:earned and 175 Ast and UgbBAstF7
*UgbBAstF8a
		name:Astlöffele
		desc:<.> Erhöht die Produktion von Ästen um <b>75</b> %.
		icon:icons[2,1] icons[3,7]
		req:1111100000000000000 BauMaterial:earned and 200 Ast and UgbBAstF8
*UgbBAstF9a
		name:Zerbrochener Ast
		desc:<.> Erhöht die Produktion von Ästen um <b>75</b> %.
		icon:icons[2,1] icons[3,8]
		req:111110000000000000000 BauMaterial:earned and 225 Ast and UgbBAstF9
*UgbBAstF10a
		name:Tote Äste
		desc:<.> Erhöht die Produktion von Ästen um <b>75</b> %.
		icon:icons[2,1] icons[3,9]
		req:11111000000000000000000 BauMaterial:earned and 250 Ast and UgbBAstF10
*UgbBAstF11a
		name:Morsche Äste
		desc:<.> Erhöht die Produktion von Ästen um <b>75</b> %.
		icon:icons[2,1] icons[3,10]
		req:1111100000000000000000000 BauMaterial:earned and 275 Ast and UgbBAstF11
*UgbBAstF12a
		name:Astreich
		desc:<.> Erhöht die Produktion von Ästen um <b>75</b> %.
		icon:icons[2,1] icons[3,11]
		req:111110000000000000000000000 BauMaterial:earned and 300 Ast and UgbBAstF12
	
//3a	

*UgbBWurzeln1a
		name:Baumwurzel
		desc:<.> Erhöht die Produktion von Wurzeln um <b>10</b> %.
		icon:icons[2,2] icons[3,0]
		req:UgbBWurzeln1
*UgbBWurzeln2a
		name:Kleine Wurzel
		desc:<.> Erhöht die Produktion von Wurzeln um <b>10</b> %.
		icon:icons[2,2] icons[3,1]
		req:UgbBWurzeln2
*UgbBWurzeln3a
		name:Knollenwurzel
		desc:<.> Erhöht die Produktion von Wurzeln um <b>10</b> %.
		icon:icons[2,2] icons[3,2]
		req:UgbBWurzeln3
*UgbBWurzeln4a
		name:Fadenwurzel
		desc:<.> Erhöht die Produktion von Wurzeln um <b>10</b> %.
		icon:icons[2,2] icons[3,3]
		req:UgbBWurzeln4
*UgbBWurzeln5a
		name:Graswurzel
		desc:<.> Erhöht die Produktion von Wurzeln um <b>10</b> %.
		icon:icons[2,2] icons[3,4]
		req:UgbBWurzeln5
*UgbBWurzeln6a
		name:Unkrautwurzel
		desc:<.> Erhöht die Produktion von Wurzeln um <b>10</b> %.
		icon:icons[2,2] icons[3,5]
		req:UgbBWurzeln6
*UgbBWurzeln7a
		name:Dicke Wurzel
		desc:<.> Erhöht die Produktion von Wurzeln um <b>10</b> %.
		icon:icons[2,2] icons[3,6]
		req:UgbBWurzeln7
*UgbBWurzeln8a
		name:Feine Wurzel
		desc:<.> Erhöht die Produktion von Wurzeln um <b>10</b> %.
		icon:icons[2,2] icons[3,7]
		req:UgbBWurzeln8
*UgbBWurzeln9a
		name:Kaputte Wurzel
		desc:<.> Erhöht die Produktion von Wurzeln um <b>10</b> %.
		icon:icons[2,2] icons[3,8]
		req:UgbBWurzeln9
*UgbBWurzeln10a
		name:Feste Wurzel
		desc:<.> Erhöht die Produktion von Wurzeln um <b>10</b> %.
		icon:icons[2,2] icons[3,9]
		req:UgbBWurzeln10
*UgbBWurzeln11a
		name:Morsche Wurzel
		desc:<.> Erhöht die Produktion von Wurzeln um <b>10</b> %.
		icon:icons[2,2] icons[3,10]
		req:UgbBWurzeln11
*UgbBWurzeln12a
		name:Tiefe Wurzel
		desc:<.> Erhöht die Produktion von Wurzeln um <b>10</b> %.
		icon:icons[2,2] icons[3,11]
		req:UgbBWurzeln12
	
//3a

*UgbBWurzelnF1a
		name:Baumwurzeln
		desc:<.> Erhöht die Produktion von Wurzeln um <b>75</b> %.
		icon:icons[2,2] icons[3,0]
		req:UgbBWurzelnF1
*UgbBWurzelnF2a
		name:Kleine Wurzeln
		desc:<.> Erhöht die Produktion von Wurzeln um <b>75</b> %.
		icon:icons[2,2] icons[3,1]
		req:8960000 BauMaterial:earned and UgbBWurzelnF2
*UgbBWurzelnF3a
		name:Knollenwurzeln
		desc:<.> Erhöht die Produktion von Wurzeln um <b>75</b> %.
		icon:icons[2,2] icons[3,2]
		req:896000000 BauMaterial:earned and UgbBWurzelnF3
*UgbBWurzelnF4a
		name:Fadenwurzeln
		desc:<.> Erhöht die Produktion von Wurzeln um <b>75</b> %.
		icon:icons[2,2] icons[3,3]
		req:89600000000 BauMaterial:earned and UgbBWurzelnF4
*UgbBWurzelnF5a
		name:Graswurzeln
		desc:<.> Erhöht die Produktion von Wurzeln um <b>75</b> %.
		icon:icons[2,2] icons[3,4]
		req:8960000000000 BauMaterial:earned and UgbBWurzelnF5
*UgbBWurzelnF6a
		name:Unkrautwurzeln
		desc:<.> Erhöht die Produktion von Wurzeln um <b>75</b> %.
		icon:icons[2,2] icons[3,5]
		req:896000000000000 BauMaterial:earned and UgbBWurzelnF6
*UgbBWurzelnF7a
		name:Dicke Wurzeln
		desc:<.> Erhöht die Produktion von Wurzeln um <b>75</b> %.
		icon:icons[2,2] icons[3,6]
		req:89600000000000000 BauMaterial:earned and UgbBWurzelnF7
*UgbBWurzelnF8a
		name:Feine Wurzeln
		desc:<.> Erhöht die Produktion von Wurzeln um <b>75</b> %.
		icon:icons[2,2] icons[3,7]
		req:8960000000000000000 BauMaterial:earned and UgbBWurzelnF8
*UgbBWurzelnF9a
		name:Kaputte Wurzeln
		desc:<.> Erhöht die Produktion von Wurzeln um <b>75</b> %.
		icon:icons[2,2] icons[3,8]
		req:896000000000000000000 BauMaterial:earned and UgbBWurzelnF9
*UgbBWurzelnF10a
		name:Feste Wurzeln
		desc:<.> Erhöht die Produktion von Wurzeln um <b>75</b> %.
		icon:icons[2,2] icons[3,9]
		req:89600000000000000000000 BauMaterial:earned and UgbBWurzelnF10
*UgbBWurzelnF11a
		name:Morsche Wurzeln
		desc:<.> Erhöht die Produktion von Wurzeln um <b>75</b> %.
		icon:icons[2,2] icons[3,10]
		req:8960000000000000000000000 BauMaterial:earned and UgbBWurzelnF11
*UgbBWurzelnF12a
		name:Tiefe Wurzeln
		desc:<.> Erhöht die Produktion von Wurzeln um <b>75</b> %.
		icon:icons[2,2] icons[3,11]
		req:896000000000000000000000000 BauMaterial:earned and UgbBWurzelnF12
	
	
//4a	

*UgbBSteine1a
		name:Kieselstein
		desc:<.> Erhöht die Produktion von Steinen um <b>10</b> %.
		icon:icons[2,3] icons[3,0]
		req:UgbBSteine1
*UgbBSteine2a
		name:Backstein
		desc:<.> Erhöht die Produktion von Steinen um <b>10</b> %.
		icon:icons[2,3] icons[3,1]
		req:UgbBSteine2
*UgbBSteine3a
		name:Scharfer Stein
		desc:<.> Erhöht die Produktion von Steinen um <b>10</b> %.
		icon:icons[2,3] icons[3,2]
		req:UgbBSteine3
*UgbBSteine4a
		name:Runder Stein
		desc:<.> Erhöht die Produktion von Steinen um <b>10</b> %.
		icon:icons[2,3] icons[3,3]
		req:UgbBSteine4
*UgbBSteine5a
		name:Glitzerstein
		desc:<.> Erhöht die Produktion von Steinen um <b>10</b> %.
		icon:icons[2,3] icons[3,4]
		req:UgbBSteine5
*UgbBSteine6a
		name:Dreckiger Stein
		desc:<.> Erhöht die Produktion von Steinen um <b>10</b> %.
		icon:icons[2,3] icons[3,5]
		req:UgbBSteine6
*UgbBSteine7a
		name:Glänzender Stein
		desc:<.> Erhöht die Produktion von Steinen um <b>10</b> %.
		icon:icons[2,3] icons[3,6]
		req:UgbBSteine7
*UgbBSteine8a
		name:Großer Stein
		desc:<.> Erhöht die Produktion von Steinen um <b>10</b> %.
		icon:icons[2,3] icons[3,7]
		req:UgbBSteine8
*UgbBSteine9a
		name:Versteckter Stein
		desc:<.> Erhöht die Produktion von Steinen um <b>10</b> %.
		icon:icons[2,3] icons[3,8]
		req:UgbBSteine9
*UgbBSteine10a
		name:Steinhaufen
		desc:<.> Erhöht die Produktion von Steinen um <b>10</b> %.
		icon:icons[2,3] icons[3,9]
		req:UgbBSteine10
*UgbBSteine11a
		name:Steinnest
		desc:<.> Erhöht die Produktion von Steinen um <b>10</b> %.
		icon:icons[2,3] icons[3,10]
		req:UgbBSteine11
*UgbBSteine12a
		name:Steinreich
		desc:<.> Erhöht die Produktion von Steinen um <b>10</b> %.
		icon:icons[2,3] icons[3,11]
		req:UgbBSteine12

*UgbBSteineF1a
		name:Glitzernde Kieselsteine
		desc:<.> Erhöht die Produktion von Steinen um <b>75</b> %.
		icon:icons[2,3] icons[3,0]
		req:UgbBSteineF1
*UgbBSteineF2a
		name:rote Backsteine
		desc:<.> Erhöht die Produktion von Steinen um <b>75</b> %.
		icon:icons[2,3] icons[3,1]
		req:91290000 BauMaterial:earned and UgbBSteineF2
*UgbBSteineF3a
		name:Scharfe Steine
		desc:<.> Erhöht die Produktion von Steinen um <b>75</b> %.
		icon:icons[2,3] icons[3,2]
		req:9129000000 BauMaterial:earned and UgbBSteineF3
*UgbBSteineF4a
		name:Runde Steine
		desc:<.> Erhöht die Produktion von Steinen um <b>75</b> %.
		icon:icons[2,3] icons[3,3]
		req:912900000000 BauMaterial:earned and UgbBSteineF4
*UgbBSteineF5a
		name:Glitzersteine
		desc:<.> Erhöht die Produktion von Steinen um <b>75</b> %.
		icon:icons[2,3] icons[3,4]
		req:91290000000000 BauMaterial:earned and UgbBSteineF5
*UgbBSteineF6a
		name:Dreckige Steine
		desc:<.> Erhöht die Produktion von Steinen um <b>75</b> %.
		icon:icons[2,3] icons[3,5]
		req:9129000000000000 BauMaterial:earned and UgbBSteineF6
*UgbBSteineF7a
		name:Glänzende Steine
		desc:<.> Erhöht die Produktion von Steinen um <b>75</b> %.
		icon:icons[2,3] icons[3,6]
		req:912900000000000000 BauMaterial:earned and UgbBSteineF7
*UgbBSteineF8a
		name:Große Steine
		desc:<.> Erhöht die Produktion von Steinen um <b>75</b> %.
		icon:icons[2,3] icons[3,7]
		req:91290000000000000000 BauMaterial:earned and UgbBSteineF8
*UgbBSteineF9a
		name:Versteckte Steine
		desc:<.> Erhöht die Produktion von Steinen um <b>75</b> %.
		icon:icons[2,3] icons[3,8]
		req:9129000000000000000000 BauMaterial:earned and UgbBSteineF9
*UgbBSteineF10a
		name:Zerbrachener Stein
		desc:<.> Erhöht die Produktion von Steinen um <b>75</b> %.
		icon:icons[2,3] icons[3,9]
		req:912900000000000000000000 BauMaterial:earned and UgbBSteineF10
*UgbBSteineF11a
		name:Steinnester
		desc:<.> Erhöht die Produktion von Steinen um <b>75</b> %.
		icon:icons[2,3] icons[3,10]
		req:91290000000000000000000000 BauMaterial:earned and UgbBSteineF11
*UgbBSteineF12a
		name:Steinigung
		desc:<.> Erhöht die Produktion von Steinen um <b>75</b> %.
		icon:icons[2,3] icons[3,11]
		req:9129000000000000000000000000 BauMaterial:earned and UgbBSteineF12
		
*UgbBDreck1a
		name:Nasser Dreck
		desc:<.> Erhöht die Produktion von Dreck um <b>10</b> %.
		icon:icons[2,4] icons[3,0]
		req:UgbBDreck1
*UgbBDreck2a
		name:Staubiger Dreck
		desc:<.> Erhöht die Produktion von Dreck um <b>10</b> %.
		icon:icons[2,4] icons[3,1]
		req:UgbBDreck2
*UgbBDreck3a
		name:Matschiger Dreck
		desc:<.> Erhöht die Produktion von Dreck um <b>10</b> %.
		icon:icons[2,4] icons[3,2]
		req:UgbBDreck3
*UgbBDreck4a
		name:Klumpiger Dreck
		desc:<.> Erhöht die Produktion von Dreck um <b>10</b> %.
		icon:icons[2,4] icons[3,3]
		req:UgbBDreck4
*UgbBDreck5a
		name:Viel Dreck
		desc:<.> Erhöht die Produktion von Dreck um <b>10</b> %.
		icon:icons[2,4] icons[3,4]
		req:UgbBDreck5
*UgbBDreck6a
		name:Grober Dreck
		desc:<.> Erhöht die Produktion von Dreck um <b>10</b> %.
		icon:icons[2,4] icons[3,5]
		req:UgbBDreck6
*UgbBDreck7a
		name:Feiner Dreck
		desc:<.> Erhöht die Produktion von Dreck um <b>10</b> %.
		icon:icons[2,4] icons[3,6]
		req:UgbBDreck7
*UgbBDreck8a
		name:Drecks Sack
		desc:<.> Erhöht die Produktion von Dreck um <b>10</b> %.
		icon:icons[2,4] icons[3,7]
		req:UgbBDreck8
*UgbBDreck9a
		name:Harter Dreck
		desc:<.> Erhöht die Produktion von Dreck um <b>10</b> %.
		icon:icons[2,4] icons[3,8]
		req:UgbBDreck9
*UgbBDreck10a
		name:Dreckonia
		desc:<.> Erhöht die Produktion von Dreck um <b>10</b> %.
		icon:icons[2,4] icons[3,9]
		req:UgbBDreck10
*UgbBDreck11a
		name:Humus
		desc:<.> Erhöht die Produktion von Dreck um <b>10</b> %.
		icon:icons[2,4] icons[3,10]
		req:UgbBDreck11
*UgbBDreck12a
		name:Lehm
		desc:<.> Erhöht die Produktion von Dreck um <b>10</b> %.
		icon:icons[2,4] icons[3,11]
		req:UgbBDreck12
		
*UgbBDreckF1a
		name:Braunfarbiger Dreck
		desc:<.> Erhöht die Produktion von Dreck um <b>75</b> %.
		icon:icons[2,4] icons[3,0]
		req:UgbBDreckF1
*UgbBDreckF2a
		name:Graufarbiger Dreck
		desc:<.> Erhöht die Produktion von Dreck um <b>75</b> %.
		icon:icons[2,4] icons[3,1]
		req:923000000 BauMaterial:earned and UgbBDreckF2
*UgbBDreckF3a
		name:Hellbraunfarbiger Dreck
		desc:<.> Erhöht die Produktion von Dreck um <b>75</b> %.
		icon:icons[2,4] icons[3,2]
		req:92300000000 BauMaterial:earned and UgbBDreckF3
*UgbBDreckF4a
		name:Klumpen Dreck
		desc:<.> Erhöht die Produktion von Dreck um <b>75</b> %.
		icon:icons[2,4] icons[3,3]
		req:9230000000000 BauMaterial:earned and UgbBDreckF4
*UgbBDreckF5a
		name:Ockerfarbiger Dreck
		desc:<.> Erhöht die Produktion von Dreck um <b>75</b> %.
		icon:icons[2,4] icons[3,4]
		req:923000000000000 BauMaterial:earned and UgbBDreckF5
*UgbBDreckF6a
		name:Gelbfarbiger Dreck
		desc:<.> Erhöht die Produktion von Dreck um <b>75</b> %.
		icon:icons[2,4] icons[3,5]
		req:92300000000000000 BauMaterial:earned and UgbBDreckF6
*UgbBDreckF7a
		name:Orangefarbiger Dreck
		desc:<.> Erhöht die Produktion von Dreck um <b>75</b> %.
		icon:icons[2,4] icons[3,6]
		req:9230000000000000000 BauMaterial:earned and UgbBDreckF7
*UgbBDreckF8a
		name:Beigefarbiger Dreck
		desc:<.> Erhöht die Produktion von Dreck um <b>75</b> %.
		icon:icons[2,4] icons[3,7]
		req:923000000000000000000 BauMaterial:earned and UgbBDreckF8
*UgbBDreckF9a
		name:Camelfarbiger Dreck
		desc:<.> Erhöht die Produktion von Dreck um <b>75</b> %.
		icon:icons[2,4] icons[3,8]
		req:92300000000000000000000 BauMaterial:earned and UgbBDreckF9
*UgbBDreckF10a
		name:Nougatfarbiger Dreck
		desc:<.> Erhöht die Produktion von Dreck um <b>75</b> %.
		icon:icons[2,4] icons[3,9]
		req:9230000000000000000000000 BauMaterial:earned and UgbBDreckF10
*UgbBDreckF11a
		name:Mahagonifarbiger Dreck
		desc:<.> Erhöht die Produktion von Dreck um <b>75</b> %.
		icon:icons[2,4] icons[3,10]
		req:923000000000000000000000000 BauMaterial:earned and UgbBDreckF11
*UgbBDreckF12a
		name:Kupferbraunfarbiger Dreck
		desc:<.> Erhöht die Produktion von Dreck um <b>75</b> %.
		icon:icons[2,4] icons[3,11]
		req:92300000000000000000000000000 BauMaterial:earned and UgbBDreckF12
		
// Erfolge --Achievements-------------------------------------------------------------------------------			
		
Achievements
	*TEMPLATE
		on click:anim glow
		class:noBackground
		on earn:yield 1 Erfolg

// Upgrades haben Achievments

*UHaben1
		name:19!
		desc:Habe 19 Upgrades
		req:19 upgradesII:earned
		icon:iconsb[17,0]
*UHaben2
		name:Verbessern
		desc:Habe 50 Upgrades
		req:50 upgradesII:earned
		icon:iconsb[17,1]
*UHaben3
		name:Abändern
		desc:Habe 100 Upgrades
		req:100 upgradesII:earned
		icon:iconsb[17,2]
*UHaben4
		name:Korrigieren
		desc:Habe 150 Upgrades
		req:150 upgradesII:earned
		icon:iconsb[17,3]
*UHaben5
		name:Reformieren
		desc:Habe 200 Upgrades
		req:200 upgradesII:earned
		icon:iconsb[17,4]
*UHaben6
		name:Ausbauen
		desc:Habe 250 Upgrades
		req:250 upgradesII:earned
		icon:iconsb[17,5]
*UHaben7
		name:Umbauen
		desc:Habe 300 Upgrades
		req:300 upgradesII:earned
		icon:iconsb[17,6]
*UHaben8
		name:Ändern
		desc:Habe 350 Upgrades
		req:350 upgradesII:earned
		icon:iconsb[17,7]
*UHaben9
		name:Umwerfen
		desc:Habe 400 Upgrades
		req:400 upgradesII:earned
		icon:iconsb[17,8]
*UHaben10
		name:Abwandeln
		desc:Habe 450 Upgrades
		req:450 upgradesII:earned
		icon:iconsb[17,9]
*UHaben11
		name:Variieren
		desc:Habe 500 Upgrades
		req:500 upgradesII:earned
		icon:iconsb[17,10]
*UHaben12
		name:Modifizieren
		desc:Habe 550 Upgrades
		req:550 upgradesII:earned
		icon:iconsb[17,11]
*UHaben13
		name:Upgraden
		desc:Habe 600 Upgrades
		req:600 upgradesII:earned
		icon:iconsb[17,12]
*UHaben14
		name:Bessern
		desc:Habe 650 Upgrades
		req:650 upgradesII:earned
		icon:iconsb[17,13]
*UHaben15
		name:Wandeln
		desc:Habe 700 Upgrades
		req:700 upgradesII:earned
		icon:iconsb[17,14]
*UHaben16
		name:Tauschen
		desc:Habe 750 Upgrades
		req:750 upgradesII:earned
		icon:iconsb[17,15]
*UHaben17
		name:Einwechseln
		desc:Habe 800 Upgrades
		req:800 upgradesII:earned
		icon:iconsb[17,16]
*UHaben18
		name:Umsetzen
		desc:Habe 850 Upgrades
		req:850 upgradesII:earned
		icon:iconsb[17,17]
*UHaben19
		name:Auswechseln
		desc:Habe 900 Upgrades
		req:900 upgradesII:earned
		icon:iconsb[17,18]
*UHaben20
		name:Ablösen
		desc:Habe 950 Upgrades
		req:950 upgradesII:earned
		icon:iconsb[17,19]
*UHaben21
		name:Schönen
		desc:Habe 1000 Upgrades
		req:1000 upgradesII:earned
		icon:iconsb[17,20]
		
//klick Achievements

*KIAchiev1
		name:Click it!
		desc:Klick das Insekt ein mal!
		req:1 InsektenButton click
		icon:icons[6,0] icons[5,3]
*KIAchiev2
		name:Klick! Klick! Klick!
		desc:Klick das Insekt 1000 mal!
		req:1000 InsektenButton clicks
		icon:icons[6,0] icons[5,3]
*KIAchiev3
		name:Du hast es!
		desc:Klick das Insekt 1000000 mal!
		req:1000000 InsektenButton clicks
		icon:icons[6,0] icons[5,3]
*KIAchiev4
		name:Klickoman!
		desc:Klick das Insekt 1000000000 mal!
		req:1000000000 InsektenButton clicks
		icon:icons[6,0] icons[5,3]
*KIAchiev5
		name:Klicktastisch!
		desc:Klick das Insekt 1000000000000 mal!
		req:1000000000000 InsektenButton clicks
		icon:icons[6,0] icons[5,3]
*KIAchiev6
		name:Klickoholic!
		desc:Klick das Insekt 1000000000000000 mal!
		req:1000000000000000 InsektenButton clicks
		icon:icons[6,0] icons[5,3]
*KIAchiev7
		name:Klickster!
		desc:Klick das Insekt 1000000000000000000 mal!
		req:1000000000000000000 InsektenButton clicks
		icon:icons[6,0] icons[5,3]
*KIAchiev8
		name:So oft?!
		desc:Klick das Insekt 1000000000000000000000 mal!
		req:1000000000000000000000 InsektenButton clicks
		icon:icons[6,0] icons[5,3]
*KIAchiev9
		name:Klicktastisch!
		desc:Klick das Insekt 1000000000000000000000000 mal!
		req:1000000000000000000000000 InsektenButton clicks
		icon:icons[6,0] icons[5,3]
*KIAchiev10
		name:Klick Imperium!
		desc:Klick das Insekt 1000000000000000000000000000 mal!
		req:1000000000000000000000000000 InsektenButton clicks
		icon:icons[6,0] icons[5,3]
*KIAchiev11
		name:Klickforisch!
		desc:Klick das Insekt 1000000000000000000000000000000 mal!
		req:1000000000000000000000000000000 InsektenButton clicks
		icon:icons[6,0] icons[5,3]
		
*IHAchiev1
		name:Ein Insekt!
		desc:Habe ein Insekt.
		req:1 Insekt:earned
		icon:icons[0,0] icons[5,3]
*IHAchiev2
		name:Ein paar mehr!
		desc:Habe 1000 Insekten.
		req:1000 Insekt:earned
		icon:icons[0,0] icons[5,3]
*IHAchiev3
		name:Es krabbelt überall!
		desc:Habe 1000000 Insekten.
		req:1000000 Insekt:earned
		icon:icons[0,0] icons[5,3]
*IHAchiev4
		name:Mama mag es nicht!
		desc:Habe 1000000000 Insekten.
		req:1000000000 Insekt:earned
		icon:icons[0,0] icons[5,3]
*IHAchiev5
		name:Ich kann sie nicht mehr zählen!
		desc:Habe 1000000000000 Insekten.
		req:1000000000000 Insekt:earned
		icon:icons[0,0] icons[5,3]
*IHAchiev6
		name:Es summt überall!
		desc:Habe 1000000000000000 Insekten.
		req:1000000000000000 Insekt:earned
		icon:icons[0,0] icons[5,3]
*IHAchiev7
		name:Krabbel! Krabbel!
		desc:Habe 1000000000000000000 Insekten.
		req:1000000000000000000 Insekt:earned
		icon:icons[0,0] icons[5,3]
*IHAchiev8
		name:Wo kommen sie nur alle her?!
		desc:Habe 1000000000000000000000 Insekten.
		req:1000000000000000000000 Insekt:earned
		icon:icons[0,0] icons[5,3]
*IHAchiev9
		name:Insektastisch!
		desc:Habe 1000000000000000000000000 Insekten.
		req:1000000000000000000000000 Insekt:earned
		icon:icons[0,0] icons[5,3]
*IHAchiev10
		name:Wie viele Nullen sind das?!
		desc:Habe 1000000000000000000000000000 Insekten.
		req:1000000000000000000000000000 Insekt:earned
		icon:icons[0,0] icons[5,3]
*IHAchiev11
		name:Kannst du sie noch zählen?!
		desc:Habe 1000000000000000000000000000000 Insekten.
		req:1000000000000000000000000000000 Insekt:earned
		icon:icons[0,0] icons[5,3]
*IHAchiev12
		name:Insekten überall!
		desc:Habe 1000000000000000000000000000000000 Insekten.
		req:1000000000000000000000000000000000 Insekt:earned
		icon:icons[0,0] icons[5,3]
*IHAchiev13
		name:Insektenwelt!
		desc:Habe 1000000000000000000000000000000000000 Insekten.
		req:1000000000000000000000000000000000000 Insekt:earned
		icon:icons[0,0] icons[5,3]
		
*LKAchiev1
		name:Geschlüpft!
		desc:Klick die Larve ein mal!
		req:1 LarveButton click
		icon:icons[6,0] icons[5,3]
*LKAchiev2
		name:Du kannst es!
		desc:Klick die Larve 1000 mal!
		req:1000 LarveButton clicks
		icon:icons[6,0] icons[5,3]
*LKAchiev3
		name:Sorge gut für sie!
		desc:Klick die Larve 1000000 mal!
		req:1000000 LarveButton clicks
		icon:icons[6,0] icons[5,3]
*LKAchiev4
		name:Wo ist die Mama?
		desc:Klick die Larve 1000000000 mal!
		req:1000000000 LarveButton clicks
		icon:icons[6,0] icons[5,3]
*LKAchiev5
		name:Eine Puppe!
		desc:Klick die Larve 1000000000000 mal!
		req:1000000000000 LarveButton clicks
		icon:icons[6,0] icons[5,3]
*LKAchiev6
		name:Aus klein wird groß!
		desc:Klick die Larve 1000000000000000 mal!
		req:1000000000000000 LarveButton clicks
		icon:icons[6,0] icons[5,3]
*LKAchiev7
		name:Und eins! Und zwei! Und drei!
		desc:Klick die Larve 1000000000000000000 mal!
		req:1000000000000000000 LarveButton clicks
		icon:icons[6,0] icons[5,3]
*LKAchiev8
		name:GUT gemacht!
		desc:Klick die Larve 1000000000000000000000 mal!
		req:1000000000000000000000 LarveButton clicks
		icon:icons[6,0] icons[5,3]
*LKAchiev9
		name:Massenkrabbeln!
		desc:Klick die Larve 1000000000000000000000000 mal!
		req:1000000000000000000000000 LarveButton clicks
		icon:icons[6,0] icons[5,3]
*LKAchiev10
		name:Krabbeltorium!
		desc:Klick die Larve 1000000000000000000000000000 mal!
		req:1000000000000000000000000000 LarveButton clicks
		icon:icons[6,0] icons[5,3]
*LKAchiev11
		name:Larvenmeister!
		desc:Klick die Larve 1000000000000000000000000000000 mal!
		req:1000000000000000000000000000000 LarveButton clicks
		icon:icons[6,0] icons[5,3]
		
*LHAchiev1
		name:Deine erste Larve!
		desc:Habe eine Larve.
		req:1 Larve:earned
		icon:icons[1,0] icons[5,3]
*LHAchiev2
		name:Pass gut auf sie auf!
		desc:Habe 1000 Larven.
		req:1000 Larven:earned
		icon:icons[1,0] icons[5,3]
*LHAchiev3
		name:Sie brauchen es warm!
		desc:Habe 1000000 Larven.
		req:1000000 Larven:earned
		icon:icons[1,0] icons[5,3]
*LHAchiev4
		name:Hunger haben sie auch!
		desc:Habe 1000000000 Larven.
		req:1000000000 Larven:earned
		icon:icons[1,0] icons[5,3]
*LHAchiev5
		name:Wer kümmert sich um sie?
		desc:Habe 1000000000000 Larven.
		req:1000000000000 Larven:earned
		icon:icons[1,0] icons[5,3]
*LHAchiev6
		name:Sie wollen Gesellschaft!
		desc:Habe 1000000000000000 Larven.
		req:1000000000000000 Larven:earned
		icon:icons[1,0] icons[5,3]
*LHAchiev7
		name:Ganz nah zusammen!
		desc:Habe 1000000000000000000 Larven.
		req:1000000000000000000 Larven:earned
		icon:icons[1,0] icons[5,3]
*LHAchiev8
		name:Sie kuscheln gerne!
		desc:Habe 1000000000000000000000 Larven.
		req:1000000000000000000000 Larven:earned
		icon:icons[1,0] icons[5,3]
*LHAchiev9
		name:Gemeinsam sind sie stark!
		desc:Habe 1000000000000000000000000 Larven.
		req:1000000000000000000000000 Larven:earned
		icon:icons[1,0] icons[5,3]
*LHAchiev10
		name:Welche war die erste?
		desc:Habe 1000000000000000000000000000 Larven.
		req:1000000000000000000000000000 Larven:earned
		icon:icons[1,0] icons[5,3]
*LHAchiev11
		name:Langsam werden es viele!
		desc:Habe 1000000000000000000000000000000 Larven.
		req:1000000000000000000000000000000 Larven:earned
		icon:icons[1,0] icons[5,3]
*LHAchiev12
		name:Und noch ein paar mehr!
		desc:Habe 1000000000000000000000000000000000 Larven.
		req:1000000000000000000000000000000000 Larven:earned
		icon:icons[1,0] icons[5,3]
*LHAchiev13
		name:Larvenstaat!
		desc:Habe 1000000000000000000000000000000000000 Larven.
		req:1000000000000000000000000000000000000 Larven:earned
		icon:icons[1,0] icons[5,3]

*BKAchiev1
		name:Geklickt!
		desc:Klick den Baumstamm ein mal!
		req:1 TreeButton click
		icon:icons[6,0] icons[5,3]
*BKAchiev2
		name:Steinklicker!
		desc:Klick den Baumstamm 1000 mal!
		req:1000 TreeButton clicks
		icon:icons[6,0] icons[5,3]
*BKAchiev3
		name:Astklicker!
		desc:Klick den Baumstamm 1000000 mal!
		req:1000000 TreeButton clicks
		icon:icons[6,0] icons[5,3]
*BKAchiev4
		name:Baumklicker!
		desc:Klick den Baumstamm 1000000000 mal!
		req:1000000000 TreeButton clicks
		icon:icons[6,0] icons[5,3]
*BKAchiev5
		name:Wurzelklicker!
		desc:Klick den Baumstamm 1000000000000 mal!
		req:1000000000000 TreeButton clicks
		icon:icons[6,0] icons[5,3]
*BKAchiev6
		name:Callophanklicker!
		desc:Klick den Baumstamm 1000000000000000 mal!
		req:1000000000000000 TreeButton clicks
		icon:icons[6,0] icons[5,3]
*BKAchiev7
		name:Staubklicker!
		desc:Klick den Baumstamm 1000000000000000000 mal!
		req:1000000000000000000 TreeButton clicks
		icon:icons[6,0] icons[5,3]
*BKAchiev8
		name:Dreckklicker!
		desc:Klick den Baumstamm 1000000000000000000000 mal!
		req:1000000000000000000000 TreeButton clicks
		icon:icons[6,0] icons[5,3]
*BKAchiev9
		name:Blumenklicker!
		desc:Klick den Baumstamm 1000000000000000000000000 mal!
		req:1000000000000000000000000 TreeButton clicks
		icon:icons[6,0] icons[5,3]
*BKAchiev10
		name:Zweigklicker!
		desc:Klick den Baumstamm 1000000000000000000000000000 mal!
		req:1000000000000000000000000000 TreeButton clicks
		icon:icons[6,0] icons[5,3]
*BKAchiev11
		name:Grasklicker!
		desc:Klick den Baumstamm 1000000000000000000000000000000 mal!
		req:1000000000000000000000000000000 TreeButton clicks
		icon:icons[6,0] icons[5,3]
		class:noBackground			
	
*BHAchiev1
		name:Dein erstes BauMaterial!
		desc:Habe eine BauMaterial.
		req:1 BauMaterial:earned
		icon:icons[5,0] icons[5,3]
*BHAchiev2
		name:Holzgrabbler!
		desc:Habe 1000 BauMaterial.
		req:1000 BauMaterial:earned
		icon:icons[5,0] icons[5,3]
*BHAchiev3
		name:Steine Sammler!
		desc:Habe 1000000 BauMaterial.
		req:1000000 BauMaterial:earned
		icon:icons[5,0] icons[5,3]
*BHAchiev4
		name:Holzstapel!
		desc:Habe 1000000000 BauMaterial.
		req:1000000000 BauMaterial:earned
		icon:icons[5,0] icons[5,3]
*BHAchiev5
		name:Dreckhaufen!
		desc:Habe 1000000000000 BauMaterial.
		req:1000000000000 BauMaterial:earned
		icon:icons[5,0] icons[5,3]
*BHAchiev6
		name:Wurzelberg!
		desc:Habe 1000000000000000 BauMaterial.
		req:1000000000000000 BauMaterial:earned
		icon:icons[5,0] icons[5,3]
*BHAchiev7
		name:Zweigbündel!
		desc:Habe 1000000000000000000 BauMaterial.
		req:1000000000000000000 BauMaterial:earned
		icon:icons[5,0] icons[5,3]
*BHAchiev8
		name:Kieselreich!
		desc:Habe 1000000000000000000000 BauMaterial.
		req:1000000000000000000000 BauMaterial:earned
		icon:icons[5,0] icons[5,3]
*BHAchiev9
		name:Federstapel!
		desc:Habe 1000000000000000000000000 BauMaterial.
		req:1000000000000000000000000 BauMaterial:earned
		icon:icons[5,0] icons[5,3]
*BHAchiev10
		name:Daunenkissen!
		desc:Habe 1000000000000000000000000000 BauMaterial.
		req:1000000000000000000000000000 BauMaterial:earned
		icon:icons[5,0] icons[5,3]
*BHAchiev11
		name:Lehmklumpen!
		desc:Habe 1000000000000000000000000000000 BauMaterial.
		req:1000000000000000000000000000000 BauMaterial:earned
		icon:icons[5,0] icons[5,3]
*BHAchiev12
		name:Matsch!
		desc:Habe 1000000000000000000000000000000000 BauMaterial.
		req:1000000000000000000000000000000000 BauMaterial:earned
		icon:icons[5,0] icons[5,3]
*BHAchiev13
		name:Bauhof!
		desc:Habe 1000000000000000000000000000000000000 BauMaterial.
		req:1000000000000000000000000000000000000 BauMaterial:earned
		icon:icons[5,0] icons[5,3]
		

//  BH- Buildings haben   Achievements---------
// Nahrungs buildings

//1

*BHSammler1
		name:Sammelsurium
		desc:Habe eine SammlerAmeise
		req:1 SammlerAmeise
		icon:icons[9,0]
*BHSammler2
		name:Sammelrama
		desc:Habe 19 SammlerAmeisen
		req:19 SammlerAmeise
		icon:icons[9,1]
*BHSammler3
		name:Sammelmeister
		desc:Habe 50 SammlerAmeisen
		req:50 SammlerAmeise
		icon:icons[9,2]
*BHSammler4
		name:Messi
		desc:Habe 100 SammlerAmeisen
		req:100 SammlerAmeise
		icon:icons[9,3]
*BHSammler5
		name:Sammelstunde
		desc:Habe 150 SammlerAmeisen
		req:150 SammlerAmeise
		icon:icons[9,4]
*BHSammler6
		name:Sammeltum
		desc:Habe 200 SammlerAmeisen
		req:200 SammlerAmeise
		icon:icons[9,5]
*BHSammler7
		name:Sammel! Sammel! Sammel!
		desc:Habe 250 SammlerAmeisen
		req:250 SammlerAmeise
		icon:icons[9,6]
*BHSammler8
		name:Sammeltastisch!
		desc:Habe 300 SammlerAmeisen
		req:300 SammlerAmeise
		icon:icons[9,7]
*BHSammler9
		name:Samlung
		desc:Habe 350 SammlerAmeisen
		req:350 SammlerAmeise
		icon:icons[9,8]
*BHSammler10
		name:Sammeltitis
		desc:Habe 400 SammlerAmeisen
		req:400 SammlerAmeise
		icon:icons[9,9]
*BHSammler11
		name:Sammeltits
		desc:Habe 450 SammlerAmeisen
		req:450 SammlerAmeise
		icon:icons[9,10]
*BHSammler12
		name:Horten!
		desc:Habe 500 SammlerAmeisen
		req:500 SammlerAmeise
		icon:icons[9,11]
*BHSammler13
		name:Sichtung
		desc:Habe 550 SammlerAmeisen
		req:550 SammlerAmeise
		icon:icons[9,12]
*BHSammler14
		name:Mitbringsel
		desc:Habe 600 SammlerAmeisen
		req:600 SammlerAmeise
		icon:icons[9,13]
*BHSammler15
		name:Sammelstock
		desc:Habe 650 SammlerAmeisen
		req:650 SammlerAmeise
		icon:icons[9,14]
*BHSammler16
		name:Angel
		desc:Habe 700 SammlerAmeisen
		req:700 SammlerAmeise
		icon:icons[9,15]
*BHSammler17
		name:Rute
		desc:Habe 750 SammlerAmeisen
		req:750 SammlerAmeise
		icon:icons[9,16]
*BHSammler18
		name:Sammlerin
		desc:Habe 800 SammlerAmeisen
		req:800 SammlerAmeise
		icon:icons[9,17]
*BHSammler19
		name:Klebestock
		desc:Habe 850 SammlerAmeisen
		req:850 SammlerAmeise
		icon:icons[9,18]
*BHSammler20
		name:Zange
		desc:Habe 900 SammlerAmeisen
		req:900 SammlerAmeise
		icon:icons[9,19]
*BHSammler21
		name:Deckelkorb
		desc:Habe 950 SammlerAmeisen
		req:950 SammlerAmeise
		icon:icons[9,20]

// Larven Buildings Achievements--------------------------
  
//1  

*BHRaupe1
		name:Gelbe Raupe
		desc:Habe eine Raupe
		req:1 Raupe
		icon:icons[18,0]
*BHRaupe2
		name:Grüne Raupe
		desc:Habe 19 Raupen
		req:19 Raupe
		icon:icons[18,1]
*BHRaupe3
		name:Rote Raupe
		desc:Habe 50 Raupen
		req:50 Raupe
		icon:icons[18,2]
*BHRaupe4
		name:Schöne Raupe
		desc:Habe 100 Raupen
		req:100 Raupe
		icon:icons[18,3]
*BHRaupe5
		name:Kleine Raupe
		desc:Habe 150 Raupen
		req:150 Raupe
		icon:icons[18,4]
*BHRaupe6
		name:Dicke Raupe
		desc:Habe 200 Raupen
		req:200 Raupe
		icon:icons[18,5]
*BHRaupe7
		name:Braune Raupe
		desc:Habe 250 Raupen
		req:250 Raupe
		icon:icons[18,6]
*BHRaupe8
		name:Haarige Raupe
		desc:Habe 300 Raupen
		req:300 Raupe
		icon:icons[18,7]
*BHRaupe9
		name:Kahle Raupe
		desc:Habe 350 Raupen
		req:350 Raupe
		icon:icons[18,8]
*BHRaupe10
		name:Raupastisch Raupe
		desc:Habe 400 Raupen
		req:400 Raupe
		icon:icons[18,9]
*BHRaupe11
		name:Blaue Raupe
		desc:Habe 450 Raupen
		req:450 Raupe
		icon:icons[18,10]
*BHRaupe12
		name:Bunte Raupe
		desc:Habe 500 Raupen
		req:500 Raupe
		icon:icons[18,11]
*BHRaupe13
		name:Dünne Raupe
		desc:Habe 550 Raupen
		req:550 Raupe
		icon:icons[18,12]
*BHRaupe14
		name:Fiese Raupe
		desc:Habe 600 Raupen
		req:600 Raupe
		icon:icons[18,13]
*BHRaupe15
		name:Schwarze Raupe
		desc:Habe 650 Raupen
		req:650 Raupe
		icon:icons[18,14]
*BHRaupe16
		name:Leichte Raupe
		desc:Habe 700 Raupen
		req:700 Raupe
		icon:icons[18,15]
*BHRaupe17
		name:Beige Raupe
		desc:Habe 750 Raupen
		req:750 Raupe
		icon:icons[18,16]
*BHRaupe18
		name:Mutige Raupe
		desc:Habe 800 Raupen
		req:800 Raupe
		icon:icons[18,17]
*BHRaupe19
		name:Ängstliche Raupe
		desc:Habe 850 Raupen
		req:850 Raupe
		icon:icons[18,18]
*BHRaupe20
		name:Zornige Raupe
		desc:Habe 900 Raupen
		req:900 Raupe
		icon:icons[18,19]
*BHRaupe21
		name:Fleißige Raupe
		desc:Habe 950 Raupen
		req:950 Raupe
		icon:icons[18,20]

//2		

*BHBienenstock1
		name:Honig
		desc:Habe einen Bienenstock
		req:1 Bienenstock
		icon:icons[19,0]
*BHBienenstock2
		name:Bienenwabe
		desc:Habe 19 Bienenstöcke
		req:19 Bienenstock
		icon:icons[19,1]
*BHBienenstock3
		name:Kleehonig
		desc:Habe 50 Bienenstöcke
		req:50 Bienenstock
		icon:icons[19,2]
*BHBienenstock4
		name:Waldhonig
		desc:Habe 100 Bienenstöcke
		req:100 Bienenstock
		icon:icons[19,3]
*BHBienenstock5
		name:Blütenhonig
		desc:Habe 150 Bienenstöcke
		req:150 Bienenstock
		icon:icons[19,4]
*BHBienenstock6
		name:Löwenzahnhonig
		desc:Habe 200 Bienenstöcke
		req:200 Bienenstock
		icon:icons[19,5]
*BHBienenstock7
		name:Blatthonig 
		desc:Habe 250 Bienenstöcke
		req:250 Bienenstock
		icon:icons[19,6]
*BHBienenstock8
		name:Tannenhonig
		desc:Habe 300 Bienenstöcke
		req:300 Bienenstock
		icon:icons[19,7]
*BHBienenstock9
		name:Honigbier
		desc:Habe 350 Bienenstöcke
		req:350 Bienenstock
		icon:icons[19,8]
*BHBienenstock10
		name:Met
		desc:Habe 400 Bienenstöcke
		req:400 Bienenstock
		icon:icons[19,9]
*BHBienenstock11
		name:Kunsthonig
		desc:Habe 450 Bienenstöcke
		req:450 Bienenstock
		icon:icons[19,10]
*BHBienenstock12
		name:Türkischer Honig
		desc:Habe 500 Bienenstöcke
		req:500 Bienenstock
		icon:icons[19,11]
*BHBienenstock13
		name:Honigkuchen
		desc:Habe 550 Bienenstöcke
		req:550 Bienenstock
		icon:icons[19,12]
*BHBienenstock14
		name:Bienentee
		desc:Habe 600 Bienenstöcke
		req:600 Bienenstock
		icon:icons[19,13]
*BHBienenstock15
		name:Goldener Honig
		desc:Habe 650 Bienenstöcke
		req:650 Bienenstock
		icon:icons[19,14]
*BHBienenstock16
		name:Zäher Honig
		desc:Habe 700 Bienenstöcke
		req:700 Bienenstock
		icon:icons[19,15]
*BHBienenstock17
		name:Großer Bienenstock
		desc:Habe 750 Bienenstöcke
		req:750 Bienenstock
		icon:icons[19,16]
*BHBienenstock18
		name:Dicker Bienenstock
		desc:Habe 800 Bienenstöcke
		req:800 Bienenstock
		icon:icons[19,17]
*BHBienenstock19
		name:Dünner Bienenstock
		desc:Habe 850 Bienenstöcke
		req:850 Bienenstock
		icon:icons[19,18]
*BHBienenstock20
		name:Verstärkter Bienenstock
		desc:Habe 900 Bienenstöcke
		req:900 Bienenstock
		icon:icons[19,19]
*BHBienenstock21
		name:Verkleideter Bienenstock
		desc:Habe 950 Bienenstöcke
		req:950 Bienenstock
		icon:icons[19,20]
		
//3		

*BHTermitenbau1
		name:Termitenhügel
		desc:Habe einen Termitenbau
		req:1 Termitenbau
		icon:icons[20,0]
*BHTermitenbau2
		name:Termitenberg
		desc:Habe 19 Termitenbauten
		req:19 Termitenbau
		icon:icons[20,1]
*BHTermitenbau3
		name:Termitenbaum
		desc:Habe 50 Termitenbauten
		req:50 Termitenbau
		icon:icons[20,2]
*BHTermitenbau4
		name:Morscher Baum
		desc:Habe 100 Termitenbauten
		req:100 Termitenbau
		icon:icons[20,3]
*BHTermitenbau5
		name:Verzweigter Termitenbau
		desc:Habe 150 Termitenbauten
		req:150 Termitenbau
		icon:icons[20,4]
*BHTermitenbau6
		name:Hoher Termitenbau
		desc:Habe 200 Termitenbauten
		req:200 Termitenbau
		icon:icons[20,5]
*BHTermitenbau7
		name:Dichter Termitenbau
		desc:Habe 250 Termitenbauten
		req:250 Termitenbau
		icon:icons[20,6]
*BHTermitenbau8
		name:Enger Termitenbau
		desc:Habe 300 Termitenbauten
		req:300 Termitenbau
		icon:icons[20,7]
*BHTermitenbau9
		name:Großer Termitenbau
		desc:Habe 350 Termitenbauten
		req:350 Termitenbau
		icon:icons[20,8]
*BHTermitenbau10
		name:Runder Termitenbau
		desc:Habe 400 Termitenbauten
		req:400 Termitenbau
		icon:icons[20,9]
*BHTermitenbau11
		name:Lehmiger Termitenbau
		desc:Habe 450 Termitenbauten
		req:450 Termitenbau
		icon:icons[20,10]
*BHTermitenbau12
		name:Hölzerner Termitenbau
		desc:Habe 500 Termitenbauten
		req:500 Termitenbau
		icon:icons[20,11]
*BHTermitenbau13
		name:Tarnbau
		desc:Habe 550 Termitenbauten
		req:550 Termitenbau
		icon:icons[20,12]
*BHTermitenbau14
		name:Langer Termitenbau
		desc:Habe 600 Termitenbauten
		req:600 Termitenbau
		icon:icons[20,13]
*BHTermitenbau15
		name:Löchriger Termitenbau
		desc:Habe 650 Termitenbauten
		req:650 Termitenbau
		icon:icons[20,14]
*BHTermitenbau16
		name:Effectiver Termitenbau
		desc:Habe 700 Termitenbauten
		req:700 Termitenbau
		icon:icons[20,15]
*BHTermitenbau17
		name:Ausgebauter Termitenbau
		desc:Habe 750 Termitenbauten
		req:750 Termitenbau
		icon:icons[20,16]
*BHTermitenbau18
		name:Ausgelasteter Termitenbau
		desc:Habe 800 Termitenbauten
		req:800 Termitenbau
		icon:icons[20,17]
*BHTermitenbau19
		name:Termitenhaus 
		desc:Habe 850 Termitenbauten
		req:850 Termitenbau
		icon:icons[20,18]
*BHTermitenbau20
		name:Termitenbalken
		desc:Habe 900 Termitenbauten
		req:900 Termitenbau
		icon:icons[20,19]
*BHTermitenbau21
		name:Morsche Veranda
		desc:Habe 950 Termitenbauten
		req:950 Termitenbau
		icon:icons[20,20]
//4		

*BHBlatt1
		name:Kleines Blatt
		desc:Habe eine Blatt
		req:1 Blatt
		icon:iconsa[0,0]
*BHBlatt2
		name:Rotes Blatt
		desc:Habe 19 Blätter
		req:19 Blatt
		icon:iconsa[0,1]
*BHBlatt3
		name:Grünes Blatt
		desc:Habe 50 Blätter
		req:50 Blatt
		icon:iconsa[0,2]
*BHBlatt4
		name:Zerkratztes Blatt
		desc:Habe 100 Blätter
		req:100 Blatt
		icon:iconsa[0,3]
*BHBlatt5
		name:Zerrissenes Blatt
		desc:Habe 150 Blätter
		req:150 Blatt
		icon:iconsa[0,4]
*BHBlatt6
		name:Braunes Blatt
		desc:Habe 200 Blätter
		req:200 Blatt
		icon:iconsa[0,5]
*BHBlatt7
		name:Orangenes Blatt
		desc:Habe 250 Blätter
		req:250 Blatt
		icon:iconsa[0,6]
*BHBlatt8
		name:Grobes Blatt
		desc:Habe 300 Blätter
		req:300 Blatt
		icon:iconsa[0,7]
*BHBlatt9
		name:Starkes Blatt
		desc:Habe 350 Blätter
		req:350 Blatt
		icon:iconsa[0,8]
*BHBlatt10
		name:Winziges Blatt
		desc:Habe 400 Blätter
		req:400 Blatt
		icon:iconsa[0,9]
*BHBlatt11
		name:Leuchtendes Blatt
		desc:Habe 450 Blätter
		req:450 Blatt
		icon:iconsa[0,10]
*BHBlatt12
		name:Hellgrünes Blatt
		desc:Habe 500 Blätter
		req:500 Blatt
		icon:iconsa[0,11]
*BHBlatt13
		name:Buntes Blatt
		desc:Habe 550 Blätter
		req:550 Blatt
		icon:iconsa[0,12]
*BHBlatt14
		name:Herbstblatt
		desc:Habe 600 Blätter
		req:600 Blatt
		icon:iconsa[0,13]
*BHBlatt15
		name:Echsenblatt
		desc:Habe 650 Blätter
		req:650 Blatt
		icon:iconsa[0,14]
*BHBlatt16
		name:Blättle
		desc:Habe 700 Blätter
		req:700 Blatt
		icon:iconsa[0,15]
*BHBlatt17
		name:Blättchen
		desc:Habe 750 Blätter
		req:750 Blatt
		icon:iconsa[0,16]
*BHBlatt18
		name:Blättling
		desc:Habe 800 Blätter
		req:800 Blatt
		icon:iconsa[0,17]
*BHBlatt19
		name:Plattes Blatt
		desc:Habe 850 Blätter
		req:850 Blatt
		icon:iconsa[0,18]
*BHBlatt20
		name:Rundes Blatt
		desc:Habe 900 Blätter
		req:900 Blatt
		icon:iconsa[0,19]
*BHBlatt21
		name:Goldenes Blatt
		desc:Habe 950 Blätter
		req:950 Blatt
		icon:iconsa[0,20]
		
//5

*BHWNest1
		name:Wespig
		desc:Habe ein WespenNest
		req:1 WespenNest
		icon:iconsb[5,0]
*BHWNest2
		name:Wespenstich
		desc:Habe 19 WespenNester
		req:19 WespenNest
		icon:iconsb[5,1]
*BHWNest3
		name:Wespender
		desc:Habe 50 WespenNester
		req:50 WespenNester
		icon:iconsb[5,2]
*BHWNest4
		name:Wespenspaß
		desc:Habe 100 WespenNester
		req:100 WespenNester
		icon:iconsb[5,3]
*BHWNest5
		name:Wespenfeier
		desc:Habe 150 WespenNester
		req:150 WespenNester
		icon:iconsb[5,4]
*BHWNest6
		name:Wespenparty
		desc:Habe 200 WespenNester
		req:200 WespenNester
		icon:iconsb[5,5]
*BHWNest7
		name:Wespenessen
		desc:Habe 250 WespenNester
		req:250 WespenNester
		icon:iconsb[5,6]
*BHWNest8
		name:Wespenfete
		desc:Habe 300 WespenNester
		req:300 WespenNester
		icon:iconsb[5,7]
*BHWNest9
		name:Wespensause
		desc:Habe 350 WespenNester
		req:350 WespenNester
		icon:iconsb[5,8]
*BHWNest10
		name:Wespenschule
		desc:Habe 400 WespenNester
		req:400 WespenNester
		icon:iconsb[5,9]
*BHWNest11
		name:Wespenunterricht
		desc:Habe 450 WespenNester
		req:450 WespenNester
		icon:iconsb[5,10]
*BHWNest12
		name:Wespenazubi
		desc:Habe 500 WespenNester
		req:500 WespenNester
		icon:iconsb[5,11]
*BHWNest13
		name:Wespenmeister
		desc:Habe 550 WespenNester
		req:550 WespenNester
		icon:iconsb[5,12]
*BHWNest14
		name:Wespenkappo
		desc:Habe 600 WespenNester
		req:600 WespenNester
		icon:iconsb[5,13]
*BHWNest15
		name:Wespenvormann
		desc:Habe 650 WespenNester
		req:650 WespenNester
		icon:iconsb[5,14]
*BHWNest16
		name:Wespenführer
		desc:Habe 700 WespenNester
		req:700 WespenNester
		icon:iconsb[5,15]
*BHWNest17
		name:Wespenverfolgung
		desc:Habe 750 WespenNester
		req:750 WespenNester
		icon:iconsb[5,16]
*BHWNest18
		name:Wespenerweiterung
		desc:Habe 800 WespenNester
		req:800 WespenNester
		icon:iconsb[5,17]
*BHWNest19
		name:Wespentiming
		desc:Habe 850 WespenNester
		req:850 WespenNester
		icon:iconsb[5,18]
*BHWNest20
		name:Wespenkindergarten
		desc:Habe 900 WespenNester
		req:900 WespenNester
		icon:iconsb[5,19]
*BHWNest21
		name:Wespenkita
		desc:Habe 950 WespenNester
		req:950 WespenNester
		icon:iconsb[5,20]
		
//6

*BHVApfel1
		name:Grumbelchen
		desc:Habe einen VerfaultenApfel
		req:1 VerfaulterApfel
		icon:iconsb[6,0]
*BHVApfel2
		name:Schrumpel
		desc:Habe 19 VerfaulteÄpfel
		req:19 VerfaulterApfel
		icon:iconsb[6,1]
*BHVApfel3
		name:Apfelmus
		desc:Habe 50 VerfaulteÄpfel
		req:50 VerfaulterApfel
		icon:iconsb[6,2]
*BHVApfel4
		name:Apfelpudding
		desc:Habe 100 VerfaulteÄpfel
		req:100 VerfaulterApfel
		icon:iconsb[6,3]
*BHVApfel5
		name:Apfel mit Haaren
		desc:Habe 150 VerfaulteÄpfel
		req:150 VerfaulterApfel
		icon:iconsb[6,4]
*BHVApfel6
		name:Apfelig
		desc:Habe 200 VerfaulteÄpfel
		req:200 VerfaulterApfel
		icon:iconsb[6,5]
*BHVApfel7
		name:Apfelwein
		desc:Habe 250 VerfaulteÄpfel
		req:250 VerfaulterApfel
		icon:iconsb[6,6]
*BHVApfel8
		name:Apfelmost
		desc:Habe 300 VerfaulteÄpfel
		req:300 VerfaulterApfel
		icon:iconsb[6,7]
*BHVApfel9
		name:Apfeltaschen
		desc:Habe 350 VerfaulteÄpfel
		req:350 VerfaulterApfel
		icon:iconsb[6,8]
*BHVApfel10
		name:Apfelkuchen
		desc:Habe 400 VerfaulteÄpfel
		req:400 VerfaulterApfel
		icon:iconsb[6,9]
*BHVApfel11
		name:Apfelwasser
		desc:Habe 450 VerfaulteÄpfel
		req:450 VerfaulterApfel
		icon:iconsb[6,10]
*BHVApfel12
		name:Apfelschorle
		desc:Habe 500 VerfaulteÄpfel
		req:500 VerfaulterApfel
		icon:iconsb[6,11]
*BHVApfel13
		name:Apfelkorb
		desc:Habe 550 VerfaulteÄpfel
		req:550 VerfaulterApfel
		icon:iconsb[6,12]
*BHVApfel14
		name:Apfelbäumlein
		desc:Habe 600 VerfaulteÄpfel
		req:600 VerfaulterApfel
		icon:iconsb[6,13]
*BHVApfel15
		name:Apfelsüß
		desc:Habe 650 VerfaulteÄpfel
		req:650 VerfaulterApfel
		icon:iconsb[6,14]
*BHVApfel16
		name:Apfelsauer
		desc:Habe 700 VerfaulteÄpfel
		req:700 VerfaulterApfel
		icon:iconsb[6,15]
*BHVApfel17
		name:Apfelfarm
		desc:Habe 750 VerfaulteÄpfel
		req:750 VerfaulterApfel
		icon:iconsb[6,16]
*BHVApfel18
		name:Äpfle
		desc:Habe 800 VerfaulteÄpfel
		req:800 VerfaulterApfel
		icon:iconsb[6,17]
*BHVApfel19
		name:Apfelkern
		desc:Habe 850 VerfaulteÄpfel
		req:850 VerfaulterApfel
		icon:iconsb[6,18]
*BHVApfel20
		name:Apfelkeimling
		desc:Habe 900 VerfaulteÄpfel
		req:900 VerfaulterApfel
		icon:iconsb[6,19]
*BHVApfel21
		name:Apfelhaufen
		desc:Habe 950 VerfaulteÄpfel
		req:950 VerfaulterApfel
		icon:iconsb[6,20]
		
//7

*BHANest1
		name:Erste Sichtung
		desc:Habe ein AltesNest
		req:1 AltesNest
		icon:iconsb[7,0]
*BHANest2
		name:Gewirr aus Zweigen
		desc:Habe 19 AlteNester
		req:19 AltesNest
		icon:iconsb[7,1]
*BHANest3
		name:Geflochtenes Nest
		desc:Habe 50 AlteNester
		req:50 AltesNest
		icon:iconsb[7,2]
*BHANest4
		name:Verlassenes Nest
		desc:Habe 100 AlteNester
		req:100 AltesNest
		icon:iconsb[7,3]
*BHANest5
		name:FederNest
		desc:Habe 150 AlteNester
		req:150 AltesNest
		icon:iconsb[7,4]
*BHANest6
		name:Gepolstertes Nest
		desc:Habe 200 AlteNester
		req:200 AltesNest
		icon:iconsb[7,5]
*BHANest7
		name:Nestling
		desc:Habe 250 AlteNester
		req:250 AltesNest
		icon:iconsb[7,6]
*BHANest8
		name:Nestfreund
		desc:Habe 300 AlteNester
		req:300 AltesNest
		icon:iconsb[7,7]
*BHANest9
		name:Nestsammler
		desc:Habe 350 AlteNester
		req:350 AltesNest
		icon:iconsb[7,8]
*BHANest10
		name:Nestliebhaber
		desc:Habe 400 AlteNester
		req:400 AltesNest
		icon:iconsb[7,9]
*BHANest11
		name:Nestelung
		desc:Habe 450 AlteNester
		req:450 AltesNest
		icon:iconsb[7,10]
*BHANest12
		name:Nesthalter
		desc:Habe 500 AlteNester
		req:500 AltesNest
		icon:iconsb[7,11]
*BHANest13
		name:Nestfeier
		desc:Habe 550 AlteNester
		req:550 AltesNest
		icon:iconsb[7,12]
*BHANest14
		name:Nestgröße
		desc:Habe 600 AlteNester
		req:600 AltesNest
		icon:iconsb[7,13]
*BHANest15
		name:Nestordnung
		desc:Habe 650 AlteNester
		req:650 AltesNest
		icon:iconsb[7,14]
*BHANest16
		name:Nestpackung
		desc:Habe 700 AlteNester
		req:700 AltesNest
		icon:iconsb[7,15]
*BHANest17
		name:Nesterer
		desc:Habe 750 AlteNester
		req:750 AltesNest
		icon:iconsb[7,16]
*BHANest18
		name:Nestbauer
		desc:Habe 800 AlteNester
		req:800 AltesNest
		icon:iconsb[7,17]
*BHANest19
		name:Nestberger
		desc:Habe 850 AlteNester
		req:850 AltesNest
		icon:iconsb[7,18]
*BHANest20
		name:Nesteros
		desc:Habe 900 AlteNester
		req:900 AltesNest
		icon:iconsb[7,19]
*BHANest21
		name:Nestgruß
		desc:Habe 950 AlteNester
		req:950 AltesNest
		icon:iconsb[7,20]

//8

*BHSchuh1
		name:Lackschuh
		desc:Habe einen ÜberwuchertenSchuh
		req:1 UeberwucherterSchuh
		icon:iconsb[8,0]
*BHSchuh2
		name:Stiletto
		desc:Habe 19 ÜberwucherteSchuhe
		req:19 UeberwucherterSchuh
		icon:iconsb[8,1]
*BHSchuh3
		name:Klocks
		desc:Habe 50 ÜberwucherteSchuhe
		req:50 UeberwucherterSchuh
		icon:iconsb[8,2]
*BHSchuh4
		name:Schuhkarton
		desc:Habe 100 ÜberwucherteSchuhe
		req:100 UeberwucherterSchuh
		icon:iconsb[8,3]
*BHSchuh5
		name:Slipper
		desc:Habe 150 ÜberwucherteSchuhe
		req:150 UeberwucherterSchuh
		icon:iconsb[8,4]
*BHSchuh6
		name:Cowboystiefel
		desc:Habe 200 ÜberwucherteSchuhe
		req:200 UeberwucherterSchuh
		icon:iconsb[8,5]
*BHSchuh7
		name:Mudboots
		desc:Habe 250 ÜberwucherteSchuhe
		req:250 UeberwucherterSchuh
		icon:iconsb[8,6]
*BHSchuh8
		name:Schuhlöffel
		desc:Habe 300 ÜberwucherteSchuhe
		req:300 UeberwucherterSchuh
		icon:iconsb[8,7]
*BHSchuh9
		name:Schuhspanner
		desc:Habe 350 ÜberwucherteSchuhe
		req:350 UeberwucherterSchuh
		icon:iconsb[8,8]
*BHSchuh10
		name:Schuhsohle
		desc:Habe 400 ÜberwucherteSchuhe
		req:400 UeberwucherterSchuh
		icon:iconsb[8,9]
*BHSchuh11
		name:Mokassin
		desc:Habe 450 ÜberwucherteSchuhe
		req:450 UeberwucherterSchuh
		icon:iconsb[8,10]
*BHSchuh12
		name:Schnürsenkel
		desc:Habe 500 ÜberwucherteSchuhe
		req:500 UeberwucherterSchuh
		icon:iconsb[8,11]
*BHSchuh13
		name:Ein Paar Schuhe
		desc:Habe 550 ÜberwucherteSchuhe
		req:550 UeberwucherterSchuh
		icon:iconsb[8,12]
*BHSchuh14
		name:Schuster
		desc:Habe 600 ÜberwucherteSchuhe
		req:600 UeberwucherterSchuh
		icon:iconsb[8,13]
*BHSchuh15
		name:Pantoffel
		desc:Habe 650 ÜberwucherteSchuhe
		req:650 UeberwucherterSchuh
		icon:iconsb[8,14]
*BHSchuh16
		name:Treter
		desc:Habe 700 ÜberwucherteSchuhe
		req:700 UeberwucherterSchuh
		icon:iconsb[8,15]
*BHSchuh17
		name:Latschen
		desc:Habe 750 ÜberwucherteSchuhe
		req:750 UeberwucherterSchuh
		icon:iconsb[8,16]
*BHSchuh18
		name:Steinzeitschuh
		desc:Habe 800 ÜberwucherteSchuhe
		req:800 UeberwucherterSchuh
		icon:iconsb[8,17]
*BHSchuh19
		name:Skischuh
		desc:Habe 850 ÜberwucherteSchuhe
		req:850 UeberwucherterSchuh
		icon:iconsb[8,18]
*BHSchuh20
		name:Schneeschuh
		desc:Habe 900 ÜberwucherteSchuhe
		req:900 UeberwucherterSchuh
		icon:iconsb[8,19]
*BHSchuh21
		name:Schnürschuh
		desc:Habe 950 ÜberwucherteSchuhe
		req:950 UeberwucherterSchuh
		icon:iconsb[8,20]
				

// Insekten achievments -----------------------------------		
//1

*BHAmeise1
		name:Magd
		desc:Habe eine Ameise
		req:1 Ameise
		icon:iconsa[11,0]
*BHAmeise2
		name:Kämmerer
		desc:Habe 19 Ameisen
		req:19 Ameise
		icon:iconsa[11,1]
*BHAmeise3
		name:Mundschenk
		desc:Habe 50 Ameisen
		req:50 Ameise
		icon:iconsa[11,2]
*BHAmeise4
		name:Notar
		desc:Habe 100 Ameisen
		req:100 Ameise
		icon:iconsa[11,3]
*BHAmeise5
		name:Graf
		desc:Habe 150 Ameisen
		req:150 Ameise
		icon:iconsa[11,4]
*BHAmeise6
		name:Gräfin
		desc:Habe 200 Ameisen
		req:200 Ameise
		icon:iconsa[11,5]
*BHAmeise7
		name:Diener
		desc:Habe 250 Ameisen
		req:250 Ameise
		icon:iconsa[11,6]
*BHAmeise8
		name:Schildknappe
		desc:Habe 300 Ameisen
		req:300 Ameise
		icon:iconsa[11,7]
*BHAmeise9
		name:Komtess
		desc:Habe 350 Ameisen
		req:350 Ameise
		icon:iconsa[11,8]
*BHAmeise10
		name:Ritter
		desc:Habe 400 Ameisen
		req:400 Ameise
		icon:iconsa[11,9]
*BHAmeise11
		name:Edelmann
		desc:Habe 450 Ameisen
		req:450 Ameise
		icon:iconsa[11,10]
*BHAmeise12
		name:Medicus
		desc:Habe 500 Ameisen
		req:500 Ameise
		icon:iconsa[11,11]
*BHAmeise13
		name:Konsul
		desc:Habe 550 Ameisen
		req:550 Ameise
		icon:iconsa[11,12]
*BHAmeise14
		name:Baron
		desc:Habe 600 Ameisen
		req:600 Ameise
		icon:iconsa[11,13]
*BHAmeise15
		name:Vogt
		desc:Habe 650 Ameisen
		req:650 Ameise
		icon:iconsa[11,14]
*BHAmeise16
		name:Kanzler
		desc:Habe 700 Ameisen
		req:700 Ameise
		icon:iconsa[11,15]		
*BHAmeise17
		name:Hofnarr
		desc:Habe 750 Ameisen
		req:750 Ameise
		icon:iconsa[11,16]
*BHAmeise18
		name:Prinzessin
		desc:Habe 800 Ameisen
		req:800 Ameise
		icon:iconsa[11,17]
*BHAmeise19
		name:Prinz
		desc:Habe 850 Ameisen
		req:850 Ameise
		icon:iconsa[11,18]
*BHAmeise20
		name:King
		desc:Habe 900 Ameisen
		req:900 Ameise
		icon:iconsa[11,19]
*BHAmeise21
		name:Queen
		desc:Habe 950 Ameisen
		req:950 Ameise
		icon:iconsa[11,20]
	


//2

*BHTermite1
		name:Nasen Termite
		desc:Habe eine Termite
		req:1 Termite
		icon:iconsa[12,0]
*BHTermite2
		name:Trocken Termite
		desc:Habe 19 Termiten
		req:19 Termite
		icon:iconsa[12,1]
*BHTermite3
		name:Ernte Termite
		desc:Habe 50 Termiten
		req:50 Termite
		icon:iconsa[12,2]
*BHTermite4
		name:Riesen Termite
		desc:Habe 100 Termiten
		req:100 Termite
		icon:iconsa[12,3]
*BHTermite5
		name:Hodo Termite
		desc:Habe 150 Termiten
		req:150 Termite
		icon:iconsa[12,4]
*BHTermite6
		name:Trockenholz Termite
		desc:Habe 200 Termiten
		req:200 Termite
		icon:iconsa[12,5]
*BHTermite7
		name:Ast Termite
		desc:Habe 250 Termiten
		req:250 Termite
		icon:iconsa[12,6]
*BHTermite8
		name:Baum Termite
		desc:Habe 300 Termiten
		req:300 Termite
		icon:iconsa[12,7]
*BHTermite9
		name:Strauch Termite
		desc:Habe 350 Termiten
		req:350 Termite
		icon:iconsa[12,8]
*BHTermite10
		name:Tropen Termite
		desc:Habe 400 Termiten
		req:400 Termite
		icon:iconsa[12,9]
*BHTermite11
		name:Wüsten Termite
		desc:Habe 450 Termiten
		req:450 Termite
		icon:iconsa[12,10]
*BHTermite12
		name:Savannen Termite
		desc:Habe 500 Termiten
		req:500 Termite
		icon:iconsa[12,11]
*BHTermite13
		name:Regenwald Termite
		desc:Habe 550 Termiten
		req:550 Termite
		icon:iconsa[12,12]
*BHTermite14
		name:Spanische Termite
		desc:Habe 600 Termiten
		req:600 Termite
		icon:iconsa[12,13]
*BHTermite15
		name:Ungarische Termite
		desc:Habe 650 Termiten
		req:650 Termite
		icon:iconsa[12,14]
*BHTermite16
		name:Französiche Termite
		desc:Habe 700 Termiten
		req:700 Termite
		icon:iconsa[12,15]		
*BHTermite17
		name:Amerikanische Termite
		desc:Habe 750 Termiten
		req:750 Termite
		icon:iconsa[12,16]
*BHTermite18
		name:Osteuropäische Termite
		desc:Habe 800 Termiten
		req:800 Termite
		icon:iconsa[12,17]
*BHTermite19
		name:Mongolische Termite
		desc:Habe 850 Termiten
		req:850 Termite
		icon:iconsa[12,18]
*BHTermite20
		name:Mexikanische Termite
		desc:Habe 900 Termiten
		req:900 Termite
		icon:iconsa[12,19]
*BHTermite21
		name:Termitidae
		desc:Habe 950 Termiten
		req:950 Termite
		icon:iconsa[12,20]
//3

*BHFliege1
		name:Bssssssssss
		desc:Habe eine Fliege
		req:1 Fliege
		icon:iconsa[13,0]
*BHFliege2
		name:Bsssss Bsssss
		desc:Habe 19 Fliegen
		req:19 Fliege
		icon:iconsa[13,1]
*BHFliege3
		name:Bsss
		desc:Habe 50 Fliegen
		req:50 Fliege
		icon:iconsa[13,2]
*BHFliege4
		name:Flugzeug
		desc:Habe 100 Fliegen
		req:100 Fliege
		icon:iconsa[13,3]
*BHFliege5
		name:Helikopter
		desc:Habe 150 Fliegen
		req:150 Fliege
		icon:iconsa[13,4]
*BHFliege6
		name:Hubschrauber
		desc:Habe 200 Fliegen
		req:200 Fliege
		icon:iconsa[13,5]
*BHFliege7
		name:Segelflugzeug
		desc:Habe 250 Fliegen
		req:250 Fliege
		icon:iconsa[13,6]
*BHFliege8
		name:Propellerflugzeug
		desc:Habe 300 Fliegen
		req:300 Fliege
		icon:iconsa[13,7]
*BHFliege9
		name:Jäger
		desc:Habe 350 Fliegen
		req:350 Fliege
		icon:iconsa[13,8]
*BHFliege10
		name:Bomber
		desc:Habe 400 Fliegen
		req:400 Fliege
		icon:iconsa[13,9]
*BHFliege11
		name:Schlachtflugzeug
		desc:Habe 450 Fliegen
		req:450 Fliege
		icon:iconsa[13,10]
*BHFliege12
		name:Torpedobomber
		desc:Habe 500 Fliegen
		req:500 Fliege
		icon:iconsa[13,11]
*BHFliege13
		name:Drone
		desc:Habe 550 Fliegen
		req:550 Fliege
		icon:iconsa[13,12]
*BHFliege14
		name:Jet
		desc:Habe 600 Fliegen
		req:600 Fliege
		icon:iconsa[13,13]
*BHFliege15
		name:Kampfjet
		desc:Habe 650 Fliegen
		req:650 Fliege
		icon:iconsa[13,14]
*BHFliege16
		name:Düsenjet
		desc:Habe 700 Fliegen
		req:700 Fliege
		icon:iconsa[13,15]		
*BHFliege17
		name:Flattermann
		desc:Habe 750 Fliegen
		req:750 Fliege
		icon:iconsa[13,16]
*BHFliege18
		name:Flotte Fliege
		desc:Habe 800 Fliegen
		req:800 Fliege
		icon:iconsa[13,17]
*BHFliege19
		name:Brumse Fliege
		desc:Habe 850 Fliegen
		req:850 Fliege
		icon:iconsa[13,18]
*BHFliege20
		name:Fliegelitis
		desc:Habe 900 Fliegen
		req:900 Fliege
		icon:iconsa[13,19]
*BHFliege21
		name:Fliegensammlung
		desc:Habe 950 Fliegen
		req:950 Fliege
		icon:iconsa[13,20]	

//4

*BHKaefer1
		name:Käfermobil
		desc:Habe einen Käfer
		req:1 Kaefer
		icon:iconsa[14,0]
*BHKaefer2
		name:Käferplatz
		desc:Habe 19 Käfer
		req:19 Kaefer
		icon:iconsa[14,1]
*BHKaefer3
		name:Käferdojo
		desc:Habe 50 Käfer
		req:50 Kaefer
		icon:iconsa[14,2]
*BHKaefer4
		name:Käferkungfu
		desc:Habe 100 Käfer
		req:100 Kaefer
		icon:iconsa[14,3]
*BHKaefer5
		name:Käferboxen
		desc:Habe 150 Käfer
		req:150 Kaefer
		icon:iconsa[14,4]
*BHKaefer6
		name:Käferringen
		desc:Habe 200 Käfer
		req:200 Kaefer
		icon:iconsa[14,5]
*BHKaefer7
		name:Käferball
		desc:Habe 250 Käfer
		req:250 Kaefer
		icon:iconsa[14,6]
*BHKaefer8
		name:Käferrücken
		desc:Habe 300 Käfer
		req:300 Kaefer
		icon:iconsa[14,7]
*BHKaefer9
		name:Käfersummen
		desc:Habe 350 Käfer
		req:350 Kaefer
		icon:iconsa[14,8]
*BHKaefer10
		name:Käfermusik
		desc:Habe 400 Käfer
		req:400 Kaefer
		icon:iconsa[14,9]
*BHKaefer11
		name:Käferschwimmen
		desc:Habe 450 Käfer
		req:450 Kaefer
		icon:iconsa[14,10]
*BHKaefer12
		name:Käferkegeln
		desc:Habe 500 Käfer
		req:500 Kaefer
		icon:iconsa[14,11]
*BHKaefer13
		name:Käferbowlen
		desc:Habe 550 Käfer
		req:550 Kaefer
		icon:iconsa[14,12]
*BHKaefer14
		name:Käferfusball
		desc:Habe 600 Käfer
		req:600 Kaefer
		icon:iconsa[14,13]
*BHKaefer15
		name:Käferessen
		desc:Habe 650 Käfer
		req:650 Kaefer
		icon:iconsa[14,14]
*BHKaefer16
		name:Käferfangen
		desc:Habe 700 Käfer
		req:700 Kaefer
		icon:iconsa[14,15]		
*BHKaefer17
		name:Käferweitspringen
		desc:Habe 750 Käfer
		req:750 Kaefer
		icon:iconsa[14,16]
*BHKaefer18
		name:Käferwerfen
		desc:Habe 800 Käfer
		req:800 Kaefer
		icon:iconsa[14,17]
*BHKaefer19
		name:Käferstoßen
		desc:Habe 850 Käfer
		req:850 Kaefer
		icon:iconsa[14,18]
*BHKaefer20
		name:Käferspringen
		desc:Habe 900 Käfer
		req:900 Kaefer
		icon:iconsa[14,19]
*BHKaefer21
		name:Käferitis
		desc:Habe 950 Käfer
		req:950 Kaefer
		icon:iconsa[14,20]

//5

*BHBiene1
		name:Biene!
		desc:Habe eine Biene
		req:1 Biene
		icon:iconsb[10,0]
*BHBiene2
		name:Bientastisch!
		desc:Habe 19 Bienen
		req:19 Biene
		icon:iconsb[10,1]
*BHBiene3
		name:Bienolös!
		desc:Habe 50 Bienen
		req:50 Biene
		icon:iconsb[10,2]
*BHBiene4
		name:Bienartig!
		desc:Habe 100 Bienen
		req:100 Biene
		icon:iconsb[10,3]
*BHBiene5
		name:Bienper!
		desc:Habe 150 Bienen
		req:150 Biene
		icon:iconsb[10,4]
*BHBiene6
		name:Boll!
		desc:Habe 200 Bienen
		req:200 Biene
		icon:iconsb[10,5]
*BHBiene7
		name:Bienotisch!
		desc:Habe 250 Bienen
		req:250 Biene
		icon:iconsb[10,6]
*BHBiene8
		name:Biemazing!
		desc:Habe 300 Bienen
		req:300 Biene
		icon:iconsb[10,7]
*BHBiene9
		name:Bienblowing!
		desc:Habe 350 Bienen
		req:350 Biene
		icon:iconsb[10,8]
*BHBiene10
		name:Bienflying!
		desc:Habe 400 Bienen
		req:400 Biene
		icon:iconsb[10,9]
*BHBiene11
		name:Biemarkable!
		desc:Habe 450 Bienen
		req:450 Biene
		icon:iconsb[10,10]
*BHBiene12
		name:Biecredible!
		desc:Habe 500 Bienen
		req:500 Biene
		icon:iconsb[10,11]
*BHBiene13
		name:Bextraordinary!
		desc:Habe 550 Bienen
		req:550 Biene
		icon:iconsb[10,12]
*BHBiene14
		name:Biesational!
		desc:Habe 600 Bienen
		req:600 Biene
		icon:iconsb[10,13]
*BHBiene15
		name:Bieprising!
		desc:Habe 650 Bienen
		req:650 Biene
		icon:iconsb[10,14]
*BHBiene16
		name:Biestaunlich!
		desc:Habe 700 Bienen
		req:700 Biene
		icon:iconsb[10,15]
*BHBiene17
		name:Bientopia
		desc:Habe 750 Bienen
		req:750 Biene
		icon:iconsb[10,16]
*BHBiene18
		name:Bienenhyphe
		desc:Habe 800 Bienen
		req:800 Biene
		icon:iconsb[10,17]
*BHBiene19
		name:Bielinear!
		desc:Habe 850 Bienen
		req:850 Biene
		icon:iconsb[10,18]
*BHBiene20
		name:Biekubisch!
		desc:Habe 900 Bienen
		req:900 Biene
		icon:iconsb[10,19]
*BHBiene21
		name:Bieson!
		desc:Habe 950 Bienen
		req:950 Biene
		icon:iconsb[10,20]
				
		

//6

*BHRoteAmeise1
		name:Feuerrot!
		desc:Habe eine RoteAmeise
		req:1 RoteAmeise
		icon:iconsb[11,0]
*BHRoteAmeise2
		name:Rötlich!
		desc:Habe 19 RoteAmeisen
		req:19 RoteAmeise
		icon:iconsb[11,1]
*BHRoteAmeise3
		name:Granatrot!
		desc:Habe 50 RoteAmeisen
		req:50 RoteAmeise
		icon:iconsb[11,2]
*BHRoteAmeise4
		name:Röter!
		desc:Habe 100 RoteAmeisen
		req:100 RoteAmeise
		icon:iconsb[11,3]
*BHRoteAmeise5
		name:Ahornrot!
		desc:Habe 150 RoteAmeisen
		req:150 RoteAmeise
		icon:iconsb[11,4]
*BHRoteAmeise6
		name:Blutrot!
		desc:Habe 200 RoteAmeisen
		req:200 RoteAmeise
		icon:iconsb[11,5]
*BHRoteAmeise7
		name:Bordeauxrot!
		desc:Habe 250 RoteAmeisen
		req:250 RoteAmeise
		icon:iconsb[11,6]
*BHRoteAmeise8
		name:Chilli!
		desc:Habe 300 RoteAmeisen
		req:300 RoteAmeise
		icon:iconsb[11,7]
*BHRoteAmeise9
		name:Erdbeerrot!
		desc:Habe 350 RoteAmeisen
		req:350 RoteAmeise
		icon:iconsb[11,8]
*BHRoteAmeise10
		name:Glutrot!
		desc:Habe 400 RoteAmeisen
		req:400 RoteAmeise
		icon:iconsb[11,9]
*BHRoteAmeise11
		name:Hellrot!
		desc:Habe 450 RoteAmeisen
		req:450 RoteAmeise
		icon:iconsb[11,10]
*BHRoteAmeise12
		name:Dunkelrot!
		desc:Habe 500 RoteAmeisen
		req:500 RoteAmeise
		icon:iconsb[11,11]
*BHRoteAmeise13
		name:Kirschrot!
		desc:Habe 550 RoteAmeisen
		req:550 RoteAmeise
		icon:iconsb[11,12]
*BHRoteAmeise14
		name:Knallrot!
		desc:Habe 600 RoteAmeisen
		req:600 RoteAmeise
		icon:iconsb[11,13]
*BHRoteAmeise15
		name:Purpurrot!
		desc:Habe 650 RoteAmeisen
		req:650 RoteAmeise
		icon:iconsb[11,14]
*BHRoteAmeise16
		name:Scharlachrot!
		desc:Habe 700 RoteAmeisen
		req:700 RoteAmeise
		icon:iconsb[11,15]
*BHRoteAmeise17
		name:Ziegelrot!
		desc:Habe 750 RoteAmeisen
		req:750 RoteAmeise
		icon:iconsb[11,16]
*BHRoteAmeise18
		name:Magmarot!
		desc:Habe 800 RoteAmeisen
		req:800 RoteAmeise
		icon:iconsb[11,17]
*BHRoteAmeise19
		name:Zinoberrot!
		desc:Habe 850 RoteAmeisen
		req:850 RoteAmeise
		icon:iconsb[11,18]
*BHRoteAmeise20
		name:Rostrot!
		desc:Habe 900 RoteAmeisen
		req:900 RoteAmeise
		icon:iconsb[11,19]
*BHRoteAmeise21
		name:Oxidrot!
		desc:Habe 950 RoteAmeisen
		req:950 RoteAmeise
		icon:iconsb[11,20]
		
//7

*BHGrKaefer1
		name:Buntkäfer
		desc:Habe einen GroßenKäfer
		req:1 GrosserKaefer
		icon:iconsb[12,0]
*BHGrKaefer2
		name:Sackkäfer
		desc:Habe 19 GroßeKäfer
		req:19 GrosserKaefer
		icon:iconsb[12,1]
*BHGrKaefer3
		name:Blattkäfer
		desc:Habe 50 GroßeKäfer
		req:50 GrosserKaefer
		icon:iconsb[12,2]
*BHGrKaefer4
		name:Spitzmausrüssler
		desc:Habe 100 GroßeKäfer
		req:100 GrosserKaefer
		icon:iconsb[12,3]
*BHGrKaefer5
		name:Bienenwolf
		desc:Habe 150 GroßeKäfer
		req:150 GrosserKaefer
		icon:iconsb[12,4]
*BHGrKaefer6
		name:Blaubock
		desc:Habe 200 GroßeKäfer
		req:200 GrosserKaefer
		icon:iconsb[12,5]
*BHGrKaefer7
		name:Schnellläufer
		desc:Habe 250 GroßeKäfer
		req:250 GrosserKaefer
		icon:iconsb[12,6]
*BHGrKaefer8
		name:Waldlaufkäfer
		desc:Habe 300 GroßeKäfer
		req:300 GrosserKaefer
		icon:iconsb[12,7]
*BHGrKaefer9
		name:Halsbock
		desc:Habe 350 GroßeKäfer
		req:350 GrosserKaefer
		icon:iconsb[12,8]
*BHGrKaefer10
		name:Prachtkäfer
		desc:Habe 400 GroßeKäfer
		req:400 GrosserKaefer
		icon:iconsb[12,9]
*BHGrKaefer11
		name:Weichkäfer
		desc:Habe 450 GroßeKäfer
		req:450 GrosserKaefer
		icon:iconsb[12,10]
*BHGrKaefer12
		name:Nagekäfer
		desc:Habe 500 GroßeKäfer
		req:500 GrosserKaefer
		icon:iconsb[12,11]
*BHGrKaefer13
		name:Blütenbock
		desc:Habe 550 GroßeKäfer
		req:550 GrosserKaefer
		icon:iconsb[12,12]
*BHGrKaefer14
		name:Schneckenhauskäfer
		desc:Habe 600 GroßeKäfer
		req:600 GrosserKaefer
		icon:iconsb[12,13]
*BHGrKaefer15
		name:Eichelbohrer
		desc:Habe 650 GroßeKäfer
		req:650 GrosserKaefer
		icon:iconsb[12,14]
*BHGrKaefer16
		name:Glanzkäfer
		desc:Habe 700 GroßeKäfer
		req:700 GrosserKaefer
		icon:iconsb[12,15]
*BHGrKaefer17
		name:Großer Rosenkäfer
		desc:Habe 750 GroßeKäfer
		req:750 GrosserKaefer
		icon:iconsb[12,16]
*BHGrKaefer18
		name:Schildkäfer
		desc:Habe 800 GroßeKäfer
		req:800 GrosserKaefer
		icon:iconsb[12,17]
*BHGrKaefer19
		name:Kugelkäfer
		desc:Habe 850 GroßeKäfer
		req:850 GrosserKaefer
		icon:iconsb[12,18]
*BHGrKaefer20
		name:Körnerbock
		desc:Habe 900 GroßeKäfer
		req:900 GrosserKaefer
		icon:iconsb[12,19]
*BHGrKaefer21
		name:Fruchtstecher
		desc:Habe 950 GroßeKäfer
		req:950 GrosserKaefer
		icon:iconsb[12,20]
		
//8

*BHSchmetterling1
		name:Zipfelfalter
		desc:Habe einen Schmetterling
		req:1 Schmetterling
		icon:iconsb[13,0]
*BHSchmetterling2
		name:Feuerfalter
		desc:Habe 19 Schmetterlinge
		req:19 Schmetterling
		icon:iconsb[13,1]
*BHSchmetterling3
		name:Bläuling
		desc:Habe 50 Schmetterlinge
		req:50 Schmetterling
		icon:iconsb[13,2]
*BHSchmetterling4
		name:Schwarzfleckiger Schmetterling
		desc:Habe 100 Schmetterlinge
		req:100 Schmetterling
		icon:iconsb[13,3]
*BHSchmetterling5
		name:Kreuzenzian Schmetterling
		desc:Habe 150 Schmetterlinge
		req:150 Schmetterling
		icon:iconsb[13,4]
*BHSchmetterling6
		name:Storchenschnabelfalter
		desc:Habe 200 Schmetterlinge
		req:200 Schmetterling
		icon:iconsb[13,5]
*BHSchmetterling7
		name:Himmelblauer Bläuling
		desc:Habe 250 Schmetterlinge
		req:250 Schmetterling
		icon:iconsb[13,6]
*BHSchmetterling8
		name:Mauerfuchs
		desc:Habe 300 Schmetterlinge
		req:300 Schmetterling
		icon:iconsb[13,7]
*BHSchmetterling9
		name:Eismohrenfalter
		desc:Habe 350 Schmetterlinge
		req:350 Schmetterling
		icon:iconsb[13,8]
*BHSchmetterling10
		name:Gletscherfalter
		desc:Habe 400 Schmetterlinge
		req:400 Schmetterling
		icon:iconsb[13,9]
*BHSchmetterling11
		name:Kleiner Mohrenfalter
		desc:Habe 450 Schmetterlinge
		req:450 Schmetterling
		icon:iconsb[13,10]
*BHSchmetterling12
		name:Landkärtchen
		desc:Habe 500 Schmetterlinge
		req:500 Schmetterling
		icon:iconsb[13,11]
*BHSchmetterling13
		name:Roter Schneckenfalter
		desc:Habe 550 Schmetterlinge
		req:550 Schmetterling
		icon:iconsb[13,12]
*BHSchmetterling14
		name:Silberfleckfalter
		desc:Habe 600 Schmetterlinge
		req:600 Schmetterling
		icon:iconsb[13,13]
*BHSchmetterling15
		name:Bündner Schneckenfalter
		desc:Habe 650 Schmetterlinge
		req:650 Schmetterling
		icon:iconsb[13,14]
*BHSchmetterling16
		name:Tintenfleckfalter
		desc:Habe 700 Schmetterlinge
		req:700 Schmetterling
		icon:iconsb[13,15]
*BHSchmetterling17
		name:Hochmoorgelbling
		desc:Habe 750 Schmetterlinge
		req:750 Schmetterling
		icon:iconsb[13,16]
*BHSchmetterling18
		name:Alpengelbling
		desc:Habe 800 Schmetterlinge
		req:800 Schmetterling
		icon:iconsb[13,17]
*BHSchmetterling19
		name:Grünaderweißling
		desc:Habe 850 Schmetterlinge
		req:850 Schmetterling
		icon:iconsb[13,18]
*BHSchmetterling20
		name:Segelfalter
		desc:Habe 900 Schmetterlinge
		req:900 Schmetterling
		icon:iconsb[13,19]
*BHSchmetterling21
		name:Schwarzer Apollo
		desc:Habe 950 Schmetterlinge
		req:950 Schmetterling
		icon:iconsb[13,20]

//9

*BHSchabe1
		name:Kleine Schaben
		desc:Habe eine Schabe
		req:1 Schabe
		icon:iconsb[14,0]
*BHSchabe2
		name:Große Schaben
		desc:Habe 19 Schaben
		req:19 Schabe
		icon:iconsb[14,1]
*BHSchabe3
		name:Viele Schaben
		desc:Habe 50 Schaben
		req:50 Schabe
		icon:iconsb[14,2]
*BHSchabe4
		name:Ein Paar Schaben
		desc:Habe 100 Schaben
		req:100 Schabe
		icon:iconsb[14,3]
*BHSchabe5
		name:Ein Haufen Schaben
		desc:Habe 150 Schaben
		req:150 Schabe
		icon:iconsb[14,4]
*BHSchabe6
		name:Schabenreich
		desc:Habe 200 Schaben
		req:200 Schabe
		icon:iconsb[14,5]
*BHSchabe7
		name:Schabenberg
		desc:Habe 250 Schaben
		req:250 Schabe
		icon:iconsb[14,6]
*BHSchabe8
		name:Schabenknäul
		desc:Habe 300 Schaben
		req:300 Schabe
		icon:iconsb[14,7]
*BHSchabe9
		name:Schabenauto
		desc:Habe 350 Schaben
		req:350 Schabe
		icon:iconsb[14,8]
*BHSchabe10
		name:Schabenbus
		desc:Habe 400 Schaben
		req:400 Schabe
		icon:iconsb[14,9]
*BHSchabe11
		name:Schabenzug
		desc:Habe 450 Schaben
		req:450 Schabe
		icon:iconsb[14,10]
*BHSchabe12
		name:Schabenumzug
		desc:Habe 500 Schaben
		req:500 Schabe
		icon:iconsb[14,11]
*BHSchabe13
		name:Schabenwanderung
		desc:Habe 550 Schaben
		req:550 Schabe
		icon:iconsb[14,12]
*BHSchabe14
		name:Schabenstraße
		desc:Habe 600 Schaben
		req:600 Schabe
		icon:iconsb[14,13]
*BHSchabe15
		name:Schabentümpel
		desc:Habe 650 Schaben
		req:650 Schabe
		icon:iconsb[14,14]
*BHSchabe16
		name:Schabenteich
		desc:Habe 700 Schaben
		req:700 Schabe
		icon:iconsb[14,15]
*BHSchabe17
		name:Schabensee
		desc:Habe 750 Schaben
		req:750 Schabe
		icon:iconsb[14,16]
*BHSchabe18
		name:Schabenmeer
		desc:Habe 800 Schaben
		req:800 Schabe
		icon:iconsb[14,17]
*BHSchabe19
		name:Schabenozean
		desc:Habe 850 Schaben
		req:850 Schabe
		icon:iconsb[14,18]
*BHSchabe20
		name:Schabenmasse
		desc:Habe 900 Schaben
		req:900 Schabe
		icon:iconsb[14,19]
*BHSchabe21
		name:Schabend!
		desc:Habe 950 Schaben
		req:950 Schabe
		icon:iconsb[14,20]
//10

*BHSkorpion1
		name:Rotbrauner Kaiserskorpion 
		desc:Habe einen Skorpion
		req:1 Skorpion
		icon:iconsb[15,0]
*BHSkorpion2
		name:Smith's Kaiserskorpion 
		desc:Habe 19 Skorpione
		req:19 Skorpion
		icon:iconsb[15,1]
*BHSkorpion3
		name:Gregory's Kaiserkorpion 
		desc:Habe 50 Skorpione
		req:50 Skorpion
		icon:iconsb[15,2]
*BHSkorpion4
		name:Wandernder Kaiserskorpion 
		desc:Habe 100 Skorpione
		req:100 Skorpion
		icon:iconsb[15,3]
*BHSkorpion5
		name:Blauer Waldskorpion 
		desc:Habe 150 Skorpione
		req:150 Skorpion
		icon:iconsb[15,4]
*BHSkorpion6
		name:Bunter Waldskorpion 
		desc:Habe 200 Skorpione
		req:200 Skorpion
		icon:iconsb[15,5]
*BHSkorpion7
		name:Indischer Waldskorpion 
		desc:Habe 250 Skorpione
		req:250 Skorpion
		icon:iconsb[15,6]
*BHSkorpion8
		name:Laos-Waldskorpion 
		desc:Habe 300 Skorpione
		req:300 Skorpion
		icon:iconsb[15,7]
*BHSkorpion9
		name:Zweifarbiger Rindenskorpion 
		desc:Habe 350 Skorpione
		req:350 Skorpion
		icon:iconsb[15,8]
*BHSkorpion10
		name:Arizona-Rindenskorpion 
		desc:Habe 400 Skorpione
		req:400 Skorpion
		icon:iconsb[15,9]
*BHSkorpion11
		name:Dunkler Honduras-Rindenskorpion 
		desc:Habe 450 Skorpione
		req:450 Skorpion
		icon:iconsb[15,10]
*BHSkorpion12
		name:Baumskorpion 
		desc:Habe 500 Skorpione
		req:500 Skorpion
		icon:iconsb[15,11]
*BHSkorpion13
		name:Zwergdickschwanzskorpion 
		desc:Habe 550 Skorpione
		req:550 Skorpion
		icon:iconsb[15,12]
*BHSkorpion14
		name:Großer Felsskorpion
		desc:Habe 600 Skorpione
		req:600 Skorpion
		icon:iconsb[15,13]
*BHSkorpion15
		name:Skorpionpaar
		desc:Habe 650 Skorpione
		req:650 Skorpion
		icon:iconsb[15,14]
*BHSkorpion16
		name:Skorpionansammlung
		desc:Habe 700 Skorpione
		req:700 Skorpion
		icon:iconsb[15,15]
*BHSkorpion17
		name:Skorpionssammlung
		desc:Habe 750 Skorpione
		req:750 Skorpion
		icon:iconsb[15,16]
*BHSkorpion18
		name:Skorpionsversammlung
		desc:Habe 800 Skorpione
		req:800 Skorpion
		icon:iconsb[15,17]
*BHSkorpion19
		name:Skorpiontreffen
		desc:Habe 850 Skorpione
		req:850 Skorpion
		icon:iconsb[15,18]
*BHSkorpion20
		name:Skorpionsitzung
		desc:Habe 900 Skorpione
		req:900 Skorpion
		icon:iconsb[15,19]
*BHSkorpion21
		name:Skorpionmeeting
		desc:Habe 950 Skorpione
		req:950 Skorpion
		icon:iconsb[15,20]

//11

*BMoskito1
		name:Ein Stecher!
		desc:Habe einen Moskito
		req:1 Moskito
		icon:iconsb[16,0]
*BMoskito2
		name:Mehr Stecher!
		desc:Habe 19 Moskitos
		req:19 Moskito
		icon:iconsb[16,1]
*BMoskito3
		name:Oft Gestochen!
		desc:Habe 50 Moskitos
		req:50 Moskito
		icon:iconsb[16,2]
*BMoskito4
		name:Blutsauger
		desc:Habe 100 Moskitos
		req:100 Moskito
		icon:iconsb[16,3]
*BMoskito5
		name:Blutarmut
		desc:Habe 150 Moskitos
		req:150 Moskito
		icon:iconsb[16,4]
*BMoskito6
		name:Blutverlust
		desc:Habe 200 Moskitos
		req:200 Moskito
		icon:iconsb[16,5]
*BMoskito7
		name:Es Juckt!
		desc:Habe 250 Moskitos
		req:250 Moskito
		icon:iconsb[16,6]
*BMoskito8
		name:Mückenbiss
		desc:Habe 300 Moskitos
		req:300 Moskito
		icon:iconsb[16,7]
*BMoskito9
		name:Blutbeutel
		desc:Habe 350 Moskitos
		req:350 Moskito
		icon:iconsb[16,8]
*BMoskito10
		name:Moskitoparty
		desc:Habe 400 Moskitos
		req:400 Moskito
		icon:iconsb[16,9]
*BMoskito11
		name:Moskitoschwarm
		desc:Habe 450 Moskitos
		req:450 Moskito
		icon:iconsb[16,10]
*BMoskito12
		name:Moskitobündnis
		desc:Habe 500 Moskitos
		req:500 Moskito
		icon:iconsb[16,11]
*BMoskito13
		name:Moskitouniversität
		desc:Habe 550 Moskitos
		req:550 Moskito
		icon:iconsb[16,12]
*BMoskito14
		name:Moskitohochschule
		desc:Habe 600 Moskitos
		req:600 Moskito
		icon:iconsb[16,13]
*BMoskito15
		name:Moskitogymnasium
		desc:Habe 650 Moskitos
		req:650 Moskito
		icon:iconsb[16,14]
*BMoskito16
		name:Moskitoflieger
		desc:Habe 700 Moskitos
		req:700 Moskito
		icon:iconsb[16,15]
*BMoskito17
		name:Moskitoüberflieger
		desc:Habe 750 Moskitos
		req:750 Moskito
		icon:iconsb[16,16]
*BMoskito18
		name:Moskitositzung
		desc:Habe 800 Moskitos
		req:800 Moskito
		icon:iconsb[16,17]
*BMoskito19
		name:Moskitoverband
		desc:Habe 850 Moskitos
		req:850 Moskito
		icon:iconsb[16,18]
*BMoskito20
		name:Moskitovereinigung
		desc:Habe 900 Moskitos
		req:900 Moskito
		icon:iconsb[16,19]
*BMoskito21
		name:Moskitoregion
		desc:Habe 950 Moskitos
		req:950 Moskito
		icon:iconsb[16,20]
				
		
// Baumateial Achievements -------------------------


//1

*BHGras1
		name:Ein Gras
		desc:Habe eine Gras
		req:1 Gras
		icon:iconsa[15,0]
*BHGras2
		name:Zwei Gras
		desc:Habe 19 Gräser
		req:19 Gras
		icon:iconsa[15,1]
*BHGras3
		name:Viel Gras
		desc:Habe 50 Gräser
		req:50 Gras
		icon:iconsa[15,2]
*BHGras4
		name:Gräser
		desc:Habe 100 Gräser
		req:100 Gras
		icon:iconsa[15,3]
*BHGras5
		name:Rasen
		desc:Habe 150 Gräser
		req:150 Gras
		icon:iconsa[15,4]
*BHGras6
		name:Rollrasen
		desc:Habe 200 Gräser
		req:200 Gras
		icon:iconsa[15,5]
*BHGras7
		name:Wiese
		desc:Habe 250 Gräser
		req:250 Gras
		icon:iconsa[15,6]
*BHGras8
		name:Weide
		desc:Habe 300 Gräser
		req:300 Gras
		icon:iconsa[15,7]
*BHGras9
		name:Äsung
		desc:Habe 350 Gräser
		req:350 Gras
		icon:iconsa[15,8]
*BHGras10
		name:Fusballfeld
		desc:Habe 400 Gräser
		req:400 Gras
		icon:iconsa[15,9]
*BHGras11
		name:Golfplatz
		desc:Habe 450 Gräser
		req:450 Gras
		icon:iconsa[15,10]
*BHGras12
		name:Springplatz
		desc:Habe 500 Gräser
		req:500 Gras
		icon:iconsa[15,11]
*BHGras13
		name:Vielseitgkeitsgelände
		desc:Habe 550 Gräser
		req:550 Gras
		icon:iconsa[15,12]
*BHGras14
		name:
		desc:Habe 600 Gräser
		req:600 Gras
		icon:iconsa[15,13]
*BHGras15
		name:Park
		desc:Habe 650 Gräser
		req:650 Gras
		icon:iconsa[15,14]
*BHGras16
		name:Parkanlage
		desc:Habe 700 Gräser
		req:700 Gras
		icon:iconsa[15,15]		
*BHGras17
		name:Garten
		desc:Habe 750 Gräser
		req:750 Gras
		icon:iconsa[15,16]
*BHGras18
		name:Blumengarten
		desc:Habe 800 Gräser
		req:800 Gras
		icon:iconsa[15,17]
*BHGras19
		name:Rasenmäher
		desc:Habe 850 Gräser
		req:850 Gras
		icon:iconsa[15,18]
*BHGras20
		name:Sichel
		desc:Habe 900 Gräser
		req:900 Gras
		icon:iconsa[15,19]
*BHGras21
		name:Rasentrimmer
		desc:Habe 950 Gräser
		req:950 Gras
		icon:iconsa[15,20]
		
//2

*BHAst1
		name:Astreich
		desc:Habe einen Ast
		req:1 Ast
		icon:iconsa[16,0]
*BHAst2
		name:Astgabelung
		desc:Habe 19 Äste
		req:19 Ast
		icon:iconsa[16,1]
*BHAst3
		name:Ästeln
		desc:Habe 50 Äste
		req:50 Ast
		icon:iconsa[16,2]
*BHAst4
		name:Ästetik
		desc:Habe 100 Äste
		req:100 Ast
		icon:iconsa[16,3]
*BHAst5
		name:Astieren
		desc:Habe 150 Äste
		req:150 Ast
		icon:iconsa[16,4]
*BHAst6
		name:Astung
		desc:Habe 200 Äste
		req:200 Ast
		icon:iconsa[16,5]
*BHAst7
		name:Astloch
		desc:Habe 250 Äste
		req:250 Ast
		icon:iconsa[16,6]
*BHAst8
		name:Zweiglinge
		desc:Habe 300 Äste
		req:300 Ast
		icon:iconsa[16,7]
*BHAst9
		name:Ästig
		desc:Habe 350 Äste
		req:350 Ast
		icon:iconsa[16,8]
*BHAst10
		name:Ästweg
		desc:Habe 400 Äste
		req:400 Ast
		icon:iconsa[16,9]
*BHAst11
		name:Ästroute
		desc:Habe 450 Äste
		req:450 Ast
		icon:iconsa[16,10]
*BHAst12
		name:Ästgut
		desc:Habe 500 Äste
		req:500 Ast
		icon:iconsa[16,11]
*BHAst13
		name:Ästadium
		desc:Habe 550 Äste
		req:550 Ast
		icon:iconsa[16,12]
*BHAst14
		name:Ästtag
		desc:Habe 600 Äste
		req:600 Ast
		icon:iconsa[16,13]
*BHAst15
		name:Ästlung
		desc:Habe 650 Äste
		req:650 Ast
		icon:iconsa[16,14]
*BHAst16
		name:Astose
		desc:Habe 700 Äste
		req:700 Ast
		icon:iconsa[16,15]		
*BHAst17
		name:Astille
		desc:Habe 750 Äste
		req:750 Ast
		icon:iconsa[16,16]
*BHAst18
		name:Astope
		desc:Habe 800 Äste
		req:800 Ast
		icon:iconsa[16,17]
*BHAst19
		name:Astweich
		desc:Habe 850 Äste
		req:850 Ast
		icon:iconsa[16,18]
*BHAst20
		name:Astgurt
		desc:Habe 900 Äste
		req:900 Ast
		icon:iconsa[16,19]
*BHAst21
		name:Stamm!
		desc:Habe 950 Äste
		req:950 Ast
		icon:iconsa[16,20]

//3

*BHWurzel1
		name:Tiefwurzler
		desc:Habe eine Wurzel
		req:1 Wurzel
		icon:iconsa[17,0]
*BHWurzel2
		name:Flachwurzler
		desc:Habe 19 Wurzeln
		req:19 Wurzel
		icon:iconsa[17,1]
*BHWurzel3
		name:Herzwurzler
		desc:Habe 50 Wurzeln
		req:50 Wurzel
		icon:iconsa[17,2]
*BHWurzel4
		name:Wurzelreich
		desc:Habe 100 Wurzeln
		req:100 Wurzel
		icon:iconsa[17,3]
*BHWurzel5
		name:Wurzelig 
		desc:Habe 150 Wurzeln
		req:150 Wurzel
		icon:iconsa[17,4]
*BHWurzel6
		name:Kleine Wurzel
		desc:Habe 200 Wurzeln
		req:200 Wurzel
		icon:iconsa[17,5]
*BHWurzel7
		name:Schwache Wurzel
		desc:Habe 250 Wurzeln
		req:250 Wurzel
		icon:iconsa[17,6]
*BHWurzel8
		name:Dünne Wurzel
		desc:Habe 300 Wurzeln
		req:300 Wurzel
		icon:iconsa[17,7]
*BHWurzel9
		name:Dicke Wurzel
		desc:Habe 350 Wurzeln
		req:350 Wurzel
		icon:iconsa[17,8]
*BHWurzel10
		name:Harte Wurzel
		desc:Habe 400 Wurzeln
		req:400 Wurzel
		icon:iconsa[17,9]
*BHWurzel11
		name:Große Wurzel
		desc:Habe 450 Wurzeln
		req:450 Wurzel
		icon:iconsa[17,10]
*BHWurzel12
		name:Lange Wurzel
		desc:Habe 500 Wurzeln
		req:500 Wurzel
		icon:iconsa[17,11]
*BHWurzel13
		name:Verzweigte Wurzel
		desc:Habe 550 Wurzeln
		req:550 Wurzel
		icon:iconsa[17,12]
*BHWurzel14
		name:Dunkle Wurzel
		desc:Habe 600 Wurzeln
		req:600 Wurzel
		icon:iconsa[17,13]
*BHWurzel15
		name:Helle Wurzel
		desc:Habe 650 Wurzeln
		req:650 Wurzel
		icon:iconsa[17,14]
*BHWurzel16
		name:BaumWurzel
		desc:Habe 700 Wurzeln
		req:700 Wurzel
		icon:iconsa[17,15]
*BHWurzel17
		name:GrasWurzel
		desc:Habe 750 Wurzeln
		req:750 Wurzel
		icon:iconsa[17,16]
*BHWurzel18
		name:StrauchWurzel
		desc:Habe 800 Wurzeln
		req:800 Wurzel
		icon:iconsa[17,17]
*BHWurzel19
		name:BlumenWurzel
		desc:Habe 850 Wurzeln
		req:850 Wurzel
		icon:iconsa[17,18]
*BHWurzel20
		name:KaktusWurzel
		desc:Habe 900 Wurzeln
		req:900 Wurzel
		icon:iconsa[17,19]
*BHWurzel21
		name:Kartoffel!
		desc:Habe 950 Wurzeln
		req:950 Wurzel
		icon:iconsa[17,20]

//4

*BHStein1
		name:Stone
		desc:Habe einen Stein
		req:1 Stein
		icon:iconsa[18,0]
*BHStein2
		name:Stono
		desc:Habe 19 Steine
		req:19 Stein
		icon:iconsa[18,1]
*BHStein3
		name:Kivi
		desc:Habe 50 Steine
		req:50 Stein
		icon:iconsa[18,2]
*BHStein4
		name:Bato
		desc:Habe 100 Steine
		req:100 Stein
		icon:iconsa[18,3]
*BHStein5
		name:Pierre
		desc:Habe 150 Steine
		req:150 Stein
		icon:iconsa[18,4]
*BHStein6
		name:Pedra
		desc:Habe 200 Steine
		req:200 Stein
		icon:iconsa[18,5]
*BHStein7
		name:Stien
		desc:Habe 250 Steine
		req:250 Stein
		icon:iconsa[18,6]
*BHStein8
		name:Kamen
		desc:Habe 300 Steine
		req:300 Stein
		icon:iconsa[18,7]
*BHStein9
		name:Harri
		desc:Habe 350 Steine
		req:350 Stein
		icon:iconsa[18,8]
*BHStein10
		name:Klip
		desc:Habe 400 Steine
		req:400 Stein
		icon:iconsa[18,9]
*BHStein11
		name:Guri
		desc:Habe 450 Steine
		req:450 Stein
		icon:iconsa[18,10]
*BHStein12
		name:Piatra
		desc:Habe 500 Steine
		req:500 Stein
		icon:iconsa[18,11]
*BHStein13
		name:Cloiche
		desc:Habe 550 Steine
		req:550 Stein
		icon:iconsa[18,12]
*BHStein14
		name:Akmens
		desc:Habe 600 Steine
		req:600 Stein
		icon:iconsa[18,13]
*BHStein15
		name:Ibwe
		desc:Habe 650 Steine
		req:650 Stein
		icon:iconsa[18,14]
*BHStein16
		name:Dhagax
		desc:Habe 700 Steine
		req:700 Stein
		icon:iconsa[18,15]
*BHStein17
		name:Batu
		desc:Habe 750 Steine
		req:750 Stein
		icon:iconsa[18,16]
*BHStein18
		name:Kö
		desc:Habe 800 Steine
		req:800 Stein
		icon:iconsa[18,17]
*BHStein19
		name:Tas
		desc:Habe 850 Steine
		req:850 Stein
		icon:iconsa[18,18]
*BHStein20
		name:Nkume
		desc:Habe 900 Steine
		req:900 Stein
		icon:iconsa[18,19]
*BHStein21
		name:Dwayne The Rock Johnson
		desc:Habe 950 Steine
		req:950 Stein
		icon:iconsa[18,20]
		
//5

*BHDreck1
		name:Dreckonia
		desc:Habe Dreck
		req:1 Dreck
		icon:iconsa[19,0]
*BHDreck2
		name:Drerym
		desc:Habe 19 Dreck
		req:19 Dreck
		icon:iconsa[19,1]
*BHDreck3
		name:Drecraft
		desc:Habe 50 Dreck
		req:50 Dreck
		icon:iconsa[19,2]
*BHDreck4
		name:D&D
		desc:Habe 100 Dreck
		req:100 Dreck
		icon:iconsa[19,3]
*BHDreck5
		name:Decktoria
		desc:Habe 150 Dreck
		req:150 Dreck
		icon:iconsa[19,4]
*BHDreck6
		name:Dreckanno
		desc:Habe 200 Dreck
		req:200 Dreck
		icon:iconsa[19,5]
*BHDreck7
		name:Dreshock
		desc:Habe 250 Dreck
		req:250 Dreck
		icon:iconsa[19,6]
*BHDreck8
		name:Dreck to dye
		desc:Habe 300 Dreck
		req:300 Dreck
		icon:iconsa[19,7]
*BHDreck9
		name:Dreckout
		desc:Habe 350 Dreck
		req:350 Dreck
		icon:iconsa[19,8]
*BHDreck10
		name:Drecksfarm
		desc:Habe 400 Dreck
		req:400 Dreck
		icon:iconsa[19,9]
*BHDreck11
		name:Dreck Your Life
		desc:Habe 450 Dreck
		req:450 Dreck
		icon:iconsa[19,10]
*BHDreck12
		name:Dreck Of Thrones
		desc:Habe 500 Dreck
		req:500 Dreck
		icon:iconsa[19,11]
*BHDreck13
		name:Dreckest
		desc:Habe 550 Dreck
		req:550 Dreck
		icon:iconsa[19,12]
*BHDreck14
		name:Dodus
		desc:Habe 600 Dreck
		req:600 Dreck
		icon:iconsa[19,13]
*BHDreck15
		name:Muddy
		desc:Habe 650 Dreck
		req:650 Dreck
		icon:iconsa[19,14]
*BHDreck16
		name:Dreckmark
		desc:Habe 700 Dreck
		req:700 Dreck
		icon:iconsa[19,15]
*BHDreck17
		name:Dreck Is Feudal
		desc:Habe 750 Dreck
		req:750 Dreck
		icon:iconsa[19,16]
*BHDreck18
		name:The Dreck Beginns
		desc:Habe 800 Dreck
		req:800 Dreck
		icon:iconsa[19,17]
*BHDreck19
		name:Dreckolord
		desc:Habe 850 Dreck
		req:850 Dreck
		icon:iconsa[19,18]
*BHDreck20
		name:Of Dreck And Men
		desc:Habe 900 Dreck
		req:900 Dreck
		icon:iconsa[19,19]
*BHDreck21
		name:Serious Dreck
		desc:Habe 950 Dreck
		req:950 Dreck
		icon:iconsa[19,20]
