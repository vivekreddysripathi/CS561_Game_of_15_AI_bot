# CS561_Game_of_15_AI_bot

<img width="1078" alt="Screenshot 2023-03-06 at 3 50 59 PM" src="https://user-images.githubusercontent.com/98629420/223243256-6fdd7e41-7eae-438c-8649-064ba8e5c9a2.png">

<img width="1089" alt="Screenshot 2023-03-06 at 3 51 25 PM" src="https://user-images.githubusercontent.com/98629420/223243306-22818ccb-bc01-4782-af28-fc02fd15af23.png">

<img width="1119" alt="Screenshot 2023-03-06 at 3 55 35 PM" src="https://user-images.githubusercontent.com/98629420/223243855-031b5018-77b9-4412-9cfa-18cab4ad2d2d.png">

<img width="994" alt="Screenshot 2023-03-06 at 3 58 18 PM" src="https://user-images.githubusercontent.com/98629420/223244861-83ac57dd-d49d-4d94-a4f3-0c07bf3f7996.png">

<img width="991" alt="Screenshot 2023-03-06 at 3 58 39 PM" src="https://user-images.githubusercontent.com/98629420/223244906-b6097faf-ab0f-4fbd-86b1-86703c8fad73.png">

<img width="998" alt="Screenshot 2023-03-06 at 3 59 04 PM" src="https://user-images.githubusercontent.com/98629420/223244952-ac4c37a8-61d5-4403-bbaa-7db7f97b4bfe.png">


Instructions to play the game using AI:
1. Run the Main class.
2. AI will ask for input.
3. You can choose either odd or even. If you choose odd choose your number and position and give input as 0 0 0 9 0 0 0 0 0 if you choose 9 at position left center. And you will be fetched with an even number at some position by the AI.
4. If you choose even then give input as 0 0 0 0 0 0 0 0 0. It will automatically provide you with an odd number at certain position. Remember, as this is the very first step, extremely high number of computations will be made so it will take approx 3 min for the result.
5. You will be prompted to give your next choice. Now take the output given byt AI in the last round, choose you number and position, add it to the previous output and now give this combination as input for the next round.
6. Suppose AI is playing odd and returned you 0 9 0 0 0 0 0 0 0, now it is you turn which is even. You might choose 4 at position right bottom. So give the input for the next round as 0 9 0 0 0 0 0 0 4
7. Play until the game ends.
