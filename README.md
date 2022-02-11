# Electric Phin (พิณ)
This is the model for a full sized 3 string electric Phin, a 3 String Thai lute.<br>
Making this instrument required both CNC and 3D printed parts, as well as some hand tools for cleaning things up.<br>

<img src ="https://github.com/caleb221/cnc_electric_phin/blob/main/img/ThaiCompared.jpg" width=300 height=350></img>
<img src ="https://github.com/caleb221/cnc_electric_phin/blob/main/img/soloFinished.jpg" width=200 height=250></img>
<img src="https://github.com/caleb221/cnc_electric_phin/blob/main/img/phinFreeCAD.png" width=200 height=250></img>
<br>
I think you could probably make one using hand tools / a bandsaw / routing table if you wanted to as well!<br>

# Model/CAD
  The model posted here had been created using freeCAD.
  
  The scale length measures at  22'' (558.8mm) and was matches a Phin I had bought in Thailand.
  
  Fret markers were calculated using the <a href="https://www.ekips.org/tools/guitar/fretfind2d/">FretFind2D</a> tool
  
  <img src ="https://github.com/caleb221/cnc_electric_phin/blob/main/img/CAM_body.jpg" width=200 height=200></img>
  <img src ="https://github.com/caleb221/cnc_electric_phin/blob/main/img/thaiComparedCloseup.jpg" width=200 height=200></img>
  
# Machining/CAM
  Feeds for OPEN BUILDS 1010 LEAD<br>
  Material: Poplar wood (technically hardwood, but still pretty soft)<br>
  
  1/4'' fluted downcut (6mm) bit:   20mm/s,  1200mm/min<br>
  1/8'' fluted downcut (~3mm) bit:  18mm/s,  1080mm/min<br>
  0.5mm Ball nose bit: 15mm/s, 900mm/min<br>
  
  <b>BODY:</b><br>
  
  
  Load and Clamp stock (8x3x3'' rectangle board)
  Machine out the inlay if desired<br>
  change bit and then run pickup/neck/electronics pockets<br>
  run the top contour path (this will NOT cut all the way through)<br>
  flip the wood stock<br>
  pocket the electronics back pocket<br>
  finish out the contour from the backside<br>
  remove from machine<br>
  
  sand, stain, do what you want!<br>
  <img src ="https://github.com/caleb221/cnc_electric_phin/blob/main/img/freshCutBODY.jpg" width=200 height=200></img>
  <img src ="https://github.com/caleb221/cnc_electric_phin/blob/main/img/FinishingColoring.jpg" width=200 height=200></img>
  <br><b>Finger Board:</b><br>
    This one requires a bit of patience<br>
    Machine out the inlays<br>
    backfill with epoxy resin and pigment (wait for resin to cure fully before next operation)<br>
    plane out the surface until epoxy overfill and stained parts of wood are even (about 0.5-1.5mm)<br>
    change bit to 0.5mm ball nose and pocket out the fret markers<br>
    take off machine and do the rest of the luthier work on the frets<br>
   <img src ="https://github.com/caleb221/cnc_electric_phin/blob/main/img/fingerBoardNoFret.jpg" width=200 height=200></img>
   <br><b>Neck:</b><br>
     Clamp stock to workplace<br>
     Machine out the headstock<br>
     Machine out the neck contour<br>
     remove stock from machine<br>
     finish out the backside radius by hand (working on fixing this in the future)<br>
    
   
   <img src ="https://github.com/caleb221/cnc_electric_phin/blob/main/img/neckBuilding.jpg" width=200 height=200></img>
    

# Electronics
   <b>Pickups</b><br>
   The pickup bobbins were 3D printed, then neodyium magnets placed in their press-fit spots on the underside.<br>
   #6 iron deck screws were cut to length and placed in the top portion of the bobbin, making good contact with the magnets.<br>
   42 AWG Copper wire was then wrapped around the bobbin until a resistance of about 20K was reached using a multimeter.<br>
   Hot glue was used to "pot" the pickups.<br>
      
      
   <img src ="https://github.com/caleb221/cnc_electric_phin/blob/main/img/pickupsTOPSIDE.jpg" width=200 height=200></img>
   <img src ="https://github.com/caleb221/cnc_electric_phin/blob/main/img/pickupsUNDERSIDE.jpg" width=200 height=200></img>
      
 <br><b>Wiring:</b><br>
 The pickups were wired to a 500K Potentiometer and 1/4'' output jack using the diagram from:<br>
 <a href="https://www.seymourduncan.com/blog/latest-updates/guitar-wiring-102"> Seymour Duncan Wiring Diagram</a>
 <br>
   <img src ="https://github.com/caleb221/cnc_electric_phin/blob/main/img/electronicsOpened.jpg" width=200 height=200></img>
      

# BOM


Materials:<br>
    Wood stock (I used Poplar)<br>
    3x2''     x8'  (back of body, neck, headstock)<br>
    3x1/4''   x2'  (fingerboard)<br>
    1x6''     x1'  (Body front)<br>
    Slim Fretwire<br>
    500K Potentiometer<br>
    42AWG Copper Wire<br>
    20AWG Copper wire<br>
    #6x1' Deck Screws<br>
    1/4'' Standard Audio Input Jack<br>
  
Consumables:<br>
 Epoxy Resin<br>
 Mica Powder<br>
 Keda Wood Dye<br>
 Water based Wood Finish<br>
 Boiled Linseed Oil/Japan Dryer<br>
 Sand Paper<br>
 Safety stuff<br>
