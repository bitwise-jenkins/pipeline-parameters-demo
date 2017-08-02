pipeline {
  agent any
  parameters {
    booleanParam(name: 'MY_BOOLEAN', defaultValue: false, description: 'Checkbox parameter')
    choice(name: 'a_choice_param', choices: 'one, two, three', description: 'What door do you choose?')
    string(name: 'FuNkYcHiCkEn', defaultValue: 'Dance!', description: 'Do the funky chicken!')
    string(name: 'FuNkYcHiCkEn_b', defaultValue: 'Dance!', description: 'Do the funky chicken!')
  }
  stages {
    stage('Example') {
      steps {
        echo 'Hello World!'
        echo "${params.FuNkYcHiCkEn_b}"
      }
    }
  }
}
