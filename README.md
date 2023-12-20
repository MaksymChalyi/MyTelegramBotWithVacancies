# MyTelegramBotWithVacancies

## Description
This is an educational Telegram bot project implemented using Java Spring Boot. The bot assists users in obtaining information about job vacancies from a CSV file. Additionally, the bot features a "Get Cover Letter" button for users to transition to ChatGPT and receive assistance in crafting cover letters.

## Features
- **Display of Job Vacancies:** The bot reads data from a CSV file, enabling users to search for and view current job vacancies.
  
- **"Get Cover Letter" Button:** A button has been added to allow users to seamlessly transition to ChatGPT and receive recommendations for writing cover letters.

## Usage
1. Launch the application using `mvn spring-boot:run` or compile and use the JAR file.
2. Start a conversation with the bot on Telegram: @YourTelegramBotUsername.
3. Use commands to interact with the bot and browse job vacancies.
4. Utilize the "Get Cover Letter" button to receive cover letter writing recommendations from ChatGPT.

## Technologies
- **Java 17:** The primary programming language.
- **Spring Boot 3.2.0:** Used for creating efficient and flexible web applications based on the Spring Framework.
- **Telegram Bot API:** Facilitates interaction with Telegram through the respective API.
- **ChatGPT Integration:** Integration to obtain recommendations for cover letter writing.

## Dependencies
- **spring-boot-starter-web 3.2.0:** Platform for creating web applications based on the Spring Framework.
- **spring-boot-starter-test 3.2.0:** Set of tools for testing Spring Boot applications.
- **telegrambots 6.8.0:** Library for working with the Telegram Bot API.
- **opencsv 5.7.1:** Library for working with CSV files.
