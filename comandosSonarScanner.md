./gradlew sonarqube \
  -Dsonar.projectKey=OnJava8 \
  -Dsonar.host.url=http
  -Dsonar.login=09a770c63817ad358ac629b95b793b80ec39043f
  
  export PATH=$PATH:/home/ubuntu/environment/sonar/bin
  
  sonar-scanner \
  -Dsonar.projectKey=OnJavaScript \
  -Dsonar.sources=. \
  -Dsonar.host.url=http://localhost:8080 \
  -Dsonar.login=71ceb150a1d16d6d033e927a64a5cc530f59ceeb