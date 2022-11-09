# LinkML
To say: <br/>

CarSpecification is about Car <br/>
Car hasPart Tank. <br/>
Tank hasProperty TankVolume <br/>
CarSpecification has Requirement1, Requirement2, <br/>
         TankVolume = TankLength * TankHeight * TankWidth   (litre) <br/>
         Requirement1 :    TankVolume > 40   and   TankVolume < 120 <br/>
         Requirement2 :    fuelConsumption_per_hundredKilometers < 15 <br/>
if  Requirement1 && Requirement2 then <br/>
        CarQualified=True <br/>
else <br/>
        CarQualified = False<br/>

How can I model this schema in LinkML?<br/>
