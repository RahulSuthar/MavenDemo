#!groovy

parallel (
    "stream 1" : { 
                     node { 
                           echo "binary"                           
                           echo "sleep 20s" 
                           echo "echo hstream1"
                       } 
                   },
    "stream 2" : { 
                     node { 
                           echo "binary"
                           echo "echo hello2"
                           echo "hashtag fail"                                                       
                       } 
                   }
          )
