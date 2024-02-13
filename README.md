# Ex6_A

בחלק זה עשינו בכל פעם שהשחקן יגיע לטווח ראייה של הסייר, הסייר יתחיל לרדוף אחרי השחקן וכל צעד שיעשה יקבל עיכוב של 3 שניות וכשהוא תופס את השחקן שניהם יעלמו.

ע"מ לשחק במשחק [לחץ כאן](https://m-h-a.itch.io/ex6-a)

נשים לב שהשינויים שעשינו זה על הסצנה בתקייה בשם 3-enemies ושם הסטצנה הוא c-patrol.

נראה בהתחלה את החלק שהסייר ממתין 3 שניות בכל צעד שעושה:

כאשר השחקן נכנס לתחום של הסייר אז הסייר ימתין בפונקציה הזאת:

![image](https://github.com/MHA-FinalProject/Ex6_A_Weekly/assets/118104946/482a4135-6362-48ad-b331-c71cf973692a)

לפי הפונקציית wait הזאת:

![image](https://github.com/MHA-FinalProject/Ex6_A_Weekly/assets/118104946/cfb6725d-36cc-45b0-ba74-11630b5de00c)

ואפשר לשנות את הזמן של ההמתנה:

![image](https://github.com/MHA-FinalProject/Ex6_A_Weekly/assets/118104946/f2e4a159-9aad-423f-b875-bf5a25d34208)


נראה עכשיו את הקוד שבו השחקן והסייר נעלמים כאשר הסייר תופס אותם:

עשינו סקריפט חדש לשחקן בשם PlayerDisapper שבו עשינו שכאשר הטאג של הסייר הוא הטאג שבו מתנגשים אז שניהם נעלמים:

![Screenshot 2024-02-13 235136](https://github.com/MHA-FinalProject/Ex6_A_Weekly/assets/118104946/ffedb80b-02f8-4ca6-99d8-97b3a3928ffe)

שהגדרנו פה איזה טאג:

![image](https://github.com/MHA-FinalProject/Ex6_A_Weekly/assets/118104946/4b0cd873-7f2d-409b-87e6-262908876832)


