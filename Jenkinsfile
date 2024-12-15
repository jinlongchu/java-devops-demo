pipeline{
    agent any
    environment {
      hello = "1234"
      word = "446"
    }

//     environment
    stages{
        stage('代码编译'){
            steps{
                mail bcc: '', body: 'ddddd', cc: '', from: '', replyTo: '',
                subject: 'ddd', to: 'jlongc89@gmail.com'
                echo "hello"
                echo "bianyi..."
                echo "{world}"

            }
        }
        stage('代码测试'){
            steps{
                echo "test..."

            }
        }
        stage('代码打包'){
            steps{
                echo "pakaging..."

            }
        }
        stage('代码deploy'){
            steps{
                echo "deploy..."

            }
        }

    }








}