get_data_types <- function(data){
  dataTypes <- list(names = names(df), types = NULL)
  i <- 1
  for (i in 1:length(names(df))){
    dataTypes$types[[i]] <- typeof(df[[dataTypes$names[[i]]]])
  }
  return(dataTypes)
}
