  Geospatial machine learning is used by Microsoft to solve and investigate further into environmentally based world problems. It uses land cover mapping to increase forest coverage on land, which helps inform conservation actions, and used to find areas of riparian buffers to be restored which is important because they prevent pollution from running into and through the water. The application goal is to create an accurate high resolution land cover map, in order to make predictions through the high resolution imagery. 

  Starting at the Chesapeake bay watershed, they began generalizing to the other 98% of the United States. High resolution means 1m land cover labels, and the model was then applied to the rest of the US covering over 8 trillion pixels.

  The Interactive Segmentation Tool: users can click on the map with small square segments and see the land/water predictions through the color coating, and if it’s clearly inaccurate you can clear the square to update/rectify it yourself. The motivation behind it is to allow any user to create land covered data for any purpose of theirs. 

  It uses transfer learning which transitions from the original model, to the semantic segmentation network, and through pixel embedding (where each pixel is fascinatingly made by vector of features) it ends in the linear model(throw away linear model previously had, freeze weights of main network, retrain new linear model for our new task).

  The challenges of Geospatial AI consist of only having access to noisy 30m labels to evaluate the land cover change in an area overtime. 

  One specific project he’s working on, which I took particular interest in is the problem of mapping in poultry barns, monitoring different locations and sizes of poultry barns to track where disease can stem from for conservation scientists. 

  Caleb Robinson ended his talk by emphasizing the fact that you are never done learning, which is something very important to me and I loved concluding the session that way. A student asked him how they should continue learning about Data Science after they are technically done with school, and Caleb replied with a general rule of always seeking new information and never being afraid to say “I actually don’t know much about that”.
