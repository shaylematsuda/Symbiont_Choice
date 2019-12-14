# Symbiont_Choice
Symbiont choice infection experiment (AIMS)


Metadata:
Plate: ddPCR plate number
Well: 96 well plate location 
Sample: code, disregard
Day: Day the sample was collected after infection, NAs for Copy Number and CONTROLS
Temp: Temperature treatment
Symbiont: Clade of symbiont infected with
Pot: tank replicate (3/infection/temp)
Replicate: pot replicate # (3 pots/infection/temp)
Box: DNA extraction box #
Number: DNA extraction number (corresponds to DNA box)
Primer: Primer used for ddPCR amplification
Info: Sample assay type: CopyNumber=for copy number assay, CONTROL:for testing for amplification of aposymbiotic larvae and for single-infection larvace infected with other clades than the target primer, C1= C1 single infection, D1= D1 single infection, F1=F1 single infection, G3=G3 single infection, ALL: multi-infection with C1, D1, F1, G3
ALL.number: Each larvae that was multi-infection is assigned a unique number
ul.DNA: amount of DNA added in a 25ul PCR
BACKUP.NUMBER: extra ID number for larvae that had been frozen as backup samples

ddPCR output: (only things we are interested in)
Well: 96 well plate location - used to bind to metadata per individual plate
Sample: ignore
Target: Primer
Conc.copies.uL.: # copies per uL PCR (20uL rxn)
Supermix: ddPCR supermix assay
Accepted.Droplets: # total droplets 
Positives: positive for marker
Negatives: negative for marker
Threshold1:positive/negative threshold, set in program based on visual assessment (by primer)
