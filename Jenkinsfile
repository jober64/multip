try {
  node("maven") {
  
    stage("Checkout") {
    echo "Checkout"
    }
  } 
} 
  catch (err) {
    echo "in catch block"
    echo "Caught: ${err}"
    currentBuild.result = 'FAILURE'
    throw err
}
