pipeline{
    agent none
    stages{
        stage('build'){
            steps{
                script{
                    echo "Hi am from build"
                }
            }
        }
        stage('Test'){
            steps{
                script{
                    echo "Hi am from test"
                }
            }
        }
        stage('deploy'){
            steps{
                script{
                    echo "Hi am from deploy"
                }
            }
        }
    }
}


// pipeline{
//     agent none
//     stages{
//         stage('Build'){
//             steps{
//                 script{
//                     sh """
//                         echo "Hello, this is build !!!"
//                     """
//                 }
//             }
//         }
//         stage('Test'){
//             steps{
//                 script{
//                     sh """
//                         echo "Hello, this is test !!!"
//                     """
//                 }
//             }
//         }
//         stage('Deploy'){
//             steps{
//                 script{
//                     sh """
//                         echo "Hello, this is deploy !!!"
//                     """
//                 }
//             }
//         }
//     }
// }