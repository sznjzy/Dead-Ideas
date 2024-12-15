# Chemical Compound Maker

A database/visualization engine for chemical compounds, mapping steps, reactions, procedures and everything that organic chemistry as a whole lacks.


## Why

Everything at the end of the day, if broken down into its simplest is just a bunch of linked carbons, hydrogens and what not. [Neil Red](https://www.youtube.com/nilered) is a youtuber that embodies these perfectly by doing crazy experiments like [Turning styrofoam into cinnamon candy](https://www.youtube.com/watch?v=zMaTrgUKC1), [Turning plastic gloves into hotsauce](https://www.youtube.com/watch?v=1B3Xi5L6siI) etc. 

But the issue is that the research that goes into this is tremendous and sometimes it doesn't lead to anything. But in the world of chemistry 
using rudimentary reactions like [Wurtz reaction](https://byjus.com/chemistry/wurtz-reaction/) and much more you can create anything. But there 
isn't already a solution that tells you that you need to use that reaction to do it.

We also had questions during JEE prep to convert compound X to compound Y but we just never knew what path to take and honestly google was horrible at doing it.

Hence the idea to create a platform where you just input compound X and compound Y and it will automatically spit out the chain of reactions that you need to perform to reach the ending state.

## How

- A database that houses only reactions with generalized branches that can be applied anywhere
- every reaction is treated like a hashmap with the compound as a key (i feel this way would be most easy)
- [SMILES](https://archive.epa.gov/med/med_archive_03/web/html/smiles.html) notation for input and output of compounds

## Challenges faced

- No real good existing database housing reactions (may be able to prompt engineer chatgpt to make one)
- The reactions might straight up just be wrong because of how wonky chemistry is with its exceptions 
- niche user base

## Good to have features

- Compound visualization/drawing of compounds
- Reaction explanation on what is exactly happening

contributed by [Aditya Jyoti](https://github.com/aditya-jyoti)
