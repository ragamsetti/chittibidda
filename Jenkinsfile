node {
        stage('config')
        {
    dir ('chitti') {
        writeFile file:'dummy', text:''
                }
         }
        stage('create'){
             dir ('chitti') {
             writeFile file:'chittitalli', text:''
        }         
        }
        stage('addcontent'){
        echo"hai hema how are you" >> chittitalli.txt
        }
}
