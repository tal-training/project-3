# הנחיות פרוייקט 3

עליכם לממש את הפתרונות לתרגילים הבאים.

### הנחיות כלליות

יש לבצע FORK ל REPO הזה ולהשתמש כדי לנהל את הקוד, כלומר לעשות commit ו push לפתרונות.

יש לבצע לפחות 5 commits לאורך זמן הפיתוח (לא כולם בבת אחת). 

יש לתעד את הפתרונות ב README הזה (לכתוב בקצרה מה עשיתם והנחיות איך בדיוק להריץ).

### תרגיל 1

כתבו REST API פשוט ב FLASK עם נקודות קצה שמקבלות נתונים כ-JSON ומחזירות תשובות המבוססות על הנתונים הניתנים.

ה API צריך לכלול SQLITE DB לשמירת הנתונים.

ה API יכול להיות כל שירות שתרצו. במידה ואין לכם רעיון, אפשר לעשות מחשבון אבל אז הציון המקסימלי עבור התרגיל הוא 30 ולא 50. 

- אפשר לעשות API לפרוייקט 2, כלומר מנהל משימות.

#### הנחיות 
1
- עליכם לכתוב לפחות 4 נקודות קצה לפי מודל CRUD
- כתבו פונקציות בדיקות ב pytest כדי לוודא שה API עובד בצפוי
- בדקו ידנית את ה API בעזרת POSTMAN
- עבודה שלא כוללת בדיקות, או שכוללת בדיקות שנכשלות לא תיבדק.

ניקוד:

50 נקודות עבור רעיון משלכם ל API. 

30 נקודות עבור מחשבון

### תרגיל 2

צרו Docker Image מהפרוייקט והעלו אותו ל docker hub. עדכנו את ה README הזה עם השם של ה image ב docker hub.

עליכם לבדוק שאפשר להריץ את ה container ולהשתמש בו כ API עבור הפרוייקט, כלומר שניתן לבצע בקשות ל .../http://127.0.0.1:5000/api אחרי שעושים docker run ל image.

ניקוד:
50 נקודות

### תרגיל 3 בונוס 20 נקודות

צרו FRONTEND ב REACT או JS שמתחבר ל API שכתבתם בתרגיל 1 ומבצע איתו פעולות. למשל, אם ה API הוא של מחשבון אז ה FRONTEND מאפשר הכנסת שני מספרים ופעולה חשבונית ומציגה את התוצאה שהגיעה מה API.

### בהצלחה :)

    

    
