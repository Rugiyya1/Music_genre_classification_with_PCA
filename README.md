# Music_genre_classification_with_PCA								
The dataset consists of information about various music tracks and their characteristics.										


Variable	                      Description
Tempo	                          Beats per minute (BPM) of the track.
Dynamic Range	                  The range between the quietest and loudest parts of a track, typically measured in decibels (dB).
Vocal Presence	                The prominence of vocals in a track.
Percussion                      Strength	 the intensity and presence of percussion instruments in a track, such as drums or cymbals.
String Instrument Detection	    The presence and prominence of string instruments like guitars, violins, or cellos in a track.	
Electronic Element Presence    	The intensity and presence of percussion instruments in a track, such as drums or cymbals.
Rhythm Complexity	              The complexity and variation in a track's rhythm patterns, reflecting the intricacy of its beat and timing.
Drums Influence:               	The drums contribution to the overall sound of a track, focusing on their impact rather than just presence.	
Distorted Guitar	              The extent to which electronic sounds or synthesizers are used in a track.
Metal Frequencies	              The use of distorted guitar sounds, often associated with genres like rock or metal.
Ambient Sound Influence	        The use of ambient sounds in a track, which can add texture and atmospheric elements to the music.
Instrumental Overlaps	          How different instruments interplay and overlap in a track, indicating the complexity of its instrumental arrangement.
Genre                          	The categorized genre of the track.


The data contains null labels therefore these values removed and predicted at the end with chosen model
With PCA classification number of components have been chosen based on minimum 80% variance.
Logistic Regression model has been tarined with original and PCA components and accuracy score has been calculated for both models. 
Finally model with PCA components overperformed that original fetaures and missing genres have been determined. 
