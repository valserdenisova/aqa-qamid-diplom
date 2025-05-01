<h1 align="center"> Процедура запуска автотестов</h1>
</br>

*  **Предусловие** 
    
   * Клонировать репозиторий

   * Запустить **Docker Desktop**.

   * Открыть клонированный проект в **IntelliJ IDEA**.

*  **Для запуска приложения поочередно ввести команды в терминале IntelliJ IDEA**

   * `docker pull mysql/mysql-server:latest`
     
   * `docker-compose up`
     
   * `java -jar artifacts/aqa-shop.jar -port=8080`
     
*  **Для запуска тестов поочередно ввести команды в терминале IntelliJ IDEA**

   * `./gradlew clean test`
     
   * `./gradlew allureServe` 
