Data can be loaded into R using 
> load(mamm.comm.data)

> y = comm.data$det.data.mamm # detection data (18 dataframes with 120 rows (sites) and 18 columns (surveys)
> n.species = dim(y)[1] # number of species
> n.sites = dim(y)[2] # number of sites
> n.visits = dim(y)[3] #number of surveys

> x = comm.data$site.covs #site covariates

> CC=x[,1] #Canopy cover
> UC=x[,2] #Understory cover
> BA=x[,3] #Basal area
> AC=x[,4] #Absolute cover
> WA=x[,5] #Distance to water
> RO=x[,6] #Distance to grassland
> UR=x[,7] #Pathcost distance to urban area
> PE=x[,8] #Protection effort
> HUM=x[,9] #Count of human detections
> GR=x[,10] #Distance to grassland
> HC=x[,11] #Percent high canopy 
> LAT=x[,12] #Latitude
> FB=x[,13] #Bamboo forest (categorical)
> SE=x[,14] #Wet season (categorical)
