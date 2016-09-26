norm-dev-atlas-test
===================

Test functionality of Atlas and create short form structures

Issues: 
       Atlas structures are massively bloated.
       So far Atlas does not provide a net benefit replacement for the Radio Times xmltv service.
       Following the withdrawal of the the Radio Times xmltv service, there is now no equivalent
       service that can provide the equivalent data in a sufficiently efficient form.
       
Example of Purpose
       Populate program metadata for actors, contributors, crew etc. so that a smart recording schedule can be 
       created to, for example, record any program featuring George McGavin.
       This metadata was present in the Radio Times xmltv data, and is probably present in the Altas data if
       if can be accessed specifically by program name, channel, start time.
       
Project Options:
       Creating real-time attachment between a single program (the current topic) and the metadata so
       that a one-time call can be used to attach metadata such as actors, director etc. and then retain
       the metadata for the life of the program. Downside is channel-hopping will cause multiple calls if
       the program info window is open.
       
       Creating background data gathering for subsets of programs, e.g. Films, TV Series, that populate the 
       metadata in small bursts. This can run in parallel with the above.
       
       
