# LinkML
# To say:

CarSpecification is about Car
Car hasPart Tank.
Tank hasProperty TankVolume
CarSpecification has Requirement1, Requirement2,
         TankVolume = TankLength * TankHeight * TankWidth   (litre)
         Requirement1 :    TankVolume > 40   and   TankVolume < 120
         Requirement2 :    fuelConsumption_per_hundredKilometers < 15 
if  Requirement1 && Requirement2 then 
        CarQualified=True 
else 
        CarQualified = False

How can I model this schema in LinkML?
